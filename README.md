# This is a sample Python script.

# Press Shift+F10 to execute it or replace it with your code.
# Press Double Shift to search everywhere for classes, files, tool windows, actions, and settings.
# print(5)
# print(5+3)
# print("Hello")
# print(5+3+3)
# print("I am a good boy")

#form
name = input("Enter your name: ")
print(name)
email = input("Enter your email address: ")
print(email)
# print("Thank you")
# p = input("Enter your principal: ")int
#
# r = input("Enter your rate of interest: ")int
#
# t = input("Enter your time: ")int
#
# si = p * r * t / 100

# print(si)

p = 10000
r = 5
t = 3
si = p * r * t / 100
print(si)
amount = p + si
print(amount)
print("rate of interest compunded anually")
amounta = p * (1 + 5/100) ** 3
print(amounta)
ci = amounta - p
print(ci)

print("celcius to fahrenheit")
C = 100
F = (C * 9 / 5) + 32
print(F)
a = 30
b = 20
if a > b:
    print(a)
elif b < a:
    print(10)
else:
    print(20)

a = 9
b = 6
c = 4
if a!=b and b!=c and c!=a:
    print("scalene")
elif a==b or b==c or c==a:
    print("isosceles")
else:
    print("equilateral")

a = 6
b = 6
c = 6
if a!=b and b!=c and c!=a:
    print("scalene")
elif a==b and b==c:
    print("equilateral")
else:
    print("isosceles")

a = 8
b = 5
c = 5
if a!=b and b!=c and c!=a:
    print("scalene")
elif a==b or b==c or c==a:
    print("isosceles")
else:
    print("equilateral")

a = 8
b = 1
c = 6
if a > b:
    if a > c:
        print(a)
    else:
        print(c)
else:
    if b > c:
        print(b)
    else:
        print(c)
a = 1
b = 2
sum = a+b
print(sum)
difference = a-b
print(difference)
multiplication = a*b
print(multiplication)
division = a//b
print(division)
remainder = a%b
print(remainder)
a = 8
b = 12
c = 6
if a+b>c and b+c>a and a+c>b:
    print("Yes")
else:
    print("No")

x = 10
y = 5
z = 5
if x==y==z:
    print("equilateral")
elif x==y or y==z or z==x:
    print("isosceles")
else:
    print("scalene")

#foo
def foo():
    print("Manganba")
    return 20
m = 15
n = 50
o = 25
if m < n and n < foo():
    print("Good boy")
else:
    print("Bad boy")

'''
<HTML><BODY><H1>HAHA</H1></BODY></HTML>
'''

#Ternary operator(3)
signal = "Blue"
action = "Fight" if signal=="Green" else"Silent"
print(action)
