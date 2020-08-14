# Switch Emulation

Guide for emulating Nintendo Switch Games on PC
Unfortunately, since all of the games on the drive are in a special format that reduces file size, you need to use a tool in order to make them playable on PC, and the amount of time it takes to make it playable varies a lot depending on your setup.

## Requirements

[Ryujinx](https://ryujinx.org/download) Download the Windows version

[prod.keys](https://drive.google.com/file/d/1aTgSpLSSDsTUrKpWgCJLKlvUPO5Csxb9/view?usp=sharing) (log into the account that has access to the drive before clicking this link)

[Nintendo Switch Firmware](https://mega.nz/file/xVwVFazC#sFkKEKkHhp2YEcqR5UQhAg_qxEPfZq8oRUalgleKVDA)

[nsZip](https://github.com/nicoboss/nsz/releases/download/3.1.1/nsz_v3.1.1_win64_portable.zip) (Windows only)

[Games](https://darkmode.123bluestacks123bluestacks.workers.dev) (this one is the recommended version, has dark mode, search features, and a mirror, but [this one](httpsL//bit.ly/peakstash) has bulk loading, which is slower but is better in some situations) Both are powered by [rclone](https://rclone.org/), [Cloudflare workers](https://www.cloudflare.com/), and [goindex](https://github.com/alx-xlx/goindex)

## Setting up Ryujinx

1. Download ryujinx, prod.keys, and the Nintendo Switch Firmware

2. Extract the ryujinx files from the file, and run `Ryujinx.exe`

3. In Ryujinx, click on `File` then `Open Ryujinx Folder`, then copy the prod.keys file into the system folder

![gif4](https://i.imgur.com/xcJbmfy.gif)

4. Close and reopen Ryujinx, then select `Tools` then `Install Firmware` then `Install firmware from a XCI or ZIP` Navigate to wherever you installed the firmware file, then select it in Ryujinx, click yes to the confirmation

![gif2](https://i.imgur.com/ygTR2YM.gif)

## Using nsZip to convert the files to usuable files with Ryujinx

1. Download nsZip from the link in the Requirements section and the game that you want to play

2. Open File Explorer and click on the address bar on the top, then type `C:\Users\`, go into the folder with the name that matches the name of the user that you're currently logged into, make a folder named `.switch`, and copy the prod.keys file into this new folder.

![gif1](https://i.imgur.com/u7Suj9y.gif)

3. Extract the files from the nsZip zip file, then run `nsz.exe`

4. Click `Select Input File/Folder`, then navigate to the game file you downloaded using the file browser

![image3](https://i.imgur.com/UeM6iWy.png)

5. After you select the game file, click `Select Output File/Folder` and select where you want the new game file to be, make sure it's somewhere you'll remember

![image4](https://i.imgur.com/HAeCjOk.png)

6. Wait. Depending on how big the game is supposed to be and how powerful your computer is, it could take minutes to hours to generate the game file.

## Playing

1. Now that the file is done, go back into Ryujinx and click `File`, then `Load Application from File`

![image5](https://i.imgur.com/sSdDwbT.png)

2. Go to where the file is and select it

3. Ryujinx should automatically start the game

4. That's it!

**Frequently check for Ryujinx updates by selecting `Help`, then `Check for Updates`**
