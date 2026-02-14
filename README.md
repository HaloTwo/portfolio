<!-- =========================
README.md (Portfolio)
Author: <YOUR_NAME>
========================= -->

# 🧩 <YOUR_NAME> | Game Client Programmer (Unreal / Unity)

> **7초 요약**  
> - **엔진:** Unreal Engine 5 (C++/Blueprint), Unity (C#)  
> - **관심/강점:** 게임플레이 시스템, 네트워크/멀티플레이, 성능 최적화  
> - **어필:** “문제 정의 → 원인 분석 → 해결 → 결과” 중심으로 정리했습니다.

**Links**
- 📄 Resume (PDF): <RESUME_LINK>
- 🧱 Portfolio (Notion/Website): <PORTFOLIO_LINK>
- 🧑‍💻 GitHub: <GITHUB_LINK>
- ✉️ Email: <EMAIL>
- 🔗 LinkedIn (선택): <LINKEDIN_LINK>

---

## 🔥 Highlights (한 줄 성과)
- (예) **Dedicated Server** 기반_attach/replication 구조 설계 및 동기화 이슈 해결
- (예) **GAS/Ability** 구조화로 스킬 확장 비용 감소 및 밸런싱 워크플로우 개선
- (예) **프로파일링 기반 최적화**로 특정 구간 FPS 드랍 원인 제거

> 숫자/지표가 있으면 최강. 없으면 “감소/개선/안정화”라도 써.

---

## 🧰 Tech Stack
- **Unreal:** C++, Blueprint, UMG, GAS(선택), Replication/RPC, Dedicated Server(선택), Gameplay Framework
- **Unity:** C#, URP(선택), Addressables(선택), Timeline(선택)
- **Tools:** Visual Studio / Rider, Perforce/Git, Jira/Notion
- **Etc:** Profiling(Stat/Insights), Build/Packaging, CI(선택)

---

## 📌 Projects (대표 프로젝트 먼저)
> 각 프로젝트는 **1) 무엇을 만들었나 2) 내가 뭘 했나 3) 어떤 문제를 어떻게 풀었나**만 빠르게 보이게 구성

| Project | Type | Role | Tech | Links |
|---|---|---:|---|---|
| **Project A (대표)** | Company/Commercial | Client/Gameplay | UE5, C++ | [Summary](./projects/project-a/README.md) · [Video](<VIDEO_LINK>) |
| **Project B** | Personal/Team | Network/Server | UE5, Dedicated | [Summary](./projects/project-b/README.md) · [Code](<REPO_LINK>) |
| **Project C** | Personal | Systems/Tools | Unity, C# | [Summary](./projects/project-c/README.md) |

> 회사 프로젝트는 코드 공개가 불가하면 **Summary 문서 + 영상 + 내가 한 일**로 승부.

---

## 🧠 Problem Solving (문제 해결 사례)
> “답” 말고 **풀이 과정**. 면접관이 제일 좋아함.

### Case 1) (예) Replication 지연으로 위치 튐 발생
- **Problem:** 네트워크 지연 상황에서 캐릭터 위치가 순간이동처럼 보임
- **Analysis:** (예) 서버 권위 이동 + 클라 예측/보정 로직 부재, 특정 RPC 타이밍 충돌
- **Solution:** (예) Client-side prediction 도입 + 보정 스무딩, RPC 빈도 조절
- **Result:** (예) 지연 150ms 환경에서 체감 튐 감소 / 동기화 안정화

### Case 2) (예) 특정 구간 FPS 급락
- **Problem:** 전투 중 특정 연출에서 프레임 급락
- **Analysis:** Unreal Insights로 스파이크 구간 분석 → (예) Tick 과다 / UMG 갱신 폭증
- **Solution:** (예) Tick 제거, 이벤트 기반 갱신, 오브젝트 풀링
- **Result:** (예) 최악 프레임 구간 안정화 (수치 있으면 기입)

---

## 🧾 Experience (경력 요약)
### <Company Name> | <Role> (YYYY.MM ~ YYYY.MM)
- 상용 프로젝트 <프로젝트명> 참여 (담당: <담당 영역>)
- (예) 전투 시스템/스킬/애니메이션 연동/네트워크 동기화 등
- 협업: 기획/아트/QA 커뮤니케이션 및 일정 단위 기능 인수인계

> 상세 경력은 Resume(PDF)로 보내고, README에는 **핵심만**.

---

## 📂 Repository Structure (권장)
