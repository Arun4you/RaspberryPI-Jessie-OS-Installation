# RaspberryPI-Jessie-OS-Installation

1.1 Open up the Network and Sharing Center settings and navigate to Change Adapter Setting

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/raspberry_pi_wifi_sharing.png)

1.2 Right click on the Wireless Adapter and hit Properties

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/2.png)

Navigate to the Sharing Tab and select the Allow other network users to connect through this computer’s Internet connection checkbox

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/3.png)

1.4 Now right click the Lan Adapter and hit Properties. Double click the IPV4 option and verify that some dynamic IP is populated (192.168.137.1 in my example)

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/4.png)

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/5.png)

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/6.png)

1.5 Now Power ON the Raspberry Pi (ignore if already powered ON :P) and connect one end of the LAN Cable to the Raspberry Pi and the other end to the PC. You should be able to see status messages Identifying… and eventually Unidentified network

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/7.png)

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/8.png)

1.6 Open up cmd prompt and type in:
```
ping raspberrypi.mshome.net

```
You should be able to ping the Raspberry Pi:

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/10.png)

If you’re using the latest PIXEL Image, please make sure you enable the SSH Server by placing a a file named as ssh in the boot directory before trying any of the following methods. The SSH Server on boot has been disabled in the latest Raspbian image as a security measure.

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/ssh_file_creation.png)

1.7 Open up Putty and set the Host Name as: raspberrypi.mshome.net and hit connect. (You can also use the IP address of the Pi revealed in the above ping prompt: 192.168.137.149)

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/11.png)

1.8 You should be able to see the login prompt. Hit pi and raspberry and Enter

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/12.png)

1.9 You can now
```
ping www.google.com
```

(or any other website) from within the Shell and you’ll have response messages. Congratulations! Your Pi now is connected to the World Wiiiiiiide Web 😉

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/13.png)

Testing apt-get

![alt tag](https://github.com/Arun4you/RaspberryPI-Jessie-OS-Installation/blob/master/images/14.png)

