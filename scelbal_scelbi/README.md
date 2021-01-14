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

Initially in the development of the SIMH SCELBY simulator I could not get hold
of the AS8 assembler, so instead I modified the SCELBAL source code to be assembled
with the Macro Assembler AS (http://john.ccac.rwth-aachen.de:8000/as/).
The modified SCELBAL source is sc-asl.asm.

To assemble and make a loadable binary:
* asl -L sc-asl.asm
* p2bin -l 0 -r 0-\$ sc-asl
