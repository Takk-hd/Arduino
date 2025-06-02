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

void loop()
  
{
    digitalWrite(9,HIGH);
     delay(1000);
    digitalWrite(9,LOW);
 delay(1000);

}

 ```
