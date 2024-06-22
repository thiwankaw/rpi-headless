# rpi-headless
Setting up rpi-2 ( model b) headless device

download 32 bit image from https://downloads.raspberrypi.org/raspios_lite_armhf/images/ and write it to sd card

Boot rpi-2, and enable ssh

sudo raspi-config
Navigate to Interfacing Options and then to SSH.
Choose Yes to enable the SSH server.
Exit raspi-config

apt-get update
apt-upgrade





