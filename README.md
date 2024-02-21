 A-4-week-Research-Internship-on-RISC-V-using-VSDSquadron-Mini-RISC-V-Dev-Board

![IMG_6005 copy](https://github.com/Sandeepkumar-bs/vsdquardron/assets/140676646/ed98d917-2c63-4c2e-9214-086e4a369bd2)



BOARD SPECS:

1.CH32V003F4U6 chip with 32-bit RISC-V core based on RV32EC instruction set

2.SRAM 2kb onchip volatile sram 16kb external program memory

3.Processor 24 MHz

4.Sink Current per I/O Pin 8 mA

5.Source Current per I/O Pin 8 mA

6.Input voltage (nominal) 5 V

7.I/O voltage 3.3 V

8.Programmer/debugger Onboard RISC-V programmer/debugger, USB to TTL serial port support

9.SPI 1x, PC5(SCK), PC1(NSS), PC6(MOSI), PC7(MISO)

 I2C 1x, PC1(SDA), PC2(SCL)

 USART 1x, PD6(RX), PD5(TX)

10.External interrupts 8 external interrupt edge detectors, but it only maps one external interrupt to 18 I/O ports
   PWM pins 14X

11.Analog I/O pins 10-bit ADC, PD0-PD7, PA1, PA2, PC4

12.Digital I/O pins 15

13.Built-in LED Pin 1X onboard user led (PD6)

14.USB 2.0 Type-C

This repo is intended to document the weekly progress.

###The first online meet was held on 16th of Feb 2024 @6PM

TASK-1

1.install Yosys

2.install iverilog

3.install gtkwave


# TO INSTALL GIT

```sudo apt get install git```

![install git](https://github.com/Sandeepkumar-bs/vsdquardron/assets/140676646/33a3512b-322e-495e-bdc5-4dc4e3d70ff5)

1.yosys
```cd yosys```

![yosys](https://github.com/Sandeepkumar-bs/vsdquardron/assets/140676646/5d0a3d7c-439c-48d4-8a87-ece161de6906)

```sudo apt install yosys```

![yosys1](https://github.com/Sandeepkumar-bs/vsdquardron/assets/140676646/266189e6-42b5-49d9-aa36-580369f1db5f)

2.iVerilog
```sudo apt-get install iverilog```

![iverilog](https://github.com/Sandeepkumar-bs/vsdquardron/assets/140676646/f58d8486-13fe-46e6-aa38-c42513c8dc38)

3.GTkWave
```sudo apt-get install gtkwave```

![gtkwave](https://github.com/Sandeepkumar-bs/vsdquardron/assets/140676646/793989a6-457c-426b-a443-ebb40b9b77b0)



------------------------------------------------------------------------------------------------------------------------------------


### 2nd Meeting - The second online meet was held on 20th of Feb 2024 @6PM


Task-2 

1.To create a block diagram of the respective project  

2.To identify input ports, input waveforms, output ports and output waveforms  

**Block Diagram**  







