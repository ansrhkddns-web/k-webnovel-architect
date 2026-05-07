# K-Webnovel Architect

**한국 웹소설을 상업 연재 가능한 작품 바이블로 설계하고 점검하는 Codex Skill**

`k-webnovel-architect`는 한국 웹소설 기획을 위한 Codex 스킬입니다.  
아이디어 한 줄에서 시작해 장르 문법, 핵심 독자층, 제목, 소개글, 주인공 욕망, 성장 루프, 인물 기능, 회차 로드맵, 회차 집필 지시서, 장기 떡밥, 유료화 지점, 플랫폼 패키징, 품질 평가, IP 확장성까지 한 번에 설계하고 진단하도록 만들어졌습니다.

이 스킬은 단순한 글쓰기 조언용이 아니라, **상업 연재형 장르물 기획서와 작품 바이블을 만들기 위한 작업 도구**입니다.

---

## 이 스킬이 하는 일

이 스킬은 다음 작업에 사용합니다.

- 한국 웹소설 신작 기획
- 장르 문법 점검
- 콘셉트 상업성 검증
- 독자 페르소나와 구매 욕망 분석
- 상업성 진단
- 제목 후보와 소개글 설계
- 핵심 독자층과 독자 보상 정리
- 주인공 욕망, 결핍, 특수 우위 설계
- 성장물의 보상 루프 설계
- 인물 기능표 작성
- 1화 훅과 초반 무료분 설계
- 회차 집필 지시서 생성
- 유료화 후보 지점 설계
- 장기 떡밥과 회수표 작성
- 플랫폼별 리서치 체크리스트 작성
- 기존 원고/설정집/작품 바이블 진단
- 원고/기획 리뷰와 수정 처방
- 장기 시리즈 확장 구조 설계
- 제작 파이프라인 설계
- 스킬 출력 품질 테스트
- 웹툰, 영상, 오디오, 게임 등 IP 확장성 점검

---

## 왜 만들었나

한국 웹소설은 장르 문법이 강합니다.  
독자는 제목과 소개글, 1화 초반만 보고도 자신이 받을 재미를 빠르게 판단합니다.

그래서 웹소설 기획은 단순히 “멋진 설정”을 만드는 것으로는 부족합니다.

좋은 상업 기획에는 다음 질문에 대한 답이 있어야 합니다.

- 이 작품은 어떤 장르인가?
- 독자는 어떤 보상을 기대하고 들어오는가?
- 1화에서 바로 클릭을 유지할 이유가 있는가?
- 5화 안에 반복 재미가 증명되는가?
- 무료분 끝에서 결제할 만큼 신뢰를 줬는가?
- 50화, 100화 이상 끌고 갈 이야기 엔진이 있는가?
- 장기 떡밥이 보상 없이 쌓이기만 하지는 않는가?
- 제목, 소개글, 본문, 유료화 지점의 약속이 서로 맞는가?

`k-webnovel-architect`는 이런 질문들을 체계적으로 다루기 위해 만들어졌습니다.

---

## 핵심 철학

### 1. 장르 문법은 독자와의 계약이다

이 스킬은 장르 문법을 “뻔한 공식”으로 보지 않습니다.  
장르 문법은 독자가 이 작품을 클릭한 이유이며, 작가는 그 기대를 먼저 충족해야 합니다.

차별화는 장르 약속을 깨는 방식이 아니라, **익숙한 재미를 준 뒤 더 기억에 남게 만드는 방식**으로 설계합니다.

### 2. 설정보다 반복 보상이 중요하다

웹소설 독자는 세계관 설정만 보려고 계속 읽지 않습니다.  
매화 혹은 짧은 간격으로 성장, 승리, 관계 변화, 정보, 지위 상승, 돈, 사이다, 긴장 같은 보상을 받아야 합니다.

### 3. 숫자와 설정은 체감되어야 한다

스탯, 랭크, 돈, 호감도, 명성, 단서 같은 변화는 표로만 존재하면 약합니다.  
독자가 장면 안에서 “이전과 달라졌다”고 느껴야 보상으로 작동합니다.

### 4. 참고작 데이터는 베끼지 않는다

