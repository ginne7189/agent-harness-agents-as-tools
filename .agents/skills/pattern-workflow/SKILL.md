---
name: agents-as-tools-workflow
description: 한 Manager가 전문 Agent를 Tool처럼 호출하고 최종 대화를 계속 맡을 때 사용합니다.
---

1. Manager가 사용자 요청과 필요한 전문 분야를 확인합니다.
2. 필요한 Specialist만 호출하고 최소 Context만 전달합니다.
3. Specialist는 맡은 결과를 Contract 형식으로 Manager에게 반환합니다.
4. 사용자 대화와 최종 통제권은 Manager가 유지합니다.
5. 결과 충돌은 숨기지 않고 최종 답변에 표시합니다.

