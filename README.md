# Project setup

1. Follow [this guide](https://rpxomi.github.io/) to set up GLAD
   - don't go beyond OpenGL version 4.1 if on Mac
   - these header files are system dependent
2. Install [GLFW](https://www.glfw.org/)

3. If done correctly, base project structure should be as follows:
   - `opengl_rendering/`
     - `include/`
       - `glad/glad.h`
       - `KHR/khrplatform.h`
     - `lib/libglad.a`
     - `glad.c`
     - `glad.o`
     - `main.cpp`

4. Compile with 
```bash
clang++ -Wall main.cpp -o ./out/test -Llib -lglad -lglfw
```

