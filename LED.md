# MVP 2.4 LED Status
## Disconnected
- If advertising publicly: Fast Blue LED
- If disconnected but not advertising: Slow Blue LED

## READY (Connected) / Transmitting Data
- No LED

## ERROR 
- ECG/PPG Error: Fast Blink Red LED
- Temperature Sensor Error: Slow Blink Red LED
- Skin not detected: Slow Blink Red LED
- All Sensors Error: Solid Red LED

## Sleep / Charging
- No LED

# Verbose LED States
## Disconnected
- If advertising publicly: Fast Blue LED
- If disconnected but not advertising: Slow Blue LED

## READY (Connected) 
- Slow Blink Red LED
- Slow Blink Blue LED

## Transmitting Data
- Fast Blink Red LED
- Fast Blink Blue LED

## ERROR 
- ECG/PPG Error: Fast Blink Red LED
- Temperature Sensor Error: Slow Blink Red LED
- Skin not detected: Slow Blink Red LED
- All Sensors Error: Solid Red LED

## Sleep 
- Solid Red LED
- Solid Blue LED

## Charging
- Solid Blue LED for a second and then turns off (Sleep)

# Charger
Red and green led. When connected Green LED will turn off until fully charged. 



# Charger (3.1 Eco)
- If it has input power, 2 red leds light up
- Each LED represents a different battery voltage level, indicating the current charge status of the MVP. As the battery passes each voltage threshold, the respective LED lights up, providing a visual indicator of the battery's charge state.
(Blue LEDs)
