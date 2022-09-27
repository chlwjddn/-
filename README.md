### String slicing and indexting

```python

d = "Life is short, you need python"

print(d[1])
print(d[4:]) #띄어쓰기 역시 하나의 자리를 차지
print(d[5:9]) #end 값의 숫자는 범위에 포함되지 않음
```

### String function

```python
print(d.startswith("L")) #True or False 로 결과값이 나타남
print(d.endswith("n"))

print(d.find("o"))
print(d.count("o"))

d2 = "  apple apple  "
print(d2.strip()) #양끝의 공백을 날리는 함수, 중간읙 공백은 남김
```

```python

#스트링 복습

s = 'today\'s score'
n = 97

print(f'{s} is {n}') #f스트링 f다음 바로 문자열
```
### Data type
``` python 
print(10 + float("314e-2) # 숫자1e숫자2 숫자 곱하기 10의 숫자2승(양수든 음수든)

print(round(2.6)) #round 반올림 
print(round(2.785,2)) #,뒤 숫자만큼 소수점자리 다음 자리에서 반올림하기
```

