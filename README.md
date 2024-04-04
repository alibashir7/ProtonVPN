<h1>VPN Setup and Usage</h1>

<h2>Description</h2>
In this lab, we will learn what VPNs are and what they are used for. I'll show you how to download and use Proton VPN for free. VPN stands for Virtual Private Networks. VPNs can securely link two computers (or networks) together across an insecure network such as the internet, allowing them to send encapsulated and encrypted data to each other. There are two main use cases for VPN the first one is it's used when a person want to connect to resources at work from home. The second one is to access content or resources available in another country.
<br />

<h2>Environments Used </h2>
- <b>Windows 10</b> (21H2)

<h2>Checking Current IP Address:</h2>
<p align="center">
In your web browser go to the following website: https://https://whatismyipaddress.com/  <br/>
<p align="center">
Open your Notepad application and take note of the IP address and location your computer is located at. <br/>
<img src="https://imgur.com/fKGjvpI.png" height="80%" width="80%" alt=""/>
<br/>
  
<h2>Downloading and Using ProtonVPN:</h2>
The first thing we will do is create a Windows 10 VM in Azure. Follow the following images below and create an exact replica VM. Don't create a resource group; we will let the VM create its own resource group. If you don't have Europe available as a region, you can select another country; just make sure it has the same configurations as shown in the image. Don't forget to create a username and password for accessing the VM. Make sure to save it somewhere. When the deployment process is done, go to the resource. <br/>
<img src=".png" height="80%" width="80%" alt=/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=/>
<br />
<br />
Next, we will open our VM using a remote desktop connection. Use the public IP address given by the VM to connect. Once the connection is established, make sure to select more choices and enter the username and password of the VM we created. When the security warning pops up, just click yes. Follow the same process I do in the images below and once your in the Windows 10 VM interface open edge and go the https://https://whatismyipaddress.com/ website. <br/>
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
Take note of the IP address and location our VM is located in. <br/>
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
We will now proceed to go back to our actual computer interface and sign up for a free Proton VPN account. The reason we aren't doing it in the VM is because our VM is in another region, so the language may be different depending on the reigion you have your VM set to. So, to make it easier, we will sign up in our actual browser. Go to the follwing website and follow the prompts below https://protonvpn.com/download-windows. You can use the following video to help you sign up if you don't understand how to do it https://youtu.be/otKaa2dANlM?si=M56AZqrJvF_nRMuk. Just make sure not to download the Proton VPN application on your browser were going to download it in the VM. <br/>
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<img src=".png" height="80%" width="80%" alt=""/>
<br />
<br />
<h2>Conclusion </h2>
That concludes this lab. Now you should know what a VPN is and what it is used for. And you also have knowledge of how to use and navigate Proton VPN.  <br/>
<br />
Thank You! <br/>
</p>
