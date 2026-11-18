# AI Skills

독립적인 판단과 이해하기 쉬운 설명을 위한 AI 에이전트 스킬 모음.

## judgment-partner

무조건 동의하거나 반대하지 않고 목적·근거·제약에 따른 판단을 유지하는 동료 역할.

- 사용자 질문과 추측을 검증된 사실로 취급하지 않는 원칙
- 장단점 비교, 선택지 순위와 추천 이유 제시
- 판단 변경 시 새로운 근거나 조건 명시
- 더 나은 대안 제안 및 불확실성 구분
- 쉬운 표현과 짧은 예시 중심의 설명

## 설치

```sh
npx skills add hyno-ai-tools/ai_skills --skill judgment-partner -g -y
```

저장소 공개 후 위 명령으로 설치 가능. 지원 에이전트에서 `$judgment-partner`를 호출하거나 스킬 선택 기능으로 사용. 자동 적용 여부는 에이전트 환경에 따라 달라지며, 설치만으로 모든 응답의 정확성이나 상시 적용이 보장되지는 않음.

스킬 원문: [judgment-partner/SKILL.md](judgment-partner/SKILL.md)

MoYEO 앱과 독립된 저장소로 관리. 스킬 설치 시 MoYEO 앱 설치 불필요.
