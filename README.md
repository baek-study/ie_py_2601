# 파이썬 프로그래밍 입문 - 화 15:00
산업경영공학과 학생 대상 파이썬 입문 수업시간의 요약 및 코드 배포를 위한 학습 공간입니다. 
<hr size = "10px", width ="500px">



## [🐍1주차 강의 &nbsp;-&nbsp; 파이썬 소개 및 첫걸음](https://github.com/baek-study/ie_py_2601/blob/main/source/week1_exam.ipynb)

### [🔹 파이썬 소개](https://github.com/baek-study/ie_py_2601/blob/main/source/week1_exam.ipynb)
<ul>
<li><b>특징:</b> 인터프리터 언어, 객체지향 언어 </li>
<li><b>통합 개발 환경:</b> IDLE, Colab, Jupyter Notebook 등 </li>  
</ul>

### [🔹 실습 환경 세팅 (Google Colab)](https://github.com/baek-study/ie_py_2601/blob/main/source/week1_exam.ipynb)
<ul>
<li>구글 코랩(Colab): 웹 브라우저 바로 코드를 작성하고 실행 </li>
<li>구글 드라이브와 연동되어 실습 파일(사본) 자동 저장</li>  
</ul>

### [🔹 실습 파일 및 배포 코드](https://github.com/baek-study/ie_py_2601/blob/main/source/week1_exam.ipynb)
<ul>
<li>1주차 실습: "hello world" 출력 </li>
</ul>

<br>

## [📦2주차 강의&nbsp;-&nbsp;변수와 자료형](https://github.com/baek-study/ie_py_2601/blob/main/source/week2_exam.ipynb)

### [🔹 변수(variable)](https://github.com/baek-study/ie_py_2601/blob/main/source/week2_exam.ipynb)
<ul>
  <li><b>변수</b> : 데이터를 저장하는 공간 </li>
  <li>이름 규칙 : 알파벳, 숫자, 밑줄(_)로 구성 <br>
  - 시작시 숫자 안됨, 공백/예약어 안됨 </li>
   <li><b>변수이름 = 값</b> <br>
     ex) x = 100 &ensp; #변수이름은 왼쪽
    </li> 
</ul>

### [🔹 자료형(Data Type)](https://github.com/baek-study/ie_py_2601/blob/main/source/week2_exam.ipynb)
<ul>
  <li> 정수형(<b>int</b>): 123</li>
  <li> 실수형(<b>float</b>): 3.14</li>
  <li> 문자열(<b>str</b>): "hi", 'hi'</li>
  <li> 논리형(<b>bool</b>): True, False</li>
  <li> 자료형 확인 함수: <b>type</b>(1234) </li>
</ul>

### [🔹 표준출력함수 print()](https://github.com/baek-study/ie_py_2601/blob/main/source/week2_exam.ipynb)
<ul>
    <li> 문자열 출력: print('hello') </li>
    <li> 다양한자료형: print(1004); print(3.14);</li>
    <li> 여러개 값: print(2, '+', 3)&ensp;#<b>콤마</b> 이용</li>
    <li> 출력제어문자: print('탭키 <b>\t</b> 줄바꿈 <b>\n</b> ')</li>
  </li>
</ul>

### [🔹 산술 연산자](https://github.com/baek-study/ie_py_2601/blob/main/source/week2_exam.ipynb)
<ul>
  <li> + - * / (사칙연산) <br> 
  - 나눗셈 결과는 실수 &ensp; ex) 2/2 = 1.0 </li>
 <li> //(몫), %(나머지), **(제곱) <br>
  - 몫(정수)&ensp; <b>//</b> &ensp; ex) 5//3 = 1<br>
  - 나머지&ensp; <b>%</b> &ensp; ex) 5%3 = 2</li>
</ul>

<br>

## [🔄3주차 강의&nbsp;-&nbsp;입력과 형변환]()

### [🔹 표준 입력함수 input()&형변환]()
<ul>
   <li>키보드를 통해 입력한 값을 '문자열'로 반환</li>
    <li> msg = input('안내메시지')&ensp;#문자열로 반환</li>
    <li> age = int(msg)&ensp;#정수변환</li>
    <li> fage = float(msg)&ensp;#실수변환</li>
</ul>

### [🔹 대압/복합대입 연산자](h)
<ul>
  <li> x = 10 # 왼쪽 변수공간에 오른쪽 값 할당 </li>
  <li>다중 할당 : x=y=z=1 <br>
    -  x,y = 1, 2 # 여러 개 값을 각 변수에
  </li>
  <li>자기 할당 : x = x + 3  </li>
  <li>복합대입 : x += 3 &ensp;# x=x+3 <br>
  - 할당과 산술/기타 연산자 결합 
  </li>
