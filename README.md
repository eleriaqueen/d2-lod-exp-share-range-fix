# Diablo II - LOD - "Exp Share Range Fix"
Gets rid of the two-screen experience share range limit.

## How to use the info in this repository

Bare minimum you need a hexadecimal editor and need to know how to search for and how to modify hex values using this type of software.

Recommended hex editor : [ImHex](https://github.com/WerWolv/ImHex)

## Details

The method used in this repository is to change the target address of a conditional jump to be the next instruction instead of its original target address (essentially NOP-ing it) thus bypassing a range check

## Thanks
Devurandom  /  lolet  /  Fearedbliss

For their posts on the Phrozen Keep which helped me find the right offsets for several game versions
