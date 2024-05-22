<p align="center">
<img src="https://i.imgur.com/xuPnuuE.png" height="80%" width="80%" alt="VPN"/>
</p>

<h1>Virtual Private Networks</h1>
A virtual private network or VPN is a service that protects your privacy by masking your internet connection. There are a lot of VPN applications out there and they all operate the same way. A VPN connects your actual IP address to a VPN server and encrypts it. 

<p></p>

In this tutorial, I will show you ProtonVPN. You can download it and use it for free. You can also upgrade the services for a fee.

<p></p>

[ProtonVPN](https://www.protonvpn.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Virtual Machines
- Microsoft Remote Desktop
- ProtonVPN

<h2>Steps</h2>

<h3>Create a virtual machines</h3>

First step is to create a virtual machine (VM) in Azure. If you don't know how to do that, you can follow my tutorial. Ensure that you create a VM that's in a different geographic region than where you're located. I chose East US 2. 

<p></p>

[Tutorial](https://github.com/klcarpio/Create-an-Azure-Account-and-Deploy-a-Virtual-Machine)

<p>
<img src="https://i.imgur.com/ZgmrcLR.png" height="80%" width="80%" alt="1."/>
</p>

<p>
<img src="https://i.imgur.com/B6GSnkX.png" height="80%" width="80%" alt="2."/>
</p>

Once you create your VM, open it using Microsoft Remote Desktop. Then download and install ProtonVPN to the VM. 

<p></p>

Then open a new web browser and visit [WhatsMyIPAddress](https://whatismyipaddress.com).

<p></p>

Take note of the IP address and where it's located. The IP address for my VM was 20.22.241.63 and located in Boydton, Virginia. 

<p>
<img src="https://i.imgur.com/EbY7tMr.png" height="80%" width="80%" alt="3."/>
</p>

<p>
<img src="https://i.imgur.com/MROkGvr.png" height="80%" width="80%" alt="4."/>
</p>

<p>
<img src="https://i.imgur.com/xrZGmlK.png" height="80%" width="80%" alt="5."/>
</p>

Once ProtonVPN is downloaded and installed, open the application. Then make a connection. I chose to connect to The Netherlands. 

<p>
<img src="https://i.imgur.com/3qKOCYR.png" height="80%" width="80%" alt="6."/>
</p>

<p>
<img src="https://i.imgur.com/CAr2y5D.png" height="80%" width="80%" alt="7."/>
</p>

Once you're connected to ProtonVPN, go back to WhatIsMyAddress and look at the changes. Notice that the IP address is different and the location. (169.150.196.137 im Amsterdam, The Netherlands).

<p>
<img src="https://i.imgur.com/dgR3JD9.png" height="80%" width="80%" alt="8."/>
</p>

Congratulations, you now know what a VPN is and how it works! You also have ProtonVPN for free unless you want to upgrade. VPNs are vital if you want to protect your data. Especially if you are doing work in another country or in public, it's probably a good idea to use a VPN. Thank you for checking out my tutorial!


**REMEMBER TO DELETE YOUR RESOURCES ONCE YOU ARE DONE WITH THE LAB!**
