python multicast
================

This repository contains a simple multicast client/server implementation.

The client and the server must use the same multicast address and port.

The official list from IANA may be found [here](http://www.iana.org/assignments/multicast-addresses/multicast-addresses.xhtml)


server.py
---------

The server that waits for the multicast data. Could be run on multiple machines.


client.py
----------

The client that sends the multicast trafic.

It just sends the data, no check is perfomed to know whether or not anyone is listening or receiving.
