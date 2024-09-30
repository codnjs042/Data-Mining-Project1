# Data-Mining-Project1

### AI-Hub의 상수관로 누수 감지 데이터 활용
[![image](https://github.com/codnjs042/Data-Mining-Project1/assets/73993796/8221421e-b79c-475f-91d6-27602d082f09)  ](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=138)  
https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=138


### AI 모델
모델 간결화 및 다양한 접근법 공략
- 변수 선택
  - 상관 계수 기반 변수 선택을 통해 독립 변수 간 상관 관계가 높은 변수를 제거하여 다중공선성을 감소시켰습니다.
- 파생 변수 생성
  - 날짜 변수를 활용하여 연도, 월, 일, 요일 등 새로운 변수를 생성하여 모델의 정보량을 증가시켰습니다.
- 다양한 머신러닝 분류 모델 실험
  - KNN, Decision Tree, SVM, XGBoost, Random Forest, LGBM 등 여러 모델을 시도했습니다. 
- 앙상블 진행
  - 상위 모델 3가지(KNN, XGBoost, Random Forest)를 하드 보팅 방식으로 결합하여 단일 모델보다 성능을 향상시켰습니다.
- 최종 모델 성능 평가
  - Accuracy 0.9624
