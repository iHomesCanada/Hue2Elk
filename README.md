# Hue2Elk
Simple apache config to send commands from a Philips Hue Emulator to an Elk M1 Security system.

The configuration built with a Raspberry Pi (any model), Rasbian with Apache2, CGI, JAVA and the Hue Emulator at https://github.com/armzilla/amazon-echo-ha-bridge

The Raspberry Pi is also running an Apache server with CGI enabled. There is a very simple cgi script that is called via On or Off URL called by the Hue emulator that send an ASCII string to the Elk via netcat. The command strings are created with a google sheet. 

[Work in Progress]
