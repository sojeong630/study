# 파트 1 시작하기
Javascript 의 특징
-	HTML+CSS와 함께 사용해 client side 웹 프로그램을 작성할 수 있다

alert 명령어
-	alert뒤에 따라오는 괄호 안에 들어있는 메시지를 브라우저 경고창에 띄워주는 명령어
-	alert(“Hello world”); ~~~~<script src=”파일명”></script>

개발자 도구 (Developer Console)
- 브라우저의 우측 상단 메뉴에서 더보기, 개발자 도구 메뉴를 이용해 활성화
- 여러 탭 중 console 탭을 사용해 console 을 확인 가능

console.log 명령어
- console.log 뒤에 따라오는 괄호 안에 들어있는 메시지를 콘솔창에 출력하는 명령어
- console.log("Hello developer console");

# 파트 2 변수
변수
- var variable_name=value;

prompt() 명령어
- promprt 뒤에 따라오는 괄호 안에 들어있는 메세지를 사용자에게 보여주고, 문자열을 입력받는 명령
- var name=prompt("이름을 입력해 주세요");

console.log 명령어
- 괄호 에 여러개의 메시지 가능 
- console.log("홍길동", "님 안녕하세요")

# 파트 3 자료형
자료형 
- 변수에 저장할 있는 값의 종류

typeof() 명령어
- typeof 뒤에 따라오는 괄호 안에 들어있는 변수의 type을 알려주는 명령어
- var a=100;
- console.log(a,typeof(a));
- //100 "number"라고 출력

number 자료형
- 숫자를 나타내는 형, 실수 정수 상관없음
- parseInt, parseFloat 명령어 : 입력된 명령어에서 정수, 실수 부분을 인식해서 변수에 저장 // 문자열의 시작부터 인식 

Object
- 단순 자료형보다 더 복잡한 자료를 표현할 때 사용
- 중괄호 {} 를 사용해 정의 가능
<img width="254" alt="1" src="https://user-images.githubusercontent.com/62346198/92322870-f377b980-f06e-11ea-894b-1ca7f16e94ba.PNG">

# 파트 4 연산자
Math 관련 명령어
- Math.pow(A,b) : A의 B승을 구해 줌
- Math.sqrt(A) : A의 제곱근을 구해 줌
- Math.random() : 0~1 사이의 임의의 난수를 발생시켜 줌

함수
