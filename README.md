***********************************************************************************************************
This is a small project aimed at learning a bit more about Networks and Networking.
I'm doing this while I practice and learn stuff for the CCNA exam.

The idea is to create a single .pkt file (Packet Tracer file) which contains a single network I build upon.
I'll loosely follow through Jeremy's IT Lab for the CCNA:

https://www.youtube.com/watch?v=H8W9oMNSuwo&list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ&index=1


...and add new machines (rooters, switches, etc) as I see fit, in order to keep on par with the lessons.
In the end, I'll have a complex (enough) network, which will showcase most aspects within the syllabus.


***********************************************************************************************************

----------------8<-------------[ cut here ]---------------------->8----------------------------------------


***********
23 Mar 2023
***********

- Updated Packet Tracer to 8.2.1

- Created empty Git Repository inside /home/ricardo/PLAYGROUND/PacketTracerProject

- Added this README.md file with a short introduction and these notes

- Added example file to the repository (test)

- Added the GitSteps.md, because I can't be assed to remember those commands, nor repeatedly web search

- Remover the example file

- Added Sketch1.pkt, Main.pkt, Sketch1.png & MainTable.ods

- Sketch1.pkt holds a specific Packet Tracer step/practice. Main.pkt is the main file holding the Network

- Sketch1.png has an image file of a specific table state. MainTable.ods is that main Table (Excel)

- Idea: Perhaps use Git Branches to keep practice Networks (thus practicing a bit with Git)

***********
24 Mar 2023
***********

- Added a couple of machines to my network (still working with one area)

- Gave the diagram some pretty coloring. Greyed the image table as well

- Checked out the ARP PDU, and the ARP tables for all devices. After a couple of PINGs, it all fell into place

***********
25 Mar 2023
***********

- Created new /Sketches folder, to hold all the different sketches and keep the main folder clean

- Created a .gitignore file so that I can better control which files get pushed

- Added another network, with 12.0.0.0. An A class network. Connected a switch and two PCs to it

- Pinged the new network and from the new network. Everything is fine

***********
26 Mar 2023
***********

- Added virtualization to my network, specifically 2 VLANs (home and office)
	
- Turned R0's g0/0 connection into a Router on a Stick, to accomodate the VLANs

- Trunking protocols between switches and switch and router. Accessports between switches and end hosts

- Corrected a minor typo on the table

***********
27 Mar 2023
***********

- Changed the lab to include a L3 Switch (MSW2). Added another VLAN as well, and added a host to VLAN20

- Haven't pushed the results just yet. Got some (theoretic) questions with subnetting and size/economy

- As soon as these issues are ironed out, I'll commit and push the whole thing

- Won't be deleting the RoaS. Just including an SVI for the neighbor's network

***********
31 Mar 2023
***********

- Added a new folder for experiments and stuff that doesn't belong (yet) to the main file

- Two experiments (.pkt files) and a README were added to that folder

***********
26 Apr 2023
***********

- Added this repository to my 'school' computer, so that i can work from there

test3



