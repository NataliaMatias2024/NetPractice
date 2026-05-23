<h1 align="center">
    <img alt="NetPractice" width="200px" src="https://raw.githubusercontent.com/NataliaMatias2024/42-project-badges/main/badges/netpracticem.png">
</h1>

# 👩‍💻 NetPractice - @42SP
**Score:** 100/100 ✅

_This project has been created as part of the 42 curriculum by namatias._

This repository contains the solved configurations for the NetPractice project, developed as part of the curriculum at [42 São Paulo](https://www.42sp.org.br/).

## 🚀 Description

**NetPractice** is a practical project focused on the fundamentals of computer networking. 
The objective is to understand the inner workings of IP addressing, subnet masking, and packet routing through a web-based training interface, solving connectivity issues in small-scale networks.

## 🛠️ Instructions

### 1. Running the Training Interface
1. Download the project files from the official page on the 42 Intranet.
2. Extract the files into a directory of your choice.
3. Open the `index.html` file directly in your web browser to load the graphical environment.
4. Enter your intranet login (e.g., `namatias`) in the **Training** tab and click **Start!** to begin.
5. Use the **[Check again]** button to validate the modifications you made.

### 2. Exporting Configurations
* For each of the **10 levels** solved successfully, click the **[Get my config]** button available at the top of the interface.
* This button will download the configuration file corresponding to that specific level.

### 3. Submission Requirements
* The **10 exported configuration files** (one per level) must be placed directly at the **root** of the Git repository for evaluation.
* Make sure that all files were exported with your login correctly entered into the platform.

## 🧠 Key Concepts

### 🌐 TCP/IP Addressing & Subnet Masks
* **IP Address:** A unique identifier for each device within a network. In IPv4, it is split into the network portion and the host portion.
* **Subnet Mask:** Defines the boundaries and the size of a network. It determines which IPs belong to the same local scope and can communicate directly, mapping the mask both in decimal format (e.g., `255.255.255.0`) and CIDR notation (e.g., `/24`).
* **Reserved Addresses:** Every subnet has two reserved addresses that cannot be assigned to any host: the *Network Address* (the first IP in the range, representing the network itself) and the *Broadcast Address* (the last IP in the range, used to broadcast packets to all hosts on that network).

### 📡 Routing & Default Gateway
* **Default Gateway:** The IP address of the router interface that serves as an exit point for local hosts to send packets outside their own subnet.
* **Routing Tables:** Decision tables utilized by routers. The router analyzes the destination IP of a packet and finds the most specific matching route to forward it. If no exact match is found, it uses the default route (`0.0.0.0/0`).

### 🗺️ Network Devices
* **Routers:** Equipment responsible for interconnecting different networks and forwarding packets between them using routing tables.
* **Switches:** Devices that connect hosts within the same local network, distributing data traffic internally.

## 📚 Resources
- [Playlist YouTube - Subnetting Mastery](https://youtube.com/playlist?list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE&si=fAibshMaaLJgvs5O)
- [Geeks for Geeks - Role of Subnet Mask](https://www.geeksforgeeks.org/computer-networks/role-of-subnet-mask/)
- [Wikipedia - IPv4](https://pt.wikipedia.org/wiki/IPv4)

## 🤖 Artificial Intelligence (AI) Usage Statement
In compliance with the project guidelines, Artificial Intelligence tools were utilized during development with an exclusive focus on workflow optimization and conceptual validation:
* **Tasks Executed:** AI was applied as a productivity asset to structure and review the Markdown formatting and the grammar of this documentation file.
* **Validation Rigor:** No network configurations or level solutions were generated or copied from automated tools. All subnetting and routing logic was analyzed, calculated, and implemented in a strictly autoral manner.

## 💻 Hard Skills
`Networking` • `TCP/IP` • `Subnet Masking` • `IP Routing` • `Systems Infrastructure`
