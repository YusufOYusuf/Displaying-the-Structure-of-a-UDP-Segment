<h1>Displaying the structure of a UDP Segment</h1>



<h2>Description</h2>
In this lab, I learned to display the structure of a UDP (User Diagram Protocol) segment. Udp is a connectionless, unreliable protocol. The UDP segment's header simply contains source and destination port numbers, a UDP checksum, and the segment length. 
<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 

<h2>Languages and Utilities</h2>

- <b>Wireshark</b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop open Wireshark application: <br/>
<img src="https://i.postimg.cc/1Rg3NqjW/Screen-Shot-2022-06-23-at-11-18-54-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br />
In the Wirshark Network Analyzer window, select the Ethernet0 interface and click the start Capturing packets icon (sharkfin icon) </br>
<img src="https://i.postimg.cc/xC3yvZ82/Screen-Shot-2022-06-23-at-11-20-10-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Stop capturing packets after you notice SSDP (simple service discovery protocol):</br>
<img src="https://i.postimg.cc/G38XtGW3/Screen-Shot-2022-06-23-at-11-53-43-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Under the Packet details pane, you will observe User Datagram Protocol:  <br/>
<img src="https://i.postimg.cc/sgrzwVYS/Screen-Shot-2022-06-23-at-11-56-50-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<p align="center">
Expand the packet to observe its fields: <br/>
<img src="https://i.postimg.cc/PJnH9hgB/Screen-Shot-2022-06-23-at-11-58-25-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br />
Click file and save the file as udpsegment for further observation: </br>
<img src="https://i.postimg.cc/YjcJj3rZ/Screen-Shot-2022-06-23-at-12-02-19-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
