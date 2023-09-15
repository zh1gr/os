os
=

install before run:
- NASM
- qemu

run: 
- `make`
- `qemu-system-i386 -fda build/main_floppy.img`

close os window/terminal: press *control+option+2* then write `quit`