# 2023-Inha-AI-Challenge
2023 인하 인공지능 챌린지  
- 멀티 모달을 이용한 추천 시스템 구현
- AutoRec을 이용한 모델: 사용자-아이템 상호작용 행렬(sparsity 약 99.9%)을 잠재요인 분석을 통해 아이템 추천

- Dataset Info.  
  - train.csv: user_id, item_id, rating(1~5)
  - image.npy: item_id와 매핑되는 item의 이미지 feature 데이터 (I,4096)
  - text.npy: item_id와 매핑되는 item의 리뷰 feature 데이터 (I,384)
- 제출 파일 형식: train.csv에 존재하는 모든 user_id별 추천 아이템 리스트 우선 순위 상위 50개 순서로 예측 ((user_id, item_id)인 column이 2개인 csv 형태로 제출)
