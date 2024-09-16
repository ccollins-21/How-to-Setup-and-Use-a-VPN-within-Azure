<p align="center">
<img src="https://i.imgur.com/nBkHqaM.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>How to Setup and Use a VPN | ProtonVPN</h1>

 ### [YouTube Demonstration](https://youtu.be/_Jwpo0GfadQ)

<h2>Description</h2>
In this project I create an Azure VM (Virtual Machine) where I download, install, and use a free VPN (Virtual Private Network) called ProtonVPN. <br />
<br />
VPNs (Virtual Private Networks) allow you to connect to a network through encrypted tunnels, enhancing security. Two commons ways VPNs are used are, for companies to allow for remote work, and accessing different content that otherwise would be unavailable without a VPN.  
<br/>


<h2>Environments and Utilities Used</h2>

- <b>ProtonVPN</b>
- <b>Microsoft Azure</b>

<h2>Project Walk-through:</h2>

<p align="center">
First, I will create an Azure VM: <br/>
<img src="https://i.imgur.com/iQRAiPJ.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/5OSa0sF.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
While that's creating I will navigate to this website https://whatismyipaddress.com to get my physical IP address and location. I will write this down in my notepad so that I can observe the changes later when we connect to our VM:  <br/>
<img src="https://i.imgur.com/cXaQGAj.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Next, I'll connect to the VM I just created using Remote Desktop Connection:  <br/>
<img src="https://i.imgur.com/245dku7.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Once I'm connected to my VM I will navigate to the same IP website, then observe and note the different IP and location since I set this VM up to be in Canada. (This RDP connection is like a VPN connection in the sense that there is a tunnel connecting my physical computer to the VM in a different location entirely):  <br/>
<img src="https://i.imgur.com/y0itDin.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now, I can head over to ProtonVPN and sign up for a free account:  <br/>
<img src="https://i.imgur.com/dkzaTum.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
After I made my account, now I can download the windows version in the downloads tab:  <br/>
<img src="https://i.imgur.com/KYdNGNv.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
The download will start and then I'll install the VPN client. It will then have a pop-up for me to sign in with my ProtonVPN account I just made:  <br/>
<img src="https://i.imgur.com/8Kn8q2w.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
After I sign in, it will take me to the homepage where I can start a VPN connection:  <br/>
<img src="https://i.imgur.com/cup7xHR.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I'll click on "Quick Connect" and it will choose and start a VPN connection for me:
<img src="https://i.imgur.com/uMCJ8Px.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now, if i go back to the IP address website and refresh the page, it shows me that I am in Romainia instead of Canada, and I have another different IP address:  <br/>
<img src="https://i.imgur.com/bmCGOuW.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Also, while connected to the VPN I can go to different sites like, www.google.com and www.netflix.com to see the difference compared to if I were on these sites within my own physical computers browser:  <br/>
<img src="https://i.imgur.com/AlHOv92.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/UrfIVcB.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />

<h2> The Setup and Use of Proton is now Complete!</h2>

<b> We've successfully downloaded, installed, and used a free VPN called ProtonVPN! We observed all of the different changes that happened with our IP address and location, and saw some possibilites like, accessing different content while using a VPN! </b>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
