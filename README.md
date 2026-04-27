# OSSCA 1주차 OT

OSSCA LitmusChaos 멘토링 1주차 온보딩 자료입니다. 이번 주차에서는 멘토링 전체 흐름을 소개하고, 앞으로 함께 기여하게 될 LitmusChaos 프로젝트와 카오스 엔지니어링의 기본 개념을 가볍게 살펴봅니다.

## LitmusChaos란?

LitmusChaos는 쿠버네티스 환경에서 카오스 엔지니어링을 설계하고 실행할 수 있도록 돕는 오픈소스 플랫폼입니다. 사용자는 쿠버네티스에 대한 깊은 전문 지식이 없더라도 실험을 정의하고, 장애를 주입하고, 시스템이 정상 상태를 유지하는지 확인할 수 있습니다.

LitmusChaos는 여러 컴포넌트로 구성된 마이크로서비스 프로젝트입니다. React 기반 프론트엔드, Go로 작성된 백엔드 서버, Python과 C로 작성된 카오스 실험, 쿠버네티스 오퍼레이터 등 다양한 언어와 프레임워크가 함께 사용됩니다.

- 공식 웹사이트: <https://litmuschaos.io/>
- 주요 사용 언어: Go, TypeScript, Python, C, Markdown
- 문서 기여를 시작할 때는 Markdown 기반의 작은 수정부터 진행할 수 있습니다.

멘토링 기간 동안 LitmusChaos의 구조와 기여 방법을 차근차근 다룰 예정입니다. 따라서 프로젝트를 미리 깊게 알고 있지 않아도 괜찮습니다.

## 카오스 엔지니어링

현대 애플리케이션은 복잡한 분산 시스템과 마이크로서비스 위에서 동작합니다. 이런 환경에서는 장애가 발생했을 때 어느 영역에서 문제가 생겼는지 파악하기가 쉽지 않습니다.

카오스 엔지니어링은 운영 환경에서도 갑작스러운 장애를 견딜 수 있는 시스템을 만들기 위해, 통제된 방식으로 시스템에 실험을 수행하는 분야입니다. 장애를 주입한 뒤에도 시스템이 정상 상태(steady state)를 유지한다면 해당 시스템은 회복성(resilience)을 갖추고 있다고 볼 수 있습니다.

즉, 카오스 엔지니어링의 목표는 예상치 못한 문제를 사전에 발견하고 시스템의 회복성을 높이는 것입니다.

참고: [카오스 엔지니어링 원칙](https://principlesofchaos.org/ko/)

## 멘토링 운영 계획

### 1주차: 온보딩

- 진행 방식: 온라인
- OT 진행
- GitHub 실습 안내
- Litmus Chaos Korea Mentorship Organization 초대

### 2주차: LitmusChaos 커뮤니티 참여 안내

- 진행 방식: 온라인
- GitHub 교육 영상 시청
- Litmus Slack 가입 안내
- Contributor Call 참여 안내
- Litmus GitHub 저장소 및 기여 흐름 안내

> GitHub 교육 영상은 2주차까지 시청을 완료해 주세요.

### 3주차: Git 복습 및 Go 언어 실습

- 진행 방식: 오프라인
- 일정: 5월 8일 금요일 19:00
- Git 복습
- Issue 등록, 개발, Pull Request 생성 흐름 실습
- Pull Request conflict 상황 경험 및 해결
- Go 기본 문법 강의
- Go 기반 CRUD 실습

### 4주차: Kubernetes 개념 및 실습

- 진행 방식: 오프라인
- 일정: 5월 17일 일요일 14:00
- Kubernetes 핵심 개념 설명
- LitmusChaos에서 자주 만나는 Kubernetes 개념 중심 실습

### 5주차: LitmusChaos 실습

- 진행 방식: 오프라인
- 일정: 5월 24일 일요일 14:00
- LitmusChaos 실습 환경 소개
- Pod 삭제 카오스 실험 진행
- 모니터링 튜토리얼 진행

### 6주차: 이슈 할당 및 향후 기여 계획

- 진행 방식: 오프라인 예정
- 일정: 미정
- 메인테이너 일정에 맞춰 조율 예정
- 기여 가능한 이슈 안내 및 할당
- 멘토링 이후 기여 방향 설명
- 가능하다면 메인테이너 또는 기존 커뮤니티 멤버 초청 예정

## 참여 전 준비 사항

멘토링을 원활하게 진행하기 위해 아래 항목을 미리 준비해 주세요.

- GitHub 계정 생성 및 로그인 확인
- Git 기본 명령어 사용 환경 준비
- GitHub 교육 영상 시청
- Litmus Chaos Korea Mentorship Organization 초대 수락
- 안내에 따라 Litmus Slack 가입


## 1주차 출석 체크 안내

출석 체크는 아래 GitHub Organization 참여 여부를 기준으로 진행할 예정입니다.

<https://github.com/LitmusChaos-Korea-Mentorship>

참가자 25명 모두 해당 Organization에 초대할 예정입니다. 초대를 받으면 반드시 수락해 주세요.