이 스킬은 레퍼런스를 분석할 수 있지만, 특정 작품의 고유명사, 사건, 문장, 설정값을 복사하지 않습니다.  
레퍼런스에서 추출하는 것은 오직 **작업 방식, 장르 구조, 보상 패턴, 이탈 위험, 상업적 판단 기준**입니다.

---

## 설치 방법

Codex가 로컬 스킬을 읽을 수 있는 위치에 이 저장소를 복제합니다.

### Windows PowerShell

```powershell
git clone https://github.com/ansrhkddns-web/k-webnovel-architect.git "$env:USERPROFILE\.codex\skills\k-webnovel-architect"
```

### macOS / Linux

```bash
git clone https://github.com/ansrhkddns-web/k-webnovel-architect.git ~/.codex/skills/k-webnovel-architect
```

설치 후 Codex를 새로 열거나 새 대화를 시작하면 스킬 목록에서 사용할 수 있습니다.

---

## Quick Start

처음 쓰는 경우에는 아래 순서로 요청하면 됩니다.

1. 먼저 장르와 독자층을 잡습니다.

```text
$k-webnovel-architect 로 현대판타지 신작을 기획해줘.
장르 문법, 핵심 독자층, 한 줄 콘셉트, 제목 후보부터 잡아줘.
```

2. 콘셉트가 팔릴 구조인지 점검합니다.

```text
$k-webnovel-architect 로 이 콘셉트의 상업성을 진단해줘.
클릭성, 반복 보상, 5화 유지력, 유료화 신뢰를 점수화해줘.
```

3. 1화부터 유료화 지점까지 회차 구조를 만듭니다.

```text
$k-webnovel-architect 로 1~25화 로드맵을 만들어줘.
각 화의 기능, 보상, 엔딩 훅, 이탈 위험을 표로 정리해줘.
```

4. 실제 원고 작성 전 회차 브리프를 뽑습니다.

```text
$k-webnovel-architect 로 3화 회차 브리프를 만들어줘.
장면 순서, 반드시 넣을 보상, 피해야 할 설명, 엔딩 훅을 정리해줘.
```

---

## 사용 예시

Codex에게 아래처럼 요청하면 됩니다.

```text
$k-webnovel-architect 로 헌터물 신작 기획을 만들어줘.
상업성 있게 제목, 한 줄 콘셉트, 주인공 욕망, 1~25화 로드맵까지 잡아줘.
```

```text
$k-webnovel-architect 로 이 로판 기획을 진단해줘.
장르 문법, 독자 보상, 1화 훅, 유료화 지점이 약한지 봐줘.
```

```text
$k-webnovel-architect 로 기존 설정집과 1~15화 원고를 분석해줘.
회차별 기능, 보상, 엔딩 훅, 이탈 위험을 표로 정리해줘.
```

```text
$k-webnovel-architect 로 상업성 진단을 해줘.
장르 명료도, 클릭성, 반복 보상, 유료화 신뢰, IP 확장성을 점수화해줘.
```

```text
$k-webnovel-architect 로 1화 훅을 고쳐줘.
첫 화면 압박, 장르 신호, 엔딩 훅을 더 강하게 만들어줘.
```

```text
$k-webnovel-architect 로 스킬 출력 품질을 평가해줘.
요청 적합성, 장르 명료도, 상업성 판단, 수정 처방이 충분한지 봐줘.
```

---

## 지원하는 주요 장르

이 스킬은 특정 한 장르만을 위한 도구가 아닙니다.  
한국 웹소설에서 자주 쓰이는 장르 슬롯과 트로프를 폭넓게 다루도록 설계되어 있습니다.

### 성장형 / 남성향 중심

- 헌터
- 게이트
- 탑
- 던전 독점
- 현대판타지
- 게임판타지
- 회귀
- 귀환자
- 빙의
- 망나니
- 먼치킨
- 아카데미
- 무협
- 선협
- 아포칼립스
- 영지물
- 국가건설물

### 관계형 / 여성향 중심

- 로맨스판타지
- 악녀물
- 계약결혼
- 후회물
- 파혼/이혼물
- 궁정물
- 현대로맨스
- 오피스 로맨스
- 캠퍼스 로맨스
- 비엘
- 지엘
- 가이드버스
- 오메가버스

### 전문직 / 무대형

