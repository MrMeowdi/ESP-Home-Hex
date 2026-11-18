# ESP-Home-Hex
 
ESP Home Hex is a 6-channel WiFi smart switch system with real-time clock automation, allowing precise control of home appliances anytime, anywhere.
 
 
## Working
 
1 - *Put the ESP32 in boot mode and connect it to your PCB*
 
2 - *Use arduino IDE to upload the CODE to the Board and* **make sure that you have entered correct SSID and it's password in the code** . *The following libraries should downloaded and transferred in the microcontroller :*
 
`<WiFi.h>`
 
`<WebServer.h>`
 
`<EEPROM.h>`
 
`<Wire.h>`
 
`"RTClib.h"`
 
`"time.h"`
 
**Now ESP Home Hex will be ready to function .**
 
3 - *Connect the  main AC phase wire to AC slot and the 6 Appliances or switches wire ( That are needed to be operated with this PCB ) to the OUT 1-6 slots .*
 
4 - *Now the PCB is completely set up and would function great if everything goes as expected* :) 
 
5 - *Find your ESP-32 ip address by Arduino IDE serial monitor* .
 
6 - *Open browser on any device that is connected to same Wi-Fi and put the ip address that you found out from serial monitor from IDE* .
 
All set , you are now connected to ESP Home Hex and can operate it and perform all the present functions.
 
### Features
 
> Set on and off time for each relay respectively.
 
> Configure onboard time.
 
> Toggle each relay manually.

### BOM


# SwitchX-Pro PCB BOM

Prices are in USD. “Quote qty” and “Quote total” are from the supplied screenshots; unit price is calculated from them.

| Designator | Footprint | Qty | Value | LCSC Part # |
|---|---|---:|---|---|
| AC, OUT2, OUT3, OUT4, OUT5, OUT6, OUT_1 | CONN-TH_2P-P5.00_WJ500V-5.08-2P | 7 | WJ500V-5.08-2P-14-00A | `C8465` |
| BAT1 | BAT-SMD_BS-CR2032-8 | 1 | BS-CR2032-8 | `C7498149` |
| C1, C2 | C0805 | 2 | 10uF | `C15850` |
| C10, C9 | C0805 | 2 | 100nF | `C49678` |
| D1, D2, D3, D4, D5, D6 | DO-41_BD2.4-L4.7-P8.70-D0.9-RD | 6 | 1N4007 | `C106903` |
| D7 | SMA_L4.3-W2.6-LS5.2-RD | 1 | SS34 | `C8678` |
| FH1 | 64600001003 | 1 | 64600001003 | `C206887` |
| HOLE_GGE9527 | Hole_gge9527 | 1 | Hole_gge9527 | N/A |
| HOLE_GGE9566 | Hole_gge9566 | 1 | Hole_gge9566 | N/A |
| HOLE_GGE9581 | Hole_gge9581 | 1 | Hole_gge9581 | N/A |
| HOLE_GGE9596 | Hole_gge9596 | 1 | Hole_gge9596 | N/A |
| LED1, LED2, LED3, LED4, LED5, LED6 | LED0805-R-RD_RED | 6 | YLED0805R | `C19171391` |
| Q1, Q2, Q3, Q4, Q5, Q6 | TO-92-3_L5.1-W4.1-P1.27-L | 6 | S8050D331 | `C22751469` |
| R1, R2, R3, R4, R5, R6 | RES-TH_BD5.0-L15.5-P19.50-D0.7 | 6 | 1kΩ | `C119712` |
| R13, R14 | R0805 | 2 | 4.7kΩ | `C163996` |
| R15, R7 | RES-TH_BD4.5-L11.5-P15.50-D0.7 | 2 | 10kΩ | `C714145` |
| R16, R17 | R0402 | 2 | 5.1kΩ | `C384321` |
| RLY1, RLY2, RLY3, RLY4, RLY5, RLY6 | RELAY-TH_SRD-XXVDC-XL-C | 6 | SRD-05VDC-SL-C | `C35449` |
| SW1 | KEY-SMD_4P-L6.0-W6.0-P3.90-LS9.0 | 1 | Boot | `C2834918` |
| SW2 | KEY-SMD_4P-L6.0-W6.0-P3.90-LS9.0 | 1 | Reset | `C2834918` |
| U1 | WIFI-SMD_ESP32-WROOM-32E | 1 | ESP32-WROOM-32E-N16 | `C701343` |
| U2 | SOIC-16_L10.3-W7.5-P1.27-LS10.3-BL | 1 | DS3231SN# | `C9866` |
| U3, U4, U5, U6, U7, U8 | RES-TH_BD2.3-L3.7-P7.70-D0.9 | 6 | 220Ω | `C2848572` |
| U9 | SOT-223-3_L6.5-W3.4-P2.30-LS7.0-BR | 1 | AMS1117-3.3 | `C6186` |
| U10 | PWRM-TH_HLK-PM01 | 1 | HLK-PM01 | `C209903` |
| U13 | TYPE-C-SMD_TYPEC16PL7.35MM | 1 | TYPEC-700-ARP16X7 | `C7421430` |
| U14 | SOP-16_L10.0-W3.9-P1.27-LS6.0-BL | 1 | CH340C | `C84681` |


 
## Images
 
<img width="973" height="793" alt="image" src="https://github.com/user-attachments/assets/0216d9d6-ddfe-4d95-8628-2b5c3b74770c" />


 
<img width="1400" height="573" alt="image" src="https://github.com/user-attachments/assets/3a5d607d-6615-4275-bbc9-3bce427e3812" />

 
<img width="796" height="641" alt="image" src="https://github.com/user-attachments/assets/f79108bc-4561-4d2d-bb93-ef7b6eaaccb3" />

 
<img width="1121" height="858" alt="image" src="https://github.com/user-attachments/assets/751cf9a6-b6b1-486a-9638-e0f63e2bf778" />

 
<img width="997" height="619" alt="image" src="https://github.com/user-attachments/assets/064ec578-3dc3-430a-9ca4-3449eb6a7d41" />

 

<img width="1689" height="825" alt="image" src="https://github.com/user-attachments/assets/a19729d7-a19d-4bfa-80aa-3ca19f0e0937" />
<img width="1689" height="825" alt="image" src="https://github.com/user-attachments/assets/2e29ca54-2dbc-4c3b-a2c1-5aadd3fb92b9" />

<img width="1683" height="823" alt="image" src="https://github.com/user-attachments/assets/d85074e9-1ec9-4fae-9a04-11ae2f6e28f4" />
<img width="1683" height="823" alt="image" src="https://github.com/user-attachments/assets/8ffe0686-5251-4e08-8ff8-81c13c936514" />

 
## JLCPCB
 
<img width="1455" height="756" alt="image" src="https://github.com/user-attachments/assets/1b15aab9-ec76-4a2b-bcad-a6a20e00a669" />

<img width="1455" height="756" alt="image" src="https://github.com/user-attachments/assets/ba361bea-b5f6-46d9-a5b6-fec7c7c5942c" />


 
## ` PCB TOTAL = 150 USD `
 
