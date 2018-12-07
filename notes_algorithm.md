#Math:
<1> reverse a digit
```
// pop operation
pop = x % 10;
x /= 10;

// push operation
temp = rev * 10 + pop;
rev = temp;
```

//////////////////////////////////////////////////////////////////////////////////////////////

#Code: (JAVA)
<1> determine if digit cause integer overflows;
```
if (ans > Integer.MAX_VALUE/10 || (ans == Integer.MAX_VALUE/ 10 && pop > 7)) return 0;
if (ans < Integer.MIX_VALUE/10 || (ans == Integer.MIN_VALUE/ 10 && pop < -8)) return 0;
```