- 의학물
- 법정물
- 수사물
- 재벌/기업물
- 사업/경영물
- 요리물
- 농사/귀농물
- 스포츠물
- 이스포츠
- 인터넷 방송
- 아이돌
- 배우/연예계

### 긴장형 / 확장 세계

- 공포
- 괴담
- 미스터리
- 추리
- 스릴러
- 데스게임
- 루프물
- 재난 생존
- SF
- 사이버펑크
- 가상현실
- 대체역사
- 전쟁/군사물

---

## 주요 기능

### 1. 상업성 진단

작품의 상업적 기본기를 점검합니다.

진단 항목:

- 장르 명료도
- 클릭성
- 반복 보상
- 초반 유지력
- 유료화 신뢰
- 장기 확장성
- IP 확장성

관련 문서:

- `references/commercial-market-fit.md`
- `references/reader-retention-diagnostics.md`
- `references/quality-gates-and-stress-tests.md`

---

### 2. 장르 문법 설계

작품이 어떤 장르 약속을 갖는지 정리합니다.

예를 들어 헌터물이라면 독자는 보통 다음을 기대합니다.

- 측정 가능한 힘
- 던전/게이트/몬스터
- 랭크나 스킬 같은 성장 지표
- 사회적 지위 상승
- 공개 인정 또는 숨은 강자 쾌감

이 스킬은 장르별로 어떤 보상이 필요한지, 어떤 지점에서 독자가 이탈하는지 함께 점검합니다.

관련 문서:

- `references/genre-grammar.md`
- `references/genre-reference-matrix.md`
- `references/genre-deep-dive-cards.md`
- `references/genre-specialized-deep-dives.md`

---

### 3. 트로프 조합

트로프를 단순히 나열하지 않고 상업적 콘셉트 공식으로 조합합니다.

기본 공식:

```text
출발 처지
+ 특수 우위
+ 반복 사건 엔진
+ 보상 사다리
+ 차별화 twist
= 한 줄 콘셉트
```

예를 들어 다음 요소들을 따로 봅니다.

- 최약체, 폐급, 망나니, 엑스트라, 회귀 전 실패자
- 미래 지식, 상태창, 숨은 스킬, 독점 자원, 전문 지식
- 던전, 시험, 의뢰, 사교전, 무대, 경기, 사건 수사
- 힘, 돈, 지위, 관계, 명성, 단서, 영토, 자유

관련 문서:

- `references/trope-combination-library.md`
- `references/concept-title.md`

---

### 4. 성장 루프 설계

성장물에서 가장 중요한 것은 보상이 반복 가능해야 한다는 점입니다.

이 스킬은 아래 루프를 기준으로 성장 구조를 만듭니다.

```text
압박 또는 문제
-> 주인공의 선택
-> 행동과 실패/대가
-> 보상 또는 기록
-> 체감 변화
-> 주변 반응
-> 다음 욕망 또는 다음 위험
```

관련 문서:

- `references/growth-loop-model.md`

---

### 5. 인물 기능 설계

인물을 성격표로만 만들지 않고, 회차에서 맡는 기능으로 설계합니다.

예를 들어:

- 주인공을 움직이게 하는 인물
- 주인공의 약점을 찌르는 적대자
- 주인공 변화를 목격하는 외부 관찰자
- 정보는 주지만 비용도 만드는 조력자
- 주인공과 닮았지만 다른 선택을 하는 라이벌
- 관계와 사건을 동시에 움직이는 감정축

관련 문서:

- `references/character-function-model.md`

---

### 6. 회차 로드맵과 1화 훅

회차표를 단순 줄거리 요약이 아니라, 각 화의 기능으로 설계합니다.

회차 카드에는 다음이 들어갑니다.

- 회차 기능
- 시작 압박
- 주인공 목표
- 장애물
- 선택/행동
- 보상/변화
- 체감 증거
- 주변 반응
- 심거나 회수한 떡밥
- 이탈 위험
- 엔딩 훅

관련 문서:

- `references/episode-roadmap.md`
- `references/opening-hook-library.md`
- `references/episode-brief-generator.md`
- `references/chapter-production-brief.md`

---

### 7. 무료분과 유료화 설계

유료화는 단순히 이야기를 끊는 위치가 아닙니다.  
독자가 이미 받은 보상을 믿고 다음 보상에 돈을 내는 위치입니다.

좋은 유료화 후보:

