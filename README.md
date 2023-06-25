# Magnetic Field Polarity Detector 
## This device is designed for use in the field of magical arts.

## Description
The Magnetic Field Polarity Detector is a compact device designed to detect the presence of a magnetic field and indicate its polarity through vibrations. When the device is exposed to a north-to-south magnetic field, it will vibrate intermittently, while a south-to-north magnetic field will cause continuous vibrations.

## Schematic Design and Simulation in Multisim 14
The chosen design is based on the implementation of a linear Hall sensor, AH49E, which provides an output voltage proportional to the intensity of the magnetic field. The sensor outputs a voltage within specific thresholds depending on the magnetic field intensity. This voltage is then processed by comparators to activate the vibration motor accordingly.

### Design Adaptations
To accommodate the power supply requirements of the circuit components, an additional boost converter stage was included. This stage provides a stable 5V output from the 3V battery. The motor is directly powered from the 3V line to prevent feedback into the 5V line.

## Usage
1. Ensure that the device is turned off before use.
2. Insert a 3V battery into the battery holder.
3. Turn on the device using the power switch.
4. Hold the Magnetic Field Polarity Detector near the target area.
5. Observe the vibration patterns:
- Intermittent vibrations indicate the presence of a magnetic field in the south-to-north direction.
- Continuous vibrations indicate the presence of a magnetic field in the north-to-south direction.
6. Move the detector away from the proximity of the magnetic object to stop the vibrations.
7. Turn off the device when not in use to conserve battery life.
  
## Specifications
- Dimensions: 25mm x 30mm
- Power Supply: 3V battery (included)
- Power Switch: On/Off control


