# gbdcon
### 2021 여름학기 DAYS 공모전 참여 활동 - 경상북도 공공데이터 경진대회 
http://www.gbdcon.kr/
### 공모분야: 1-2. 데이터 분석 및 활용

#### - 아이디어에 사용된 추천 시스템 모델 코드 -
`1. 콘텐츠 기반 필터링 (Content-based filtering)`
##### 상품 자체가 지닌 속성을 기반으로, 특정 상품과 유사한 유형의 다른 상품을 추천하는 방식

`2. 아이템 기반 협업 필터링 (Item-based Collaborative filtering)`
##### 최근접 이웃(Nearest Neighbor) 협업 필터링 중 아이템 기반 협업 필터링 모델 구현
##### 상품을 향한 고객의 평점, 관심도, 고객의 구매 이력 등 사용자의 행동양식(User behavior)에 기반으로 함
##### 사용자들이 상품에 대해 평가한 척도를 바탕으로, 유사한 상품을 추천하는 방식

`3. 잠재요인 협업 필터링 (Latent Factor Collaborative filtering)`
##### 대규모 다차원 행렬을 SVD(차원 감소 기법)으로 분해하는 과정 (Matrix Factorization)을 통해 잠재요인 추출
##### 사용자와 상품 평점 matrix 내에서 추출한 잠재요인을 기반으로 상품을 추천하는 방식
