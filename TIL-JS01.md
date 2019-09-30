<h1 align="center">자바스크립트 1일차</h1>
:bulb: :duck: :dog: :note: :happy:

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

# **Javascript can change HTML Styles CSS
```html
<p id='demo'>Hello worlds</p>
```
```javascript
documnet.getElemntById('demo').style.fontSize="32px"
```