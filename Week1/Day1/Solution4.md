What will be the output of the following pseudocode?

1. Integer a, b
2. Set a = 3, b = 3
3. a = b
4. if (1 ^ 1) then
5.     a = 1
6. else
7.     b = 2
8. end if
9. print a + b
Note: ^ is the bitwise XOR operator.
1 ^ 1 = 0 because both bits are same.
The if(x) block runs only if x is non-zero.

Steps to Analysis

1. a=3 ,b=3

2 line 3: a=b -> a=3

3 line 4 1 ^ 1 = 0 → false → else block runs

4 line 7 b = 2

5 Final Values: a=3,b=2

6 line 9 print a + b → 3 + 2 = 5

final Output 5






