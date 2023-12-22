# CodeFugPortFolio Project 

* ## Loading
  * 처음엔 display:grid인 상태로 화면을 채우다가 js를 활용하여 load event가 일어나면 2초 후에 사라지도록 하여  로딩 화면을 구현하였다.
  
* ## body
  * grid를 사용하기 전에 레이아웃을 미리 짜놔야 나중에 다시 갈아엎는 일이 없다. 특히나 1fr 2fr 처럼 비율이 정해질 경우 content가 그 크기를 벗어나면 컨테이너에서 content가 나와버리는 상황이 발생한다. 미리 생각해서 auto로 해놓는 방법이 좋다.