- 첫 주요 사이다 직후
- 첫 공개 인정 직후
- 첫 관계 전환 직후
- 첫 큰 공략 성공 직후
- 첫 비밀 노출 직후
- 첫 세계 확장 직후

관련 문서:

- `references/paid-conversion-model.md`
- `references/serialization-strategy.md`
- `references/platform-packaging-model.md`
- `references/platform-research-checklists.md`

---

### 8. 레퍼런스 리서치

상위권 작품군, 플랫폼 장르 페이지, 리뷰, 공모전 수상작, 산업 보고서 등을 볼 때 무엇을 추출해야 하는지 정리합니다.

추출 대상:

- 제목 신호
- 소개글 약속
- 1화 훅 유형
- 5화 내 보상
- 무료분 끝 약속
- 유료화 훅
- 반복 보상 사다리
- 독자 이탈 신호
- IP 확장 신호

중요한 점:  
레퍼런스는 베끼는 것이 아니라 구조만 일반화합니다.

관련 문서:

- `references/reference-research-protocol.md`

---

### 9. IP 확장성 점검

웹툰, 드라마, 애니메이션, 오디오, 게임 등으로 확장될 수 있는 신호를 점검합니다.

확장성 요소:

- 시각성
- 캐릭터 실루엣
- 관계성
- 장면 반복성
- 세계 확장성
- 팬덤 언어

관련 문서:

- `references/ip-adaptation-model.md`

---

### 10. 콘셉트 검증

아이디어가 상업 연재형 작품으로 버틸 수 있는지 검증합니다.

검증 항목:

- 장르가 선명한가
- 핵심 독자가 분명한가
- 주인공 처지가 클릭을 만드는가
- 특수 우위가 반복 보상을 만들 수 있는가
- 5화 안에 재미를 증명할 수 있는가
- 50화 이상 확장 가능한가

관련 문서:

- `references/premise-validation-lab.md`
- `references/reader-persona-demand-map.md`

---

### 11. 수정 처방과 제작 파이프라인

진단 결과를 실제 작업 지시로 바꿉니다.

예를 들어:

- 1화에서 어떤 설명을 삭제할지
- 어떤 장르 신호를 앞당길지
- 어떤 인물 기능을 합치거나 바꿀지
- 회차표의 어느 화에 보상과 훅을 추가할지
- 제목과 소개글을 어떤 방향으로 고칠지

관련 문서:

- `references/revision-playbooks.md`
- `references/production-pipeline.md`
- `references/review-rubric.md`

---

### 12. 평가 프롬프트와 품질 루브릭

스킬이 “그럴듯한 말”만 하는지, 실제 상업 연재 설계 도구로 작동하는지 점검합니다.

평가 항목:

- 요청에 맞는 산출물을 냈는가
- 장르와 독자층을 선명하게 잡았는가
- 제목, 소개글, 1화, 유료화 지점의 약속이 이어지는가
- 회차 기능과 반복 보상이 구체적인가
- 이탈 위험을 충분히 찾았는가
- 약점 지적이 실제 수정 지시로 바뀌었는가
- 참고한 레퍼런스의 고유 데이터를 복사하지 않았는가

관련 문서:

- `references/evaluation-prompts.md`
- `references/output-quality-rubric.md`

---

### 13. 회차 집필 지시서

회차 로드맵을 실제 원고 작성 전 단계로 바꿉니다.  
줄거리 요약이 아니라, 그 화가 독자에게 어떤 기능을 해야 하는지 정리합니다.

브리프에 포함되는 내용:

- 회차 기능
- 시작 압박
- 주인공 목표
- 장면 순서
- 반드시 넣을 독자 보상
- 체감 증거와 주변 반응
- 심거나 회수할 떡밥
- 피해야 할 이탈 요소
- 엔딩 훅
- 다음 화 인계

관련 문서:

- `references/episode-brief-generator.md`
- `references/chapter-production-brief.md`

---

## 파일 구조

