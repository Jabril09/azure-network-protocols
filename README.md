<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1 - Sign into portal.azure.com and create a resourse group called RG-LAB-02. Make the region US west 3 and then click create and review 
- Step 2 - Create a Virtual machine (VM) and put it in the same resourse group you just created. Name the virtual machine VM1, windows 10 pro. 2 vcpus and make user name labuser and password whatever you want it to be , but please remember it and write it down!then click creat and review. 
- Step 3 - Create another Virtual machine (VM) and put this one in the same resourse group as the first virtual machine RG-LAB-02. Name this vm VM2 ubuntu (linux) server 20.04 lts - gen 2, 2 vcpus and click password and not SSH public key, Name this labuser then click next, next review and create. 
- Step 4 - Open up VM1 in remote desktop and go to google.com and download wireshark. Once installed close out everthing and open up wireshark. 
- Step 5 - Minimize VM1 and go back to the azure portal and copy VM2 private IP address. Once  copied, open up VM1. In VM1 open up Powershell in the windows prompt. In powershell type in ping and the private IP address and hit enter. Notice the ping and replies from VM1 to VM2. 
- Step 6 - 
- Step 7 - 
- Step 8 - 
- Step 9 - 





<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/f5vVlgU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once signed into azure, create a resource group and call it RG-LAB-02. RG is for Resourse group. 
</p>
<br />

<p>
<img src="https://i.imgur.com/LQfZV4v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Make sure the resourse group is us west 3 .
</p>
<br />

<p>
<img src="https://i.imgur.com/oomnUxU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Virtual Machine (VM). Put it in the same resourse group you just created. RG-LAB-02
</p>
<br />
<p>
<img src="https://i.imgur.com/ZIOtKAC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the Virtual Machine (VM1). US west 3 user name labuser and password (something you will not forget) same resource group RG-LAB-02 windows 10 pro version 2vcpu and click review and create. 
</p>
<br />
<p>
<img src="https://i.imgur.com/f2maKSL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name the Virtual Machine (VM2). Us west 3 name labuser and password (something you will not forget) same resource group RG-LAB-02 ubuntu server (linux) 20.04 Lts-gen2 click password and not SSH public key click review and create. 
</p>
<br />
<p>
<img src="https://i.imgur.com/IFlouzd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open up VM1 in remote desktop and go to google.com and download wireshark. Then download windows installer(64-bit). Then click open file click next through everthing to install and finish. Once installed close out everthing and open up wireshark. Click the windows tab and type wireshark and click the wireshark app. Once in wire shark click the shark fin in the upper left corner to start seeing live actual traffic happening in VM1.
</p>
<br />
<p>
<img src="https://i.imgur.com/NR5CnFd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Minimized VM1 and find go into VM2 to get the private IP address. Copy it and go back to VM1. Click the windows button and type powershell and open up powershell.(More powerful command-line shell and scripting language than the Command-prompt, similar to command prompt) In the top bar click and type in ICMP (Inter control messaging protocol) and hit enter. Notice how everthing stopped?. 
</p>
<br />
<p>
<img src="https://i.imgur.com/UiaJmII.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In powershell type in ping 10.0.0.5 (VM2 private Ip address). Hit enter and you will notice the ping and replies. Type in ping 10.0.0.5 (space) -t. Now you will be ping forever. pretty cool.
</p>
<br />
<p>
<img src="https://i.imgur.com/W1BfEjy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor 
</p>
<br />
</p>
<br />
<p>
<img src="https://i.imgur.com/hr4O4QJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet.
</p>
<br />
</p>
<br />
<p>
<img src="https://i.imgur.com/Dd5BmL4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor 
</p>
<br />
</p>
<br />
<p>
<img src="https://i.imgur.com/Xsn0rU1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet.
</p>
<br />
</p>
<br />
<p>
<img src="https://i.imgur.com/iXqPyaD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor 
</p>
<br />
</p>
<br />
<p>
<img src="https://i.imgur.com/v9aMadS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet.
</p>
<br />
