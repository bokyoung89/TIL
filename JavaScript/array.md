# 배열
## 정의 및 의의

* 정보를 담는 그릇.  서로 연관된 여러 정보들을 연속된 그릇에 담아 체계적으로 관리하는 도구이다.

* 왜 배열을 써야 하는가? 관계성이 있는 정보들을 list라는 이름으로 그룹핑하고, 특정한 정보를 표출할 수 있다.

## 문법
* JavaScript
```javascript 
list = new Array("one","two","three"); 
list[0];
```
* php
```php
$list = array("one", "two", "three"); 
$list[0];	
``` 
프로그래밍에서 숫자는 0부터 카운트 

## 예시
* JavaScript
```javascript
<script>
  list = new Array("one","two","three");
  document.write(list[2]);
  document.write(list.length);
</script>
``` 
* php
```php
<?php
  $list = array("one", "two", "three");
  echo $list[2];
  echo count($list);
?>
```
결과값 three3

# 배열+반목문
## 예시
* JavaScript
```javascript
list = new Array("최진혁", "최유빈", "한아람", "이고잉");
i = 0;
while(i < list.length){
  document.write(list[i]);
  i = i + 1;
  }
```
* php
```php
$list = array("최진혁", "최유빈", "한아람", "이고잉");
$i = 0;
while($i < count($list)){
  echo $list[$i];
  $i = $i + 1;
  }
```
length와 count는 배열 값의 갯수를 카운트하므로, 갯수가 늘어도 오류없이 출력된다.
