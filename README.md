# Musinsa_3rd_project
딥러닝을 통한 리뷰 점수 재평가

- crawling 
  - musinsa에 등록 된 상품의 리뷰 및 점수 크롤링
  - 네이버 쇼핑에 등록 된 상품의 리뷰 및 점수 크롤링 ( 점수가 낮은 리뷰 수가 너무 적어 추가 데이터 확보를 위함 )

- data_augmentation
  - 점수가 낮은 리뷰의 수가 적어 데이터 추가를 위해 다양한 방법( back translation, generation, EDA 등 )으로 augmentation 진행
  
- data_handing
  - 모델 학습 전 데이터 정제 및 전처리 진행
  
- KoBert Classification 모델을 이용해 학습하여 점수 재평가
