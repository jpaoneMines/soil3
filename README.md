# soil3
Simple OpenGL 3.0 Image Library

This library is a version of the Simple OpenGL Image Library (SOIL) http://www.lonesock.net/soil.html that compiles against OpenGL 3.0+.  

It depends upon GLEW.


In order to build, change to projects/makefile and edit the makefile.  You must set the INCLUDE_PATH to the location that GLEW is included
on your machine.

After building, copy the libSOIL3.a library to your preferred location and begin linking your projects against SOIL3 instead of SOIL.
