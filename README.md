# OpenGLScene

An interactive 3D graphics application developed using C++ and modern OpenGL.

![OpenGLScene](OpenGLScene.png)

## Overview

OpenGLScene is a 3D graphics application demonstrating real-time rendering, lighting, shadow mapping, model loading and animation.

The scene features an animated helicopter flying in a circular path, multiple aircraft models, a textured environment and several dynamic light sources. The player can freely navigate the environment using a first-person camera, with a spotlight attached to the camera that illuminates the surroundings as they move.

## Features

- **3D Model Loading and Rendering** – Importing and rendering 3D models using Assimp.
- **Multiple Lighting Types** – Directional lights, point lights and spotlights.
- **Dynamic Camera Spotlight** – A spotlight attached to the camera that follows the player's movement and viewing direction.
- **Shadow Mapping** – Directional and omnidirectional shadow mapping.
- **Omnidirectional Shadows** – Cubemap-based depth mapping for point light shadows.
- **Object Animation** – An animated helicopter following a circular flight path.
- **Interactive Camera** – First-person movement through the 3D environment.
- **Skybox Rendering** – Environmental background rendering.
- **Shader Programming** – GLSL shaders for rendering, lighting and shadow calculations.

## Technologies & Libraries

- **C++** – Application logic and rendering systems.
- **OpenGL** – Real-time graphics rendering.
- **GLEW** – OpenGL extension loading.
- **GLFW** – Window management and input handling.
- **Assimp** – 3D model importing.
- **GLM** – Mathematics library for graphics programming.
- **GLSL** – Vertex and fragment shaders.

## Building & Running

The project uses a Visual Studio solution.

1. Clone or download the repository.
2. Open `OpenGLScene.sln` in Visual Studio.
3. Build the solution.
4. Run the application.

Originally developed using Visual Studio 2015. The project has also been successfully opened, built and run using Visual Studio 2022.

## Controls

| Key | Action |
|---|---|
| W | Move forward |
| S | Move backward |
| A | Move left |
| D | Move right |
| ESC | Close application |

## Project Background

This project was developed as part of my learning journey with C++ and modern OpenGL, following the Udemy course [Computer Graphics with Modern OpenGL](https://www.udemy.com/course/graphics-with-modern-opengl/).

The course provided practical experience with real-time rendering, lighting models, shadow mapping, 3D transformations, model importing and shader programming.

This project represents a practical application of the graphics programming techniques explored during the course.
