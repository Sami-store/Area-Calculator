The AreaCalculator program is designed to compute the areas of various geometric shapes, including circles, triangles, rectangles, squares, and trapezoids. The program will utilize several methods to perform specific calculations and display options to the user.
Method Overview

    printOptions():
        Prints the title and menu options for the user.
        Does not take any arguments and does not return anything.

    pi():
        Returns a constant value of 3.14159.
        Does not require any arguments.

    circle(double radius):
        Calculates and returns the area of a circle using the formula Area=π×radius2Area=π×radius2.
        Calls the pi() method to obtain the value of π.

    triangle(double base, double height):
        Calculates and returns the area of a triangle using the formula Area=12×base×heightArea=21​×base×height.
        Requires two arguments: base and height.

    rectangle(double width, double height):
        Calculates and returns the area of a rectangle using the formula Area=width×heightArea=width×height.
        Requires two arguments: width and height.

    square(double side):
        Calculates and returns the area of a square using the formula Area=side2Area=side2.
        Requires one argument: side length.

    trapezoid(double top, double bottom, double height):
        Calculates and returns the area of a trapezoid using the formula Area=12×(top+bottom)×heightArea=21​×(top+bottom)×height.
        Requires three arguments: top length, bottom length, and height.

Program Flow

    Main Method:
        Calls the printOptions() method to display the menu.
        Uses a loop to keep prompting the user for shape options and inputs until the user enters 0 to exit.
        Based on user selection, calls the appropriate area calculation method and displays the result.
