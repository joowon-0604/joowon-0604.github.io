---
layout: single
title: "11차시 문제풀이" 
---
    
[문제 상황]
  요트 경주는 물 위에 부표를 띄워 표시해 둔 코스를 정해진
시간 내에 가장 빨리 완주하는 게임입니다. 육상에서 하는 스
포츠와는 다르게 바람, 조류, 파도 등 여러 영향을 많이 받기
때문에 레이스를 여러 번 하여 종합점수로 순위를 정합니다. 5팀이 출전하여 3번의 기록이 다음과 표와 같을 때, 각 팀 기
록의 평균을 구하여 출력하는 프로그램을 작성해 보시오. 팀 명 1차 2차
      
          
[문제풀이]      
~~~python
#Q9
lst = [['A팀', 55, 48, 60], ['B팀', 77, 60, 55], ['C팀', 49, 65, 60], ['D팀', 70, 58, 63], ['E팀', 54, 50, 58]]
avlst = []
for x in range(len(lst)):
  sum = 0
  for y in range(1, len(lst[x])-1):
    sum+=lst[x][y]
  avlst.append(int(sum/len(lst[0])))

print(avlst)
~~~  
          
          
[결과]    
[25, 34, 28, 32, 26]      
