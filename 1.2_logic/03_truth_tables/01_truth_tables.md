# Boolean expressions

## Completed tables

### Basic Completion

Output 1 = $A\times B$

Output 2 = $A+B$

| $A$ | $B$ | Output 1 | Output 2 |
|:---:|:---:|:---------:|:--------:|
| 0 | 0 |    0    |   0    |
| 0 | 1 |    0    |   1    |
| 1 | 0 |    0    |   1    |
| 1 | 1 |    1    |   1    |

### Compound Expression

Output 1 = $A + B$

Output 2 = $\overline C$

Output 3 = $(A + B) \times \overline C$

| $A$ | $B$ | $C$ | Output 1 | Output 2  | Output 3 |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 0 | 0 | 0 |   0    |   1    |         0          |
| 0 | 0 | 1 |   0    |   0    |         0          |
| 0 | 1 | 0 |   1    |   1    |         1          |
| 0 | 1 | 1 |   1    |   0    |         0          |
| 1 | 0 | 0 |   1    |   1    |         1          |
| 1 | 0 | 1 |   1    |   0    |         0          |
| 1 | 1 | 0 |   1    |   1    |         1          |
| 1 | 1 | 1 |   1    |   0    |         0          |


### Match the Expression

**Expressions:**
1. $A \land B$
2. $A \lor B$
3. $\neg A$
4. $A \oplus B$ (XOR)

**Truth Tables:**

**Table A**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   0    |

**Table B**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

**Table C**

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   1    |
| 1 | 0 |   1    |
| 1 | 1 |   1    |

**Table D**

| A | Output |
|---|--------|
| 0 |   1    |
| 1 |   0    |




## Expression matches

| Expression | Matching table | Explanation |
|---|---|---|
| 1. A AND B | Table B | 1 only when both inputs are 1. |
| 2. A OR B | Table C | 1 when at least one input is 1. |
| 3. NOT A | Table D | Reverses the input. |
| 4. A XOR B | Table A | 1 when the two inputs differ. |

Here, + means Boolean OR and × means Boolean AND. The bar over C means NOT C. Therefore, (A + B) × NOT C is 1 exactly when C is 0 and at least one of A or B is 1.
