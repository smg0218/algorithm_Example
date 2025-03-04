# algorithm_Example
알고리즘 문제 업로드 파일 형식 예제
<br><br>
in과 out파일의 경우 ${\large\textsf{\color{#f03c15}첫글자는 반드시 숫자}}$로 입력해주셔야 합니다.
<br>
in과 out파일의 파일명이 일치하고 처음에 숫자가 입력되어 있다면 형식은 상관없습니다.

가능 예시
```
1_1
00001
1-01
1a1
```
<br>

불가능 예시

```
a1
#1 
```
<br>
서브태스크가 없는 문제의 경우 b_example_directory와 같이 subtask1 폴더를 생성하여 테스트케이스를 전부 입력하시고 똑같이 점수를 넣으시면 됍니다.
<br><br>

```
config.json 정보
{
    "problem_title": {문제 제목},
    "problem_name": {관리용 문제 제목}(관리자만 보기 가능),
    "time_limit": {단위:초},
    "memory_limit": {단위:MB}
}

description.md 정보
{문제 지문}
```
<br>

**github에서 압축파일을 받은 경우 상위 폴더가 존재하므로 반드시 압축파일을 열었을 때 알고리즘 문제 폴더가 보이는 형태로 zip파일을 다시 만드셔야 합니다**
<br>

파일구조
```
algorithm
├─a_a_plus_b
│  │  config.json
│  │  description.md
│  │  
│  ├─subtask1
│  │      1.in
│  │      1.out
│  │      2.in
│  │      2.out
│  │      score.txt
│  │      
│  ├─subtask2
│  │      1.in
│  │      1.out
│  │      score.txt
│  │      
│  └─subtask3
│          1.in
│          1.out
│          score.txt
│          
└─b_example_directory
    │  config.json
    │  description.md
    │  
    └─subtask1
            1.in
            1.out
            score.txt
```
