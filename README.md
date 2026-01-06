# RetiQ_VCP(Retina Blood Vessel Segmentation in PyTorch)

간단한 설명
이 저장소는 망막 혈관 분할을 위한 PyTorch 기반 구현입니다. 주로 UNet 계열 모델을 사용하여 DRIVE, HRF 데이터셋을 대상으로 학습·평가를 수행합니다.

주요 내용
- 모델 구현: UNET/model.py
- 학습 스크립트: UNET/train.py
- 평가/테스트: UNET/test.py, UNET/test_hrf.py
- 데이터 로더/유틸: UNET/data.py, UNET/utils.py
- 손실 함수: UNET/loss.py
- 예비 체크포인트: UNET/files/checkpoint.pth
- 데이터셋 폴더: DRIVE/, HRF/, new_data/

**데이터 출처**
- DRIVE (Digital Retinal Images for Vessel Extraction): https://drive.grand-challenge.org/  
- HRF (High-Resolution Fundus Image Database): https://www5.cs.fau.de/research/data/fundus-images/  


**폴더 구조(요약)**
- UNET/: 모델 및 학습/테스트 관련 코드
- DRIVE/: DRIVE 데이터셋 (training / test)
- HRF/: HRF 데이터셋 및 결과
- new_data/: 사용자 준비 데이터(학습/테스트)
- data_aug.py: 데이터 증강 스크립트
- requirements.txt: 의존성 목록

"This project is based on https://github.com/nikhilroxtomar/Retina-Blood-Vessel-Segmentation-in-PyTorch (Nikhil Roxtomar)."
"본 프로젝트는 Nikhil Roxtomar 님의 저장소(https://github.com/nikhilroxtomar/Retina-Blood-Vessel-Segmentation-in-PyTorch)를 기반으로 합니다."
