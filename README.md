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



root@raspberrypi:/home/pi# cat /proc/cpuinfo
processor	: 0
model name	: ARMv6-compatible processor rev 7 (v6l)
BogoMIPS	: 697.95
Features	: half thumb fastmult vfp edsp java tls
CPU implementer	: 0x41
CPU architecture: 7
CPU variant	: 0x0
CPU part	: 0xb76
CPU revision	: 7

Hardware	: BCM2835
Revision	: 000e
Serial		: 00000000a2ba23d5
Model		: Raspberry Pi Model B Rev 2
root@raspberrypi:/home/pi#
root@raspberrypi:/home/pi#

