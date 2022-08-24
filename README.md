# sdl2-msvc-prebuilt
Prebuilt static and dynamic SDL2 libraries for MSVC x64 using Visual Studio 17 2022.

# CMake commands used to generate these libs

SDL2
	cd <root>/VisualC
	mkdir build
	cd build
	cmake -G "Visual Studio 17 2022" -A x64 ../..
	cmake --build . --config debug
	cmake --build . --config release
