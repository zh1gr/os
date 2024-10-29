os
=

install before run:
- NASM
- qemu

build:
```shell
make
```

run:
```shell
qemu-system-i386 -fda build/main_floppy.img
```

close OS window/terminal:
- press *control+option+2* then write `quit`


mac m1:
- `brew install dosfstools`
- `brew install mtools`

written by [tutorial](https://youtu.be/9t-SPC7Tczc?si=iJsT3CcTrXMTVSeS)