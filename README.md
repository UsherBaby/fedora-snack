# fedora-snack
Fix fedora grub after updating Windows 10

[Run this on your windows admin command line](https://ask.fedoraproject.org/en/question/106435/how-to-recover-grub-bootloader/)
```groovy
bcdedit /set {bootmgr} path \EFI\fedora\grubx64.efi
```

H264 decoder
```groovy
sudo dnf install gstreamer1-libav gstreamer1-vaapi gstreamer1-plugins-{good,good-extras,ugly} -y

//Optional
sudo dnf config-manager --set-enabled fedora-cisco-openh264
sudo dnf install gstreamer1-plugin-openh264 mozilla-openh264
```

Spotify
```groovy
sudo  dnf config-manager --add-repo=http://negativo17.org/repos/fedora-spotify.repo
sudo  dnf install spotify
```
Chrome
```groovy
sudo dnf install redhat-lsb
```
