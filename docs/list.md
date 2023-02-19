# List

Indexing:
```
~n == (-n - 1)
~0 == (-0 - 1) == -1
~1 == (-1 - 1) == -2

digits = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10] 
digits[~1] # => 9

# Pattern
digits[~i] == digits[-i - 1]
```



# List Comprehension

```
[i for i in range(11)]
# [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# a-z with map()
az = [*map(chr, range(97, 123))]
# az => ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v' , 'w', 'x', 'y', 'z']

# A-Z with map()
AZ = [*map(chr, range(65, 91))]
# AZ => ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V' , 'W', 'X', 'Y', 'Z']

# a-z with chr()
az = [chr(i + 97) for i in range(26)]
# az => ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v' , 'w', 'x', 'y', 'z']

# A-Z with chr()
AZ = [chr(i + 65) for i in range(26)]
# AZ => ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V' , 'W', 'X', 'Y', 'Z']

```
