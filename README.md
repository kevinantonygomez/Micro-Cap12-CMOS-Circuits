# Micro-Cap12-CMOS-Circuits
A collection of circuit macros using ASU's 22nm PTM models [http://ptm.asu.edu/] for use with Micro-Cap12

Included:
1. AND gate (2-input)
2. AND gate (3-input)
3. AND gate (4-input)
4. AND gate (5-input)
5. OR gate (2-input)
6. OR gate (3-input)
7. OR gate (4-input)
8. XOR gate (2-input)
9. XNOR gate (2-input)
10. NAND gate (2-input)
11. NAND gate (3-input)
12. NOT gate
13. 1-bit Adder
14. 1-bit Adder and Subtractor
15. 1-bit Encoder
16. 1-bit Decoder
17. 32-bit Decoder
18. Mux (2x1)
19. Mux (3x1)
20. Mux (4x1)
21. 32-bit Binary Shifter (+ dependent macro called '22nmCMOS_BinaryShiftComp')
22. 1-bit Half Adder (Gate input)
23. 1-bit Full Adder (Gate input)
24. Sense Amp

To get started:
1. Add the Standard.cmp and standard.shp files to your Micro-cap root directory. Also, add it to your list of components by using the 'Component Editor' window in Micro-Cap.
2. Replace your nom.lib file in your LIBRARY folder with the given nom.lib. Alternatively, simply add the following lines to your pre-existing nom.lib file: \
.lib "22nm.lib"\
.lib "22nmPMOS.lib"
3. Add the macro files to your LIBRARY folder.

