# Ports used by EZCast Pro

Please refer to the tables below for EZCast Pro port information.

## Ports by Service

### AirPlay

Port | Type                  
:---- | :----------------------
7000 | TCP          
7001 | TCP         
7100 | TCP         
5353 | UDP         

### EZCast Pro App / ProCast

| Port |
| :---- |
| 2425 |
| 63630 |

### ChromeCast

| Port | Type
| :---- | :---
| 80 | TCP
| 443 | TCP
| 8008 | TCP
| 8009 | TCP
| 53 | UDP
| 1900 | UDP
| 5353 | UDP

### Web Server for the web interface

| Port |
| :---- |
| 80 |
| 8080 |

### Over-The-Air (OTA) Firmware

| Port |
| :---- |
| 80 |
| 443 |

### DLNA

| Port | Type
| :---- | :---
| 1900 | UDP
| 2869 | TCP


## How to query ports used by EZCast Pro

Are certain features such as Chromecast not working when connecting to EZCast Pro via your network infrustructure? Microsoft has a Graphical User Interface tool called PortQueryUI which can be used to troubleshoot these kinds of scenarios with port connectivity issues. You can use this tool to troubleshoot TCP/IP connection issues. The utility reports the port status of TCP and UDP ports on a device that you select.

### Download PortQueryUI.exe

* Download and launch the tool [portqueryui.exe](https://download.microsoft.com/download/3/f/4/3f4c6a54-65f0-4164-bdec-a3411ba24d3a/portqryui.exe). Accept the license agreement and proceed:

![Accept the license agreement](/assets/img/PortQueryUI-License-Agreement.png)

* Choose a location to extract the files:

![Extract the files](/assets/img/PortQryUI_extract.png)
 
* You don't need to install `PortQueryUI.exe`, simply run it by double clicking on it:

![PortQueryUI.exe Double click to start](/assets/img/portqueryui.exe.png)

### Query Ports

* Make a note of the Infrastructure IP address which is displayed on the bottom left of the landing page:

![Infrastructure IP address](/assets/img/Infrustructure_IPaddress.png)

In the `destination IP` field, enter the infrastructure IP address. Then specify the ports to be checked and click `Query`, for example:

For the `ChromeCast` service:

* `Ports to query` = **80,443,8008,8009**
* `Protocol` = **TCP**

![Specify Ports](/assets/img/TCP.png)

### More Information

PortQueryUI.exe reports the status of a TCP/IP port in one of the following three ways:

`LISTENING`

A process is listening on the port on the EZCast Pro device that you selected. PortQueryUI.exe received a response from the port.

`NOT LISTENING`

No process is listening on the target port on the target system. Please check your infrstructure in order to allow network connections for this port.

`Filtered`

The port on the computer that you selected EZCast Pro device is being filtered. PortQueryUI.exe didn't receive a response from the port. A process may or may not be listening on the port. By default, TCP ports are queried three times, and UDP ports are queried one time before a report indicates that the port is filtered.


![Query Results](/assets/img/TCP.results.png)