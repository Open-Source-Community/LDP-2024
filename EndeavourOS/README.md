<link rel="stylesheet" type="text/css" href="styles.css">

# Endeavour OS
### 1- Distribution History

<img src="imgs/EndeavourOS_4.webp" alt="EndeavourOS_4">

- When the popular Arch-based distro Antergos ended
its run in May 2019, it left a friendly and extremely helpful community behind.
Within a matter of days after the announcement, Bryan Poerwoatmodjo opted for
the idea to continue the community feeling on a new forum that would invite any
Arch or Arch-based Linux user into the group. The idea received a lot of
enthusiastic response, more than enough for him to get the project going.

- Quickly, Johannes Kamprad, Fernando Omiechuk Frozi and
Manuel joined him to set up the project and when that happened, the plan changed
from preserving the former community on a new forum to creating a new distro
with that vibrant community at its core.

<br>

  <div class="img-row">
    <img src="imgs/antergosblue_by_decluttermind-d87lvni.webp" alt="antergosblue" width=500 margin-right=10px>
    <img src="imgs/endeavorrwall9.webp" alt="endeavorwall9" width=500>
</div>
<br>

- With the plan to turn Endeavour into EndeavourOS, we deliberately travelled another road than Antergos did. It never was and it will never be our intention to be an Antergos clone. In fact, our departure point was the Antergos community and not Antergos the distro and that’s why we chose to let go of the look and feel of our predecessor and find our own voice in creating our own identity with the community at our side.

<br>

- To avoid the project becoming unmanageable, we decided in the early stage of development to provide a basic system that is close to Arch Linux. That’s why we are aiming for a Linux user with an intermediate level of knowledge who likes to handle a system that needs hands-on customization from the get-go, with the help of our main standout feature: Our vibrant and friendly community.

![endevouros-preview](imgs/endeavouros-preview.webp)
<p style="font-size: 20px; color: #6e62b6;">
First release and a snapshot of the original website
</p>

- This resulted in a distro that is lightweight and ships with a minimum amount of preinstalled apps. An almost blank canvas ready to personalize.

- Flavors:
  - KDE
  - GNOME
  - Xcfe4
  - Cinnamon
  - Mate
  - Budgie
  - LXQT
  - LXDE
  - i3-wm
  
  
### References
- [EndeavourOS site](https://endeavouros.com/)


### 2- Intended Users
- Use cases:
  - Users who have some experience with Linux and are comfortable with tasks such as manual system configuration, command-line usage, and troubleshooting.
  - Users who are comfortable to use arch-based distro and know how to use pacman and Arch User Repository (AUR) but with user-friendly interface.
- Cases where don't use this distro:
  - Endeavour OS is not for servers because it is Rolling Release Model.
  - If you are new to linux, Endeavour OS may be not comfortable for you. 


### 3- Strengths & Weakness
- Strengths:
  - Pacman package manager is so fast.
  - Having access to Arch User Repositery (AUR).
  - Have many flavors like KDE(default), GNOME, Xfce4, i3-wm, Budgie, Cinnamon, Mate, LXDE and LXQT.
  - User-Friendly Installation Tool
- Weakness:
  - Limited Official Support
  - Rolling Release Model
  - Potientional Learning Curves


![Endeovour OS](imgs/endeavouros-dark.png)
### 4- Installation Guide
  1. Direct installation
     1. Download the EndeavourOS ISO file from their website.

     2. Burn the ISO file to a blank DVD or USB drive, using a tool like Rufus or Etcher.

     3. Insert the DVD or USB drive into your computer and boot up from it.

     4. You will be prompted to select your language and keyboard layout. Make sure to choose the correct ones.

     5. You will then be taken to the partitioning screen where you can select how you want your hard drive divided into partitions for your install. If you are unsure what to do, select “guided partitioning” for an automated setup process.

     6. After selecting your partitions, you will be asked what packages you would like to install during the setup process. Select any packages you want installed, or leave them all unchecked for a minimal install.

     7. Once all of your options have been selected, click “Install” and let EndeavourOS take care of the rest! The installation should take about 15 minutes depending on your hardware specs and package selection.

     8. When the installation is complete, reboot your computer and enjoy EndeavourOS!
  2. VirtualBox:
     1. [Download the EndeavourOS ISO](https://endeavouros.com/)
     2. Download VirtualBox
     3. Create new VM
     4. To better performance change the vram for VM to 128MB from VM Settings ![](imgs/Screenshot%20from%202024-03-06%2016-40-56.png)
     5. Start VM
     6. Choose first choice ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_37_59.png)
     7. Wait for booting ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_38_14.png)
     8. Start the installer ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_45_39.png)
     9. Choose online if you want to download other Desktop or offline if KDE good for you ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_46_14.png)
     10. Choose Language ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_46_44.png)
     11. Choose Location ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_46_52.png)
     12. Choose Keyboard Layout ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_47_02.png)
     13. Choose Desktop (if online installation) ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_47_48.png)
     14. Review Packages ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_48_10.png)
     15. Erase Disk because it is VM ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_48_32.png)
     16. Make User ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_48_57.png)
     17. Review Installation ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_49_08.png)
     18. Install ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_49_31.png)
     19. Wait for 15 Minutes ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_49_51.png)
     20. Installation Done Poweroff VM ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_17_10_30.png)
     21. Remove ISO from VM ![](imgs/Screenshot%20from%202024-03-06%2018-58-57.png) 
     22. Start VM & Choose to boot Endeavour OS ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_17_11_02.png)
     23. Write Password ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_17_12_33.png)
     24. Installation Done ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_17_12_51.png)
     25. if you Restarted after install and found Installation Menu because you don't remove ISO from VM. Choose Boot existing OS Here ![](imgs/VirtualBox_Endeovour%20OS_06_03_2024_16_37_59.png)
