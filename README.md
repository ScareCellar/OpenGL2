# OpenGL Engine (Neumont) — README

Overview
--------
A small C++20 OpenGL-based rendering engine and sample application. The solution uses SDL3 for windowing/input, GLM for math, and RapidJSON for scene/material serialization. Shaders, materials and scenes live in the `Build/Assets` folder so the engine can load them at runtime.

Quick facts
-----------
- Language: C++ (C++20)
- Build environment: Visual Studio 2022
- Key libraries: SDL3, GLM, RapidJSON, OpenGL (project may also include an OpenGL loader such as GLAD/GLEW, depending on local configuration)
- Assets: `Build\Assets` (shaders, materials, scenes, textures, etc.)

Prerequisites
-------------
1. Visual Studio 2022 with Desktop development with C++ workload installed.
2. C++ toolset supporting __C++20__.
3. SDL3 development libraries (include + libs).
4. GLM headers.
5. RapidJSON headers.
6. OpenGL driver on your machine. If the solution requires an OpenGL loader (GLAD/GLEW), ensure that it is available or included in the project.

If you don't have the headers/libraries installed system-wide, point the project include and library paths in Visual Studio to where you placed them.
