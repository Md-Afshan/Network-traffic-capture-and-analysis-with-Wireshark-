# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:

- Captured Packets with Protocol Analysis and Detailed Packet Info


![alt text](<LAB-9 IMG-1.png>)

- **Start Capturing Packets**

• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.


![alt text](<LAB-9 IMG-2.png>)

- **Apply Filters to Focus on Specific Traffic**
  
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.


![alt text](<LAB-9 IMG-3.png>)

- **Analyze Packet Details**
  
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.


![alt text](<LAB-9 IMG-4.png>)

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
