Scout Robot Architecture using STM32 and FreeRTOS.

The original scout robot code used bare metal OS in Arduino. However, I wanted to learn FreeRTOS and decided to port all the functionalities using task queues and interrupt handing with the STM32-F446RE. The functionalities:

1. PWM for motor speed control. Left and Right for steering.
2. UART port for steering control and speed reporting.
3. Quadrature control for robot speed and odometry.
4. Heartbeat signal using LED to signal firmware health.
5. SPI interface with nRF24L01 radio control module to communicate with controller. 

The firmware was designed in STM32CubeIDE.

![scout_robot1](https://github.com/user-attachments/assets/533a21c0-eaf6-4648-9e02-2c17284dc78f)

![scout_robot2](https://github.com/user-attachments/assets/de97b1ce-8327-4a87-802d-2496b77735bc)

![scout_robot3](https://github.com/user-attachments/assets/31a6d153-473f-4bed-8bea-b504828ea80f)

![scout_robot4](https://github.com/user-attachments/assets/003fd357-b451-4b32-9ce2-2e4ccbb91975)

![scout_robot5](https://github.com/user-attachments/assets/446c6835-3b48-4952-9091-9f6b1e5e4b81)
