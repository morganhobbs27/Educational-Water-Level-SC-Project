
# Add all educational steps here:
## How to put sensor and boards together:

- Attatch on pins to all three of the boards.
  
 <img width="217" height="170" alt="Screenshot 2026-04-13 at 11 31 24 AM" src="https://github.com/user-attachments/assets/fca5c5a6-f606-42c1-88f7-65c4ec07b820" />
 
- Attatch each board onto FeatherWing tripler.
  
- Connect and soulder wires onto sensor and OLED display microcontroller, as shown in pictures below. (red and blue will cross).

  <img width="484" height="271" alt="Screenshot 2026-04-13 at 11 32 15 AM" src="https://github.com/user-attachments/assets/1b7060d7-fff9-4b39-8e16-54b3ca851091" />

- Combine all three sensors on the feather board tripler, as shown below.

<img width="517" height="239" alt="Screenshot 2026-04-13 at 11 32 57 AM" src="https://github.com/user-attachments/assets/6229418a-bf73-4e07-9e3c-f911af770203" />

- Connect micro USB to computer

## Downloading Arduino to computer and basic code flash
- Download Arduino software onto computer - download all neccesary libraries:

 📌 Adafruit GFX Library
 📌 Adafruit SSD1306
 📌 Adafruit BusIO
 
( Quit Arduino program and re-open to refresh libraries )
  
- Go to Tools → Board → Boards Manager… Search for "Adafruit SAMD" and install.

- Go to Tools → Board → Adafruit SAMD Boards → Select "Adafruit Feather M0 Adalogger"

- Next, go to Tools → Port → Select "/dev/cu.usbmodemXXXX"

- After Arduino program download, run basic code ensure it is working correctly – flashing words to the OLED screen. (Code can be found in Github file "Basic_CodeStep1" )  Copy and paste this code into the Arduino project you have been working in - can change word in line #41 to flash different word to OLED screen. "upload" will flash code.
  
## Flashing adapted code to run sensor and get distance measurements from Ultrasonic Rangefinder
- Flash the adapted code to run water level sensor in Arduino.  

- Once code runs correctly, unplug from computer and plug in battery, code should still run with only the battery plugged in.

## Housing and Deploying sensor
- Place sensor in housing with battery plugged in & deploy.  
