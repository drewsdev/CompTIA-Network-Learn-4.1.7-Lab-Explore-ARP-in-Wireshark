# CompTIA-Network-Learn-4.1.7-Lab-Explore-ARP-in-Wireshark
##CompTIA CertMaster Learn v9.1

Your task is to do the following:

* Use Wireshark to capture packets from the enp2s0 interface (about 5 seconds).  
* Apply a display filter to show arp requests (arp).  
* In the packet list pane, select a packet where the info starts with Who has.  
* Use the information in the packet details pane to answer the questions 1-2.  
* Apply a display filter to show ARP requests with the target of 192.168.0.147 (arp.dst.proto_ipv4==192.168.0.147).  
* Select a packet indicating where 192.168.0.147 is at.  
* Use the information in the packet details pane to answer the questions 3-4.

![WireShark1](/Screenshot_1.png)
![WireShark2](/Screenshot_2.png)
![QnA](/Screenshot_3.png)

Explanation

Complete this lab as follows:

1. Begin a Wireshark capture.  
  a. From the Favorites bar, select Wireshark.  
  b. Maximize the window for easier viewing.  
  c. Under Capture, select enp2s0.  
  d. Select the blue fin to begin a Wireshark capture.  
  e. Wait about 5 seconds,then select the red square to stop the Wireshark capture.  
2. Apply the arp filter.  
  a. In the Apply a display filter field, type arp and press Enter.  
  b. In the packet list pane, select a packet where the info starts with Who has.  
  c. In the packet details pane, expand Address Resolution Protocol.  
  d. Select Questions, then answer Questions 1 and 2.  
  e. Minimize the Lab Questions dialog.  
3. Apply the arp.dst.proto_ipv4==192.168.0.147 filter.  
  a. In the Apply a display filter field, type arp.dst.proto_ipv4==192.168.0.147 and press Enter.  
  b. In the packet list pane, select a packet indicating where 192.168.0.47 is at.  
  c. In the packet details pane, expand Ethernet and Address Resolution Protocol.  
  d. Select Questions, then answer Questions 3 and 4.
