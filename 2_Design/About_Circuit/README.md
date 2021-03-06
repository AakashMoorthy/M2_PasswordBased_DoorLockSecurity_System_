# Components Used
## Kaypad

It is customizable in size ( rows and columns ) and key labels.
By default it is an standard 12 keys; 4 rows, 3 Cols.

More Info:
 http://simulide.blogspot.com/p/blog-page_22.html

![kaypad](https://user-images.githubusercontent.com/98838252/155747679-a49f537e-ab30-45db-ab38-4c0dcfe93840.png)

## Atmega 328
 ### Package: 28-pin-PDIP

* 1: Reset
* 2: PD0 RXD0   PCINT16
* 3: PD1 TXD0   PCINT17
* 4: PD2 INT0   PCINT18
* 5: PD3 INT1   OC2B    PCINT19
* 6: PD4 T0     XCK0    PCINT20
* 7: Vcc
* 8: Gnd
* 9: PB6 TOSC1  XTAL1   PCINT6
* 10: PB7 TOSC2  XTAL2   PCINT7
* 11: PD5 T1     OC0B    PCINT21
* 12: PD6 AIN0   OC0A    PCINT22
* 13: PD7 AIN1   PCINT23
* 14: PB0 ICP1   CLKO    PCINT0
* 15: PB1 OC1A   PCINT1
* 16: PB2 !SS    OC1B    PCINT2
* 17: PB3 MOSI   OC2A    PCINT3
* 18: PB4 MISO   PCINT4
* 19: PB5 USCK   PCINT5
* 20: AVCC
* 21: AREF
* 22: Gnd
* 23: PC0 ADC0   PCINT8
* 24: PC1 ADC1   PCINT9
* 25: PC2 ADC2   PCINT10
* 26: PC3 ADC3   PCINT11
* 27: PC4 ADC4   SDA     PCINT12
* 28: PC5 ADC5   SCL     PCINT13

### Summary:
* The high-performance Microchip picoPower 8-bit AVR RISC-based microcontroller
* 32 KB ISP flash memory with read-while-write capabilities,
* 1024 B EEPROM,
* 2 KB SRAM,
* 23 general purpose I/O lines,
* 32 general purpose working registers,
* 2 x 8-bit, 1 x 16-bit timer/counters with compare modes,
* 6-channel PWM,
* 1 comparators,
* internal and external interrupts,
* 1 serial programmable USART,
* 1 byte-oriented 2-wire serial interface,
* 1 SPI serial port,
* 6-channel 10-bit A/D converter,
* programmable watchdog timer with internal oscillator,
* 5  software selectable power saving modes.
* The device operates between 1.8-5.5 volts.

![Screenshot 2022-02-25 213212](https://user-images.githubusercontent.com/98838252/155747736-672602ae-33f8-44ca-8567-3e2391b85444.png)

## Stepper motor
Step by step Motor.

- Configurable number of steps per revolution.
- Configurable coil resistance.

For simplicity and speed, Motor Coils are modelled as resistors.

![stepper](https://user-images.githubusercontent.com/98838252/155747798-3f268b58-4874-468d-8fd2-e2a36de71243.png)

## Speaker
Connection to default audio output in you machine.

If no default audio device is found, you will se an "X" in the symbol.

![buzzer](https://user-images.githubusercontent.com/98838252/155747860-17082cf2-f1d4-4e5b-825c-9085e6f42427.png)

## Display
HD44780 LCD:

5x8 dot-matrix liquid crystal display based on Hitachi HD44780 LCD controller.

Configurable in characters rows and columns.

![display](https://user-images.githubusercontent.com/98838252/155747953-a7af087e-57d2-4255-8a05-b2334af4e246.png)

## motor driver
![Screenshot 2022-03-08 130703](https://user-images.githubusercontent.com/98838252/157189409-bfa6bea4-e1fc-4263-9165-6f6db35ccb43.png)

