# Pop!\_OS

## Distribution History

- ### Release date:
	- Pop!\_OS was made by System76, but before we dive into Pop!\_OS release date, let's talk about System76.
	- System76 is an American computer manufacturer founded by **Carl Richell** and **Erik Fetzer** In 2003 to sell computers with ***Linux*** operating systems preinstalled.
	- In 2005 all computers that shipped from System76 came out of the box with Ubuntu preinstalled, and this is **very important** information.
	- But in ***2017*** System76 decided to make a **BIG** change in their computer lineup and the ___Linux___ community; they decided to make their distribution the best distribution ever "**at least in my opinion**", they called it Pop!\_OS, and beginning from that moment they shipped all there computers with it. 
	
- ### Based on distribution:
	- Now let's talk more in technical detail, do you remember when I told you that System76 shipped their computers from 2005 with Ubuntu, guess what is the base distribution of Pop!\_OS!!..... you are right, it's Ubuntu.

	- So, the question is why System76 decided to make their distribution!!?
	  after small research, it turns out that they want to make more simpler OS for both beginners and professionals but we will dive into this in the Intended Users section.

---
## Intended Users
- ### Real life use cases:
  - to answer on the question "__Isn’t Pop!\_OS just a re-skinned Ubuntu?__".... and the short answer is __NO__.
  - Pop!\_OS has been designed with vibrant colors, a flat theme, and a clean desktop environment, but developers created it to do so much more than just look pretty. (Although it does look very pretty.)
  - Pop!\_OS is designed to be:
    - **easy to use** for Linux beginners from the beginning to the end, also it's tech-savvy professional. 
    - **for all**, Pop!\_OS comes with 3 versions:
      - the base version for Intel/AMD devices.
      - NVIDIA version that come with NVIDIA driver out of the box.
      - Raspberry Pi 4 version for Raspberry SOC.
  
  - **More Privacy**, Pop!\_OS comes with encryption enabled by default, and reporting through Ubuntu disabled out of the box.
  - **more lightweight**, Pop!\_OS avoid providing some larger programs by default that slow down your computer, it's give you the basics.
  - **Featured across the board**, Pop!\_OS come with some major improvements:
    - **Vulkan** drivers and libraries are installed by default to get the most out of your GPU’s performance.
  
    - The power profile picker in the top right menu easily toggles between high performance, balanced, and battery saver modes.
    
    - For scientific workloads, installing **CUDA** and **TensorFlow** is made simple with a single command line.
    
    - systemd-boot bootloader and the automatic configuration tool System76 have created for it called kernelstub replace the outdated GRUB bootloader used on Ubuntu.   
  
- ### Cases where it might not be beneficial to use this specific distribution.
  - In my humble opinion you **don't** need Pop!\_OS in case you are not: 
  	- Software Engineer 
  	- ML&DL researcher
  	- Bioinformatics Engineer
  	- Media Production man
  	- Gamer
  	- regular user
  - if you are not one of the above, you may not need Pop!\_OS... but give it a try. 

---
- ## Strengths and Weakness

  - Installation difficulty
  	- One of the most brilliant features in Pop!\_OS is that the install operation is **SO EASY**, At the same time it protects your file "**if you want**" by encrypting the system, this operation is done by simple clicks here and there.... remember the main goal of Pop!\_OS is to be as simple as possible for all.
  	
  	- **DON'T WORRY**, Keep going to the "**Installation Guide**", I'll explain how to install Pop!\_OS for you. 

  - Software availability. (i.e. How hard is it to install non-FOSS Software?)
  	- **LET's** be more realistic, we aren't in heaven and we can't get everything we need, we must **abandon** somethings in our lives to gain another.
  	
  	- when you use Pop!\_OS or any other Linux distributions there are a bunch of programs you can't run naively, an example is "Visual Studio", and there is a lot of programs that you can't run naively on Linux, the common between these programs is that they are a **~~close source~~**("not an Open Source") programs and no one can make a port for Linux except the company that owns these programs.
  	
  	- But **DON'T WORRY**, using Linux means that you have a **freedom** to do what you want, in your way and at any time.... so, we have multiple choices to solve the problem of software availability:
  		1. code this program from scratch by reverse engineering and make it **Open Source**. 
  		2. try the alternative, there are a lot of **Open Source** alternatives for the Non-ones.
  		3. try emulation, there are programs to run the Non-Open Source program on Linux.
  		4. try virtualization, you can run virtually the operating system that has a port from these programs, but this step is a little complex so try steps 1, 2, and 3 first.
  		
  	- On the other hand, there are some Non-Open Source Programs that have an official port for Linux, Like all JetBrains programs, Spotify, and more. 

  - Is Flatpak pre-installed?
  	- for those who don't know what Flatpak is, simply Flatpak is a store for programs Like ~~Microsoft~~ Store, or as we call it in the Linux Community it's a package manager.
  	  
  	- **Imagine** that you are in front of a store that sells everything for free, you **CAN'T**!!!..... You're excused, but there are stores like this and Flatpak is one of these stores, and **GUESS** what!... Flatpak is **pre-installed** on Pop!\_OS.
