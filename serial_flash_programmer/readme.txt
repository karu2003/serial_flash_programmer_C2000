Texas Instruments C2000 Serial Flash Programmer Example Package


The serial_flash_programmer.sln should be loaded into Visual Studio
and built in Visual Studio.  Although the source files contain some C++ 
for linux within some #defines, we have NOT yet compiled and tested it 
to run on linux machines.

The resulting serial_flash_programmer.exe should be run from the command line.

For build in Windows it need Visual Studio 2017 BuildTools.

base on C2000Ware_1_00_06_00.

Build on Linux

mkdir build
cd build
cmake ..
make

tested 
WSL, Raspberry Pi.
  
