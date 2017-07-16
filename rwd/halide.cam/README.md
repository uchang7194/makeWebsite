#반응형 그리드 레이아웃 모듈 만들기
1. toggle grid 
2. 기본적인 mobile, tablet, desktop columns와 offset 만들어 놓음.

## sass/rwd 
1. _rwd-settings.scss: 반응형 초기설정값 
2. _rwd-grid.scss: 각 device별 column/ offset 설정
3. _rwd-toggle-grid.scss: 각 device별 가이드 라인
4. utills/_rwd-utill-function: _rwd-grid.scss에서 설정할 때 필요한 함수
4. utills/_rwd-utill-mixin: _rwd-grid.scss에서 설정할 때 필요한 믹스인


# 반응형 제작시 햇갈리는 점.
지금 제작하고 있는 halide사이트는 모바일 반응형이 컨텐츠가 있는 영역이 고정넓이를 가지고 가운데 정렬이 되어 있는 형태이다. 하지만 나는 반응형 그리드 레이아웃 형식을 가지고 만들고 있는데 각 mobile, tablet의 컬럼의 넓이를 가변적인 넓이(%)로 맞춰놓고 넓이를 주었기 때문에 브라우저 창의 넓이가 좁아지고 넓어질 때마다 컨텐츠의 크기 또한 변화가 이루어져 정신이 사나워 지는 느낌이다.
그럼 이때 생각해 본 것이 반응형을 제작할 때 mobile, tablet, desktop의 넓이를 고정넓이로 만들게끔.