---
## Installation Guide
- here we are..... **finally**, the most funny part of this page.
- if you want to install Pop!\_OS or try it, you have 3 methods:
	1. you can use a cool feature called live booting, this feature allows you to try the OS without needing to install it on your computer and it's very easy, but stay until the end to see all the steps.
	
	2. you can install Pop!\_OS **AS** a second OS on your machine by making another cool feature called **DUAL BOOT**.

	3. finally you can make a virtual machine in your main OS and install Pop!\_OS on it. (**I don't recommend this option**).
- So to install Pop!\_OS we have general steps and specific steps.
---
## General Steps:

- **first**, install the image file of the OS from the official website  [System76](https://pop.system76.com/) and click on the download button.

	![](imgs/Pop!_OS_website.png)

	![](imgs/Pop!_OS_list.png)

- if you have **NVIDIA** graphics card choose the **NVIDIA** one.
- **second**, if you willing to do the **first** method or the **second** one install balenaEtcher form official website [balenaEtcher](https://etcher.balena.io/).

	![](imgs/BalenaEtcher_website.png)

	![](imgs/BalenaEtcher_download.png)

- if you willing to do the **third** method download the **Oracle VM VirtualBox** from the official website [Oracle VM VirtualBox](https://www.virtualbox.org/wiki/Downloads).
	
	![](/home/omar/Pictures/Screenshots/Screenshot from 2024-03-06 12-49-28.png)
---
## Specific Steps:
### 1st method:
- install balenaEtcher on your computer after downloading it.
	
	![](imgs/BalenaEtcher_insatll_1.png)
- click on "I Agree" and it will load for some moments
	
	![](imgs/BalenaEtcher_insatll_2.png)
- voilà.... now you installed balenaEtcher on your computer.
	
	![](imgs/BalenaEtcher_program_1.png)
- now click on the "Flash from file" button.
- go to the folder that you but the "**.iso**" file on it.(probably it will be in the Download folder)
	
	![](imgs/BalenaEtcher_program_2.png)
- but a flash drive on your laptop to burn the ".iso" image on it.(you need a 4GB flash drive as a minimum)
- click on the "Select target" button.
	
	![](imgs/BalenaEtcher_program_3.png)
- select you flash drive, then click "select".
	
	![](imgs/BalenaEtcher_program_4.png)
- now click the "Flash" button, **make sure that you don't have any files in this flash drive... this operation will format the flash drive**.
	
	![](imgs/BalenaEtcher_program_5.png)
	
	![](imgs/BalenaEtcher_program_6.png)
	
	![](imgs/BalenaEtcher_program_7.png)
	
	![](imgs/BalenaEtcher_program_8.png)
- Turn off your OS and open your Boot Menu, it will lock like this. (if you don't know how to reach your boot menu, you can search on the internet)
	
	![](imgs/boot_menu.jpeg)
- Choose the name of your flash drive, in my case it's (SanDisk)... then click the "Enter" key.
	
	![](imgs/Pop!_OS_start_window.jpeg)
- it gives you a screen like this, click the "Enter" key.
- scroll down to the **complete installation** section to see what to do next.  
---
###  3rd method:
- install Oracle VM VirtualBox on your computer after downloading it.
	
	![](imgs/VirtualBox_program_1.png)
- click next.
	
	![](imgs/VirtualBox_program_2.png)
- also click next, and be patient.
	
	![](imgs/VirtualBox_program_3.png)
- click yes.
	
	![](imgs/VirtualBox_program_4.png)
- also click yes.
	
	![](imgs/VirtualBox_program_5.png)
- click install.
	
	![](imgs/VirtualBox_program_6.png)
	
	![](imgs/VirtualBox_program_7.png)
- congratulations, you finally did it. 
	
	![](imgs/VirtualBox_program_8.png)
- To create a new virtual machine click on "New" button
	
	![](imgs/VirtualBox_program_9.png)
- name your virtual machine as you want, and select a folder for this virtual machine, and select the ISO image (Pop!\_OS image), you will see that the type will change automatically.
	
	![](imgs/VirtualBox_program_10.png)
- click on "Next" button.
	
	![](imgs/VirtualBox_program_11.png)
- this is the specification of your virtual machine, give it as you want and click on "Next". (I **recommend** to give it 4GB RAM and 4 cores, but for **minimum** specs give it 2GB RAM and 2 cores).
	
	![](imgs/VirtualBox_program_12.png)
- this is the storage of your virtual machine, give it as you want and click on "Next". I **recommend** to give it 32GB of storage, but for **minimum** 16GB).
	
	![](imgs/VirtualBox_program_13.png)
- congratulations.... you are done!, click on "Finish".
	
	![](imgs/VirtualBox_program_14.png)
- click on "Start" button, you will see a new window pops up and Pop!\_OS will run.
	
	![](imgs/inside_pop_vm_1.png)
- to fix the window size go to the setting icon in the left down.
	
	![](imgs/inside_pop_vm_2.png)
- scroll down to displays.
	
	![](imgs/inside_pop_vm_3.png)
- select you screen resolution and click on **apply** then **keep**.
	
	![](imgs/inside_pop_vm_4.png)
---
### complete installation:
- the first time you open Pop!\_OS you will see this screen
	
	![](imgs/Pop!_OS_native_1.png)
	
- chose the language you want, then click "**select**".
	
	![](imgs/Pop!_OS_native_2.png)
	
- chose the region of the language you chose, then click "**select**".
	
	![](imgs/Pop!_OS_native_3.png)
	
	![](imgs/Pop!_OS_native_4.png)
	
- chose your keyboard layout, then click "**select**".
	
	![](imgs/Pop!_OS_native_5.png)
	
- this step is very **IMPORTANT**:
	- IF YOU USE the 1st method, click on "**Try Demo Mode**" button
	
		![](imgs/Pop!_OS_native_6.png)
		
	- IF YOU USE the 3rd method, click on **clean install**, then click on the green "clean install" button.
