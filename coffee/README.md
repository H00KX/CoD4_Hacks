A multihack for COD4 that includes a wallhack, no-recoil, and internal ui.

The injector was written in C++ and compiled with VS6 but should compile with any modern C++ compiler.

The hack was written in mASM and needs to be linked as a dll. To do this:
```
\masm32\bin\ml /c /coff coffee.asm
\masm32\bin\Link /SUBSYSTEM:WINDOWS /DLL coffee.obj
```

Originally written on 2010/03/10 by attilathedud.

Injector:

![Injector Screenshot](screenshot_i.png?raw=true "Screenshot Injector")

Hack:

![Hack Screenshot](screenshot_h.jpg?raw=true "Screenshot Hack")