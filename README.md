<p align="center">
<img src="https://www.highspeedoptions.com/wp-content/uploads/2023/06/choosing-and-using-vpn-featured-image.png" alt="VPN"/>
</p>

<h1>Installing a Virtual Private Network (VPN) on a Azure Virtual Machine</h1>
In this tutorial, we will install a VPN on a Azure Virtual Machine from scratch <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- NordVPN or any VPN software

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE
- Create a Resource Group
- Create a Windows 10 Virtual Machine in another geographic location (try a different country)
- On your actual computer, sign up for the free version of Proton VPN
- Back within your VM, download the Proton VPN client
- Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server

<h2>Actions and Observations</h2>

<h3>Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE</h3>

<h3>Create a Resource Group</h3>

![01](https://github.com/user-attachments/assets/2a130069-903d-49af-a2e2-0eabd95f692f)

<h3>Create a Windows 10 Virtual Machine in another geographic location (try a different country)</h3>

![02](https://github.com/user-attachments/assets/7bdf3d7e-fc52-4109-9c86-5485b61a0c23)

<p>Log into the VM with Remote Desktop</p>

![03](https://github.com/user-attachments/assets/fd5e2ea1-b359-4e65-bd44-97672517d1c7)

<p>Browse to https://whatismyipaddress.com/</p>

<h3>On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en </h3>

![04](https://github.com/user-attachments/assets/c613770f-c149-4762-afca-ea72d348f2a1)

<h3>Back within your VM, download the Proton VPN client</h3>

![05](https://github.com/user-attachments/assets/82e824d2-62a7-4fcb-8361-65ee34b67191)

<p>Login to the VPN (https://account.protonvpn.com/login) and choose a VPN server in yet another country (such as Japan)</p>

![06](https://github.com/user-attachments/assets/e6f53511-8f76-4bff-8aa0-3d3725ded49a)

<p>Browse to https://whatismyipaddress.com/</p>

<h3>Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server</h3>

<h2>(Clean up Azure resources)</h2>

<h3>Delete the resource group you created in Step 2</h3>
<h3>Ensure the resources/Resource Group has been deleted.</h3>

