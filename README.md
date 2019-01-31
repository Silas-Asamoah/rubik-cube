# Rubik's Cube

This creates the Rubik cube in a 3D dimensional space in the browser using Three.js and WebGL

The individual cubes(cubelets) are manipulated by adding them as children to a parent object which is then rotated. This automatically updates cubelet positions. After each rotation cubelets are removed from the parent and added back to the scene, which requires an explict update of cubelet materials. 


![](https://media.giphy.com/media/13ckNooklW6V9u/giphy.gif)