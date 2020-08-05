# Spencer Melnick - Software Engineer

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

### [Meritocracy Train (Global Game Jam 2019 Entry)](https://github.com/BuiltInParris/The-Meritocracy-Train)

- Fast-paced local multiplayer 2D action game developed in Unity 3D
- Try to repair the train as fast as possible to score points, while stopping your friends from racking up more points. Only the highest scoring players will survive!
- Kinematic platforming controls with simple acceleration, friction, and jump extension

### [Hearth (Global Game Jam 2019 Entry)](https://github.com/spencer-melnick/hearth)

- Simple 2D adventure game developed in the Godot Engine
- Journey into the wilderness to find fuel and fight back the ever encroaching winter
- Atmospheric audio and visual effects

### [Simple Vulkan Renderer](https://github.com/spencer-melnick/simple-render)

- Bare bones example of a functioning Vulkan program
- RAII wrappers around common functions
- CMake build including automatic SPIR-V shader compilation

### [Threshold (Unreal Engine Combat)](https://github.com/spencer-melnick/Threshold)

- Game demonstrating a work-in-progress action RPG combat system
- Takes full advantage of existing Unreal Engine features and gameplay framework
- Clean code that follows Unreal Engine standards

### [spencermelnick.net](https://github.com/spencer-melnick/spencer-melnick.github.io)

- Simple website using only HTML and CSS for my personal portfolio
- Nice clean design, supported on all major mobile and desktop browser

### [RUIN (Robot Frontend Control Software)](https://gitlab.com/templerobotics1718/RUIN)

- Graphical frontend for Temple Robotics' 2018 NASA RMC robot
- Multithreaded control and TCP communication with robot to deliver commands and receive telemetry data with a strict bandwidth limit
- Basic OpenGL renderer with lighting and texture support to render 3D view of autonomous telemetry data (full autonomous control was not finished, so there are only placeholder models currently)
- Detailed control GUI developed using ImGUI
- Cross-platform build support with CMake 

### [Ceph - BeliefCache Integration](https://github.com/spencer-melnick/ceph)

- Implementation of an [experimental caching algorithm](https://www.usenix.org/sites/default/files/conference/protected-files/hotstorage17_slides_ramljak.pdf) into the Ceph distributed filesystem
- Rapid analysis of data in C++ using Ceph thread pools and Boost sparse arrays
- Completed as part of my time as an undergraduate research assistant for Temple University's Computer Science Department
- Submitted for publication in 2019

### [ADNS Robot](https://github.com/spencer-melnick/adns_robot)

- A collection of ROS packages framework for an autonomous robot
- Utilizes a collection of libraries for fiducial image recognition and navigation
- Custom ROS nodes developed in C++ including external plugins for GazeboSim
- Developed for my senior design project at Temple University

### Other/Unfinished Projects

Quite a lot of unfinished projects, too many to list individually.Many of these showcase how my programming skills (particularly in C++) developed over the years, and there are numerous attempts to develop a full game engine.

These have implementations of different low-level memory management algorithms, such as memory stacks and object pools, as well as insertion sorting and an attempt to develop data structures using extra indirection to limit cache-misses on large data loops.

Often times I would abandon these as I had been interested in developing a game engine, quickly realizing that between school and work I simply did not have the time to meet the massive scope required in a full "game engine", before returning with newfound conviction to repeat the process at some later time.
