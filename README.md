# Adding ISTPrinter on MacOS 10.15.X or Higher
This guide will assist staff and faculty in installing the ISTPrinter on their Mac machines.   
Note: **YOU MUST BE INSIDE THE BUILDING ON AN ETHERNET CONNECTION OR ON THE VPN WHEN USING WIFI OR FROM OFF CAMPUS FOR THIS TO WORK**

1. Download and install the 2 drivers for MacOS that are located on our Github repository. These drivers will install the needed software for the printer. To install them, you simply need to double click them, and go through the install process. Shouldn't take long and is straight forward.

2. Click on the apple on the top-left corner of the screen.

3. Click 'System Preferences'

4. Click on 'Printers and Scanners'

![printers](pictures/printers.png)

5. In the new window, look for the + and click it

![add](pictures/add.png)

6. In the blank space beside the options that say "Default, IP, and Windows", Right click or hold control and click, then select "customize toolbar. Find the "Advanced" icon and drag that next to the shaking icons to add it to the toolbar and hit done. 

![advanced](http://g.recordit.co/yRqd8XTR3r.gif)

7. Click the "Advanced" icon, and let it load. Once it loads, change the type to "Windows printer via spoolss" and device to "Another Device. Once those have been set, change URL box to say smb://printers/ISTPrinter    
In the Name field, add ISTPrinter to avoid confusion. 


![setup](http://g.recordit.co/e0cyf3969z.gif)


8. Under "Use" click "Select Software" and scroll down until you see Konica Minolta 754e PS. Select this option. Hit OK when you have changed the other settings. This will lead you to a next page that asks for more set up options. You will want to set each one as the following: Paper unit LU-301, Finisher is FS-535, Punch Unit is PK-521 2/3 hole. 

9. Once the printer has been set up, you can right click it and set as default. Then run a test print by opening textedit or word and writing "test". This should bring up a window asking for your credentials. **Fill in your full UNO email address and your UNO email password to log in.** If it doesn't take your email address, try just your NetID (Just remove the @unomaha.edu). Sometimes it can be picky. If you don't want to enter your credentials every time, check the box to store it into keychain. After this, the printer is all set up!

Note: If you would like to to hole punch and/or staple, you will need to click the dropdown during page setup that says layout, choose printer features and scroll down. The options are in the list somewhere.
