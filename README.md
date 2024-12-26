# System Setup
This guide is going to assume you already have unity3d and visual studio installed.


## Installing Git
Downloading and installing git navigate to https://git-scm.com/downloads/win


 Select 64-bit git for windows setup 

 ![image](https://github.com/user-attachments/assets/5f5d62f5-a082-445c-a69d-833dd8056c20)


 
When installing git select the default options for everything, until you get to the following page. Make sure Use Windows default console window.

![image](https://github.com/user-attachments/assets/eb8e578e-3cdc-4845-bc1d-f1404bdfe666)



## Github Desktop
Next we need to install github desktop. If you already have another prefered git client that is fine, however if you're not very expirienced with version control I suggest you get github desktop so you can follow along exactly as I am.

https://desktop.github.com/download/

## Visual Studio Workflows
Next we need to make sure we have the needed visual studio workflows installed.

Launch visual studio installer, then click modify on your visual studio version.

![image](https://github.com/user-attachments/assets/8ddf1ce6-2219-4550-ab0d-af565a20f7e8)

Since our game is going to have an ASP.NetCore WebAPI and a couple of blazor projects, we will need to make sure we have the ASP.Net and webdevlopment workload selected,

![image](https://github.com/user-attachments/assets/8284f185-1408-46d7-9feb-128bd1525c4d)

additonally we are going to need the .Net Multi-platform App UI development workload, this will be for the mobile app which will be powered by .NetMAUI

![image](https://github.com/user-attachments/assets/52a2ae53-006d-4d53-b590-2d0346e301ab)

if it is not already installed please ensure you install .Net desktop development

![image](https://github.com/user-attachments/assets/58888a66-3881-47e3-ae77-51138a0cc37c)


## Microsoft SQL Server
Once those are installed its time to install Microsoft SQL Server
https://www.microsoft.com/en-us/sql-server/sql-server-downloads

![image](https://github.com/user-attachments/assets/2039b6a0-9f93-4d9b-8ab9-cc62bd29e06a)


either developer or express edition can be used for this course. I chose developer.

on the first screen select basic

![image](https://github.com/user-attachments/assets/6030f816-4193-45d4-861d-40d2fd99e0fd)

accept the license agreement and chose the install path. 

Once complete you will see the following screen.


![image](https://github.com/user-attachments/assets/2663f6b6-e818-45d3-aa0b-ebd3e7913f6c)

click install SMSS and you will be taken to the download link to install SQL Server Management Studio

Now that everything is installed its finally time to install the template. Fork this repository then clone it to your pc.




