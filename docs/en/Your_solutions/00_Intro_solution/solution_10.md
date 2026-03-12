# Infinite Series Problem

An ant starts at the **origin (0,0)** and moves in the following pattern:

- $1$ m east  
- $\frac{1}{2}$ m north  
- $\frac{1}{3}$ m west  
- $\frac{1}{4}$ m south  
- $\frac{1}{5}$ m east  
- and so on.

Find the **final position of the ant**.

---

# Step 1: Understand the pattern

The ant moves in four repeating directions:

1. **East**
2. **North**
3. **West**
4. **South**

The distances follow the pattern:

$$
1,\ \frac{1}{2},\ \frac{1}{3},\ \frac{1}{4},\ \frac{1}{5},\ \frac{1}{6},\dots
$$

So every step is $\frac{1}{n}$ meters.

We separate the motion into **x-direction (east-west)** and **y-direction (north-south)**.

---

# Step 2: Horizontal movement (x-direction)

East is **positive x**, west is **negative x**.

So the horizontal movement is:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \frac{1}{9} - \dots
$$

This is a well-known infinite series:

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$

This series converges to:

$$
\frac{\pi}{4}
$$

So the final **x-coordinate** is:

$$
x = \frac{\pi}{4}
$$

---

# Step 3: Vertical movement (y-direction)

North is **positive y**, south is **negative y**.

So the vertical movement is:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \frac{1}{10} - \dots
$$

Factor out $\frac{1}{2}$:

$$
y = \frac{1}{2}\left(1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots\right)
$$

The series inside the parentheses is the **alternating harmonic series**, which equals:

$$
\ln(2)
$$

So:

$$
y = \frac{1}{2}\ln(2)
$$

---

# Step 4: Final position

The final position of the ant is:

$$
\left(\frac{\pi}{4},\ \frac{1}{2}\ln(2)\right)
$$

---

# Step 5: Approximate numerical value (optional for explanation)

Using numerical values:

$$
\frac{\pi}{4} \approx 0.785
$$

$$
\frac{1}{2}\ln(2) \approx 0.347
$$

So approximately:

$$
(0.785,\ 0.347)
$$

---

# Final Answer

The ant approaches the position

$$
\left(\frac{\pi}{4},\ \frac{1}{2}\ln(2)\right)
$$

from the origin.

---