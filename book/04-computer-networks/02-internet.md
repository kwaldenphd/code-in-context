# The Internet

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=cbd745c0-1db8-40f8-a234-aef401865bf1">Computer Networks</a></td>
  </tr>
  </table>

## Key Concepts

**Internet**
- "The Internet is the global system of interconnected computer networks that uses the Internet protocol suite (TCP/IP) to communicate between networks and devices. It is a network of networks that consists of private, public, academic, business, and government networks of local to global scope, linked by a broad array of electronic, wireless, and optical networking technologies" ([Wikipedia](https://en.wikipedia.org/wiki/Internet))

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/LAN_WAN.svg?raw=true" width="500"></p>

**Wide Area Network (WAN)**
- "A wide area network (WAN) is a telecommunications network that extends over a large geographic area" ([Wikipedia](https://en.wikipedia.org/wiki/Wide_area_network))

**Internet Service Provider (ISP)**
- "An Internet service provider (ISP) is an organization that provides services for accessing, using, or participating in the Internet. ISPs can be organized in various forms, such as commercial, community-owned, non-profit, or otherwise privately owned" ([Wikipedia](https://en.wikipedia.org/wiki/Internet_service_provider))
- Common commercial ISPs in the U.S. include: AT&T, Verizon, Xfinity, Comcast, Windstream

**Packet Switching**
- "Packet switching is a method of grouping data that is transmitted over a digital network into packets. Packets are made of a header and a payload. Data in the header are used by networking hardware to direct the packet to its destination where the payload is extracted and used by application software. Packet switching is the primary basis for data communications in computer networks worldwide" ([Wikipedia](https://en.wikipedia.org/wiki/Packet_switching))

**User Datagram Protocol (UDP)**
- "In computer networking, the User Datagram Protocol (UDP) is one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network" ([Wikipedia](https://en.wikipedia.org/wiki/User_Datagram_Protocol))

**Transmission Control Protocol (TCP, or TCP/IP)**
- "The Transmission Control Protocol (TCP) is one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol (IP). Therefore, the entire suite is commonly referred to as TCP/IP" ([Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol))

**Internet Protocol (IP) Address**
- "An Internet Protocol address (IP address) is a numerical label such as 192.0.2.1 that is connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: network interface identification and location addressing" ([Wikipedia](https://en.wikipedia.org/wiki/IP_address))

**Port**
- "In computer networking, a port is a number assigned to uniquely identify a connection endpoint and to direct data to a specific service. At the software level, within an operating system, a port is a logical construct that identifies a specific process or a type of network service. A port is identified for each transport protocol and address combination by a 16-bit unsigned number, known as the port number. The most common transport protocols that use port numbers are the Transmission Control Protocol (TCP) and the User Datagram Protocol (UDP)" ([Wikipedia](https://en.wikipedia.org/wiki/Port_(computer_networking)))

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/DNS_Tree.png?raw=true" width="500"></p>

**Domain Name System (DNS)**
- "The Domain Name System (DNS) is the hierarchical and decentralized naming system used to identify computers reachable through the Internet or other Internet Protocol (IP) networks" ([Wikipedia](https://en.wikipedia.org/wiki/Domain_Name_System))

**Top-Level Domains (TLDs)**
- "A top-level domain (TLD) is one of the domains at the highest level in the hierarchical Domain Name System of the Internet after the root domain" ([Wikipedia]())
- Examples include: `.com`, `.org`, `.edu`

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/OSI_Model.png?raw=true" width="500"></p>

**Open System Interconnection (OSI) Model**
<ul><li>"The Open Systems Interconnection model (OSI model) is a conceptual model that describes the universal standard of communication functions of a telecommunication system or computing system, without any regard to the system's underlying internal technology and specific protocol suites" (<a href="https://en.wikipedia.org/wiki/OSI_model">Wikipedia</a>)</li>
 <li>Layers in the OSI Model:</li>
<ol type="1">
 <li value="7">Application</li>
 <li value="6">Presentation</li>
 <li value="5">Session</li>
 <li value="4">Transport</li>
 <li value="3">Network</li>
 <li value="2">Data link</li>
 <li value="1">Physical</li>
 </ol>
 </ul>

[Click here](https://github.com/kwaldenphd/internet/blob/main/key-concepts.md) for a full list of key concepts and definitions for this lab.

## Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSdcKWzqImWVevjXXv766giq0E3xwbdsEHV1OvkZmt4YIVhbag/viewform?usp=sf_link">The Internet Comprehension Check</a></td>
  </tr>
  </table>

## Application

Q3a: Let's use the `ipconfig` (Windows) or `ifconfig` (Mac) commands to learn more about your computer's network configuration. Open a terminal shell (`Terminal` or `Git BASH`). Type `ipconfig` (Windows) or `ifconfig` (Mac) followed by `Enter`/`Return`.

Q3b: Describe what you're seeing in the output. What information are these results providing about your network? How do they connect to concepts covered in this lab?

A couple resources that can help with understanding these results:
- `ipconfig`
  * LazyAdmin, "[How to use the ipconfig command and options explained](https://lazyadmin.nl/it/ipconfig-command/)"
  * Meridian Outpost, "[How to use ipconfig command with examples](https://www.meridianoutpost.com/resources/articles/command-line/ipconfig.php)"
- `ifconfig`
  * StackExchange, "[MacOS ifconfig output](https://superuser.com/questions/267660/can-someone-please-explain-ifconfig-output-in-mac-os-x)"
  * Oracle, "[Monitoring the interface with the `ifconfig` command](https://docs.oracle.com/cd/E19253-01/816-4554/ipconfig-141/index.html)"
