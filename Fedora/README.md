# Fedora

<img src="Imgs/Fedora_LOGO.png"  width="150" height="150">

---

## Distribution History

---

Fedora Linux or **_"Fedora"_** is an **Open_source Linux** distribution that was released in **6 November 2003**. It was originally developed as a continuation of [Red Hat Linux](https://en.wikipedia.org/wiki/Red_Hat_Linux) project.
Although Fedora is not as stable as Red Hat Enterprise Linux (RHEL), but it is completely free to use and full of innovations, unlike Red Hat that is typically sold through an annual subscription.

## Distro Image

![Desktop](Imgs/desktop.png)

## Flavors

---

**Fedora Spins** are alternative versions of fedora like:

1. **[Fedora KDE PLASMA DESKTOP](https://fedoraproject.org/spins/kde/)**: It is one of the oldest and most customizable desktop environments available for Linux

1. **[Fedora XFCE](https://fedoraproject.org/spins/xfce/)**: It aims to be fast and lightweight, while still being visually appealing and user friendly so, it is designed to run well on less powerful hardware.

1. **[Fedora CINAMMON](https://fedoraproject.org/spins/cinnamon/)**: Its layout is similar to GNOME 2 and the underlying technology is forked from GNOME Shell. It is known for delivering a high-end audiovisual experience with a fast and responsive interface.

1. **[Fedora MATE-COMPIZ](https://fedoraproject.org/spins/mate/)**: this spin bundles MATE Desktop with Compiz Fusion. MATE Desktop is a lightweight, powerful desktop designed with productivity and performance in mind. The default windows manager is Marco which is usable for all machines and VMs. Compiz Fusion is a beautiful 3D windowing manager with Emerald and GTK+ theming. It was developed as a reaction to the Linux community’s mass rejection of changes introduced in GNOME 3. The MATE team decided to fork GNOME 2 into another project that would preserve the GNOME 2 experience that so many users wanted.

1. **[Fedora i3](https://fedoraproject.org/spins/i3/)**: This spin is good for users who prefer not to use a mouse, touchpad, or other pointing device to interact with their environment.

1. **[Fedora LXDE](https://fedoraproject.org/spins/lxde/)**: Stands for _"Lightweight X11 Desktop Environment"_ and the main goal of LXDE is to keep computer resource usage low. It is especially designed for computers with low hardware specifications like netbooks, mobile device.

1. **[Fedora LXQT](https://fedoraproject.org/spins/lxqt/)**: It provides a small, well selected collection of applications like the Falkon browser, which combines Chromium's rendering engine with a nice Qt experience. LXQt actually began as a spinoff from LXDE when the lead developer decided to try to recreate the desktop using the Qt libraries (which power KDE) instead of GTK. The experience on both desktops is very similar.

1. **[Fedora SOAS](https://fedoraproject.org/spins/soas/)**: Stands for _"Sugar on a Stick"_ and it is is a highly specialized desktop designed for educational use with children. The system is simplified into games and puzzles that can be adjusted based on grade levels. It is especially well suited for use with touch screen devices.

1. **[Fedora PHOSH](https://fedoraproject.org/spins/phosh/)**: This spin provides a mobile friendly, touch based desktop interface. It's built for mobile devices like phones and tablets, but also laptops with touchscreens. Phosh is built on wayland and other modern GNOME desktop technologies.

1. **[Fedora SWAY](https://fedoraproject.org/spins/sway/)**: This Spin offers a complete experience with a minimalist user interface. It makes Sway accessible and appealing to both novices and advanced users who prefer not to use a mouse, touchpad, or other pointing device to interact with their environment.

1. **[Fedora BUDGIE](https://fedoraproject.org/spins/budgie/)**:Budgie Desktop uses common desktop design metaphors while offering users sophisticated functionality such as its Raven widget and notification center, and an approachable method to personalization.

## Real Life use case

---


[Tom Kunz](https://www.trustradius.com/reviews/fedora-linux-2021-06-29-11-16-36) ~ a Solid Rock Technologies Engineer:

**"Fedora is excellent for test-lab/R&D deployment"**
We have had Fedora Linux in testing for a while, and done some limited deployments. It's not our first-choice system, but it is definitely something we have used for certain applications and systems.

You can see more use cases [here](https://www.reddit.com/r/linuxmasterrace/comments/gx5i3b/what_are_the_real_use_cases_for_fedora/).

## When it might not be beneficial to use Fedora?

---

If you don't like changes and want a very stable distribution then Fedora will not be the best choice for you.

## Its Strengths :)

---

- Easy to use, simple, and beginner friendly.
- 100% free.
- Good balance between bleeding edge and stability.
- Customizable.
- Flatpak is installed by default on Fedora.

## Its weaknesses :(

---

- Requires long time to install.
- Does not include proprietary software and software with usage restrictions.
- Not as stable as Red Hat Enterprise because New release of Fedora Core occur about every six months.

## Installation Guide

### Creating a Virtual Machine (VirtualBox)

---

1. Follow this [link](https://www.virtualbox.org/wiki/Downloads) to download **VirtualBox** and choose the suitable package.

1. Download the latest version of Fedora using this [link](https://fedoraproject.org/en/workstation/download).

1. Open the virtual box and click on **new** button in the upper left corner next to the **Add** button.![VB Step 3](<Imgs/VB Step3.png>)

1. Give a name to your distro like **"Fedora"** or any other name in the **Name** field.

1. For the **Folder** field: Choose the local disk where you have much space.

1. For the **ISO Image** field: Choose the **other** option and select the ISO image you downloaded in **step 2**, then press **Next**. ![VB Step 6](<Imgs/VB Step6.png>)

1. Now it's time to customize your memory so:

   1. For the **Base Memory** section give it any number of GBs based on your available memory.

   1. For the **processor** section give it any number of cores.![VB Step 7-2](<Imgs/VB Step7-2.png>)

   1. Remember to check **Enable EFI** option then press on **Next** button.![VB Step 7-3](<Imgs/VB Step7-3.png>)

1. Give Fedora any number of GBs from your Hard disk (preferable 20 GBs) then press on **Next** button.![VB Step 8](<Imgs/VB Step8.png>)

1. Press on **Finish** button.![VB Step 9](<Imgs/VB Step9.png>)

1. Go to **Settings => System => Processor** and check **Enable PAE/NX** option. ![VB Step 10](<Imgs/VB Step10.png>)

1. Go to **Settings => System => Display** and in the **Video memory** section make it 128 MBs. ![VB Step 11](<Imgs/VB Step11.png>)

1. Go to **Settings => System => Shared folders** then Click on **+** button in the upper right corner and choose **Other**.

1. In the **Folder Path** section you can share any local drive you want and check **Auto-Mount** option then press **OK => OK** (steps 12 & 13 are optional).![=VB Step 13](<Imgs/VB Step13.png>)

1. Click on **start** button and wait for a while.

### Dual Boot

---

1. You can get Fedora's ISO image [here](https://fedoraproject.org/en/workstation/download).

1. You can then burn the ISO image to a USB stick using [Balena Etcher](https://etcher.balena.io/) or [Rufus](https://rufus.ie/en/).

1. Research dual boot instructions for your existing operating system.

   - For Windows, you can follow the steps [here](https://itsfoss.com/dual-boot-fedora-windows/).
   - If you are dual booting with Windows, you might need to disable some features like BitLocker, Fast Startup and Hibernate
   - You might need to disable Secure Boot if it is enabled

1. Restart your device and boot into USB stick.![Dual Boot Step3](<Imgs/Dual Boot Step3.png>)

1. You can try out Fedora before installing it on your hard drive.![Dual Boot Step4](<Imgs/Dual Boot Step4.png>)

1. If you like the look and feel, you can choose "Install to hard drive" option.

### Setting Up Fedora

---

1. Click on **Install Fedora**.![VB Step 15](<Imgs/VB Step15.png>)

1. Select any Language you want (preferable to choose English).![VB Step 16](<Imgs/VB Step16.png>)

1. Choose **Installation Destination** Option.![VB Step 17](<Imgs/VB Step17.png>)

1. _If you are dual booting, choose the hard drive that you want Fedora to be installed on._![Dual Boot Step8](<Imgs/Dual Boot Step8.png>)

1. Make sure that **Storage Configuration** is **Automatic** then click on **Done**.![VB Step 18](<Imgs/VB Step18.png>)

1. Click on **Begin Installation** button and wait for a while.![VB Step 19](<Imgs/VB Step19.png>)

1. Click on **Finish Installation**.![VB Step 20](<Imgs/VB Step20.png>)

1. _If you are dual booting, remove your USB._
1. In the upper right corner click on the **Baterry** icon next to the **sound** icon then click on **Power** icon and choose the **"Restart..."** option.![VB Step 21](<Imgs/VB Step21.png>)

1. Click on **Restart** Button and wait for a while.![VB Step 22](<Imgs/VB Step22.png>)

1. Click on **Start Setup**.![VB Step 23](<Imgs/VB Step23.png>)

1. Turn off the **Location services** and **Automatic Problem reporting** options then click on **Next**.![VB Step 24](<Imgs/VB Step24.png>)

1. Click on **Enable-Third Party Repository** then click on **Next**.![VB Step 25](<Imgs/VB Step25.png>)

1. You can Link your accounts or Skip this step for now. ![VB Step 26](<Imgs/VB Step26.png>)

1. Write your name in the **Full Name** field and click on **Next**.![VB Step 27](<Imgs/VB Step27.png>)

1. Write a strong password for your system in **Password** field and confirm it then click on **Next**.![VB Step 28](<Imgs/VB Step28.png>)

1. Click on **Start Using Fedora Linux**.![VB Step 29](<Imgs/VB Step28.png>)

1. Enjoy using your system :)

### Helpful resources

- [ How to Install Fedora 38 on Virtualbox ](https://youtu.be/4eJ3pF4-CN4?si=2ydu6BxTvOByQWJv)
- [How to Dual Boot Fedora and Windows](https://itsfoss.com/dual-boot-fedora-windows/)
- [Fedora Docs - Getting started](https://docs.fedoraproject.org/en-US/fedora/latest/getting-started/)
