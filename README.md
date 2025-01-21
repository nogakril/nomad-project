# "Nomads and Technology in Extreme Conditions" - Final Project


### How to start working in Arduino IDE:
1. Open "Board Manager" -> Download the package "esp32" (by Expressif)
2. Choose the port and the board "SEP32 Dev Mode"
3. Set: Tools -> Upload Speed -> 115200
4. Open: Tools -> Serial Monitor -> Set: baud 115200 (on the top right dropdown menu)
5. Upload Code: Press long on the "BOOT" button on the board, and release when the writing starts.

### How to set a phone as a scanned device:
1. Turn on the Bluetooth.
2. Download the app nRF Connect.
3. In the "Peripheral" tab: Add Advertiser -> Edit the name.
4. Switch the radio button to "Locked"
5. In the code: Edit the "name" variable to match the name you defined.

![image](https://github.com/user-attachments/assets/4768498a-11f1-40b6-9bc1-385d6fbd5006)

### How to write code for the led ring:
1. Install library: Tools -> Manage Libraries -> Adafruit NeoPixel
2. Connect the data pin to D15 (or other pin, make sure to change in the code)
![image](https://github.com/user-attachments/assets/bef5a7af-349c-4343-9399-6208b06d412c)

