## Repository Structure

```text
python-functions-and-strings/
├── README.md
├── 01_functions_fundamentals.py
└── 02_strings_lists_tuples.py
```

## Lecture Files

| File | Concepts |
|---|---|
| `01_functions_fundamentals.py` | Function definition and calls, parameters, arguments, defaults, `print()` vs `return`, scope, `*args`, `**kwargs`, validation, reusable function design |
| `02_strings_lists_tuples.py` | Quotes, indexing, slicing, immutability, f-string formatting, string cleaning, `split()` and `join()`, lists, list methods, list comprehension, tuples, unpacking |



## Key Concepts

### Functions

Functions organize code into reusable blocks. Parameters receive information; `return` sends a result back to the caller.

```python
def calculate_total(price: float, quantity: int) -> float:
    return price * quantity

bill = calculate_total(250, 3)
print(bill)
```

### `print()` vs `return`

| `print()` | `return` |
|---|---|
| Displays information on the screen | Sends a value back to the caller |
| Useful for messages and output | Useful when a result must be stored, reused, or tested |

### Strings

Strings store text. They support indexing and slicing, but are immutable: individual characters cannot be changed in place. Create a new string when modifying text.

### Lists

Lists are ordered, mutable collections. Use methods such as `append()`, `insert()`, `remove()`, and `pop()` to manage items.

### Tuples

Tuples are ordered, immutable collections. They are useful for fixed records and support unpacking into variables.