```text
k-webnovel-architect/
├── SKILL.md
├── LICENSE
├── agents/
│   └── openai.yaml
└── references/
    ├── blurb-and-metadata-generator.md
    ├── chapter-production-brief.md
    ├── character-function-model.md
    ├── commercial-market-fit.md
    ├── concept-title.md
    ├── continuity-workflow.md
    ├── data-model.md
    ├── draft-bible-analysis.md
    ├── episode-brief-generator.md
    ├── episode-roadmap.md
    ├── evaluation-prompts.md
    ├── foreshadowing-system.md
    ├── genre-deep-dive-cards.md
    ├── genre-grammar.md
    ├── genre-reference-matrix.md
    ├── genre-specialized-deep-dives.md
    ├── growth-loop-model.md
    ├── ip-adaptation-model.md
    ├── opening-hook-library.md
    ├── output-quality-rubric.md
    ├── paid-conversion-model.md
    ├── planning-template.md
    ├── platform-packaging-model.md
    ├── platform-research-checklists.md
    ├── premise-validation-lab.md
    ├── production-pipeline.md
    ├── project-bible-workflow.md
    ├── quality-gates-and-stress-tests.md
    ├── reader-persona-demand-map.md
    ├── reader-retention-diagnostics.md
    ├── reference-research-protocol.md
    ├── review-rubric.md
    ├── revision-playbooks.md
    ├── serialization-strategy.md
    ├── series-architecture-and-escalation.md
    └── trope-combination-library.md
```

---

## 참조 문서 요약

| 문서 | 역할 |
|---|---|
| `data-model.md` | 스킬 내부에서 쓰는 기획 데이터 모델 |
| `reader-persona-demand-map.md` | 독자 페르소나와 구매 욕망 지도 |
| `premise-validation-lab.md` | 콘셉트 상업성 검증 |
| `commercial-market-fit.md` | 상업성, 클릭성, 유료화 신뢰 진단 |
| `genre-grammar.md` | 기본 장르 문법과 장르 혼합 원칙 |
| `genre-reference-matrix.md` | 다양한 장르 슬롯과 핵심 보상 지도 |
| `genre-deep-dive-cards.md` | 장르별 1화, 5화, 반복 보상, 유료화 훅 |
| `genre-specialized-deep-dives.md` | 세부 장르와 변형 장르의 구매 이유, 유료화 훅, 이탈 위험 |
| `trope-combination-library.md` | 트로프 조합 공식 |
| `concept-title.md` | 제목, 한 줄 콘셉트, 소개글 설계 |
| `growth-loop-model.md` | 성장/보상 루프 설계 |
| `character-function-model.md` | 인물 기능 설계 |
| `episode-roadmap.md` | 회차표와 아크 카드 |
| `episode-brief-generator.md` | 회차별 집필 지시서 생성 기준 |
| `chapter-production-brief.md` | 장면 순서와 원고 제작 브리프 기준 |
| `opening-hook-library.md` | 1화 훅과 엔딩 훅 설계 |
| `paid-conversion-model.md` | 유료화 지점 설계 |
| `series-architecture-and-escalation.md` | 장기 시리즈 확장 구조 |
| `reader-retention-diagnostics.md` | 독자 이탈 위험 진단 |
| `serialization-strategy.md` | 연재 전략과 무료분/유료분 구조 |
| `platform-packaging-model.md` | 플랫폼 성격별 패키징 |
| `foreshadowing-system.md` | 장기 떡밥 설계 |
| `continuity-workflow.md` | 설정 충돌과 변경 로그 관리 |
| `project-bible-workflow.md` | 작품 바이블 폴더/문서 구조 |
| `draft-bible-analysis.md` | 기존 원고와 설정집 분석법 |
| `reference-research-protocol.md` | 외부 레퍼런스 분석 프로토콜 |
| `platform-research-checklists.md` | 플랫폼별 리서치 체크리스트 |
| `ip-adaptation-model.md` | IP 확장성 점검 |
| `quality-gates-and-stress-tests.md` | 10초/5화/25화/50화 테스트 |
| `evaluation-prompts.md` | 스킬 평가용 대표 요청 프롬프트 |
| `output-quality-rubric.md` | 스킬 산출물 품질 점수표 |
| `review-rubric.md` | 원고/기획 리뷰 점수표 |
| `revision-playbooks.md` | 문제별 수정 처방 |
| `production-pipeline.md` | 기획부터 연재 운영까지 제작 파이프라인 |
| `blurb-and-metadata-generator.md` | 제목, 소개글, 태그 생성 기준 |
| `planning-template.md` | 사용자 출력용 기획서 템플릿 |

