#raspberry-pi-tempmon
=====================
A simple bash script to monitor the network service.

Setup
-----
1. copy the scripts to a local folder on the pi (in this case /home/pi)
2. add the following entry to crontab */10 * * * * /home/pi/networkmon.sh >> /home/pi/networkmon.log*
3. restart the Raspberry Pi

