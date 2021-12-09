
# C++ First Project
This is first C++ Project - **Hello World**

In this project, we have printed **Hello World**.




## Prerequisites
 - **C++ IDE**
   - [VS Code (Visual Studio Code)](https://code.visualstudio.com/docs/?dv=win)
   - Install following extensions : -
       - C/C++
       - Code runer
       - C/C++ Makefile Project 
    - Go to manage setting and open Command Palette,type **create c++ project** and select folder for creating project.
  
 - **MinGW Compiler**
   - [MinGW-w64](https://sourceforge.net/projects/mingw-w64/)
   - Now you need to set the environment variables, so for which you need to paste the bin path.In bin folder "make.exe" must be otherwise you will find the error such as "'make' is not recognized as an internal or external command".
   - To avoid above such error we simply do following : -
        -  Make another copy of **C:\MinGW\bin\mingw32-make.exe** file in the same folder.
        -  Rename the file name from **mingw32-make.exe** to **make.exe**.
        -  Run make command again.
        -  [For more details click here.](https://stackoverflow.com/questions/23723364/windows-7-make-is-not-recognized-as-an-internal-or-external-command-operabl)
    


## Compile and Run Program
**After generating project and implementing the code we simply do following two steps : -**
-  To Compile the Program, type

```bash
  make
```

-  To run the Program, first change the directory and go to output folder where your **'main.exe'** file exits.For changing the directory,type **cd output** and for running the Program,type


```bash
  ./main
```
 *where ./ represents present working directory and 'main' is the executable target file.*
 
 ## Output 
 ![First_C++_project](https://user-images.githubusercontent.com/72221154/145340730-511b130d-c642-434a-a454-2c18549172a8.png)



