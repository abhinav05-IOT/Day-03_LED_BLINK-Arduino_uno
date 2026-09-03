# Day-03_LED_BLINK-Arduino_uno
To blink single LED using Arduino Uno and Wokwi simulator

## Objective
Blink LED on Pin 13 to learn GPIO Output - First step for Embedded Job.

## Components
- Arduino UNO
- 1x LED
- Wokwi Simulator

## Wiring
Pin 13 -> LED Anode (Long)
GND -> LED Cathode (Short)

## Code
```cpp
void setup() {
  pinMode(13, OUTPUT);
}
void loop() {
  digitalWrite(13, HIGH);
  delay(500);
  digitalWrite(13, LOW);
  delay(500);
}
