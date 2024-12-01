# ModXo-Basic

![alt text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/logo.png?raw=true) <img src="https://github.com/Darkone83/ModXo-Basic/blob/main/Images/team-resurgent.png" width="180"> ![alt text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/DC%20logo.png?raw=true)

A carrier board designed for ModXo V1.X

This is designed around Team Resutgents and Shalx's work on ModXo an open-source modchip for the OG XBOX

For more information on the software side of things and the ModXo project please visit: https://github.com/Team-Resurgent/Modxo

The BOM and IBOMS are included for ease of assembly

### Parts

RP2040 Tiny: <a href="https://www.aliexpress.us/item/3256805837992528.html?spm=a2g0o.productlist.main.21.2f7926c5zGZBOW&algo_pvid=a59806cb-1f8b-4000-8595-0b05ca9fd6e6&algo_exp_id=a59806cb-1f8b-4000-8595-0b05ca9fd6e6-10&pdp_npi=4%40dis%21USD%217.22%214.48%21%21%217.22%214.48%21%402101c80217323295821625728e786b%2112000035369681956%21sea%21US%21196794698%21X&curPageLogUid=5ESoEvR4Kxce&utparam-url=scene%3Asearch%7Cquery_from%3A">AliExpress</a> <a href="https://www.amazon.com/gp/product/B0CHDW1MY5/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1">Amazon</a>

JST 1.0 6P headers: <a href="https://www.aliexpress.us/item/3256807921170605.html?spm=a2g0o.order_list.order_list_main.5.2ab61802WqdO85&gatewayAdapt=glo2usa">AliExpress

Resistor network: <a href="https://www.aliexpress.us/item/3256805393765008.html?spm=a2g0o.order_list.order_list_main.15.2ab61802WqdO85&gatewayAdapt=glo2usa">AliExpress</a>

680ohm 0805 SMD Resistor: <a href="https://www.aliexpress.us/item/3256805001000955.html?spm=a2g0o.productlist.main.1.21e92a8bJSREJB&algo_pvid=166c6b88-0bcd-419e-a2aa-9cdee6e1159c&algo_exp_id=166c6b88-0bcd-419e-a2aa-9cdee6e1159c-0&pdp_npi=4%40dis%21USD%211.61%211.61%21%21%2111.58%2111.58%21%402103010b17330203904498265e203c%2112000032028480646%21sea%21US%21196794698%21X&curPageLogUid=gv6us4jd9bBm&utparam-url=scene%3Asearch%7Cquery_from%3A">AliExpress</a> Select 680ohm

0805 SMD LED: <a href="https://www.aliexpress.us/item/3256805040539430.html?spm=a2g0o.order_list.order_list_main.115.2ab61802WqdO85&gatewayAdapt=glo2usa">AliExpress</a> (Select any color 0805 size)

SOD-323 Diode 1N4148: <a href="https://www.aliexpress.us/item/3256802700704767.html?spm=a2g0o.order_list.order_list_main.103.2e201802yQpjZo&gatewayAdapt=glo2usa">AliExpress</a> (Select 1N4148 SOD-323)

Pin headers: <A href="https://www.aliexpress.us/item/2251832418097093.html?spm=a2g0o.productlist.main.3.7b0d3df3QSv0wF&algo_pvid=3a181168-b342-4628-83c9-fb164c7798a5&algo_exp_id=3a181168-b342-4628-83c9-fb164c7798a5-1&pdp_npi=4%40dis%21USD%214.99%214.24%21%21%214.99%214.24%21%402103205217330210383736191ef8d4%2159185858513%21sea%21US%21196794698%21X&curPageLogUid=qyKTKZWKL4zD&utparam-url=scene%3Asearch%7Cquery_from%3A">AliExpress <a href="https://www.amazon.com/gp/product/B08R8QXWBR/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1">Amazon</a>
#### Builders note

LED1 and R1 are optional and not required for the PCB to work as expected. If your XBOX is a revision 1.6 you will need to rebuild the LPC manually or use a LPC rebuild PCB.

## Where to get one

You can download the gerbers and make your own or soon would will be able to purchase PCB's and assembled units @ <a href="https://www.darkonecustoms.com">Darkone Customs</a>

Assembled Boards: Comming Soon!

PCB's: Comming soon!

## Navigation

Root: BOM and IBOM are located here

Images: All images, branding, PCB renders, and schematics are located in this folder

PCB: Gerbers and pick and place files are located in this folder

## Port pinouts

DISP:

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/DISP.png?raw=true)

EXP:

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/EXP.png?raw=true)

RGB:

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/RGB_EXP.png?raw=true)

To enable the RBG EXP port you will need to manually install a jumper on the lower left pin of the RGB LED to the RBP pad on the carrier board. At this time RGP expansion is not currently enabled. See the example below for connecting the RGB pad

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/RGB_EN.png?raw=true)

LPC:

![alt_text](https://github.com/Darkone83/ModXo-Basic/blob/main/Images/LPC.png?raw=true)
