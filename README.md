<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Installation Steps</h2>

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/58c172ec-7442-4db9-be0b-55eb71f97d1d)
<h2>**1.) Before we install anything onto our device we will first make a resource group using Microsoft Azure in order to make a Virtual machine from there we will continue.**</h2>

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/f12c0bb1-10d0-4ad1-b73d-1e26ba5c2b67)
**2.) After the resource group is created we will then create a VM.**

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/e6394ad5-e700-434e-ad8a-5bda40a775e7)
**3.) Once we get to this screen after hitting create a VM you will the put the resource group you have created in, then you will pick Windows 10 as your Virtual Machine.**

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/5812b167-c57e-4709-b480-c41bf6d91d0f)
**4.) Then scroll down and enter any username and passowrd (make sure you remeber/write it down) after that hit review and create.**

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/60c80616-e67a-4b95-9872-3f9bc48ae38d)
**5.) Once your VM is done creating click on it and look for the public IP address and copy it and paste it into remote desktop and connect.**

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/1f7633a7-ef4c-43c7-80d3-e8d121e86518)
![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/e1af81fc-2596-4cee-9e5b-3ed020e53b8a)
![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/6c0e6068-5f69-4ff1-b70e-832eb7731612)
![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/37e20963-032a-4304-b53d-0a25c9281cb3)



**6.) Once we are into our VM we have to Install/Enable IIS with windows CGI, first you will have to go to Control Pannel and click on Programs, Turn Windows Feat. on or off, then go through the list and look for Internet Information Services box and check and expand the box -> then go to World Wide Web Services, you then have to expand the World Wide Web Services -> then go to App Dev Features and expand it from their check the CGI box, then collapse App Dev -> then go to common HTTP Feat -> then make sure all boxes are checked. Then hit ok and it will install IIS.**

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/9ffd0956-eb81-4dde-9649-fac00c97fd2e)
**7.) To insure you Enabled/installed IIS go to any browser and type "127.0.0.1" and if this pops up you would now have this step completed.**

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/bff95587-8714-46ed-aa73-4dc409bfb4ed)
**8.) Next we will download PHP Manager for IIS, after you've downloaded PHP Manager click on through your files and hit agree and finish the install.** 

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/4b13dc83-59e2-44bc-a406-7afeba6bf556)
**9.) Same thing with the Rewrite Module, just download it and hit install and finish**

  
  ![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/d3bd12d2-9168-4f25-82ea-bdf6abe89ccd)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/3b359936-142b-4e90-a2c8-7681049632ab)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/36a966c2-b856-43f7-9a94-72386fa2ec91)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/5e967aa5-6609-48ca-b1d0-360a98b740ce)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/55f975f3-562a-413d-975e-c0437af03805)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/779103b0-1d29-410e-a9af-e9b0c0af7206)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/c555d2ce-e04e-4def-88dd-7f88dac018b5)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/8508792b-7b93-4140-b4ba-8241a18765a7)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/78987396-a829-4961-a159-c22609077bb2)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/5c14957d-5a17-4568-8226-080308604597)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/54950ca6-00b9-4458-b199-245bac314a45)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/99cbca1a-df67-48a2-be57-3a0f499cf581)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/9308c52a-3664-4a44-876b-da1c5531f705)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/ee63c56b-040d-4688-84bd-2b664e3ded0d)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/91787e4e-b231-4e73-8b93-acd33acf37d8)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/d444a42e-2c82-4b51-9692-09d9caab03ce)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/382f8b7d-4025-48b1-b5ff-1679df4dc92f)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/485f3f60-65f9-49e4-8643-66b2404f4069)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/a68e3b84-4fea-459a-8dce-5a254c81a58f)

![image](https://github.com/MartindIT/osticket-prereqs/assets/151476834/0fa594bf-572e-4dda-9f61-6f83b4a7c6cd)

<br />
