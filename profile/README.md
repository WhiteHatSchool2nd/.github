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

### 22년도 데이터 셋

#### 손실률, 학습률 그래프
![](../loss_22.png)

#### 성능 평가 그래프

![](../result_22.png)
### 23년도 데이터 셋

#### 손실률, 학습률 그래프

![](../loss_23.png)
#### 성능 평가 그래프

![](../result_23.png)

## MTAD-GAT

## LSTM-Autoencoder

## Autoencoder

### 20년도 데이터 셋

#### 손실률, 학습률 그래프
<img width="547" alt="스크린샷 2024-09-11 오전 10 23 54" src="https://github.com/user-attachments/assets/15f232a8-5704-411a-a248-68bfb9277e4d">

#### 성능평가 그래프
<img width="824" alt="스크린샷 2024-09-11 오전 10 23 58" src="https://github.com/user-attachments/assets/b834d3a7-f30d-4a67-89a1-cbf31fbf56b7">

#### F1스코어

**F1 Score: 0.739969<br>
Precision: 0.960922<br>
Recall: 0.601631<br>
Accuracy: 0.97<br>
Confusion Matrix:<br>
18318   39<br>
 635          959**

### 21년도 데이터 셋

#### 손실률, 학습률 그래프
<img width="553" alt="스크린샷 2024-09-11 오전 11 07 38" src="https://github.com/user-attachments/assets/7e148a33-c68c-469c-aeae-f1fc7c53d190">


#### 성능평가 그래프
<img width="826" alt="스크린샷 2024-09-11 오전 11 07 40" src="https://github.com/user-attachments/assets/0738c2ef-b7dc-4bb6-8a43-baca6dfe6f95">


#### F1스코어

**F1 Score: 0.611183<br>
Precision: 0.470942<br>
Recall: 0.870370<br>
Accuracy: 0.97<br>
Confusion Matrix:<br>
18882   529<br>
 71          469**

### 22년도 데이터 셋

#### 손실률, 학습률 그래프



#### 성능평가 그래프



#### F1스코어

**F1 Score: 0.61<br>
Precision: 0.47<br>
Recall: 0.87<br>
Accuracy: 0.97<br>
Confusion Matrix:<br>
18882   529<br>
 71          469**

## ResNet

### 20년도 데이터 셋

#### 성능 평가 그래프

![image](https://github.com/user-attachments/assets/0155e1dc-d2ea-4cef-9b5e-d8d8a37a27eb)

#### F1스코어
- **F1 Score: 0.3503
- **Precision:  0.5582
- **Recall: 0.2552
- **Accuracy: 0.9484

### 21년도 데이터 셋

#### 손실률, 학습률 그래프

![image](https://github.com/user-attachments/assets/de819617-0467-4d0e-bbf4-349544d1c6cc)


#### 성능 평가 그래프

![image](https://github.com/user-attachments/assets/41e9d6bc-d855-450e-b8be-906b1a77c8bf)

- HAI 21.03 데이터셋 15만개 사용

#### F1스코어
- **F1 Score: 0.2747
- **Precision:  0.8641
- **Recall: 0.1633
- **Accuracy: 0.9751
- **Confusion Matrix:
390057 298 <br>
9703 1894


