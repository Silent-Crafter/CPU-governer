# CPU-governer

## General info
This will change the governer of your cpu to performance by default. If you right-click on the icon you will see more options to change your cpu to the following mode
* Performance
* On-demand (Normal)
* Powersave

This app/script is tested only on GNOME/DEBIAN based distros.

## Setup
To run this program type the following in you terminal:
``` sudo nano cpu.desktop ```
type in the password. This will open it in nano editor. Make sure you are in the same directory where you've downloaded the files.

Then look for the digit 3 in it. it will be written in the line which starts with Exec. Replace 3 with the number of cpus you have -1. if you have 4 cpus add 3.
The simplest way to know how many cpus you have is to open your system monitor and go in the resources tab, you will see CPU1, CPU2, ......, CPU(n). Replace 3 with n-1. 

Afterwards just run:
```
sudo chmod +x install.sh
sudo ./install.sh
```
And you are done!

Open your application menu and look for CPU governer. When you run it, it will set the cpu-mode to performance by default. if you right-click on the icon, you can select between the 3 options

##Uninstallation
```
sudo chmod +x uninstall.sh
sudo ./uninstall.sh
```
