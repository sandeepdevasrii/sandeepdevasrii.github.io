# Mount USB drive in Linux installed inside Windows using Windows Subsystem for Linux (WSL)

`sudo mkdir /mnt/usb`
here, usb the name of the folder to which USB drive will be mounted.
`sudo mount -t drvfs D: /mnt/usb`
Here, D is the partition name of the USB drive in windows.
