Arm Compiler v5 project

To build this you'll need a [Keil ARM compiler v5](https://www2.keil.com/mdk5/compiler/5) which is licensed.

However, it is possible to build this project using [MDK-Community edition](https://www2.keil.com/mdk5/editions/community) which is free for non-commercial use and comes with Arm compiler v6 (need to register on the website and request license online). 

To build with v6 compiler you'll need to slightly modify the code. The [guide to project migration](https://www.keil.com/appnotes/files/apnt_298.pdf) is available on Keil website and in `docs`.

Missing *.lib files are located in in [Lense SDK](../SDK) in `lib` dir.

##### TODO:

- [ ] Arm Compiler v6 project (Windows, free for non-commercial use)
