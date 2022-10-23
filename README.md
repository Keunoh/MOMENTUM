# MOMENTUM
This is my first JS Project! So Excited~! 

1. Basic Information 
	자바스크립트는 브라우저에 내장되어있다!   
	Browser는 HTML을 불러오고 HTML은 CSS와 JS를 불러온다   
	HTML이 접착제 느낌

	* always const, sometimes let, never var  
	boolean -> true, false  ( 1, 0 )  
	null -> 아무것도 아닌 값이 채워져 있다.  
	undefined -> 변수는 정의 되어있지만 값이 정의되지 않았다.  
	NaN -> Not A Number  

	* const days [ ] -> array(list) 만들기  
	array.push() -> 배열에 데이터를 추가할 수 있다.

	* const player {} -> object 만들기  
	안에 항목들을 property라고한다.  
	const로 객체를 만들더라도 그 안의 property를 변경시킬 수 있다.  
	그러나 const 객체 자체를 바꾸는 것(boolean타입이라던가, int 타입이라던가)
	은 불가능하다.

	* function 함수이름(파라미터(그냥 변수 이름만)) { 원하는 기능 }  
	ex) function sayHello(name){  
		console.log("Hello! " + name);  
	}
	
	* 함수에서 값을 리턴 받을 수도 있다.  
	ex) function add(a, b){  
		return a + b;  
	}  
	return이 되는 순간 함수는 종료된다.

	* object안에 function 넣기  
	ex) const player = {  
		name: "keunoh"  
		sayHello: function () {  
			console.log("Hello!");  
		}  
	};

2. JavaScript와 document  
	f12에서 document(해당 페이지의 html의미)를 입력하면 html객체를 볼 수 있다.  

	* console.dir(document) 하면 객체를 좀더 상세히 볼 수 있다.  
	자바스크립트에서 html에 접근할 수 있는 방법  
	
	* 해당 객체의 property에 값을 arrangement 할 수도 있다!!  
	ex) document.title = 'Hello from console' <- 웹페이지 탭 이름 변함   
	document.location <- html path 알 수 있다.  
	document.body <-  body부분 확인할 수 있다.  
	document.getElementById("") <- 괄호안에 입력한 element id구간을 가져온	다.  
	document.getElementsByClassName("") <- 클래스 네임으로 여러개 가져옴  
	document.getElementsByTagName("h1") <- 태그네임으로 가져옴  
  
	* 노마드가 좋아하는 방법  
	ex) document.querySelector(".hello h1") -> className hello이고 h1가져옴
	querySelector는 element를 css방식으로 검색할 수 있다. 
	클래스 이름이 중복되는 경우 가장 첫 번째 element가져온다.