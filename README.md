<!-- MED-007 -->

# Virus Shape

This program creates a beautiful visual pattern using Python's Turtle graphics library. The pattern resembles the shape of a virus, which is generated by a simple loop that progressively draws lines and turns the turtle to create a spiraling effect.

## Repository

[Virus-Shape Repository on GitHub](https://github.com/MED-007/Virus-Shape.git)

## Getting Started

To run this program, you'll need to have Python installed on your machine. The script uses the `turtle` module, which is included with Python's standard library.

### Prerequisites

- Python 3.x

### Running the Script

1. Clone the repository:
    ```bash
    git clone https://github.com/MED-007/Virus-Shape.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Virus-Shape
    ```

3. Run the script:
    ```bash
    python VirusShape.py
    ```

## How It Works

The script creates a `turtle.Turtle()` object and a `turtle.Screen()` object to control the drawing and background.

- The background is set to black with `s.bgcolor("black")`.
- The turtle's drawing color is set to green with `t.pencolor("green")`.
- The turtle starts at the top of the screen and begins drawing a spiral pattern by moving forward with increasing length and turning by an incrementing angle.
- The loop runs until the turtle completes 200 turns, creating the virus-like shape.

### Customization

You can customize the pattern by modifying the values of `a` and `b` in the loop, which control the length of the lines and the turning angle. You can also change the colors to create different effects.

## Demo

Here's a preview of the pattern generated by this script:

![Screenshot 2024-08-23 110347](https://github.com/user-attachments/assets/858f5576-b7fd-47a6-8e17-bb3145261ae6)
