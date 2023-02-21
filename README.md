# AIFFEL_EXPLORATION
|  | 프로젝트 요약 |
| --- | --- |
| EX-01 : Digit Classification | sklearn을 활용하여 숫자 손글씨 데이터를 다양한 ML모델을 사용해 학습시킨 후 분류 성능 평가 및 시각화 - 우수노드 선정됨 |
| EX-02 : Kaggle | Kaggle 대회에서 주어진 자전거 사용량 데이터셋을 활용하여 데이터 EDA 및 sklearn 을 사용하여 ML 모델 학습 후 시각화 하였음. |
| EX-03 : ARIMA for time series | Yahoo의 주가 데이터를 정상성을 띄도록 전처리 한 후 statsmodels 라이브러리를 사용하여 정확도가 높은 ARIMA  모델의 모수를 찾는 프로젝트 진행하였음. |
| EX-04 : Data Analysis | 캘리포니아의 House Price 데이터셋을 활용하여 데이터 EDA 및 sklearn의 ML 모델을 사용하여 예측, 결과는 좋지 않음 |
| EX-05 : Rock, Scissor, Paper | Tensorflow 사용하여 가위 바위 보 분류 모델 학습. 직접 찍은 사진 뿐만이 아닌 다른 사람들의 사진을 사용하여 Data Augmentation  진행, 하이퍼 파라미터와 모델을 반복적으로 수정하여 학습, test 데이터에 따라 모델의 정확도가 엄청나게 달라질 수 있다는 결론. |
| EX-06 : Song Writer | 영어 팝송 가사 데이터셋 사용, Tensorflow 를 사용하여  특수문자 및 반복되는 단어를 제거한 말뭉치를 만드는 전처리 후 keras 모델로 학습 후 가사를 생성하는 프로젝트 |
| EX-07 : Abstract News | 영문 뉴스 기사 데이터셋을 사용, Tensorflow 를 사용하여 텍스트 정규화 및 불용어 제거와 같은 전처리 후 Attnetion 모델 인코더와 텍스트를 생성하는 디코더 모델 학습 후 뉴스 내용을 요약하는 프로젝트, 다만 데이터 크기 문제와 전처리 품질이 좋지 않았던 탓인지 요약이 제대로 되진 않았음. |
| EX-08 : Sticker Camera | 요즘 카메라에 탑재되는 사진 어플의 sticker 기능을 구현하는 프로젝트,CV2와 dlib 라이브러리 사용, dlib에서 이미 학습된 모델을 사용하여, 사람의 얼굴 이미지의 랜드마크를 찾고 이를 스티커 이미지와 합성하는 프로젝트. 수염 이미지를 사용 했을 때 어울리는 랜드마크의 좌표를 계산하는것이 어려웠음.  |
| EX-09 : Sentimental Analysis | 긍정일 때 1, 부정일 때 0으로 라벨링 되어있는 네이버 영화리뷰 데이터셋을 사용, Tensorflow 를 사용하여 리뷰 내용의 감성을 분석하기 위해 데이터 셋을 전처리 후  LSTM 과 1D CNN모델을 사용하여 학습시킨 후 임베딩 레이어를 기존 pre trained 된 임베딩레이어와 비교하였고, 감성 분석 모델을 학습시켰음. |
| EX-10 : Semantic Segmentation | pixelib 라이브러리에서 학습된 모델을 사용하여 이미지에서 배경과 인물을 분리하여 배경을 블러 처리하는 프로젝트, pre-trained 모델을 사용한 결과에서 문제점 분석을 수행 |
| EX-11 : Chatbot | github 에서 공개된 chatbot 데이터를 전처리한 후 트랜스포머 모델을 사용하여 chatbot을 만드는 프로젝트. - 우수노드 선정. |
| EX-12 : OCR | keras-ocr, Tesseract 에서 pre-trained 모델을 사용하여 웹에서 수집한 이미지를 가지고 OCR성능및 결과를 비교하는 프로젝트. |
| EX-13 : BERT | Tensorflow 를 사용하여 BERT 모델을 pre-trained 된 모델을 fintuning, non-pretrained 모델을 학습시키는 두 가지 방식으로 진행, 모델 building 및 학습보다는 Inference 결과를 비교하는데 중점을 둔 프로젝트였음. |
| EX-14 : GAN | Fashion MNIST dataset을 사용하여 직접 GAN 모델을 빌드하고 학습시키는 프로젝트였음, Tensorflow 를 사용하여 모델을 직접 빌드하고 학습시켰으나 좋은 결과는 나오지 않음. |
| EX-15 : Recomendation | 영화 평점 데이터셋을 사용, 가설을 세우고 데이터를 전처리 한 후 내가 좋아하는 상위 5개의 영화를 입력하면 그와 비슷한 영화를 추천해주는 프로젝트. |
| EX-16 : cGAN | cGAN 을 구현하여 pix2pix 모델을 학습시키는 프로젝트, 그러나 결과는 매우 좋지 않았음.   |
| EX-17 : Movie predict | 영화 정보와 사용자별 영화 시청 정보 데이터셋을 사용하여 다음에 볼 영화를 예측하는 프로젝트, 직접 모델을 수정하려다 오류가 너무 많이 발생하여 결과는 좋지 않음. |
