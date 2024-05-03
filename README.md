# Script Autoinstaller for SSHws and Xray
Supports Debian 10 and Ubuntu 20, please those using other OS versions, rebuild to a supported OS version (Ubuntu 20 recommended)

NB: These codes are totally free, open source, and all belongs to ©Yudhynet. Me personally just completed some codes

## Installer
### Select one of the two links below
Long link 2
```
wget https://raw.githubusercontent.com/LawVPN/SSH-XRAY/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
Short link
```
wget s.id/lawsc; bash lawsc
```

If you are already using Debian 10 but still encounter errors when installing the script, please copy and paste the code below and install the script again.
```
sudo su
```
```
apt update; apt install -y vnstat htop nload; apt upgrade -y; update-grub; reboot
```

### Note for squid error or not running
Make sure to edit the banner and make it not too long
```
nano /etc/issue.net
```
