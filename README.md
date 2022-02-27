# scrcpy-bin-bash
First you have to install `scrcpy` like described on [github](https://github.com/Genymobile/scrcpy) and install `adb platform tools` from [android developers](https://github.com/Genymobile/scrcpy) to be able to use this files. 


## For Linux
### Steps to do: 
1. Enable the developer settings on your devices and set `permit usb debugging`
3. Connect the devices you want to display on your screen.
4. Open `terminal`.
5. Get the ID of your device via `adb devices -l`
6. Open the file `device1_scrcpy.sh` and paste the ID. 
7. Make the file executable with `sudo chmod +x /path/to/device1_scrcpy.sh`. Once executed the file you can see the screen the screen of the device on your PC.
8. More functions you can get by typing `scrcpy -help`.

### Optional steps
9. To make an "app" you can start by clicking on it you need to open the file `app_template.desktop`and put in the date like described in the file. 
10. Copy the file into `/usr/share/applications`. 
11. If you want to connect more than one device you have to repeat the steps 5 to 10 using the file `all_devices_scrcpy.sh`.

## For Windows
To be created...