</ul>

### [🔹 서식 : f-문자열]()
<ul>
  <li> f'..{표현식}..' # 중괄호 사용  <br>
    ex) print(f'hi. {name}, age {25}') </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li> 
</ul>
<br>

## [📋4주차 강의&nbsp;-&nbsp;리스트]()

### [🔹 리스트 기본 구조]()
<ul>
<li> 여러 데이터를 하나로 묶어 순번에 따라 저장  </li>   
<li> temps=[28, 31, 33, 35, 27] # 대괄호사용 </li>
<li> 양의 인덱스: 첫요소부터 0부터 시작 </li>
<li> 음의 인덱스: 끝요소부터 0-1터 시작 </li>
</ul>

### [🔹 리스트 인덱싱&슬라이싱]()
<ul>
<li>인덱싱: temps[3], temps[-1]  </li>
<li>슬라이싱: temps[2:5]  &ensp;#시작에서 끝-1 까지 </li>
<li>수정1: temps[3] = 5 &ensp;# 인덱싱 이용한 수정 </li>  
<li>수정2:  temps[2:5] = [1, 2] &ensp;# 슬라이딩 이용힌 수정 </li>    
<li>단순할당 : list1 = temps &ensp;# 같은것 가리킴</li>  
<li>복사 : list2 = list(temps) &ensp;# temps[:] 새로운 리스트 </li>  
</ul>

### [🔹 리스트 연산&메소드]()
<ul>
 <li> 연산 (+, *, in, == )<br>
   - 결합 : [1,2]+[3,4,5] <br>
   - 반복 : [1,2]*3 <br>
   - 멤버쉽 1 in [1,2]  &ensp;# not in<br>
     </li> 
  <li> 추가 : temps.append(5)  </li>  
  <li> 삽입 : temps.insert(1, 100)   </li>  
  <li> 삭제 : temps.remove(100)   </li>  
  <li> 삭제 : t = temps.pop(0)   </li>  
  <li> 검색 : temps.index(31) </li>
</ul>
<br>

## [📋5주차 강의&nbsp;-&nbsp;조건문]()

### [🔹관계 연산자 & 논리연산자]()
<ul>
<li><b>관계(비교)연산자</b> <br>
  &ensp;  ==(같다) != (같지않다) <br>
  &ensp;  > < >= <=  ( =가 항상 뒤)  <br>
</li>  
<li><b>논리 연산자</b> <br>
  &ensp;  and, or, not <br>
</li>  
</ul>


### [🔹단순 if(if~ - 선택 명령 1개)]()
<ul>    
  <li><b>if</b> score >= 60 <b>:</b>&ensp;<br>
    &ensp;&nbsp;  print('pass') <br>
  </li>
</ul>

### [🔹선택 if(if~else - 선택 명령 2개)]()
<ul>    
  <li><b>if</b> score >= 60 <b>:</b>&ensp;<br>
    &ensp;&nbsp;  print('pass') <br>
    <b>else:</b>&ensp; <br>
    &ensp;&nbsp;  print('fail')
  </li>
</ul>
<br>

## [📋6주차 강의&nbsp;-&nbsp;다중조건문]()

### [🔹중첩 if 문 - if 안에 if]()  
<ul>
  <li><b>if</b> score >= 60<b>:</b>&ensp;  <br>
    &ensp;&ensp;&nbsp;print('pass') <br>
    &ensp;&ensp;&nbsp;<b>if</b> score >= 90<b>:</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('장학금') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;print('fail') <br>
  </li>
</ul>

### [🔹연속 if 문: if ~ elif ~ else]()
<ul>
  <li><b>if</b> score >= 90<b>:</b>&ensp;  <br>
    &ensp;&nbsp;print('A') <br>
    <b>elif</b> score >= 80<b>:</b>&ensp; <br>
    &ensp;&nbsp;print('B') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&nbsp;print('C') <br>
  </li>
</ul>
  
<br>

## [📋7주차 강의&nbsp;-&nbsp;반복문-for]()

### [🔹for 기본 순회]()
<ul>
  <li><b>for</b> ch <b> in 군집(반복 가능한 객체) : </b> <br>
  &ensp;&ensp;문장</li>
  <li><b>for</b> i <b> in</b> [0,1,2,3,4]:&ensp;#리스트 객체<br>
  &ensp;&ensp;print(f'{i=}')
  </li>
</ul>

