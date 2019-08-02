In order to enable BATMAN connection on a turtlebot, follow the following steps:
- Download batctl by running: sudo apt install batctl
- Replace current module files in /etc/modules with the "modules" file provided
- Replace interfaces file in /etc/network/interfaces with the "interfaces" file that is provided
NOTE: make sure that the interface "eth0" is replaced by the correct interface. You can check this by running "ifconfig" and checking using the intereface that starts with "en"
