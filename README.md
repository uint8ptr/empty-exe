# Empty Windows executable files

Empty PE images, useful for embedding shellcode and executing it.

It contains only the header and a 4 KB code section, which starts at offset `0x400` and is both writable and executable.