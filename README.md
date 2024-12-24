# Python-For-Beginners


# Python Built-in Data Types

Python includes the following categories of built-in data types:

## Categories:
1. **String Type (`str`)**
2. **Boolean Type (`bool`)**
3. **Binary Types (`bytes`, `bytearray`, `memoryview`)**
4. **Number Types (`int`, `float`, `complex`)**
5. **Sequence Types (`list`, `range`, `tuple`)**
6. **Set Types (`set`, `frozenset`)**
7. **Dictionary Type (`dict`)**

## Python Code Examples

### 1. **String Type (`str`)**

```python
# `str`: Represents text
greeting = "Hello, World!"

print(f"String Example: {greeting}")

```
### Explanation:
`greeting` is assigned a string value `"Hello, World!"`.

The `print()` function is used to display the value of `greeting`.

#### Expected Outcome:
```python
String Example: Hello, World!
```


### 2. **Boolean Type (`bool`)**
```python
# `bool`: Represents True or False
is_active = True

print(f"Boolean Example: is_active = {is_active}")
```

#### Explanation:
The `variable is_active` is assigned a boolean value `True`.

The `print()` function is used to display the boolean value of `is_active`.

### Expected Outcome:
```python
Boolean Example: is_active = True
```



### 3. Number Types (int, float, complex)
```python
# `int`: Whole numbers
age = 42

# `float`: Decimal numbers
pi = 3.14

# `complex`: Numbers with real and imaginary parts
z = 2 + 3j

print(f"int Example: {age}")
print(f"float Example: {pi}")
print(f"complex Example: {z}")
```

### Explanation:

`age` is an `int` with the value `42`.

`pi` is a `float` representing the value of Pi `(3.14)`.

`z` is a `complex` number with a real part of `2` and an imaginary part of `3`.

#### Expected Outcome:
```python
int Example: 42
float Example: 3.14
complex Example: (2+3j)

```


### 4. Sequence Types (list, range, tuple)
```python
# `list`: Ordered, mutable collection
numbers = [1, 2, 3]

# `range`: Immutable sequence of numbers
r = range(5)

# `tuple`: Ordered, immutable collection
coordinates = (1, 2, 3)
print(f"list Example: {numbers}")
print(f"range Example: {list(r)}")
print(f"tuple Example: {coordinates}")
```

### Explanation:

`numbers` is a `list`, which is an ordered, mutable collection of numbers.

`r` is a `range`, which generates a sequence of numbers from `0` to `4`.

`coordinates` is a `tuple`, an ordered, immutable collection of numbers.


#### Expected Outcome:
```python
list Example: [1, 2, 3]
range Example: [0, 1, 2, 3, 4]
tuple Example: (1, 2, 3)
```


### 5. Set Types (set, frozenset)

```python
# `set`: Unordered collection of unique items
unique_numbers = {1, 2, 3}

# `frozenset`: Immutable version of a set
frozen_numbers = frozenset([1, 2, 3])
print(f"set Example: {unique_numbers}")
print(f"frozenset Example: {frozen_numbers}")

```

### Explanation:
`unique_numbers` is a `set`, which is an unordered collection of unique numbers. Duplicate values are automatically removed.

`frozen_numbers` is a `frozenset`, which is similar to a set but immutable.

#### Expected Outcome:
```python
set Example: {1, 2, 3}
frozenset Example: frozenset({1, 2, 3})
```


### 6. Dictionary Type (dict)

```python
# `dict`: Collection of key-value pairs
person = {"name": "Alice", "age": 25}
print(f"dict Example: {person}")

```


### Explanation:

`person` is a `dict` that stores key-value pairs. The keys are `"name"` and `"age"`, and the corresponding values are `"Alice"` and `25`.

#### Expected Outcome:
```python

dict Example: {'name': 'Alice', 'age': 25}
```


### 7. Binary Types (bytes, bytearray, memoryview)
```python
# `bytes`: Immutable sequence of bytes
data = b"hello"
print(f"bytes Example: {data}")

# `bytearray`: Mutable sequence of bytes
mutable_data = bytearray(b"hello")
print(f"bytearray Example: {mutable_data}")

# `memoryview`: Provides a view of a binary object
view = memoryview(b"hello")
print(f"memoryview Example: {view.tobytes()}")

```


### Explanation:

`data` is a `bytes` object that contains the bytes representation of the string `"hello"`.

`mutable_data` is a `bytearray`, which is mutable and contains the same bytes as data.

`view` is a `memoryview` of the byte string `"hello"`, which allows access to the data without copying it.


#### Expected Outcome:
```python
bytes Example: b'hello'
bytearray Example: bytearray(b'hello')
memoryview Example: b'hello'
```





