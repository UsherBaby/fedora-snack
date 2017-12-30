# fedora-snack
Fix fedora grub after updating Windows 10

Run this on your windows command line
```
bcdedit /set {bootmgr} path \EFI\fedora\grubx64.efi
```