### [🔹for range]()
<ul>
  <li><b>for</b> i <b> in</b> range(0,5,1):&ensp; #range 객체 <br>
  &ensp;&ensp;print(f'{i=}')</li>
  <li> <b>range(start,stop,step)</b> &ensp;<br>
  - start에서 (stop-1)까지 <br>
  - range(0, 5, 1)&ensp; # 0, 1, 2, 3, 4 </li>
</ul>

### [🔹보조제어 break, continue]() 
<ul>
   <li> break : 반복문 탈출 </li>
   <li>continue : 반복 다시 시작 </li>
</ul>

<br>


## [📋9주차 강의&nbsp;-&nbsp;반복문-while]()
### [🔹while 문]()
<ul>
  <li>조건 반복 1 : start, 반복조건(끝), step<br>
  count = 0 &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# start<br>
  <b>while</b> count < 5 <b>:</b> # 반복조건(끝) <br>
  &ensp;&ensp;count += 1 &ensp;&ensp; # step <br> 
  &ensp;&ensp;print(f'{count}회') <br> 
  </li>
  <li>조건 반복 2 : 조건이 만족되는 동안<br>
  pwd = ' ' &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;# 초기화<br>
  <b>while</b> pwd != 'mju' <b>:</b> # 조건 만족하는지? <br>
  &ensp;&ensp;pwd=input('password') <br> 
  </li>
</ul>
   
### [🔹무한 루프]()
<ul>
  <li> <b>while True :</b> #  무한 루프<br>
  &nbsp; &nbsp; 문장<br>
  &nbsp; &nbsp; if menu == 0 :<br>
   &nbsp; &nbsp;&nbsp; &nbsp; break # 무한 루프 탈출 
</li>
</ul>

### [🔹중첩 for]()
<ul>
<li><b>for</b> i <b>in</b> range(1, 9)<b>:</b> <br>
  &ensp;&ensp; <b>for</b> j <b>in</b> range(1, 9)<b>:</b><br>
  &ensp;&ensp;&ensp;&ensp;print(f"{i}*{j}={i*j}")  # 구구단<br>  
</li>
</ul>

<br>

## [📋10주차 강의&nbsp;-&nbsp;문자열]()

### [🔹문자열 기본구조]()
<ul>
  <li> 생성 : msg = '안녕하세요' <br>
  - 인덱스: 첫문자에서 0부터 시작 <br>
  - 음의 인덱스 : 끝 문자에서 -1로 시작 </li>
  <li> 인덱싱 [순번]: msg[0]&ensp; #'안' <br>
    - 특정 순번의 개별 문자 </li>
  <li> 슬라이싱 [시작:끝]: msg[2:4] &ensp; #'하세'<br> 
    - 시작부터 (끝-1)까지 부분문자열 </li>
</ul>


### [🔹서식 : f-문자열]()
<ul>
  <li> f'..{표현식}..' # 중괄호 사용  <br>
    ex) print(f'hi. {name}, age {25}') </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li>
  <li> 자릿수: {25:5d} &ensp; #다섯자리 확보 </li>
  <li> 정밀도: {3.145:.2f} &ensp; #소수점 몇자리 </li>  
</ul>

### [🔹문자열 연산/함수]()
<ul>
  <li> 연산 (+, *, in, == )<br>
   - 'hi'+'mju' : 문자열 결합<br>
   - 'mju'*3 : 문자열 반복<br>
   - 'm' in 'mju' : 멤버쉽<br>
    - 'hi' =='mju' : 문자열 비교<br>
     </li> 
  <li> len(msg) : 문자열 길이 함수 </li>  
  <li> msg.split(구분자) : 문자열 분리 메소드 </li>  
  <li> 구분자.split(문자열리스트) : 결합 메소드 </li>  
  <li> msg.find('안') : 문자열 발견 위치 </li>  
  <li> msg.count('안') : 문자열 발견 횟수</li>  

</ul>

### [🔹2차원 리스트]()
<ul> 
<li>1차원 리스트를 요소로 가지는 리스트</li> 
<li>s = [ <br>
  [ 1, 2, 3, 4, 5],<br>
  [ 6, 7, 8, 9, 10]<br>
    ] </li>
<li>s[1][2] &ensp;# 이름[행][열] - 8 </li>   
</ul>

<br>

## [📋11주차 강의&nbsp;-&nbsp;함수 기본]()


### [🔹함수 정의&함수 호출]()
<ul>
<li>함수 정의 <br>
  &nbsp; <b>def</b> get_area(radius) <b>:</b> <br>
  &nbsp; &nbsp; area = radius*radius*3.14 <br>
  &nbsp;&nbsp;  <b>return</b> area
  <br>
