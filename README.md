# Debian Installation process

## go to `https://www.debian.org/CD/live/` download from DVD/CD it will redirect you to `https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/`

- Choose any distro you want in my case Gnome with iso file
- insert 8GB usb drive
- in Terminal write `lsblk` and be sure for your usb drive
- in Terminal `sudo umount /dev/sdb` to be sure that the drive in unmounted
- when your iso file downloaded navigate to Downloads folder In terminal `cd Downloads`
- in terminal write `sudo dd bs=4M if=debian-live-10.5.0-amd64-gnome.iso of=/dev/sdb status=progress oflag=sync`
- Congrats!! your debian live is ready