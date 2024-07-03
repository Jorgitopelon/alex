
<div align="center">
<h1 >🪐Sytem Solar☀️</h1>
<p ><sup><b>Educational project that aims to create an interactive simulation of the solar system. </b></sup></p>
</div>

![poster](https://github.com/Rayo070305/Proyecto_final_pg/blob/main/Documentacion/Imagenes%20referencia/presen.jpg)

# Introduction

The solar system simulator is an interactive educational application developed in Python using the OpenGL and Pygame libraries. This application features a menu of options where users can choose between navigating a solar system simulation and accessing a section with detailed information about each planet. In the solar system simulation, users can move around the entire scene by controlling the camera with the keyboard and mouse.

![posterfinal](https://github.com/Rayo070305/Proyecto_final_pg/blob/main/Documentacion/Imagenes%20referencia/inicio.jpg)

## Screenshots

### Helicopter Mode

![CityTourHelicopter](https://raw.githubusercontent.com/jamesadhitthana/City-Tour/main/Documentation/Screenshots/helimode.png)

### Car Mode

![CityTourCar](https://raw.githubusercontent.com/jamesadhitthana/City-Tour/main/Documentation/Screenshots/carmode.png)

# How it's made

We did this project by forming boxes (cubes), which we placed with a pattern, and then we gave the squares textures to form a building. The shapes of buildings are made by combining several boxes into one. There are four types of structures that we created, and we put the types of buildings randomly.

We use a skybox for the day and night backgrounds, which is a combination of 6 texture images and forms a 3-dimensional cube map. Skybox will change to day or night according to the time we have set. We also added the sun, moon, car, and people using the texture image and removed the fragments of the parts of the texture that we wanted to make transparent. We also use translation and rotation in our texture image to make it move more realistically.

We also utilized the Camera class from learnopengl.com to create a camera perspective of our program.
The animation for the city tour is done by moving the camera location coordinates to make it move like a car or helicopter.We also employed city ambiance sounds and even car and helicopter sounds according to the camera perspective. To run the background music, we use the Windows library and MMSystem and use the PlaySound function, which plays in the background and loops the song until the application is closed.

### Documentation:

- [Documentation](<https://github.com/jamesadhitthana/City-Tour/raw/main/Documentation/City%20Tour%20(Bahasa%20Indonesia)%20-Christopher%20Yefta-James%20Adhitthana.pdf>)

## Built With

- [Pygame](https://www.pygame.org/docs/) - Mixer
- [OpenGL](https://www.opengl.org/) - OpenGL
  - [Math](https://docs.python.org/3/library/math.html) - Math
  - [Numpy](https://numpy.org/) - Numpy
  - [GLM](https://glm.g-truc.net/0.9.9/index.html) - GLM, matrix_transform.hpp, type_ptr.hpp
- [Python](https://docs.python.org/3/) - Python


## Authors

- **Aleman Jorge** - [Jorge](https://github.com/Rayo070305)

* **Salinas Ethan** - [Ethan](https://github.com/Brown001605)

* **Rayo Anthony** - [Rayo](https://github.com/Rayo070305)

* **Mendoza Alejandro** - [Alejandro](https://github.com/aamendoza24)

![CityTourGallery](https://raw.githubusercontent.com/jamesadhitthana/City-Tour/main/Documentation/Screenshots/gallery.png)
