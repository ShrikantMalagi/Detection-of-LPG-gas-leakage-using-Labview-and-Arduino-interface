# Detection-of-LPG-gas-leakage-using-Multisim-and-Arduino-interface
The project makes use of an MQ-2 gas sensor for detection of butane in LPG (80% of its composition), which connects to the Arduino, The calculations are all processed in multisim and interfaced with the LINX tool.  The processed inputs detect whether there is a gas leakage and if it's true a stepper motor opens the window to let the gas out.

There is the working .vi file for the project "LPG.vi"
You need to install linx tool in Multisim to use this project, you also need a stepper motor, a gas sensor, and an arduino.
You can tweak the parameters for your requirements and detect other gases and use other gas sensors just make sure to read the documentation of the sensor and set the parameters accordingly
