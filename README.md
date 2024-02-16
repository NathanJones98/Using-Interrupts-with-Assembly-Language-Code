# Using Interrupts with Assembly Language Code
A Lab for ECE243

The purpose of this exercise is to investigate the use of interrupts for the ARM* processor, using assembly-
language code. 

Part 1: Demonstrates handling interrupts from pushbutton keys. It configures the ARM generic interrupt controller and sets up interrupt service routines (ISRs) for handling button presses.

Part 2: Expands on Part 1 by incorporating a timer interrupt. It configures a timer and its interrupt to increment a global counter, which in turn is used to control the output to LEDR lights.

Part 3: Further expands on the previous parts by incorporating additional functionalities such as modifying timer values based on button presses.

Each part begins with vector definitions followed by a main section where the program logic resides. Here's a brief summary of each part:

# Part 1:

Configures IRQ and SVC stack pointers.
Configures the ARM generic interrupt controller (GIC).
Defines interrupt service routines (IRQ_HANDLER, KEY_ISR) to handle button presses.
Configures interrupts for pushbutton keys.

# Part 2:

Similar to Part 1 but also includes a timer configuration and an additional ISR (TIMER_ISR) for handling timer interrupts.
Configures interrupts for both pushbutton keys and the timer.

# Part 3:

Builds upon the previous parts by adding functionality to modify timer values based on button presses.
ISR (KEY_ISR) now handles button presses and adjusts the timer accordingly.
Each part demonstrates a progressive understanding of interrupt handling and manipulation of hardware peripherals using ARM assembly language
