# TextToKernel
Simple example how to print a text via a kernel using Video Memory

## Installation
For the kernel to run and compile we need
* GNU/Linux	- an environment to work on
* Assembler	- GAS (GNU Assembler) to assemble all files
* C Buildtools	- GCC (GNU Compiler Collection), a strong C compiler
* Xorriso	- To create, load and manipulate ISO 9660 filesystem images
* grub-mkrescue	- To make a GRUB (Grand Unified Bootloader) rescue image and to build an ISO image
* QEMU		- [Q]uick [Emu]lator to boot the kernel in a virtual machine

```bash
sudo apt-get install build-essential xorriso qemu-kvm qemu virt-manager virt-viewer
```

## Running
Run the command
```bash
./run.sh
```
possibly also give the file execution permissions
```bash
sudo chmod u+x run.sh
```
