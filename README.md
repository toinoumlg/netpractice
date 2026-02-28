*This project has been created as part of the 42 curriculum by amalangu.*

# NetPractice

## Description

NetPractice is a networking training project from the 42 curriculum designed to build a solid understanding of fundamental networking concepts through practical exercises.

The project consists of 10 progressively complex levels where small network configurations must be corrected in order to allow proper communication between devices. Each level requires careful configuration of IP addresses, subnet masks, and default gateways.

The primary goal of NetPractice is to fully understand how networks function at a foundational level by applying concepts such as:

- TCP/IP addressing
- Subnet masks and CIDR notation
- Default gateways
- Routing between networks
- Routers and switches
- OSI model layers
- Network segmentation

This project focuses on reasoning and understanding rather than memorization, ensuring strong networking fundamentals.

---

## Instructions

### Running the Training Interface

NetPractice is accessed through the provided web-based interface.

If your campus provides a local version, you can launch it using:

```bash
./run.sh
```
After running the script, open the displayed local address in your web browser.

## Solving the Levels

### Solving the Levels

Each level presents a broken or incomplete network diagram.

To complete a level:

1. Configure the correct IP addresses.
2. Apply appropriate subnet masks.
3. Set correct default gateways where required.
4. Ensure all required devices can communicate successfully.
5. Validate the configuration using the interface’s validation system.

All configurations must be logically consistent with networking rules.

---


### Exporting Configurations

After successfully completing a level:

1. Click the **Get my config** button in the interface.
2. Download the configuration file.
3. Ensure the file name clearly corresponds to its level (for example: `level1.json`, `level2.json`, etc.).
4. Place the exported file at the **root of the repository**.

---

### Submission Requirements

For evaluation, the repository must contain:

- This `README.md` file at the root.
- One exported file per level (Levels 1 through 10) at the root also.

---

## Networking Concepts Covered

During this project, the following networking concepts were studied and applied:

- IPv4 addressing
- Public and private IP ranges
- Subnet masks
- CIDR notation (/24, /30, etc.)
- Network and broadcast addresses
- Default gateways
- Role of routers
- Role of switches
- Basic routing logic

These concepts are fundamental to understanding how devices communicate across networks.

---

## Resources

### Documentation & Learning References

- [Beej's Guide to network](https://beej.us/guide/bgnet0/)
- [Classless Inter-Domain Routing](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing)
- [Networking Fundamentals - Cisco](https://www.cisco.com/c/dam/global/fi_fi/assets/docs/SMB_University_120307_Networking_Fundamentals.pdf)
- [NetPractice: An Intro to IP Addresses and Subnets](https://www.youtube.com/watch?v=HQUw0CfQWAM&t=1097s) 
- [Guide to NetPractice - lpaube](https://github.com/lpaube/NetPractice)
- [NetPractice basic explaination - tblaase](https://github.com/tblaase/Net_Practice)

These references were used to better understand IP addressing, subnetting logic, and routing principles.

---

### Networking Concepts Studied

This project specifically focused on understanding:

- TCP/IP addressing structure
- Subnet mask calculation
- Default gateway functionality
- Router behavior
- Switch behavior
- OSI layers
- Communication between separate networks

---

---

### AI Usage Disclosure

Artificial Intelligence tools were used responsibly during this project for:

- Structuring and formatting documentation (README file)

All network configurations were manually analyzed and completed to ensure full understanding of the logic behind each solution.

---

## Author

amalangu  
42 Student


