# argon one for ubuntu 
Added installation of raspi-config (since it's available now) and libraspberrypi-bin. Also it complained about /boot/cmdline.txt, so script now creates the appropriate file, if you're using the SD Card. I haven't converted mine yet to boot from M.2 so idk.

https://download.argon40.com/argon1.sh is the original script, if you would like to compare.

```
git clone https://github.com/davethepear/argonone-ubuntu.git
chmod +x argon1m.sh
sudo ./argon1m.sh

Use argonone-config to configure fan
Use argonone-uninstall to uninstall
Use argonone-tempmon to monitor the temperature
```
