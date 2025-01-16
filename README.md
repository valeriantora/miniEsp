# Overview
The **miniEsp** is my solution to the limitations of the ESP-01 module. One of the biggest issues I faced with the ESP-01 was its lack of I/O pins, having only 2 I/O pins made it too restrictive for many of my projects. To fix this, I designed the miniEsp, a larger version based on the ESP-12F. It offers 8 I/O pins, giving me the flexibility I need for more richer applications.

I also included an ME6211 voltage regulator chip to ensure the ESP-12F stays safe when powered by 5V sources. Despite being slightly bigger than the ESP-01, the miniEsp keeps the same pin header format, so it’s just as easy to use and integrate.

## References
- [ESP-12F Datasheet](https://docs.ai-thinker.com/_media/esp8266/docs/esp-12f_product_specification_en.pdf)
- [ME6211 Datasheet](https://www.lcsc.com/datasheet/lcsc_datasheet_2410121248_MICRONE-Nanjing-Micro-One-Elec-ME6211C30M5G_C94042.pdf)
