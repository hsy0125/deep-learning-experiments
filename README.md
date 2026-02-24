# 🧠 Deep Learning 실험 및 분석 프로젝트

본 프로젝트는 딥러닝 모델을 단순 구현하는 것이 아닌,  
학습 특성 및 하이퍼파라미터 변화에 따른 수렴 특성을 분석하기 위한 실험 중심 저장소입니다.

---

## 🎯 프로젝트 목표

- CNN 기반 이미지 분류 모델 구현
- 하이퍼파라미터 변화에 따른 성능 비교
- 학습 안정성 및 수렴 특성 분석
- Seed에 따른 분산 분석

---

## 🛠 사용 기술

- Python
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 프로젝트 구조
deep-learning-experiments
│
├── notebooks      # 실험 노트북
├── models         # 모델 정의 코드
├── experiments    # 하이퍼파라미터 실험 코드
├── results        # 실험 결과 그래프 및 로그
└── README.md

---

## 🧪 실험 계획

1. Baseline CNN 구현
2. Learning Rate 변화 실험
3. Optimizer 비교 (SGD vs Adam)
4. Batch Size 변화 실험
5. Multi-seed 실험을 통한 평균 및 표준편차 분석

---

## 📊 분석 관점

- 수렴 속도 비교
- Loss 진동 여부
- Overfitting 발생 시점
- 일반화 성능 차이
- Seed에 따른 학습 안정성

---

## 🚀 향후 확장

- Data Augmentation 적용
- Regularization 비교 (Dropout / Weight Decay)
- 모델 구조 확장 (ResNet 비교)
- 실험 반복 횟수 증가 및 통계 분석

---

## 📌 개발 방향

단순히 모델을 학습시키는 것이 아니라,

✔ 왜 이런 결과가 나오는지  
✔ 하이퍼파라미터가 수렴에 어떤 영향을 미치는지  
✔ 모델의 안정성은 어떻게 평가할 수 있는지  

를 분석하는 것을 목표로 합니다.
