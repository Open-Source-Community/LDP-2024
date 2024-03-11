# ParrotOS

- ## Distribution History
  - ## Release date:
	- Parrot Security OS is designed and developed by security expert **Lorenzo Faletra** and a team of other security experts, open-source developers, digital rights advocates, and other Linux enthusiasts. The initial public launch was in ***April 2013***. Parrot OS version 1.0, codenamed Hydrogen, was launched in ***July 2014***.

	- In ***September 2015***, Parrot OS version 2.0, codenamed Helium, was released. In ***June 2016***, the third version, codenamed Lithium, was released. In ***May 2018***, version 4 was launched. The latest version of Parrot OS is 4.11, which was published in ***March 2021***.

	- In ***2017***, the Parrot team faced some system issues and thought about switching to Devuan, but eventually, they were able to resolve the problems and did not have to make the switch. The team decided to stop supporting 32-bit in ***January 2019*** to concentrate on x64 and ARM. In ***August 2020***, the **XFCE** Desktop environment (Home Edition) was officially supported, which made the system lighter.
  - ## Flavors
    + Home Edition: The Home Edition is the base edition of Parrot OS, designed for daily use. It targets regular users who need a lightweight system on their laptops or workstations. The specific release date or history of this edition is not readily available.
    + Security Edition: The Security Edition is designed for penetration testing, vulnerability assessment and mitigation, computer forensics, and anonymous web browsing. It was part of the initial release of Parrot OS on ***April 10th, 2013***.
    + Architect Edition: The Architect Edition is a minimal Parrot OS with nothing pre-installed. It allows for any software and desktop environment chosen by the user. The specific release date or history of this edition is not readily available. However, there was an improvement in Tasksel layout, enhancing the user experience during software selection.
    + WSL Edition: The WSL Edition is specifically designed for the ~~Windows~~ Subsystem for Linux. It was made available for ~~Windows 11~~ and allows users to install and set up Parrot Security Distro with GUI on ~~Windows 11~~ with WSL 2.
    + Cloud Edition: The Cloud Edition is designed for cloud-based applications. The specific release date or history of this edition is not readily available.
    + Raspberry Pi Edition: This is a lightweight Parrot release for embedded systems. It is currently available for Raspberry Pi devices. The specific release date or history of this edition is not readily available.
  - ## What's it based on?
    Parrot OS is a **Debian-based Linux distribution** that emphasizes security, privacy, and software development.
---
- ## Intended Users
  - ### Real life use cases:

    - Parrot OS is tailored for cybersecurity professionals, ethical hackers, and pen testers who require a robust and adaptable platform for their tasks.

    - It is equipped with an array of tools for network analysis, vulnerability assessment, and penetration testing, as well as tools for digital forensics, reverse engineering, and cryptography, making it a versatile choice for cybersecurity experts.

    - Moreover, Parrot OS prioritizes privacy and security, boasting features such as built-in encryption and secure boot capabilities. This makes it an ideal option for individuals who prioritize data protection and online privacy.

    - Furthermore, Parrot OS appeals to users who value open-source software and seek a free operating system with unrestricted access to its source code.

    - Lastly, Parrot OS is a suitable choice for those who enjoy customizing their operating system and prefer a more adaptable and open computing experience. Its lightweight and modular design allows users to personalize the system according to their specific requirements and preferences.
   - ### Cases where it might not be beneficial to use this specific distribution.  
	  + Parrot OS may not be the optimal option for individuals who lack familiarity with Linux-based operating systems or those who seek a more user-friendly and uncomplicated platform. It necessitates a certain level of technical knowledge and expertise to utilize effectively, making it less suitable for beginners or casual users.

	  + Parrot OS is not specifically designed for general-purpose computing tasks like web browsing, multimedia, and productivity applications.

      + Parrot OS may also not be appropriate for individuals who do not require the advanced security and privacy features provided by the operating system. If you simply require a basic operating system for everyday use, Parrot OS may not be the most advantageous choice.

	  + Lastly, Parrot OS may not be compatible with all hardware configurations, so it is crucial to verify the system requirements before attempting to install it.
