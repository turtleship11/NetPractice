# 🌐 NetPractice

*This project has been created as part of the 42 curriculum by jaeklee.*

---

## Description

NetPractice is a hands-on networking project designed to help students understand how computer networks operate.  
The project focuses on fixing broken network configurations using an interactive graphical interface.

The project consists of **10 progressively challenging levels**.  
Each level presents a **non-functional network diagram** that must be corrected by properly configuring networking components.

The main goal is to analyze the network, apply correct configurations, and ensure that communication between devices works as expected.

Through this project, students gain practical experience with:
- IP addressing
- Subnet masks
- Routing
- Switches
- OSI layers
- Network troubleshooting

Once a level is successfully completed, its configuration must be **exported and saved** for submission.

---

## Instructions

### Running the Training Interface

1. Download the NetPractice project files from the official source.
2. Extract the contents into a directory of your choice.
3. Open the extracted folder.
4. Launch the training interface by opening the `index.html` file in a web browser.

### Using the Interface

- Enter your **42 login** in the input field to personalize the session.
- The **Evaluation** tab allows you to generate randomized network configurations for additional practice.
- Each level displays a broken network setup that must be fixed.

### Completing the Levels

- There are **10 levels** in total.
- Depending on the level, you may need to:
  - Assign correct IP addresses
  - Choose appropriate subnet masks
  - Configure routers and default gateways

To validate a solution:
- Click **[Check again]** to verify the configuration.
- When the configuration is correct, click **[Get my config]** to export it.

### Exporting and Submission Requirements

- Export **one configuration file per level**
- A total of **10 exported configuration files** must be provided
- All configuration files **must be placed at the root of the Git repository**

The repository must also include a `README.md` file describing the project.

---

## Resources

### Networking Concepts Studied

This project covers the following networking fundamentals:

- **TCP/IP Addressing**  
  Each device requires a unique IP address to communicate within a network.

- **Subnet Masks and CIDR Notation**  
  Used to define network and host portions of an IP address and to divide networks into subnets.

- **Default Gateway**  
  Enables communication between different networks by forwarding traffic outside the local network.

- **Routers and Switches**  
  Routers connect multiple networks and forward packets, while switches connect devices within the same local network.

- **Routing Tables**  
  Define destination networks and next-hop paths to ensure correct packet forwarding.

- **OSI Model**  
  The seven-layer OSI model provides a structured way to understand how data moves through a network. By separating communication into distinct layers, it helps identify where failures occur (hardware, addressing, routing, or transport), making network analysis and troubleshooting more precise.

### References

- TCP/IP Networking Model documentation  
- Subnetting tutorials  
- NetPractice official documentation  
- OSI Model overview and networking fundamentals

### Use of AI Tools

AI tools were used strictly as **learning support** during the project to:
- Improve understanding of networking fundamentals
- Clarify subnetting calculations and routing behavior
- Validate reasoning while troubleshooting network configurations

No automated solutions were generated using AI tools.  
All configurations were designed, tested, and completed **manually**.

---

## Conclusion

NetPractice provides a strong foundation in computer networking through hands-on problem solving.  
It reinforces theoretical knowledge while developing practical skills in network configuration and troubleshooting.
