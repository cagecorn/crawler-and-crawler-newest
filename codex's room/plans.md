# 개발 계획 및 지침

이 문서는 Codex가 차후 세션에서 참고할 기본 지침과 로드맵을 기록합니다.

## 기본 원칙
1. 저장소 내 문서를 우선적으로 확인하여 기존 구조나 규칙을 존중합니다.
2. 새로운 기능을 구현할 때는 가능한 한 테스트 파일도 함께 갱신합니다.
3. 의존성 설치가 필요하면 `package.json`을 수정하고 적절한 스크립트를 추가합니다.
4. 커밋 메시지는 간결하게 작성하되 변경된 내용을 명확히 설명합니다.
5. 오컴의 면도날 원칙을 적용합니다. "이 로직이 정말 필요한가? 이미 달성된 동작을 반복하진 않는가? 더 간단하게 구현할 방법은 없는가?"를 항상 자문하여 무용하거나 과도한 처리를 줄입니다.

## 앞으로의 작업 아이디어
- `src/ai.js`의 AI 유형을 세분화하여 몬스터와 용병의 개성을 강화 (일부 진행)
- 던전 생성 규칙을 확장하여 다양한 지형 요소를 추가 (용암 지형 구현 완료)
- 전투 로그를 콘솔뿐 아니라 파일로도 남길 수 있는 기능 시도 (완료)

필요한 작업이 생각나면 이 파일에 계속 추가하십시오.
