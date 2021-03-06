# NIPA 2020 인공지능 문제해결 경진대회
![[nipa]](img/nipa_main_contest_info_full_2.jpg)
## 1. 예선 - 식물과 병충해의 종류 예측
  - 목표: 주어진 식물 사진을 통해 해당 식물의 종류와 병충해 종류를 분류하는 알고리즘 개발
  - 데이터 셋
    - Train - jpg 이미지 16,000장, 라벨 tsv 파일
    - Test - jpg 이미지 3,997장, 라벨 tsv 파일
  - 모델 평가: Accuracy

## 2. 본선 1 - 중고차 판매기간 예측
  - 목표: KB차차차에 등록된 중고차 매물의 등록부터 판매까지 소요된 총 기간을 예측
  - 데이터 셋
    - 중고차 매물과 관련된 38개의 Numeric 변수
    - 원핫 인코딩이 된 33개의 Categorical 변수
    - 판매 소요 기간인 Target 변수
  - 모델 평가: RMSE

## 3. 본선 2 - 육군 민원 모델 분류
  - 목표: 육군 SNS 계정 게시글 댓글을 이용해 긍정/부정/중립 3가지 카테고리를 분류하는 감성 분석
  - 데이터 셋
    - 육군 Youtube, Facebook, Instagram의 게시글 댓글
    - 원핫 인코딩이 된 33개의 Categorical 변수
    - 판매 소요 기간인 Target 변수
  - 모델 평가: F1-Score