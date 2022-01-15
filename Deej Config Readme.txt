Readme

1. After plugging in open "device manager" by opening start menu and typing that in (or hit Winkey+R and type in "Devmgmt.msc")

2. Under Ports (COM & LPT) look for the CH340 and take note of what "COM" it is (Ex. "COM1" or "COM2" etc)

3. Download my config.yaml file on github and copy it into the directory you're storing deej in (overwrite it if it's already there)

4. Open the config.yaml file, scroll down to the bottom and check where it says "com_port: COM5" change that COM5 to whatever COM port yours is from step 2

5. Startup deej, you should see the icon in your taskbar, and give it a whirl. Modify the config as necessary to yoru own use

6. If your sliders are "backwards" change the "invert_sliders: false" to "invert_sliders: true"