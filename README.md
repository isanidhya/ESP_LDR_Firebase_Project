# ESP LDR Firebase Project

This project uses ESP8266 and ESP32 to read values from two LDR sensors and upload them to Firebase. The values are also displayed on the Serial Monitor.

## Components Used

- NodeMCU (ESP8266)
- ESP32
- Two LDR sensors
- Resistors
- Breadboard and jumper wires

## Circuit Diagram

(Insert your circuit diagram here)

## Code

### ESP8266

The Arduino code for ESP8266 is in the `ESP8266/LDR_Firebase_ESP8266.ino` file. 

### ESP32

The Arduino code for ESP32 is in the `ESP32/LDR_Firebase_ESP32.ino` file.

### Key Points:

1. **Wi-Fi Setup:** Ensure you have the correct Wi-Fi credentials in the code.
2. **Firebase Setup:** Configure your Firebase API key and database URL.
3. **Analog Pins:** 
    - ESP8266 has one analog pin, so the second LDR is simulated.
    - ESP32 has multiple analog pins.

## How to Use

1. Connect the components as per the circuit diagram.
2. Upload the corresponding code to your NodeMCU (ESP8266) or ESP32 using the Arduino IDE.
3. Open the Serial Monitor to see the sensor values and the status of the Firebase updates.

## License

(Choose a license and include the appropriate license file)
