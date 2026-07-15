# Day 4: EC2 Deep Dive

EC2: Virtual server can be rent in AWS

Components of EC2:
- Name (eg: Cloud-Lab-Server)
- Operating System (Amazon Machine Image, AMI)
- Instance Type (cpu, ram)
- Key Pair (key to access server using ssh)
- Security Group (virtual firewall to the server)

All server has IP addresses. And Security Group acts as a door for the server and can only be open when SSH it with a Key Pair to access it.

Relationship between desktop pc and EC2:
- EC2 is a virtual computer that can be rented in AWS, whearas desktop pc sits locally on my desk
- Both have operating system, ram, and storage
- EC2 provides on-demand scalability and is managed remotely by the internet without physical hardware

