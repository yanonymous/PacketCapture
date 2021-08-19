# NETWORK PACKET CAPTURE

Jpcap is a java library which is is used for network related programs which uses WinPcap (windows) or libpcap (Linux or MacOS)

However this works only in 32-bit systems

In this project I aim to achive network interception using Pcap4j library.

### ABOUT
   
  * ArchType - maven-archtype-quickstart
  * Additional dependencies - org.pcap4j (1.7.3), org.slf4j (1.7.5)
  * Development platfrom used - Windows
  * IDE - VsCode (with JAVA EXTENSION PACK)

### Working

PcapNetworkInterface gets all the available network interfaces on your system

PacketListener Listener defines that the recived packet should be stored in out.pcp file with timeStamp

In the end it prints all the stats

BEFORE YOU RUN THIS YOU NEED TO DEFINE DEPENDENCIES IN YOUR CLASSPATH

Thats all folks

Contributions are always welcome :)

