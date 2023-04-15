## Materials and Equipment
- Thermocouple (x1)
- Arduino / RPI (x1)
- Noctua PWM 12v fan (x1)
- Arcrylic panel (x4) 
	- Will be used to construct a duct/tunnel
- Copper plate (x1)
- Ceramic fibre cotton
- Timer
- Hot plate (?)
- Tongs (?)
- Heat resistance gloves
- 

## Procedure
- With the duct constructed of arcrylic, attach the fan to its front
- Connect the fan to the arduino
- At the other side of the duct, place the ceramic fibre inside the trough in the arcrylic
- Place the thermocouple end on top of the ceramic fibre
- Turn the fan on to the desired speed
- Turn on the hot plate on, and heat the copper plate
- After one minute, use the tongs to transfer the copper plate and situate it on top of the thermocouple, on top of the ceramic fibre
- Read the thermocouple, start recording the timer when the thermocouple reads 100C
- After 30 seconds have passed on the timer, record the temperature on the thermocouple
	- **Note:** Software should be used to record the entire thing
- Remove the copper plate with the tongs and place it onto a heat resistance surface
- Adjust the fan speed and repeat the experiment

## Variables
**Independant**
- Temperature of the copper plate after X seconds of cooling
**Dependant**
- The fan RPM
**Control**
- Ambient room temperature
- Fluid used for cooling (air)
- Type/model of fan
- Enclosure
- Copper plate
- Pressure of room

## Assumptions
- All flow is perfectly laminar or perfectly turbulent (no transition)
- All fluid is incompressible
- Conductive heat transfer from the copper plate to the ceramic fibre is negligible
- No pressure difference along the duct
- No temperature gradient between the surface and bottom of the copper plate
- Gravity is negligible
- Fan speed is perfectly constant

## Equipment
- RPI 
- [Noctua 5v fan](https://www.amazon.ca/Noctua-NF-F12-5V-PWM-Premium-Quality/dp/B07DXDQKZM/ref=sr_1_5?crid=319TK6CGRVUUP&keywords=5v+noctua+pwm+fan&qid=1675980273&s=electronics&sprefix=5v+noctua+pwm+fa%2Celectronics%2C140&sr=1-5)
- [Thermocouple](https://www.adafruit.com/product/270)
- [Thermocouple to RPI Adapter](https://www.adafruit.com/product/269)
- 