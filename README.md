# Deepfake Audio Watermark Robustness Study

본 연구는 딥페이크 음성 표시 기술의 서비스 환경 내 생존성을 평가한다.

## Dataset
- ASVspoof 2019 LA
- Synthetic only
- 300 samples
- 16kHz / mono / wav

## Attacks
- MP3 compression (128, 96, 64, 48, 32 kbps)
- AWGN (SNR 30, 20, 10 dB)

## Metrics
- BER
- Success Rate
- Collapse Threshold
