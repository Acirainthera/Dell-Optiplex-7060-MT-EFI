Specs:
- i7 8700
- IGPU (UHD 630)
- HDD 1TB
- Intel Mausi Ethernet
- 8GB DDR4 2600MHZ (Dual Channel)
-No Integrated Wireless Lan.
Instructions:
First download the EFI and feel free to make any small changes to the config.plist with OC auxilary tools (ONLY)
Add any kexts which are required in OC auxilary tools. If going below BigSur/Monterey/Ventura Do the following:
Set Securebootmodel according to the OC Guide
Enable XHCIPORTLIMIT
If your optiplex variant has a wireless lan please add itwlmkext for internet. This EFI only has IntelMausi.kext

good luck. If any issues are known post it in issues, i will check and fix it.
Untested-:
DVD Rewritable Drive
Card Reader Unknown
these will not be fixed, because they are useless for me.
