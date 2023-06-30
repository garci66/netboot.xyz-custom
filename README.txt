boot ipxe using iso / similar
(see https://ipxe.org/)
set the ilo boot url to the following:
http://boot.netboot.xyz/ipxe/netboot.xyz.iso

  Press Ctrl-B for the iPXE command line...

then, once booted, 
in the shell call the following:

chain https://raw.githubusercontent.com/garci66/pf-boot/main/boot.ipxe

