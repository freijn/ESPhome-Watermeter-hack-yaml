# ESPhome-Watermeter-hack-yaml
ESPhome Watermeter hack yaml,  a hack to move from a binary switch to a pulse counter

As my watermeter went crazy if the metal piece stopped exacly under the sensor head, I have create a wire helper
to jump from a binary sensor ( where edge detection is working correctly) to the pulse counter.
In this example code the jump wire is between GPIO02 <=> GPIO04 but can be any as long as you keep the 
code in sync with the pin numbers.
