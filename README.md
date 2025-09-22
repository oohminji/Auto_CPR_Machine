# Auto_CPR_Machine

## 프로젝트 개요
> - 장시간 진행해야하는 CPR을 자동으로 시행하는 시스템<br>
> - 사람보다 올바른 위치와 힘으로 정확한 CPR 제공 <br>
> - 의료 인력 부족과 이동 시간 확보
## 시스템 기능
- 🔄 실시간 처리: 환자의 심박수 측정 및 App을 통한 실시간 모니터링<br>
- 🫀 자동 심폐소생술 : 리니어 액추에이터를 이용한 흉부 압박<br>
- 📍 흉부 위치 파악 : Pixy카메라와 압박센서를 활용한 환자의 흉부 위치 파악<br>
- ↔️ 흉부 위치 이동: 리니어 레일을 통해 흉부 위치로 이<br>

## 시스템 구성도
<img width="600" height="550" alt="image" src="https://github.com/user-attachments/assets/097a003d-8af3-4a28-a1dc-8f7f47baa968" />

## 시스템 흐름도
<img width="572" height="500" alt="image" src="https://github.com/user-attachments/assets/6236444f-69e3-473c-bf36-5a75951f3210" />

  
## 담당 역할
- 하드웨어 제작 & 설계
  
## 사용 기술
| 구분 | 기술&장비|
|---|---|
| MCU & Module | MPINO-8A8R, Arduino Mega |
| 개발 TOOl | MPINO STUDIO, Arduino IDE | 
| 통신 | I2C |
| Sensor | 리니어 액추에이터, 압박 센서, 리니어 레일|
| Language | C , C++ |

## 개발 중 문제 및 해결
| 제작/기획 과정 | 문제점 | 해결 방안 |
|---|---|---|
| 리니어 레일 동작 | 모터의 속도와 힘 부족 | 전선을 AWG24 -> AWG22교체로 전류용량 증가 & Power Supply 사용 |
| 회로 연결 | Arduino UNO의 Analog&Digital 핀 부족 | Arduino Mega로 변경 |

## 시연 결과
**[시스템 내부]**<br>
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/da215ce7-fb89-43ac-912e-f3e0acde2e39" /> <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/2ba7f620-5765-4ee6-a48a-16955a742f73" /><br>
**[시스템 외관]**<br>
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/e2164f00-fd95-4fd9-9817-c3278bdc2fa5" />




