# fedora-snack
Fix fedora grub after updating Windows 10

Run this on your windows command line
```java
bcdedit /set {bootmgr} path \EFI\fedora\grubx64.efi
```

https://ask.fedoraproject.org/en/question/106435/how-to-recover-grub-bootloader/
