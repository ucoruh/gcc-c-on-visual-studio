# Development of C with GCC by Using Visual Studio Community Edition

### Download and Install GCC

https://sourceforge.net/projects/mingw-w64/

- Installation folder 

```batch
C:\Program Files\mingw-w64\x86_64-8.1.0-win32-seh-rt_v6-rev0\mingw64\bin
```

### Add installation folder to system envorinment path

```batch
C:\Program Files\mingw-w64\x86_64-8.1.0-win32-seh-rt_v6-rev0\mingw64\bin
```

### Test installation with console by typing "gcc --version" and "g++ --version"

```batch
C:\Users\ugur.coruh>gcc --version
gcc (x86_64-win32-seh-rev0, Built by MinGW-W64 project) 8.1.0
Copyright (C) 2018 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

### Download and Install Visual Studio Community Edition

[Visual Studio Community 2019 - Free IDE and Developer Tools](https://visualstudio.microsoft.com/tr/vs/community/)



### Open Visual Studio and Create "Makefile Project"

![](images\2020-11-04-16-28-03-image.png)

Choose and create folder for your project

![](images\2020-11-04-16-28-45-image.png)



Create build.bat and clean.bat files for nmake

![](images\2020-11-04-16-29-11-image.png)



## Set the search paths

![](images\2020-11-04-16-30-37-image.png)



![](images\2020-11-04-16-31-19-image.png)



![](images\2020-11-04-16-32-00-image.png)



Nmake section edit Include Search Path

![](images\2020-11-04-16-39-31-image.png)

Add followings from mingw-w64 folder.

![](images\2020-11-04-16-39-46-image.png)

Create build.bat file and locate on project

![](images\2020-11-04-16-41-09-image.png)



![](images\2020-11-04-16-54-16-image.png)

Insert following command in the build.bat

`gcc -Wall -O3 Main.c -o Project1`



Create sample hello world application

![](images\2020-11-04-16-55-09-image.png)

Build application to create exe file

![](images\2020-11-04-16-55-25-image.png)

![](images\2020-11-04-16-55-40-image.png)



Run from visual studio



![](images\2020-11-04-16-56-01-image.png)

Thats all...





