# 2026 반도체공학회 하계종합학술대회

**2026 Summer Annual Conference of ISE** 참가 및 발표 기록을 정리한 Experience Portfolio 저장소입니다.

- **Conference:** 2026년도 반도체공학회 하계종합학술대회
- **Period:** 2026.07.14–2026.07.17
- **Presentation:** 2026.07.15
- **Venue:** 아난티 앳 부산 코브
- **Session:** 숭실대학교 차세대반도체학과 특별세션 1
- **Role:** Presenter
- **Status:** Complete

## Overview

반도체공학회가 주최한 2026년도 하계종합학술대회에 참가해 TCAD 기반 Dual-Metal Gate MOSFET 연구를 발표했습니다. 학회 현장에서 연구의 공정 구현 가능성과 계면 상태 검증에 관한 피드백을 받았으며, 이를 바탕으로 BCAT과 유사한 매몰 게이트 구조 및 계면 상태 분석을 후속 연구 방향으로 검토하고 있습니다.

## Summary

Presented a TCAD-based Dual-Metal Gate MOSFET feasibility study at the 2026 Summer Annual Conference of the Institute of Semiconductor Engineers. The presentation received feedback on buried-gate process implementation and interface-state validation, which will be considered in a follow-up study for a next-generation semiconductor competition.

## Presented Work

**Dual Metal Gate를 이용한 미세 MOSFET의 SCE 및 Leakage Current 개선 효과 분석**

- 발표자: 이선재, 주상현
- 발표 일시: 2026년 7월 15일
- 세션: 숭실대학교 차세대반도체학과 특별세션 1
- 장소: G층 크루즈 그랜드 볼룸 A

연구의 상세 구조, 시뮬레이션 과정 및 결과는 아래 프로젝트 페이지에서 확인할 수 있습니다.

- [Dual-Metal Gate MOSFET Feasibility Study](https://jujushmaterial.github.io/TCAD-Dual-Metal-Gate-MOSFET-Feasibility-Study/)

## Conference Feedback

현장 질의에서는 평면 구조의 공정 복잡성에 대해, **BCAT과 유사한 트렌치 기반 매몰 게이트 구조로 구현 가능성을 검토할 수 있다**는 의견을 받았습니다. 또한 구조의 실현 가능성을 판단하기 위해 **게이트 유전체와 반도체 사이의 interface state가 소자 특성에 미치는 영향을 함께 확인할 필요가 있다**는 피드백을 받았습니다.

## Development Plan

- TCAD에서 계면 트랩 및 고정 전하 조건을 추가해 전기적 특성 변화 확인
- BCAT과 유사한 트렌치·매몰 게이트 구조의 구현 가능성 검토
- 기존 Dual-Metal Gate 연구와의 연결성 및 공정 현실성 재평가
- 후속 결과를 차세대반도체 경진대회 연구 주제로 발전시키는 방안 논의

## Public Materials

- [Published Experience Page](https://jujushmaterial.github.io/2026-Summer-Annual-Conference-of-ISE/)
- [2026 하계종합학술대회 프로그램북](assets/docs/2026-ise-summer-conference-program.pdf)
- [반도체공학회 공식 홈페이지](https://www.theise.org/)

## Repository Structure

```text
2026-Summer-Annual-Conference-of-ISE/
├─ README.md
├─ index.html
├─ assets/
│  ├─ css/
│  │  └─ style.css
│  ├─ docs/
│  │  └─ 2026-ise-summer-conference-program.pdf
│  └─ images/
│     ├─ ise-logo.png
│     ├─ presentation-closeup.jpg
│     ├─ presentation-stage.jpg
│     ├─ presentation-title-slide.jpg
│     └─ conference-badge.jpg
└─ .github/
   └─ workflows/
      └─ pages.yml
```

공개 사진은 행사 기록 및 발표 활동 증빙을 목적으로 사용하며, 주변 인물은 식별되지 않도록 처리된 이미지를 사용합니다.