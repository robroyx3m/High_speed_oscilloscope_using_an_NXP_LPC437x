# High speed oscilloscope using an NXP LPC437x
Course name : "D7018E - special studies in embedded systems"
Carl Bäck, carbck-4@student.ltu.se, 950601-3474

# Project description
The project is meant to evaluate the use of the RUST programming language to implement high speed data accusition on the NXP LPC43XX, 200Mhz M4/M0 multicore microcontroller. Project done in cojunction with Grepit AB. The parts that will be worked on in this project is first to get the dual core system up and running. A connection between the microcontroller and an external PC will have to be implemented to be able to transfer data between these units. Control of the ADC is to be implemented which is the hardware unit that will mainly be used for the oscilloscope. To be able to use the ADC at the intended speeds an efficient implementation of a DMA configuration will probably have to be implemented. 

# Grading goals
Grade 3:
For a grade 3 ....
e.g. Using RUST to implement the connection to the ADC we should be able to connect to this hardware unit and read data from it, speed do not matter and neither does resolution or data processing/storage.
e.g. Implementing the above  (in the project description) given parts, in RUST, separate of each other so that each is can be used but that no framework for connecting it all together exists. 

Grade 4:
For a grade 4 ....

Grade 5:
For a grade 5 ....
