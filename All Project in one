#define BUTTON_PIN 2 
#define BUZZER_PIN 4
int buttonState = 0; 

void setup()
{
        //Set the digital pin modes
        pinMode(BUZZER_PIN, OUTPUT);
        pinMode(BUTTON_PIN, INPUT);
        pinMode(4,OUTPUT);
}

void loop()
{
        //Read the current state of the button
        buttonState = digitalRead(BUTTON_PIN);
        if (buttonState == HIGH) 
        {
                //If the button is pressed, turn the buzzer on
             
                digitalWrite(BUZZER_PIN, HIGH);
                digitalWrite(4, HIGH);
                delay(500);
                digitalWrite(4, LOW);
                delay(500);
      
        }
        else 
        {
                //If not, turn the buzzer off
                digitalWrite(BUZZER_PIN, LOW);
        }
}
