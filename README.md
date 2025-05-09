🌐 Project Title: Secure Site-to-Site WAN Configuration Using IPsec over GRE in EVE-NG

📘 Project Description:

This project demonstrates a secure, scalable, and emulated Site-to-Site VPN configuration between two branch routers using GRE over IPsec inside the EVE-NG network emulator. The setup enables dynamic routing via BGP over an encrypted GRE tunnel, simulating a real-world WAN scenario between two remote sites over the public internet.

🛠️ Project Environment (EVE-NG):

Emulator: EVE-NG Community/Pro Edition

Router Image: Cisco IOSv (e.g., IOSv 15.6)

Topology:

2 Cisco routers (Router A & B)

2 cloud or host nodes simulating LANs behind each router (optional)

Interfaces connected to a simulated public network for tunnel establishment
🔐 Key Technologies Used:

GRE: To encapsulate routed traffic and support dynamic protocols (like BGP)

IPsec (ESP): To encrypt GRE tunnel traffic over the internet

BGP: For dynamic route exchange over the GRE tunnel

Wireshark inside EVE-NG or external VM: For monitoring ESP packets

🎯 Purpose & Benefits:

Simulates real-world inter-branch VPN design

Teaches integration of encryption + dynamic routing

Reinforces practical knowledge of GRE, IPsec, and BGP

Demonstrates use of EVE-NG as a powerful lab platform

📁 Deliverables:

Complete configuration files (.txt or via EVE-NG export)

Topology screenshot or diagram

Wireshark capture file (optional)

Documentation (this description)
