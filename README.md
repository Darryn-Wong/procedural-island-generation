## Welcome to Procedural Island Generation

### Demonstration of the project
https://darryn-wong.github.io/procedural-island-generation/

### Terrain 
- Uses a perlin map to randomly generate islands

### Trees and Flowers
- They are randomly droped from the air
- The object is destoryed if
  1. the object is hanging
  2. bad angle
  3. on top of another object
  4. on water
- To Prevent this from happening
  1. Use raycasts to detect the angle of the terrain
  2. Use raycasts to detect if all sides are landed
  3. Use layers to detect if its landing on the terrain
