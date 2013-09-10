Keyswitch Breakout Boards
=========================

**This is a work in progress, and the hardware/software described here has not been shown to work correctly.**

These small boards are designed to adapt [Cherry MX](http://www.cherrycorp.com/english/switches/key/mx.htm) and ALPS SKC keyswitches to standard 0.1″ breadboards.

The center of the keyswitch is offset by 0.025″ on each axis from the 0.1″ breadboard grid. This allows for adjacent keys at 0.75″ spacing to be mounted on a 0.1″ breadboard by rotating successive units 90°.

For the Cherry MX, a matrix diode can be installed either in the switch (through hole) or on the breakout board (surface mount); the ALPS board only has room for an SMD matrix diode. Both allow mounting an LED of the appropriate type — 3mm round for Cherry MX, 2mm × 5mm rectangle for APLS. (APLS variants with click plates have no room for an LED.)

The boards also have pins that bypass any installed matrix diode.

Except for the LED, all connections are duplicated at two or three points to simplify building a matrix.

Schematics and boards are in [Eagle CAD](http://www.cadsoftusa.com/download-eagle/) format.

<!-- vim:set et sts=4 sw=4 linebreak ft=ghmarkdown: -->
