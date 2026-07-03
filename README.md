 ASSIGNMENT NO - 09

Que 1 . write a program which contains one function names as Display() that prints "Jay Ganesh" on console.

program -
```python
def display():
    print("Jay Ganesh")

display()
```

Output - 

<img width="685" height="150" alt="Screenshot 2026-07-01 192509" src="https://github.com/user-attachments/assets/7b8aa7da-f500-4a6b-81e7-07a4a345806b" />

Que. 2 Write a program which contains one function ChkGreater() that accepts two numbers and prints the greater number.

program -
```python
def ChkGreater(No1,No2):
    if(No1>No2):
        print(No1, "is greater ")
    else:
        print(No2, "is greater ")

ChkGreater(10,20)
```

Output-

<img width="697" height="143" alt="Screenshot 2026-07-01 193040" src="https://github.com/user-attachments/assets/e0373c38-d412-4569-a015-afc08171d6bc" />

Que 3. Write a program which accepts one number and prints square of that number.

Program -
```python
def square(No):
    result = No * No
    print("square is: " , result)

num = int(input("Enter number: "))
square(num)
```

Output-

<img width="682" height="150" alt="Screenshot 2026-07-01 193447" src="https://github.com/user-attachments/assets/618a6be5-c4e5-4a5c-a663-9ce9d383f87d" />

Que 4. Write a program which accepts one number and prints cube of that number.

program-
```python
def Cube(No):
    result = No * No * No
    print("Cube is : ", result )

num = int(input("Enter number: "))
Cube(num)
```

Output-

<img width="763" height="166" alt="Screenshot 2026-07-01 193824" src="https://github.com/user-attachments/assets/dc548a3e-6d40-445f-8cab-8da0016db05d" />

Que 5. Write a program which accepts one number and checks whether it is divisible by 3 and 5.

Program-
```python
def CheckDivisible(No):
    if No % 3 == 0 and No % 5 == 0:
        print("Divisible by 3 and 5 ")
    else:
        print("Not Divisible by 3 and 5 ")

num = int(input("Enter number : "))
CheckDivisible(num)
```

Output-

<img width="687" height="138" alt="Screenshot 2026-07-01 194352" src="https://github.com/user-attachments/assets/c01c1b4f-533d-4bcc-9e69-4174235cce50" />




ASSIGNMENT NO - 10

Que 1.Write a program which accepts one number and prints multiplication table of that number.

Program -
```python
def main():
    num = int(input("Enter number : "))

    for i in range (1 , 11 ):
        print( num * i , end = " " )

if __name__ == "__main__":
    main()
```

Output- 

<img width="731" height="153" alt="Screenshot 2026-07-01 200033" src="https://github.com/user-attachments/assets/e7f069cb-0ac5-47e6-9782-499f88aa912a" />

Que 2. write a program which accepts one number and prints sum of first N natural numbers.

Program-
```python
def main():
    num = int(input("Enter number : "))
    Sum = 0

    for i in range (1 , num + 1 ):
        Sum = Sum + i

    print("Sum is : ", Sum )

if __name__ == "__main__":
    main()
```

Output-

<img width="725" height="126" alt="Screenshot 2026-07-01 200808" src="https://github.com/user-attachments/assets/452f6e91-5d61-4876-829f-a33bea4f236a" />

Que3 . Write a program which accepts one number and prints factorial of that number.

Program -
```python
def main():
    num = int(input("Enter number : "))
    fact = 1

    for i in range ( 1, num + 1 ):
        fact = fact * i 

    print("fact is : ", fact)

if __name__ == "__main__":
    main()
```

Output-

<img width="697" height="161" alt="Screenshot 2026-07-01 201558" src="https://github.com/user-attachments/assets/1ef6349a-8b9f-4e2b-a3ed-a575049a173b" />

Que 4 . write a program which accepts one number and prints all even numbers till that number.

Program-
```python
def main():
    num = int(input("Enter number :"))

    for i in range(2 , num + 1 , 2):
        print(i , end = " ")

if __name__ == "__main__":
    main()
```

Output-

<img width="682" height="130" alt="Screenshot 2026-07-01 202229" src="https://github.com/user-attachments/assets/80e07290-be69-47af-ab1a-44d8e2098f35" />


Que 5. Write a program which accepts one number and prints all odd numbers till that number.

Program -
```python
def main():
    num = int(input("Enter number :"))

    for i in range(1 , num + 1 , 2):
        print(i , end = " ")

if __name__ == "__main__":
    main()
```

Output-


<img width="680" height="120" alt="Screenshot 2026-07-01 202712" src="https://github.com/user-attachments/assets/5164a214-fe3c-4f52-80c3-4277ee8e73af" />




ASSIGNMENT NO - 11 


Que 1.Write a program which accepts one number and checks whether it is prime or not.

Program-
```python
num = int(input("Enter number: "))

if num <= 1:
    print("Not Prime")
else:
    for i in range(2, num):
        if num % i == 0:
            print("Not Prime")
            break
    else:
        print("Prime Number")
```

Output-

<img width="660" height="148" alt="Screenshot 2026-07-03 215140" src="https://github.com/user-attachments/assets/6bf45af7-3ba5-4e1a-b9ab-efb64903cba7" />

Que 2.Write a program which accepts one number and prints count of digits in that number.

Program-
```python
num = int(input("Enter number: "))
count = 0

while num > 0:
    count += 1
    num = num // 10

print("Count of digits:", count)
```

Output-

<img width="691" height="177" alt="Screenshot 2026-07-03 215305" src="https://github.com/user-attachments/assets/8e867cd7-aa08-406b-9b97-64820f41b999" />


Que 3. write a program which accepts one number and prints sum of digits.

