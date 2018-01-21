Installation
************
The BTS-CE application is distributed in Docker containers to simplify the installation. Docker is a way to distribute self-contained applications easily. We provide Docker images for the Community Edition that you can very easily install and upgrade on your PC, Laptops, or server. The docker hub repositories are located at https://hub.docker.com/u/bodastage/

Although this is the recommended installation method, you can still download the individual components from the Bodastage Solutions github page and install them as your see fit.

Requirements
============
To run BTS-CE Docker containers, you will need:

* A 64 bit operating system. (Windows 10, Linux, MacOSX)

* Atleast 10 GB disk space

* Atleast 4 GB RAM


Windows  
=======

1. Enable HyperV or install Oracle VirtualBox 

2. Download and install Docker Community Edition for your platform from https://www.docker.com/community-edition#/download. Optionally, install Docker Toolbox depending on your Windows OS version for Windows users.

3. Download the latest release files for BTS-CE from https://github.com/bodastage/bts-ce/releases

4. Unzip the BTS-CE realease files. Open **cmd** as an Administrator and run **manager.bat up -d**

4. Access the web client at localhost or <docker-machine ip> for Windows users

Enable HyperV or Install Oracle VirtualBox 
------------------------------------------

When installing Docker CE on Windows. You can either use HyperV or Oracle VirtualBox.  These are used to create virtual machines from which your containers will run. 

HyperV is an optional feature available on Windows 10 Enterprise, Professional, or Education. If you are using Windows 10 Home or any other windows release, you will need to upgrade or use Oracle VirtualBox.

To enabled HyperV, follow the steps at https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v

Download Oracle VirtualBox from https://www.virtualbox.org/

.. Add note on which windows build versions are supported 


Lunix and MacOSX
================

Follow the steps below to install the application:

1. Download Docker Community Edition for your platform from https://www.docker.com/community-edition#/download. Optionally, install Docker Toolbox depending on your Windows OS version for Windows users.

2. Download the latest release files for BTS-CE from https://github.com/bodastage/bts-ce/releases

3. Unzip the zip file in 2) to your desired location

4. Run manage.sh start

5. Access the web client at localhost or <docker-machine ip> for Windows users