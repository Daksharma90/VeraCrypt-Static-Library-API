# VeraCrypt-Static-Library-API

Requirements of this API:

You must be on Linux OS and VeraCrypt Source code must be downloaded from the official VeraCrypt site.
After Dowloading the Source Code then open Terminal.

step 1: Change the directory to the directory where the source code is present.

step 2: cd to src.

now execute the command:
make NOGUI=1;

This will creaye a executable in Main named as "veracrypt".

now copy the files of this respository and do change the file paths in source code as per your system.

now change to the directory where API files are present then perform 

make

Now perform 

g++ -std=c++11 -Wall Main.cpp VeraCryptFacade.cpp -o Main

for compiling the test program.

Now You can see a "Main" executable which can be executed by:

./Main

And You will get options and functionalities from this API such as:

Create Volume

Mount Volume, etc.
