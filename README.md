# Wake up light

This is the circuit and code for a smart, super bight light that slowly brightens in the mornings to wake me up without an alarm.
The light can also be used as reading light at night with a timer to turn off automatically.
It features a 2004 LCD and a rotary encoder for user input.
The encoder has a calibrated debounce circuit and a schmitt-trigger for the cleanest possible signal.


An LED driver is required alongside this circuit.
I have decided to use a ZK-SJ20 to protect the LED from over current.
Max. LED power is 50 watts.
A CR2032 battery is required for the RTC to keep the time when the power is disconnected.


## To Do

* Since the device is connected to the wall outlet, energy efficiency was not of the highest concern. However, in feauture iterations, I will replace the linear voltage regulator with a buck converter.

