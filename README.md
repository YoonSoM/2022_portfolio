### NLP
- NLP MUSINSA (2022.06~07)
- LSTM Seq2Seq with Attention(2022.05)
- Text Mining ML (2022.04~08)


### CV(Computer Vision)
* Car Damage Detection(2022.07~08)
* Kaggel Competition : HuBMAP + HPA - Hacking The Human Body (2022.08~09)

# 이미지처리

### 이미지 분류 프로젝트
### 주요기능
- Resnet50의 pretrain model 사용
### class별 이미지 분류작업 프로젝트이다.
----
# 음성 처리

### 텍스트 감성분류 프로젝트
- kolnpy를 nlp에서 형태소 단위 Tokenizer를 하는 한국어 전처리에서 사용
- 정규화 방식으로 결측치 제거 
### 리뷰 텍스트 감셕을 통해 독자의 감정 상태를 파악하는 프로젝트이다

# 객체인식

### 졸음운전 방지 운전자 상태 인식
### 주요기능
- 사용한 모델 (yolo v4)
- AlexNet으로 학습 진행
- 전이학습으로 분류기 부분만 재학습 훈련/테스트 셋 7/3 ---> 훈련/테스트 셋 5/5
- 전이학습을 하기 위해 사전학습된 모델을 가져와 층을 더 추가하여서 include_top=False으로 줌
- 하위층 일부 재학습 시킴

- 졸음운전 예방을 위한 운전자 상태 정보를 인식하여 졸음운전을 사전 방지하는 프로젝트입니다.
---

### 무신사 입점브랜드에 관한 실질적 평가지표 제시
### 주요기능
- 사용한 모델 (KoEDA)(BERT)
- AutoTokenizer의 SKT의 kogpt2-base-v2로 tokenizer를 진행.
- TFGPT2Model의 pretrained된 SKT의 kogpt2-base-v2를 사용

- 무신사에서의 별점과 댓글의 반응 차이가 달라 실질적으로 별점만 신뢰할 수 없기때문에 새로운 평가지표를 만들어야 한다고 생각한 프로젝트입니다


# CV
### 차량 파손 여부 판단
### 주요기능
- 고객이 입력한 이미지가 차량의 어떤 부위를 촬영한 것인지 인지하고, 이미지 내 픽셀 단위로 분석해 파손 여부 판단
- 사용한 모델 (Deeplab_v3)(Unet)
- Backbone(ResNet_50)(ResNet_101)
- Segmentation
- Semantic Segmentation
- 치량 파손이미지를 인식하여 인식 부위와 여부를 판단해 소비자와 기업에게 도움을 주는 프로젝트 입니다.

---

# nlp
### 시(詩) 창작을 위한 AI 개발
### 주요기능
- 새로운 문장 생성
- 사용한 모델 (KOGPT2)

- 문예 창작활동에 도움을 주는 모델 NLP AI 개발 프로젝트 입니다.

