# HOW TO SETUP A VIRTUAL MACHINE USING VIRTUALBOX
## Description
VirtualBox is a software that allows users to create and run virtual machines, Virtual Machines allows you to run multiple OS
and application on a single physical machine without affecting each other.Here
I'm gonna walk you through on how to install Virtual Box and setup a VM (virtual machine)

## OBJECTIVE
* Install VirtualBox Software
* Download OS for our VM
* Setup a VM on our VirtualBox

## WALKTHROUGH
### STEP: 1 Download VirtualBox
Here is the link where you can download VirtualBox [https://www.virtualbox.org/](https://www.virtualbox.org/)

The link should redirect you to this page, We will see quick description, updates about VirtualBox and we also got the Download button we click it to proceed.


<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/42669c04-018c-4d3c-878b-7da3b544c9c7" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Now we choose depending on what OS we are using:
- <b>Windows</b> 
- <b>macOS / Intel </b>
- <b>Linux</b> 
- <b>Solaris</b>
For this example I am choosing the Windows OS because thats the one i'm using

We can also check the SHA256 and MD5 hash so we can confirm the integrity of the download packages.


<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/9fd844dd-3308-4c95-ae88-70a9c1955df7" height="80%" width="80%" alt="Disk Sanitization Steps"/>

### STEP: 2 Install VirtualBox

After downloading the VirtualBox software we proceed into installing it follow these procedures for the installation.
you can use the short cut ctrl + J to access your downloads or go to your downloads file folder now we run the software that we downloaded to begin installation. 

<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/42cbe5bb-65ef-439a-9514-68382adf34da" height="80%" width="80%" alt="Disk Sanitization Steps"/>

We get a dialogue box we just click on "Next" to proceed with the installation 

<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/01d3a075-aaa2-4200-b96e-6725e549ddd3" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Here we can change the way features will be installed. We will not dive much deeper on this so we just proceed again and click on "Next"
<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/38538b1d-3568-4928-bee0-71f451859b09" height="80%" width="80%" alt="Disk Sanitization Steps"/>

We get a warning that we could experience that the installation will temporary reset  your network connection and temporarily disconnect you from your network.It's normal so we proceed

<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/f1f45c0b-377d-4e44-922e-155a5a0a538a" height="80%" width="80%" alt="Disk Sanitization Steps"/>

During the installation the installer have identified that some dependencies are missing which is the Python Core / win32api, we just click "Yes" and that means that we approve the installation of the missing dependecies for our VirtualBox

<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/616d7e82-7580-49e9-a2a0-f4b54daa7548" height="80%" width="80%" alt="Disk Sanitization Steps"/>

We are almost done installing our VirtualBox, we will Click on the "Install" button on this dialogue box so we can proceed.
<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/417dc6f0-1e6d-481d-b5f0-879a15c25caf" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Installation now in progress.
<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/09470aab-6597-42c2-8ede-874fcb6c7b0d" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Now we are done, we are gonna run the VirtualBox software after our installation.

<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/d3904f8d-bd34-4309-8756-8bc670e45642" height="80%" width="80%" alt="Disk Sanitization Steps"/>

This how our VirtualBox interface will look like.

<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/f3352f9d-f127-44c7-995e-ffc6f22d2803" height="80%" width="80%" alt="Disk Sanitization Steps"/>

### STEP: 3 Download and create an ISO file for the OS of our VM 

We are gonna use Windows 10 as an example for the OS of our VM
Here is the link where you can download windows 10 ISO file : [https://www.virtualbox.org/]([https://www.microsoft.com/en-us/software-download/windows10](https://www.microsoft.com/en-us/software-download/windows10)
it should redirect you to this page,We will choose the "Create Windows 10 installation media" and click the download now button.

<img src="https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/68160e5b-0921-4ffd-b23f-38cb24889837" height="80%" width="80%" alt="Disk Sanitization Steps"/>

After Clicking the Download button we are gonna get the mediac creation tool for Windows this will be used to create the ISO file for our VM

![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/bba45990-bbda-4172-8304-e31237f7d94d)

We are gonna run the media creation tool and we'll gonna get a dialogue box.
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/a9fe8d93-cd45-43f1-b132-2b48302a9404)

Now that all are set up and ready,we got to accept the license terms and agreements.
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/b7097baf-c3e1-44c1-a43a-4879c837923b)

