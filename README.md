# pico_datalogger
Raspberry pi pico datalogger
BME280 Datalogger
Measures temperature, humidity and air pressure and writes to files which can be opened in a spreadsheet.
Save the code as main.py and it will run as sooon as power is applied.
To use, set the time that you want the datalogging to start (time_input), and then plug into a power supply or connect your battery at the time you have set.
 The code will run for a number of days storing each days data in a file.
Set number of days to run (j), the number of readings taken per day (i) and sleep() near the end is number of seconds between readings.
When the dataset is complete, the onboard LED will flash. At this point, plug into your computer so that you can access the files stored on your pico. 
