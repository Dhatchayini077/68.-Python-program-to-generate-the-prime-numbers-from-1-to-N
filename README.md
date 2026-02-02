# 68.-Python-program-to-generate-the-prime-numbers-from-1-to-N
num = int(input("Enter the range: "))

for n in range(2, num):      # start from 2 (1 is not prime)
    for i in range(2, n):
        if n % i == 0:
            break
    else:
        print(n)
Output:
Enter the range: 15
2
3
5
7
11
13
