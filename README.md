# KK24402 GRAPHICS AND VISUALISATION

This project is for the **Graphics and Visualisation** course (KK24402). It uses **OpenGL** for rendering. Make sure you set up everything properly before running the project!

---

## 🔧 How to Make It Work?

1. **Install OpenGL**
   - On Windows: Download and install **freeglut**, **GLFW**, or use prebuilt OpenGL libraries.
   - On Linux/macOS: Use your package manager (e.g., `sudo apt install freeglut3-dev`).

2. **Install VS Code**
   - Get the purple one from [https://code.visualstudio.com/](https://code.visualstudio.com/).
   - Install C/C++ extensions (by Microsoft) in VS Code.

3. **Copy Required Files**
   - Copy all the necessary OpenGL-related files (`.dll`, `.lib`, headers, etc.) to your working folder.  
     For example:
     ```
     ProjectFolder/
     ├── main.cpp
     ├── opengl/
     │   ├── include/
     │   ├── lib/
     │   └── dlls/
     ```

4. **Set Up Include & Library Paths**
   - Configure your `tasks.json` and `c_cpp_properties.json` in VS Code to point to the OpenGL headers and libraries.
   - Or just use a Makefile/CMake if you’re feeling fancy.

---

## ▶️ How to Run?

- Open the folder in VS Code.
- Make sure your compiler (like MinGW or g++) is installed and working.
- Press `Ctrl + Shift + B` to build.
- Run the `.exe` or `./yourProgram` from terminal.

---

## 💡 Tips

- If you get linker errors, make sure the `.lib` or `.dll` files are correctly linked.
- Use `#include <GL/glut.h>` or whatever your setup requires.
- Some helpful OpenGL examples: [LearnOpenGL](https://learnopengl.com/)

---

Happy coding & may your polygons be smooth ✨  
