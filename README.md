#raspberry-pi-networkmon
A simple bash script to output the cpu temprature and load.

Setup
copy the scripts to a local folder on the pi (in this case /home/pi)
add the following entry to crontab /10 * * * * /home/pi/networkmon.sh >> /home/pi/networkmon.log
restart the Raspberry Pi
