This directory contains the SCELBAL source code modified for mtc8008 (the "homemade" 8008 based computer).

The code for the "mtc8008" simulator in SIMH is here:
https://github.com/hansake/simh/tree/master/Intel-Systems/mtc8008

The SCELBAL source code as modified from sc1.asm downloaded from http://www.willegal.net/scelbi/scelbal.html

Assemble sc1pmk.asm with as8, just do make.

Test running SCELBAL:
* mtc8008
*
* mtc8008 simulator V4.0-0 Current        git commit id: 65af08bd
* sim> load sc1mtc.bin
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
