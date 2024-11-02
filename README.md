# KOMODO
Corresponded with friends via encrypted messages over short distances.

![IMG_20241028_150928](https://github.com/user-attachments/assets/91028187-f26e-48a4-a6a8-bbc3fd184f5a)


## Components 
for default setup you need:

- ESP32
- Buzzer
- Some buttons
- 18650 li-ion battery
- Charging PCB (like a TP4056)
- Antena
(The standard antenna covers a radius of 250 meters,so I strongly recommend using an external one)
- And of course some wires

The project based on the ESP32 uses the "ESP32-2432S028R" board also known as "CYD".
Link to information about the board 
https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display

## Adding friend

inside "General.cpp" you will see

uint8_t broadcastAddress[] = { 0x00, 0x00, 0x00, 0x00, 0x00, 0x00 };

write MAC ardress of your friend here.

## Configuration

Here you can configure some colors

![image](https://github.com/user-attachments/assets/245bae60-2f44-4f5e-b7c0-9d4de7308b5c)


