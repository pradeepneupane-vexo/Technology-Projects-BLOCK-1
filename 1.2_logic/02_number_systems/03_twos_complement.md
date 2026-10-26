## Two's Complement
**Find the two's complement of the binary number:**
   - 101010
   - 110011
   - 1001

---

## Worked answers

Keep the original bit width, invert every bit, then add 1.

| Original | Inverted bits | Add 1 | Two's complement |
|---|---|---|---|
| 101010 (6 bits) | 010101 | 010101 + 000001 | 010110 |
| 110011 (6 bits) | 001100 | 001100 + 000001 | 001101 |
| 1001 (4 bits) | 0110 | 0110 + 0001 | 0111 |

If the originals are interpreted as signed two's complement numbers, they represent −22, −13, and −7. Their results represent +22, +13, and +7. Bit width matters: extending an unsigned number with zeroes before negating it would be a different calculation.
