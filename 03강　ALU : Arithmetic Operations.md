## 🦄 ALU: Arithmetic Operations (3 / 13회차)
<br>

### 3.5 정수의 산술 연산　　　	`kycho`

요기엔 문제를 적어주세연-

<details>
<summary> <b> :page_facing_up: 답지 </b>  </summary><br>
  
답지의 구성은<br>
문제와 동일하게 부탁드려연-

</details>
<br><br>

### 3.6 부동소수점 수의 표현　　　　	`jakang`

요기엔 문제를 적어주세연-

<details>
<summary> <b> :page_facing_up: 답지 </b>  </summary><br>
  
답지의 구성은<br>
문제와 동일하게 부탁드려연-

</details>
<br><br>

### 3.7 부동소수점 산술 연산　　	`gaekim`

```
[부동소수점 산술 연산 개념정리]

1. 덧셈 / 뺄셈

    1단계. 두 수의 지수가 같아지도록 만든다(소수점의 위치를 이동)

    2단계. 가수들끼리 덧셈 / 뺄셈한다

    3단계. 결과값을 정규화한다.(가수의 숫자가 소숫점 첫째자리에서 시작하도록)

          예시) 1.001001 x 2^5 → 0.1001001 x 2^6

2. 곱셈 / 나눗셈

    1단계. 가수끼리 곱한다

    2단계. 지수끼리 더하거나(곱셈) 뺀다(나눗셈)

    3단계. 정규화한다.
 ```   
    

- 다음 중 부동소수점 덧셈 과정에서 필요하지 않은 연산은 어느 것인가? [기본문제 3.15번]


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 가. 지수 조정 &nbsp;&nbsp;&nbsp; 나. 정규화 &nbsp;&nbsp;&nbsp; 다. 지수 덧셈 &nbsp;&nbsp;&nbsp; 라. 가수 덧셈
- 다음 중 부동소수점 나눗셈 과정에서 필요하지 않은 연산은 어느 것인가? [기본문제 3.16번]


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 가. 지수 조정 &nbsp;&nbsp;&nbsp; 나. 정규화 &nbsp;&nbsp;&nbsp; 다. 가수 나누기 &nbsp;&nbsp;&nbsp; 라. 지수 뺄셈
- 아래의 부동소수점 산술 연산들을 수행하라. [연습문제 3.24번 변형]


  1번>  (0.111001 x 2<sup>-5</sup>) + (0.100111 x 2<sup>-3</sup>)
  
  
  2번>  (0.100011 x 2<sup>6</sup>) - (0.111001 x 2<sup>3</sup>)
  
  
  3번>  (0.1001 x 2<sup>8</sup>) x (0.1011 x 2<sup>12</sup>)
- 부동소수점 산술연산 과정에서는 `__` 오버플로우, `__` 언더플로우, `__` 언더플로우, `__` 오버플로우 등의 문제가 발생할 가능성이 있다.


<details>
<summary> <b> :page_facing_up: 답지 </b>  </summary><br>
  

- 다음 중 부동소수점 덧셈 과정에서 필요하지 않은 연산은 어느 것인가? [기본문제 3.15번]


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 가. 지수 조정 &nbsp;&nbsp;&nbsp; 나. 정규화 &nbsp;&nbsp;&nbsp; **다. 지수 덧셈** &nbsp;&nbsp;&nbsp; 라. 가수 덧셈
- 다음 중 부동소수점 나눗셈 과정에서 필요하지 않은 연산은 어느 것인가? [기본문제 3.16번]


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **가. 지수 조정** &nbsp;&nbsp;&nbsp; 나. 정규화 &nbsp;&nbsp;&nbsp; 다. 가수 나누기 &nbsp;&nbsp;&nbsp; 라. 지수 뺄셈
- 아래의 부동소수점 산술 연산들을 수행하라. [연습문제 3.24번 변형]


  1번>  (0.111001 x 2<sup>-5</sup>) + (0.100111 x 2<sup>-3</sup>) = **0.11010101 x 2<sup>-3</sup>**
  
  
  2번>  (0.100011 x 2<sup>6</sup>) - (0.111001 x 2<sup>3</sup>) = **0.11011111 x 2<sup>5</sup>**
  
  
  3번>  (0.1001 x 2<sup>8</sup>) x (0.1011 x 2<sup>12</sup>) = **0.1100011 x 2<sup>19</sup>**
  
  <img src = "https://user-images.githubusercontent.com/59970070/100898551-388f7880-3504-11eb-9ef7-d292843994be.jpg" width="70%" height="70%">

- 부동소수점 산술연산 과정에서는 `지수` 오버플로우, `지수` 언더플로우, `가수` 언더플로우, `가수` 오버플로우 등의 문제가 발생할 가능성이 있다.
   > 표현할 수 있는 범위를 넘어설 경우, 위와 같은 문제들이 발생할 수 있다.
</details>
<br><br>
