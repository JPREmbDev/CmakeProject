# CmakeProject
Learn to master modern CMake Projects, Unit Tests, Continuous Tools and more to use in your daily C/C++ workflow!

0.) Crear los archivos fuentes y el CMakeFile

1.) mkdir build --> Creamos la carpeta build dentro de la carpeta del proyecto.

2.) Ejecutamos el comando cmake para generar los archivos Build y la configuración del proyecto.
    --> CmakeProject\1_HelloWord> cmake -G "MinGW Makefiles" .

Directorio: ..\CmakeProject\1_HelloWord

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        20/11/2023     20:33                build

d-----        20/11/2023     23:24                CMakeFiles

-a----        20/11/2023     23:24          17023 CMakeCache.txt

-a----        20/11/2023     20:03            657 CMakeLists.txt

-a----        20/11/2023     23:24           1658 cmake_install.cmake

-a----        20/11/2023     20:03             91 main.cc

-a----        20/11/2023     23:24           5545 Makefile



3.) cmake --build --> Dentro de la carpeta del proyecto
    --> CmakeProject\1_HelloWord> cmake --build .

[ 50%] Building CXX object CMakeFiles/Executable.dir/main.cc.obj
[100%] Linking CXX executable Executable.exe
[100%] Built target Executable

4.) ./Executable    o     .     .\Executable.exe