## Projects
### [Load Store Analysis Pass](https://github.com/ahmedshakill/load-store-pass)
- An LLVM based compiler pass to find aliasing load store instructions inside a function. Got familiar
with AliasAnalysis passes such as MemoryDependenceAnalysis, MemorySSA.

### [RISC‑V Simulator](https://github.com/ahmedshakill/Sim)
- A RISC‑V simulator written using C++17 following OOP principles. It is able to fetch, decode and execute
load‑store, arithmetic and logical shift, arithmetic operations and conditional branching instructions without pipeline support.

### [Chip8 Emulator for Android](https://github.com/ahmedshakill/Emu8)
- It is an emulator that emulates chip8 platform written in modern C++ using NDK. Also used SDL2
for graphics support. Used an array of std::function to create a table of methods where methods correspond to each opcode.
At runtime opcode from game ROM are read and corresponding method is selected from array and invoked allowing dynamic
dispatch. Games written for chip8 platform can be played and enjoyed in android using this emulator. 

### [Asynchronous Web‑Server and Client](https://github.com/ahmedshakill/TCPServer)
- Asynchronous multi‑threaded Web Server using BOOST ASIO, C++17 and CMake which
serves multiple clients simultaneously. The server compiles and runs c++ code provided over http request and returns the result.
The Web‑Server required using CRTP (Curiously recurring template pattern) where a templated object keeps reference to itself to
increase the life time of itself (scenarios like, socket waiting to serve a client), asynchronous programming, lambda functions and
smart pointers with other language fundamentals. I hosted the server on heroku in a docker container. 

### [Modernization of WinBGIm library](https://github.com/ahmedshakill/WinBGIm-64)
- Improved WinBGIm graphics library targeting GCC 64bit compiler for windows. The last
release build by Borland was around 20 years ago and thus is now incompatible with 64bit MinGW compiler. I gave a new build.
Also integrated this into a project with CMake support which is easily usable and thus helpful for beginners in graphics as it
requires minimal setup.
