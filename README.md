# Safe VLA Agent 🚗

## 연구 개요
 명령 억제 및 센서 불확실성 대응을 위한 지능형 자율주행 VLA 에이전트 연구

**석사과정** | 정보통신대학원 인공지능공학과 | 202433351 허대원

## 핵심 기능
- **Safety Arbitration Policy (SAP)**: 위험 명령 자동 감지 및 거부
- **SensorTrustScore**: 센서 신뢰도 실시간 측정
- **Gaussian Cost Map**: BEV 공간 위험도 계산

## 환경
- LMDrive (베이스라인)
- CARLA 시뮬레이터
- PyTorch 2.12 + CUDA 12.9

## 진행일지
- [2026-06-01](docs/2026-06-01.md) - 환경 세팅 완료 (WSL2, Docker, CARLA 연결)

## 참고
- [LMDrive](https://github.com/opendilab/LMDrive)
