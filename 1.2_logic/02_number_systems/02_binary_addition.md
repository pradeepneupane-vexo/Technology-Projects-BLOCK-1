## Adding Binary Numbers
   - 1011 + 1101
   - 100110 + 101011
   - 11101 + 10111

## Subtracting Binary Numbers
   - 1101 - 1010
   - 10110 - 1001
   - 10001 - 1110

---

## Worked answers

### Addition

| Calculation | Binary result | Decimal check |
|---|---|---|
| 1011 + 1101 | 11000 | 11 + 13 = 24 |
| 100110 + 101011 | 1010001 | 38 + 43 = 81 |
| 11101 + 10111 | 110100 | 29 + 23 = 52 |

Binary addition uses 0 + 0 = 0, 0 + 1 = 1, and 1 + 1 = 10 (write 0 and carry 1). Adding 1 + 1 with a carry of 1 gives 11 (write 1 and carry 1). Keep the final carry, allowing the result to use an extra bit.

### Subtraction

| Calculation | Binary result | Decimal check |
|---|---|---|
| 1101 − 1010 | 0011 | 13 − 10 = 3 |
| 10110 − 01001 | 01101 | 22 − 9 = 13 |
| 10001 − 01110 | 00011 | 17 − 14 = 3 |

Align the numbers on the right and pad the shorter number with leading zeroes. When subtracting 1 from 0, borrow from the next available higher bit. The current column then has 10₂, so 10₂ − 1₂ = 1₂.
