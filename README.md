아두이노로 온도를 측정하고, 온도를 서버로 보내고, 화면에 표시하시오.
![image](https://github.com/chanwoong00/Arduino/assets/127822662/227e9343-dabd-45d2-ac65-94d739a4d441)
주황선은 GND 흰선은 5V 노란선은 A0에 연결하였습니다

아두이노 코드에 th() 함수는 아날로그 입력 값을 온도로 변환합니다. 그리고 Serial.println(temperature, 2);를 사용하여 온도를 소수점 두 자리까지 출력하도록 만들었습니다.

프로세싱 코드에서 시리얼 모니터에 m 값을 출력하고 m 값을 부동 소수점 숫자로 변환해 그 값이 28.0보다 크면 배경화면을 빨간색으로 설정하고 그렇지 않으면 녹색으로 나오도록 설정했습니다.



소감
아두이노로 온도를 측정하는 코드를 작성하면서 하드웨어와 소프트웨어의 상호작용에 대해 더 깊이 이해하게 되었습니다.
아날로그 센서를 사용하여 데이터를 수집하고, 이를 컴퓨터로 전송하여 처리하는 과정을 경험했습니다. 
이를 통해 센서와 마이크로컨트롤러 간의 상호작용 및 데이터 통신을 더 잘 파악하게 되었습니다.
이번에 코드를 작성해 보면서 아두이노가 전보다 더욱 재밌어진 것 같습니다
다음 과제나 팀 과제도 더욱 열심히 하도록 하겠습니다.
