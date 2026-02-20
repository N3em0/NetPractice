# NetPractice

*This project has been created as part of the 42 curriculum by egache.*

## Description
NetPractice is a networking project designed to teach the fundamentals of IP addressing and routing. The project consists of a series of 10 levels, each presenting a network system with connectivity issues. The goal is to configure IP addresses, subnet masks and routing tables to ensure that all goals are met. It provides an understanding to how data travels through routers, switches, and different subnets.

## Instructions

### Running the Training Interface
To launch the NetPractice interface and start solving the levels:
1. Download and extract the **net_practice.1.9.tgz** from the project page
2. Open your terminal in the project directory.
3. Execute the provided script:
```sh run.sh```

### Exporting and Submission Requirements
Once a level is successfully completed:
* Click on the "Get my config" button.
* Save the resulting configuration file at the root of your repository.

To validate the project, you must:
* Solve all 10 levels.
* Place all 10 exported configuration files at the root of your repository.
* The files should be named from **level_1** to **level_10**.

## Resources

### Networking Concepts Studied
This project required an understanding of the following concepts:
* **TCP/IP Addressing**: TCP/IP addressing is a system that assigns unique identifiers, called IP addresses, to devices on a network to enable communication over the Internet or private networks. These addresses are used to identify the network and the specific host within that network.
* **Subnet Masks**: Subnet Masks are used to divide a network into smaller subnets using both Decimal (e.g. 255.255.255.0) and CIDR (e.g. /24).
* **Default Gateways**: A default gateway connects two or more networks and routes traffic between them. This allows devices on the local network to communicate with resources on external networks.
* **Routers**: Routers connect different networks together. It has an interface for each network it connects to.
* **Switches**: Switches connect multiple devices within the same local network (LAN).
* **OSI Model**: OSI Model is a conceptual model consisting of 7 layers (Physical, Data Link, Network, Transport, Session, Presentation, and Application).
* **Routing Tables**: A routing table is a data table stored in a router or a network host that lists the routes to particular network destinations. A Destination (a network or a host) to a Next Hop (the IP of the next router).

### Use of Artificial Intelligence
* **Mask understanding**: Explaining the calculation of valid host ranges for specific masks.
* **Troubleshooting**: Analyzing specific error made during training exercices and understanding the concepts behind those.
* **Documentation**: Assisting in the structure of this README file.
