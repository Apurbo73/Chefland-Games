# Chefland-Games

This C++ program checks whether four binary values are all zero for each test case and prints a result based on that.

---

### **Explanation:**

1. The program starts by reading an integer `T`, which represents the number of test cases.
2. For each test case, it reads four integers: `R1`, `R2`, `R3`, and `R4`. These values are usually 0 or 1.
3. It then checks:

   * If **all four values are 0**, it prints `"IN"` (meaning possibly *inside* or *inactive*).
   * Otherwise, if **any one is not 0**, it prints `"OUT"`.

---

### **Example Input:**

```
2
0 0 0 0
1 0 0 0
```

### **Output:**

```
IN
OUT
```

