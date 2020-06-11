#### Here i will guide you through recovering your Windows 10 OS from an infection.
This guide is only for some viruses and can't help you against ransomware!


### Sign's of infection:  

- When a virus is infected on to your system, icon's and taskbars can flicker breifly.  
- Slower than usual performance while gaming or high background usage that mysteriously dissappears when you open task manager.  
- Multiple Apps not working that are usually fine.  
- Windows Update is not working.  

These are only a few sign's of infection, some can be unique, obvious or subtle.  


### Removal of the virus:  

Using a well known antivirus is great for preventing infection; BUT! in some cases it is totally useless if you do not update your system or its trail has expired.  
At this time of writing i prefer (Malwarebytes)[https://www.malwarebytes.com/premium/]. But like all technology it changes and evolves which is why its important to read up on the latest info.  

First lets use Malwarebytes Antirootkit to scan you system https://www.malwarebytes.com/antirootkit/  
When you extract and run the app click the update button before scanning.  
This will scan your system for malicous software and remove it.  
(if this part fails, try this again after following the repairing section)


### Repairing the damage:  

OpenCommand prompt in admin mode, this is usually found by right clicking the start button and opening Command Prompt.  
Type: 
> dism.exe /Online /Cleanup-image /Restorehealth   

and hit enter.  
Then  
> sfc /scannow

If both scan's report that fixes/repairs have been made then its a good sign your system has been repaired.  
If it fails then more work is needed to remove the virus. (see the hard way)  


### You wanna do this the hard way? we can do this the hard way!

Some viruses can be persistent and require special treatment.  

Option 1: Install Malwarebytes and start a full scan. https://www.malwarebytes.com/premium/  

Option 2:  
- Open your task manager and browse through your running apps.  
- If you see a app that looks suspicous look up the name of the app in google search like so:
> Is drgjytf.exe a virus?  

Then once you find the app, go to This PC and click the search on the top right.  
Type in the name of the suspicous app and search.  

Once you find the location of the file you will most likely not be able to just simply delete it while its running.  
You will have to do this through safe mode, take note of the files location.  
Open the start menu > click power > Hold the shift key and click restart.  
Once in the menu go to: Toubleshoot > Advanced Options > Startup Settings and click restart.  
Then select option 4: Enable Safe Mode and you will start windows 10 in safe mode.  
Now navigate to the files location and choose to delete the file.  
If the file has a folder with a similar name with other files in it, delete those aswell.  
Now restart windows normally and follow the repairing the damage and cleaning up section in that order.  


### Cleaning up:

First uninstall all antiviruses on system that is not Windows Defender.
Check windows update for updates.  
If you want to search for a 3rd party antivirus to replace what you have been using then do you research, if not stick to Windows Defender.
You MUST have only one antivirus running, windows defender is designed to be disabled with the installation of a we antivirus but any more than that can cause problems.  

If you wish to do further cleaning see my guide here in section 5: https://tiberiusmoon.github.io/Tibs-Guide-to-Windows-10/  



That should resolve the most basic infections to your system, if you have a particularly nasty infection google search the virus in question for idea's or reinstall your OS.

Good luck and try to have fun!
