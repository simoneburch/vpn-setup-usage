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

- Step 1: Create a Virtual Machine in Azure
- Step 2: Log into a VM with Remote Desktop
- Step 3: Sign up for ProtonVPN, test your VPN connection
- Step 4: Log into the VPN, choose your server

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 1: Create a Virtual Machine in Azure - First, browse to https://whatismyaddress.com/ and make a note of this IP address (maybe in a separate text file). 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Resource Group.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Windows 10 Virtual Machine in another geographic location (try another country or continent).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to the VM with Remote Desktop.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Browse to https://whatismyaddress.com/ and make note of this different IP address (we'll compare these later).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2: Log into a VM with Remote Desktop
</p>
<br />

<p>
<img src="https://github.com/simoneburch/vpn-setup-usage/assets/152559137/9b55688d-cf98-4762-ab7e-12ee89a30017" height="50%" width="50%" alt="ProtonVPN sign up"/>
</p>
<p>
Step 3: On your computer, sign up for the free version of ProtonVPN https://account.protonvpn.com/signup?plan=free&language=en
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within your VM, download the ProtonVPN client.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4: Login to the VPN and choose a VPN server in yet another country or even continent. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Browse to https://whatismyaddress.com/ and take note of this third IP address (It should be different from the others you've already noted).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, you can browse to Google or Amazon. Try "McDonald's near me" or "Restaurants near me" and observe the website language or location. They should correspond to where you chose to create your VM and VPN. Hopefully in the native language of the country you chose. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
You should also be able to see the three different IP addresses in your notes and realize that you're essentially using a computer in three different locations around the world. :)
</p>
<br />
