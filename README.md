```
int led1 = 13;  // 첫 번째 LED 핀 번호
int led2 = 11;  // 두 번째 LED 핀 번호

void setup() {
  pinMode(led1, OUTPUT);  // led1 핀을 출력으로 설정
  pinMode(led2, OUTPUT);  // led2 핀을 출력으로 설정
}

void loop() {
  digitalWrite(led1, HIGH);  // led1 ON
  delay(500);                // 0.5초 대기
  digitalWrite(led1, LOW);   // led1 OFF
  delay(500);                // 0.5초 대기

  digitalWrite(led2, HIGH);  // led2 ON
  delay(500);                // 0.5초 대기
  digitalWrite(led2, LOW);   // led2 OFF
  delay(500);                // 0.5초 대기
}
```
![아두이노](다운로드.jpg)

