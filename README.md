# Dacon 구내식당 식수 인원 예측 AI 경진대회 코드
(참고했던 코드, 직접 작성한 코드 포함)

private 기준 139/481 기록 했으며, 아직 더 학습이 필요함

참고했던 코드로 인해 점수 상승에 큰 도움이 되었음.

metrics 사용(MAE), 모델에 직접 적용하는데 많은 오류나 시행착오가 있었음.

<strong>private 상위권에 위치한 사람들의 코드를 보며 아이디어나 metrics 사용하는법, 적용하는 법을 배워야할것!</strong>

---

나와 다른 아이디어로는 1. 밥, 국, 메인 반찬으로 메뉴를 나누어서 encoding을 진행을 하였음, 2.metrics는 gridsearcv 시에 socring = 'neg_mean_squared_error' 옵션만 적용

present 특성을 만들었지만 사용하지는 않은 것으로 보임
