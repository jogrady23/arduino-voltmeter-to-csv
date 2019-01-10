# arduino-voltmeter-to-csv
Turns your Arduino into a voltmeter that writes data to a CSV

### Hardware required
You'll need an Arduino/Genuino Uno and N number of resistors (I used 3) to make a voltage divider if the voltage you are measuring is above 5v

### Software required
* Arduino IDE to upload code onto your Arduino
* Python interpreter to run the code

## How to Run
1. Upload the Arduino_voltmeter.ino onto your Arduino. You'll need the IDE open to upload it, but to run the Python script to scrape the serial output, you'll need the IDE closed.
  * You'll need to adjust the values of R1, R2, and R3 according to your voltage divider (if any).

2. Once your Arduino is set, close your IDE and open your Python interpreter to run arduino_serial_reader.py.
  * You'll need to update the name of the port you are using for your Arduino in the Python code.
  * You'll also want to update the output file name depending on your desired name and location.

3. Run the Python script, and your data will be output into a csv file in the file path you specified in the program.

