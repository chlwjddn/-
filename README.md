
```python

d = "Life is short, you need python"

print(d[1])
print(d[4:]) #띄어쓰기 역시 하나의 자리를 차지
print(d[5:9]) #end 값의 숫자는 범위에 포함되지 않음
'''
결과
i
 is short, you need python
is s

print(d.startswith("L")) #True or False 결정해주는 것
print(d.endswith("n"))

print(d.find("o"))
print(d.count("o"))

d2 = "  apple apple  "
print(d2.strip()) #양끝의 공백을 날리는 함수, 중간읙 공백은 남김

s = 'today\'s score'
n = 97

print(f'{s} is {n}') #f스트링 f다음 바로 문자열

```
