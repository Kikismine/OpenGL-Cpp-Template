# Template for OpenGL programming

## Features:

- Makefile for compiling with all libs
- No struggling with Makefile :D
- src/main.cpp (start main file)
- Libraries: GLFW, Glad, GLM
- Resource folder with default texture (256x256)

## How to add GLEW
1. Download *[glew]*
2. Move the glew library to the 'lib' folder
3. Open Makefile
4. Add into Makefile:
```Makefile
CFLAGS += -Ilib/glew/include/GL
lib/glew/lib/libGLEW.a
```
5. Add into Makefile's 'libs:' category:
```Makefile
cd lib/glew && make
```
6. You are done 👍

### Optional:
If you want to add other libraries, you can do the same like with the GLEW lib.

******
*PS: best OpenGL tutorials:*<br>
*https://youtu.be/W3gAzLwfIP0*<br>
*https://learnopengl.com/*<br>

[header]: <https://en.wikipedia.org/wiki/Header-only/>
[glew]: <https://sourceforge.net/projects/glew/>

