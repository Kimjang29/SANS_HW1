# Project Configuration (LTM)

*This file contains the stable, long-term context for the project.*
*It should be updated infrequently, primarily when core goals, tech, or patterns change.*

---

## Core Goal

에너지 절약 제도 및 캠페인 관련 정보를 수집하여 한국어 뉴스레터를 제작합니다.
주요 수집 대상:
- 국민 DR 제도 관련 뉴스 및 공고
- 에코마일리지 소식
- 지역 에너지 절약 캠페인 및 행사
- 에너지 효율 관련 정부 정책

---

## Tech Stack

*(List the primary technologies, frameworks, and languages used. E.g.,)*
*   **Frontend:** React, TypeScript, CSS Modules
*   **Backend:** Node.js, Express, PostgreSQL
*   **Testing:** Jest, React Testing Library
*   **Linting/Formatting:** ESLint, Prettier

**Content Management:**
- 한국어 콘텐츠
- Markdown 형식
- 날짜 기반 업데이트

---

## Critical Patterns & Conventions

*(Document any non-standard but crucial design patterns, architectural decisions, or coding conventions specific to this project. E.g.,)*
*   **State Management:** Redux Toolkit slices pattern.
*   **API Design:** RESTful principles, specific endpoint naming convention `/api/v1/...`.
*   **Error Handling:** Use custom `AppError` class for backend errors.
*   **Commit Messages:** Follow Conventional Commits format.

**뉴스레터 형식:**
- 제목: "🌱 에너지 세이빙 뉴스레터 (YYYY년 M월 D일 기준)"
- 각 항목: 제목, 설명, 출처/링크, 발행일 포함
- 새로운 뉴스가 없을 경우 명시

---

## Key Constraints

*(List any major limitations or non-negotiable requirements. E.g.,)*
*   Must support IE11 (if applicable).
*   Deployment target is AWS Lambda.
*   Strict adherence to budget/performance targets.
*  한국 시간 기준 (KST/UTC+9)
*  공신력 있는 출처의 정보만 포함
*  최신 정보 우선

---

## Tokenization Settings

*   **Estimation Method:** Character-based
*   **Characters Per Token (Estimate):** 4
