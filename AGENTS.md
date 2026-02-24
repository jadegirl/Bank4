# Bank4 — 문제은행 v4

## 프로젝트 개요
- 수학 학원용 문제은행 v3의 **FE 완전 리빌드** (BE는 기존 REST API 유지)
- 20만건+ 문제 DB, MySQL + Vector DB(신규)
- 배포: Vercel | 레포: github.com/jadegirl/Bank4

## 현재 상태
- **Phase 0**: HTML 목업 제작 → 사장님 디자인 승인 대기
- 코딩 미착수 (승인 후 React 전환)

## 기술스택
- React 18 + TypeScript + Vite + Tailwind CSS
- 수식: KaTeX(화면) / XeLaTeX(PDF)
- 폰트: Pretendard(UI) + KoPubBatang(문제 본문)

## 디자인 규칙
- 컬러: Indigo/Blue (#4F46E5~#6366f1)
- **라이트모드 기본**, 다크모드는 토글 선택옵션
- 접기식 사이드바 (240px↔64px)
- 네이티브 폼 금지 (select, input[date] 등)
- 모든 소통·주석·커밋은 **한국어**

## 상세 맥락
- 전체 대화 요약, 결정사항, v3 구조, 비즈니스 전략 → **docs/context.md** 참조