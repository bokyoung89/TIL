# Chapter 1-8
## 첫번째 java프로그램 만들기1(메모장 이용) 
* javac.exe - 자바 컴파일러. 사람이 작성한 문장을 기계어로 번역 소스 파일(*.java)를 클래스 파일(*.class)로 변환
* java.exe - 자바 인터프리터. 자바 프로그램(클래스 파일)을 실행
* 클래스 - 자바 프로그램의 단위. 자바 프로그램은 클래스들로 구성

```
class 클래스 이름 {
	// 모든 문장은 클래스의 {}안에 있어야 한다. 
}
```

* main메서드 - 자바 프로그램의 시작점. 이 메서드 없이 실행불가  
**(메서드 - 다른 언어의 함수와 같다. 관련된 문장을 하나로 묶어놓은 것.)**

```
class 클래스 이름 {
	public static void main(String[] args){ //main메서드의 시작
	// 실행할 문장을 넣는다.(첫 문장부터 순서대로 실행)
}
```

# Chapter 1-9
## 첫번째 java프로그램 만들기2(이클립스 이용)
>> 이클립스에서 자바 프로그램을 작성하는 순서
1. 프로젝트를 생성한다.
2. 클래스를 생성한다.
3. 소스파일의 작성 후 저장(자동 컴파일됨)
4. 실행

>> Build 관련 메뉴 설명
* Build - 소스파일(*.java)로부터 프로그램을 만들어 내는 전 과정 
* Project > Build All - workspace의 모든 프로젝트를 빌드 
* Project > Build Project - 현재 프로젝트를 빌드(변경된 소스 파일만 새로 컴파일) 
* Project > Clean - 이전 빌드의 정보를 모두 삭제(모든 소스 파일을 새로 컴파일) 
* Project > Build Automatically - 소스 파일을 변경 후, 저장할 때 마다 자동 컴파일 

# Chapter 1-13~16 
## 이클립스 단축키, 자동완성기능, 주석
>> 단축키 바꾸기

window - preferences - General - Keys - edit - Apply and Close

>> Templates 바꾸기

window -  preferences - Java - Editor - Templates

>> 자동완성 체크 확인

window -  preferences - Java - Editor - Content Assist - Enable auto activation

# Chapter 1-17~19 
## 소스파일 가져오기, 내보내기
>> 소스파일 가져오기

explorer - 빈공간 - import - Existing Projects into Workspace - Select root directory - Options(Copy projects into workspace) - Finish

>> 소스파일 내보내기

Export - Archive file - 폴더 체크 - To archive file : Browse 선택 - Options(Save in zip format) - Finish
