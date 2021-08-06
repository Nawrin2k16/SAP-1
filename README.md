# Implementation of SAP-1 Computer
The SAP(Simple-As-Possible)-1 computer is a very basic model of a microprocessor. The SAP-1 design includes all of the necessary components for a functional microprocessor. Its primary goal is to provide a fundamental understanding of how a microprocessor operates, interacts with memory, and interacts with other components of the system such as input and output. The instruction set is very limited and straightforward. SAP-1 is the first stage in the evolution of modern computers.

The SAP-1 computer is a bus-organized computer that engages Von-Neumann architecture. It has ten main elements and makes use of an 8-bit central bus. The architecture of the SAP-1 computer is shown below.
![sap-1-architecture](https://user-images.githubusercontent.com/52257670/128532866-0503b1de-da15-4d2a-8fdd-d8e530e81ab8.png)


In this academic project, I along with my team-mate implement an SAP-1 computer in logisim (a tool for designing and simulating logic circuits). Each component of the SAP-1 architecture is implemented separately. D Flip Flop and half adder are used to design the program counter. We implement an accumulator, B-register, & output register using an 8-bit tri-state register and also implement an instruction register & memory address register using a 4-bit tri-state register. With the help of the full adder and XOR gate, we implement the adder-subtractor module. We create a ring counter to implement the controller sequence. Built-in RAM is used. After designing all complements, they are integrated into one system using w-bus. All registered outputs to the W bus are three-state, allowing for orderly data transfer. All other register outputs are two-state; these outputs continuously drive the boxes to which they are connected.\
The following figure represents the SAP-1 computer that we have implemented.

![1607041 SAP-1](https://user-images.githubusercontent.com/52257670/128535405-e2da34d2-608f-4d4d-92ae-2dded56a2fd9.png)



Want to learn more? Go through the references. Thank you!

## Learn More?
1. [Digital Computer Electronics Third Edition by Albert Paul Malvino, Ph.D. and Jerald A. Brown (Page 140)](https://drive.google.com/file/d/1D2qXMVkX8xhGaP6OZdw7Sn8RgAXdskBH/view?usp=sharing)
2. [Project Report](https://drive.google.com/file/d/1Z09-KzC-AR6FDs3Cmzemm2Cj3knNiRXz/view?usp=sharing)
