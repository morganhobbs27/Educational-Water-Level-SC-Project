# Add all educational steps here:
## How to put sensor and boards together:

- Attatch on pins to each board.
  
- Attatch each board onto FeatherWing tripler.
  
- Connect and soulder wires onto sensor and OLED display microcontroller, as shown in pictures below. (red and blue will cross).
  
- Combine all three sensors on the feather board tripler, as shown below.

- Connect micro USB to computer

## Downloading Arduino to computer and basic code flash
- Download Arduino software onto computer - download all neccesary libraries:
 ✅ Adafruit GFX Library
 ✅ Adafruit SSD1306
 ✅ Adafruit BusIO
  ( Quit Arduino program and re-open to refresh libraries )
  
- Go to Tools → Board → Boards Manager… Search for "Adafruit SAMD" and install.

- Go to Tools → Board → Adafruit SAMD Boards → Select "Adafruit Feather M0 Adalogger"

- Next, go to Tools → Port → Select "/dev/cu.usbmodemXXXX"

- Arduino program download, run basic code assure it is working correctly – flashing word to the OLED screen. (Found in Github file "Basic_CodeStep1" )  Copy and paste this code into Arduino - can change word in line #41 to flash different word to OLED screen. "upload" will flash code.

- Flash the adapted code to run water level sensor in Arduino.  

- Once code runs correctly, unplug from computer and plug in battery, code should still run with only the battery plugged in. 

- Place sensor in housing with battery plugged in & deploy.  
