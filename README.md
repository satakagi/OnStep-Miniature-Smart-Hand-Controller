# OnStep-Miniature-Smart-Hand-Controller

## About
This is a much smaller design of the [Smart Hand Controller](https://onstep.groups.io/g/main/wiki/7152) for [OnStep](https://onstep.groups.io/g/main)*1.
It is based on the [OnStep ESP32 Smart Hand Controller](https://baheyeldin.com/astronomy/onstep-esp32-smart-hand-controller-shc.html) circuit.

*1: OnStep is an open source GoTo motor drive for telescope mounts

![mini SHC working image](imgs/img1.jpg)

## Parts List

* [DOIT ESP32 DEVKIT V1](https://www.amazon.com/s?k=DOIT+ESP32+DEVKIT+V1)
  * Note: Unlike the original ESP32 SHC, this design uses the DOIT ESP32 DEVKIT V1 with 30 pins.
* PCB ( refer to [kicad](kicad/) directory )
* [0.96" SSD1306 OLED Module](https://www.amazon.com/s?k=0.96+ssd1306+oled)
  * Note: Stick tape on the back side for insulation.
* Modular Jack 6P6C x 2
* 7 Resistor Network (2K ohm)
* 4 Resistor Network (2K ohm)
* 2.54mm Header Pins 15pin F x 2, 4pin M, 2pin M 
* Momentary Tact Button Switches 0.2" x 0.24" x 7
  * Buttons would need to be at least 0.24" long.
* Case ( refer to [miniSHCcase.stl](miniSHCcase.stl) )

## Photos of the interior structure
![Three modules make up the controller](imgs/img2.jpg)
Tape is attached to the back of the OLED module for insulation.
|  - |  -  |
| ---- | ---- |
|  ![PCB](imgs/img3.jpg)  |  ![Connection with OLED](imgs/img4.jpg)  |
|  ![Side view](imgs/img5.jpg)<br>To avoid interference with the OLED, the leads protruding from the through-holes are trimmed.  |  ![Backside view and installation in a case](imgs/img6.jpg)<br>Attach a pad to the lid to hold the board in place and close the lid. (In this picture, the lid is fastened with tape.)   |

## License
This is licensed under the [TAPR Open Hardware License](https://tapr.org/the-tapr-open-hardware-license/), one of the well-known open-source hardware licenses.
