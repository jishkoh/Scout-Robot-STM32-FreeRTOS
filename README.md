Scout Robot Architecture using STM32 and FreeRTOS.

The original scout robot code used bare metal OS in Arduino. However, I wanted to use an STM32 NUCLEO-F446RE board in order to implement a RTOS with task queues and interrupt handling. The OS was developed in STM32CubeIDE.