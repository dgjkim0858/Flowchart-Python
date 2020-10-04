# Flowchart Python

∙ '안녕' 출력하기<br>
![01](https://user-images.githubusercontent.com/69303473/95014948-5ae05380-0685-11eb-9f2d-526e7bf6c0c5.PNG)<br>
print('안녕')<br>

∙ 입력받은 이름 출력하기<br>
![02](https://user-images.githubusercontent.com/69303473/95014953-5e73da80-0685-11eb-9f4d-ea1f184d5e40.PNG)<br>
name = input('이름: ')<br>
print(name)<br>

∙ 입력받은 두 수 더하기<br>
![03](https://user-images.githubusercontent.com/69303473/95014955-60d63480-0685-11eb-9910-2d77f4b3c675.PNG)<br>
a = int(input('정수: '))<br>
b = int(input('정수: '))<br>
print(a+b)<br>

∙ 몫과 나머지 구하기
![04](https://user-images.githubusercontent.com/69303473/95014957-63388e80-0685-11eb-8074-261cc5e94c19.PNG)
a = int(input('정수: '))
b = int(input('정수: '))
print(a//b, a%b)

∙ 초 단위의 시간을 분과 초로 변환하기
![05](https://user-images.githubusercontent.com/69303473/95014960-66cc1580-0685-11eb-8fe5-700a5d3c824b.PNG)
s = int(input('초 단위 시간: '))
m = s//60
s = s%60
print(m, '분', s, '초')

∙ 두 수 중 큰 수 찾기
![06](https://user-images.githubusercontent.com/69303473/95014962-692e6f80-0685-11eb-8b54-97c1ff8b7c8e.PNG)
a = int(input('정수: '))
b = int(input('정수: '))
if a>b:
  print('큰 수:', a)
else:
  print('큰 수:', b)
  
∙ 세 수 중 가장 큰 수 찾기
![07](https://user-images.githubusercontent.com/69303473/95014963-6c296000-0685-11eb-92e4-2604f9fc3261.PNG)
a = int(input('정수: '))
b = int(input('정수: '))
c = int(input('정수: '))
if a>b:
  if a>c:
    print('가장 큰 수:', a)
  else:
    print('가장 큰 수:', c)
else:
  if b>c:
    print('가장 큰 수:', b)
  else:
    print('가장 큰 수:', c)

