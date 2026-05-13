# ShieldDose_GUI v3 + 전통 GEANT4 통합 튜토리얼

> P2.17.1.0 세션 산출물 — 사용자 친화 학습 자료

GEANT4 방사선 차폐 시뮬레이션을 **두 가지 방법**으로 수행하는 단계별 따라하기 가이드:

1. **전통적 GEANT4 방식** — cc 파일 직접 작성 + cmake/make + 매크로
2. **ShieldDose_GUI v3 (우리 GUI) 방식** — 클릭 한 번으로 자동 매크로 + 시뮬

그리고 **두 방식의 가교**: 우리 GUI에서 cc 파일을 자동 출력하는 기능 (Ctrl+E).

## 자료 보기

👉 **[GitHub Pages 링크](https://jyc0289y-art.github.io/shielddose-tutorial/)**

또는 본 repo clone 후 `index.html` 브라우저로 열기.

## 11 섹션 구성

- §0 사전 환경 셋업 (GEANT4 + Qt5 + CMake)
- §1 STL 사전 시각화 (9 파일 × 3 시점 = 27 PNG)
- §2 ShieldDose_GUI v3 단계별 따라하기 (9 step + 신뢰 기관 데이터 출처)
- §3 cc 파일 export (Ctrl+E 5 단계)
- §4 생성 cc 파일 8개 본문 + 한국어 인라인 주석
- §5 전통 GEANT4 빌드 (cmake/make/실행 — 복사 가능)
- §6 시뮬 결과 산출물 (CSV 컬럼 의미 + 정량 결과)
- §7 GEANT4 vis manager 3D (기존 GUI 사용법)
- §8 전통 vs 우리 GUI 비교 매트릭스
- §9 물리 개념 (H*(10), CPE, SA ratio, buildup, ISS-087 학습 사례)
- §10 에러 처리 + FAQ
- §11 검증 체크리스트 + 클립보드 피드백 버튼

## 신뢰 기관 데이터 출처

- ICRP Publication 21 / ICRP-74 — 핵종 감마상수 + H*(10) 환산
- ENDF/B-VIII.0 — 핵종 spectrum (RaD parameters)
- Verbinski 1973 — Cf-252 prompt gamma
- NIST XCOM SRD 126 — 재료 감쇠계수
- ANS-6.4.3-1991 / NCRP Report 49 — 빌드업 팩터

## 본체 코드

본 튜토리얼이 시연하는 시스템 (ShieldDose CLI + ShieldDose_GUI v3) 코드는 별도 **private repo**에 보존. 본 자료는 학습용 자료만 포함.

## 라이센스

본 자료의 학습 자료 (HTML + 스크린샷)는 자유 열람.
ShieldDose 본체 코드는 별도 라이센스 적용 (private repo).

---

세션: P2.17.1.0 | 작성: 2026-05-14 | Claude (자동) + 사용자 명시 사양
