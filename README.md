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
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/14feb7fc-1b01-49ad-a965-10a903ec8804" width="80%" alt=/>
<br />
<br />

<h2>Creating Windows 10 VM in Azure:</h2>

The first thing we will do is create a Windows 10 VM in Azure. Follow the following images below and create an exact replica VM. Don't create a resource group; we will let the VM create its own resource group. If you don't have Europe available as a region, you can select another country; just make sure it has the same configurations as shown in the image. Don't forget to create a username and password for accessing the VM. Make sure to save it somewhere. When the deployment process is done, go to the resource. <br/>
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/270775e4-bdad-4f34-8282-0654cb71a96a" alt=/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/ff38257c-5f9b-4ffa-9852-5c4f40ef767a" alt=/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/ba57f746-ffa3-41aa-9039-50be1ad858d0" alt=/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/15b3d650-fb9b-48f0-9ae3-ad469f5d18a5" alt=/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/47608364-6a19-48e3-ba66-db391546dc07" alt=/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/3f21da14-1bb6-414a-9dc9-c6d096bb7e5e" alt=/>
<br />
<br />
Next, we will open our VM using a remote desktop connection. Use the public IP address given by the VM to connect. Once the connection is established, make sure to select more choices and enter the username and password of the VM we created. When the security warning pops up, just click yes. Follow the same process I do in the images below and once your in the Windows 10 VM interface open edge and go the https://https://whatismyipaddress.com/ website. <br/>
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/3763ebd0-6c20-43dd-8feb-dacdc300362a" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/283cc652-e339-4e22-a37e-309217eef9f9" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/1aff81d2-2990-4b78-97d7-e1b6c0191baf" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/05896e90-47a0-4462-bdbb-782e98d855f4" width="80%" alt=""/>
<br />
<br />
Take note of the IP address and location our VM is located in. <br/>
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/074c936e-1ac8-4801-a393-5115d605209a" alt=""/>
<br />
<br />

<h2>Downloading and Using ProtonVPN:</h2>

We will now proceed to go back to our actual computer interface and sign up for a free Proton VPN account. The reason we aren't doing it in the VM is because our VM is in another region, so the language may be different depending on the region you have your VM set to. So, to make it easier, we will sign up in our actual browser. Go to the following website and follow the prompts below: https://protonvpn.com/download-windows. Don't mind the black background on my PC; I just have it in dark mode. You can also use the following video to help you sign up for an account if you don't understand how to do it: https://youtu.be/otKaa2dANlM?si=M56AZqrJvF_nRMuk. Just make sure not to download the Proton VPN application on your browser if you are going to download it in the VM. <br/>

<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/a88e8eb0-b776-45c4-ac34-faff063693a2" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/5c026d0f-2b90-4d36-9d36-bd95ac6e3e37" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/107dc461-e77a-4740-b2b6-39aab8cd86eb" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/d2977a6c-5ae5-4a49-a59f-894caafcc034" width="80%" alt=""/>
<br />
<br />
Now that we have signed up for an account, I will go back to the VM and search for https://protonvpn.com/download in the Edge browser. Click on the download link in the middle of the page and follow the prompts to download the application in your browser. Once again, if you're confused about how to download the actual application, you can refer to the YouTube video I linked above. 
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/a6df44bf-8a5d-4a2b-88b4-3c177dfac92f" height="80%" width="80%" alt=""/>
<br />
<br />
Finally, we will sign into the application with the username and password we created for our account. Once you go through the verification screen, you will be brought into the Proton VPN interface. We will click on Quick Connect in the top left corner of the application. Once connected, you will see that the location has changed to Poland and you have been assigned a new IP address. To confirm this change was made, we will go back to https://whatismyipaddress.com/. 
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/90e7eea6-962d-40ce-b404-09f7af756474" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/18fd4af0-7aff-4886-b0d8-c86ac6ec8ecf" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/c1f0a910-5dd8-4baa-9f84-ec97e81e2c80" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/f7cb9632-b114-4586-b1ed-e3d88edfe68f" height="80%" width="80%" alt=""/>
<br />
<br />
As you can see, the location and IP address have indeed changed to the same one our VPN connected to and assigned us to. 
To test out the change, we will go to Google.com and Netflix.com. You can see how the language and region have changed. Our VM is in Poland, even though it's actually in the UK. So whatever we do in the web browser at this point will route the traffic through Poland servers. 
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/cea696f7-ab91-4655-ad09-7d5dbbc36530" height="80%" width="80%" alt=""/>
<br />
<br />
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/37ab423f-a201-453e-910e-56799b95fdb0" height="80%" width="80%" alt=""/>
<br />
<br />
Make note of how our IP address and location have changed through the different processes. 
<img src="https://github.com/alibashir7/ProtonVPN/assets/165006117/3a0aef76-16d2-4b8d-925f-4f2b739023d0" height="80%" width="80%" alt=""/>
<br />
<br />
<h2>Conclusion </h2>
That concludes this lab. Now you should know what a VPN is and what it is used for. And you also have knowledge of how to use and navigate Proton VPN. As always don't forget to delete the resource group associated with this lab. <br/>
<br />
Thank You! <br/>
</p>
