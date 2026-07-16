1. What is a Firmware Library?

A firmware library is a collection of source code files, functions, and utilities that help developers interact with the hardware of an embedded system. Instead of writing low-level code for every peripheral such as GPIO, UART, SPI, I2C, ADC, or Timers, developers can use the functions provided by the library.

Firmware libraries simplify embedded software development by providing reusable and well-tested code. They reduce development time, improve code reliability, and make programs easier to read and maintain. Since the library functions are tested by the hardware vendor or development team, they also help reduce programming errors.

2. Why APIs are Important in Embedded Systems?

An API (Application Programming Interface) is a set of functions and rules that allow different parts of software to communicate with each other. In embedded systems, APIs provide a standard way for application code to access hardware through firmware libraries.

3. What was understood from the lab code?

The code showed how the main.c file calls the GPIO API functions (gpio_init(), gpio_write(), and gpio_read()) that are implemented in gpio.c and declared in gpio.h. This helped me understand the use of firmware libraries, APIs, and modular programming in embedded systems.