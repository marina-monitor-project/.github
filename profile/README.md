# Welcome to our Marina Monitor Project

Project to help marinas keep boats safe.

# Background

Boats moor at slips in a marina. At most slips there is a pedistal that provides power to the boat while it is moored. The power is used by the boats for things like running to pumps to stop the boat from sinking. 

In this project, we want to add a small device to the pedistal. That device will record electricity usage. The data will be used to alert the marina (maybe boat owner too) if the power is down. That way, we can reduce the chance that the boat will sink becaue the pumps aren't work. 

Also, the marina can use the data to better charge electrical use while moored at the marina and check for boat users leaving facilities on after leaving the slip,


# Technical Overview
1. A small device will designed that can monitor electricity on the pedistial
2. the device will use low power Radio to send its message to a hub that will push the data to the web
3. Once in the web, the data will be used to identify issues with the pedistal
4. Alerts will be sent from the web to the marina watchman so that they can walk over and investigate the issue
5. Other services can be added to web system over time (e.g. bills for power usage,etc)
