# HC-SR04 module example
## Description
Simple demonstration of ultrasonic module usage with STM32F429I-DISC1 board.
- Peripherals
  - GPIO
    - PA6: Echo pin
    - PA11: Trigger pin
  - USART1: VCOM (PA9, PA10)

## Build&Run
1. Clone the example and install missing CMSIS packs
    - CMSIS version 6.0.0
    - CMSIS-Compiler version 2.0.0
    - STM32F4xx_DFP version 2.17.0
2. Build example
3. Connect HR-S04 module to STM32F429I-DISC1 board to corresponding pins
4. Connect STM32F429I-DISC1 board to your PC and flash
5. Test with obstacle moving closer and further away and watch output on terminal (Tera Term, Termite...)

## User manual
https://cdn.sparkfun.com/datasheets/Sensors/Proximity/HCSR04.pdf
