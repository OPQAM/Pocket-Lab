This folder keeps loose files that I don't want to add to the main file just yeat, or that simply will never see the light of day.

***********
Mar 31 2023
***********

- Created a simple network with a router, a switch and a couple of PCs (representing groups of 10 PCs)

- Created two separate VLANS. 

- Trunking between the Router and the Switch, and the former as a RoaS.

- Experimented with shutting down the Router after all the configuration was done, and troubleshooted it. More details inside TroubleshootingSimpleVLAN.pkt.

- Main point was that after rebooting, the Router took the VLAN configuration from memory (NVRAM) which means that it won't work until we manually change it.

- I've also added another file: BasicSecurityIssue.pkt
I've just done a couple of simple security experiments - but packet tracer seems to be rather simplified in this regard. More infor can be read inside the .pkt file.
Do note that all this concerns port security.


