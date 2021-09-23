# DevNote-Boards
Development notes for devlopment boards.

## Xilinx ZC702
The lectures are developed for the graduate course, Embedded Operating System, at National Chiao Tung University.
Since all the resouces (e.g. kernel source codes, cross compilers) are availiable on the Internet, this repo only provides the instructions for the beginner to understand the common procedures to deal with a development board.
The lecture include two labs, setup and driver development.
The goal of setup lab is to boot the board with a self-configured Linux kernel.
Thus, the lab includes two parts, building the boot image (Lab 2-1) and choosing boot mediums (Lab 2-2).
In Lab 2-1, we will built the boot image, which contains boot loaders (a first stage loader and u-boot), uImage (Linux kernel), root filesystem (busybox in this lab), and the device tree.
In Lab 2-2, we put the boot image prepared in Lab 2-1 on the development board with provided boot mediums and understand their differences.
For driver development, we show the procedure to create a character device driver (Lab 4).
The device is a virtual 7-segment written in Python.