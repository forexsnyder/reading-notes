Wireshark 


Capture packets by putting Wireshark in promiscuous mode.


Packets that arrive at your NIC will be recorded rather than dropped.  It will accept everything in
in promiscuous mode.

This is the default setting.

There are limitations because a switch only sends traffic addressed to an MAC on a certain port.  There is a level of intelligence at the switch level.  The best way to get around this is to mirror the port to the gateway.
This means you will need physical access to the network.  

Once packets are being captured, 3 situations for discovering passwords.  

1. the network protocol transporting the packets is unencrypted. 
2. the protocol is encrypted and we do not have the encryption keys. 
3. the network is encrypted, but we have the encryption keys.


Case 1. Happened today for the ftp server


The other cases, are hang up your hat and call it a day.  

All of this sounds like a better way is to set up a proxy and a man in the middle attack.

Where a user enters credentials in plain text over http, errors and then gets forwarded to the correct website.  

Filter packets in filter bar.


Lower window shows different layers of the OSI model.  Each one show the headers of the layers. 
Clear text packets are in the lowest window.
Congestion control Statistics->TCP Stream graphs 
