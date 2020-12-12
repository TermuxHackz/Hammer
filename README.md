# Hammer
Ddos attack tool for termux
*What is ddos attack*
That is what a Distributed Denial of Service (DDoS) attack is—a method where cybercriminals flood a network with so much traffic that it cannot operate or communicate as it normally would. ... All it takes to create a DDoS attack are two devices that coordinate to send fake traffic to a server or website. That's it.

# What are ddos attack used for
Distributed denial of service (DDoS) attacks are a subclass of denial of service (DoS) attacks. A DDoS attack involves multiple connected online devices, collectively known as a botnet, which are used to overwhelm a target website with fake traffic.

# ddos attack tool
*Hammer*

Hammer need the Name Server of a website which you want to attack...
To get the Name Server...just type
$ nslookup example.com
Note the IP Address of that Website

then
> cd Hammer

> python hammer.py -s [ip Address] -t 135
example:

> python hammer.py -s 123.45.67.89 -t 135

# hammer
<img src="https://github.com/TermuxHackz/Hammer/blob/master/1607798352443.png" width="200px" height="200px"/>

# Installation
```pkg update && pkg upgrade

git clone https://github.com/TermuxHackz/Hammer

cd Hammer

python hammer.py
```
# Usage:
> python hammer.py -s [IP address] -t 135

example: python hammer.py -s 127.0.0.1 -t 135

=============================
