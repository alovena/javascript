<h1 align="center">자바스크립트 1일차</h1>
:bulb: :duck: :dog: :note: :happy:
  
  
> :note: Old Javascript 는 ```javascript<script type='text/javascript'></script>```를 사용
> 위의 속성은 필요 없으며 기본적으로 html안에 내장되어 있다.

# **자바 스크립트는 이것부터 시작이다.-JS를 불러오는 3가지**
## 1. 헤더에 넣기
```javascript
<head>
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head>
```  

- 헤더에 넣는 방식은 버튼이 생성되기 전 script를 생성하므로  
- 클릭시 사용이 바로가능!  
## 2. 바디에 넣기
```javascript
<body>
<p>...</p>
<button>...</button>
...
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</body>
```
  
- 바디에 넣는 방식은 버튼을 생성후 스크립트를 생성 
- 클릭시 사용이 바로가능!  
- 코드가 지저분하게 보일 수 있다.  
## 3. 외부파일로 호출 하기
```javascript
<script src="myScript.js">
</script>
```
- 외부에서 가져오는것은 html 코드와 독립성을 증가
- 가독성과 유지보수가 편하고
- 자바스크립트의 캐쉬가 로드를 더 빠르게 할 수 있다.

>:note: 이때 <script src=""></script> src안에 url 주소가 들어가도  
>가능하다!!

# **자바스크립트 click Event**
```html
<button onclick="onClickShowTime()">click button</button>
```


```javascript
<script>
function onClickShowTime(){
    document.getElementById('demo').innerHTMl=Date()
}
</script>
```
# The Result
![ex1](https://user-images.githubusercontent.com/32647144/65873791-0560cf00-e3bf-11e9-81b7-22deb002cde5.png)

# **Javascript can change HTML Styles CSS**
```html
<p id='demo'>Hello worlds</p>
```
```javascript
documnet.getElemntById('demo').style.fontSize="32px"
```
# The Result
![ex2](https://user-images.githubusercontent.com/32647144/65873998-9c2d8b80-e3bf-11e9-850f-ae2888853233.png)
