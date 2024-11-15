Font 적용하는 법.

이슈

Base Line


1. 초기

Font-size
px - Absolute Unit(px)
em - Relative Unit : equal to capital M
부모 요소, 혹은 현재 요소의 font-size * em
em: 부모 요소의 폰트 크기에 상대적이며 
중첩된 구조에서 값이 누적될 수 있다. 그래서 
em은 복잡해질 수 있기 때문에 rem을 많이 쓴다.

rem - Relative Unit
root(주로 body)의 포트 크기에 상대적인 값
문서 전체에서 일관된 크기를 유지합니다.

결론, 
Root는 ViewPort로 정하고 나머지는 ViewPort의 상대적
크기로 REM을 쓰는게 합리적이다.
