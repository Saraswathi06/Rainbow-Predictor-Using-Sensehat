# Rainbow-Predictor-Using-Sensehat
To create a project which predicts a rainbow when the required conditions for temperature and humidity are met.


In this mini project we will use the temperature and humidity sensors on the Sense HAT to predict whether there is a good chance of spotting a rainbow. When the right conditions are detected the rainbow will be displayed on the Sense HAT LED matrix.

A threshold is a number that indicates an import change. 20 degree Celsius and 80% humidity are thresholds for the rainbow detector.

1. Import the necessary header files.
2. Make a Sense hat object.
3. Set the variables for colors.
4. Set up a list named rainbow containing the colour of each pixel.
5. Give input by changing the values of temperature and humidity by moving the slider.
6. Run a while loop in which conditions are checked.
7. If humidity >80 and temperature>20 ,call sense.set_pixels(rainbow) and print the humidity and temperature values.
8. Else if humidity>80 and temperature<0 ,call sense.clear[255,255,255]
9. Else if humidity<=80 and temperature>20, call sense.clear[255,255,0]
10. Else call sense.clear() to clear the LED matrix
