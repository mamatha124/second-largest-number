# second-largest-number in python
a = 10
b = 20
c = 30
if a>b and a>c:
    a = 0
elif b>c:
    b = 0
else:
    c = 0
if a>b and a>c:
    print(a)
elif b>c:
    print(b)
else:
    print(c)
