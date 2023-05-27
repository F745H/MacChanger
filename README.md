# MAC
A MAC (Media Access Control) address is also known as physical address and it is unique identifier on network. It is a 12-digit and 48-bits long hexadecimal format. It is assigned to the NIC (Network Interface card) of each device that can be connected to the network.

# MacChanger

MacChanger is a script that makes the maniputation of MAC address of network interface. 

To change address randomly execute like this:
```
sudo ./MacChanger.sh eth0
```
To change specific address execute like this:
```
sudo ./MacChanger.sh eth0 00:00:00:00:00:00
```
To change it's original address execute like this:
```
sudo ./MacChanger.sh -O eth0
```

![image](https://github.com/F745H/MacChanger/assets/102409904/447491b7-60e5-4a4f-90f5-06b2ef790b0d)

**Note:**
After restarting the device MAC address changes to it's original address.

# Requirement
To run this script you should have installed macchanger.

On Debian, Ubuntu, Linux Mint, Kali Linux:
```
sudo apt-get update
sudo apt-get install macchanger
```
On Arch Linux or Manjaro:
```
sudo pacman -S macchanger
```
On Fedora, CentOS, RHEL:
```
sudo dnf install macchanger
```
