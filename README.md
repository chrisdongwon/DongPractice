*This project has been created as part of the 42 curriculum by cwon.*

# NetPractice

## Description

**NetPractice** is a networking training project from the 42 curriculum designed to build a strong foundation in computer networking concepts. The goal of the project is to correctly configure network setups by applying theoretical knowledge of IP addressing, subnet masks, routing, and communication rules.

The project consists of multiple interactive levels where the student must analyze a network topology and assign correct configurations so that hosts can communicate as required. No programming is involved; the focus is entirely on network logic, protocol understanding, and binary reasoning.

---

## Instructions

### Running the training interface

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd NetPractice
   ```

2. Open the training interface:
   - Locate the `index.html` file provided by the project.
   - Open it using a web browser (Chrome or Chromium recommended):
     - Double-click the file, or
     - Right-click → Open with Browser

3. The NetPractice interface will open and allow you to navigate through the different levels.

### Completing levels

Each level displays a network diagram containing hosts, routers, and switches. You must assign the correct values such as IP addresses, subnet masks, and default gateways. A level is validated once all required network communications are successful.

### Exporting configurations

After successfully completing a level, use the **Export** button in the interface to generate a configuration file. Rename each file clearly according to its level (for example: `level1.json`).


### Submission requirements

- **10 exported configuration files** must be submitted  
- **One configuration file per level**  
- All files must be placed **at the root of the repository**  
- No additional files or directories should be included  

Expected repository structure:

```
NetPractice/
├── level1.json
├── level2.json
├── level3.json
├── level4.json
├── level5.json
├── level6.json
├── level7.json
├── level8.json
├── level9.json
├── level10.json
└── README.md
```

---

## Resources

### Networking concepts studied

This project focuses on the following networking fundamentals:

- TCP/IP addressing
- IPv4 structure and binary representation
- Subnet masks and CIDR notation
- Network address and broadcast address
- Default gateway
- Routers and routing between networks
- Switches and local network communication
- OSI model layers
- Direct communication vs routed communication
- Network segmentation and subnetting

---

### References

- Computer Networking: A Top-Down Approach by James F. Kurose & Keith W. Ross
- Wikipedia articles on IP addressing, subnet masks, CIDR notation, and the OSI model
- 42 NetPractice subject PDF

---

### Use of AI tools

AI tools were used strictly as a learning and documentation aid, not to automatically generate solutions.

AI was used for:
- Clarifying networking theory (IP addressing, subnet masks, routing logic)
- Explaining binary operations and subnet calculations
- Improving conceptual understanding of NetPractice exercises
- Writing and structuring this README documentation

All network configurations and level solutions were completed manually by the student, in compliance with 42’s academic integrity rules.

---

## Notes

This project does not require compilation and does not involve any programming language. Success depends entirely on understanding networking concepts rather than trial and error.

