# CCNA
CCNA Notes

## TCP/IP

### History
Originally conceived by the US DOD as a means to create an open networking model to replace various vendors proprietary models. This would allow more networks to be able to communicate with each other with less complications. It was competing with the International Organization for Standardization's (ISO) OSI Networking model, defined in [ISO 7498](https://www.iso.org/standard/20269.html)/[ITU-T X.200](https://www.itu.int/rec/T-REC-X.200-199407-I/)

### Technical Specification
The TCP/IP model is broadly defined over [RFC 1122](https://datatracker.ietf.org/doc/html/rfc1122)/[RFC 1123](https://datatracker.ietf.org/doc/html/rfc1123) with a tutorial/example data flow given in [RFC 1180](https://datatracker.ietf.org/doc/html/rfc1180). It uses various other protocols defined in other [RFC's](https://en.wikipedia.org/wiki/Request_for_Comments) such as [TCP](https://datatracker.ietf.org/doc/html/rfc793), [UDP](https://datatracker.ietf.org/doc/html/rfc768), and [IP](https://datatracker.ietf.org/doc/html/rfc791). As well it uses protocols defined by other standards bodies such as 802.3 (Ethernet) and 802.11 (Wireless LAN) both defined by the [IEEE](https://en.wikipedia.org/wiki/Institute_of_Electrical_and_Electronics_Engineers)

### Reference Model

Traditonally TCP/IP was defined as [4 Layer Model](https://en.wikipedia.org/wiki/Internet_protocol_suite#Layer_names_and_number_of_layers_in_the_literature), but more recently is being referenced to as a 5 Layer Model [^CiscoPress]. This likely to make it easier to see the comparison with the OSI Model.

![tcp_ip_4v5.svg](https://github.com/johnsoga/CCNA/blob/main/assests/tcp_ip_4v5.svg)

### Connectivity

![tcp_ip_encapsulation.svg](https://github.com/johnsoga/CCNA/blob/main/assests/tcp_ip_encapsulation.svg)

[^CiscoPress]: Odom, W., 2020. CCNA 200-301 official cert guide. San Jose, CA: Cisco Press.
