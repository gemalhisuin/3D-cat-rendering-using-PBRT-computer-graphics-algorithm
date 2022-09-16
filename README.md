# 3D-cat-rendering-using-PBRT-computer-graphics-algorithm
The PBRT-based Cat Rendering attempts to process and create a photorealistic cat object model from a 3D model object using a mathematical algorithm, computer program, and physics principles to model light-matter interaction.

The desired result necessitates the most apparent physically-based technique for achieving cat rendering, and the corresponding object is considered render.
The geometry, orientation, background, illumination, and shading details of the cat render model represent the simulated scene. The content of the scene file is then transferred to a rendering program to be interpreted, followed by the creation of a digital object file and, finally, the rendering of the model.


3D source image
![sourcecat](https://user-images.githubusercontent.com/22916069/190535459-82298e6c-4c1c-4b5d-b77b-eef6d4c595b2.jpg)

Materials and Textures

”plastic” material to characterize a specific plastic material, defined specular reflection coefficients, surface roughness value of 0.1 and ”kd” to diffuse surface reflectivity. The ”imagemap” calls the pbrt class ”imageTexture” with source image from a local directory.

Rendered output image
![catrender](https://user-images.githubusercontent.com/22916069/190535774-71bfa686-e548-4914-b6a9-d4b7c26fbf5b.png)
