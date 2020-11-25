# BasicArduino

## Hello Arduino

//Jack Helmke
//November 24, 2020
//This code tells an LED to blink on and off every second.


  //Tells arduino what pin is led
int led = 13;

void setup() {
    Serial.begin(9600);   
    pinMode(led, OUTPUT); //Tells it that the led pin is an output
}

void loop() {
    digitalWrite(led, HIGH);  //Turns the led on
    delay(1000);              //Waits 1 second
    digitalWrite(led, LOW);   //Turns the led off
    delay(1000);              //Waits a second before repeating
}

It was fun to get started coding! It's tricky how precise you have to be with some things though, even on a small assignment like this.

[Arduino Code Link](https://create.arduino.cc/editor/jhelmke83/d0e1fae3-fb51-4115-a15f-b76e9aeb4ad8)
