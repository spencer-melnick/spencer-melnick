# Spencer Melnick - Software Engineer, Hobbyist Game Developer

## Projects

### [Unreal Engine Realtime Ocean Simulation](https://github.com/spencer-melnick/VoidRoom/tree/OceanSim)

- Custom GPU accelerated inverse fast-fourier transform implementation running on Unreal Engine compute shaders
- Generation of height frequency data using the method as described in [Tessendorf, 2001](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.161.9102&rep=rep1&type=pdf)
- Height, displacement, and foam textures output as `URenderTexture2D`s for easy use in Unreal's material system
- Integration with Unreal's cutting-edge Render Dependency Graph

### [Unity 3D Volumetric Cloud Renderer](https://github.com/spencer-melnick/Chalice)

- Volumetric cloud texture generated based on the techniques used in Guerilla Games' Horizon Zero Dawn
- Post-processing and material surface based volumetric raymarcher
- Custom external plugin for Unity 3D for fast generation of 3D Perlin and Worley noise textures 