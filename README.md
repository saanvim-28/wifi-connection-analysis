# wifi-connection-analysis
An Analysis of the Effect of Public Wi-Fi Connections on User Security - tests the security level on public wifi networks when accessing encrypted (HTTPS) networks, compared to unencrypted (HTTP) networks, both with and without a Virtual Private Network (VPN).

Abstract:

This experiment tests the security of using a public wifi network when accessing encrypted
(HTTPS) networks, compared to unencrypted (HTTP) networks, both with and without a
Virtual Private Network (VPN). Public wifi networks, commonly accessed at cafes, public
libraries, restaurants, and malls, are often not secured, allowing those monitoring the
networks to retrieve sensitive information. However, the usage of VPNs, which encrypt and
obfuscate user data, are said to improve this risk. While HTTP connections were previously
more widespread, the majority of popular internet connections now use HTTPS, which use
encryption to protect user data.

Due to the widespread usage of public wifi networks, this experiment aims to approximate
the extent to which public wifi exposes vulnerabilities, whether they can be mediated by
strictly accessing HTTPS connections and/or using a VPN, or if public wifi usage should be
avoided entirely. To determine the level of security when using versus not using each of
these safety measures, Wireshark was used to capture and analyze network packets under
each of these conditions. By comparing the amount of compromised data obtained from each
website at different public wifi locations, the experiment determines whether it is safe to
connect to a public wifi network, and the extent to which you would need to use extra
precautions.

Sources:
(PDF) network traffic analysis and Intrusion Detection Using Packet Sniffer. (n.d.-b).
https://www.researchgate.net/publication/232625696_Network_Traffic_Analysis_and_Intrusio
n_Detection_Using_Packet_Sniffer
(PDF) potential threat analysis hypertext transfer protocol and secure hypertext transfer
protocol of public WIFI users (Batam case). (n.d.-c).
https://www.researchgate.net/publication/335474322_Potential_Threat_Analysis_Hypertext_
Transfer_Protocol_and_Secure_Hypertext_Transfer_Protocol_of_Public_WiFi_Users_Batam
_Case
Enhancing data protection provided by VPN connections over open WIFI networks | IEEE
conference publication | IEEE Xplore. (n.d.-a). https://ieeexplore.ieee.org/document/8923104
