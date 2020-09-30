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

<img width="324" alt="캡처" src="https://user-images.githubusercontent.com/62346198/93765926-a1c75580-fc50-11ea-8e1b-774dcda00b90.PNG">

# 파트 5 String
문자열 길이 알아내기 : str.length 

문자열 붙이기
- str1.concat(str2)
- str1+str2

특정 위치 문자열 알아내기
- str.charAt(0) : charAt 함수 사용
- str[0] : 대괄호 사용
- str.substring(pos1, pos2) : pos1부터 pos2 까지의 문자열 반환
- str.substr(pos, length) : pos부터 length길이 만큼의 문자열 반환

문자열 검색하기
- indexOf(str) : 처음 나온 문자열 위치 반환
- lastIndexOf(str) : 마지막으로 나온 문자열 위치 반환
- 존재하지 않으면 -1 반환

# 파트 6 배열
배열 ex) var arr=[]; , var arr=[1,2,3,4,5];
- 어떤 자료형이든 상관 없음, 서로 다른 자료형이여도 괜찮음

배열 엘리먼트 다루기
- arr.pop() : 맨 뒤에 엘리먼트 삭제
- arr.shift() : 제일 처음 엘리먼트 삭제
- arr.push() : 뒤에 엘리먼트 추가
- arr.unshift() : 앞에 엘리먼트 추가
- arr.reverse() : 배열 뒤집기
- arr.sort() : 배열 정렬하기

배열 다루기 
- arr1.concat(arr2) : arr1과 arr2 붙임  // 붙여서 리턴만 해주고 변환은 X
- arr.indexOf(element) : element가 있는 첫 위치를 검색
- arr.lastIndexOf(element) :  element가 있는 마지막 위치를 검색

split 함수 : 문자열을 구분자로 나눠 배열로 변환

# 파트 7 조건문
if, else if, else, switch

# 파트 8 반복문
while문
- break : 즉시탈출
- continue : 남은 반복 실행될 코드 skip

do while문
- 한번은 무조건 실행되고, 이후에 반복할지 말지를 결정

for in문
- 객체의 엘리먼트에 접근할 수 있는 반복문
