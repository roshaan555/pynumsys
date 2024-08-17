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

For more examples see [Examples](https://github.com/roshaan555/pynumsys/blob/main/Examples "Examples of funcions of pynumsys").


