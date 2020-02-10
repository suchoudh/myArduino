########WeekNumber is 07#####***readme_myArduino.txt ##################################
##   File                : readme_myArduino.txt 
##   Creation DateTime   :07_20200210-09_45
##   Last Updated Date   :07_20200210-09_45 
##   Author              : Sunil Choudhary 
##   Remarks             :  This is my trials at DRMZ 
##                              1) This is first point 
##########111#############################################################
#

Attaching potentiometer to analog read signal gives error as 
also need to reset the pins 




Arduino: 1.8.11 (Linux), Board: "Arduino Uno"

Sketch uses 1898 bytes (5%) of program storage space. Maximum is 32256 bytes.
Global variables use 188 bytes (9%) of dynamic memory, leaving 1860 bytes for local variables. Maximum is 2048 bytes.
An error occurred while uploading the sketch
avrdude: ser_open(): can't open device "/dev/ttyACM0": No such file or directory
processing.app.SerialException: Error opening serial port '/dev/ttyACM0'.
	at processing.app.Serial.<init>(Serial.java:147)
	at processing.app.Serial.<init>(Serial.java:82)
	at processing.app.SerialMonitor$2.<init>(SerialMonitor.java:131)
	at processing.app.SerialMonitor.open(SerialMonitor.java:131)
	at processing.app.AbstractMonitor.resume(AbstractMonitor.java:134)
	at processing.app.Editor.resumeOrCloseSerialMonitor(Editor.java:2107)
	at processing.app.Editor.access$1300(Editor.java:117)
	at processing.app.Editor$UploadHandler.run(Editor.java:2081)
	at java.lang.Thread.run(Thread.java:748)
Caused by: jssc.SerialPortException: Port name - /dev/ttyACM0; Method name - openPort(); Exception type - Port not found.
	at jssc.SerialPort.openPort(SerialPort.java:167)
	at processing.app.Serial.<init>(Serial.java:136)
	... 8 more
Error opening serial port '/dev/ttyACM0'.

This report would have more information with
"Show verbose output during compilation"
option enabled in File -> Preferences.


Ran on 07_20200210-09_45
