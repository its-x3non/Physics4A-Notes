
## Precision vs. Accuracy
- **Accuracy** - How close is the measured value of a quantity to the true value?
- **Precision** - How consistent are repeated measurements of the quantity?
- **Dartboard Analogy** - The center represents the true value, the points on the board represent different measurements.

### Measurement Precision
There are limits to how precise a measurement can be, due to a number of factors:
- Human Error
- Unpredictable experimental conditions
- Imperfectly manufactured measurement devices
- Least count of measurement devices
The smallest value that can be measured using a given device is called the <u>Least Count</u>. This is often the limiting factor in the provision of a measurement.

## Significant Figures
The number of <u>significant figures</u> (sig figs) is the number of digits we *actually* know, given the precision of the measurement that was made.

### Counting Sig Figs
**Rule 1:** If there is a decimal point in the number, don't count the leading zeros before the first non-zero digit.
**Example:** 0.00**12** has **2** significant figures
**Rule 2:** If there is no decimal point in the number, don't count trailing zeros after the last non-zero digit.
Example: **123**00 has **3** significant figures

## Scientific Notation
Written in <u>scientific notation</u>, a number has a coefficient and an exponent:
- The <u>coefficient</u> is a factor between 1 and 10
- The <u>exponent</u> is a whole-number power of 10
- The number of significant figures is just the number of significant figures in the coefficient
**Example:** 0.00134 -> 1.34x10<sup>-3</sup>

## Sig Figs Mathematics
### Addition and Subtraction
**Rule:** round the number to the smallest number of decimal places of all the numbers involved in the calculation. **<u>(To the Tenths)</u>**
**Example:** 0.12 + 1.2 = 1.32 → 1.3
**Example:** 0.12- 0.021 = 0.099 → 0.10

### Multiplication and Division
**Rule:** Round the answer to the smaller number of sig figs of all numbers involved in the calculation.
**Example:** 12.0 * 0.23 = 2.76 → 2.8 (2 sig figs)
**Example:** 1.3/0.003 = 433.333 → 400 (1 sig fig)

### More Complex Calculations
For a mix of operations (i.e., addition and multiplication), simply follow the standard order of operations and use the rules for rounding to the proper number of sig figs at each step
**Example:** (2.145+2.13)/1.54 = 4.275/1.54 --> 2.776

When using any other functions (cos, log, etc.), round the calculation to the same number of significant figures as the input.
**Example:** ln(4.57) + 1.3 = 1.541 + 1.3 = 2.841 → 2.8

### Formulae
Consider numerical factors in a formula to be exact, known an infinite number of significant figures.
They should not affect the final number of significant figures after making a calculation using a formula
**Example:** Calculating the area of a triangle $$A = 1/2(b*h)$$The number of significant figures in A depends only on the number of significant figures in b and h, not the ½ factor.

