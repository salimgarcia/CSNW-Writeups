# Smokeping_writeup

- Connect Raspberry Pi to monitor and performed install of Raspberry Pi OS
- Once install is finished, enable SSH by clicking the Pi logo in the top left and navigating to Preferences, Pi Configuration, and selecting the Interfaces tab
- Shutdown Raspberry Pi, unplug from monitor, and connect to router with ethernet cable
- Power on the Raspberry Pi and SSH into it from desktop
- Check for updates with `sudo apt update && sudo apt upgrade`
- Install smokeping with `sudo apt install smokeping`
- Open a web browser and navigate to IP of Pi/cgi-bin/smokeping.cgi
- To add targets for smokeping, to `/etc/smokeping/config.d` and edit the file Targets
- Save the file and restart smokeping with the command `service smokeping restart`
- To view the graphs created by smokeping, navigate back to the web interface and click on Local
- Let smokeping run for about 12 hours to gather enough data to generate a graph

### Graphs

![alt text](images/smokeping1.png)

![alt text](images/smokeping2.png)

![alt text](images/smokeping3.png)