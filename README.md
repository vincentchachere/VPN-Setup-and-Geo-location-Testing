<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1 align="center">VPN Setup and Geo-Location Testing</h1>

In this lab, you will set up a virtual machine in Azure, test internet geolocation from different regions, and configure a VPN to explore how it affects online location and browsing experiences. You will also learn to manage Azure resources and observe the impact of VPN connections on websites and services.

<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/6b91c617-7fb4-431a-b1de-a948749b5799">

<h1 align="center">Lab Overiew (Image above Explained)</h1>

1. Visit https:whatismyipaddress.com from our personal computer
2. Create a VM and connect via RDP
3. Access https:whatismyipaddress.com from the VM
4. Install and connect to a VPN on the VM
5. Revisit https:whatismyipaddress.com from the VPN

<h1 align="center">What is a VPN?</h1>

A **VPN (Virtual Private Network)** is a secure connection that encrypts your internet traffic and routes it through a server in another location, masking your IP address and making your online activities more private.  

**Example:** If you're in the U.S. and connect to a VPN server in Japan, websites will see your location as Japan, allowing access to region-specific content while keeping your data secure.

**VPN Metaphor Example:** A VPN is like a secure tunnel for your internet traffic. Imagine sending a letter through a courier that hides the sender’s address and replaces it with their own. The recipient sees the courier's address, not yours, keeping your identity private and secure.

## Environment and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN
- WhatIsMyIpAddress.com

## Operating systems Used

- Windows 10 (21H2)

## High-Level VPN Setup and Geo-Location Testing Steps

- Browse https:whatismyipaddress.com from your Personal Computer
- Browse https:whatismyipaddress.com from your Virtual Machine
- Install and connect to a VPN on the VM
- Revisit https:whatismyipaddress.com from the VPN
- Explore various websites using the VPN on the VM

## Configuration Steps

<details>

<summary>

### 🌐 Part 1: Create a Resource Group and Virtual Machine 

</summary>

Before creating our resources we'll **browse to https:whatismyipaddress.com** from our **personal computer** and take note of this in a text file.

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

</details>

<details>

<summary>

### 🌐 Part 2: Sign Up for ProtonVPN and Test the VPN Connection

</summary>

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

</details>

<details>

<summary>

### 🌐 Part 3: Clean Up Azure Resources

</summary>

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

<br>
<br>
<br>

<img width="800" alt="isolated" src="">

</details>

<h2 align="center">Final Thoughts</h2>

This lab demonstrated how VPNs can enhance online privacy, mask your location, and provide access to region-specific content. By setting up a virtual machine in Azure and testing a VPN, we explored the practical impacts of geolocation changes and gained hands-on experience with cloud resources and VPN configuration. These skills are essential for understanding network security, privacy, and global connectivity in today’s digital world.

If you haven’t done so yet, check out my other labs to further enhance your knowledge and skills. Explore topics like [Group Policy and Account Management](https://github.com/vincentchachere/Group-Policy-and-Managing-Accounts), [File Shares and Permissions](https://github.com/vincentchachere/Network-File-Shares-and-Permissions), and [DNS Resolution](https://github.com/vincentchachere/DNS-Fundamentals).

Thank you for following along with this project. Your time and effort in learning and implementing these concepts are greatly appreciated. 

☎️ For questions or to connect you can reach me at: www.linkedin.com/in/vincentchachere
