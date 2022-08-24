# sdl2-msvc-prebuilt
Prebuilt SDL2 libraries for MSVC x64 using Visual Studio 17 2022.

# Command used to generate these libs
cmake -G "Visual Studio 17 2022" -A x64 ../..
cmake --build . --config release
