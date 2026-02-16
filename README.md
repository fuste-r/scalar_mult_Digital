### About

This project utilizes hneemann's [Digital](https://github.com/hneemann/Digital "Digital") to build a simulated processor specialized for scalar multiplication. 

![](https://github.com/fuste-r/scalar_mult_Digital/blob/main/images/scalar_diagram.png)


### Features

- The processor found in **main_cpu.dig** takes a 40-bit input (split between 32 + 8 bits due to a bus limitation in Digital). The breakdown of input is:
 - 10 4-bit inputs
 - 9 input values, creating a 3x3 grid
 - 1 scalar value, the value to multiply the 3x3 grid by
- The resulting output is 72 bits, consisting of 9 8-bit values from the resulting operation
