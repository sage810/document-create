# middle school info curriculum — 정보과 교육과정 지식 베이스 목록

중학교 정보 수업 계획·평가 계획·활동지 목표를 **교육과정 고시 문장**에 맞출 때 참고하는 자료 모음이다.
요청을 받으면 이 목록에서 자료를 고르고, 그 자료의 `SKILL.md`(색인)부터 읽는다.
교과서·지도서의 활동과 발문은 이웃 폴더 [middle school info book read](<../middle school info book read/INDEX.md>)에 있다.

## 자료 목록

| 폴더 | 자료 | 범위 | 색인 |
|---|---|---|---|
| [info-curriculum](info-curriculum/SKILL.md) | 2022 개정 정보과 교육과정 (교육부 고시 제2022-33호 [별책 10], PDF 75쪽) | p.1~23: 공통 교육과정 「정보」(설계의 개요, 성격 및 목표, 영역 5개 내용 체계·성취기준 25개·해설·고려 사항, 교수·학습 및 평가), 선택 중심 교육과정 설계의 개요 | [SKILL.md](info-curriculum/SKILL.md) |

## 자료마다 들어 있는 파일

- `SKILL.md` — 핵심 틀, **성취기준 원문 25개**, 장 색인, 용어 색인
- `cheatsheet.md` — 성취기준 한 장 표, 판단 규칙, 역량→평가 항목, 어긋남 점검, 고시 표기
- `patterns.md` — 교육과정 문장을 수업·평가 설계로 바꾸는 기법
- `glossary.md` — 용어 정의
- `chapters/` — 설계 개요(ch00), 성격 및 목표(ch01), 영역별 파일(ch02~ch06), 교수·학습 및 평가(ch07), 선택 중심 개요(ch08)

## 자료 추가 규칙

- 새 자료는 `middle school info curriculum/<자료-이름>/` 하위 폴더로 만들고 위 표에 한 줄 추가한다.
- 같은 PDF의 p.24 이후(고등학교 선택 과목)를 더할 때는 info-curriculum에 장을 이어 붙인다(ch09~).
- 원문 PDF는 넣지 않는다(`.gitignore`가 `*.pdf`를 제외한다).
