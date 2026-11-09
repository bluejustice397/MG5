# MG5
## Devlog
Put your Devlog here.

### MG5 Devlog


1. It is better to use a navmesh in games where the enemy ai needs pathfinding to navigate the environment without getting stuck on the terrain, like Halo or The Last of Us. Navmeshs are also useful in games where you click to move characters like Civilization or Baldur's Gate. The Navmesh defines where players can move on the grid in those games. It is better to use physics based movement when building a player control for games like platformers, or have an emphasis on momentum and physics like Sonic the Hedgehog.


2. In the original statement only one bird would scatter, but after fixing the loop, it iterates starting at 0 and runs for the number of birds in the array. The vector3.distance call is being used to calculate the distance between a bird and the pudu and if that distance is less than or equal to the interact distance then the bird will run away using bird.Runaway which puts it out of the interact distance.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)