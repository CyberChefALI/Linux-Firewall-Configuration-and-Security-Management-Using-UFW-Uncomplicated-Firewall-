# Linux-Firewall-Configuration-and-Security-Management-Using-UFW-Uncomplicated-Firewall-


## INTRODUCTION

Uncomplicated Firewall (UFW) is a user-friendly firewall management tool for Linux systems. It simplifies network traffic control by allowing administrators to configure rules for incoming and outgoing connections.

This project focuses on installing, configuring, and managing UFW to enhance Linux system security by controlling network access, allowing authorized traffic, blocking unwanted connections, and monitoring firewall activity.


## 	Lab Environment Setup

Kali Linux

## PROCESS

## STEP - 1  UFW Installation

 UFW installation is the process of adding the Uncomplicated Firewall package to a Linux system, enabling it as a persistent host-level firewall service, and applying initial access rules (such as allowing SSH) so network traffic is filtered automatically across reboots.
 
 <img width="1920" height="991" alt="kali-linux-2026 1-virtualbox-amd64  Running  - Oracle VirtualBox 14_11_2026 10_15_03" src="https://github.com/user-attachments/assets/096ad350-ea5a-4f9a-b80b-c63d15f3716a" />

## STEP - 2  Check firewall status

Checking firewall status means verifying whether your firewall is active or inactive and viewing the rules currently controlling network traffic.

<img width="1920" height="991" alt="kali-linux-2026 1-virtualbox-amd64  Running  - Oracle VirtualBox 14_11_2026 10_16_57" src="https://github.com/user-attachments/assets/c01e89c4-eef9-46fb-a76c-2162e793a260" />

## STEP - 3  	Enable & Disable firewall

Enabling and disabling the firewall turns active packet filtering on or off on your system—typically while keeping your saved rules intact for future use.

<img width="1920" height="991" alt="kali-linux-2026 1-virtualbox-amd64  Running  - Oracle VirtualBox 19_11_2026 13_53_26" src="https://github.com/user-attachments/assets/2c32190d-251f-444a-b852-aa674fcf99d3" /> 

<img width="1920" height="991" alt="Captures - File Explorer 14_11_2026 10_23_49" src="https://github.com/user-attachments/assets/0b120610-e2b4-4077-add6-bbec0645f469" />



## STEP - 4  	Allow SSH traffic

Allowing SSH traffic in UFW opens port 22/tcp (or a custom SSH port) so remote connections can reach your host when the firewall is active.

<img width="1920" height="991" alt="kali-linux-2026 1-virtualbox-amd64  Running  - Oracle VirtualBox 19_11_2026 13_53_26" src="https://github.com/user-attachments/assets/a843403f-42ba-465b-ba9b-3a82872a7c78" />
<img width="1920" height="991" alt="ubantu  Running  - Oracle VirtualBox 19_11_2026 13_53_05" src="https://github.com/user-attachments/assets/2bf9af09-6a89-45f5-8325-6e29297be999" />

## STEP - 5  	Block Telnet traffic

Blocking Telnet traffic in UFW closes TCP port 23 ( standard unencrypted Telnet port) so incoming or outgoing Telnet connection attempts are stopped by the firewall.
<img width="1920" height="991" alt="kali-linux-2026 1-virtualbox-amd64  Running  - Oracle VirtualBox 19_11_2026 13_58_25" src="https://github.com/user-attachments/assets/ed109363-4a8e-44f8-b855-2537ff767fc3" />

## STEP - 6  	Allow HTTP traffic 

Allowing HTTP traffic in UFW opens TCP port 80 so incoming web traffic can reach your server.

<img width="1920" height="991" alt="kali-linux-2026 1-virtualbox-amd64  Running  - Oracle VirtualBox 19_11_2026 15_50_09" src="https://github.com/user-attachments/assets/0163e94a-066e-451f-9873-49a2111408c5" />



