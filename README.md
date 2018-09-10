# TurtleCoin nodes map

Visualizes TRTL nodes and master nodes on the map.


## How to run
install and run freegeoip
```
cd ~
wget https://github.com/fiorix/freegeoip/releases/download/v3.4.1/freegeoip-3.4.1-linux-amd64.tar.gz
tar xvfz freegeoip-3.4.1-linux-amd64.tar.gz
cd freegeoip-3.4.1-linux-amd64
chmod +x freegeoip
./freegeoip --cors-origin "<SITE>" --quota-max 0
```
and run
`npm i`
`sudo node app.js --startnode=[str] --interval=[num] [[ --port=[num]], --freegeoserverUrl=[str]`
interval must more than 3600 
Open localhost:8081.

Example :  node app.js --startnode=localhost  --port=11898 --interval=12000 --freegeoserverUrl=localhost:8080

It's caching nodes' ips every 24 hrs into memory 

![image](https://raw.githubusercontent.com/polar-it/turtle-nodes-map/master/TurtleMap.PNG)




Thanks     Karbovanets/karbo-nodes-map
 
