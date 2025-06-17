# STM32 LWIP TCP Client

This project demonstrates how to set up a simple TCP client on the STM32 Nucleo-F746ZG board using the LWIP stack for network communication. The client connects to a server and sends JSON-formatted data over TCP. The application uses FreeRTOS for multitasking.

## Project Overview

The primary function of this project is to send JSON data to a server over a TCP connection. The data includes a "Node ID" and a "Door Status", and the client attempts to connect to a remote server at `192.168.1.127` on port `8000`. It uses the STM32F7 microcontroller along with the LWIP networking stack and FreeRTOS for task scheduling.

### Features
- LWIP-based TCP client communication.
- Sends JSON data over TCP.
- Simple logging via `snprintf` for debug output.
- FreeRTOS task management.
- Network status monitoring to check if the network is up before connecting.

### Hardware Requirements
- **STM32 Nucleo-F746ZG** or any compatible STM32 board.
- **Ethernet** connected to the network.
- **UART (Serial)** connection for debug output.


https://github.com/user-attachments/assets/2214b6bf-6076-42c2-b275-5237941b47cd

