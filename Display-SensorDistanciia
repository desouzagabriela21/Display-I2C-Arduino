#include <Adafruit_LiquidCrystal.h> // adiciona a biblioteca

Adafruit_LiquidCrystal lcd(0x20); 

  int triggerPin = 9;  
  int echoPin = 10;  

void setup()
{
  lcd.begin(16,2); 
  
  Serial.begin(9600);
  pinMode(triggerPin, OUTPUT);
  pinMode(echoPin, INPUT);
 
}

void loop()
{
  digitalWrite(triggerPin, HIGH);
  delayMicroseconds(10);
  digitalWrite(triggerPin, LOW);
    
    
  float tempo = pulseIn(echoPin, HIGH);
  float distancia = 0.01723 * tempo;
  
  
  lcd.setCursor(0,0);
  lcd.print("Distancia em cm:");
  
  lcd.setCursor(0,1);
  lcd.print(distancia);
}
