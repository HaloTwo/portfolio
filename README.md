<img width="763" height="355" alt="image" src="https://github.com/user-attachments/assets/e9703cbd-cf9b-4e38-b992-c345fdf57b32" /># 🎮 이수민 | Game Programmer 

> 상용 게임 클라이언트 및 코어 로직 개발 경험을 기반으로  
> 액션 게임의 전투 시스템, AI, 게임플레이 구조 구현에 집중하는 프로그래머입니다.

📧 Email: lsm6265@naver.com  

# 👋 About Me

> 상용 모바일 게임 클라이언트 및 코어 로직 개발 경험을 가진 프로그래머입니다.  
> Unity 실무 경험을 바탕으로 현재는 Unreal Engine 5 기반 액션 전투 시스템과 게임플레이 구조 설계에 집중하고 있습니다.
> 팀 협업을 중요하게 생각하며, 문제를 구조적으로 분석하고 시스템 단위로 해결하는 개발 방식을 지향합니다.

## 🧱 Tech Stack

### 🎮 Engine
<img src="https://img.shields.io/badge/Unreal%20Engine%205-313131?style=flat-square&logo=UnrealEngine&logoColor=white"/> <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=Unity&logoColor=white"/>

### 💻 Language
<img src="https://img.shields.io/badge/CSharp-239120?style=flat-square&logo=C%20Sharp&logoColor=white"/> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=C%2B%2B&logoColor=white"/>

### 🧠 Gameplay & Systems
<img src="https://img.shields.io/badge/GAS-5C2D91?style=flat-square"/> <img src="https://img.shields.io/badge/Behavior%20Tree-AI-orange?style=flat-square"/> <img src="https://img.shields.io/badge/Object%20Pool-Optimization-blue?style=flat-square"/> <img src="https://img.shields.io/badge/Save%20System-Data-green?style=flat-square"/>

### 🛠 Tools
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/> <img src="https://img.shields.io/badge/Photon-0A91D5?style=flat-square"/>


---

# 🧠 Main Project (Unreal Engine 5)

## ⚔️ UE5 Action RPG (Lies of P Inspired)
Gameplay Ability System(GAS) 기반 싱글플레이 액션 전투 시스템 프로젝트

- Engine: Unreal Engine 5 (C++ / Blueprint)
- Focus: Combat System / AI / Gameplay Architecture
- 💻 GitHub: [프로젝트 상세 설명](https://github.com/HaloTwo/LOP)

### Core Features
- Gameplay Ability System(GAS) 기반 전투 시스템 설계
- Target Lock-On 시스템 구현
- Weapon Trace 기반 공격 판정 처리
- Behavior Tree + EQS 기반 적 AI
- Boss Phase 패턴 전환 시스템
- Motion Warping + Anim Notify 전투 연출
- DataAsset 기반 무기/스킬 데이터 구조 설계

---

# 💼 Commercial Experience (Released Games)

ALBUS | Client Programmer (2023.09 ~ 2025.03)  
Unity3D 기반 상용 모바일 게임 개발 및 출시 경험

- 🏝 WaterParkBoys  
  📱 [Google Play](https://play.google.com/store/apps/details?id=com.Albus.WaterParkBoys&hl=ko) | 🍎 [App Store](https://apps.apple.com/us/app/waterpark-boys/id6457257165)

- 🎡 AwesomePark : Idle Game  
  📱 [Google Play](https://play.google.com/store/apps/details?id=com.Albus.AwesomePark&hl=ko) | 🍎 [App Store](https://apps.apple.com/kr/app/awesome-park-idle-game/id6482050793)

- 🛼 Skate Shop: Roller Disco Dance  
  📱 [Google Play](https://play.google.com/store/apps/details?id=com.albus.newrollerdisco&hl=ko) | 🍎 [App Store](https://apps.apple.com/us/app/skate-shop-roller-disco-dance/id6744957869)

- 👑 MakeAQueen (Android Only)  
  📱 [Google Play](https://play.google.com/store/apps/details?id=com.Albus.MakeAQueens&hl=ko)

### 🔧 Core System Development
- 코어 게임 로직 아키텍처 설계 및 기능 구현
- NPC(손님) 이동 및 행동 패턴 로직 구현
- 이벤트 트리거 기반 상호작용 시스템 개발
- 건물 기능을 Delegate 기반 이벤트 구조로 설계하여 시스템 결합도 감소

### 💾 Hybrid Save & Data Architecture
- 중요 게임 데이터는 암호화된 JSON 파일 기반으로 저장/복호화 구조 설계
- 시간, 설정 등 경량 데이터는 PlayerPrefs로 분리 저장하는 Hybrid Save System 구현
- 저장 데이터 계층 분리를 통해 안정성과 성능을 동시에 고려한 구조 설계

### 🧩 Save Data Integrity & Migration System
- 게임 실행 시 저장 데이터 존재 여부 및 버전 검증 파이프라인 구축
- 레벨 기준으로 건물, 해금 상태, 진행 데이터를 역추적하는 정합성 검사 로직 구현
- 데이터 불일치 발생 시 최소 정상 상태로 강제 보정하는 자동 복구 시스템 설계
- 저장 포맷 변경에 대응하는 세이브 데이터 마이그레이션 로직 구현

### ⏱ Offline Progression System
- 마지막 접속 시간과 현재 시간을 비교한 ΔTime 기반 오프라인 보상 시스템 구현
- 건물 생산 구조와 연동된 누적 보상 시뮬레이션 로직 설계
- 장시간 미접속 환경에서 데이터 오염 및 불일치를 보정하는 로직 개발

### ⚡ Large Scale NPC & Performance Optimization
- 100명 이상의 NPC 동시 동작 환경을 고려한 시스템 설계
- 상태에 따라 특정 NPC에만 동적 컴포넌트가 부착되는 구조 구현
- Component Pool 시스템 직접 설계 및 구현으로 생성/삭제 비용 감소
- 런타임 GC 감소 및 프레임 안정화

### 🎮 Gameplay Interaction System
- 기존 NPC 전용 놀이기구 탑승 시스템을 플레이어 인터랙션 기능으로 확장
- 플레이어 탑승 상태 전환(State) 로직 설계 및 구현
- 탑승 시 카메라 시점 전환 시스템 구현 (View Mode Switching)
- 탑승/하차 이벤트와 게임 로직을 연동한 상호작용 구조 설계

---

# 🎮 Additional Gameplay Projects (Unity)

> 상세 구현 및 시스템 구조는 각 GitHub Repository에 정리되어 있습니다.

---

## 🤖 Nier: Automata (Team Project)
3D 액션 전투 및 Enemy / Boss AI 구현 프로젝트  

>- 기간: 2023.05 ~ 2023.06  
>- 환경: Unity3D, C#  
>- 역할: Enemy / Boss / 전투 시스템 구현  
>- GitHub: https://github.com/HaloTwo/Nier-Automata  
---

## 🧁 Cuphead (Personal Project)
2D 보스 전투 중심 액션 시스템 구현  

- 기간: 2023.04 ~ 2023.04  
- 환경: Unity2D, C#  
- 역할: 보스 패턴, 전투 시스템, UI 구현  
- GitHub: https://github.com/HaloTwo/Cuphead  
---

## 🐉 Pokemon: Scarlet (Personal Project)
상태 패턴 기반 AI 및 게임 시스템 구현 프로젝트  

- 기간: 2023.06 ~ 2023.07  
- 환경: Unity3D, C#  
- 역할: AI 시스템, 인벤토리, 데이터 구조 설계  
- GitHub: https://github.com/HaloTwo/Pokemon  


