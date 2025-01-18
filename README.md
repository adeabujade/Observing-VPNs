<p align="center">
</p>

<h1>Testing ProtonVPN|  Hotel Topology<h1>
  
This project demonstrates the steps to create a virtual machine (VM) in Microsoft Azure, test geographic IP location changes, and evaluate VPN functionality using ProtonVPN. The purpose is to showcase skills in cloud computing, VPN usage, and networking fundamentals. All steps were documented to provide a clear understanding of the process.

<h2>Environments and Technologies Used</h2>
-Microsoft Azure
-Remote Desktop
-Proto VPN
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Objectives</h2>

-Understand the concept of geographic IP locations and how they can be changed.

-Test VPN functionality using ProtonVPN and evaluate its impact on network behavior.

-Explore website localization based on different geographic locations.

<h2>1.Azure Virtual Machine</h2>

**1. Record the IP address of your Machine**

   a.Browse to https://whatismyipaddress.com/ on your local machine.

  b.Note down your public IP address in a text file (e.g., ip_addresses.txt).


**2. Create a Resource Group**

    a. Give the resource group a name 

    b. For Region choose (US) West US 2

    c. Press Review + Create and then create again

**3. Deploy a Windows 10 Virtual Machine (VM):**

    a. Assign it to the newly created Resource Group.

    b. During the VM setup, allow the creation of a new Virtual Network (VNet) and Subnet.

    c. For the image select Windows 10 Pro

    d. For the size select any with 2 vcpus

    e. Create a username and password for the VM

    f. Press Review + Create and then create again

The Resource Group should look like this after you configure the Virtual Machine.

![image](https://github.com/user-attachments/assets/3b980b10-71e8-4ce7-8cfe-01ca847d8d94)


**3. Accessing the Virtual Machines through Remote**

  a. Open Remote Desktop through Windows search bar

  b. Go into the Virtual Machine that was just ticket and enter the public ip address

  c. Enter the Username and password for the VM



**4.Install ProtonVPN**

    a.On your local machine, sign up for ProtonVPN’s free version at https://account.protonvpn.com/signup?plan=free&language=en

    b.Inside the VM, download the ProtonVPN client from https://protonvpn.com/.

    c.Log into the ProtonVPN client using your account credentials.

    d. After you sign in you can begin using different VPNs by changing severs

**5. Observe IPv4 Addresses**

    <h2>Personal Computer:<h2> 
    
    IPv4:_________

    ISP: Verizon
    
    City: Providence
    
    Region: Rhode Island
    
    Country: United States

    <h2>Within VM West US 2 (Non-VPN Connection):<h2>

  ![image](https://github.com/user-attachments/assets/d1f19077-3212-453b-9deb-9304ec0a5167)

    1st VPN Connection Within VM West US 2 (VPN Connection):

 ![image](https://github.com/user-attachments/assets/a2264c93-d308-4db9-9609-e4dbefe587e7)


 ![image](https://github.com/user-attachments/assets/a7730a8e-d675-48c3-aa16-89d3e639bef4)

    <h2>2nd VPN Connection Within VM West US 2 (VPN Connection):<h2>

 ![image](https://github.com/user-attachments/assets/6863a67f-1b98-41bd-a6c8-0335dc8a9b05)


![image](https://github.com/user-attachments/assets/4f6c96fc-522f-4532-b9e8-7615cb9e48c8)

    <h2>3rd VPN Connection Within VM West US 2 (VPN Connection):<h2>

 ![image](https://github.com/user-attachments/assets/084dee06-8a13-473c-8e46-ea1b5f8556cd)

![image](https://github.com/user-attachments/assets/2151491e-a645-4db1-bc4f-dbb2f2e4df4a)




   
    
    


  






