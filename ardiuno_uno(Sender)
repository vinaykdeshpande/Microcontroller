int pin = 13;

void setup() {
  Serial.begin(9600);  // Initialize Serial at 9600 baud
  pinMode(pin, OUTPUT); // Set pin 13 as OUTPUT
}

void loop() {
  digitalWrite(pin, HIGH);   // Turn the LED on
  Serial.println("ON");      // Print ON to Serial Monitor
  Serial.write("ON\n");      // Send ON via UART
  delay(3000);               // Wait for 3 seconds

  digitalWrite(pin, LOW);    // Turn the LED off
  Serial.println("OFF");     // Print OFF to Serial Monitor
  Serial.write("OFF\n");     // Send OFF via UART
  delay(3000);               // Wait for 3 seconds
}
