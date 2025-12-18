NetPractice

*This project was completed as part of the 42 curriculum by jaeklee.*

Project Overview

NetPractice is a hands-on networking project designed to help students understand how computer networks operate. The project consists of solving networking issues using an interactive graphical interface. Each exercise presents a broken network setup that must be fixed by correctly configuring networking components.

There are 10 levels, each increasing in difficulty. At every level, the goal is to analyze the network diagram, apply proper configurations, and ensure that communication between devices works as expected.

Through this project, students gain practical experience with key networking topics such as IP addressing, subnet masks, routing, switches, OSI layers, and network troubleshooting. Once a level is successfully completed, its configuration must be exported and saved for submission.

How to Use the Project
Downloading the Project

Download the project files from the official source.

Extract the contents into a directory of your choice.

Launching the Training Interface

Open the extracted folder.

Launch the project by opening the index.html file in a web browser.

Working with the Interface

Enter your 42 login in the input field to personalize your setup.

The Evaluation tab allows you to generate randomized configurations for additional practice.

Each level displays a non-working network diagram that must be corrected.

Completing the Levels

There are 10 levels in total.

Each level provides specific objectives, such as:

Assigning correct IP addresses

Choosing appropriate subnet masks

Configuring routers and gateways

Use the [Check again] button to verify your solution.

When the configuration is valid, click [Get my config] to export it.

Exporting Configurations

Export one configuration file per level.

Make sure all 10 configuration files are saved at the root of your Git repository.

Submission Guidelines

To submit the project successfully:

Include 10 exported configuration files, one for each level, in the root directory.

Add a README.md file describing the project and its purpose.

Networking Concepts Covered
IP Addressing (TCP/IP)

Every device connected to a network requires a unique IP address to communicate. IPv4 addresses (such as 192.168.0.1) allow devices to locate and exchange data with each other. Devices on the same network can communicate directly, while communication between different networks must pass through a router.

Subnet Masks

A subnet mask defines which part of an IP address represents the network and which part identifies the host. In NetPractice, subnetting is essential for:

Determining which devices belong to the same network

Dividing networks into smaller subnets

Preventing address conflicts and overlapping networks

Subnet masks are often expressed using CIDR notation (for example /24, /28).

Default Gateway

The default gateway is the device responsible for forwarding traffic outside the local network. When a host needs to communicate with a different network, it sends packets to the gateway—typically a router. Without a correct default gateway, external communication is impossible.

Routers

Routers are used to interconnect separate networks. Each router interface belongs to a distinct network and helps forward data between them. In this project, routers are configured to:

Connect multiple networks

Forward packets correctly

Use routing information to determine the best path

Switches

Switches operate within a local network and connect multiple devices together. They enable communication between devices that share the same network and subnet. Switches do not perform routing and cannot connect different networks.

Routing Tables

A routing table acts as a reference map for a device, showing:

The destination network

The next hop to reach that destination

Proper routing tables are necessary to ensure data can travel to and from all networks without interruption.

OSI Model Overview

The OSI model explains how network communication works by dividing it into seven layers:

Physical Layer – Manages hardware components such as cables and signals.

Data Link Layer – Handles MAC addressing, error detection, and switching.

Network Layer – Responsible for IP addressing, subnetting, and routing.

Transport Layer – Ensures reliable or fast data transmission using TCP or UDP.

Session Layer – Manages communication sessions between devices.

Presentation Layer – Formats, encrypts, and compresses data.

Application Layer – Provides network services to applications like browsers and email clients.

Understanding these layers helps identify where network communication problems occur.

References

TCP/IP Networking Model

Subnetting Basics

NetPractice Documentation

OSI Model Overview

Use of AI Tools

AI tools were used strictly as a learning support to:

Improve understanding of networking fundamentals

Clarify subnetting calculations and routing behavior

Validate reasoning during problem-solving

No automated solutions were generated, and all configurations were completed manually.

If you want, I can also:

Shorten this version

Make it more “42-style” minimal

Adjust tone (more technical / more beginner-friendly)

Format it exactly for Markdown submission

Just tell me 👍
