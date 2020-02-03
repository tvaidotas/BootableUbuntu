Bootable Ubuntu 19.10 LTS

#Creating the bootable USB:
* DownLoad 18.04 LTS from https://ubuntu.com/download/desktop
* Plug in USB
* Run Startup Disc Creator
* Make sure iso and USB are selected
* Click 'Make startup disc'
* Wait (only takes a few minutes)
* Remove Drive

#Freeing up space on windows if dual-booting
* Press start button and search for 'Create and format hard disk partitions'
* Select the C: drive by right clicking it
* Select option 'Shrink volume...'
* Put 100,000 under the 'Enter the amount of space to shrink in MB'
* Click on 'Shrink'

#Installing Ubuntu 18.04 on the machine:
* Plug in USB while power off
* Choose install ubuntu (have to be quick or it will choose try ubuntu automatically)
* Choose 'English' then click 'continue'
* Choose 'English(UK)' then click 'continue'
* Choose 'normal installation' and 'install third-party software' then click 'continue'
* Choose 'Erase disk and install Ubuntu' then click 'install now'
* then click 'continue'
* click on 'london' then click 'continue'
* Set your name to 'QA-Admin' and password as 'password' then click 'continue'
* wait while it installs (should take about 10 minutes)
* when prompted, remove USB and restart computer - you may have to do this manually with the button on the machine
* log in with the credentials above

#What's new in Ubuntu:
* click next
* click next
* 'no, don't send' then click next
* click done

#Connecting to the Network: 
* click the three blocks in the top right corner
* click 'wired connection' and then wired settings
* click the 'cog' underneath wired
* navigate to IPv4 tab
* change the method to manual and enter the following:
	* Address: 192.168.1.<ask your trainer for a number to put here>
	* Netmask: 255.255.255.0
	* Gateway: 192.168.1.254
	* DNS: 8.8.8.8
	* Turn off the wired connection and turn it back on
