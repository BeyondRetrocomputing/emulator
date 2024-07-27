# Understanding computer emulation

<img src="/res/icon_computer_in_computer.jpg?raw=true" width=50% align="left">

This project takes you on the fast track, understanding the fundamental workings of a **computer**, a **compiler**, and a **debugger**, all within your browser! But first and foremost, we'll build a hassle-free computer emulator entirely in JavaScript, demonstrating core concepts like processing instructions, memory, and input/output, let alone the basics of emulation itself.  

**Understanding how to build computer emulators remains extremely valuable**, often misunderstood but omnipresent under different buzzwords like virtual machines (VMs), cross-platform virtualisation, containerisation, cloud computing and many other services we take for granted like Robotic Process Automation (RPA), orchestrators, software-defined networking and more.  

Retrocomputing has gained significant popularity among nostalgic amateurs (in the proper sense of the word), but beyond that; we also should appreciate Retrocomputing as the key to understanding large bytes of contemporary technology!

Whether one prefers to read instructions or watch the videos we recorded on this topic, they can help you understand the very basics of binary-logic-based computing, in other words, a [universal Turing machine](https://en.wikipedia.org/wiki/Universal_Turing_machine) based on the [Von Neumann architecture](https://en.wikipedia.org/wiki/Von_Neumann_architecture).  While more powerful architectures exist, the concepts outlined here trace the evolution of digital computing as it entered our households around 1980 and has been participating in our daily lives ever since.  In this section, we will step-by-step build all the essential components that make a fully functioning computer.

## What You'll Learn

- A :heart: for the emulator: the system clock
- Computer :gear::
   - the databus
   - memory (RAM/ROM)
   - I/O (memory-mapped)
   - CPU (instructions & program execution)
- Last, but not least, a good portion of JavaScript :coffee: programming practice!

## Getting Started:

While this project starts from very simple code to gradually more complex, you require no additional software or server setup; just some basic understanding of JavaScript.  Download this project and start the emulators directly in your browser by clicking the local file **index.html**.  Alternatively, check out [index.html](https://BeyondRetrocomputing.github.io/emulator/) to run this project directly on GitHub.
All the JavaScript components can be found in the /res folder and can be opened using your favorite development environment (IDE) featuring basic JavaScript syntax highlighting.

index.html: The main HTML file that displays the emulator interface and loads the JavaScript components.
cpu.js: Defines the Central Processing Unit with functions for fetching, decoding, and executing instructions.
memory.js: Implements the memory component, storing data and instructions.
io.js: Handles input/output operations, allowing interaction with the emulator.

Running the Emulator:

Open index.html in your development environment.
The webpage will display an interface for providing instructions and observing the emulator's output.
Enter simple instructions (explained in the code comments) and press "Run" to see the emulator process them.
Understanding the Code:

Each JavaScript file focuses on a specific component of the computer:

cpu.js: This file defines the CPU's functionality. It reads instructions from memory, decodes them, and performs operations based on the instruction type (e.g., adding values, storing data in memory).
memory.js: This file acts as the computer's memory, holding both data and instructions as an array. The CPU interacts with memory to read and write data.
io.js: This file handles user interaction with the emulator. It allows you to input instructions and displays the output generated by the CPU during program execution.
Embrace the Journey:

This is a simplified representation of a computer, but it provides a solid foundation for understanding how these machines work at their core. Explore the code, experiment with different instructions, and see how they manipulate data and influence the emulator's behavior.

# Further Exploration:

The included code offers a basic framework. You can extend it to:

Implement additional instructions for more complex operations.
Develop a visual representation of the memory and its contents.
Design an assembly language format for user-friendly instruction creation.
Feel free to tinker and expand upon this project to deepen your understanding of the fascinating world of computers!
