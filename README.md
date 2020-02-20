## Welcome to Procedural Island Generation

### The below link is a demonstration of the project
https://darryn-wong.github.io/procedural-island-generation/

### Terrain 
- Uses a perlin map to randomly generate islands

### Trees and Flowers
- They are randomly droped from the air
- The object is destoryed if
  1. the object is hanging
  2. bad angle
  3. on top of other objects
  4. on water
 - To Prevent this from happening
  1. Uses raycast to detect the angle of the terrain
  2. Uses raycast to detect all for sides are landed
  2. Use Layers to detect if its landing on the terrain
 
