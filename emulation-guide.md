# Switch Emulation

Guide for emulating Nintendo Switch Games on PC
Unfortunately, since all of the games on the drive are in a special format that reduces file size, you need to use a tool in order to make them playable on PC, and the amount of time it takes to make it playable varies a lot depending on your setup.

## Requirements

[Ryujinx](https://ryujinx.org/download) Download the Windows version

[prod.keys](https://drive.google.com/file/d/1aTgSpLSSDsTUrKpWgCJLKlvUPO5Csxb9/view?usp=sharing) (log into the account that has access to the drive before clicking this link)

[Nintendo Switch Firmware](https://mega.nz/file/xVwVFazC#sFkKEKkHhp2YEcqR5UQhAg_qxEPfZq8oRUalgleKVDA)

[nsZip (Windows only)](https://github.com/nicoboss/nsz/releases/download/3.1.1/nsz_v3.1.1_win64_portable.zip)

Games (get them from the switchgames folder on the drive, base folder is the base game, updates are updates for the games, dlc is dlc for the games, use google drive's search to find the games, spreadsheet coming soon)

## Setting up Ryujinx

1. Download ryujinx, prod.keys, and the Nintendo Switch Firmware

2. Extract the ryujinx files from the file, and run `Ryujinx.exe`

3. In Ryujinx, click on `File` then `Open Ryujinx Folder`

![image1](https://i.imgur.com/py1bM4X.png)

4. Copy the prod.keys from wherever you downloaded it to into the system folder inside the Ryujinx folder

5. Close Ryujinx and reopen it, then select `Tools` then `Install Firmware` then `Install a firmware from XCI or ZIP`

![image2](https://i.imgur.com/thfhpm0.png)

6. Navigate to wherever you installed the firmware file, then select it in Ryujinx

7. Confirm that you want to install Firmware 10.0.4

## Using nsZip to convert the files to usuable files with Ryujinx

1. Download nsZip from the link in the Requirements section and the game that you want to play

2. Open File Explorer and click on the address bar on the top, then type `C:\Users\`

![gif1](https://i.imgur.com/awUPnT0.gif)

3. Select the folder with the name that matches the name of the profile and make a folder inside named `.switch`

4. Copy the prod.keys file into the `.switch` directory

5. Extract the files from the nsZip zip file, then run `nsz.exe`

6. Click `Select Input File/Folder`, then navigate to the game file you downloaded using the file browser

![image3](https://i.imgur.com/UeM6iWy.png)

7. After you select the game file, click `Select Output File/Folder` and select where you want the new game file to be, make sure it's somewhere you'll remember

![image4](https://i.imgur.com/HAeCjOk.png)

8. Wait. Depending on how big the game is supposed to be and how powerful your computer is, it could take minutes to hours to generate the game file.

## Playing

1. Now that the file is done, go back into Ryujinx and click `File`, then `Load Application from File`

![image5](https://i.imgur.com/sSdDwbT.png)

2. Go to where the file is and select it

3. Ryujinx should automatically start the game

4. That's it!
