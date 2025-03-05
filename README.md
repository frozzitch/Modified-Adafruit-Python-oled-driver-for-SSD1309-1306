# Modified-Adafruit-Python-oled-driver-for-SSD1309-1306
I had troube using Adafruit SSD1306 driver for my project with SSD1309 so I modified it to work with this display. Display was little bit messy with low brightness. To avoid this its necessary to edit Initialization and Show sections. I hope this will help someone facing same problem.

ONLY WORK WITH I2C

Tested on Raspberry Pi 3b+, Raspberry Pi OS Legacy (bullseye)


# Installing and setting up the display
>https://www.the-diy-life.com/add-an-oled-stats-display-to-raspberry-pi-os-bullseye/

# Replacing installed driver
Replace file in folder where the script is installed. In my case:
>/usr/local/lib/python3.9/dist-packages