Program -
```python
num = int(input("Enter number: "))
sum = 0

while num > 0:
    digit = num % 10
    sum += digit
    num = num // 10

print("Sum of digits:", sum)
```

Output-

<img width="687" height="140" alt="Screenshot 2026-07-03 215416" src="https://github.com/user-attachments/assets/6b363ff5-0f28-434e-8a4e-4af79d287c77" />

Que 4 . Write  a program which accepts one number and prints reverse of that number.

Program -
```python
num = int(input("Enter number: "))
rev = 0

while num > 0:
    digit = num % 10
    rev = rev * 10 + digit
    num = num // 10

print("Reverse number:", rev)
```

Output-

<img width="663" height="156" alt="Screenshot 2026-07-03 215530" src="https://github.com/user-attachments/assets/660a6074-1a22-4e95-9c0e-6b13bd966cb9" />


Que 5 . Write a program which accepts one number and checks whether it is palindrome or not.

Program - 
```python
num = int(input("Enter number: "))
temp = num
rev = 0

while num > 0:
    digit = num % 10
    rev = rev * 10 + digit
    num = num // 10

if temp == rev:
    print("Palindrome")
else:
    print("Not Palindrome")
```

Output-

<img width="672" height="153" alt="Screenshot 2026-07-03 215638" src="https://github.com/user-attachments/assets/1e9bbf64-5595-4df0-a4d6-154813731641" />


ASSIGNMENT NO - 12

Que 1. Write a program which accepts one character and checks whether it is vowel or consonant.

Program - 
```python
ch = input("Enter a character: ")

if ch.lower() in ['a', 'e', 'i', 'o', 'u']:
    print("Vowel")
else:
    print("Consonant")
```

Output-

<img width="650" height="132" alt="Screenshot 2026-07-03 220008" src="https://github.com/user-attachments/assets/74d6433a-169b-40d1-8adb-68965b5c64b8" />

Que 2 . Write a program which accepts one number and prints its factors.

Program-
```python
num = int(input("Enter number: "))

print("Factors are:")
for i in range(1, num + 1):
    if num % i == 0:
        print(i, end=" ")
```

Output-

<img width="656" height="131" alt="Screenshot 2026-07-03 220121" src="https://github.com/user-attachments/assets/1ec8449f-225b-4d89-903e-b6c3429d7f47" />


Que 3 . Write a program which accepts two number  and prints addition , subtraction , multiplication, division.

Program- 
```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)

if b != 0:
    print("Division:", a / b)
else:
    print("Division not possible")
```

Output-

<img width="672" height="176" alt="Screenshot 2026-07-03 220236" src="https://github.com/user-attachments/assets/a85c7f25-31f1-40c8-90b1-4f2ae2a9c255" />

Que 4. Write a program which accepts one number and prints that many numbers starting from 1.

Program -
```python
num = int(input("Enter number: "))

for i in range(1, num + 1):
    print(i, end=" ")
```

Output-

<img width="682" height="106" alt="Screenshot 2026-07-03 220349" src="https://github.com/user-attachments/assets/0810aecb-0388-45aa-94ff-b7161bf7b500" />

Que 5 . Write a program that accepts one number and prints that many numbers in reverse order.

Program-
```python
num = int(input("Enter number: "))

for i in range(num, 0, -1):
    print(i, end=" ")
```

Output-


<img width="658" height="92" alt="Screenshot 2026-07-03 220453" src="https://github.com/user-attachments/assets/9c0bfee3-96bd-4e63-b16a-81385df7fd5f" />


ASSIGNMENT NO: 13

Que 1 . Write a program which accepts length and width of rectangle and prints area.

Program -
```python
length = float(input("Enter length: "))
width = float(input("Enter width: "))

area = length * width
print("Area of Rectangle:", area)
```

Output-


<img width="677" height="143" alt="Screenshot 2026-07-03 220724" src="https://github.com/user-attachments/assets/fc9fbd42-6526-46f4-88d8-c678e51be8d5" />

Que 2 . Write a program that accepts radius of circle and prints area of circle.

Program -
```python
radius = float(input("Enter radius: "))

area = 3.14 * radius * radius
print("Area of Circle:", area)
```

Output-


<img width="657" height="122" alt="Screenshot 2026-07-03 220837" src="https://github.com/user-attachments/assets/0597e23c-6d8d-4327-a61c-74b467202c0e" />

Que 3 . Write a program that accepts one number and checks whether it is perfect number or not

Program-
```python
num = int(input("Enter a number: "))

sum = 0
for i in range(1, num):
    if num % i == 0:
        sum += i

if sum == num:
    print("Perfect Number")
else:
    print("Not a Perfect Number")
```

Output-


<img width="682" height="132" alt="Screenshot 2026-07-03 220946" src="https://github.com/user-attachments/assets/549b2457-ac31-4a01-be50-0ce5e487d07c" />


Que 4. Write a program that accepts one number and prints binary equivalent.

Program-
```python
num = int(input("Enter a number: "))

binary = bin(num)
print("Binary Equivalent:", binary[2:])
```

Output-


<img width="672" height="126" alt="Screenshot 2026-07-03 221123" src="https://github.com/user-attachments/assets/08974d9d-97c1-4d71-b70f-1d4e2a182841" />

Que 5 . Write a program that accepts marks and display grade.

Program -
```python
marks = float(input("Enter marks: "))

if marks >= 75:
    print("Distinction")
elif marks >= 60:
    print("First Class")
elif marks >= 50:
    print("Second Class")
else:
    print("Fail")
```

Output-


<img width="682" height="195" alt="Screenshot 2026-07-03 221239" src="https://github.com/user-attachments/assets/1909d53c-0d2b-46ea-b0b9-398bfcaee5e8" />








