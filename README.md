# Azure-IoT-Central-with-ESP

## Prerequisite 
#### Install DHT Library for ESP board

Go to `Sketch` > `Include Library` > `Manage Libraries...` > `**DHT sensor library for ESPx** by **beegee_tokyo**` > `Install`

## Hardware Connection
#### NodeMCU v3 (Lolin)

The DHT11 sensor is connected as follows:
| DHT11 | NodeMCU |
|---|---|
| VCC | 3.3V |
| DAT | D1 |
| GND | GND |

## Instruction
1. Download these respiratory as ZIP file and extract.
2. Open `esp_8266.ino` file.
3. Change the following codes.
   1. `WIFI_SSID` to your WiFi SSID
   2. `WIFI_PASSWORD` to your WiFi Password
   3. `SCOPE_ID` to your Scope ID generated in Azure IoT Central
   4. `DEVICE_ID` to your Device ID generated in Azure IoT Central
   5. `DEVICE_KEY` to Primary/Secondary Key generated in Azure IoT Central
4. Upload and run.

*PS: It takes 12 seconds to update once in IoT Central.
