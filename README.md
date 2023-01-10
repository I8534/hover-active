# hover-active

  /* transition: all 400ms ease-in-out; -> transfrom scale */
  /* transition: border 400ms ease-in-out; */
  /* 밑에 호버는 색상 변환하는 것을 입력하는 것. 위의 트랜지션은 밑의 호버 속도 및 효과를 조정하기 위해 입력하는 값이다. 
  
    transfrom all, transfrom border 이것은 hover시에 변화가 올 때 모든 거에 적용시켜라 아니면 보더에 적용시켜라 이것을 의미한다.*/
}

/* .wrapper:hover {
  border: 10px solid red; 파란색에서 빨란색으로 변함
  이건 래퍼에 호버되었을 때 래퍼가 돌아가라는 의미이다.
} */

/* .wrapper:hover {
  transform:scale(1.2);
  /* 위의 트랜지션에 border 대신 all을 이용한다.
} */

/* .wrapper:hover .box{
  transform: rotate(45deg);
} */
/* .wrapper:hover .box 이 의미는 래퍼에 호버되었을 때 박스들이 돌아가라는 의미이다.
즉 아까랑 다르게 이때는 띄어써야 한다. 그래서 밑에 박스한테 트렌지션 값을 줘야 한다. */


a:active {
  color: red;
}

a 태그를 클릭했을 
