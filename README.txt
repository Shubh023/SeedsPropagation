# VISION - TP Seeds Initial

### **Student :** *PATEL Shubhamkumar at M2 IMA*


This program is meant to take as input two images, with a slight translation in the scene (from right to left) and compute a Disparity Map in order to generate a 3D view of a scene.

## **Build the project** :

#### *Generate an executable binary Fundamental for your distribution* :

- ***``` mkdir build ```***

- ***``` cd build ```***

- ***``` cmake ../CMakeLists.txt -B . ```***

- ***``` make ```***

- ***``` ./Seeds ```***

**PS** : *For my local setup i had to add ```set(OpenGL_GL_PREFERENCE GLVND)``` in the **CMakeLists.txt**. So in case there is problem related to this setting please remove this line and try to build with the same process as above.*

## **Calculating Seeds** :

#### I've added multiple results in the ***Results*** directory with files which show each steps :
- **Computing seeds**
- **Propagating them around the neighbourhood**
- **Generating a 3D view to get some sense of the depth from the scene**
