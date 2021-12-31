# xsetwacom-areachanger
Dead simple bash script for quick tablet area resizing. 

## Required
- xsetwacom (https://github.com/linuxwacom/xf86-input-wacom/wiki/xsetwacom)

## Setup
- `chmod +x xsetwacom-areachanger` in the same directory as the file to make it executable
- `./xsetwacom-areachanger` in the same directory. 
- to run it in anywhere, [add it to your $PATH](https://www.howtogeek.com/658904/how-to-add-a-directory-to-your-path-in-linux/)

## Usage
- run the program after you plug in your tablet devices
- after changing the default values with a Text Editor, you can just spam ENTER when you run the program and quickly resize the tablet.
  + ```
    #default values. change them for quick use
    #to revert changes, restart the session or re-run the program with "1.0" resolutionMultiplier value
    defaultTabletName="Wacom Intuos PT S 2 Pen stylus"
    defaultScreenResolution=(1525 858)
    defaultResolutionMultiplier=6
    ```
    (These defaults does increase my tablet resolution by 6x. Which results in much faster movement of cursor.)
- yes it is confusing but put your **Stylus** name as Tablet name when asked.


Resized area will be at the center of the tablet.







