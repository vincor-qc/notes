# Accuracy vs Precision

**Accuracy:** An accurate measurement is close to the actual value.

**Precise:** A precise measurement is _reproducible_. For the purposes of IB chemistry, more s.f. equates to higher precision

An instrument may be precise yet inaccurate; this occurs when it hasn't been calibrated properly. (For example, a scale could be incorrectly configured so it starts at $1$ instead of $0$. In this case, all the measurements it yields would be precise and reproducible but be off by $1$ from the actual value.)

## Quantifying
**Accuracy:**

Accuracy can be quantified by:
$$
\text{percent deviation} = \frac{|\text{experimental} - \text{theoritical}|}{\text{theoritical}} \times 100
$$
- Ensure that you zero measuring devices
- Ensure to take parallax into account


**Precision:**

In IB Physics, we will use:
$$
\text{uncertainty} = \frac{\text{range}}{2}
$$
For analogue devices, we can use $\frac{1}{2}$ the smallest division as a good estimate.
- E.g. A ruler would have ±0.5mm

For digital devices, use ±1 of the smallest division.
- E.g. A stopwatch would have ±0.1s

## Examples

Assume that the actual width of a room is $\pu{5.32000 m}$, and the following measurements are obtained:

1. $\pu{5.45217 m}$: not close to actual value, so not accurate. However, measurement has many s.f. so it's precise.
2. $\pu{5.32001 m}$: close to actual value and has many s.f., so both accurate and precise.
3. $\pu{5.3 m}$: close to actual value but does not have many s.f., so accurate but imprecise.
5. $\pu{7.1 m}$: not close to actual value and does not have many s.f., so neither accurate nor precise.


# Uncertainty Rules
 1. When you add or substract values, you must add the absolute uncertainty.
	 - The absolute uncertainty is just a number, so in $1 ± 0.1$, the absolute uncertainty is ±0.1 
 2. When you multiply or divide values, you must add the percent uncertainty 
	 - The percentage uncertainty is $\frac{\text{uncertainty}}{value}$, so in $1 ±0.1$, the percent uncertainty is $\frac{0.1}{1} = \text{10\%}$

## Uncertainty and s.f.
 1. The number of digits in a measurement indicate the uncertainty. If no uncertainty is given, the digits imply the uncertainty.
	- $\pu{2.0m}$ imples the uncertainty is $±\pu{0.1m}$
	- $\pu{2.01m}$ imples the uncertainty is $±\pu{0.01m}$
2. If the uncertainty is given, round the value to the uncertainty
	- If a value of $\pu{20.01m}$ is given with an uncertainty of $\pu{\pm0.1m}$, then the value should be rounded to $\pu{20.0 ± 0.1m}$

**The uncertainty must have only one non-zero digit!**