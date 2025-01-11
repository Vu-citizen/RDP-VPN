# Vitual Private Network (VPN)
<p align="center">
<img src="https://i.imgur.com/MntON5Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/e5382856-c754-4052-9059-141594eeeb98" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<h1>VPN - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation ousing a VPN.<br />

<h2>Environments and Technologies Used</h2>

- VPN (Proton VPN)(NordVPN)
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>STEPS INCLUDED</h2>

- STEP 1 - Locate Local IP
- STEP 2 - Setting Up VM Using Azure
- STEP 3 - Locating IP Through VM (France)
- STEP 4 - Connecting to VPN Through VM
- STEP 5 - Locating IP Through VPN (Japan)

<h2>Installation Steps</h2>

STEP 1 - Locate your own personal IP address by going to "www.whatismyipaddress.com" which will be able to show you your local IP address. We will use this later as well. See EXAMPLE 1A below.

EXAMPLE 1A
<p>
<img src="![image](https://github.com/user-attachments/assets/caf25865-660f-4e69-8e46-b8b48cf433c7)
)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Next we will set up a virtual machine on Azure. 
  
</p>
<br />

STEP 2 - Go to www.portal.azure.com and find Virtual Machines. (Create a free account with $200 if you need to). See Example 2A looking at the Virtual Machine set up page. 

EXAMPLE 2A
<p>
<img src="![image](https://github.com/user-attachments/assets/4ea3c1ff-de81-45e7-8463-76d5c29d4050)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Creating the Virtual Machine on Example 2B the VM as “any name you want ” and select that for the REGION as well. Ensure the other items are selected as shown in EXAMPLE 2B & 2C.

EXAMPLE 2B
<p>
<img src="![image](https://github.com/user-attachments/assets/ad64ef82-489b-4946-89e8-5639b5ae517e)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

For the Username and Password you can create your custom information, just record it personally.
  
</p>
<br />

EXAMPLE 2C
<p>
<img src="![image](https://github.com/user-attachments/assets/9998221b-10b5-40df-bd27-026247dffb5a)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Select the “Networking” tab towards the top of the page and view EXAMPLE 2D inputs to match. 
  
</p>
<br />

EXAMPLE 2D
<p>
<img src="![image](https://github.com/user-attachments/assets/31f4627f-43fe-4c66-9dde-83a6af802a84)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Then select “Review and Create”, once it passes validation select “Create” at the bottom. 
  
</p>
<br />

NEXT: At the Virtual Machine we find that the IP to the Virtual Machine is “20.216.176.18”. See EXAMPLE 2E

EXAMPLE 2E

<p>
<img src="![image](https://github.com/user-attachments/assets/e778a11f-588b-4d5d-ac56-d065d40cd2d8)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


STEP 3 – Log Into the VM and Find IP Address
<p>
Now that we have set up the Virtual Machine we will connecting to it using the application “Remote Desktop Connection” (EXAMPLE 3A) and input the IP address for the VM that we located in EXAMPLE 2E and then input the set credentials we set when creating the VM (see EXAMPLE 3B). Once logged in, we will open the web browser and again look up www.whatismyipaddress.com (EXAMPLE 3C).

  
</p>
<br />
EXAMPLE 3A
<p>
<img src="![image](https://github.com/user-attachments/assets/24443bcc-ddc1-4878-91f0-0fe4b4bfd354)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="![image](![image](https://github.com/user-attachments/assets/da1431a5-93a9-404d-9acd-ccf2e78a0261)
)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  
</p>
<br />

EXAMPLE 3B
<p>
<img src="![image](https://github.com/user-attachments/assets/982643b7-1e66-44be-b979-b75407b871df)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

When we look up the IP address for this VM through www.whatismyipaddress.com we see that this VM is showing the location for France (EXAMPLE 3C).
  
</p>
<br />

EXAMPLE 3C
<p>
<img src="![image](https://github.com/user-attachments/assets/c8f99503-c0d5-4e8a-b7a4-3d1f580d4993)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

STEP 4 – CONNECTING TO VPN (Free Version)

Using the local computer go to protonvpn.com and create a free account (if you use the VM then French will display on your browser, so use local computer desktop). Once you are logged into your account, copy the URL from the Proton VPN website (EXAMPLE 4A) and then paste the URL to the VM web browser. 

  
</p>
<br />

EXAMPLE 4A
<p>
<img src="https://i.imgur.com/orO2O5y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Once you have logged into your Proton VPN account on the VM, you will select “Downloads” and choose to download the “Windows” versionSee EXAMPLE 4B2. Once the application Proton VPN is installed we will log in using the credentials we used when setting up a free account on Proton VPN. Then connect to the VPN through the installed app. See EXAMPLE 4B1 when this steps are completed.  

EXAMPLE 4B
<p>
<img src="hhttps://github.com/user-attachments/assets/f64b1fec-8fd5-4895-8723-29a851dadea5" height="80%" width="80%" />
</p>
<p>
</p>
<br />


EXAMPLE 4B
<p>
<img src="![image](https://github.com/user-attachments/assets/866df8b9-820e-440a-a25f-f630fa6d5e49)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

On the left hand side of the VPN you can select a country where you want your VPN to be, the image below shows the VPN being connected to an IP in Netherland. See EXAMPLE 4C
  
</p>
<br />

EXAMPLE 4C
<p>
<img src="![image](https://github.com/user-attachments/assets/627d9b70-12e7-4124-b4bd-4a8d3a29d58f)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Next we will look at the IP again using the VM browser now that we have connected the VPN to Japan. The website www.whatismyipaddress.com shows yet another IP address using the VPN from Japan. This is quite amazing.
  
</p>
<br />

EXAMPLE 4D
<p>
<img src="![image](https://github.com/user-attachments/assets/ae16fbb3-2f8a-4d02-b97e-fbdd509ce143)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Next we will look at the to use a new vpn service call nord vpn and connect to japan.This is a subscription service require you to paid but is advertise as more secure but no all vpn are not that secure at the end of the day expecial the free one if its its free you are the money they want. look at example 5
</p>
<br />

EXAMPLE 5
<p>
<img src="![image](![image](https://github.com/user-attachments/assets/2c17e075-3557-4f07-bbae-dd0b796d03d1)
)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <p>
<img src="![image](![image](![image](https://github.com/user-attachments/assets/9817cdc4-f28c-4a5c-901e-1f659a56edc3)
)
)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Home IP (USA): 137.103.51.136
Virtual Machin IP (northeurope): 52.169.30.220
Virtual Machin IP VPN thru nord vpn  (Japan) 2.56.252.155

  
</p>
<br />
If you no longer need the VM, ensure to remove it from the Asure account for unwanted charges.
