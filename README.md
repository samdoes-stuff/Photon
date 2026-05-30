## PHOTON

<img width="6379" height="9779" alt="PHOTON_page-0001_compressed" src="https://github.com/user-attachments/assets/706f9f75-7e87-4973-bcf9-f61b399a5b78" />





A nrf52840 based devboard made for custom handwired keyboard. This board has a onboard antenna and USB type-C connector. Exposed pads for 14 columns and 5 rows. Also comes with SWD interface to flash the board and battery powered & charging support. 

This board is an end product of my keyboard. My PCB for the (xd keyboard) never arrived. So I made this development board to finish my keyboard build. With the help of the column and rows exposed pad, I will handwire my keyboard. The column pad orientation may be not organized that is because it helps me handroute my keyboard according to my key matrix.


## Schematics

For reference, I used my keyboard schematics to design my schematics. Whole schematics and PCB were made in Easyeda Pro.

<img width="1023" height="686" alt="SCHEMATICS" src="https://github.com/user-attachments/assets/52d1302d-a292-42d6-832a-7856ce9c4840" />



## PCB

I had to reroute the PCB different from my keyboard because component placement were different and more compacted & clean. I also panelized the PCB to make proper use of the space. Also for the first time, I used teardrop feature which made my pcb more beautiful.

<img width="876" height="370" alt="Screenshot 2026-05-24 124442" src="https://github.com/user-attachments/assets/62fa7294-5b7e-4c9f-b1bf-9eaf74b46716" />

<img width="896" height="395" alt="Screenshot 2026-05-24 124436" src="https://github.com/user-attachments/assets/6464ff13-16ab-487d-97af-6ceab0532726" />

<img width="522" height="578" alt="Screenshot 2026-05-24 124421" src="https://github.com/user-attachments/assets/a65333f0-bf03-45bf-b344-aa63de0f82c5" />


## Renders

I am not very good at renders. But still tried fusion 360 to render some image. Though It did not turn out the very best, I promise to learn blender to render more realistic things.

<img width="854" height="480" alt="Front SIde Render" src="https://github.com/user-attachments/assets/94da1a19-7eaf-40c7-8225-9cf72adc4740" />

<img width="1600" height="589" alt="Backside Render" src="https://github.com/user-attachments/assets/6ad9eb9f-c98f-4dff-a192-7ad82e32d8ac" />

## Firmware & Build

From my experience with PCB, I think I cannot build the PCB on my own. So, I will probably take assembly service from local vendors or hopefully in Fallout (China)

And for the Firmware, I already built the firmware for my keyboard. Both nrf52 firmware and ZMK firmware. The nrf52 firmware is a hex file. So, it requires a ST-Link to flash that is why I have open SWD interface to flash it and also included the hex file for the board. So, the work is 80% done. You can follow some ST-Link tutorial according to your understanding.

For the zmk firmware, once you flashed the hex file, you can upload the zmk firmware with USB. To see the whole zmk firmware, please do visit my [ZMK repo](https://github.com/samdoes-stuff/zmk-config) to get a idea about my keymapping and firmware build in depth. But I have already given the uf2 file in the firmware section so that would be very easy if you already workes with xiao rp2040 or the hackpad kit.


## BOM

I already have the components from my keyboard build. Still the prices and the links of the components are given in BOM.csv 
