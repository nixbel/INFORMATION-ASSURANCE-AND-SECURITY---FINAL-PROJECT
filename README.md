# INFORMATION ASSURANCE AND SECURITY - FINAL PROJECT
## Submitted by **Group 9 - BSCS 3B**
- Albonial, Jeland
- Belmonte, Jacques Nico
- Sinfuego, Jade
- Tibi, Christian Jay



# Raspberry Pi Installation Guide

## 1. Prepare and Install Headless Raspian OS in Raspberry Pi

- ### Download Raspbian OS

- ### Visit the [Official Raspberry Pi Website](https://www.raspberrypi.com/software/)

![Pic1](pic1.png)

- ### Now click _**"Download for Windows"**_ or [Click this](https://downloads.raspberrypi.org/imager/imager_latest.exe) to redirect download.

![Pic 2](pic2.png)

- ### Run the Downloaded file and Install

![Pic 3](pic3.png)

- ### Insert SD Card or Memory Card. Open the Raspberry Pi Application

![Pic 4](pic4.png)

- ### Click _**"Choose Device"**_, and choose any version of Raspberry Pi Device. In this case I select Raspberry Pi 3, and then click _**"Choose OS"**_, and choose any version of Raspberry Pi Operating System. And last click _**"Choose Storage"**_, and choose where storage can you install the OS and proceed to next Step.

![Pic 5](pic5.png)

- ### Click _**"Edit settings"**_, because we need to configure some settings.

![Pic 6](pic6.png)

- ### Set **_username and password_**, and add **_SSID and password_**, set the **_Wireless LAN country_** to PH. In the _**"Services"**_, enable **SSH** and save it.

![Pic 7](pic7.png)

![Pic 8](pic8.png)

- ### Now click _**"Yes"**_. And now we wait until the installation is done.

![Pic 9](pic9.png)

![Pic 10](pic10.png)

- ### Now the Raspberry Pi OS has been written to SDHC Card or SD Card. Now click Continue and remove the SD Card to your Computer.

![Pic 11](pic11.png)






## 2. Connecting to Raspberry Pi via SSH using terminal

- ### In the terminal, type ssh and your username and the hostname, **_"ssh username@hostname"._**

![Pic 12](pic12.png)

- ### Next, type **_"sudo apt update"._** After that, wait until the installation is done.

![Pic 13](pic13.png)

- ### Then, after the installation is complete, type again this line **_"sudo apt upgrade"._** Like the previous, wait until the process is done.

![Pic 14](pic14.png)

## 3. Deploying LAMP (Linux Apache MySQL PHP) Stack in Raspberry Pi

- ### Type this in terminal **_"sudo apt install apache2"_** and wait to complete.

![Pic 15](pic15.png)

- ### Next type this command **_"sudo apt install mariadb-server"_** and wait again until the process is complete.

![Pic 17](pic17.png)

- ### Then, this line **_"sudo mysql_secure_installation"_**.

![Pic 19](pic19.png)

- ### After that, input this command line **_"sudo apt install php libapache2-mod-php php-mysql"_**.

![Pic 20](pic20.png)

- ### Then after the process is complete, type this command **_"sudo apt-get install php *"_**.

![Pic 30](pic30.png)

- ### Select **_"apache2"_** and click enter

![Pic 21](pic21.png)

- ### Lastly, type this command **_"sudo apt install phpmyadmin"_**. And wait until the process is complete.

![Pic 22](pic22.png)

## 4. Enabling and Controlling Raspberry Pi using VNC

- ### Download RealVNC Viewer, to download [click this](https://www.realvnc.com/en/connect/download/viewer/)

![Pic 31](pic31.png)

- ### Install the Downloaded file, after installing, type this in terminal **_"sudo raspi-config"_**.

![Pic 28](pic28.png)

- ### And then, select **_"Interface Options"_**, and click enter.

![Pic 23](pic23.png)

- ### Enable the VNC, click enter.

![Pic 24](pic24.png)

- ### Open the **_RealVNC Viewer_** app and type the ip address of your raspberry

![Pic 25](pic25.png)

- ### Enter the username and the password and click **_"Ok"_**.

![Pic 26](pic26.png)

- ### Now your Raspberry setup is done.

![Pic 27](pic27.png)
