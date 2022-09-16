# 3D-cat-rendering-using-PBRT-computer-graphics-algorithm
The PBRT-based Cat Rendering attempts to process and create a photorealistic cat object model from a 3D model object using a mathematical algorithm, computer program, and physics principles to model light-matter interaction.

The desired result necessitates the most apparent physically-based technique for achieving cat rendering, and the corresponding object is considered render.
The geometry, orientation, background, illumination, and shading details of the cat render model represent the simulated scene. The content of the scene file is then transferred to a rendering program to be interpreted, followed by the creation of a digital object file and, finally, the rendering of the model.

3D source image <br />
![sourcecat](https://user-images.githubusercontent.com/22916069/190535459-82298e6c-4c1c-4b5d-b77b-eef6d4c595b2.jpg)

Materials and Textures <br />
”plastic” material to characterize a specific plastic material, defined specular reflection coefficients, surface roughness value of 0.1 and ”kd” to diffuse surface reflectivity. The ”imagemap” calls the pbrt class ”imageTexture” with source image from a local directory.

Defining the lighting of cat scene <br />
The cat scene utilizes pbrt light source vector ’infinite’ with RGB values of 0.6, 0.6, and 1.0 to
produce red , green, and blue light sources for illumination by using InfiniteAreaLight() API.
InfiniteAreaLight() represents a constantly distant light source, potentially reflecting light from all
directions involved in a latitude-length modeling environment mapping.

Setting the translation coordinates <br />
The corresponding value is forwarded to the pbrtTranslate()API call which changes the current
transformation matrix (CTM) by assigning it to the product of the current transformation matrix
(CTM), with translate floating-point numbers, x=0, y=0 and z=-40.

Defining the shape of the cat scene <br />
The TriangleMesh() API describes ’cat render’ shapes with trianglemesh variable and takes the
name of a shape type and a list of parameters to specify shape characteristics. The trianglemesh
for the surface areas is defined in the vertex arrays by an index parameter of length 2 * 3 and an
array integer index of values [0 1 2 3 0] that represents adjustments of the vertices of a triangle.

Rendered output image
![catrender](https://user-images.githubusercontent.com/22916069/190535774-71bfa686-e548-4914-b6a9-d4b7c26fbf5b.png)
