## Matrix_Factorization
---------------------------
>아래 내용"만" 참고하여 다음 업무를 수행할 것
  - Matrix Factorization 을 numpy 만으로 구현할 것
  - 영화 시청 이력을 기반으로 영화 평점 예측 모델 구현
  - 데이터 셋은 아래 것을 사용할 것: https://grouplens.org/datasets/movielens/
  - 학습 데이터:  timestamp >= 1104505203 ~ timestamp <= 1230735592
  - 평가 데이터: timestamp >= 1230735600 이후
  - 최종 산출물 평가데이터에 대한 아래 결과와 함께 구현 코드: 'userId', 'movieId', 'predicted rating', 'timestamp'
  - 구현의 성능 향승을 위한 동시성 사용방안에 대해 고민할 것

### 참고
* [Netflix 추천시스템](https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf?fbclid=IwAR1Ff0kNw5Q8FcAlseaifAa6FQ4e4CynoKEFW4yMWrSCDdnJhLGEEv2vtKc)

* [Wikipedia : matrix factorization](https://en.wikipedia.org/wiki/Matrix_factorization_(recommender_systems)#:~:text=Matrix%20factorization%20is%20a%20class,two%20lower%20dimensionality%20rectangular%20matrices.)

* [How does Netflix recommend movies? Matrix Factorization](https://www.youtube.com/watch?v=ZspR5PZemcs&feature=youtu.be&fbclid=IwAR1s02b72t_kUUXKRmvcJZMjEwAXlHhrTdVKMJr8svuyTXSgOI17hrb8_rE)
