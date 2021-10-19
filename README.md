# Portfolio <br>
포트폴리오 정리 <br>


# 1. Project - 휴일과 매출의 관계 분석 <br>
   1) Background <br>
   - Holiday 일때와 아닐때, 매출에 차이가 있는가? <br>
   - 월마트 매출 데이터를 가지고 휴일 유무에 따른 매출 차이 분석 <br>
   <br>
   
   2) 데이터 출처 <br>
   캐글 월마트 데이터 <br>
   <br>
   
   3) 분석설계 <br> 
      (1) 각 store 별로 평균 매출 도출 <br>
      (2) Weekly sales 기준으로 극단값 제거 <br>
      (3) holiday True/False 로 groupby <br>
      (4) 등분산검정을 시행해 0가설 검증 <br>
    <br>
   
   4) 결과 <br>
   - 등분산 결과 p > .05 이므로 0가설 기각 불가하다. <br>
   - 따라서 휴일과 매출은 관계가 없다. <br>

# 2. Project - 상점 매출 분석 및 매출 증대 계획 제안<br>
  1) Background<br>
  - 매출을 결정짓는 요인을 분석하고 그에 따른 매출 증대 계획 제안<br>
  <br>
  
  2) 데이터 출처<br>
  캐글 로스만 세일즈 데이터<br>
  <br>
  
  3) 분석설계<br>
     (1) 베이스라인 모델링<br>
     (2) 피처 엔지니어링을 통해 여러 변수들 생성하기<br>
     (3) 매출 증대 방안 고려<br>
     <br>
     
  4) 결과<br>
  - 보조 데이터의 feature engineering과 변수 중요도 개념을 활용한 변수선택으로 예측 rmse는 1800까지 떨어짐.
  - 매출에 가장 중요한 요소는 프로모션 여부이다.
  - 경쟁업체와의 거리는 생각보다 덜 중요한 요소로 판명 됨

# 3. Project - 대출 상환 분석<br>
  1) Background<br>
  - 대출 상환 여부를 결정짓는 요인을 분석하고 그에 따른 대출 플랜 제안<br>
  <br>
  
  2) 데이터 출처<br>
  Kaggle / Home Credit Default Risk 데이터<br>
  <br>
  
  3) 분석 설계<br>
    (1) 모델링<br>
    (2) 모델링에 따른 피처들의 영향력 알아보기<br>
    (3) 영향을 많이 주는 5개의 변수와 대출금 상환 여부와의 관계 보기<br>
<br>

  4) 결과<br>
  <상환 여부 영향 상위 요소 5가지><br>
  1. AMT_CREDIT_TO_ANNUITY_RATIO : 대출 금액 대비 월별 상환금액의 비율<br>
  2. DAYS_EMPLOYED : 취업한 시기<br>
  3. DAYS_CREDIT : 다른 대출을 받은 시기<br>
  4. DAYS_LAST_PHONE_CHANGE : 핸드폰을 바꾼 시기<br>
  5. DAYS_BIRTH : 태어난 시기<br>


