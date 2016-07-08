# Apple 2 Hardware Disassembly Project - Peripheral: ThunderClock Plus

# == Parts List ==

* 1x 1990C
* 1x 2708 (EPROM)
* 1x 74LS08
* 1x 74LS27
* 1x 74LS74
* 1x 74LS109
* 1x 74LS132
* 1x 74LS126
* 1x 74LS174
* 1x CD4050  (Motorola MC14050B / CP QQ8014)
* 1x D4050
* B1 HOLDER BATTERY 1CELL N ALUMINUM DigiKey: [36-154-ND](http://www.digikey.com/product-detail/en/keystone-electronics/154/36-154-ND/61790)
* B2 HOLDER BATTERY 1CELL N ALUMINUM DigiKey: [36-154-ND](http://www.digikey.com/product-detail/en/keystone-electronics/154/36-154-ND/61790)
* C1 104Z (East)
* C2 104Z (East)
* C3 104Z (North)
* C4 104Z (North)
* C5 104Z (East)
* C6 104Z (North)
* C7 NPO 20J
* C8 variable
* CX ???
* D1 ??? M5?2?   (Diode)
* D2 ??? N40-0 (Diode)
* R 1 Brown- Black- Orange Gold = 10 * 1K Ohm +/- 5%
* R 2 Yellow Violet Orange Gold = 47 * 1K Ohm +/- 5%
* R 3 Yellow Violet Orange Gold = 47 * 1K Ohm +/- 5%
* R 4 Yellow Violet Orange Gold = 47 * 1K Ohm +/- 5%
* R 5 Yellow Violet Orange Gold = 47 * 1K Ohm +/- 5%
* R 6 Orange Orange Red--- Gold = 33\*100 Ohm +/- 5%
* R 7 Brown- Black- Orange Gold = 10 * 1K Ohm +/- 5%
* R 8 Yellow Violet Orange Gold = 47 * 1K Ohm +/- 5%
* R 9 Orange Orange Red--- Gold = 33\*100 Ohm +/- 5%
* R10 Blue-- Orange Black  Gold = 63 *  1 Ohm +/- 5%
* R11 Brown- Black- Orange Gold = 10 * 1K Ohm +/- 5%
* R12 Brown- Black- Green- Gold = 10*100K Ohm +/- 5%
* R13 Brown- Black- Green- Gold = 10*100K Ohm +/- 5%
* SW1 DIP SWITCH 
* SW2 -- not installed --
* Q1 2N3904
* Q2 2N3904 ???
* Q3 2N3904
* Q4 2N3904 ???
* Y1 ???

|Color  |Digit|Multiplier|
|:------|:---:|---------:|
|Black  |  0  |    1 Ohm |
|Brown  |  1  |   10 Ohm |
|Red    |  2  |  100 Ohm |
|Orange |  3  |   1K Ohm |
|Yellow |  4  |  10K Ohm |
|Green  |  5  | 100K Ohm |
|Blue   |  6  |   1M Ohm |
|Violet |  7  |  10M Ohm |
|Grey   |  8  |          |
|White  |  9  |          |
|Gold   |  -  |    x 0.1 |
|Silver |  -  |   x 0.01 |

# == Layout ===

* Component Side:

```
 _______________________________________________________________________________
|                B2      B1      C8    SW1           ThunderClock Plus          |
|R12 R13 Q4                     Y1 C7                              C4       Q1  |
|                             D2     1990C  CD4050  74LS174  74LS08   74LS132   | A
|        Q3                 Q2                    R3       R2                R1 |
|                                    R4                                         |
|        R11                  R7     R5                                   Sw2   |
|                                                                               |
|            D1   74LS74  74LS109  74LS126                   2708  C3  74LS27   | B
|        R10    R9      R8       R6                                C2           |
|                                       C6         C5          C1            CX |
 ___________________________________________________                         ___|
                                                    |_|_|_|_|_|_|_|_|_|_|_|_|
                                                     1                    25
```

# == Schematic ==

* [ ] TODO

# == Questions ==

* What is Y1 ?
* What is CX ?
* What is D1 ?
* What is D2 ?

