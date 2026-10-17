<div align="center">

<img src="https://resources-public-prd.modulabs.co.kr/home-section/asset-lab/ccdb66da-1c92-477a-becf-723348c577d5.png" alt="Legato User Group Banner" width="100%" />

# 🎵 Legato User Group
### **Connecting AI Models to Silicon — Open Low-Level IR & AI System SW Community**

[![ModuLabs](https://img.shields.io/badge/Community-ModuLabs%20(모두의연구소)-F7585C?style=for-the-badge)](https://modulabs.co.kr/labs/811)
[![Supported by](https://img.shields.io/badge/Supported%20by-MSIT%20%26%20IITP%20(K--Cloud)-004EA2?style=for-the-badge)](https://www.iitp.kr)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=for-the-badge)](https://opensource.org/licenses/Apache-2.0)

</div>

---

## 👋 Welcome to Legato User Group!

**Legato User Group**은 개방형 저수준 중간표현(**Legato Open Low-Level IR**)과 **AI 시스템 소프트웨어(컴파일러·런타임·커널·가속기 아키텍처)**를 함께 연구하고 학습하며 오픈소스 생태계를 만들어가는 개발자·연구자 커뮤니티입니다.

> 🎵 **Why "Legato"?**  
> 음악에서 *"음과 음을 끊지 않고 매끄럽게 이어 연주하라"*는 뜻의 지시어 **Legato(레가토)**처럼, 빠르게 변화하는 상위 AI 모델·프레임워크(`PyTorch`, `vLLM`, `SGLang`)와 다양한 하드웨어 가속기(`LPU`, `NPU`, `GPU`)를 특정 벤더 종속 없이 매끄럽게 연결한다는 의미를 담고 있습니다.

---

## 🧭 주요 활동 및 레포지토리 로드맵 (Projects & Roadmap)

| 구분 | 레포지토리 / 프로그램 | 설명 | 상태 |
| :---: | :--- | :--- | :---: |
| 📘 **학습 & 교재** | [**`tensor2slicon-lab`**](https://github.com/legato-user-group/tensor2slicon-lab) | **[T2S Lab]** AI 모델에서 가속기 커널까지 — 실행 스택, Roofline, Tiling, Triton, xPU 비교를 다루는 오픈소스 온라인 교재 및 실습 코드 | 🟢 **진행 중** |
| 📄 **명세 & 문서** | `legato-docs` *(예정)* | Legato 저수준 IR 명세서, 프로그래밍 모델 가이드, API 레퍼런스 및 튜토리얼 (국/영문) | 🔜 공개 예정 |
| 💻 **샘플 & 툴킷** | `legato-samples` *(예정)* | 외부 개발자 온보딩을 위한 Legato 기반 커널 작성 예제 및 PyTorch/vLLM 연동 샘플 | 🔜 공개 예정 |
| 🏆 **벤치마크** | `legato-leaderboard` *(예정)* | 오픈소스 기여자 중심의 AI 가속기 커널 성능 벤치마크 및 리더보드 | 🔜 공개 예정 |

---

## 🤝 함께하는 기관 (Consortium & Ecosystem Partners)

본 커뮤니티는 **과학기술정보통신부** 및 **정보통신기획평가원(IITP)**의 **「AI반도체를 활용한 K-클라우드 기술개발사업」**(*과제명: 지속적 AI반도체 성능 최적화를 위한 AI 생태계 적응형 시스템SW 기술 개발, `RS-2026-25521385`*)의 일환으로 산·학·연 컨소시엄과 함께 운영됩니다.

- **㈜하이퍼엑셀 (HyperAccel)** — Legato 저수준 공개 IR 설계, 컴파일러 백엔드·런타임 및 LPU 아키텍처 개발
- **㈜스퀴즈비츠 (SqueezeBits)** — PyTorch/vLLM 연동 컴파일러 프론트엔드 및 정밀도 제어 기반 모델 경량화·양자화
- **서울대학교 (SNU)** — NPU 특화 커널 설계 공간 정의, 그래프 변환 및 연산·통신 중첩 스케줄링 최적화
- **한국과학기술원 (KAIST)** — NPU-GPU 이기종 LLM 서빙 시스템 시뮬레이터 및 클러스터 스케줄링 자동 탐색
- **모두의연구소 (ModuLabs)** — 오픈소스 커뮤니티(Legato User Group) 운영, 공개 교재 집필(T2S Lab) 및 기술 컨퍼런스/워크숍 개최

---

## 🚀 참여 방법 (Get Involved)

- **스터디 & 공동 집필**: [모두의연구소 Tensor2Silicon LAB](https://modulabs.co.kr/labs/811)에서 주차별 리서치 노트와 실습 코드를 확인하고 Issue/PR로 피드백을 남겨주세요.
- **기술 워크숍 & 세미나**: 연 2회 개최되는 공개 기술 워크숍 및 **모두콘(MODUCON)** 세션을 통해 누구나 함께 배우고 기여할 수 있습니다.
- **문의 (Contact)**: 모두의연구소 커뮤니티팀 이영빈 ([@yblee110](https://github.com/yblee110) / `yb.lee@modulabs.co.kr`)
