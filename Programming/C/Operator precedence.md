#programming/c/operator

```tx
Precedence|Operator|Description|
-------|-------|-------|
1|x++ x--|suffix increment and decrement|
^^|fn(args)|function call|
^^|arr[n]|array subscripting|
^^|struct.member|structure and union member access|
^^|struct->member|structure and union member access through pointer|
^^|(type){list}|compound literal|
2|++x --x|prefix increment and decrement|
^^|+x -x|[[Unary operator]] plus and minus|
^^|!x ~x|logical NOT and bitwise NOT|
^^|(type)exp|cast|
^^|\*x|dereference|
^^|&x|address-of|
^^|sizeof type|size-of|
^^|\_Alignof type|[[Data Structure Alignment]] requirement|
3|a\*b a/b a%b|multiplication, division and remainder|
4|a+b a-b|addition and subtraction|
5|a<<b a>>b|bitwise left shift and right shift|
6|a<b a<=b a>b a>=b|relational operators|
7|a==b a!=b|relational operators|
8|a&b|bitwise AND|
9|a^b|bitwise XOR|
10|a\|b|bitwise OR|
11|a&&b|logical AND|
12|a\|\|b|logical OR|
13|(condition)?exp1:exp2|ternary conditional|
14|a\=exp|assignment|
^^|a+=b a-=b a*=b a/=b a%=b a<<=b a>>=b a&=b a^=b a\|=b|assignment|
15|a,b|comma|
```

[[Data Structure Alignment]]

[[Unary operator]]