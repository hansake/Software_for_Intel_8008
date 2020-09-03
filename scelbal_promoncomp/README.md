This directory contains the SCELBAL source code modified for promoncomp (the "homemade" 8008 based computer).

The code for the "promoncomp" simulator in SIMH is here:
https://github.com/hansake/simh/tree/master/Intel-Systems/promoncomp

The SCELBAL source code as modified from sc1.asm downloaded from http://www.willegal.net/scelbi/scelbal.html

Assemble sc1pmk.asm with as8, just do make.

Test running SCELBAL:
* promoncomp
*
* promoncomp simulator V4.0-0 Current        git commit id: 65af08bd
* sim> load sc1pmk.bin
* 16384 Bytes loaded.
* sim> g 100
*
* READY
*
* SCR
*
* READY
*
* 10 PRINT 4*5
* RUN
*  20.0
*
* READY
*
*
* Simulation stopped, PC: 000103 (INP 4)
* sim> bye
* Goodbye
