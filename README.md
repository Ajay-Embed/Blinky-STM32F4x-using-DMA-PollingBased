# Blinky-STM32F4x-using-DMA-PollingBased
Here I am using the DMA controller of the MCU to toggle the LED.



I have initialized tow bytes in the SRAM1 of the MCU, I am sendin them byte by byte to the AHB1 connected GPIOA. 
One byte is high one is LOW, GPIOA-PIN5 has an in built  LED on the Board that blinks.

MCU - STM32F446RET6 Nucleo
