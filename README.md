# arduino_matrix_led_mlapp
matlab interface application that communicates with arduino

![image](https://user-images.githubusercontent.com/49786364/207008245-f5dd8370-30a5-450a-aa53-fafad2bba163.png)

interface looks above

First of all, I should talk about what the buttons do. communicate button initiates communication with arduino. led on and led off buttons are used to turn the leds on and off. The plot button plots the time-lumen graph with the data from the photoresistor. The print button prints the graph. The save button saves the graphic.

The boxes on the right are the representation of a 6x6 matrix led. If the led on button is pressed, the leds representing the positions of the ticked boxes will work. if the led off button is pressed, no led will work. The bar below is the bar where the brightness of the LEDs is adjusted. In fact, the pwm cycle duty is determined by the number selected from this bar.
