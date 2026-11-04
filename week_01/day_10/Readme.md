# Day 010 – Basic Recursion in Python

## Concepts Learned

### 1. Recursion
- Understanding recursion
- Function calling itself
- Recursive problem-solving
- Recursive function execution

### 2. Base Case
- Understanding the base condition
- Stopping recursive calls
- Preventing infinite recursion

### 3. Call Stack
- Understanding function call stack
- How recursive calls are stored
- Returning from recursive calls
- Stack execution flow

### 4. Types of Recursion

**Parameterized Recursion**
- Passing parameters during recursive calls.
- Updating values through function arguments.

**Functional Recursion**
- Returning calculated values from recursive calls.
- Combining results using return statements.

## LeetCode Problems

### 1. Add Digits
- Problem: [LeetCode 258 – Add Digits](https://leetcode.com/problems/add-digits/)
- Pattern: Digit Manipulation
- Revision: Re-solve without notes.

### 2. Print 1 to N Using Recursion
- Pattern: Basic Recursion
- Concepts: Base case, recursive calls and call stack.

### 3. Fibonacci Number
- Problem: [LeetCode 509 – Fibonacci Number](https://leetcode.com/problems/fibonacci-number/)
- Pattern: Recursion
- Concepts: Recursive function, base cases and Fibonacci sequence.

## Fibonacci Series

The Fibonacci sequence is calculated by adding the previous two numbers.

Example:
```text
0, 1, 1, 2, 3, 5, 8, 13, 21
```

Python implementation:
```python
def fib(n):
    if n <= 1:
        return n

    return fib(n - 1) + fib(n - 2)
```

## Print 1 to N Using Recursion

```python
def print_numbers(n):
    if n == 0:
        return

    print_numbers(n - 1)
    print(n)

print_numbers(5)
```

Output:
```text
1
2
3
4
5
```

## Pattern Recognition

| Problem clue | Pattern |
|---|---|
| Function calls itself | Recursion |
| Condition to stop calls | Base case |
| Function calls stored in memory | Call stack |
| Passing updated arguments | Parameterized recursion |
| Returning calculated results | Functional recursion |
| Previous two numbers | Fibonacci |

## Learning Outcome

Learned basic recursion, base cases, call stack execution, parameterized recursion and functional recursion using Python.

