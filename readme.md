## 강의로 알게 된 것들
### 5-1강_Position
- position: relative; // 내가 있던 위치에서 밀리는거, 있는 자리 기준에서 옮김
   position: absolute; // 부모 절대값 기준으로 옮김, 절대위치 (내 화면에서 x,y 좌표), 스크롤바 움직여도 그 자리 그대로에 있다
   position: sticky; // 일단 그 위치에 있고 스크롤바를 내리면 고정
   position: fixed; // 내가 스크롤바를 움직여도 absolute 위치에서 고정!
   position: static; // 웹브라우저의 디폴트값, static은 left, top, right, bottom을 사용 안함, 딱히 기억할 필요는 없다
   * 단! 여기서 부모란?: 부모 태그가 relative, absolute, fixed 속성 중 하나여야 함. 만약 부모태그가 해당 속성을 가지고있지 않다면 body태그 기준으로 움직임 왜냐하면 body태그는 relative를 기본 속성으로 가지고 있기 때문이다 

### 5-2강_flexbox
- display: flex; // 세로가 가로정렬이 된다
        justify-content: flex-start;
                         flex-end;
                         center; // 알아서 스크린 사이즈에 맞춰서 정중앙!
                         space-between; // 자기가 알아서 요소들 사이에 공간을 줌
                         space-around; // 요소개 3개라고 가정하면 양끝에도 공간! 즉 4개 공간생김
        
        align-items: ; // 수직으로 왔다갔다, height 100vh로 해야 전체적으로 수직 이동 가능, space-between around 는 없다

        flex-direction: column; // justify-content은 세로로 align-items는 가로로 바뀜

flexbox연습하는 웹사이트🐸: https://flexboxfroggy.com/#ko

## 개발일지

## 더 알아야 할 것
- align-self : align-items는 전체를 움직이는 반면 align-self는 각각 요소 하나를 움직임
- flex-direction 사용

## 의문사항