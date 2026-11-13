2048.c - Reverse Engineering & Binary Patching

Architecture: ARM64 (AArch64)  
Platform: Linux  
Tools: Ghidra, GCC, strings, nm  
Target: https://github.com/mevdschee/2048.c

Reverse engineering of the 2048.c game and modification of its tile-merging logic through ARM64 binary patching.

Results:
- Analyzed the game's functions and internal tile representation.
- Identified the merge logic in slideArray.
- Patched the ARM64 instruction at 0x001011f0.
- Changed the tile exponent increment from +1 to +10.
- Verified the modified behavior and investigated rendering issues.

Writeup:
The full technical analysis is available in 2048writeup.pdf.
