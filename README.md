# LoRa-device-Communication
Establishing communication over long range using Dragino's LoRa gateway to receive the data sent through LoRa shield which is embedded with an Arduino to extract data from multiple sensors and displaying extracted data on the-things-network.

## Setup
Initially we need to setup IP addresses :
So, In control panel -> Network and Internet -> Network connection -> Ethernet -> Internet Protocal version 4(TCP/IPv4)
- Enter following IP addresses, 172.31.255.253 and 
- In subnet mask enter: 255.255.255.252
- In your browser enter following IP address: 172.31.255.254:8000 (You need to enter login credentials and setup your gateway as instructed in the manual).

## Connecting to the-things-network (TTN)
Please refer to the folloeing link to setup the account on TTN and adding end devices on it and registering the same: 
[Setup guide for TTN](https://support.digitalmatter.com/support/solutions/articles/16000122066-setup-devices-on-the-things-network-v3-)
