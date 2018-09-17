# ghana-computers
Some details for the Ghana project computers.

## Our current state

We will assume that the computer has Windows installed. We will replace the Windows operating system with the Ubuntu operating system. The reason for doing this is: we at CWAR have worked with the machine learning packages on Linux. With Windows support starting to be ramped up (by makers of the machine learning packages), this situation may change over the next few months. But until we test out these new developments we will use Linux. 

All of this data is easily found on the Internet. This is just my attempt to collate them in one place for convenience.  

## Making an USB installer
An useful website is: https://tutorials.ubuntu.com. In particular we will use the following: https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-windows#0 as guidance. 
 
 - Download Ubuntu on to your computer from: https://www.ubuntu.com/download. We will use version 18.04 LTS. LTS stands for Long Term Support. It basically means this particular version of Ubuntu is stable and will be a prime focus for the Ubuntu people for next few years. There are many "flavors" for Ubuntu. We will use Ubuntu Desktop
 - Download the USB burner software Rufus onto your computer from: https://rufus.akeo.ie/. 
 - Launch Rufus by double clicking on the downloaded file. 
 - Plug in the USB stick your are willing to sacrifice. Rufus will automatically detect it. It is recommended that no other external storage devices are plugged in. When creating the USB installer all the data on the USB is completely wiped out. Having no other external storage device plugged in prevents accidental wipe out of data. 
 - In Rufus select the Ubuntu ISO file you downloaded in the first step. Then make sure `Partition Scheme` is **MBR** and `Target system` has **UEFI**. Start the burn. Make sure `Write in ISO Image Mode` is selected. Wait for it to complete. Safely eject the USB and now you have an USB installer that you can use to Ubuntu on multiple computers. 
- In the future, you may want to install the latest version of Ubuntu. You can do the process of creating a USB installer on an Ubuntu machine as well. Please see the Ubuntu tutorials website above. The process is roughly the same. You just have to use a similar software on Ubuntu for burning the installer. 

## Installing Ubuntu
Now we use the USB installer we made above to convert a Windows computer to Ubuntu.

 - Shutdown the computer. 
 - Plug in the USB installer stick you made above. 
 - Restart the computer. When the screen shows some signs of life, press the **F2** button and hold it. This will bring the boot screen. 
 - On the boot screen choose that you want to use the USB. Note you have to navigate using keyboard here usually. Mouse does not work. 
 - Choose you want to Install Ubuntu. 
 - Follow prompts and finish installation (It will take a few minutes depending on internet connection). I typically make the following choices when asked: 
   - `I don't want to connect to a wi-fi network now` (Note you will still need to have internet connection. Selecting this option makes the installation faster as all the available updates are not installed up front). 
   - `Normal installation` 
   - `Erase disk and install Ubuntu` 
 - When it says restart, please do. But before it start up remove the USB. You may see a lot of messages on the screen. Wait until it prints out to its heart content. Then power down and restart. Everything should work. Note: If you dont remove the USB before restart it will get back to boot screen you got at the beginning. If this happens just shut down, remove USB and restart.  
 
The procedure to upgrade to the next LTS version of Ubuntu is very similar to the above
 
## Super quick Ubuntu/Linux tutorial
Today we will look at some basic Linux usage and install some packages/software that will be useful. 

### Getting the terminal (command prompt)
 - `CTRL-ALT-t` brings up the terminal. You can type commands here to get things done. Note the command prompt is one way to interact with Ubuntu. You can also interact with the mouse but doing it from the command line can be super useful. Here we will look at a very tiny set of commands to get started. 
### Directory navigation/creation/etc
 - The command to create a new directory/folder is `mkdir`. So to create 

## Some useful packages
  
