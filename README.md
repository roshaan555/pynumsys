# pynumsys 0.1
Python package to convert one numbering system to another such as **binary** to **decimal**, **decimal** to **binary** etc.


## Installation:
```nano
pip install pynumsys
```

## For Upgradation(pynumsys):
```nano
pip install --upgrade pynumsys
```

# Binary Conversions:

1) **Binary to Decimal**
2) **Binary to Octal**
3) **Binary to Hexadecimal**

# Binary Operations:
1) **Binary Addition**
2) **Binary Subtraction**
3) **Binary Multiplication**
4) **Binary Division**

## Binary to Decimal:
It is a function that converts binary to decimal from binary string input.

**Example:**

```py
import pynumsys as pns

bin_str = "1110011"
print(bin_to_dec(bin_str))
```

**Output:**

115

## Binary to Octal:

**Example:**

```py
import pynumsys as pns

bin_str = "1110011"
print(bin_to_oct(bin_str))
```

**Output:**

163

## Binary to Hexadecimal:

**Example:**

```py
import pynumsys as pns

bin_str = "1110011"
print(bin_to_hex(bin_str))
```

**Output:**

73

## Binary Addition:
It is a function which returns addition of two binary numbers.

**Example:**

```py
import pynumsys as pns

bin_str1 = "1010"
bin_str2 = "1101"

print(bin_to_add(bin_str1, bin_str2))
```

**Output:**

10111

## Binary Subtraction:
It is a function which returns subtraction of two binary numbers.

**Example:**

```py
import pynumsys as pns

bin_str1 = "1101"
bin_str2 = "1010"

print(bin_to_sub(bin_str1, bin_str2))
```

**Output:**

11

## Binary Multiplication:
It is a function which returns muliplication of two binary numbers.

**Example:**

```py
import pynumsys as pns

bin_str1 = "101"
bin_str2 = "11"

print(bin_to_mul(bin_str1, bin_str2))
```

**Output:**

1111

## Binary Division:
It is a function which returns division of two binary numbers. 

**Example:**

```py
import pynumsys as pns

bin_str1 = "1101"
bin_str2 = "11"

print(bin_to_div(bin_str1, bin_str2))
```

**Output:**

100

# Decimal Conversions:

1) **Decimal to Binary**
2) **Decimal to Octal**
3) **Decimal to Hexadecimal**

## Decimal to Binary:
It is a function that converts decimal to binary from decimal number.

**Example:**

```py
import pynumsys as pns

dec_num = 115
print(dec_to_bin(dec_num))
```

**Output:**

1110011

## Decimal to Octal:
It is a function that converts decimal to octal from decimal number.

**Example:**

```py
import pynumsys as pns

dec_num = 115
print(dec_to_oct(dec_num))
```

**Output:**

163

## Decimal to Hexadecimal:
It is a function that converts decimal to hexadecimal from decimal number.

**Example:**

```py
import pynumsys as pns

dec_num = 115
print(dec_to_hex(dec_num))
```

**Output:**

73

# Octal Conversions:

1) **Octal to Binary**
2) **Octal to Decimal**
3) **Octal to Hexadecimal**

# Octal Operations:
1) **Octal Addition**
2) **Octal Subtraction:**
3) **Octal Multiplication:**
4) **Octal Division**

## Octal to Binary:
It is a function that converts octal to binary from octal input string.

**Example:**

```py
import pynumsys as pns

oct_str = "163"
print(oct_to_bin(oct_str))
```

**Output:**

1110011

## Octal to Decimal:
It is a function that converts octal to decimal from octal input string.

**Example:**

```py
import pynumsys as pns

oct_str = "163"
print(oct_to_dec(dec_num))
```

**Output:**

115

## Octal to Hexadecimal:
It is a function that converts octal to hexadecimal from octal input string.

**Example:**

```py
import pynumsys as pns

oct_str = "163"
print(oct_to_hex(bin_str))
```

**Output:**

73

## Octal Addition:
It is a function which returns addition of two octal numbers. It has three parameters **a**, **b** and **output**. **Output** parameter if for getting output
in another number systems by defualt the output is in octal.

**Example:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_add(a, b))
```

**Output in octal:**

333

**Output in binary:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_add(a, b, output="binary"))
```

**Output in decimal:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_add(a, b, output="decimal"))
```

**Output in hexadecimal:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_add(a, b, output="hexa"))
```

## Octal Subtraction:
It is a function which returns subtraction of two octal numbers. It has three parameters **a**, **b** and **output**. **Output** parameter for getting output
in another number systems, by defualt the output is in octal.

**Example:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_sub(a, b))
```

**Output in octal:**

013

**Output in binary:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_sub(a, b, output="binary"))
```

**Output in decimal:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_sub(a, b, output="decimal"))
```

**Output in hexadecimal:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_sub(a, b, output="hexa"))
```

## Octal Multiplication:
It is a function which returns multiplication of two octal numbers. It has three parameters **a**, **b** and **output**. **Output** parameter if for getting output
in another number systems by defualt the output is in octal.

**Example:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_mul(a, b))
```

**Output in octal:**

2EB8

**Output in binary:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_mul(a, b, output="binary"))
```

**Output in decimal:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_mul(a, b, output="decimal"))
```

**Output in hexadecimal:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_mul(a, b, output="hexa"))
```

## Octal Division:
It is a function which returns division of two octal numbers. It has four parameters **a**, **b**, **output** and **quot**. **Output** parameter for getting output
in another number systems by defualt the output is in octal and **quot** is a boolean parameter for getting quotient with remainder together in a tuple, naturally
this functions returns remainder only due to its defualt **quot** value **False** but if you want quoteint with remainder you can pass it **quot=True**.

**Example:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_div(a, b))
```

**Output in octal:**

13

**Output in binary:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_div(a, b, output="binary"))
```

**Output in decimal:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_div(a, b, output="decimal"))
```

**Output in hexadecimal:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_div(a, b, output="hexa"))
```

**With quot=True:**

```py
import pynumsys as pns

a = "163"
b = "150"

print(oct_div(a, b, quot=True))
```

**Output:**

(1, 13)

For more examples see [Examples](https://github.com/roshaan555/pynumsys/blob/main/Examples "Examples of funcions of pynumsys").


