# Arithmetic Operations on ±17 and ±7
## Binary Representations (6-bit 2's Complement)

| Number | Binary Representation |
|--------|----------------------|
| +17 | `010001` |
| -17 | `101111` |
| +7 | `000111` |
| -7 | `111001` |

---

## 1. ADDITION

### Case 1: +17 + +7 = +24
```
  010001  (+17)
+ 000111  (+7)
  ------
  011000  (+24) ✅
```

### Case 2: +17 + -7 = +10
```
  010001  (+17)
+ 111001  (-7)
  ------
1 001010  (+10) ✅ (Carry discarded)
```

### Case 3: -17 + +7 = -10
```
  101111  (-17)
+ 000111  (+7)
  ------
  110110  (-10) ✅
```

### Case 4: -17 + -7 = -24
```
  101111  (-17)
+ 111001  (-7)
  ------
1 101000  (-24) ✅ (Carry discarded)
```

---

## 2. SUBTRACTION (Derived from Addition)

### Case 1: +17 - +7 = +17 + (-7) = **+10** (Case 2 above)

### Case 2: +17 - -7 = +17 + (+7) = **+24** (Case 1 above)

### Case 3: -17 - +7 = -17 + (-7) = **-24** (Case 4 above)

### Case 4: -17 - -7 = -17 + (+7) = **-10** (Case 3 above)

---
