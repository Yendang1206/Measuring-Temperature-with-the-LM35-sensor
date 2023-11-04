# Measuring-Temperature-with-the-LM35-sensor
## INTRODUCTION
Here is the project of measuring Temperature with the LM35 sensor. The project was divided into two parts:

    1. Simulation and measurement of temperature with LM35
    2. Manufacturing a physcial Printed Circuit Board (PCB) for transmitter
    
### Part 1: Simulation and measurement of temperature with LM35
The project's system was designed by connecting the LM35 sensor with the analog signal processing, communication (transmitter and receiver), analog to digital converter circuits and Arduino. Here is the diagram of this measurement as below:

![measurementprocess](https://github.com/Yendang1206/Measuring-Temperature-with-the-LM35-sensor/assets/86560239/019cad4f-a456-4d6d-9431-e1c69584d872)

The output voltage of receiver was around 5 V and ADC value was 1023 at -30 degree celsius. Here is the testing results of the system's circuit with Arduino at -30 degree celsius.

![testingresultswitharduino](https://github.com/Yendang1206/Measuring-Temperature-with-the-LM35-sensor/assets/86560239/5cd4a750-a1a3-40e0-9916-d2c299ce0b51)

### Part 2: Manufacturing a physcial PCB for transmitter
Besides, the project was to design a PCB for transmitter including its power supply in order to read the analog signal of temperature. PCB was designed on PADS LOGIC for schematic and on PADS LAYOUT for layout. The completed PCB for transmitter is shown as below:

![testingresultswitharduino](https://github.com/Yendang1206/Measuring-Temperature-with-the-LM35-sensor/assets/86560239/54ae7878-498c-4a41-b7ba-e45057ae20f0)

## REQUIREMENTS
- Electronic components and breadboards
- LTspice
- Arduino
- Multimeters
- PADS LOGIC/LAYOUT
