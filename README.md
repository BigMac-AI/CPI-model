trainModel.py - 단일 cpi 예측 모델 학습
trainmodelforCore4.py - 상위 4개변수 모델 학습
trainmodelforCore4withoutSenti.py-감성분석 결과 제외 상위4개변수 모델 학습
trainModelWithoutSentiCPI.py - 감성분석 결과 제외 단일 cpi 예측 모델 학습

validation.py - 단일 cpi 예측
validationforCore4.py - 상위 4개변수 원본 vs 모델 예측 지수 비교
validationfroCore4withoutSenti.py- 감성분석 결과 제외 모델 사용 상위 4개변수 원본 vs 모델 예측 지수 비교
validationWithoutSentiment.py - 감성분석 결과 제외 모델 단일 cpi 예측

모든 실행 순서는 trainModelxxx -> validationxxxx 순으로 실행하면 됩니다. 
써놓은 순서대로 짝을 맞춰서 실행해야 모델이 매칭이 됩니다.
