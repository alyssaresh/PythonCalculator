# PythonCalculator
re-creating the calculator project in Python

ScientificCalculator (maven) 
<a href="https://lucid.app/lucidchart/97fac3af-0824-4f72-b818-2256198b65ea/edit?viewport_loc=-1051%2C-827%2C2364%2C1046%2C0_0&invitationId=inv_3c21faf0-b29c-476f-b706-c0ce044a68f1"> current UML</a>

Description
In this project your team will build a small app to function as a calculator. This app will be built in Python.


Requirements

Testing

All features must be tested with Test classes. Tests must include normal behavior, and any possible error situations. Tests must have descriptive names and should be independent of each other (running or not running one test should not influence the behavior of any other test).

Documentation

You must produce UML diagrams for your program. All classes (excluding test classes) must be included in the UML class diagrams. Each class should have a UML box, with variables and a list of methods.

Core Features

All calculators should have the following features:

A state, representing the value currently displayed on the calculator (default 0) *
Get the current number on the display *
Clear the display *
Change the number on the display *
Add, subtract, multiply, and divide the value on the display by a given number
Calculate the square (x2) and square root (√x) of the number on the display *
Calculate variable exponentiation (xy)
Calculate the inverse of the number on the display (1/x) *
Invert the sign of the number on the display (switch between positive and negative)
Update the display to Err if an error occurs (eg: Division by zero) *
Errors must be cleared before any other operation can take place *
Each operation should automatically update the display

Scientific Features
Switch display mode (binary, octal, decimal, hexadecimal)
switchDisplayMode() should rotate through the options
switchDisplayMode(String mode) should set the display to the mode given
Memory - Store up to one numeric value in memory for recall later (default to 0) *
(M+ key) Add the currently displayed value to the value in memory (store in memory and update display) *
(MC key) Reset memory *
(MRC key) Recall the current value from memory to the display *
Trig functions
Sine - Calculate the sine of the displayed value and display it
Cosine - Calculate the cosine of the displayed value and display it
Tangent - Calculate the tangent of the displayed value and display it
Inverse Sine
Inverse Cosine
Inverse Tangent
Switch trig units mode (Degrees, Radians)
switchUnitsMode() should rotate through the options
switchUnitsMode(String mode) should set the trig units to the type given
Logarithmic functions
Log
10x (inverse logarithm)
Ln (natural logarithm)
ex (inverse natural logarithm)
Factorial function
Custom Features
In addition to the Core and Scientific features, you are required to create at least two of your own features for the calculator. They can be any two features that are not already covered and that you can implement as you see fit. These features must be properly tested.

Hints
The following functions should take the displayed value (x) and updated it according to the given formula: (this may not be an exhaustive list)

square(): x2
squareRoot(): √x
inverse(): 1/x
switchSign(): -x
sine(): sin(x)
cosine(): cos(x)
tangent(): tan(x)
inverseSine(): sin-1(x)
inverseCosine(): sin-1(x)
inverseTangent(): tan-1(x)
factorial(): x! (x factorial)
Submission
Completed projects should be submitted by submitting a pull request against the original repository. All work should be done in your team's repository.
