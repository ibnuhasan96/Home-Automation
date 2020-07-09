# Home-Automations
** HOW TO CONTROL AND INSTALL HEEDLESS RASPBERRYPI 4 AND ACCESS IT WITH PUTTY

1. Download raspbian image (Raspberry Pi OS) link: https://www.raspberrypi.org/downloads/raspberry-pi-os/

2. Download the etcher software to mount the raspbian image on the sd card link: https://www.balena.io/etcher/

3. Install the ssh file with no extension on the boot raspbian image(after booting with etcher software) steps: 

    a) open cmd on window
  
    b) navigate to image raspbian boot file 
  
    cd 
    
    c)type the drive for the booted file and hit enter 
  
    ex: f: 
    
   d) type echo and hit enter 
  
    ex: f:\echo >>ssh 

    e)check the boot image drive for ssh file
  
 4. Install putty terminal on the windows to access Raspbian OS.
 
 5. Configure Raspbian OS on putty, type
 
    sudo raspi-config
 
 6. Checking whether the raspberry pi is connect to internet using IP address
 
    ping raspberrypi @ ping YOURipADDRESSS
    
   
DONE!!

