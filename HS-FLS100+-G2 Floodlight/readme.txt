Tested 3 HomeSeer HS-FLS100+-G2 Floodling Sensors as part of adapting this driver.

New to the Gen 2 (-G2) are sensitity control for the motion sensor, a temperature sensor, and significant changes to the control paramters.
The user manual explains these features, and is posted with the driver.

Following are notes from testing.

Testing of all 3 units suggest internal heating is likely affecting the temperature sensor. At power on, each indicated reasonable measurements (withing 1 Deg.F).
Temperature reports increased gradually without the lights powered. Finally reaching about +5 degF above ambient of 68.5.
The device includes a parameter for calibration offsets of temperature. Testing indicated this parameter corresponds to Deg.F. as the temperature status also reports.
The manual states the temperature calibration is Deg.C.

Noted a large Lux report offset for one unit. In a low-light environment two indicated 50-80 Lux readings. One reported 9 and 10 Lux.
This affects local light activations for both motion and the dusk-dawn operation. 
The manual indicates a minimum setting of the threshold of 10 Lux for determinging dusk status.
So, one of the units may operate in some daytime environments such as complete cloud cover.
