RNN과 konlpy를 통한 영화 리뷰 긍부정 판단

1. ratings_train.txt(review와 긍부정 label로 구성)를 불러와 konlpy를 통해 한글 형태소 별로 토큰화
2. 두 가지 RNN model(SimpleRNN, GRU + LSTM)을 통해 학습
3. 성능 비교
4. 실제 리뷰(example: eternals.txt)의 긍부정 확률을 판단

