# 조건문의 활용
- **질문 : id가 "night_day"인 엘리먼트의 value 값을 알아내려면? if ( value )**
```
검색어 : javascript element get value
결과 : document.querySelector('#night_day').value  
```

*이 코드를 통해 id값이 #night_day인 태그의 value값을 가져올 수 있다.*  

- **property란? 속성 이란 뜻으로, JS에서는 객체 내부의 속성을 의미합니다.**

# 리팩토링
- 공장에 다시 보내서 개선한다?
- 동작은 그대로 두고 코드를 효율적으로 만들어 가독성은 높이고 유지보수 편리하게, 중복 코드를 낮추는 개선 작업.   
좋은 프로그램을 만들 수 있다.  

## 중복의 해결 1 )   
- onclick과 같은 이벤트 안에서 실행되는 코드들은 코드가 속해있는 태그를 가리키도록 약속되어있는 특수한 키워드   
**= 바로 this**

- 코딩을 잘하는 방법? 중복을 최대한 없애라.
여러 기능이 출현한 이유는 중복과 관련 가능성이 크다.  

## 중복의 해결 2) 
- ```document.querySelector('body')```를 변수를 활용하여 중복을 줄이고 유지보수를 높인다. 
- target은 'body' 태그를 가리킴.
- ```var target = document.querySelector('body')```  
- **즉, 변수를 활용하면 코딩을 하는데 큰 도움이 된다.**
