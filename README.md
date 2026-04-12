My personal collections of infamous gears OSMesa program samples
The original one was public domain. If you find any modifications, it will follow the original license.
Other part will be public domain.

The original program was based on OPENGL 1.0/1.1 with the glx X11 extension on X11 Server.
There are two parts of modernization.

1. glx/X11 -> EGL/Wayland
2. OPENGL 1.0 -> OPENGL 3.3 above

Both requires extra dependencies. But the No.2 requires to rewrite the entire program.
Since OPENGL3.3 Forward context is completely different set of API in my mind.
There are already many existed Github code, but I don't see code which don't use any of GLUT/SDL3/GTK4 etc...

