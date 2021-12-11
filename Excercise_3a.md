# Exercise 3

## Investigate project board
Look at the documents for the board you are considering for your final project (or any ST Discovery Board), draw the hardware block diagram for the board. For peripherals, note the communication paths (SPI, I2C, etc).
Look at the datasheet for the processor and other documents. Answer these questions:
- What kind of processor is it?
  - STM32L475VGT6
- How much Flash and RAM does it have? Any other memory types?
  - 1 Mbyte of Flash memory, 128 Kbytes of SRAM, and 64-Mbit Quad-SPI (Macronix) Flash memory.
- Does it have any special peripherals? (List 3-5 that you noted as being interesting.)
  Dynamic NFC tag (M24SR), 260-1260 hPa absolute digital output barometer (LPS22HB), Time-of-Flight and gesture-detection sensor (VL53L0X).
- Does it have a floating point unit?
  Yes, 
- If it has an ADC, what are the features?
  2× 12-bit ADC 5 Msps, up to 16-bit with hardware oversampling, 200 μA/Msps
  
Look at one application note for this processor. - AN4312 (Design with surface sensors for touch sensing applications on MCUs)

Compile your answers into a google doc or markdown file, and send a link to the #assignment-submission channel on Discord. Make sure the files are publicly viewable.
Also, be prepared to share what you learned in Live Class.

Hardware Block Diagram (ST was so kind to draw this, and I'm not one for re-inventing the wheel):
![Screenshot 2021-12-11 at 17 37 25](https://user-images.githubusercontent.com/8755037/145682354-1c6e6dc6-c097-426e-a405-74e6bd6edad2.png)
