# OpenGL Sphere Lighting

[![Hits](https://hits.sh/github.com/vmsaif/openGL-sphere-lighting-program.svg?label=Visits&color=100b75)](https://hits.sh/github.com/vmsaif/openGL-sphere-lighting-program/)

This project showcases the lighting capabilities of OpenGL by illuminating a sphere using three distinct light sources. The user can interactively select the color of the light and the material of the sphere, offering a dynamic experience to visualize the effects of different lighting conditions.

## Features

- **Three Light Sources**: Originating from the top left corner, top right corner, and directly behind the viewer.
- **Dynamic Light Colors**: Choose from white, red, blue, or green light for each light source.
- **Material Selection**: Three different surface materials can be applied to the sphere.
- **Interactive Menu**: A right-click menu system for easy selection of lighting elements and materials.
- **Sphere Rendering**: Utilizes the `glutSolidSphere` command for accurate sphere representation.

## Requirements

### This Repository

Clone this repository to your local machine with:

```bash
git clone https://github.com/vmsaif/openGL-sphere-lighting-program
```

### Visual Studio

Ensure you have Visual Studio installed. If not, download it from [Visual Studio Official Website](https://visualstudio.microsoft.com/).

### GLUT Library

This project requires the OpenGL library or `glut.h`. The easiest way to set it up in Visual Studio is as follows:

1. Go to the directory where you cloned the project.
2. Open the `openGL-sphere-lighting-program.sln` file to open the project in Visual Studio.
2. Click on `Project` in the menu bar.
3. Select `Manage NuGet Packages`.
4. Click on the "Browse" tab.
5. Search for "freeglut".
6. Select "nupengl.core" (which includes glut.h) and click `Install`.

## Interactions

- **Right-click**: Activates the menu system.
- **Menu Options**: Allows for the selection of light colors, light sources, and sphere materials.

## Credits

This project was developed using OpenGL's extensive lighting features to provide a realistic and interactive experience for users interested in graphics programming.

