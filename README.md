# Diablo II - LoD - "Exp Share Range Fix"
Gets rid of the two-screen experience share range limit introduced in LoD patch 1.10.

## How to use the info in this repository

Bare minimum you need a hexadecimal editor and need to know how to search for and how to modify hex values using this type of software.

Recommended hex editor : [ImHex](https://github.com/WerWolv/ImHex)

## Details

The method used is changing the target address of a jump so that destination is the next instruction thus making exp share map-wide.

## Thanks
Devurandom  /  lolet  /  Fearedbliss

For their posts on the Phrozen Keep which helped me find the right offsets for several game versions
