# 1일차 강의

## Keyword : 데이터 저장



>### 변수
>
>데이터를 **하나** 저장하는 것
>
>```python
>dust = 70
>```



>### 리스트
>
>데이터를 **여러개** 저장하는 것
>
>```python
>number = [10, 20, 30]
>```



>### 딕셔너리
>
>**사전형 데이터**, Key : Value를 1:1로 대응시킨 형태
>
>```python
>dic = {Key1:Value1, Key2:Value2, Key3:Value3}
>```



>### 조건문
>
>* if
>    * 만약 ~~ 라면
>
>```python
>if dust == 70 :
>    print ("나쁨")
>```
>
>* if / else
>     * 만약 ~~ 라면 // 그것이 아니라면
>
>```python
>if dust == 70 :
>    print ("나쁨")
>else:
>    print ("좋음")
>```
>
>* if / elif / else
>    * 만약 ~~ 라면 / 만약 ~~ 이 아닌데 이것이라면 / 모두 아니라면
>
>```python
>if dust == 70 :
>    print ("나쁨")
>elif dust > 70 :
>    print ("매우 나쁨")
>else:
>    print ("좋음")
>```



> ### 반복문
>
> * while
>   * for문과 차이점 : **종료 조건**이 필요하다 `While True :`
>
> ```python
> n = 0
> while n < 3:
>     print(n)
>     n += 1
> ```
>
> * for
>   * while문과 차이점 : 종료 조건이 필요없다 ( 반복하는 범위를 지정하기 때문 )`for i in range (10) :`
> ```python
> for i in range (10):
>    print (i)
> ```



> ### 함수
>
> **반복 하고 싶은 코드** 덩어리를 모아 놓은 것
>
> ```python
> def add(a, b): 
>     return a + b
> 
> print(add(3, 4))
> ```



> ### 모듈
>
> 함수나 변수 등을 **모아 놓은 파이썬 파일**
>
> * 모듈을 사용하는 이유
>   1. 코드를 편하게 보기 위해
>   2. 배포를 편하게 하기 위해
>
> ```python
> import requests
> ```



___

___

# 2일차 강의

## keyword : Git, Github

>![git](C:\Users\multicampus\Desktop\git.png)
>
>## git 
>
>* **분산버전 관리 프로그램**
>* 코드의 히스토리(버전)을 **관리하는 도구**
>* 개발되어온 **과정 파악 가능**
>* 이전 버전과의 변경 사항 **비교 및 분석**
>
>
>
>
>
>### github
>
>![github](C:\Users\multicampus\Downloads\github.png)
>
>
>
>*  **git 기반**의 **저장소 서비스**

___



>**GUI** : 그래픽을 통해 사용자와 컴퓨터가 상호 작용 하는 방식
>
>**CLI** : 명령어를 통해 사용자와 컴퓨터가 상호 작용하는 방식
>
>![gui-operating-system4](C:\Users\multicampus\Desktop\gui-operating-system4.png)
>
>​																										[출처 : GUI Operating System](https://www.javatpoint.com/gui-operating-system)
>
>### CLI
>
>* 절대경로
>  * 루트 디렉토리부터 목적 지점까지 거치는 모든 경로를 전부 작성한 것
>  * 윈도우 바탕 화면의 절대 경로 - C:/Users/ssafy/Desktop
>* 상대경로
>  * 현재 작업하고 있는 디렉토리를 기준으로 계산된 상대적 위치를 작성한 것
>  * 현재 작업하고 있는 디렉토리가 C:/Users일 때
>  * 윈도우 바탕 화면으로의 상대 경로는 ssafy/Desktop
>
>> ``./ : 현재 작업하고 있는 폴더, ../ : 현재 작업하고 있는 폴더의 부모 폴더``



___

>### 마크다운
>
>* **텍스트 기반**의 가벼운 마크업(Markup) [태그(tag)를 이용하여 문서의 구조를 나타내는 것] 언어
>* 문서의 구조와 내용을 같이 쉽고 빠르게 적고자 탄생
>
>>
>>
>>***주요 기능***
>>
>>
>>
>>1. 제목 헤더 # ~ ######
>>2. 리스트 * - /
>>3. 코드 블럭 ```python
>>4. 주소 \[string](url)
>>5. 이미지 \![string]\(img_url)
>>6. 텍스트 강조 \*기울기* \**진하게** \*\*\*진하고 굵게\*\*\* (- 나 + 로도 혼용 가능) \`텍스트배경` \~~취소선~~ 
>>7. 수평선 \--- 혹은 \___



___

___