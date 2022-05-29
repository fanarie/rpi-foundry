# use arm64 ubuntu
The 64bits image can be found here: https://ubuntu.com/download/raspberry-pi

I use the [22.04 LTS version](https://ubuntu.com/download/raspberry-pi/thank-you?version=22.04&architecture=desktop-arm64+raspi).

To manage ip setting and an ubuntu account not expired (as well as a non update kernel at boot first, this will be managed by the ansible install), we use cloud-init files. 

Template files can be found in the cloud-init folder and it must copied in the /boot partition just after the image burn. Just Change your targeted IP address in the network-config file.

