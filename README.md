# OpenCoreVersion ([Download](https://github.com/alphascorp/OpenCoreVersion/files/8334539/OpenCoreVersion.2.2.1.dmg.zip))

---

<h4 align="center">Display the version of OpenCore and OpenCore Legacy Patcher (OCLP)</h4>

---

### Easy to use

This app makes it easy to display the current version of OpenCore and OCLP on your system with a simple interface.


<p align="center"><img width="400" alt="OpenCoreVersion.app_GUI" src="https://github.com/alphascorp/OpenCoreVersion/blob/main/Screenshots/Main%20GUI.png"></p>

The following Terminal commands are no longer necessary for this.


### Terminal commands given as a reminder
:point_down:
<details> <summary> View Spoiler: (Terminal commands)  </summary>

  - For displaying OpenCore version:
```
nvram 4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:opencore-version
```


  - For displaying OCLP version:
```
nvram 4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:OCLP-Version
```

</details>


### :warning: Error message at first run

The first time you run the program, you may get the following error message:
Impossible to open "OpenCoreVersion.app" because this app comes from an unidentified developer.


This is because an attribute is added so that it can ask the user for confirmation the first time the downloaded program is run, to help stop malware. After confirmation, the attribute should be removed automatically, and then the program will run normally.

But if the program does not run, just remove this attribute (once and for all) with the following procedure:
1. Open Terminal (Applications -> Utilities -> Terminal.app)
2. Write or Copy/Paste (in Terminal) the following line
```
xattr -rd com.apple.quarantine 
```
3. Type a space
4. Drag and drop "OpenCoreVersion.app" next to it, from the Finder

Now the program will run normally.

#### :white_check_mark: Scanned with ClamXav and guaranteed virus and malware free. :white_check_mark:


## Credits

[ How to remove com.apple.quarantine](https://discussions.apple.com/thread/3145071)
