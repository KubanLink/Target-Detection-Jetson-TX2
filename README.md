#information includes, ubuntu for mac downloads and VM information only at this time.

# Target-Detection-Jetson-TX2
steps include map approach using raspberry pi and Jetson tx2 simplified with links and software packages.

<!-- from IPython.display import HTML -->

*Thank you Lockheed Martin for Funding the UAV Project 2020-2021*
<h1>This is a Notebook to keep track of my Progress.</h1>

<h2>Target Detection For Pi</h2>
---------------------------------------------

    
#This will link you what ROS

/*this is to help corbin devolop the code through his raspberry pi*/
https://www.youtube.com/channel/UC2aPsByptP3HXobjXgsXQsA

/*What is Open CV?*/
>There definitely needs to be a way to see civilians!
Thats is the purpose of CV... Read image videos and webcams,basic functions, resizing and cropping, shapes and text, wrap prespective, joining images, color detection, contour/shape determinations

*/Definitely will need to debug this for presentation purposes*/

What is CV is 3 Hours
----------------------------------------------------------
<iframe>https://www.youtube.com/watch?v=WQeoO7MI0Bs</iframe>

Let me summarize what Target Detection is...
*Database of Memory
*AI / Machine learning

RASPBERY PI WAY....
--------------------------------------
https://www.raspberrypi.org/documentation/remote-access/ssh/
https://nmap.org/book/inst-macosx.html
https://www.youtube.com/watch?v=lZcde050VMI

<h2>terminal</h2>

1.brew search nmap\
2.brew install nmap\
3.nmap -help\
4.ifconfig | greyt inet
    
   <h3>You will need to find software compatible w/ operating system</h3>
    
for securing your network it should already be secure with duckduckgo if not here is some examples.
https://www.raspberrypi.org/documentation/configuration/security.md
    
If you have not setup **SSH** review page requriements under **RASPBERRY PI WAY**
    
 After a VNC account is created start a server on the base computer you will like to view from.
    
                    Please Note

   > There may be issues on MacOSX in doing this process. Once ssh is connected you should now look into re-running any configuration commands from the beginning.>
    

<HTML src='//gifs.com/embed/found-ROz4yY' frameborder='0' scrolling='no' width='576px' height='360px' style='-webkit-backface-visibility: hidden;-webkit-transform: scale(1);'></HTML>
      
-------
    
# Now Learn how to install Unbutu for Raspberry Pi 
    October 26th, 2020
 ----------------------------
You will need to run the pi version even if you are working off the MacOS operating system.  You may also find that downloading it through MacOS will negate you to a different process and is independent from the OS and therefore may cause more trouble shooting when using the pi.
    
There are different verisons you may see differences in the processing speeds.
    
#### *NOTED ISSUES THAT YOU MAY EXPERIENCE.* 
     
>For some reason I could not get ubuntu to properly download onto my PI. It also occured to me that since I am working with another Operating system to run along side my Pi I most likely whipped my drive. 
    
 > Since the drive whiped I have had to pause for the weekend. I am a believer that I will find a solution to this! If I guess there is a way to force this software, and whatever erases...will just have to find out later. >

    --QUICK UPDATE TO THIS ANSWER: January 23,2021.
<h4>(information I ran into after 2 months)</h4> (I have learned that the reason for this failure is that there is no point in initially installing ubuntu onto a pi since the RAM is not powerful enough.) For this type of work you will need to allocate at least 40 GB to a hard disk and process more than 1GB of ram or a little over 1028 MB. You will find it in your best interest to utilize another type of PC during this work.) I have the solution to this problem but I will need to comeback to it because this is not part of my project.
    
    If you will like to use a VM properly for ubuntu you will need to dynamocally allocate space to a disk and save everything directly to a hard drive in short. (This is completely simplified and I recommend you do not spend time trying to get 512MB to run an entire operating system a long the pi...)
    
    Feel free to enjoy to glimpse at the troll documentation of someone doing it.
    
[/This is not Ethical/] -
https://www.raspberrypi.org/forums/viewtopic.php?f=62&t=14705
   -----------------------------------------------------------
    
<h2>Target Detection for Nvidia Jetson TX2</h2> 

     YOU MAY NEED VM TO TROUBLE SHOOT. 
This is not a warning this is to save you time when you realize there is issues with the system you turned on and failing to 
    
|Please make sure that you use the correct operating system.|
    

- __Start by finding the correct package.__You will have multiple options in running this board. There will be a list of options for each operating system found at this page.
    
**Note these instructions are only for host to target:**
    
For More references check the NVIDIA Website and search through jetson and you will find multiple packages for the particular AI software. 
**[Check out the NVIDIA SDK.](https://developer.nvidia.com/EMBEDDED/Jetpack)**

+ I would like to first suggest that if you have the privelege of turning the board on without trouble shooting it, please make sure you install the correct version of ubuntu. If the software version is not 14.0.4, Be prepared to trouble shoot and ignore all directions from here on.
    
+ However, if you are wanting to understand the VM you will need for the host computer then I will be covering ettiqute I made up for myself so you will not encounter the failures I did. And yes, these failures will cause you to stay up for weeks.
--------------------------------------------------------------
<h3> Steps for VM</h3>

    1. start by making sure when you activate the machine you have the correct download from oracle.
    
    2. Next, you will want to include any extensions into the system.
    

    3. You will want to make sure that you have set the USB to the correct port.

    4. You may also find it important to download the desired ubuntu version you will need for you board. (anything after July 2020) is compatible with ubuntu 14.0.4. However, do note there has been tuttorials using VM and Multipass which will be unecessary unless you do not prefer working from img.
    
    5.The benefit of this system may delete feasbily allowing you to correct any mistakes over time to your system. So feel free to interchage the opt disk.
    
    6.You will notice there is a constant override of logs in your VM. I advise you begin to save the system of the indicated PC you will be working from. Yet, If you are managing a big project I recommend you utilize a hardrive.
    
    7. Now, begin booting systems and finally you be able to run install ubuntu. 
    
    8. Yes you will want to ERASE the disk and install ubuntu. You also have the opportunity to run mutiple allocated disks interchanglebly but this may become messy to deal with unless you are required to manage multiple systems for one project.
    
--------------------------------
<h4>In case you are stuck at the homescreen</h4>
     **hold control+fn ...then click f3 and continue holding all three and final hold option at login screen.**
    
    
    


