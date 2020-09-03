SCELBAL interpreter downloaded from http://www.willegal.net/scelbi/scelbal.html
and assembled with AS8.

Assemble SCELBAL source sc1.asm
* as8 -markascii -bin -octal sc1.asm
* (or just make)

Start the SCELBI simulator
* scelbi

Load and run SCELBAL
* SCELBI simulator V4.0-0 Current        git commit id: 65af08bd
* sim> load sc1.bin
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
