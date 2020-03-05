# MAKEFILE TEMPLATE

## Description

This script automatically creates a Makefile for your project. Currently it only supports C/C++/C#, but I will extend it in the future to support other languages.

## Usage

The script can be installed as follow:

```bash
git clone https://github.com/isthattyler/Makefile-Template.git
cd Makefile-Template
./install
```

After the installation process, you can use it right away. If you have created a file named 'foo.cpp', creating a Makefile for it and use it is as simple as:

```bash
createmf foo.cpp
make
make clean
```

