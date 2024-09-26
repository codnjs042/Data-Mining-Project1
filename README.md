# Data-Mining-Project1

### AI-Hub의 상수관로 누수 감지 데이터 활용
[![image](https://github.com/codnjs042/Data-Mining-Project1/assets/73993796/8221421e-b79c-475f-91d6-27602d082f09)  ](https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=138)  
https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=138


### AI 모델
모델 간결화 및 다양한 접근법 공략
- 변수 선택 및 다중공선성 문제 해결
  - 상관 계수 기반 변수 선택을 통해 독립 변수 간 상관 관계가 높은 변수를 제거했습니다. 이를 통해 다중공선성을 줄이고 모델의 성능을 2% 향상시켰습니다.
- 특징 엔지니어링
  - 날짜 변수를 활용하여 연도, 월, 일, 요일 등 새로운 변수를 생성하여 모델의 정보량을 증가시켰습니다. 이를 통해 모델의 성능을 2% 향상시켰습니다.
- 다양한 머신러닝 분류 모델 실험
  - 실험 결과, Random Forest가 최적의 성능을 발휘하는 모델로 선정되었습니다.  
- 모델 튜닝
  - 5-겹 교차검증을 통해 모델의 일반화 성능을 평가했습니다.
  - 랜덤 서치를 통해 하이퍼파라미터 최적화했습니다. 이를 통해 모델의 성능을 0.3% 향상시켰습니다.  
- 최종 모델 성능 평가
  - 최종 모델의 Accuracy가 96%에 도달했습니다.
    
[![image](https://github.com/user-attachments/assets/bdc2d225-beae-4804-ad3b-db2d4107e6c0)](https://github.com/codnjs042/Data-Mining-Project1/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%A7%88%EC%9D%B4%EB%8B%9D%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20-%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%EC%9D%84%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%EC%83%81%EC%88%98%EB%8F%84%EA%B4%80%20%EB%88%84%EC%88%98%20%EA%B0%90%EC%A7%80.ipynb)
