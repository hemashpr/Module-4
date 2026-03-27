## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```python
dict1 = eval(input())
dict2 = eval(input())

def merge(d1, d2):
    return {**d1, **d2}

result = merge(dict1, dict2)
print(result)
```

## Output

<img width="950" height="216" alt="image" src="https://github.com/user-attachments/assets/c4ba551d-d377-4af3-b228-a15cbb3cad27" />

<img width="637" height="228" alt="image" src="https://github.com/user-attachments/assets/6032f7f4-5e00-4abe-ac6b-86ec93aae4ff" />


## Result

Thus , the program has been executed succesfully.

