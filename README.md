#include<Arduino.h>
#define LED_PIN 2  // Onboard LED for many ESP32 boards

void setup() {
  pinMode(LED_PIN, OUTPUT);  // Set pin as output
}

void loop() {
  digitalWrite(LED_PIN, HIGH);  // Turn LED ON
  delay(1000);                  // Wait 1 second
  digitalWrite(LED_PIN, LOW);   // Turn LED OFF
  delay(1000);                  // Wait 1 second
}
