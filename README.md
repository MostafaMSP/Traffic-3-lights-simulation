# Traffic-3-lights-simulation

int redled=13;
int greenled=12;
int yellowled=11;

void setup()
{
  pinMode(redled, OUTPUT);
  pinMode(greenled, OUTPUT);
  pinMode(yellowled, OUTPUT);
}

void loop()
{
  digitalWrite(redled, 1);
  delay(200); // Wait for 1000 millisecond(s)
  digitalWrite(redled, 0);
  delay(200); // Wait for 1000 millisecond(s)
  digitalWrite(greenled, 1);
  delay(200); // Wait for 1000 millisecond(s)
  digitalWrite(greenled, 0);
  delay(200); // Wait for 1000 millisecond(s)
  digitalWrite(yellowled, 1);
  delay(200); // Wait for 1000 millisecond(s)
  digitalWrite(yellowled, 0);
  delay(200); // Wait for 1000 millisecond(s)
}
