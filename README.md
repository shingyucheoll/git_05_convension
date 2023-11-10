# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

1. 순서가 있는 목록
2. 순서가 있는 목록
   1. 순서가 있는 목록
   2. 순서가 있는 목록

- 순서가 없는 목록
  - 대쉬 (hyphen)
  * 더하기 (plus sign)
  - 별표 (asterisks)
  

### 링크(Links)

이미지 줄 바꿈은 스페이스바 3번

[구글](https://www.google.com/)  
[네이버](https://www.naver.com/)  
[구글홈페이지]<https://www.google.com/>  
[네이버홈페이지]<https://www.naver.com/>  
![김민재](https://search.pstatic.net/common?type=b&size=216&quality=100&direct=true&src=http%3A%2F%2Fsstatic.naver.net%2Fpeople%2F1%2F202206281819545621.png)  
[![google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_light_color_272x92dp.png)](https://www.google.com/)   
![cat](./asset/hipcat.jpg)   
![cat](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcReolvALGYkeNuU_E4QE2gsUCEwIfagQOyy3y3LqIOXNLAKABMr)
### 인라인 (inline) 코드 강조
`백티1개`는 `인라인 코드 강조 의미`

### 블록 (block) 코드 강조
```java
   public class Exma{
      public static void main(String[] args){
         System.out.println("exam");
      }
   }
```


### 표 (table)
|이름|성별|주소|
|---|---|---:|
|홍길동|남|경기도 화성시|
|김민재|남|서울시 서초구|
|비둘기|?|어느곳이든|

### 인용문(blockQuote)
> 타인의 말이나 문장을 직접 또는 간접적으로 가져온다.
>> 인용문1
>>> 인용문2
>>>> 어디까지돼
>>>>> 우다다ㅏ
>>>>> 우다다다다
>>>>>> ㅋㅋㅋ?
>>>>>>> !!!!
>>>>>>>> ??????
>>>>>>>>>>>>> @@@

### 수평선 (Horizental Rule) 3개이상
---
***
&&&
^^^
___

### 줄바꿈 (line breaks)
바다<br>
하늘   <!-- 띄어쓰기 2번이상 (그냥 다 3번으로 생각해~)>   
구름   

----
# TIL

## 리눅스 명령어

1. ls

   > list(목록)

2. cd
   change directory (작업 경로 변경)

3. rm
   remove (파일 삭제)

4. mkdir  
   make directory(작업목록 생성)

5. rmdir  
   remove directory(작업목록 삭제)

6. touch  
   파일생성

7. cat
   파일의 내용 출력

## Git

1. init  
   git 생성
2. add <파일명>  
   staging area로 이동
3. commit -m <메세지>  
   Repository로 이동
4. push <원격저장소><브랜치>  
   원격(GitHub)으로 이동
5. pull <원격저장소><브랜치>  
   원격에서 로컬로 복사
6. clone <원격저장소><브랜치>  
   원격에서 로컬로 복제

7. status  
   Staging Area의 상태
8. log  
   repository의 상태
