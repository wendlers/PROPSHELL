PROPSHELL a simple library to create serial shells on the Parallax Propeller
sw@kaltpost.de
http://gpio.kaltpost.de/


Introduction
------------

PROPSHELL is a simple library to create serial shells on the Parallax Propeller. It could be used
for both machine to machine communication and human to machine communication.

Usage
-----

PROPSHELL is written in SPIN. Thus, a spin compiler is needed. If unsure how to get the toolchain,
have a look [here|http://gpio.kaltpost.de/?page_id=1378].

To demonstrate the usage, three examples are provided:

* ``SimpleExample``: shows the basic concepts behind propshell (command definitinos, command processing, error handling etc.)
* ``LEDShellExampleH2M``: shell to interact with a human. Allows to operate the build in LEDs of the Propeller Quick Start board.
* ``LEDShellExampleM2M``: same as above but focused on machine to machine communication (more cryptic commands and and responses, no help etc.)

