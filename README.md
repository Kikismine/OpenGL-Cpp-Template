# Template for OpenGL programming

## Features:

- Makefile for compiling with all libs
- No struggling with Makefile :D
- src/main.cpp (start main file)
- Libraries: GLFW, Glad, GLM
- Resource folder with default texture (256x256)

## How to add library

1. Download the library
2. Move the library into the 'lib' folder
3. Open Makefile
4. Add into Makefile:
```Makefile
CFLAGS += -Ilib/name-of-the-library/
```
5. If your library isn't *[header]* library then add:
```Makefile
LDFLAGS += lib/name-of-the-library/src/name-of-the-main-file
```
6. You are done 👍

******
*PS: best OpenGL tutorials:*<br>
*https://youtu.be/W3gAzLwfIP0*<br>
*https://learnopengl.com/*<br>

[header]: <https://en.wikipedia.org/wiki/Header-only>
