# DIY: How to control your home in smart way

## My devices:
- <a href="https://shopee.vn/B%E1%BA%A3ng-m%E1%BA%A1ch-m%C3%B4-%C4%91un-ph%C3%A1t-tri%E1%BB%83n-kh%C3%B4ng-d%C3%A2y-chuy%E1%BB%83n-%C4%91%E1%BB%95i-USB-sang-ESP8266-WIFI-ch%E1%BA%A5t-l%C6%B0%E1%BB%A3ng-cao-i.83038628.4842277367?sp_atk=03dca1ae-4602-4c34-9e3f-5d319272aa16">USB to Serial converter</a> 
- <a href="https://shopee.vn/M%C3%B4-%C4%91un-r%C6%A1le-WiFi-ESP8266-5V-d%C3%B9ng-cho-c%C3%B4ng-t%E1%BA%AFc-%C4%91i%E1%BB%81u-khi%E1%BB%83n-t%E1%BB%AB-xa-trong-nh%C3%A0-th%C3%B4ng-minh-APP-ESP-01-i.83038628.1732622770">ESP8266 Relay combo</a> 
- <a href="https://shopee.vn/Loa-Bluetooth-Th%C3%B4ng-Minh-Echo-Dot-Gen-3-(Th%E1%BA%BF-H%E1%BB%87-3)-Loa-Alexa-Echo-Dot-3-cho-Nh%C3%A0-Th%C3%B4ng-Minh-i.198752368.4814846568?sp_atk=64c0609d-2bb8-4e44-8ce5-bc0d65559684">Alexa Echo Dot </a> 
## Software:
- Firmware: <a href="http://ota.tasmota.com/tasmota/release/tasmota.bin">tasmota.bin</a>
- Flasher: pick for your OS from this <a href="https://github.com/Jason2866/ESP_Flasher/releases">list</a>
- USB to Serial driver: pick for your OS from this <a href="https://sparks.gogo.co.nz/ch340.html">list</a>

## References:
- https://tasmota.github.io/docs/

## Step by step:
- Install the USB driver
- Connect the USB with attached ESP module
- Flash the firmware tasmota.bin with Flasher
- Power on the ESP module and connect to the AP named Tasmota-XXXXXX (XXXXXX is last 6 letters of MAC address of the ESP module)
- Access address 192.168.4.1 and follow the instructions