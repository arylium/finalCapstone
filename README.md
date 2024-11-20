# The Capstone Project

This project is about creating a case study document that demonstrates how to perform a security assessment on a Linux system. The project involves using tools such as Nmap and Metasploit to scan for open ports, identify services with backdoor vulnerabilities, and exploit them to gain root access. The project also requires extracting the password file from the target system and analyzing it for weak passwords.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Installation

To install the required tools for this project, follow these steps:
- Download the VM basicpentesting by Josiah Pierce https://www.vulnhub.com/entry/basic-pentesting-1,216/
- Install Nmap from https://nmap.org/download.html
- Install Metasploit from https://www.metasploit.com/download
- Install a Linux virtual machine (VM) from https://www.osboxes.org/linux/
- Configure the network settings of the VM to allow port forwarding and access from the host machine

## Usage

To use this project, follow these steps:

- Install VM
- Install Kali Linux
- Install VM basic pentesting in your VM software
- Run Nmap on the target IP address to scan for open ports and services
- Use the search option in Metasploit to find a backdoor vulnerability that affects one of the services running on the target system
- Set up a payload and a handler in Metasploit to exploit the backdoor vulnerability and get a reverse shell
- Use the shell to navigate to the /etc directory and copy the passwd file to your local machine
- Use a tool such as John the Ripper or Hashcat to crack the passwords in the passwd file

## Screenshots

Screenshots of a walkthrough on how to do it is provided in the PDF file.

## Credits

This project was created by:

- James Watson (mrjwatsonbet@gmail.com)
- HyperionDev https://www.hyperiondev.com/
