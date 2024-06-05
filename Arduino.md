#include <LiquidCrystal.h>

LiquidCrystal lcd(4, 5, 8, 9, 10, 11);

int sensorEcho = 6;
int sensorTrig = 7;
int beeper = 3;
int ledRed = 2;

byte dino[] = {
  B01110,
  B01110,
  B01100,
  B01111,
  B11101,
  B01010,
  B01010,
  B01010
};

byte dino2[] = {
  B01110,
  B01110,
  B00110,
  B11110,
  B10111,
  B01010,
  B01010,
  B01010
};

byte dancer[] = {
  B00000,
  B00100,
  B10100,
  B01110,
  B00101,
  B00100,
  B01010,
  B01001
};

byte dancer2[] = {
  B00000,
  B00100,
  B00101,
  B01110,
  B10100,
  B00100,
  B01010,
  B10010
};

void setup() {

  lcd.begin(16, 2);
  lcd.createChar(0, dancer);
  lcd.createChar(1, dancer2);
  lcd.createChar(2, dino);
  lcd.createChar(3, dino2);
  

}

void loop() {
  int n;
  while(n!=-1){  
  lcd.clear();
  lcd.setCursor(0, 1);
  lcd.write(byte(0));
  lcd.write(byte(2));
  n--; 
  delay(400);
  lcd.setCursor(0,1);
  lcd.write(byte(1));
  lcd.write(byte(3));
  n--;
  delay(400);
  }
  }
