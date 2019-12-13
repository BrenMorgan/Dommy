# Dommy

Steps to bypass windows 10 defender and gain admin access

1. boot usb win 10 from USB Install
2. first windows window = next
3. at install prompt click "repair your computer" //DO NOT CLICK INSTALL
4. click Troubleshoot - system image revovery - Windows 10
5. At "re-image your computer" prompt click CANCEL
6. now click next - Advanced - Install A Driver - OK
7. Now you have an explorer file manager window....
8. Goto install drive (probably :/C drive)
9. goto /Windows/system32
10. find file called cmd click it once then right click and copy, right click again anywhere and paste then right
click and refresh and check you have two cmd files IE: cmd + cmd-copy
11. Now scroll further down and find file called Utilman
12. click once on it and right click and rename to Utilman1
13. Right click and refresh, then go up to cmd-copy and change its name to Utilman <----(capital U)
!4 again right click anywhere and click refresh
you should now have original cmd + Utilman + Utilman1 in the file system
 - Now just close everything until you get to blue screen and click on "Continue" and remove USB
 
 - Now you are booting original Win10 - now to bypass windows defender
 
 1. at login screen click the power button and Hold down SHIFT key and click restart
 This will start revovery options
 2. Click Troubleshoot then Advanced Options then Start-up Settings
 3. Click restart
 
 - reboots into safe mode options
 
  4. in startup settings choose 6 (enable safe mode with command prompt)
  
  - OK NOW THE IMPRTANT BIT
  
  in the login screen at the bottom to the left of the power button is the Utilman (Utility Manager) 
  this we changed to cmd earlier, so when you click it the command prompt will open.
  
  Windows defender might pick up on this.
  so as soon as you click it and the command prompt opens you quickly type
  
  start cmd
  
  this will open another command prompt which we will use to add an admin account
  first type
  
  whoami
  it should say = NT authority\system
  
  If so congrats you have admin console
  
  - now to create a new account and give it Admin Priv
  
  type this to open password dialoge box
  
  control userpasswords2
  
  find the admin account and change password to what ever you like
  or create a new account and give yourself admin priv
  
  apply, ok restart and she is yours
  
  # DENY US NOT
 


