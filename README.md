# Setting up Pi-Hole on a RaspberryPi

## Objective
The objective of this project is to enhance network security and privacy by implementing Pi-hole as a network-wide ad blocker on a Raspberry Pi. It aims to block intrusive advertisements and trackers across all connected devices, improving user experience and protecting privacy. Additionally, Pi-hole will be used to block known malicious domains, adding an extra layer of security against malware and phishing attacks. By eliminating unwanted ad content, the project seeks to reduce bandwidth usage and improve web page loading times, leading to more efficient network performance. The project will provide a centralized interface for managing and monitoring DNS requests, simplifying network administration and customization. It will also demonstrate the practical application of DNS-based ad-blocking technology, offering a hands-on learning experience in network security. Ultimately, the project will highlight the importance of customizable DNS-based ad-blocking in modern cybersecurity practices.

### Skills Learned
- Setting up and configuring network devices, including routers and Raspberry Pi, to implement a network-wide ad blocker.
- Installing and managing software (Pi-hole) on a Raspberry Pi, including updating and maintaining the system.
- Understanding and configuring DNS settings to route and block specific domains, enhancing network security and performance.
- Implementing measures to protect against malware and phishing by blocking malicious domains and enhancing privacy through ad blocking.
- Navigating and using Pi-hole's web-based dashboard for monitoring network activity, managing block lists, and customizing DNS configurations.
- Planning, executing, and documenting a technical project from start to finish, including setting objectives, configuring systems, and evaluating outcomes.
- Troubleshooting network and system issues, resolving configuration problems, and optimizing performance


### Tools Used
- A small, affordable computer used to host the Pi-hole software and serve as a dedicated DNS server for the network.
- A network-wide ad blocker that operates as a DNS sinkhole, blocking advertisements and tracking domains.
- The operating system installed on the Raspberry Pi, provides a platform to run Pi-hole and other necessary software.
- Used for installing software, updating packages, and configuring network settings on the Raspberry Pi.
- Configured to direct DNS traffic through the Raspberry Pi running Pi-hole, ensuring network-wide ad blocking.
- Accessing the Pi-hole admin interface for managing settings, viewing logs, and monitoring DNS queries.

## Steps
- Prepare Your Raspberry Pi with a power supply, SD card (at least 8GB), keyboard, mouse, and monitor.
- Download Raspberry Pi OS <a href="https://www.raspberrypi.com/software/">HERE</a>. Then install Raspberry Pi OS on your SD card. Follow the directions on the website to install the OS.
- Time to update and upgrade the apps on Raspberry Pi. Open the terminal and type:
- sudo apt update && sudo apt upgrade -y
- This will update and upgrade all the apps
- Now it's time to set a static IP address, so Pi-hole can have the same IP without it changing.
![Screenshot 2024-05-30 192749](https://github.com/iAmRobstar/Setting-Up-Pi-hole-on-a-Raspberry-Pi/assets/171294322/42406c48-6d86-45c7-ba3b-b8ea20537557)

