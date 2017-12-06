# High speed oscilloscope using an NXP LPC4370
Course name : "D7018E - special studies in embedded systems"

Carl Bäck, carbck-4@student.ltu.se, 950601-3474

## Project description
The project is meant to evaluate the use of the RUST programming language to implement high speed data accusition on the NXP LPC4370, 200Mhz M4/M0 multicore microcontroller. Project done in connection with Grepit AB. The parts that will be worked on in this project is first to get the dual core system up and running. A connection between the microcontroller and an external PC will have to be implemented to be able to transfer data between these units. The main idea here is to use a USB connection which probably will be developed in cooperation with another person in the course that is working on a general support crate for the LPC4370 microcontroller. Control of the ADC is to be implemented which is the hardware unit that will mainly be used for the oscilloscope. To be able to use the ADC at the intended speeds an efficient implementation of a DMA configuration will also have to be implemented. The project will be done at 25% during lecturing periods two and three at Luleå University of Technology.

## Grading goals

### Grade 3:

Testing and experimenting on the device is to be done to see what parts need to be worked on and to find possible problems concerning the implementation of the ADC and it's neccesary subsystems. Creating a proof of concept, show whatever it's possible to complete the given task. 

### Grade 4:

A plan for how to implement an efficient API, based on the RUST language model is to be created.

### Grade 5:

Implement the API solution and perform testing of it. Design relevant test cases to prove that the criterias are met and also create simple examples that will show how that the implementation fulfills the API plan. 

### Reference materials
#### Datasheet of processor:
https://www.nxp.com/docs/en/data-sheet/LPC4370.pdf
