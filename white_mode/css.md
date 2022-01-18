<!-- *** #6667ab = (102,103,171) / #1f0937 = (31,9,55) / #ffffff = (255,255,255) / #000000 = (0,0,0)
++ #E2C0BE (연한 핑크) = (226,192,190) / #E087B5 (진한 핑크) = (224,135,181) -->

계산기
<!-- - width : 432px
- height : 768px -->
<!-- ** background color : (255,255,255) -->

<!-- 버튼들 감싸는 wrapbox
- width : 320px
- height : 370px -->

계산기 버튼
<!-- - 기본 그라데이션 원들 : width, height: 60px -->
<!-- ** 그라디언트 (기본) Radius 바깥쪽-안쪽 : (255,255,255)(opacity : 0%) - (226,192,190)(opacity : 100%) (중심점 왼쪽부터 60%) -->
<!-- ** 그라디언트 (hover) Radius 바깥쪽-안쪽 : [전체 opacity 45%로 조정] (226,192,190)(opacity : 100%) - (224,135,181)(opacity : 100%) (중심점 왼쪽부터 40%) -->
<!-- ** 그라디언트 (active)
https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Images/Using_CSS_gradients
-> 링크의 stacked radial gradient 참고 -->

<!-- 베이스 : (226,192,190)(opacity : 100%) - (224,135,181)(opacity : 100%) (중심점 왼쪽부터 40%)
이 위에 3색이 더 올려져 있는 형태! -->
<!-- - 상단 : #fff3b4(255,243,180) 노랑 -->
<!-- - 오른쪽 옆 : #E087B5(224,135,181) 진한 핑크 (구현하면 좋겠지만 없어도 무방..)
- 하단 : #6667ab(102,103,171) 베리페리
(메쉬툴로 작업한지라 퍼센트는 기입이 어려움 ㅠ 눈으로 보고 조정해야할듯) -->

<!-- => stacked radial gradient 로 구현이 어려우면 그냥 bcakground image로 넣어도 됩니당 파일 첨부할게용~
(asset2(hover), asset3(active)) -->


  ++ 고려중인 추가사안 : hover 잔상
  - 잔상 1 : Radius 바깥쪽-안쪽 : [전체 opacity 20%](226,192,190)(opacity : 100%) - (224,135,181)(opacity : 100%) (중심점 왼쪽부터 40%)
  - 잔상 2 : Radius 바깥쪽-안쪽 : [전체 opacity 10%](226,192,190)(opacity : 100%) - (224,135,181)(opacity : 100%) (중심점 왼쪽부터 40%)

- 숫자 0 버튼 : width : 100px / height : 45px <<더 나은 방향 있으면 수정하기>>
- (기본 / hover) : border : 3px solid (226,192,190)
- (active) : background image (asset4)

글자 사이즈
- 전체식 : 21pt
- 결과값 : 36pt
- 버튼 내부 숫자 폰트 사이즈 : 24pt
- 버튼 가운데에 폰트 정렬

background(시안1) : 그라디언트 Linear 위-아래 : (255,255,255) - (226,192,190) (opacity : 둘다 100%) (중심점 75%)
** 내 개인적 취향인 시안입니당 회의 결과에 따라 변경될 수 있음 주의 

--------------------------

계산기로그
width : 582px
height : 768px

