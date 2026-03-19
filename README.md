# SDL3 Windows Build

Automated SDL3 DLL build for Windows using GitHub Actions.

## Status

Building SDL3 shared library (DLL) for Windows x64...

## Download

Once the build completes, download the artifacts from the [Actions tab](https://github.com/lopie-source/sdl3-windows-build/actions).

## What's Built

- **SDL3.dll** - Shared library (runtime)
- **SDL3.lib** - Import library (link-time)
- **include/SDL3/** - Header files

## Build Details

- **Platform**: Windows x64
- **Toolchain**: Visual Studio 2022 + CMake
- **SDL3 Version**: main branch (latest)
- **Build Type**: Release (Shared Library)

## Repository

SDL3 source: https://github.com/libsdl-org/SDL
