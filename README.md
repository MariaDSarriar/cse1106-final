# cse1106--final
Description:
Raspberry Pi-base application that processes readings, determines whether the classroom environment is acceptable, 
and provides a visible warning when a temperature is outside the specified range.

## Expected Product Functionality:
-Allow the use to enter classroom temperature readings in Fahrenheit.
-Determine whether a temperature is within the acceptable range 68-76 F, inclusive.
-Display an appropiate NORMAL or WARNING status.
-Calculate the average of the recorded temperatures. 
-Save temperature readings and their statuses to a file.
-Use an LED connected to the Rasberry Pi to indicate a warning condition.
-Allow the acceptable temperature range to be changed according to a new client requirement.

## Example:
        Temperature   SystemStatus     Warning LED 
        72F           NORMAL           OFF
        79F           WARNING          ON
        65F           WARNING          ON
