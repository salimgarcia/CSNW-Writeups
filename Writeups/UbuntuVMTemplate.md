# Ubuntu Template VM Writeup
Task Description: Use the most recent LTS release of Ubuntu. What is LTS? look it up and find out!
For the template, you can install a basic VM. Make sure it's up to date, but you shouldn't need to install anything extra on it.

- Go to [ubuntu.com/#download](ubuntu.com/#download) and click `Get Ubuntu Server`
- Click `Manual server installation` and get the LTS version of Ubuntu Server
- Open VMWare Workstation and click File, New Virtual Machine
- Create a VM with the Ubuntu Server ISO
- Reboot the server once Ubuntu is finished installing
- Login to the user account you created in the installation
- Update the server by running `sudo apt update && sudo apt upgrade`
- Shutdown the server when it is finished updating
- Click File in the top left, then click `export to OVF`
- Choose where to save the template, then click save
- LTS - Long Term Support
- A new LTS version is released every two years
- LTS versions get five years of support
- LTS is more enterprise focused
- LTS versions are more tested and have a longer Beta cycle to make them more stable and less buggy