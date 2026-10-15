# KTcs K-Link

<p align="center">
  <strong>업무지식을 더 빠르게 찾고, 근거와 함께 활용하는 AI</strong><br>
  생성형 AI 기반 기업 업무지식 검색·활용 Assistant 프로젝트
</p>

분산된 업무 문서에서 필요한 내용을 자연어로 찾고, 답변과 함께 근거 출처를 확인할 수 있는 AI Assistant MVP를 만듭니다.

## 만들고 있는 경험

- 업무 질문과 관련된 문서 내용을 검색합니다.
- 여러 자료의 핵심을 요약하고, 답변에 참고한 문서와 근거를 보여줍니다.
- 문서 간 정보 비교와 업무 절차 안내를 통해 실제 업무 수행을 돕습니다.
- MCP를 통해 업무지식 검색 기능을 AI 클라이언트에서 활용할 수 있도록 연결합니다.

이 기능들은 8주 프로젝트의 목표입니다. 정확도와 활용성은 대표 질문을 이용한 테스트와 사용자 검증으로 확인합니다.

## 프로젝트 저장소

| 저장소 | 역할 |
| --- | --- |
| [ai-assistant](https://github.com/KTcs-KLink/ai-assistant) | 질문 입력, 답변·출처 확인 등 사용자 화면 |
| [knowledge-mcp](https://github.com/KTcs-KLink/knowledge-mcp) | MCP 기능, 지식 문서 수집·청킹, 출처 및 데이터 관리 |
| [.github](https://github.com/KTcs-KLink/.github) | 공통 협업 가이드, Issue·PR 템플릿 |

## 지식 데이터 원칙

문서와 청크는 동일한 `source_id`로 연결해 원문 근거를 추적할 수 있도록 관리합니다. 출처와 재사용 조건이 확인된 자료만 원본과 청크로 저장하며, 조건이 불분명한 자료는 출처 정보만 기록합니다. 비밀키, 개인 정보, 비공개 업무자료는 저장소에 올리지 않습니다.

데이터 업로드 경로와 형식은 [`knowledge-mcp` 데이터 안내](https://github.com/KTcs-KLink/knowledge-mcp/tree/main/data)에서 확인할 수 있습니다.

## 함께 참여하기

1. 작업할 저장소의 README에서 역할과 실행 방법을 확인합니다.
2. 관련 Issue를 선택하거나, 새 작업은 Issue로 등록합니다.
3. 작업 브랜치에서 변경하고 Pull Request로 공유합니다.
4. 팀원 리뷰를 반영한 뒤 `main`에 병합합니다.

브랜치·커밋·리뷰 규칙은 [협업 가이드](https://github.com/KTcs-KLink/.github/blob/main/CONTRIBUTING.md)를 참고하세요.

## 프로젝트 산출물 목표

- 생성형 AI 기반 업무지식 검색·활용 Assistant MVP
- 검색·답변 품질과 업무 활용성을 정리한 최종 보고서
- 구현 과정과 시연 결과를 공유하는 최종 발표자료

프로젝트 수행 기간: **2026년 10월 12일 - 12월 6일**