The next step, is where we choose the Language, Edition, and arhcitecture for our OS, we use Windows 10 for our edition and the 64 bit architecture for better performance and to avoid compatibility issue with other software.

![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/0a0c2dfa-d820-4a12-b40b-e7199bf5427f)

After that we are gonna create our ISO file 
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/72eb7c68-4eae-4ee3-bef7-f05d81eab904)

We choose where our created iso file will be after the creation
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/d73f7a7b-5ddb-41e2-8506-db373833a891)

Now we are finished creating our ISO file, we are ready to spin up our own VM on VirtualBox
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/ecdcaf01-c5de-4dc4-941e-ee51b94e7687)

### STEP: 4 Setting up our VM on VirtualBox
We click the New button so we could create a new VM
![1](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/23e294ad-3f6b-4d92-9767-751af1c5f8a3)

after that we are going to name our VM and choose a folder where our VM will be stored
![2](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/ca765271-b349-4074-8bc4-a5d55ba8d5be)

Allocationg RAM and process for our VM, this will dictate the specs of our VM we are going to allocate 8GB of RAM and 3 CPU processor for our VM 
![3](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/39deeaf5-b3c0-4ac2-9916-7539ddc1bca2)

We are goint to need to allocate a Virtual Hard disk for our VM , we are gonna need more than 20GB of Hard Disk for our VM
![4](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/e275d445-21c9-4ac5-9519-8f9504a14560)

We are done with setting up the specs for our VM you can see here the General, System and storage setting that we allocated to our VM, Go to setting for some adjustments
![5](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/02281981-57a8-40c4-a9fb-4994eaa6338b)
click on the advance setting 
![6](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/961a3cbd-22a0-4512-acd4-70f9cf23d41a)
we could change where aour VM snapshots are stored, Snapshots are used for restoring VM to certain point of time, if we ever encounter a system failure.
![7](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/9fe9da78-c2fd-4066-89df-e31ac6752c0d)
Click on the Storage option so we can choose our iso file and run our VM, click on the disk icon.
![8](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/e867854d-6aa5-4fe0-9e6f-6408c3be1c9d)
choose a disk file
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/229758ef-dda1-4ca3-b870-567f55836774)
Choose our ISO file
![9](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/a5dc9b54-40cf-4e8c-8c69-53c3df26afd3)
After that we start our VM press start
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/3dd38eda-1bc5-40dc-bf70-7b513112e3ad)
now our VM is running
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/4a7f1f91-e25e-45f7-9de5-69173c532986)
its our first time running this VM so we need to install our OS, select desired language
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/c23dd08e-5ce5-41fd-976c-b1cdda46c49b)
Install Windows
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/44a09a1a-de9d-4161-ba8f-ce25f2ca6306)
we dont have a product key so we choose this one
![10](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/835fe0d0-d0da-466a-94f2-b48048196088)
we will choose windows 10 pro 
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/5ef50104-38f7-4c45-b683-f381de462d1e)
accept license terms and agreements
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/d0348919-6371-46c1-b873-6c78df3b6b93)

Select our Virtual Hard Disk
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/2cb7afda-bd63-4753-b428-cbe704750b43)

Let the process continue
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/47b90384-fcfc-4cdf-a6da-17473470b9c5)

we are going to need to name our virtual PC
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/5638bfe2-ceb1-4517-9e62-31d6938405cb)

and also set a password
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/c699b1e5-0cad-4ec2-8252-8dc4cebc03f5)


now we are done and ready to use our VM
![image](https://github.com/yelsanity/yelsanity-how-to-setup-VM-using-Vbox/assets/142726793/ff9fec29-8fac-4cb7-9fa9-10efbde7ce98)



























 


































