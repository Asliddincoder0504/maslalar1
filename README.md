# maslalar1
masalalar  yechimlari
![image](https://github.com/user-attachments/assets/49d2f991-7728-43c9-8251-3d6125a750b9)
#11-misol
A=int(input("A="))
B=int(input("B="))
if A!=B:
    if A>B:
        print(A)
    elif A<B:
        print(B)
elif A==B:
    print(0)
print("A=",A)
print("B=",B)
![image](https://github.com/user-attachments/assets/e434e863-f793-43a3-9428-f6fd7d03d981)
#12-masala
a=int(input("a="))
b=int(input("b="))
c=int(input("c="))

if a>b>c or b>a>c:
    print(c)
elif a>c>b or c>a>b:
    print(b)
elif b>c>a or c>b>a:
    print(a)
![image](https://github.com/user-attachments/assets/f637a020-7c58-4255-9416-1c61cfc0986b)
#13-masala
a=int(input("a="))
b=int(input("b="))
c=int(input("c="))

if a>b>c or c>b>a:
    print(b)
elif a>c>b or b>c>a:
    print(c)
elif b>a>c or c>a>b:
    print(a)
![image](https://github.com/user-attachments/assets/6776dae4-770d-4d50-9dcd-f6338a1ae42a)
#14-masala
a = int(input("a= "))
b = int(input("b= "))
c = int(input("c= "))

if a <= b and a <= c:
    eng_kichik = a
elif b <= a and b <= c:
    eng_kichik = b
else:
    eng_kichik = c

if a >= b and a >= c:
    eng_katta = a
elif b >= a and b >= c:
    eng_katta = b
else:
    eng_katta = c

print(f"Eng kichik son: {eng_kichik}")
print(f"Eng katta son: {eng_katta}")
![image](https://github.com/user-attachments/assets/f317f1ba-ac23-4526-9dd7-ae35bd5c5eaf)
#15-masala
a = int(input("a= "))
b = int(input("b= "))
c = int(input("c= "))
yigindi1=a+b
yigindi2=a+c
yigindi3=b+c

if yigindi1>yigindi2 and yigindi2>yigindi3:
    print(f"Eng katta yig'indi ",yigindi1,yigindi2)
elif yigindi2>yigindi1 and yigindi3>yigindi1:
    print(f"Eng katta yig'indi",yigindi2,yigindi3)
elif yigindi3>yigindi2 and yigindi1>yigindi2:
    print(f"Eng katta son",yigindi1,yigindi3)
![image](https://github.com/user-attachments/assets/7d4cf5de-cef6-477f-850f-f29662f38eb1)
#16-masala
a = float(input("a= "))
b = float(input("b= "))
c = float(input("c= "))

if a>b>c:
    print(a*2)
    print(b*2)
    print(c*2)
else:
    print(-a)
    print(-b)
    print(-c)
print(a)
print(b)
print(c)
![image](https://github.com/user-attachments/assets/001e5f5b-dd19-4041-9a58-73b033e53479)
#17-masala
a = float(input("a= "))
b = float(input("b= "))
c = float(input("c= "))

if a>b>c or a<b<c:
    print(a*2)
    print(b*2)
    print(c*2)
else:
    print(-a)
    print(-b)
    print(-c)
print(a)
print(b)
print(c)
![image](https://github.com/user-attachments/assets/b7770610-1619-4e7b-8d2f-6f0a22a24e46)
#18-masala
a=int(input("a="))
b=int(input("b="))
c=int(input("c="))

if a==b!=c:
    tartib=3
elif a==c!=b:
    tartib=2
elif b==c!=a:
    tartib=1
print(f"biz hoxlagan son {tartib} da")
![image](https://github.com/user-attachments/assets/32838d65-e63d-4221-aea7-cc6dbbd1ca28)
#19-masala
a=int(input("a="))
b=int(input("b="))
c=int(input("c="))
d=int(input("d="))

if a==b==c!=d:
    tartib=4
elif a==b==d!=c:
    tartib=3
elif a==c==d!=b:
    tartib=2
elif b==c==d!=a:
    tartib=1
print(f"biz hoxlagan son {tartib} da")
![image](https://github.com/user-attachments/assets/79051de9-41d1-442e-b786-cc433a6dffde)
#20-masala
A=int(input("A="))
B=int(input("B="))
C=int(input("C="))

masofa1=abs(A-B)
masofa2=abs(A-C)

if masofa1>masofa2:
    print(masofa1)
elif masofa2>masofa1:
    print(masofa2)
