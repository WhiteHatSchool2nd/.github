# 한국정보기술연구원 화이트햇 스쿨 2기 프로젝트 NeuralGurdians

# 프로젝트 개요

발전소 공정 데이터를 분석해 검증된 새로운 최신 모델을 접목하여 성능 평가를 하는 것이 목표입니다.

# 팀원 소개

## 멘토

- **박건호**
## 프로젝트 리더(PL)

-  **곽송이**

## 프로젝트 매니저(PM)

- **한준서**

## 팀원

- **김성광**
- **양호찬**
- **문서진**
- **한윤서**
- **정지현**

# 데이터셋 정보

https://github.com/icsdataset/hai

## 데이터셋 메뉴얼

https://github.com/icsdataset/hai/blob/master/hai_dataset_technical_details.pdf

# 관련 대회 정리

[# HAICon2021 산업제어시스템 보안위협 탐지 AI 경진대회](https://dacon.io/competitions/official/235757/overview/description)


# 일정

---

### 8월

- **8/1~8/7**: 성능평가에 사용할 새 모델 선정
- **8/8~8/14**: 기존 모델 성능 개선, 새 모델 훈련 과정 공부


# WBS

- 작업중
[https://docs.google.com/spreadsheets/d/12gPRNSC9bqZlqQibdWWhSHU-MFTciQ9hV2VQIW2A5ok/edit?usp=sharing]

# 프로젝트 고도화 일정

- 1회차 : 2024. 8. 7(수). 23시 59분까지  
- 2회차 : 2024. 8. 14(수). 23시 59분까지  
- 3회차 : 2024. 8. 21(수). 23시 59분까지  
- 4회차 : 2024. 8. 28(수). 23시 59분까지  
- 5회차 : 2024. 9 4(수). 23시 59분까지  
- 6회차 : 2024. 9. 11(수). 23시 59분까지
- 제출링크 : [https://forms.gle/vfej4Qm2U44nuR5t7](https://forms.gle/vfej4Qm2U44nuR5t7)

# 모델 학습

## TranAD

### 모델 훈련

#### 손실률, 학습률 그래프
![훈련 그래프](../loss.png)

#### 성능평가 그래프

![성능 그래프](../result.png)
- HAI 20.07 데이터셋 2만개 사용

#### F1스코어

**F1 Score: 0.971041948579161<br>
Precision: 0.9437138348237769<br>
Recall: 1.0<br>
Accuracy: 0.9946339017051153<br>
Confusion Matrix:<br>
18039   107<br>
 0          1794**

### 21년도 데이터 셋

#### 손실률, 학습률 그래프

![](../loss_21.png)

#### 성능 평가 그래프

![](../result_21.png)
- HAI 21.03 데이터셋 2만개 사용

- **Accuracy Score: 0.983099297893681**
- **F1 Score: 0.9856825030175624**
- **Precision: 0.85**
## MTAD-GAT

## LSTM-Autoencoder

## Autoencoder

#### 손실률, 학습률 그래프
<img width="558" alt="autoencoder_" src="https://github.com/user-attachments/assets/f61c97b0-2582-4647-9524-2fb9c68173e9">

#### 성능평가 그래프
<img width="684" alt="스크린샷 2024-08-21 오전 10 05 52" src="https://github.com/user-attachments/assets/3f2bf412-174c-45b0-9ceb-756f98b9fdd5">


#### F1스코어

**F1 Score: 0.6504668691641354<br>
Precision: 0.95<br>
Recall: 0.49<br>
Accuracy: 0.98<br>
Confusion Matrix:<br>
8538    452<br>
8939    0**

## CNN-LSTM

