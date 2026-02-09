# ARITHMETIC LOGIC UNIT (ALU)

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : REDDY HEMANTH KUMAR

*INTERN ID* : CTIS3666

*DOMAIN* : VLSI

*DURATION* : 6 MONTHS

*MENTOR* : NEELA SANTHOSH KUMAR

*DESCRIPTION* :

This repository presents the complete design and implementation of a basic 4-bit Arithmetic Logic Unit (ALU) using the VHDL hardware description language. The project demonstrates how fundamental arithmetic and logical operations can be performed within a digital system through structured hardware modeling and simulation. The main objective of this project is to understand the internal working of an ALU, which is considered the core computational unit of every microprocessor and digital processor architecture.

The designed ALU accepts two 4-bit input operands named A and B, along with a 3-bit control signal called SEL. Based on the value of this select signal, the ALU performs a specific arithmetic or logical operation and generates a 4-bit output called RESULT. An additional CARRY output signal is also included to support arithmetic operations such as addition and subtraction. This modular structure makes the ALU flexible and easy to integrate into larger digital systems.

The ALU implemented in this project supports five essential operations. These include addition, subtraction, logical AND, logical OR, and logical NOT. Each operation is selected using a unique SEL code. For example, the input combination “000” selects addition, “001” selects subtraction, “010” performs the AND operation, “011” performs OR, and “100” performs the NOT operation on input A. Any other select code results in a default output value of zero. This operation table clearly defines the functionality and behavior of the ALU.

The repository contains all necessary files required to understand, execute, and verify the project. The main design file alu.vhd includes the complete VHDL code describing the ALU architecture and logic. A separate testbench file named alu_tb.vhd is provided to validate the design through simulation. The testbench applies different input combinations to the ALU and verifies whether the generated outputs match the expected results. This method of verification ensures that the design functions correctly under all supported operations.

Simulation of the ALU design was carried out using ModelSim Intel FPGA Starter Edition, which is a widely used industry-standard simulation tool for VHDL and Verilog designs. The design files were successfully compiled, and the testbench was executed to generate waveform outputs. The waveform screenshot named ALU_Simulation_Output.png included in this repository shows the behavior of the ALU for different input conditions. This visual result confirms the correct working of the design and serves as proof of successful functional verification.

This project is highly useful for students and beginners learning digital system design, VHDL programming, and hardware simulation concepts. It provides a clear example of how complex digital logic can be modeled using hardware description languages and tested before actual hardware implementation. The structured approach followed in this project reflects real-world digital design methodologies used in industry.

All source files, simulation results, and documentation included in this repository were created as part of an academic learning exercise in digital electronics and embedded system design. The project can be further extended to support additional operations such as XOR, NAND, shift operations, and multi-bit arithmetic units. It can also be synthesized and implemented on FPGA development boards for real-time hardware testing.

Overall, this repository serves as a complete reference for designing, simulating, and understanding a basic ALU using VHDL. It demonstrates the complete workflow starting from hardware description, testbench development, simulation, and result verification, making it a valuable educational resource for anyone interested in digital logic design and computer architecture.

*OUTPUT* :

<img width="1920" height="1022" alt="Image" src="https://github.com/user-attachments/assets/f4a11013-3f70-4eae-a34e-059366127add" />
