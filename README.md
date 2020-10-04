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

∙ 몫과 나머지 구하기<br>
![04](https://user-images.githubusercontent.com/69303473/95014957-63388e80-0685-11eb-8074-261cc5e94c19.PNG)<br>
a = int(input('정수: '))<br>
b = int(input('정수: '))<br>
print(a//b, a%b)<br>

∙ 초 단위의 시간을 분과 초로 변환하기<br>
![05](https://user-images.githubusercontent.com/69303473/95014960-66cc1580-0685-11eb-8fe5-700a5d3c824b.PNG)<br>
s = int(input('초 단위 시간: '))<br>
m = s//60<br>
s = s%60<br>
print(m, '분', s, '초')<br>

∙ 두 수 중 큰 수 찾기<br>
![06](https://user-images.githubusercontent.com/69303473/95014962-692e6f80-0685-11eb-8b54-97c1ff8b7c8e.PNG)<br>
a = int(input('정수: '))<br>
b = int(input('정수: '))<br>
if a>b:<br>
  print('큰 수:', a)<br>
else:<br>
  print('큰 수:', b)<br>
  
∙ 세 수 중 가장 큰 수 찾기<br>
![07](https://user-images.githubusercontent.com/69303473/95014963-6c296000-0685-11eb-92e4-2604f9fc3261.PNG)<br>
a = int(input('정수: '))<br>
b = int(input('정수: '))<br>
c = int(input('정수: '))<br>
if a>b:<br>
  if a>c:<br>
    print('가장 큰 수:', a)<br>
  else:<br>
    print('가장 큰 수:', c)<br>
else:<br>
  if b>c:<br>
    print('가장 큰 수:', b)<br>
  else:<br>
    print('가장 큰 수:', c)<br>

∙ 홀수, 짝수 판별하기<br>
![08](https://user-images.githubusercontent.com/69303473/95014966-6f245080-0685-11eb-8bf4-2eea5be734ca.PNG)<br>
a = int(input('정수: '))
if a%2 == 0:
  print(a, ': 짝수')
else:
  print(a, ': 홀수')

∙ '안녕' 10번 출력하기<br>
![09](https://user-images.githubusercontent.com/69303473/95014972-73506e00-0685-11eb-902f-5256f61487ad.PNG)<br>
for i in range(10):
  print('안녕')

∙ 1부터 100까지 출력하기 (for)<br>
![10](https://user-images.githubusercontent.com/69303473/95014975-76e3f500-0685-11eb-83ec-5c67fc1e205a.PNG)<br>
for i in range(1, 101):
  print(i, end=' ')

∙ 1부터 100까지 출력하기 (while)<br>
![11](https://user-images.githubusercontent.com/69303473/95014979-7a777c00-0685-11eb-934c-78a11d39ba63.PNG)<br>
a = 1
while a<=100:
  print(a, end=' ')
  a = a+1











