# MoSpeed BASIC Compiler Sample

Using latest Commander X16 Release 33 emulator:

https://github.com/commanderx16/x16-emulator/releases/tag/r33

# Compiled using latest MO Speed compiler

https://github.com/EgonOlsen71/basicv2

./mospeed.sh koala.bas /target=KFAST.PRG /platform=x16 -generatesrc=true /addressheader=true

# Run

./x16emu -run -prg KFAST.PRG

# Reference:

https://www.c64-wiki.com/wiki/MOSpeed
