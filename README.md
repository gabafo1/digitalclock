# Simple C Clock Program

This is a simple C program that creates a digital clock on the command line interface. It takes input for setting the initial time and continuously updates the time display every second.

## Prerequisites

This program is designed to run on a Windows operating system due to its dependency on the `windows.h` library for functions like `Sleep()` and `system("cls")`.

## Usage

1. **Compile**: Compile the program using a C compiler such as GCC.

    ```bash
    gcc clock.c -o clock
    ```

2. **Run**: Execute the compiled program.

    ```bash
    clock
    ```

3. **Set Time**: Input the initial time in the format `hour minute second` when prompted.

4. **View Clock**: The clock will continuously update and display the current time in HH:MM:SS format.

5. **Exit**: To exit the program, press `Ctrl + C` in the terminal.

## Note

- Ensure that the input time is within valid ranges (hour: 0-12, minute: 0-59, second: 0-59).
- Closing the program window will terminate the clock.
