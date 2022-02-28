## Working with Sensors Using Python

You might remembered that in the previous lectures, we have created our UniSat OBC! 
![UniSat OBC in KiCad](https://raw.githubusercontent.com/azataiot/images/master/PicGo3.png)

The OBC instance that we created, have several sensors like:
- SDS011 PM2.5 Dust sensor
- HTS221 Humidity and Temperature sensor
- LPS251H Pressure sensor.

**But how we are going to program them ?**

Do you remmebered turtle is an object ? ok, then you can understand that sensor-board or the sense-hat in this example we are talking to, is also an object.

We first import the object that we want to talk to (as you have before):

```
from sense_hat import SenseHat
```
Then we will initialize our object:

```
sense = SenseHat()
```

Now, let's put them together and try something cool (run the code and see what will happen):

<iframe src="https://trinket.io/embed/python/cdbba2eb7f" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

To display a different message, you can write anything you like between the quotation marks ("").

Notice: try to change the code from `sense.show_message("UniSat")` to  `sense.show_message("Azat")` see what will happen.

### Measure the humidity
The humidity sensor in can measure the humidity in the air around it, a useful feature to help you gather data about the conditions in space.

The Sensor measures the humidity in the space in percentage water concentration in the air.

Add this code to take a humidity reading:
```
humid = sense.get_humidity()
```
This line will measure the current humidity, and store the measured value in the variable humid.

To display the current humidity as a scrolling message on the display, add this line of code:
```
sense.show_message(str(humid))
```
The str() part converts the humidity from a number into text so that the diaplay can display it.

Now try it together:

<iframe src="https://trinket.io/embed/python/ae9a94804a" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

### Challenge
Complete the code below to get the temperature from the sensor and show the temperature value.

<iframe src="https://trinket.io/embed/python/c0c8d181eb" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

