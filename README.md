# 🚗 안녕하세요, 임베디드 엔지니어로 성장 중인 안해성입니다.

하드웨어와 소프트웨어의 상호작용에 대한 흥미를 바탕으로 특히 자동차 전장과 로봇, SoC (System on Chip) 분야에 관심 있습니다.

---

## ⚙️ Core Competencies
* **차량용 도메인 검증 및 표준 이해**: 현대/기아차 신차(LQ2, BJ, JK 프로젝트 등) ECF DV/PV 신뢰성 시험 수행 및 결과 데이터 분석 역량
* **하드웨어 및 모터 제어 최적화**: BLDC 모터 PWM Duty 제어, 대용량 액추에이터 구동 시 발생하는 플라이백(역기전력) 현상 방지 회로 및 순차 제어 알고리즘 설계
* **임베디드 SW 최적화**: C/C++ 기반 펌웨어 개발, ROS 2 기반 로봇 개발

---

## 🚀 Education & Experience
### Long Term
* **충북대학교** | 전자공학부 졸업 (19.03.04-26.02.23) 
    * 소단위 과정: 자율주행차 SW, 자율주행차 V2X 통신시스템
    * 통신공학 과목 교육보조원 (2024.03.04 - 2024.06.30)
* **(주)보쉬전장 (Bosch Electrical Drives Co., Ltd.)** | EM/EVR-KR 시험시작팀 인턴 (25.01.03-25.06.30)
    * ECF DV/PV 및 릴리즈 테스트 프로세스 수행 및 평가
* **Intel Edge AI SW 아카데미 9기** | 900시간 수료 (25.12.23-26.07.10)
    * 임베디드/펌웨어 개발, Edge AI 개발
 
### Short Term
* **EV CAN 통신 프로토콜의 이해 및 고장진단 실습** | 대림대학교 미래자동차 혁신융합대학사업단 (25.08.11-25.08.12) 
    * 전기차 기본 구조 및 CAN 통신 프로토콜 이해 / 아이오닉 5 엑셀 & 브레이크 진단 실습
* **교류모터 이론 및 임베디드기반 인버터 시뮬레이션 실습** | 충북대학교 미래자동차 혁신융합대학사업단 (25.08.04-25.08.05)
    * DC/AC 모터 원리, PWM 제어 이해 / Matlab - PSIM 이용한 VVVF 인버터 개발 실습
* **아날로그 집적회로 설계 실무** | 청주대 SW 융합클러스터사업단, 충북대 IDEC (24.07.14-24.07.19)
    * CMOS 소자 이해 및 Virtuoso Cadence를 이용한 조합회로 아날로그 설계
   
---

## 🛠️ Tech Stacks

### 💻 Embedded Software
<p>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Embedded C-00599C?style=flat-square&text=Embedded%20C"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
   <img src="https://img.shields.io/badge/Language-Verilog-blue"/>
   <img src="https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white/>
</p>

### 📡 Protocols & Hardware Interface
<p>
  <img src="https://img.shields.io/badge/CAN / LIN-000000?style=flat-square&text=CAN/LIN"/>
  <img src="https://img.shields.io/badge/SPI / I2C-🔥?style=flat-square&text=SPI/I2C"/>
  <img src="https://img.shields.io/badge/PWM Control-00599C?style=flat-square&text=PWM"/>
  <img src="https://img.shields.io/badge/STM32 / MCU-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white/">
</p>

### 🗄️ Databases & Tools
<p>
  <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/DBML-⚙️?style=flat-square&text=DBML"/>
</p>

---

## 📂 Highlighted Projects / Excercise

### [🏥 ROS 2 자율주행 기반 스마트 병동 관리 시스템](https://github.com/HaesungAhn0205/hospital-robot-ROS2.git)
* **설명**: 다중 로봇 자율주행 기술과 AI 비전을 융합한 비대면 의료 보조 시스템
* **멀티 로봇 및 시스템 최적화**: **Domain Bridge**를 활용한 복수 로봇 제어. Nav2 파라미터 튜닝을 통해 좁은 경로 탐지 오류를 해결하고 영상 데이터 최적화로 딜레이 개선
* **실시간 제어**: YOLO11n-pose 및 D435 뎁스 카메라 기반 실시간 감시, 이벤트 중요도(낙상 감지 P1, 환자 요청 P2 등)에 따른 **우선순위 기반 Task Manager 스케줄링 알고리즘 구현**
* **Tech Stack**: ROS 2 Humble, C++, Nav2, TurtleBot3, YOLO11n-pose

### [🖥️ 솔레노이드 액추에이터 기반 실시간 점자 제어 시스템 (Graduation Project)](https://github.com/HaesungAhn0205/Kiosk_PyQt5.git)
* **설명**: 시각장애인이 사용 가능한 키오스크 점자 보조기
* **핵심 역량**: 대용량 액추에이터 구동 시의 전력 분배 및 실시간 태스크 스케줄링 디버깅, 시스템 신뢰성 평가
* **Tech Stack**: Python, PyQT, Raspberry Pi, Actuator Control

### [🧠 ARU 기억 보조 솔루션 (LLM/Vision AI/Physical AI](https://github.com/HaesungAhn0205/AI_Memory_Assist.git) 
* **설명**: LLM 기반 문맥 인지 기술과 Vector DB(또는 RAG 기술) 를 결합한 AI 일상 기억 및 루틴 파악 시스템
* **핵심 역량**: 모방학습을 통한 피지컬 AI 로봇 제어
* **Tech Stack**: ROS 2 Jazzy, Physical AI, RAG, Docker, Python, C++

### [🏭 OPC-UA 기반 Smart Factory MES](https://github.com/HaesungAhn0205/Smart_Factory_MES.git) 
* **설명**: OPC UA, Modbus TCP 등 이기종 프로토콜 간의 실시간 데이터 동기화를 구현한 시스템
* **핵심 역량**: DBML 기반의 체계적인 공정 테이블 구조 설계 및 산업용 통신 환경에서의 데이터 무결성 보장
* **Tech Stack**: C++, QT6, MariaDB

### [📟 CAN 통신 기반 ECF 제어와 HILS 시뮬레이션 (개발 중) ](https://github.com/HaesungAhn0205/motor-control-simulation-can-hils.git)
* **설명**: 차량용 모터 PWM 제어 및 ECU 거동을 모사한 임베디드 소프트웨어 프로젝트
* **핵심 역량**: PC -STM32 - BLDC MOTOR 간 CAN 통신 연결, HILS 시뮬레이션 모사 
* **Tech Stack**: C, STM32, CAN, PWM Control

### [🌐 펌웨어 프로그래밍 연습문제 풀이 모음](https://www.notion.so/2e8f74a5f0d2808884ebd1666769f1cb?source=copy_link)
* **설명**: 임베디드 현업에서 사용되는 비트 조작, 메모리 관리 등 C 프로그래밍
* **핵심 역량**: C Programming, 컴퓨터 구조, 자료구조/알고리즘
* **Tech Stack**: C
---

## 📈 GitHub Stats
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=HaesungAhn0205&show_icons=true&theme=dark" alt="Haesung's github stats" />
</p>
