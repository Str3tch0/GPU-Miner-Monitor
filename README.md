# GPU-Miner-Monitor
GPU miner monitor and notification powershell script

This script will run constantly
It will monitor for the miner process as well as the hardware monitor process. 
If either process is not running, it will start it
It will also monitor for GPU temperature threshold, if the temp is below or above the threshold it will tirgger a software restart
If 3 software restarts happen within one session it will trigger a system reboot along with a logfile that will be emailed as a notification of reboot. 

There is a hardware monitor http://openhardwaremonitor.org/downloads/ included in the archive that the script uses to call on for temperature of each GPU. 
