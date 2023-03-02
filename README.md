# hardware-playground

Welcome to the Hardware-Playground repository! This is where I store all of the Verilog/SystemVerilog modules and projects I've created while learning digital electronics and hardware design. This repository serves as my playground to experiment with different concepts, techniques, and architectures in hardware design.

## Contents

This repository contains a collection of modules covering a broad range of topics, including:

- Combinational and sequential logic
- Arithmetic circuits
- Memory and storage elements
- And more!

Each module includes a Verilog/SystemVerilog file, a testbench, and a README file with a brief description of the module and its functionality.

## Usage

Feel free to use and modify the code in this repository for your own projects. To get started, clone the repository to your local machine:

```
git clone https://github.com/diab-maslaha/hardware-playground.git
```

Each module is contained in its own directory, which includes the Verilog/SystemVerilog file, the testbench, and the README file. To run the testbench, navigate to the module directory and use the following commands:

```
iverilog -o testbench module_name_tb.v module_name.v
```

```
vvp testbench
```

Replace `module_name` with the name of the module you want to test. The `iverilog` command compiles the Verilog/SystemVerilog files, and the `vvp` command runs the simulation.

## Feedback

If you find any issues with the code or have suggestions for improvements, please feel free to let me know. I'm always looking for ways to improve my skills and learn more about digital electronics and hardware design.

## License

The code in this repository is licensed under the MIT License. Feel free to use and modify the code for your own projects, but please include a reference to this repository if you do.
