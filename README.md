# shopping-mall-item-classification

## 소개
#### 인터넷 쇼핑몰의 상품의 이미지와 텍스트 정보를 이용해서 상품을 해당 카테고리로 분류하는 방법을 제안합니다.
#### [한국정보과학회]KSC2020 논문, [P9.4-8] '이미지 및 텍스트 정보를 이용하여 딥러닝 모델기반 쇼핑몰 상품 카테고리 분류'로 논문을 기재했습니다.

## 데이터 셋 설명
#### 2020년 6월 11일, 쇼핑몰 11번가의 베스트 200 메뉴에서 크롤링으로 데이터를 추출했다. 
#### 상품 종류는 바지, 원피스, 가방, 신발, 티셔츠 5개이며 각 카테고리 별로 500개의 데이터, 총 데이터의 수는 2천 개이다. 
#### 각 카테고리 별로 학습데이터는 400개, 테스트 데이터는 100개씩으로 나누었다. 데이터 셋은 상품 이미지와 상품을 설명하는 텍스트, 카테고리 명으로 구성했다.

## 코드 소개
### 1. image classification
#### 소스 코드 파일 : image_classification_using_shoppingmall.ipynb
#### 분류 모델: CNN, TRANSFER LEARNING (RESNET18)

### 2. text classification
#### 소스 코드 파일 : text_classification_using_shoppingmall_1.ipynb
#### 분류 모델: RNN
#### 소스 코드 파일 : text_classification_using_shoppingmall_2.ipynb
#### 분류 모델: LSTM

### 참고한 자료 
#### https://tutorials.pytorch.kr/beginner/transfer_learning_tutorial.html
#### 딥 러닝을 이용한 자연어 처리 입문, 3) 로이터 뉴스 분류하기(Reuters News Classification), https://wikidocs.net/22933
