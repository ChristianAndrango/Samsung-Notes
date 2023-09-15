# Mask Galaxy Book laptop 
# edited  by manas c
This .bat script will allow you to mimic your windows pc as a Galaxy Book laptop, this is usually used to bypass Samsung's restriction on some applications such as Samsung Notes by modifying the registry. _Third-party antivirus applications such as Kaspersky and Bitfinder detecting the .bat file as a threat, it is a false positive! Just whitelist it or modify the registry yourself if that is the case._

### 4 versions
- Galaxybook_mask.bat
- Galaxybook_mask(no startup).bat
- samsungnotes-better.bat: Non startup version that launches samsung   notes, can be used as  a makeshift shortcut
- (Recommended)samsungnotes-betterv2.bat:This version stores the previous  registery key that it changes  and then reverts the key back  once the  app has  been launched

# If you're dealing with that annoying "connecting to a service" pop-up or Samsung Notes freezing while trying to sync, here's what you can do:

1. Firstly, you need to install the Winget package manager. You can download it from this [microsoft store link](https://www.microsoft.com/store/productid/9NBLGGH4NNS1?ocid=pdpshare).

2. After installing Winget, open a Command Prompt window and enter the following command: `winget install 9P98T77876KZ`. This command will install the Samsung Account application.

3. Once the Samsung Account application is installed, you should launch the script named "GalaxyBookMask(no startup).bat" from this [GitHub link](https://github.com/kellwinr/galaxybook_mask) or this repository.

4. After the script has been executed, open the Samsung Account app on your PC from the Start Menu and log in using your Samsung account credentials.

5. Finally, you can open Samsung Notes using the method used in my video, and it should work as expected.



#### Credit goes to [r/hedehede81](https://www.reddit.com/user/hedehede81), [via reddit](https://www.reddit.com/r/GalaxyBook/comments/15v05bv/samsung_notes_does_not_run_on_nongalaxy_book/?utm_source=share&utm_medium=web2x&context=3)
_Feel free to modify the script to your desired behaviour._

# How to install Samsung Notes
### If you cannot find the Samsung Notes application in the Microsoft Store, you can install it with Winget.
1. Open terminal or cmd (command promt)
2. Type in `winget install 9NBLGGH43VHV`
3. Follow the instructions & type "`Y`" to continue
4. Wait for it to download and install
5. Finish! 
