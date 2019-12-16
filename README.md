1. 프로젝트 주제 선정 동기

2. csv 자료화면 캡쳐

3. 모듈 임포트

4. csv자료 읽어오기(출처 : kaggle의 student-alcohol-consumption중 student-por.csv만사용 )


5. 데이터 구성


- 조사 대상 학생들의 특성 시각화(Visualization)의 하위항목으로는 Sex, Weekly study time, Romantic Relationship, Age, Alcohol Consumption and other features가 있다.


- Alcohol Consumption and other features의 하위 항목으로는 Weekend Alcohol Consumption, Alcohol Consumption and Health, Alcohol Consumption and Final Grade가 있다.


6. 2개의 regression 모델을 사용한 Final Grade Prediction 실시(With G1 and G2 features)


- DecisionTreeRegressor와 LinearRegression 모델을 활용한 모델링 작업


- RandomForestClassifier


- LinearRegression


- Feature Importances


7. 2개의 regression 모델을 사용한 Final Grade Prediction 실시(Without G1 and G2 features, predict G1 & G2 & G3)


- G1 & G2 prediction(LinearRegression으로 G1, G2 예측)


- DecisionTreeRegressor과 LinearRegression을 사용한 G3의 예측

