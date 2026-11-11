# OpenGLScene

![](https://github.com/cjd2207/OpenGLScene/blob/master/OpenGLScene.png)

An independently developed interactive 3D graphics application using C++ and OpenGL.

## Overview

OpenGLScene demonstrates real-time 3D rendering, lighting, model loading and animation within an interactive environment.

The scene features an animated helicopter flying in a circular path, alongside a navigable 3D environment with multiple light sources and a camera-attached spotlight.

### Features

- **3D Model Rendering:** Loading and rendering 3D models using Assimp.
- **Dynamic Lighting:** Multiple light sources illuminating the environment.
- **Camera Spotlight:** A spotlight attached to the camera that moves with the player.
- **Object Animation:** An animated helicopter following a circular flight path.
- **Interactive Camera:** Navigate around the 3D environment using keyboard controls.
- **Skybox:** Background environment rendering.

## Technologies & Libraries

- **C++**
- **OpenGL**
- **GLEW** – OpenGL extension loading.
- **GLFW** – Window management and input handling.
- **Assimp** – 3D model importing.
- **GLM** – Mathematics library for graphics programming.

## Building & Running

1. Open the Visual Studio solution (`.sln`).
2. Build the project using Visual Studio.
3. Run the application.

Originally developed using Visual Studio 2015. Successfully opened and run using Visual Studio 2022.

## Controls

| Key | Action |
|---|---|
| W | Move forward |
| S | Move backward |
| A | Move left |
| D | Move right |
| ESC | Close application |

## Screenshots

![OpenGLScene - Interactive 3D Graphics](Screenshots/OpenGLScene.png)
