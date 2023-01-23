The simulation included in this folder was written in MATLAB: Simulink.
I used no special libraries.

No special setup is required to run the default case. The default case includes all perturbations
and all sensor errors.

There are 5 desirable graphs to be looked at:
	Real Attitude(q) - Located up and to the right of the Dynamics Block
	Real Attitude(T) - Located to the right of the Real Attitude(q) scope
	Real wsat - Located below the Real Attitude scopes
	Estimated Attitude(T) - Located to the right of the Attitude Determination Block
	Nominal Ti2b - Located inside the Attitude Control Block in the top left
These graphs can be used to see effects of the switches.

There are 9 switches to turn on and off different effects:
	Gravity Gradient Torque - Located inside Dynamics Block
	Magnetic Torque - Located inside Dynamics Block
	Angular Random Walk - Located inside Sensors.Real Block
	Gyro Bias - Located inside Sensors.Real Block
	Horizon Sensor Error - Located inside Sensors.Real Block
	Magnetometer Error - Located inside Sensors.Real Block
	Actuator Error - Located inside Actuators Block
	Turn off Control System - 2 switches:
		Located above Dynamics block, turn both on or off to disconnect control input

These should be all the necessary changes you have to make an data you have to see to verify the
validity of this simulation.
	

