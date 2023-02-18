# Google Colab에서 시작
1. https://colab.research.google.com/
2. 새 노트
3. 아래 코드 실행 
```
    from google.colab import drive
    drive.mount('/content/drive’)
```
```
    import os
    os.chdir('/content/drive/My Drive’)
```
```
    !git clone https://github.com/JuhyeonHailey/KNU_2023_FC_classification.git
```

4. 파일 – 드라이브에서 찾기 – 내드라이브/KNU_2023_FC_classification/01_FC_calculation.ipynb  
  
* 오류가 생길 경우 Kernel restart 후 다시 시도해보세요! 
  

# 코드 순서
### fMRI 데이터 확인 및 기능적 연결성 계산 (01_FC_calculation.ipynb)
휴식 상태/과제 수행 fMRI 데이터 불러오기
휴식 상태/과제 수행 뇌 활성화 변화 확인
기능적 뇌연결성 계산 및 확인

### Classification 모델 구축 및 훈련 (02_DNN_classification.ipynb)
모델 훈련에 쓸 기능적 뇌연결성 데이터 불러오기
Hyperparameters 설정
모델 구축에 필요한 함수 정의
저장 위치 설정 및 모델 정보 저장
훈련 시작

### 훈련된 모델 결과 해석 (03_DNN_result_interpretation.ipynb)
훈련된 모델 불러오기
모델 해석을 위한 가중치 특징 맵 만들기
7가지 뇌 영역 네트워크로 나누어 결과 확인
3D 형태로 결과 확인

------------------ 

이주현 jh0104lee@gmail.com 

https://bspl-ku.github.io/ 
