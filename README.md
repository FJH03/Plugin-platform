Metamod:Source
==============

Metamod:Source - A C++ Plugin Environment and Detour Library for the Source Engine.

Build instructions
------------------

Make sure ambuild2 is installed: https://github.com/alliedmodders/ambuild

You can configure the build Metamod:Source for linux css x86_64:
```
cd metamod-source
mkdir build
cd build
python3 ../configure.py -s css --target x86_64
```

Build:
```
ambuild
```