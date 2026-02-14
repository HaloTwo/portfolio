# 🎮 이수민 | Game Programmer 

> 상용 게임 클라이언트 및 코어 로직 개발 경험을 기반으로  
> 액션 게임의 전투 시스템, AI, 게임플레이 구조 구현에 집중하는 프로그래머입니다.

📧 Email: lsm6265@naver.com  

# 👋 About Me

상용 모바일 게임 클라이언트 및 코어 로직 개발 경험을 가진 프로그래머입니다.  
Unity 실무 경험을 바탕으로 현재는 Unreal Engine 5 기반 액션 전투 시스템과 게임플레이 구조 설계에 집중하고 있습니다.

팀 협업을 중요하게 생각하며, 문제를 구조적으로 분석하고 시스템 단위로 해결하는 개발 방식을 지향합니다.

---

# 🧠 Main Project (Unreal Engine 5)

## ⚔️ UE5 Action RPG (Lies of P Inspired)
Gameplay Ability System(GAS) 기반 싱글플레이 액션 전투 시스템 프로젝트

- Engine: Unreal Engine 5 (C++ / Blueprint)
- Focus: Combat System / AI / Gameplay Architecture
- 💻 GitHub: [Repository](https://github.com/HaloTwo/LOP)

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

ALBUS | Client Programmer (2023.09 ~ 2025.02)  
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
- 건물 상태 기반 기능 로직 구조 설계 (Delegate 기반 이벤트 구조)

### 💾 Offline Progression System
- 마지막 접속 시간과 현재 시간을 비교한 경과 시간(ΔTime) 기반 오프라인 보상 시스템 구현
- 건물 생산 구조와 연동된 누적 보상 시뮬레이션 로직 설계
- 장시간 미접속 환경에서도 데이터 정합성을 유지하는 보정 로직 개발

### 🧩 Save Data Integrity & Migration
- 저장 데이터 존재 여부 및 버전 검증 파이프라인 구축
- 레벨 기준으로 건물/해금 상태 의존 관계를 역추적하는 정합성 검사 시스템 구현
- 데이터 불일치 발생 시 최소 정상 상태로 자동 보정하는 강제 복구 로직 설계
- 저장 포맷 변경에 대응하는 세이브 데이터 마이그레이션 시스템 구현

### ⚡ Large Scale NPC Optimization
- 100명 이상의 NPC 동시 동작 환경을 고려한 시스템 설계
- 상태에 따라 특정 NPC에만 동적 컴포넌트가 부착되는 구조 구현
- Component Pool 시스템 직접 설계 및 구현으로 생성/삭제 비용 감소
- 런타임 GC 발생 감소 및 성능 안정화

### 🛠 Tools & Data Pipeline
- Google Sheet API 기반 데이터 연동 시스템 구축
- 비동기 데이터 처리 로직 구현
- Unity Custom Editor 툴 제작으로 개발 효율 개선
- Firebase 및 외부 SDK 연동 경험

---

# 🎮 Additional Gameplay Projects (Unity)

> 액션 및 게임플레이 시스템 중심 개인 프로젝트

- Nier: Automata (Enemy / Boss / Combat 구현)  
  💻 [GitHub](https://github.com/HaloTwo/Nier-Automata)

- Cuphead (2D 보스 전투 및 액션 시스템)  
  💻 [GitHub](https://github.com/HaloTwo/Cuphead)

- Pokemon: Scarlet (AI 상태 패턴 및 시스템 구현)  
  💻 [GitHub](https://github.com/HaloTwo/Pokemon)
