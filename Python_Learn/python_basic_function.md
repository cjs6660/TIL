### Python 기초 함수

[1] 변수 

``` python
a = 3
b = 4
print(a)
print(b)
3
4

del(a)
del(b)
print(a)
print(b)

NameError          Traceback (most recent call last)
~\AppData\Local\Temp/ipykernel_1272/2921613868.py in <module>
----> 1 print(a)
      2 print(b)

NameError: name 'a' is not defined
```



---





[2]  if문

``` python
a =3
if a>1 :
    print("a is greater than 1")
a is greater than 1

# 조건문이 참일 경우에 하위 코드 실행
```



---



[3]  for문

```python
for apple in [1,2,3]
	print(apple)
1
2
3
```



---



[4] while문

```python
score = 0
while score<100 : #기간
    score = score + 10 #수식
    print("%d점 입니다" % score) #기간 동안의 출력
    if score == 100 :
        print("축하합니다.")
10점 입니다
20점 입니다
30점 입니다
40점 입니다
50점 입니다
60점 입니다
70점 입니다
80점 입니다
90점 입니다
100점 입니다
축하합니다.
```



---



[5] 함수 만들기

```python
def add(a, b):
    return a + b
add(3,4)
7
```



---



[6] 사칙연산

```python
a = 3
b = 4
print(a**b) #제곱
81

a = 7
b = 3
print(a//b) #몫 반환
2

a = 7
b = 3
print(a%b) #나머지 반환
1
```



---



[7] 문자열 포메팅

```python
print("I eat %d apples" % 3)
I eat 3 apples

number = 3 #변수 지정
print("I eat %d apples" % number)
I eat 3 apples

number = 3
day = "three"
print("I eat %d apples, so I was sick for %s days" % (number, day))
I eat 3 apples, so I was sick for three days

print("{} {} {}".format(11, 22, 33)) #.format
11 22 33

a = "Python is the best choice" #문자열 위치 찾기 .find
print(a.find("b"))
14

```

