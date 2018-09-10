# ghana-computers
Some details for the Ghana project computers.

# Installing Ubuntu

We will assume that the computer has Windows installed. We will replace the Windows operating system with the Ubuntu operating system. The reason we are doing this is that scientific computing works very well on Linux. Our main machine learning tools work well on Linux. With Windows support starting to be ramped up, this situation may change over the next few months. But until we test out these new features we will use Linux. 


An useful website is: https://tutorials.ubuntu.com. In particular we will use the following: https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-windows#0 as guidance. 
 
 - Download Ubuntu on to your computer from: https://www.ubuntu.com/download. We will use version 18.04 LTS. LTS stands for Long Term Support. It basically means this particular version of Ubuntu is stable and will be a prime focus for the Ubuntu people for next few years. There are many "flavors" for Ubuntu. We will use Ubuntu Desktop
 - Download the USB burner software Rufus onto your computer from: https://rufus.akeo.ie/. 
 - Launch Rufus by double clicking on the downloaded file. 
 - Plug in the USB stick your are willing to sacrifice. Rufus will automatically detect it. It is recommended that no other external storage devices are plugged in. When creating the USB installer all the data on the USB is completely wiped out. Having no other external storage device plugged in prevents accidental wipe out of data. 
 - In Rufus select the Ubuntu ISO file you downloaded in the first step. Then make sure `Partition Scheme` is **MBR** and `Target system` has **UEFI**. Start the burn. Make sure `Write in ISO Image Mode` is selected. Wait for it to complete. Safely eject the USB and now you have an USB installer that you can use to Ubuntu on multiple computers. 
- In the future, you may want to install the latest version of Ubuntu. You can do the process of creating a USB installer on an Ubuntu machine as well. Please see the Ubuntu tutorials website above. The process is roughly the same. You just have to use a similar software on Ubuntu for burning the installer. 
