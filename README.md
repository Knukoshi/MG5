# MG5
## Devlog
1. I think it's more advantageous to use a NavMesh when dealing with dynamic terrain and wanting a character to travel to a set destination
   along that terrain. Whereas using physics would be better if you want the character to collide and have physics interactions with other
   characters or the setting. An example for the former would be like how tamed wolves follow the player character in Minecraft. An example
   of the latter would be something like the Sonic games when he's dashing around.
2. The for loop checks the distance each bird in the array is from the player character using the Vector3.Distance call. If the distance is
   less than or equal to the labeled interaction distance, then it will call to the Bird script to make it run away from the player character.
   Only birds that are close enough for the Vector3.Distance call to return a value lower than or equal to the interaction distance float will
   run away.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)