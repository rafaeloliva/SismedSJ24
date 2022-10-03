## SISMED SJ24 version D - Public repo
(Original version 2015 - updated 09.2022)

### Introduction
This repo contains documentation on the SISMED SJ24 systems used in UASJ Campus Test Site, using the CL2bm1 board [Ref1]. A refactored version of the SISMED SJ24 firmware systems (in operation since 2015) is in process and additions will be documented here. The CL2bm1 contains an ATMega1284P controller, and has been active and in use since 2010 [CL2bm1-AVR](https://www.lyr-ing.com/Embedded/LyRAVR_CyEn.htm). 
This version uses the traditional CodevisionAVR C compilers v3 or newer [ref-CVAVR,2022] and contains an Optiboot [RefOptib] programming directory in **/SendThruOptiboot2022**, to program the CL2bm1 board using the COM0 serial port using AVRDude open tools.



### References

[Ref1 - LyR AVR+Cypress](https://www.lyr-ing.com/Embedded/LyRAVR_CyEn.htm)

[ref-CVAVR,2022] HP InfoTech / Codevision AVR C Compiler http://www.hpinfotech.ro/cvavr-features.html

[ref-AVRgcc,2021] AVR GCC compiler: from https://blog.zakkemble.net/avr-gcc-builds/ 

[RefOptib] https://github.com/Optiboot/optiboot

