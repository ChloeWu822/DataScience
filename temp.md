To find the **expected value (EV)** and **variance** for the continuous random variable with the probability density function (PDF) $f(x) = x^2$ for $1 \leq x \leq 3$, we need to follow these steps:

### Step 1: Verify the PDF
First, ensure that the PDF $f(x) = x^2$ is properly normalized by integrating it over the range $[1, 3]$ and checking that the integral equals 1:

$
\int_1^3 f(x) \, dx = \int_1^3 x^2 \, dx = \left[ \frac{x^3}{3} \right]_1^3 = \frac{27}{3} - \frac{1}{3} = \frac{26}{3}
$

To normalize, we divide by $\frac{26}{3}$, so the normalized PDF is:

$
f(x) = \frac{3}{26} x^2 \quad \text{for} \quad 1 \leq x \leq 3
$

### Step 2: Compute the Expected Value $E[X]$

The expected value is given by:

$
E[X] = \int_1^3 x f(x) \, dx
$

Substituting the normalized PDF $f(x) = \frac{3}{26} x^2$:

$
E[X] = \int_1^3 x \left( \frac{3}{26} x^2 \right) dx = \frac{3}{26} \int_1^3 x^3 \, dx
$

Now compute the integral:

$
\int_1^3 x^3 \, dx = \left[ \frac{x^4}{4} \right]_1^3 = \frac{81}{4} - \frac{1}{4} = \frac{80}{4} = 20
$

Thus,

$
E[X] = \frac{3}{26} \times 20 = \frac{60}{26} = \frac{30}{13}
$

So, the **expected value (mean)** is:

$
E[X] = \frac{30}{13}
$

### Step 3: Compute the Expected Value of $X^2$, i.e., $E[X^2]$

Now, we compute $E[X^2]$, which is given by:

$
E[X^2] = \int_1^3 x^2 f(x) \, dx
$

Substitute the normalized PDF $f(x) = \frac{3}{26} x^2$:

$
E[X^2] = \int_1^3 x^2 \left( \frac{3}{26} x^2 \right) dx = \frac{3}{26} \int_1^3 x^4 \, dx
$

Now compute the integral:

$
\int_1^3 x^4 \, dx = \left[ \frac{x^5}{5} \right]_1^3 = \frac{243}{5} - \frac{1}{5} = \frac{242}{5}
$

Thus,

$
E[X^2] = \frac{3}{26} \times \frac{242}{5} = \frac{726}{130} = \frac{363}{65}
$

### Step 4: Compute the Variance $\text{Var}(X)$

Variance is given by:

$
\text{Var}(X) = E[X^2] - (E[X])^2
$

Substitute the values of $E[X^2]$ and $E[X]$:

$
\text{Var}(X) = \frac{363}{65} - \left( \frac{30}{13} \right)^2
$

Now, compute $\left( \frac{30}{13} \right)^2$:

$
\left( \frac{30}{13} \right)^2 = \frac{900}{169}
$

Now, subtract:

$
\text{Var}(X) = \frac{363}{65} - \frac{900}{169}
$

To subtract these fractions, find a common denominator. The least common denominator of 65 and 169 is 65 × 169 = 10985:

$
\frac{363}{65} = \frac{363 \times 169}{10985} = \frac{61347}{10985}
$
$
\frac{900}{169} = \frac{900 \times 65}{10985} = \frac{58500}{10985}
$

Now, subtract:

$
\text{Var}(X) = \frac{61347}{10985} - \frac{58500}{10985} = \frac{2847}{10985}
$

Thus, the **variance** is:

$
\text{Var}(X) = \frac{2847}{10985}
$

### Final Answer:
- **Expected Value (EV):** $E[X] = \frac{30}{13}$
- **Variance:** $\text{Var}(X) = \frac{2847}{10985}$