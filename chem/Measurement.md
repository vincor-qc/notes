# Scientific Notation

**Scientific notation** simplifies displaying and comparing numbers; useful for very large/very small quantities.

## Steps

1. Write first non-zero digit followed by decimal point and then the rest of the numbers (e.g., 123 becomes 1.23)
2. Add appropriate power of ten ($10^x$). E.g. $1000 = 1.0 \times 10^3$, $0.00458 = 4.58 \times 10^{-3}$.

## Examples

a) $0.0075 = 7.5 \times 10^{-3}$
b) $0.00069 = 6.9 \times 10^{-4}$
c) $23850 = 2.385 \times 10^4$
d) $0.0058 \times 10^{-4} = 5.8 \times 10^{-7}$
e) $3.2 = 3.2 \times 10^0$.

Note that $0.25 \times 10^{-4}$, $23 \times 10^{-2}$ are not in scientific notation as $0.25$ and $23$ are not between 1 and 10.

## Adding/subtracting different exponents

Make the exponents same first (convert both to largest exponent.)

For example, $(5.19 \times 10^3) - (3.1 \times 10^2) = (5.19 \times 10^3) - (0.31 \times 10^3) = 4.88 \times 10^3.$

Another example: $(2.17 \times 10^{-3}) + (6.4 \times 10^{-5}) = (2.17 \times 10^{-3}) + (0.064 \times 10^{-3}) = 2.23 \times 10^{-3}.$

## Multiplying different exponents

Multiply the numbers together and add the exponents.

For example, $(2.00 \times 10^3)(4.00 \times 10^4) = 8.00 \times 10^7.$

## Dividing different exponents

Divide the numbers and subtract the exponents.

$\frac{9.60 \times 10^7}{1.60 \times 10^4} = 6.00 \times 10^3.$

# Significant Figures

Significant figures (s.f. or sigfigs for short) indicate how precise a measurement is. For physical properties like mass, time, volume, or length, there will always be some margin of error, so a perfectly precise measurement is impossible.

## Counting significant figures

**Rule 1a:** All non-zero digits are significant.

$123.456$ has 6 s.f.

**Rule 1b:** Zeros at the end of a number are insignificant *if no decimal point is shown.*

- $1000$ and $10$ both have 1 s.f.
- $1100$, $120$ and $10.$ have 2 s.f.
- $12500$ has 3 s.f.

**Rule 2:** A decimal point should not be used without a following digit BUT everything to the right of a decimal point is significant.

- $1.0$ has 3 s.f.
- $10$ has only 1 s.f.
- $100.0$ has 4 s.f.
- $10.$ has 2 s.f.

**Rule 3:** Captive zeros (between two non-zero digits) are significant.

E.g. $403$ and $103$ both have 3 s.f.

**Rule 4:** Leading zeros (to the left of a non-zero number) aren't significant (they are only placeholders)

$25$, $0.025$, and $0.0025$ all have two s.f.

**Rule 5:** Trailing zeros are significant and must be justified by the precision of the measuring equipment, if a decimal appears.

**Rule 6:** Exact numbers (like SI unit conversion factors) have an infinite number of s.f. and will not limit the precision of a calculation.

For example, the conversion rate $1\text{ inch} = 2.54\text{ cm}$ has $\infty$ s.f.

## Rounding: The Rule of 5

When rounding, consider the figure following (i.e., to the right of) the figure that is to be last. The figure you examine is the first figure to be dropped. E.g. when rounding $123$ to 2 s.f. $3$ is the first figure to be dropped.

Now:
- **If the figure is more than 5**, round up. E.g. $3.78721$ to 3 s.f. is $3.79$.
- **If the figure is equal to 5**, round the final number so it's even. E.g. $726.835$ rounded to 5 s.f. is $726.84$, $24.85$ rounded to 3 s.f. is $24.8$, not $24.9$.

## Measuring and s.f.

The number of s.f. is equal to all certain digits PLUS the first uncertain digit (which you estimate.)

For example, on a digital balance with a precision of $\pm 0.01 \text{g}$, the mass of one penny might be $2.35\text{g}$ and so its measurement with uncertainty would be $2.35 \pm 0.01\text{g}$.
