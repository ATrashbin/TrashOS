An os made from Nanobyte's Youtube tutorial
How to build
First you need to install nasm
$ sudo apt-get install nasm
If You Get Error
E: Unable To Locate Package nasm
Then Do
$ sudo apt-get update
Second install qemu
Do
$ sudo apt-get install qemu
Third clone the project
$ git clone https://github.com/ATrashbin/TrashOS.git
$ cd TrashOS
Fouth make the project
$ make
Fith load it in qemu
$ qemu-system-i386 -fda build/main_floppy.img
