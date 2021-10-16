****************
* Intro to WebGL
* CS 464
* 18th Sept, 2021
* Jeff Kahn
**************** 

# PROJECT OVERVIEW:

This WebGL project introduced several WebGL features such as shader, gemoetry, rotation and texture manipulation.


## INCLUDED FILES:

 * README.md - This file
 * rotate_y.html - Demonstrates rotation along y-axis 
 * shader_example.html - Changes shader to use RBG color with lighting
 * shape.html - Changes geometry from cube to rectoid
 * texture_example.html - Uses stone texture instead of box texture
 * texture1.png - Screenshot of different texture
 * texture2.png - Screenshot of different texture
 * texture3.png - Screenshot of different texture
 * shaderchange1.png - Screenshot of shader change
 * shaderchange2.png - Screenshot of shader change
 * shaderchange3.png - Screenshot of shader change



## PROJECT DESIGN NOTES:
The initial difficulty upon starting this assignment was understanding the code. Approximately 400 lines of code to draw a single cube on a webpage meant that a lot of the code was defining WebGL and javascript functions and dependencies. After an initial inspection, it became easy enough to find where the code needed to be changed in order to modify the animation, vertices, textures and shader. Of these, both the texture images and rotation were the easiest and most self-explanitory. However, upon changing the geometry, I initially attempted to draw a sphere. Unfortunately, the examples I found online seemed complex, were written in c and required calculating angles. Due to this difficulty I instead opted to draw a rectoid instead as it simply involved strething the sides of the existing cube geometry. For the lighting, I attempted to implement directional/ambient lighting by following a mozilla lighting tutorial found online. The added code allowed for the lighting of the geometry to be changed, but the orientation in relation to the light source didn't seem to change.

## RESOURCES USED

* [WebGL Mozilla Tutorial]https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial/Lighting_in_WebGL