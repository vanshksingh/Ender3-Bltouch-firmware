# Ender3-Bltouch-firmware
This repository contains the firmware for Ender3 with BL Touch Modification , Tested on Board is V4.2.2 STM32F303 or GD "NOT 103"


Your wiring isint bad , or it is interference , and nor your BL-Touch is bad..... Creality's firmware is.

Make sure your wiring makes sense...


Probe Connection Point on ender3 V4.2.2 board , using the BL-touch connecter is PB1 --- '#define Z_MIN_PROBE_PIN PB1'




Put the .bin file with an name of your choice (For reflash just change name of .bin)

The version provided here uses Bilinear method for bed leveling , although UBL was also an option.



The .bin file is created with 

<img width="801" alt="Screenshot 2024-06-02 at 12 30 58 AM" src="https://github.com/vanshksingh/Ender3-Bltouch-firmware/assets/114809624/da42c895-fed0-4398-b04b-866a039eb995">

Although this has also been tested to work although it felt slower on the machine (Placebo? maybe)

<img width="708" alt="Screenshot 2024-06-02 at 12 31 29 AM" src="https://github.com/vanshksingh/Ender3-Bltouch-firmware/assets/114809624/01eb1b09-709e-4f9e-9de1-b53bb763115a">

Initially tested with below , but switched to other as it was being depreciated

<img width="708" alt="Screenshot 2024-06-02 at 12 32 49 AM" src="https://github.com/vanshksingh/Ender3-Bltouch-firmware/assets/114809624/a58c401f-3678-467e-b214-71c52b7351c1">


