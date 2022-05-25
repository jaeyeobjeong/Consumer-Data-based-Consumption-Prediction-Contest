## Consumer-Data-based-Consumption-Prediction-Contest

주관/주최 : DACON

학습 모델 : CatBoost & XGBoost Regressor <br>
앙상블 기법 : Hard Voting<br><br> 

모델 성능 : <br>
Public : NMAE 0.1592 (대회 1등) <br>
Private : NMAE 0.18436 (대회 30등) <br>

### Feautre Description
**Numeric Features**<br>
Year_Birth : 고객 생년월일<br>
Education : 고객 학력<br>
Marital_status : 고객 결혼 상태<br>
Income : 고객 연간 가구 소득<br>
Kidhome : 고객 가구의 자녀 수<br>
Teenhome : 고객 가구의 청소년 수<br>
Dt_Customer : 고객이 회사에 등록한 날짜<br>
Recency : 고객의 마지막 구매 이후 일수<br>
NumDealsPurchases : 할인된 구매 횟수<br>
NumWebPurchases : 회사 웹사이트를 통한 구매 건수<br>
NumCatalogPurchases : 카탈로그를 사용한 구매 수<br>
NumStorePuchases : 매장에서 직접 구매한 횟수<br>
NumWebVisitsMonth : 지난 달 회사 웹사이트 방문 횟수<br><br>
**Categorical Features**<br>
AcceptedCmp(1 ~ 5): 고객이 (1 ~ 5) 번째 캠페인에서 제안을 수락한 경우 1, 그렇지 않은 경우 0<br>
Complain : 고객이 지난 2년 동안 불만을 제기한 경우 1, 그렇지 않은 경우 0<br>
Response : 고객이 마지막 캠페인에서 제안을 수락한 경우 1, 그렇지 않은 경우 0<br>

target : 고객의 제품 총 소비량
