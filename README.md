# Linux-Color-tool
A linux color tool inspired by windows color command of cmd written in zile for coloring terminals

# Tutorial
user ./color color code
eg 1 for blue or 2 for green or A for lime.

here's the table for colors

Code	Color Name	Color Code
0	Black	0
1	Blue	1
2	Green	2
3	Aqua	3
4	Red	4
5	Purple	5
6	Yellow	6
7	White	7
8	Gray	8
9	Light Blue	9
A	Light Green	A
B	Light Aqua	B
C	Light Red	C
D	Light Purple	D
E	Light Yellow	E
F	Bright White	F

user like 
```bash
./color 0 # for black or change 0 with any code shown above
```


# How to compile
Make sure that you already has GNU GCC/G++ for compile the zile's bfc++ othervise you may noe be able to install it.

## Install g++ for Ubuntu/Debian
```bash
sudo apt install g++
g++ --version
```

## Install g++ for Arch/Manjaro
```bash
sudo pacman -S g++
```

## Compile the zile program
This repo comes with zile compiler v1.2 check change logs of zile lang for seeing what was added.
download and extract this repo first
open the directory where the src dir and zile binary is present.
just execute this command if already has g++
```bash
./zile icolor.zile
g++ icolor.zile.cpp -o color
./color --version
```

if after executing this command you won't see any version of LCT then that's a path error handle the path and try again!

# Enjiy the linux
