
## Limits of Binary Representation
**Determine the limits of binary representation:**
   - Largest positive number with 8 bits in unsigned binary
   - Largest positive number with 8 bits in signed binary (two's complement)
   - Smallest negative number with 8 bits in signed binary (two's complement)

---

## Answers

| Question | Bit pattern | Decimal answer | Reason |
|---|---|---|---|
| Largest unsigned 8-bit number | 11111111₂ | 255 | 2⁸ − 1 |
| Largest positive signed 8-bit two's complement number | 01111111₂ | 127 | 2⁷ − 1 |
| Smallest negative signed 8-bit two's complement number | 10000000₂ | −128 | −2⁷ |

Unsigned 8-bit values range from 0 to 255. Signed 8-bit two's complement values range from −128 to 127. In two's complement the highest bit has weight −128; the other bits have positive weights 64, 32, 16, 8, 4, 2, and 1. The signed range has one more negative value because zero uses one of the nonnegative patterns.
