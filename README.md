# UART_Transmitter
A synthesizable FSM-based UART TX/RX implemented in Verilog and verified using a self-checking testbench and GTKWave.
This project implements a UART (Universal Asynchronous Receiver Transmitter) using Verilog RTL. Both the transmitter and receiver are designed using finite state machines (FSMs) and verified through a self-checking testbench with waveform analysis using GTKWave.
UART is an asynchronous serial communication protocol that transmits data one bit at a time without a shared clock between the transmitter and receiver. Communication is synchronized using a predefined baud rate and framing structure consisting of:

Start bit (logic 0)

Data bits (LSB first)

Stop bit (logic 1)
