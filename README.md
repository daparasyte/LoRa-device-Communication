# LoRa-device-Communication
Establishing communication over long range using Dragino's LoRa gateway to receive the data sent through LoRa shield which is embedded with an Arduino to extract data from multiple sensors and displaying extracted data on the-things-network.

## Setup
Initially we need to setup IP addresses :
1. In control panel -> Network and Internet -> Network connection -> Ethernet -> Internet Protocal version 4 (TCP/IPv4)
2. Enter following IP address `172.31.255.253`
3. In the subnet mask enter: `255.255.255.252`
4. In your browser enter following IP address: `172.31.255.254:8000`
5. Enter the login credentials and setup your gateway as instructed in the [manual](https://github.com/daparasyte/LoRa-device-Communication/blob/main/LPS8_LoRaWAN_Gateway_User_Manual_v1.3.2.pdf).

## Connecting to the-things-network (TTN)
Please refer to the following link to setup the account on TTN, add and register end devices on it: 
[Setup guide for TTN](https://support.digitalmatter.com/support/solutions/articles/16000122066-setup-devices-on-the-things-network-v3-)

${\color{red}NOTE}$ - The codes attached in this repo contain keys (Dev-EUI, APP-EUI, etc.) that we generated for our devices on TTN, in order to communicate with the LoRa Gateway. Please generate your own keys and change those in the code.
