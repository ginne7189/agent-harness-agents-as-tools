# Manager·Agents as Tools Workflow

```text
사용자 ↔ Manager
           ├→ 재무 Agent → 결과 반환
           ├→ 보안 Agent → 결과 반환
           └→ 계약 Agent → 결과 반환
        Manager가 통합 답변
```

전문 Agent는 Tool처럼 Manager에게 결과를 반환합니다. Handoff와 달리 현재 대화의 담당은 Manager에서 바뀌지 않습니다.

코드 실행 저장소가 아닙니다. [HARNESS-STRUCTURE.md](HARNESS-STRUCTURE.md)부터 열어 이 패턴의 역할·Contract·Policy·Tool·Skill 구성을 확인합니다.
