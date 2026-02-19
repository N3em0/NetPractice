# NetPractice

*This project has been created as part of the 42 curriculum by egache.*

## Description
NetPractice is a networking project designed to teach the fundamentals of IP addressing and routing. The project consists of a series of 10 levels, each presenting a network topology with connectivity issues. The goal is to configure interfaces (IP addresses and subnet masks) and routing tables to ensure that all communication requirements (Goals) are met. It provides a hands-on approach to understanding how data travels through routers, switches, and different subnets.

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
* **TCP/IP Addressing**: Understanding IPv4 structure, including the difference between public and private address ranges and how to assign unique identifiers to hosts.
* **Subnet Masks**: Mastering the logic of dividing a network into smaller subnets using both Decimal (e.g. 255.255.255.0) and CIDR (e.g. /24) notations to define network and host portions.
* **Default Gateways**: Identifying the "exit point" for a local network, allowing packets to reach destinations outside their own subnet.
* **Routers**: These devices connect different networks together. It has an interface for each network it connects to.
* **Switches**: These devices connect multiple devices within the same local network (LAN).
* **OSI Model**: A conceptual framework consisting of 7 layers (Physical, Data Link, Network, Transport, Session, Presentation, and Application).
* **Routing Tables**: A routing table is a data table stored in a router or a network host that lists the routes to particular network destinations. A Destination (a network or a host) to a Next Hop (the IP of the next router).

### Use of Artificial Intelligence
* **Mask understanding**: Explaining the calculation of valid host ranges for specific masks.
* **Troubleshooting**: Analyzing specific error made during training exercices and understanding the concepts behind those.
* **Documentation**: Assisting in the structure of this README file.
