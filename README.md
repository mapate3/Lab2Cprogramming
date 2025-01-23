# Lab2Cprogramming
It stops blinking 

/*
  Blink

  Turns an LED on for one second, then off for one second, repeatedly.

  
// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
  int timesToBling = 1;
  int timesToBlink = timesToBlink + 2 * 4;
//   if timesToBlink > 4 {
//     digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
//     delay(1000);                      // wait for a second
//     digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
//     delay(1000);  
//   }
//   else{
//     digitalWrite(LED_BUILTIN, HIGH);
//   }
// }

// for (int i = 0; i < timesToBlink; i++) {
//     digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
//     delay(1000);                      // wait for a second
//     digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
//     delay(1000);                      // wait for a second
//   }
// }

 while (timesToBlink > 0) {
    digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
    delay(1000);                      // wait for a second
    digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
    delay(1000);                      // wait for a second

    timesToBlink--;  // Decrease the blink count each time
  }

}

// the loop function runs over and over again forever
void loop() {

}
