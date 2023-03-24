본 레퍼지토리에는 MovieLens 데이터셋을 이용한 추천시스템을 구현하였습니다.

# Data
  - MovieLens 1000K Dataset (출처 : https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset)

# Model
  - CB model
  - CF model
  - ALS model

# Conclusion
  - 영화 평점에 대한 데이터를 이용하여 3가지 모델을 통해 영화를 추천하고 성능평가를 했습니다.
  - 사람마다 영화 취향이 있기 때문에 비교적 단순하게 예측하는 모델이 구현되었습니다.
  - 시간에 따라 다음 영화를 잘 추천할 수 있는지 학습데이터와 검증데이터를 시간에 따라 나누어도 확인했습니다.
  - 추천은 현재의 상황을 보고 미래를 예측하는 것이기 때문에 Sequential 모델에 대한 학습이 필요하다고 생각되어 다음 프로젝트에서는 이를 이용한 추천 시스템을 개발하고자 합니다.
