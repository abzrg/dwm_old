## dwm - dynamic window manager

[dwm](https://dwm.suckless.org/) is an extremely fast, small, and dynamic window manager for X.

## Patches and featuers

One branch for each patch:
1. actualfullscreen
2. pertag
3. swallow
4. center
5. noborder
6. vanity gaps
7. scratchpads
8. systray
9. hidevacanttags
10. and possibly a config branch

## Please install libxft-bgra!

This build of dwm does not block color emoji in the status/info bar, so you must install libxft-bgra from the AUR, which fixes a libxft color emoji rendering problem, otherwise dwm will crash upon trying to render one. Hopefully this fix will be in all libxft soon enough.
