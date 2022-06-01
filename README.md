![espoir_iso1_1080](https://user-images.githubusercontent.com/52324318/171322710-7c2c5553-c87c-41e2-900a-6afc86acddeb.jpg)

# Espoir
Espoir is a Power over Ethernet+ (PoE+ (802.3af/at)), mikroBUS<sup>TM</sup> mainboard based on the ESP32-MINI-1.

## Specifications
- MCU
  - Single **OR** dual core 240 MHz ESP32-MINI-1 (devices produced since January 2022 [are now dual core](https://www.espressif.com/sites/default/files/pcn_downloads/PCN-2021-021%20ESP32-U4WDH%20%E5%8D%87%E7%BA%A7%E4%B8%BA%E5%8F%8C%E6%A0%B8%E5%A4%84%E7%90%86%E5%99%A8%E4%BA%A7%E5%93%81_1.pdf))
  - 4 MB Flash @ 80 MHz
  - 520 KB SRAM
  - Full details in the [ESP32-MINI-1 Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-mini-1_datasheet_en.pdf)
- Power
  - Input: 37 V - 57 V PoE+ through the Ethernet connector. 2,250 V isolation
  - Input: 5 V through the USB-C connector<sup>1</sup>
  - Output: 5 V at 3 A (15 W) from PoE
  - Output: 3.3 V at 0.7 A (2.3 W)<sup>2</sup>
- Connectivity
  - 100Base-T Ethernet (80+ mbps UDP throughput)
  - Wi-Fi 2.4 GHz 802.11b/g/n with integrated antenna
  - Bluetooth 4.2 BLE
  - USB 2.0 USB-C connector
  - A full mikroBUS<sup>TM</sup> header with two grounds, 5 V, 3.3 V and 12 IOs
  - An extension header with two grounds, four additional input only pins, and the ESP32 reset signal
  - Additional details and capabilities in the [ESP32-MINI-1 Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-mini-1_datasheet_en.pdf)
- Form factor
  - Weight: 31 g
  - Size: 50.8 x 61 mm<sup>2</sup> (2.0 x 2.4 in<sup>2</sup>)
  - Mounting holes: 4x M2.5 / 4-40. The bottom-left one is plated and connected to local ground.
  - 1 mikroBUS<sup>TM</sup> header and 1x8 optional extension header. An L format (57.15 mm / 2.25 in) mikroBUS<sup>TM</sup> add-on board arrives flush with the bottom of the PCB.

<sup>1</sup> The USB VBUS (5V) power supply is connected to the 5 V rail through a protection diode. If only the USB cable is connected, the voltage on the 5 V rail will be 4.6 V.

<sup>2</sup> The 3.3 V supply is derived from the 5 V rail. Current used by the 3.3 V supply also counts towards the 5 V rail's maximum current.
