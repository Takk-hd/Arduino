# LED 예제 1
## LED 깜박이기
![LED](./images/LED00.png).

## Source code

 ```c
void setup()
{
  Serial.begin(9600);
  pinMode(9,OUTPUT);
 
}

void loop(){
 if(Serial.available() > 0)
{
  char sData = Serial.read();
  if(sData =='a')
{
    digitalWrite(9,HIGH);
}
  else if(sData == 'b')
{
 digitalWrite(9,LOW);
  }
 }
}

 ```
