## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
def merge(dict1, dict2):
    merged_dict = {**dict1, **dict2}
    return merged_dict


dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'c': 300, 'd': 40, 'e': 50}

result = merge(dict1, dict2)

print("Merged Dictionary:", result)
```

## Output
Merged Dictionary: {'a': 10, 'b': 20, 'c': 300, 'd': 40, 'e': 50}

## Result
Thus, the Python program to merge two dictionaries was successfully executed.
