
## Fixed Point Representation
**Represent the decimal number in fixed-point binary:**
   - 12.75 with 4 bits for the integer part and 4 bits for the fractional part
   - 5.125 with 3 bits for the integer part and 5 bits for the fractional part
   - 7.5 with 4 bits for the integer part and 4 bits for the fractional part

---

## Worked answers

Assume **unsigned** fixed point: all stated integer bits represent magnitude and no separate sign bit is reserved. The binary point is implied between the two fields.

| Decimal | Integer bits | Fractional bits | Fixed-point binary | Stored 8-bit pattern |
|---|---|---|---|---|
| 12.75 | 4 | 4 | 1100.1100₂ | 11001100 |
| 5.125 | 3 | 5 | 101.00100₂ | 10100100 |
| 7.5 | 4 | 4 | 0111.1000₂ | 01111000 |

Fractional place values are 1/2, 1/4, 1/8, 1/16, and so on.

- **12.75:** 12 = 1100₂ and 0.75 = 1/2 + 1/4 = .1100₂. Stored integer 204 divided by 2⁴ gives 12.75.
- **5.125:** 5 = 101₂ and 0.125 = 1/8 = .00100₂. Stored integer 164 divided by 2⁵ gives 5.125.
- **7.5:** 7 = 0111₂ and 0.5 = 1/2 = .1000₂. Stored integer 120 divided by 2⁴ gives 7.5.

All three values are represented exactly; no rounding is required.
