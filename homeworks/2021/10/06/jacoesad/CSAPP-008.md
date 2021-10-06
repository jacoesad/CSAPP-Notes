> ***2021.10.06\***

------

### 2.1.8 Logical Operations in C

C语言逻辑运算，||-OR、&&-AND、!-NOT。

逻辑运算认为所有非零的参数都表示TRUE，而参数0表示FALSE。返回的1、0分别表示结果为TRUE或者FALSE。

如果逻辑运算符的第一个参数就能确定表达式结果，那么逻辑运算符就不会对第二个参数求值。

### 2.1.9 Shift Operations in C

C语言位移运算符，向左或者向右移动位模式。

- x<<k，表示x向左移动k位，丢弃最高的k位，并且在右端补k个0。
- x>>k，可以表示两种右移，逻辑右移和算数右移：
  - 逻辑右移在左端补k个0
  - 算数右移在左端补k个最高位的值。

一般的，对有符号数使用算数右移；对于无符号数，右移必须是逻辑的。