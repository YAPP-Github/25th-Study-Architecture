# 📘 단방향 데이터 플로우 (Unidirectional Data Flow) 스터디

**Unidirectional Data Flow (UDF)** 스터디는 iOS 개발자들이 단방향 데이터 플로우 아키텍처를 깊이 이해하고, 실무에서 활용할 수 있도록 돕기 위해 기획된 스터디입니다.  
TCA와 ReactorKit 같은 UDF 구현 라이브러리를 중심으로 실습과 논의를 통해 학습합니다.

---

## 🎯 스터디 목표

1. 단방향 데이터 플로우 아키텍처의 이해
2. TCA와 ReactorKit의 유즈케이스 팁 공유
3. UDF 환경에서 테스트 코드 작성
4. 작성한 UDF 코드 리뷰 및 개선

---

## 📜 스터디 규칙

- **사전 학습과 실습 필수**: 스터디 전까지 주어진 학습 자료와 실습을 완료해야 합니다.
- **무단 불참 시 발표**: 무단으로 스터디에 불참한 경우, 차주 학습 발표가 확정됩니다.
- **피드백 적극 반영**: 사전 및 회고 피드백을 통해 지속적으로 스터디 내용을 개선합니다.

---

## 📅 스터디 커리큘럼

### 1주차: 단방향 데이터 플로우 이해
- **개념 학습**:
  - 단방향 데이터 플로우의 필요성과 장점
  - MVC, MVVM 등 기존 패턴과의 차이점
  - iOS 및 다른 플랫폼에서의 UDF 활용 사례
- **실습**:
  - 간단한 액션 → 상태 업데이트 → UI 반영 플로우 구현
  - MVI(Model-View-Intent) 형태로 직접 구현
- **논의**:
  - UDF의 필요성과 한계, 기존 패턴의 단점
  - 테스트 및 유지보수성 측면에서의 장점

### 2주차: ReactorKit & TCA 설계 철학
- **개념 학습**:
  - ReactorKit: Reactor, Action, Mutation, State의 역할
  - TCA: State, Action, Reducer, Store의 역할
  - 두 프레임워크의 설계 배경과 철학
- **실습**:
  - ReactorKit 또는 TCA를 사용한 간단한 메모 앱 구현
  - 테스트 환경 활용
- **논의**:
  - ReactorKit과 TCA의 설계 차이 및 장단점
  - 복잡한 상태 관리 프로젝트에서의 활용성

### 3주차: UDF의 복잡한 사례 적용
- **개념 학습**:
  - 복잡한 UI 상태 관리 및 비동기 작업 처리
  - 여러 화면 간 상태 공유와 에러 핸들링
- **실습**:
  - 복잡한 상황을 ReactorKit/TCA로 구현
  - 구현 후 한계점 및 개선 방안 논의
- **논의**:
  - 비동기 작업 처리, 코드 가독성, 유지보수성 비교
  - 프로젝트 상황에 따른 적합성 분석

### Extra week
- **공유 및 회고**:
  - 실제 프로젝트에 적용한 사례 공유
  - 트러블 슈팅 공유 및 유즈케이스 토론