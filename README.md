# mathlib_python 

This program uses if-else statements along with mathematical operators to perform different operation such as square, cube, cube root and square root based in the users choice.
<br>
import math
n=int(input("enter any no:"))
if 0<=n<=9:
    print("squar of no is:",math.pow(n,2))
elif 10<=n<=99:
    print("squar root of no.is:",math.squrt(n))  
elif 100<=n<=999:
    print("cube root of no is :",math.cbrt(n)) 
else:
    print("no. is not valid")         
