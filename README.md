# positioning

1. static 은 웹사이트의 기본(default)값 left, right, top, bottom 등 위치 속성은 무시됨 

2. relative 는 있는자리 기준으로 left, right, top, bottom
값을 통해 움직인다

3. absolute 는 부모 절대값 기준으로 left, right, top, bottom
을 이용해 주어진 위치로 움직인다
(단 부모태그가 relative, absolute, fixed 중 하나여야함.
만약 부모태그가 해당 속성을 가지고 있찌 않다면 body태그 기준으로
움직인다 왜냐하면 body태그는 relative를 기본 속성으로 가지기 때문.)

4. fixed 는 absolute 와 비슷하지만 스크롤을 내려도 그 위치에 고정, 무조건 브라우저 창 기준이다

5. sticky 는 relative와 비슷하지만 스크롤을 내리면 fixed처럼
   그 위치에 고정
