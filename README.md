# Zookeeper

A small Kotlin console app that lets you browse animal habitats from the terminal.  
Enter a habitat number to display its ASCII art and description, or type `exit` to quit.

## Features

- Interactive terminal menu
- ASCII art for six animal habitats
- Simple input loop with clean exit flow

## Available Habitats

- `0` Camel
- `1` Lion
- `2` Deer
- `3` Goose
- `4` Bat
- `5` Rabbit

## How to Run

1. Open the project in IntelliJ IDEA or your preferred Kotlin IDE.
2. Run `Main.kt`.
3. Enter a habitat number when prompted.
4. Type `exit` to leave the program.

## Example

```text
Please enter the number of the habitat you would like to view: 1

Switching on the camera in the lion habitat...
...ASCII art...
The lion is roaring!
Project Structure
•
src/main/kotlin/Main.kt - application entry point and habitat output logic
Notes
This project is a simple Hyperskill console exercise focused on basic Kotlin input handling, control flow, and string output.
