# Optimization Problem

A rectangle is under the curve

$$
y = 3 - x^2
$$

in the **first quadrant**. Find the dimensions of the rectangle with the **maximum area**.

---

# Step 1: Understand the geometry

We are working in the **first quadrant**, so:

- $x \ge 0$
- $y \ge 0$

Assume the **top right corner of the rectangle** touches the curve.

So the point is:

$$
(x, y)
$$

Because it lies on the curve,

$$
y = 3 - x^2
$$

The rectangle has:

- **width:** $x$
- **height:** $y = 3 - x^2$

---

# Step 2: Write the area function

Area of a rectangle:

$$
A = \text{width} \times \text{height}
$$

So:

$$
A(x) = x(3 - x^2)
$$

Expand the function:

$$
A(x) = 3x - x^3
$$

---

# Step 3: Find the derivative

To maximize the area we compute the derivative:

$$
A'(x) = \frac{d}{dx}(3x - x^3)
$$

$$
A'(x) = 3 - 3x^2
$$

Now set the derivative equal to zero:

$$
3 - 3x^2 = 0
$$

Divide by 3:

$$
1 - x^2 = 0
$$

$$
x^2 = 1
$$

$$
x = 1
$$

Since we are in the first quadrant, we take the **positive value**.

---

# Step 4: Find the height

Substitute $x = 1$ into the equation of the curve:

$$
y = 3 - x^2
$$

$$
y = 3 - 1^2
$$

$$
y = 2
$$

---

# Step 5: Dimensions of the rectangle

The rectangle with the **maximum area** has:

- **Width:** $x = 1$
- **Height:** $y = 2$

---

# Step 6: Verify it is a maximum

Second derivative:

$$
A''(x) = \frac{d}{dx}(3 - 3x^2)
$$

$$
A''(x) = -6x
$$

Evaluate at $x = 1$:

$$
A''(1) = -6 < 0
$$

Since the second derivative is negative, the area is **maximum**.

---

# Final Answer

The rectangle with the maximum area has dimensions:

$$
1 \times 2
$$

Maximum area:

$$
A_{max} = 1 \cdot 2 = 2
$$