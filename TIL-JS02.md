<h1 align="center">자바스크립트 1일차</h1>
:bulb: :duck: :dog: :note: :happy:
  
# 자바스크립트 유용한 출력함수!
> 로그캣 비슷한 역할로 테스트 및 디버깅용도로 주로 쓰인다.  
>```javascript
> <script>
>  documnet.getElementById("demo").innerHTML="string" 
>  documnet.write("text") 
>  window.alert("text")
>  console.log("log")
> </script>
> ```
> 를 사용한다.  
> :note: write를 이벤트 처리할시 기존의 html 코드는 지워지고 새로운 코드가 생성된다.
> ```html
> <p>hello world</p>
> <button id=btn click='onclickEvent'>click</button> 
>```
> ```javascript
> <script>
> function onclickEvent(){document.write('hello')}
> </script>
> ```
> :note: 버튼 클릭시 hello 만 생성!!