---
- ## Strengths & Weakness

  - ### Strengths:

    - Enhanced Security: Parrot OS offers a range of built-in security features, including a sandbox system, cryptography tools, and anonymous browsing tools.

    - Privacy Protection: Parrot OS is designed to safeguard users' privacy by providing secure and anonymous browsing options, as well as encrypted communication channels.

    - Extensive Toolset: Parrot OS comes with a wi1. Enhanced Security: Parrot OS offers a range of built-in security features, including a sandbox system, cryptography tools, and anonymous browsing tools.

    - Lightweight Design: Parrot OS is specifically designed to be lightweight, making it suitable for running on older hardware.

    - User-Friendly: Parrot OS boasts a user-friendly interface and is easy to install and configure, making it an excellent choice for beginners.

    - Versatility: Parrot OS is a versatile operating system that can be utilized for various purposes, including penetration testing, digital forensics, cryptography, and development.

    - Free and Open-Source: Parrot OS is freely available as open-source software, allowing users to download, use, and modify it according to their requirements.

    - Active Community: Parrot OS benefits from an active community of developers and users who contribute to its development, provide support, and share knowledge and resources.

    - Regular Updates: Parrot OS is regularly updated with the latest security patches and software updates, ensuring users have access to the most up-to-date tools and features.

    - High Customizability: Parrot OS offers a high level of customization, enabling users to configure and adjust various aspects of the operating system to suit their specific needs.

  - ### Weakness:

    - Limited mainstream support: Despite having a supportive community, Parrot OS may lack the same level of mainstream support as more popular Linux distributions.

    - Not suitable for everyday use: Parrot OS is primarily tailored for security and development purposes, making it less than ideal for daily tasks.

    - Steep learning curve: Certain tools in Parrot OS may pose a challenge for users due to their complex nature, requiring significant effort to master.

    - Not optimized for gaming: Parrot OS is not intended for gaming, making it a less favorable choice for users seeking a gaming-friendly operating system.

    - Limited software support: Parrot OS may not offer the same extensive software support as other Linux distributions due to its lower popularity.

    - Limited software availability: Despite its wide array of pre-installed tools, Parrot OS may not provide the same level of software availability as more mainstream distributions.

    - Hardware compatibility issues: Users with older or less common hardware configurations may encounter compatibility problems when running Parrot OS.

    - Dependency issues: Installing and configuring software in Parrot OS may involve resolving dependency issues, which can be time-consuming and daunting for newcomers.

    - Documentation challenges: While Parrot OS offers comprehensive documentation, some users, especially those new to Linux, may struggle to comprehend or navigate it effectively.
    
    - Resource-intensive tools: Certain tools in Parrot OS may demand significant system resources, potentially causing performance issues on older or less powerful hardware.
    - Parrot OS does not come with Flatpak pre-installed1. However, you can easily install Flatpak on Parrot OS
---
# Installation Guide
- #### Now we will explain How to install Parrot
    - You need to download Parrot OS installation Disk image
    - There are many Parrot OS edition , You can download them from [Parrot OS ISO](https://www.parrotsec.org/download/) , and it will be like this <br> ![1](imgs/Step1.jpeg)
    -  There are two ways to install first by selecting the Live Mode (but every time you turn off the machine , Everything in the machine will be erased) and 2nd by selecting the Install option and both will work the same. we will go with the 2nd method
Select the Parrot OS in Left Pane and click on start for installation. <br> ![2](imgs/Step2.jpeg)
    - In its home screen, Select Install Parrot to begin the installation. <br> ![3](imgs/Step3.jpeg)
    - Provide your location. Click on Next. <br> ![4](imgs/Step4.jpeg)
    - Select the default language according to your keyboard below is selected for QUERTY keyboard layout. <br> ![5](imgs/Step5.jpeg)
    - Click on the “Erase Disk” radio button (recommended for beginners ). It will automatically partition your virtual disk according to the size you have provided to it. Click on Next. <br> ![6](imgs/Step6.jpeg)
    - Finally, you just need to create a user( root user) and password to access it whenever you want so that your data is saved. <br> ![7](imgs/Step7.jpeg)
    - On the last page, it will show all the settings that you have selected or done till now so that you can verify it one last time before the final install procedure starts. <br> ![8](imgs/Step8.jpeg)
    - After verification, if you are not satisfied and change some settings then you can either click on the Back button or click on the Cancel button. If satisfied, then click on the Install button, it will prompt you to continue installation, then click on Install Now, to begin the installation. <br> ![9](imgs/Step9.jpeg)
    - Now we just need to wait for at least 20-30 minutes for the installation to finish up. After it has done, it will prompt to restart. Click on it restart so that your virtual machine will save all the necessary changes that have been made. <br> ![10](imgs/Step10.jpeg)
    - After restart you will see that it’s done. <br> ![11](imgs/Step11.jpeg)
    - #### Now Your Parrot OS is successfully installed in your PC with all the basic functionalities that are required. :D