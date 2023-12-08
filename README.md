<p align="center">
<img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/2c91b36f-a4bb-4112-8e97-825ada2d6e8b" alt="VPN Usage"/>
</p>

<h1>Exploring Virtual Private Networks</h1>
In this tutorial, we will set up a VPN using ProtonVPN's free version, run some exercises, and observe the changes in our IP address to better understand how a VPN works. <br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: Exploring the effects of a VPN on your Browsing Experience](https://www.youtube.com) -->


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

You need to already have a subscription created in the Azure portal: https://portal.azure.com/#home

- Step 1: Create a Virtual Machine in Azure
- Step 2: Log in to a VM with Remote Desktop
- Step 3: Sign up for ProtonVPN, test your VPN connection
- Step 4: Log in to the VPN, choose your server

<h2>Actions and Observations</h2>

<p align="center">
<img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/c749e8e0-7e4c-4b70-99aa-c4c6bb7d8951" height="15%" width="30%" alt="WhatisMyIP Image"/>
</p>
<p>
First, browse to https://whatismyaddress.com/ and record this IPv4 address (maybe in a separate text file). 
</p>
<br />

<br />


<p>
  <img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/e3aeaec9-4c25-40a4-a49c-781b6cb7175d" height="30%" width="40%" alt="Resource Groups img"/> 
In the Azure portal, create a Resource Group. 
</p>
<br />

<br />

<p>
  <img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/eae39aa2-f3e2-4ccd-be78-d24b2bfef065" height="30%" width="40%" alt="Azure VM img"/> 
In that Resource Group, create a Windows 10 Virtual Machine in a different geographic region than your own (try another country or continent). Copy your VM's public IP address.
</p>
<br />

<br />

<p>
<img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/15982ef5-9efe-4f66-827e-d4d7f6e84c56" height="50%" width="50%" alt="remote desktop image"/>
</p>
<p>
Use the public IP of your VM to log in via Remote Desktop. The credentials you created when setting up your VM will be the ones you use to log in to it. From within the VM, browse to https://whatismyaddress.com/ and make note of this different IP address (we'll compare these later).
</p>
<br />

<p>
<img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/9b55688d-cf98-4762-ab7e-12ee89a30017" height="50%" width="50%" alt="ProtonVPN sign up"/>
</p>
<p>
On your computer, sign up for the free version of ProtonVPN https://account.protonvpn.com/signup?plan=free&language=en
</p>
<br />

<p>
From within your VM, download the ProtonVPN client from the website.
</p>
<br />

<p>
<img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/bfce6109-1344-4738-be4d-f8bf677a7f2e" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to the VPN and choose a VPN server in another country or continent. Browse to https://whatismyaddress.com/ and take note of this third IP address (It should be different from the others you've already noted).
</p>
<br />

<p>
Now, you can browse to Google or Amazon. Try "McDonald's near me" or "Restaurants near me" and observe the website language or location. They should correspond to where you chose to create your VM and VPN. Hopefully, in the native language of the country you chose. 
</p>
<br />

<p align="center">
<img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/a27c65f3-24d0-47f3-b1d7-3e8d8fbd9703" height="60%" width="60%" alt="Three IPs"/>
</p>
<p>
You should also be able to see the three different IP addresses in your notes and realize that you're essentially using a computer in three different locations around the world from your PC. :)
</p>
<br />
