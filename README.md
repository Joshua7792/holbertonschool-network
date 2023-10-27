![GIF](https://media.giphy.com/media/3ohhwD3SWu8nvJww7u/giphy.gif)

# Network Basics

This project focuses on understanding fundamental concepts related to computer networks, protocols, and network communication. It includes tasks that require creating Bash scripts to work with network-related functionalities.

## General

- **Editors:** Vi, Vim, Emacs
- **Operating System:** Ubuntu 20.04 LTS
- **File Endings:** All files should end with a newline
- **Mandatory README:** A README.md file must be present at the root of the project folder
- **Executable Scripts:** All Bash script files must be executable
- **Shellcheck Validation:** Bash scripts must pass Shellcheck without errors
- **Script Header:** The first line of all Bash scripts should be `#!/usr/bin/env bash`
- **Comments:** The second line of all Bash scripts should include a comment explaining the purpose of the script

## More Info

The OSI (Open Systems Interconnection) model is a conceptual framework that describes the layered communication and design of computer networks. It defines different layers of network communication, from the physical transmission layer to the application-specific layer. Tasks in this project focus on understanding the Transport and Network layers, as well as MAC and IP addresses.

## Tasks

### 0. OSI Model

- **Description:** This task introduces the OSI model, which is a conceptual framework for understanding network communication.
- **Questions:**
  1. What is the OSI model?
  2. How is the OSI model organized?
- **File:** [0-OSI_model](basics_0/0-OSI_model)

### 1. Types of Network

- **Description:** This task explores different types of networks, including LAN, WAN, and the Internet.
- **Questions:**
  1. What type of network is a computer in a local area connected to?
  2. What type of network could connect offices in different buildings?
  3. What network is used when browsing a website from a smartphone not connected to Wi-Fi?
- **File:** [1-types_of_network](basics_0/1-types_of_network)

### 2. MAC and IP Address

- **Description:** This task involves understanding MAC (Media Access Control) and IP (Internet Protocol) addresses.
- **Questions:**
  1. What is a MAC address?
  2. What is an IP address?
- **File:** [2-MAC_and_IP_address](basics_0/2-MAC_and_IP_address)

### 3. UDP and TCP

- **Description:** This task focuses on UDP (User Datagram Protocol) and TCP (Transmission Control Protocol) and their characteristics.
- **Questions:**
  1. Characteristics of TCP
  2. Characteristics of UDP
  3. Questions asked by the TCP worker
- **File:** [3-UDP_and_TCP](basics_0/3-UDP_and_TCP)

### 4. TCP and UDP Ports

- **Description:** In this task, you'll write a Bash script that displays listening ports.
- **Requirements:**
  - Display only listening sockets
  - Show the PID and program name for each socket
- **File:** [4-TCP_and_UDP_ports](basics_0/4-TCP_and_UDP_ports)

### 5. Is the Host on the Network

- **Description:** Write a Bash script to ping an IP address passed as an argument.
- **Requirements:**
  - Accept an IP address as an argument
  - Display usage information if no argument is provided
  - Ping the IP address five times
- **File:** [5-is_the_host_on_the_network](basics_0/5-is_the_host_on_the_network)
