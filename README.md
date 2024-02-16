# Laundry-Machine




## 구현 내용

1. 세탁기 기능 -> [세탁, 헹굼, 탈수]
2. 버튼 종류
  - 전원 버튼
  - 일시 정지 / 시작 버튼 (한번 누르면 시작, 다시 누르면 일시 정지)
3. 여닫이 문 닫혔을 시에만 모드 시작
4. 탈수까지 모두 종료되었을 때 종료음 (Buzzer)


![image](https://github.com/koreaminyoung/Laundry-Machine/assets/159984765/e073d373-4e60-41ac-a7cc-4bf8bf33388a)

맨 왼쪽부터 1, 2, 3, 4 버튼이라고 가정  
버튼 1) 전원 버튼  
버튼 2) 모드 선택 버튼  
버튼 3) 실행 버튼 / 일시 정지 버튼  
버튼 4) 탈수 횟수 버튼  

## 구현 의의
1. 타이머/카운터 3가지를 적용하여 인터럽트끼리의 충돌을 방지 타이머/카운터0 - dc모터 PWM제어, 타이머/카운터1 - 초음파 센서, 부저 출력, 타이머/카운터3 - 일시정지 / 재시작)
2. while문을 이용하여 조건 만족할 때까지 hold 기능
3. 버튼 state를 지정하여 버튼 개수를 최소화하려고 노력함
4. 초음파 센서를 이용하여 실제 세탁기처럼 문이 잘 닫혀있을 경우에만 동작하도록 설정
5. 실제 세탁기 부저음을 입력하여 실제 세탁기처럼 구성

## 구현 내용
![image](https://github.com/koreaminyoung/Laundry-Machine/assets/159984765/5f45ce55-a850-4405-81b5-cb0cd91674b1)




![image](https://github.com/koreaminyoung/Laundry-Machine/assets/159984765/8b184d83-ec4b-4858-97e0-2775b643b1ae)

![image](https://github.com/koreaminyoung/Laundry-Machine/assets/159984765/b9493752-64ec-4625-89a4-ce15cfcb6e4c)





