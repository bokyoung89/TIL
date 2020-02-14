# 배열이란?  
데이터가 많아짐에 따라 많은 데이터 중 서로 연관된 데이터를 정리 정돈해서 담아주는 일종의 수납 상자  
- 예제
```
<script>	
	var coworker = ["egoing", "shin"];
	document.write(coworker[0]);
</script>
결과값 : egoing
``` 
### 질문
#### 배열의 갯수는 몇 개인가?  
  * javascript array count?   
  = array.length()
#### 데이터를 추가하는 방법?
  * javascript array add data?  
  = array.push('data')


# 반복문이란?
순서대로 실행되는 프로그램 순서의 흐름을 제어하는 제어문이다. if문(조건문)과 함께.    

**반목문이 언제 종료될 것인지를 잘 정하는 것이 중요**


# 배열과 반복문
**배열**은 순서대로 서로 연관된 데이터를 정리정돈 + **반복문**은 순서대로 배열에 담긴 데이터를 하나씩 꺼내서 자동화된 처리를 할 수 있는 문법.     

**두 개의 기능은 환상의 콤비라 할 수 있음.**

### 질문
#### 자바스크립트 element 다수를 css selector로 가져오는 방법은?
  * javascript get element by css selector multiple?  
  = document.querySelectorAll()  
**querySelectorAll()** 은 특정 css 선택자를 가진 모든 요소를 배열로 가져오는 매서드.  

## 결론
반목문을 사용하면 아주 많은 일을 손쉽게 할 수 있다.   
컴퓨터는 많은 경우 연관된 데이터를 배열의 형태로 우리에게 돌려주므로.
