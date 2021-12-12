# TrashOS

An os made from Nanobyte's Youtube tutorial

# How to build

First you need to install nasm

```bash
$ sudo apt-get install nasm
```

If You Get Error

```bash
E: Unable To Locate Package nasm
```

Then Do

```bash
$ sudo apt-get update
```

Second install qemu

Do

```bash
$ sudo apt-get install qemu
```

Third clone the project

```bash
$ git clone https://github.com/ATrashbin/TrashOS.git

$ cd TrashOS
```

Fouth make the project

```bash
$ make
```

Fith load it in qemu

```bash
$ qemu-system-i386 -fda build/main_floppy.img
```
