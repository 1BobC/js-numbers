JS learning outcomes 1 

1 How do you declare a variable? 
Variables are declared a type, name, value  eg let price1=”230” 

2 What are three different ways to declare a variable? 
Var, let, const. Var is less used now in favour of let.

3 Which one should you use when? 
New variables let and const at present are advised to be used most.
let for general variables and const for variables that will contain values that won’t change.
var  should be avoided at present until the difference in outcomes between let and var are understood. 
https://medium.com/javascript-scene/javascript-es6-var-let-or-const-ba58b8dcde75
https://ui.dev/var-let-const/
https://love2dev.com/blog/javaScript-var-let-const/
https://levelup.gitconnected.com/const-vs-let-vs-var-in-javascript-which-one-should-you-use-c56cf9b9e2a3

4 What are the rules for naming variables? 
Variables must have unique names, names that are related to the context of the prupose of the code and must not use JS reserved names.

5 What are operators, operands, and operations?
Operators are the +, -, *, /,%. ++,--,**, == etc.
Operands are the numbers being acted on.
Operations are the calulations that happen when the code is interpreted by the browser.

6 What is concatenation and what happens when you add numbers and strings together? 
Concatenation is the effect of the browser showing the collection of strings inline. Generally adding strings and numbers will result in numbers being treated as strings and shown as such on the webpage but with no calculation taking plce.

7 What are the different types of operators in JavaScript? 
Assignment = , +=, -=, *=, /= , %= , **= .
Arithmetic + , * , ** exponentiation, / , % modulus, ++ , –.
Comparison == , === , != , !== , > , < , >= , <= , ? temery.
Logical && , || , ! .
Type   typeof, instanceof (true if object is an instance of an object type)

Bitwise  
Operator  Description           Example  Same as      Result  Decimal
&         AND                   5 & 1    0101 & 0001  0001    1
|         OR                    5 | 1    0101 | 0001  0101    5
~         NOT                   ~ 5      ~0101        1010    10
^         XOR                   5 ^ 1    0101 ^ 0001  0100    4
<<        Zero fill left shift  5 << 1   0101 << 1    1010    10
>>        Signed right shift    5 >> 1   0101 >> 1    0010    2
>>>       Zero fill right shift 5 >>> 1  0101 >>> 1   0010    2


8 What is the difference between == and ===? 
These operaters result in true or false.
== will show true if the values are equal (and false if they are not)
=== will show true only if the value AND the type is the same

 9 What are operator precedence values? 
Generally * and ‘ will be carried out first. This can result in a different result than would be expected. EG. 4 -2 * 8 in mental arithmetic would suggest 16 whereas -12 would be shown by the browser.

10 What are the increment/decrement operators? 
++  and  --

11 What is the difference between prefixing and post-fixing them? 
a++ will return the original value of a but it will be incremented by one the next time a is called.
a-- will return the original value of a but it will be decremented by one the next time a is called.
++a will return the incremented (by one) value of a.
--a will return the decremented (by one) value of a.
12 What are assignment operators?  (Wow, will I use all of these?)
Operator    Example     Same As
=           x = y       x = y
+=          x += y      x = x + y
-=          x -= y      x = x - y
*=          x *= y      x = x * y
/=          x /= y      x = x / y
%=          x %= y      x = x % y
<<=         x <<= y     x = x << y
>>=         x >>= y     x = x >> y
>>>=        x >>>= y    x = x >>> y
&=          x &= y      x = x & y
^=          x ^= y      x = x ^ y
|=          x |= y      x = x | y
**=         x **= y     x = x ** y

13 What is the “Unary +” Operator? 
The unary + operator can be used to convert a variable to a number.
Examples:
var y = "5";      // y is a string
var x = + y;      // x is a number 

var y = "John";   // y is a string
var x = + y;      // x is a number (NaN) 

Mmmmm… can’t imagine uet where I’d use this!
