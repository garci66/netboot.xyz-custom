boot ipxe using iso / similar
(see https://ipxe.org/)
set the ilo boot url to the following:
http://boot.netboot.xyz/ipxe/netboot.xyz.iso


then, once booted, select the ipxe shell from the menu
in the shell call the following:

chain https://raw.githubusercontent.com/garci66/pf-boot/main/boot.ipxe

