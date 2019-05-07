# PCAP Lab ― AED
Updated: Spring 2019

----
## what is PCAP?
from the [Wikipedia](https://en.wikipedia.org/wiki/Pcap) page:

> "In the field of computer network administration, pcap is an application programming interface (API) for **capturing network traffic**. While the name is an abbreviation of a technical term of art (jargon) packet capture, that is not the API's proper name. Unix-like systems implement pcap in the **libpcap library**.

>Monitoring software may use libpcap to capture network packets travelling over a computer network. The pcap API is written in C".

---
##Run the code
install `libcap` through apt,

    sudo apt install libcap

then compile each source `.cpp` file using the `-lpcap` flag

    g++ source_file.cpp -lpcap

----
## What you find over here
Some exercises (C/C++) related to the usage of the libpcap library.

###exercise 1
>print some metadata (*caplen*, *len*) about a packet sensed in the network.

###exercise 2
>implement a *remote procedure call* (RPC) that counts the number of packets sensed by the library. Note that this is a stateful computation.

###exercise 3
>recognize IP packets and display their source and destination addresses. Which of them carries TCP data?

----
## changelog
* 07-May-2019 first commit

