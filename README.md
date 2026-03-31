# Assignment-4
# Assignment No 4 - All in One Program

# 1) Display even numbers from 1 to 10
print("Even numbers from 1 to 10:")
a = 2
while a <= 10:
    print(a)
    a += 2


# 2) Add odd numbers from 1 to 10
print("\nSum of odd numbers from 1 to 10:")
a = 1
sum_odd = 0

while a <= 10:
    sum_odd += a
    a += 2

print(sum_odd)


# 3) Fibonacci series between 0 to 50
print("\nFibonacci series (0 to 50):")
a = 0
b = 1

while a <= 50:
    print(a)
    c = a + b
    a = b
    b = c


# 4) Remove characters with odd index from a string
print("\nRemove characters at odd index:")
text = input("Enter string: ")
result = ""

i = 0
while i < len(text):
    result += text[i]
    i += 2

print("Result:", result)


OUTPUT 


Even numbers from 1 to 10:
2
4
6
8
10

Sum of odd numbers from 1 to 10:
25

Fibonacci series (0 to 50):
0
1
1
2
3
5
8
13
21
34

Remove characters at odd index:
Enter string: 20
Result: 2