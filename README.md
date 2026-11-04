# MG5
## Devlog
### 1
I think "NavMesh" is more useful for games where characters need to find paths and avoid obstacles automatically. For example, in an RPG game, NPCs may need to walk around trees, rocks, and buildings to reach the player. "NavMesh" makes this easier because characters can find a path to their destination. Physics-based movement is better for games that need realistic movement and physical reactions. For example, in "Super Mario", the character needs to jump, fall, and interact with objects. Physics-based movement gives the player more control over these actions.

### 2
The for loop checks every bird in the "_birds" array, starting at index 0 and continuing until it reaches the end of the array. "Vector3.Distance()" calculates the distance between each bird and the player. The if statement checks whether that distance is less than or equal to "_interactDistance". If the condition is true, that bird will run away from the player. Therefore, only the birds within the interaction distance will run away, while the birds outside that distance will not move.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
