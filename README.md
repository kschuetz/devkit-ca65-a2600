# devkit-ca65-a2600

This repository is a collection of files that are useful in building Atari 2600 projects using the ca65 assembler (a component of the cc65 suite).
The makefile automates all the assembly and linking steps.

Setup:

1.  Install cc65 (http://cc65.github.io/cc65/) and make sure it's in your PATH.

2.  Optional - install Stella (https://stella-emu.github.io) and make sure it's in your PATH.

3.  Set environment variable to `DEVKIT_CA65_A2600` to point to directory you have `devkit-ca65-a2600` located


To use this in a project:

1.  Create your project directory with the same name as the target.  For instance, for `foobar.bin` you'd call the directory `foobar`.

2.  Copy the file `Makefile` from the `template` directory to your project directory.

3.  Add any source files to the directory.  Any file with extension `.s` will automatically be included in the project.

From your project directory, you can do any of the following from the command line:

1.  `make` builds the project

2.  `make run` builds the project, and runs it in Stella

3.  `make clean` cleans the directory and removes intermediate object files, etc.


