---
layout: single
title: "8차시 문제풀이" 
---

[문제 상황]
Q5) 정확한 윤년 규칙은 다음과 같다. 4로 나누어 떨어지면서 100으로 떨어지지 않으면
윤년이다. 400으로 나누어 떨어지는 것도 윤년에 포
함된다. 년도를 입력받아 그것이 윤년이면 True/Flase를 출력
하는 프로그램을 작성하시오.
      
[문제풀이]
~~~python
num = int(input('년도 :'))
print((num%4==0 and num%100!=0) or num%400==0)
~~~       
   
   
[결과]  
년도 :800
True
         
         

[문제 상황]     
Q9) 덕텍크는 신입사원 채용시험에서 마지막 관문인 체력검정을 실시하고 있다. 체력검정
합격기준은 다음과 같다. 각 항목에 해당하는 값을 입력받아 모든 항목이 기준을 통과하였다
면 True 그렇지 않으면 False를 출력하는 프로그램을 작성하시오.
      
[문제풀이]
~~~python
x = int(input('백미터달리기 : '))
y = int(input('천미터달리기 : '))
a = int(input('윗몸일으키기 : '))
b = int(input('악력 : '))
c = int(input('팔굽혀펴기 : '))
print(x<=15 and y <260 and a>=45 and b>=50 and c>=35)
~~~         
   
   
[결과]  
백미터달리기 : 1
천미터달리기 : 1
윗몸일으키기 : 77272
악력 : 7272
팔굽혀펴기 : 7272
True       