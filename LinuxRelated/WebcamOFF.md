# How to turn your webcam ON and OFF
Use the following command to turn OFF the webcam.
`sudo modprobe -r uvcvideo` (I think `uvcvideo` is the name of the camera module. This can be ensured by the command `lsmod | grep uvcvideo`).
The webcam can be turned ON by using the following command.
`sudo modprobe uvcvideo`
