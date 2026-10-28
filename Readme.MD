# ESP32P4/C6 10.1 inch IPS JC8012P4A1C_I_W_Y

 

# ---

![Screenshot](/PICTURES/0.jpg)
![Screenshot](/PICTURES/01.jpg)
![Screenshot](/PICTURES/02.jpg)
![Screenshot](/PICTURES/03.jpg)
![Screenshot](/PICTURES/04.jpg)
![Screenshot](/PICTURES/05.jpg)
![Screenshot](/PICTURES/06.jpg)
![Screenshot](/PICTURES/07.jpg)
![Screenshot](/PICTURES/08.jpg)
![Screenshot](/PICTURES/09.jpg)
![Screenshot](/PICTURES/0.jpg)

![Screenshot](/PICTURES/0001.jpg)

| No. | Description                 | No. | Description                 | No. | Description                 |             
| :-: | :-------------------------- | :-: | :-------------------------- | :-: | :-------------------------- |
|  1  | USB Full Speed  (USB1 P4)   |  9  | Microphone                  |  17 | CN5 (ESP-Prog for ESP32-C6) |
|  2  | USB High Speed  (USB P4)    |  10 | EXTEND1 connector           |  18 | CN4 (I2C P4)                |
|  3  | USB from UART0 P4           |  11 | Reset button P4             |  19 | W25Q128 SPI Flash chip      |
|  4  | CN2 (UART0  P4)             |  12 | TF Card Holder              |  20 | ESP32-P4                    |
|  5  | LCD-FPC (MIPI-DSI P4)       |  13 | EXTEND2 connector           |  21 | RTC chip (RX8025T)          |
|  6  | Touch CTP-FPC               |  14 | Camera FPC (MIPI-CSI P4)    |  22 | RTC battery                 |
|  7  | ESP32-C6                    |  15 | Battery connector (3,7V)    |  23 | BOOT button P4              |
|  8  | Speaker connector           |  16 | Power button                |  24 | UART-USB chip (CH340)       |

 
-------------------

| No. | Key Component                       | Description                                                   |
| :-: |  :--------------------------------- |  :----------------------------------------------------------- |
| 1 | USB Full Speed  (USB1 P4) | USB Type-C port that supports USB 2.0 Full-speed data rate. It can be used as the power supply interface for the development board and as a communication interface. |
| 2 | USB High Speed  (USB P4) | The USB 2.0 Type-C Port is connected to the USB 2.0 OTG High-Speed interface of ESP32-P4, compliant with the USB 2.0 specification. When communicating with other devices via this port, ESP32-P4 acts as a USB device connecting to a USB host. Please note that USB 2.0 Type-C Port and USB 2.0 Type-A Port cannot be used simultaneously. USB 2.0 Type-C Port can also be used for powering the board. |
| 3 | USB from UART0 P4 | USB Serial/JTAG Port. USB Type-C port that supports USB 2.0 Full-speed data rate. It can be used to flash firmware to the ESP32-P4 chip, communicate with the chip via the USB protocol, and perform JTAG debugging. |
| 4 | CN2 (UART0  P4) | It can be used to flash firmware to the ESP32-P4 chip, communicate with the chip via the UART protocol, and perform JTAG debugging. |
| 7 | ESP32-C6 | This module serves as the Wi-Fi and Bluetooth communication module for the board. |
| 8 | Speaker connector | This port is used to connect a speaker. The maximum output power can drive a 4 Ω, 3 W speaker. |
| 9 | Microphone | Onboard microphone connected to the interface of Audio Codec Chip. |
| 12 | TF Card Holder | MicroSD Card Slot supports a MicroSD card in 4-bit mode and can store or play audio files from the MicroSD card.|
| 15 | Battery connector (3,7V) | Li-Ion battery port. |
| 16 | Power button| Li-Ion battery port. | Short press: enables / wakes the device. Long press: disables the device.
| 17 | CN5 (ESP-Prog for ESP32-C6) | The connector can be used with ESP-Prog or other UART tools to flash firmware onto the ESP32-C6 module. |
| 19 | W25Q128 SPI Flash chip | The 16 MB flash is connected to the ESP32-P4 chip via the SPI interface. (PSRAM) |
| 21 | RTC chip (RX8025T) | Real Time Clock chip |
| 22 | RTC battery  | CR1220 |
| 24 | UART-USB chip (CH340)  | Connected to UART0 ESP32-P4 |
|  | ES8311 chip | Audio Codec Chip. ES8311 is a low-power mono audio codec chip. It includes a single-channel ADC, a single-channel DAC, a low-noise pre-amplifier, a headphone driver, digital sound effects, analog mixing, and gain functions. It interfaces with the ESP32-P4 chip over I2S and I2C buses to provide hardware audio processing independent of the audio application. |
|  | NS4150B chip | Audio power amplifier Chip. 3 W mono Class D audio power amplifier that amplifies audio signals from the audio codec chip to drive speakers.|

-------------------


