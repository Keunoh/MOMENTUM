# MOMENTUM
This is my first JS Project! So Excited~! 

1. Basic Information 
	자바스크립트는 브라우저에 내장되어있다!   
	Browser는 HTML을 불러오고 HTML은 CSS와 JS를 불러온다   
	HTML이 접착제 느낌

	: always const, sometimes let, never var  
	boolean -> true, false  ( 1, 0 )  
	null -> 아무것도 아닌 값이 채워져 있다.  
	undefined -> 변수는 정의 되어있지만 값이 정의되지 않았다.  
	NaN -> Not A Number  

	: const days [ ] -> array(list) 만들기  
	array.push() -> 배열에 데이터를 추가할 수 있다.

	: const player {} -> object 만들기  
	안에 항목들을 property라고한다.  
	const로 객체를 만들더라도 그 안의 property를 변경시킬 수 있다.  
	그러나 const 객체 자체를 바꾸는 것(boolean타입이라던가, int 타입이라던가)
	은 불가능하다.

	: function 함수이름(파라미터(그냥 변수 이름만)) { 원하는 기능 }  
	ex) function sayHello(name){  
		console.log("Hello! " + name);  
	}
	
	: 함수에서 값을 리턴 받을 수도 있다.  
	ex) function add(a, b){  
		return a + b;  
	}  
	return이 되는 순간 함수는 종료된다.

	: object안에 function 넣기  
	ex) const player = {  
		name: "keunoh"  
		sayHello: function () {  
			console.log("Hello!");  
		}  
	};