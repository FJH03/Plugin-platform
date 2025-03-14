Build instructions
------------------

Make sure ambuild2 is installed: https://github.com/alliedmodders/ambuild

Metamod:Source
==============

Metamod:Source - A C++ Plugin Environment and Detour Library for the Source Engine.

```
cd metamod-source
mkdir build
```

You can configure the build Metamod:Source for linux css x86_64:
```
python3 ../configure.py --sdks css --target x86_64
```

Configure the build Metamod:Source for pc css x86_64:
```
chcp 65001
py ../configure.py -s css --target x86_64
```

---

SourceMod
=========

```
cd sourcemod
mkdir build
```

You can configure the build Sourcemod for linux css x86_64:
```
python3 ../configure.py --sdks css --target x86_64 --no-mysql
```

Configure the build Sourcemod for pc css x86_64:
```
chcp 65001
py ../configure.py -s css --target x86_64 --no-mysql
```

Common build method:
```
ambuild
```

General
-------
- [SourceMod website](http://www.sourcemod.net): Source Engine scripting and server administration
- [Forum](https://forums.alliedmods.net/forumdisplay.php?f=52): Discussion forum including plugin/extension development
- [General documentation](https://wiki.alliedmods.net/Category:SourceMod_Documentation): Miscellaneous information about SourceMod
 
Development
-----------
- [SourcePawn scripting](https://wiki.alliedmods.net/Category:SourceMod_Scripting): SourcePawn examples and introduction to the language
- [SourceMod plugin API](https://sm.alliedmods.net/new-api): Online SourceMod plugin API reference generated from the include files
- [SourceMod extension development](https://wiki.alliedmods.net/Category:SourceMod_Development): C++ examples and introduction to various extension interfaces