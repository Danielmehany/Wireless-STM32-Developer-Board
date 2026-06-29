# STM32 Wireless Dev Board
 
An STM32F411 dev board with a built-in Wi-Fi 6 + BLE radio module.
 
---
 
## Why
 
STM32s are great at talking to sensors. They ofer plenty of ADCs, timers, and tight
real-time control. However, they have no wireless on their own. ESP32s are the
opposite, wireless built in, but a lighter peripheral set. This board keeps the
STM32 as the host and bolts a proper radio module onto it, so you don't have to
choose between the two.
 
---
 
## RF
 
- **SiWG917Y111MGA** radio module with a **built-in antenna** - pre-certified, so
  no antenna design needed.
- **Antenna keepout:** module sits on the board edge with no copper under the
  antenna on any layer.
- **Wi-Fi 6**, 2.4 GHz.
- **Bluetooth LE 5.4**, up to 2 Mbps.
- Talks to the STM32 over SPI.
## SPI + I2C
 
- **High-speed SPI** to the radio - the STM32 drives it up to **50 MHz**.
- **I2C** broken out for sensors.
## USB-C
 
- **USB-C** for both power and data.
- **D+ / D- routed as a differential pair** 
- **ESD protection diode** on the USB lines
  
## Other features
 
- **Reset** and **boot** buttons.
- **Power LED.**
- **GPIO breakout headers.**

## Schematic
<img width="275" height="200" alt="image" src="https://github.com/user-attachments/assets/24cffeae-2997-483c-ae71-aaf39131649e" />
<img width="289" height="200" alt="image" src="https://github.com/user-attachments/assets/78d135f0-5c97-4278-83dc-6d223ccedbcc" />
<img width="350" height="200" alt="image" src="https://github.com/user-attachments/assets/97d67c1b-bb12-4800-9ed3-23338f302558" />
<img width="195" height="200" alt="image" src="https://github.com/user-attachments/assets/7e49015e-d632-4e5d-adaf-109666b782d3" />



## Board

<img width="379" height="227" alt="image" src="https://github.com/user-attachments/assets/74787665-5bda-4d63-8351-b401bccf47b6" />

