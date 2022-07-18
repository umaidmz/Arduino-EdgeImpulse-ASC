#### **Umaid Muhammad Zaffar**
#### **Data Scientist**
#### **Aceso Ai Ltd**
#### **umaid@aceso.no**
<br>

The following guide will help you start classifying the sounds in your environment using Arduino Nano BLE 33. Follow the steps carefully and if there is any problem, feel free to ping me.

**Prerequisites**
- Install Arduino IDE 1.8.19
- Install nRF Connect App on Smartphone

**Steps on Computer**
1. Open `hw_audio/Arduino/Sketch/Continuous_Inference.ino`
2. Click on Sketch from menu and go to Include Libraries.
3. Add .ZIP folder and find `hw_audio/Arduino/edge-impulse/Arduino Library Versions/ei-audio-analytics-arduino-1.0.** `(Use Latest)
4. Go to Manage Libraries and add ArduinoBLE Library.
5. Connect Arduino via USB to your computer and set the Port on your IDE
6. Compile your sketch and ignore warnings.
7. Open Serial Monitor and the output will be `Disconnected from central`.

**Steps on Mobile**
1. Open nRF app on your mobile and refresh the scanner.
2. Connect to `Arduino Environment Sensor`.
3. Expand `Unknown Service`.
4. Click on the icon with three arrows pointing down.
5. The classified sound is in value.