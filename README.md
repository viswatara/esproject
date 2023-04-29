# Problem Statement

The project will utilize an ARM Cortex-M3 based LPC1768 microcontroller. 
The program will be written in the C programming language using the Keil µVision IDE. 
The CMSIS-CORE component of the Cortex Microcontroller System Interface Standard (CMSIS) will be used to define the registers and data structures for the microcontroller's startup, core CPU access and peripheral definitions.
The microcontroller will be programmed to count down from the input value which will be taken using the 4x4 key matrix and then activate a buzzer. The system will be designed to have a reset button, which will reset the counter to zero and will prompt the program to ask for input again. The program will utilize the microcontroller's General Purpose 
Input Output (GPIO) pins to control the LCD display. We will be connecting an external component i.e. the buzzer that will be 
connected using the pin structure of the ports. C Structure definitions in the LPC17xx.h header file will be used to access the 
registers of the LPC1768 microcontroller. 


Link to presentation: https://rb.gy/9z8qc
Link to documentation: https://shorturl.at/bvxHR
