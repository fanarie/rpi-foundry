# use arm64 ubuntu
The 64bits image can be found here: https://ubuntu.com/download/raspberry-pi

I use the [22.04 LTS version](https://ubuntu.com/download/raspberry-pi/thank-you?version=22.04&architecture=desktop-arm64+raspi).

To manage ip setting and an ubuntu account not expired (as well as a non update kernel at boot first, this will be managed by the ansible install), we use cloud-init files. 

Template files can be found in the cloud-init folder and it must copied in the /boot partition just after the image burn. Just Change your targeted IP address in the network-config file.

Used to install a [Foundry VTT](https://foundryvtt.com/) server on a RPI4 (use at least a 2GB RAM rpi4 version, prefer a 4GB one).
Your linux install archive must be put in the ansible files folder.
