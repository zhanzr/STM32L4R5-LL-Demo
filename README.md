LL API Coremark.
#define ITERATIONS	5000

with microlib:
CoreMark 1.0 : 311.410065 / ARMCC 5060422 -c --cpu Cortex-M4.fp -g -O3 -Otime --apcs=interwork --split_sections --C99 / STACK

without microlib:
CoreMark 1.0 : 311.468261 / ARMCC 5060422 -c --cpu Cortex-M4.fp -g -O3 -Otime --apcs=interwork --split_sections --C99 / STACK

=======================================
With microlib:
LL Coremark For STM32L4R5 Nucleo Board @ 120000000 Hz
Flash Size:2048	,PackType:4
2K performance run parameters for coremark.
CoreMark Size    : 666
Total ticks      : 16056
Total time (secs): 16.056000
Iterations/Sec   : 311.410065
Iterations       : 5000
Compiler version : ARMCC 5060422
Compiler flags   : -c --cpu Cortex-M4.fp -g -O3 -Otime --apcs=interwork --split_sections --C99
Memory location  : STACK
seedcrc          : 0xe9f5
[0]crclist       : 0xe714
[0]crcmatrix     : 0x1fd7
[0]crcstate      : 0x8e3a
[0]crcfinal      : 0xbd59
Correct operation validated. See readme.txt for run and reporting rules.
CoreMark 1.0 : 311.410065 / ARMCC 5060422 -c --cpu Cortex-M4.fp -g -O3 -Otime --apcs=interwork --split_sections --C99 / STACK
End of Coremark

Without microlib:
LL Coremark For STM32L4R5 Nucleo Board @ 120000000 Hz
Flash Size:2048	,PackType:4
2K performance run parameters for coremark.
CoreMark Size    : 666
Total ticks      : 16053
Total time (secs): 16.053000
Iterations/Sec   : 311.468261
Iterations       : 5000
Compiler version : ARMCC 5060422
Compiler flags   : -c --cpu Cortex-M4.fp -g -O3 -Otime --apcs=interwork --split_sections --C99
Memory location  : STACK
seedcrc          : 0xe9f5
[0]crclist       : 0xe714
[0]crcmatrix     : 0x1fd7
[0]crcstate      : 0x8e3a
[0]crcfinal      : 0xbd59
Correct operation validated. See readme.txt for run and reporting rules.
CoreMark 1.0 : 311.468261 / ARMCC 5060422 -c --cpu Cortex-M4.fp -g -O3 -Otime --apcs=interwork --split_sections --C99 / STACK
End of Coremark




