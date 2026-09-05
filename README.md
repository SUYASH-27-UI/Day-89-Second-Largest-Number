# Day-89-Second-Largest-Number
# Python Day 89 - Second Largest Number

This program finds the second largest number from a list.

## Example

Input:

```text
[10, 25, 7, 40, 15]
```

Output:

```text
Second largest number: 25
```

## Concepts Used

* Lists
* `max()` function
* `remove()` method
* Variables
* `print()` function

## How It Works

1. Find the largest number using `max()`.
2. Remove the largest number using `remove()`.
3. Find the maximum number again.
4. The result is the second largest number.

## Python Code

```python
numbers = [10, 25, 7, 40, 15]

largest = max(numbers)

numbers.remove(largest)

second_largest = max(numbers)

print("Second largest number:", second_largest)
```
