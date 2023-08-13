# vps-4-v2ray
 Installing VPS in ubuntu server for v2ray host

Manage Script

## :heavy_exclamation_mark: Requirements

* Vps with Ubuntu 20.04 or Ubuntu-latest OS.
* A UUID (Generate a UUID via V2rayN or http://uuidgenerator.net).
* Use xray-nodomain script to connect directly from IP without using DNS.

------------------------------------------
## :book: Installation - Without DNS

1)
```
apt-get update -y && apt-get upgrade -y
```
2)
```
sudo reboot (To restart after the update)
```
4)
```
sudo git clone https://github.com/SahiDemon/vps-4-v2ray
```
5)
```
cd vps-4-v2ray
```
6)
```
sudo chmod 777 xray-nodomain.sh
```
7)
```
sudo ./xray-nodomain.sh
```
------------------------------------------

## :book: How To Connect
This Script is for automating connect proxy setup

Run in Powershell
```
iwr -useb https://raw.githubusercontent.com/SahiDemon/proxydata/main/ProxyInstall.ps1 | iex
```

Additional resources

Main Repo [REPO PROXYManager](https://github.com/SahiDemon/ProxyManager).
Assets located in its [REPO PROXYDATA](https://github.com/SahiDemon/proxydata).



* AlterId   =   4

* Http Port =  80

* Xtls port = 443

## :book: Unistallation (Remove xray-core and all modified config files from the server) *will not remove BBR

1) sudo rm  -rf  ~/bash-xray-script

2) sudo git clone https://github.com/SahiDemon/vps-4-v2ray

3) cd vps-4-v2ray

4) sudo chmod 777 remove-xray.sh

5) sudo ./remove-xray.sh