</li>  
<li>함수 호출 <br>
   &nbsp; value = get_area(10)
   <br>
</li>
</ul>

### [🔹매개변수&반환값](b)
<ul>
  <li><b>매개변수:</b> 함수 정의시 값을 전달받는 변수  <br>
  <b>인수:</b> 함수 호출시 실제로 전달되는 값    </li>
  <li><b>반환값:</b>(함수 정의) 함수 결과로 돌려주는 값 <br> 
  <b>결과변수:</b> 함수호출 후 결과대입   </li>
</ul>

<br>


## [📋12주차 강의&nbsp;-&nbsp;함수 심화]()

### [🔹인수유형 ]()
<ul>
<li>  위치 인수 : 순서대로 값을 전달 </li>  
<li> 기본값 인수 : 함수 정의시 기본값이 설정</li>
<li> 키워드 인수 : 함수 호출시 '키워드 = 값' </li>
<li> 가변 인수 * : 인수의 갯수가 정해지지 않음</li>
</li>
</ul>

### [🔹지역변수vs전역변수]()
<ul>
<li>  <b>지역변수</b> - 함수<b>내</b>에서 생성된 변수 <br>
  &nbsp; - 함수내에서만 사용 가능
</li>
<li> <b>전역변수</b> : 함수<b>외</b>에서 생성된 변수 <br>
  &nbsp; - 모든 함수에서 사용 가능<br>
  &nbsp; - 함수 내에서 변경시: <b>global</b> 키워드 <br>
</li>
</ul>

## [📋13주차 강의&nbsp;-&nbsp;딕셔너리]()

### [🔹딕셔너리 기본 구조]()
<ul>
<li>의미: 키와 값 쌍, { } 사용, 순서 X </li>
<li>생성: d=['a':'apple', 'b':'banana']  </li>
<li>접근: d['a']&ensp; # 딕셔너리[키]   </li>
<li>추가: d['g'] = 'graph'  </li>
<li>수정: d['b'] ='blueberry' </li>  
<li>유효성 검사 : 'a' <b>in</b> d # not in  </li>    

</ul>

### [🔹딕셔너리 메소드]()
<ul>
<li>접근: d.get('a') </li>
<li>삭제: value = d.pop('a)  </li>
<li>목록: d.keys(), d.values(), d.items()  </li>
</ul>

### [🔹딕셔너리 반복]()
<ul>
<li><b>for</b> key <b>in</b> d<b>:</b> #d.keys() <br>
  &ensp;print(key, key[value])<br>
</li>
<li><b>for</b> key, value <b>in</b> d.items()<b>:</b>  <br>
  &ensp;print(key, value)<br>
</li>
</ul>
<br>

## [📋14주차 강의&nbsp;-&nbsp;파일입출]()

### [🔹모듈(module)]()
<ul>
<li> 연관된 함수와 변수를 모아 놓은 파일(.py) </li>
<li> 모듈 가져오는 방법<br>
- <b>import</b> random  <br>
- <b>import</b> random <b>as</b> rd    <br>
- <b>from</b> random <b>import</b> randint  <br>
- <b>from</b> random <b>import</b> randint <b>as</b> rdi <br>
- <b>from</b> random <b>import *</b>   <br>
<li> 모듈 종류 <br>
- 사용자 정의, 표준 모듈, 외부 모듈 <br>
- 사용자 정의 : 직접만든 파일 <br> ex) calc_area.py
</ul>


### [🔹파일처리]()
<ul>
<li><b>with</b> open('file_name', 'r') <b>as</b> f<b>:</b> <br>
  &ensp; 파일 열고, 닫는 안전한 방법<br>
  &ensp; 파일모드: r(읽기), w(쓰기), a(추가)<br>
  &ensp; encoding = 'utf-8' #cp949 
</li>  
<li><b>파일 쓰기</b> <br>
  &ensp; write() : 모든 내용을 하나의 문자열로 반환<br>
  &ensp; writelines() : 문자열 리스트를 쓰기<br>
</li>  
<li><b>파일 읽기</b> <br>
  &ensp; write() : 모든 내용을 하나의 문자열로 반환<br>
  &ensp; writelines() : 문자열 리스트를 쓰기<br>
</li>  
<li><b>데이터 정제</b> <br>
  &ensp; 문자열.strip() : 공백문자(빈칸, \n 등) 제거<br>
  &ensp; 문자열.split(구분자) : 구분자로 나누기<br>
</li>  
</ul>


### [🔹예외처리]()
<ul>
<li> try: ~  <br>
except(오류): ~ </li>
</ul>

<br>
