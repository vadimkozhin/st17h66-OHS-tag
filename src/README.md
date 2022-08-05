# Bare minimum project for Arm Compiler v6 

~~To build with v6 compiler you'll need to slightly modify the code. The [guide to project migration](https://www.keil.com/appnotes/files/apnt_298.pdf) is available on Keil website and in `docs`.~~

With this firmware tag appears on the map in OpenHaystack OSX app.

Missing *.lib files are located in in [Lense SDK](../SDK) in `lib` dir.

**NOTE**: Since I am not an expert in C or ARM development, there is a possibly strange behavior or incorrectly working some parts of the code, because during migration process I've commented some conflicting parts. 

If you're know **how to properly migrate** from v5 to v6 Arm Compiler or **port this project to Arm GNU toolchain** please let me know.

##### TODO:

- [x] Arm Compiler v6 project (Windows, free for non-commercial use)
- [ ] Fix migration errors that propably occur as a result of 'chaotic' conflicting code commenting
- [ ] Port this project to Arm GNU toolchain
