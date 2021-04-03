# Windows_commands


## 01.Network WLAN detail :
### Show all saved networks
netsh wlan show profile
### Show detail of specific network
netsh wlan show profile "SSID" key=clear

## 02.Ports and Connections :
### NETSTAT - Network and Statistics
netstat -antoF

## 03.Ping and Trace route :
### Ping
ping www.google.com
### Trace Route
tracert www.google.com 
traceroute www.google.com (Linux) 