---

## 출력 예시

이 스킬을 사용하면 다음과 같은 결과물을 만들 수 있습니다.

### 빠른 콘셉트

```markdown
## 작품 기획 초안

### 장르와 독자층
- 주 장르:
- 보조 장르:
- 핵심 독자층:
- 독자가 기대하는 재미:

### 한 줄 콘셉트
1.
2.
3.

### 제목 후보
-
-
-

### 첫 5화 목표
-
```

### 상업성 진단

```markdown
## 상업성 진단

| 항목 | 점수 | 이유 | 보완 |
|---|---:|---|---|
| 장르 명료도 |  |  |  |
| 클릭성 |  |  |  |
| 반복 보상 |  |  |  |
| 초반 유지력 |  |  |  |
| 유료화 신뢰 |  |  |  |
| 장기 확장성 |  |  |  |
```

### 회차 로드맵

```markdown
| 화 | 회차 기능 | 핵심 사건 | 보상/변화 | 엔딩 훅 | 이탈 위험 |
|---|---|---|---|---|---|
| 1 |  |  |  |  |  |
| 2 |  |  |  |  |  |
```

### 회차 브리프

```markdown
## 3화 회차 브리프

### 회차 기능
- 반복 보상을 두 번째로 증명하고, 더 큰 무대의 입구를 보여준다.

### 장면 순서
| 순서 | 장면 기능 | 핵심 사건 | 보상/변화 | 주의 |
|---|---|---|---|---|
| 1 | 시작 압박 |  |  |  |
| 2 | 주인공 선택 |  |  |  |
| 3 | 보상 체감 |  |  |  |

### 엔딩 훅
- 다음 화에서 확인할 구체적 위험 또는 보상:
```

### 스킬 품질 평가

```markdown
| 항목 | 점수 | 근거 | 보완 |
|---|---:|---|---|
| 요청 적합성 |  |  |  |
| 장르 명료도 |  |  |  |
| 상업성 판단 |  |  |  |
| 회차 기능성 |  |  |  |
| 고유 데이터 보호 |  |  |  |
```

---

## 검증

이 저장소는 Codex Skill 형식 검증을 통과했습니다.

```text
Skill is valid!
```

---

## 주의 사항

- 이 스킬은 특정 작품의 설정이나 문장을 복사하기 위한 도구가 아닙니다.
- 시장 랭킹, 플랫폼 정책, 공모전 조건은 변할 수 있으므로 최신 판단이 필요하면 별도 확인이 필요합니다.
- 레퍼런스 분석 결과는 고유 데이터를 제거하고 구조만 일반화해야 합니다.
- 장르 문법은 절대 법칙이 아니지만, 독자 기대를 배신할 때는 반드시 보상책이 필요합니다.

---

## 이 스킬이 하지 않는 것

- 실제 작품의 문장, 회차 사건, 고유 설정을 그대로 복제하지 않습니다.
- 현재 실시간 랭킹이나 최신 플랫폼 정책을 확인하지 않고 사실처럼 단정하지 않습니다.
- 저작권이 있는 원문을 길게 재현하거나 요약을 넘어선 대체물을 만들지 않습니다.
- 상업적 성공을 보장하지 않습니다.
- 모든 작품을 하나의 공식에 억지로 끼워 맞추지 않습니다.

---

## 라이선스

이 저장소는 MIT License로 배포됩니다. 자세한 내용은 `LICENSE` 파일을 확인하면 됩니다.

---

## 기여 방향

이 스킬을 더 발전시키고 싶다면 아래 방향의 기여가 좋습니다.

- 장르별 심화 카드 추가
- 세부 장르 심화 카드 추가
- 플랫폼별 패키징 체크리스트 보강
- 플랫폼별 리서치 체크리스트 보강
- 유료화 지점 사례의 일반화
- 독자 이탈 유형 세분화
- 평가 프롬프트와 품질 루브릭 보강
- 회차 브리프와 원고 제작 브리프 개선
- IP 확장성 체크리스트 보강
- 기존 원고/설정집 분석 템플릿 개선

기여할 때도 특정 작품의 고유 설정, 문장, 회차 사건을 그대로 넣지 말고, 일반화된 판단 기준으로 정리하는 것을 권장합니다.
