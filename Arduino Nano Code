const int ledPins[6] = {3, 4, 5, 6, 7, 8};  // LEDs 1–6
const int buzzerPin = 9;

void setup() {
  for (int i = 0; i < 6; i++) {
    pinMode(ledPins[i], OUTPUT);
  }
  pinMode(buzzerPin, OUTPUT);
}

void loop() {
  for (int i = 0; i < 6; i++) {
    digitalWrite(ledPins[i], HIGH);
    tone(buzzerPin, 1000);
    delay(100);
    digitalWrite(ledPins[i], LOW);
    noTone(buzzerPin);
    delay(100);
  }
}
