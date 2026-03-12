# Elimination of Time and Interpretation of Acceleration

The motion of the object is given in parametric form:

$$
x(t) = 2t^2, \qquad y(t) = 3t^3
$$

We will:

1. Eliminate the parameter $t$
2. Describe the trajectory
3. Compute velocity and acceleration vectors and their magnitudes
4. Determine whether acceleration is constant

---

# 1. Eliminate the Parameter $t$

From the equation for $x(t)$:

$$
x = 2t^2
$$

Solve for $t$:

$$
t^2 = \frac{x}{2}
$$

$$
t = \sqrt{\frac{x}{2}}
$$

Substitute into $y(t)$:

$$
y = 3t^3
$$

Since

$$
t^3 = t \cdot t^2
$$

$$
t^3 = \sqrt{\frac{x}{2}} \cdot \frac{x}{2}
$$

Thus

$$
y = 3 \cdot \frac{x}{2}\sqrt{\frac{x}{2}}
$$

So the Cartesian equation of the trajectory is

$$
y = \frac{3x}{2}\sqrt{\frac{x}{2}}
$$

---

# 2. Trajectory Description

The trajectory is a **curved path** where:

- $x$ grows proportional to $t^2$
- $y$ grows proportional to $t^3$

Thus the curve grows faster in the **$y$ direction** as time increases.

The motion starts at the origin when $t=0$.

---

# 3. Velocity Vector

Velocity is the derivative of the position vector.

Position vector:

$$
\vec r(t) = (2t^2)\hat{i} + (3t^3)\hat{j}
$$

Differentiate:

$$
\vec v(t) = \frac{d\vec r}{dt}
$$

Components:

$$
\frac{d}{dt}(2t^2) = 4t
$$

$$
\frac{d}{dt}(3t^3) = 9t^2
$$

Velocity vector:

$$
\vec v(t) = (4t)\hat{i} + (9t^2)\hat{j}
$$

---

# 4. Speed

The magnitude of velocity is

$$
|\vec v(t)| = \sqrt{(4t)^2 + (9t^2)^2}
$$

$$
|\vec v(t)| = \sqrt{16t^2 + 81t^4}
$$

$$
|\vec v(t)| = t\sqrt{16 + 81t^2}
$$

---

# 5. Acceleration Vector

Acceleration is the derivative of velocity.

$$
\vec a(t) = \frac{d\vec v}{dt}
$$

Differentiate components:

$$
\frac{d}{dt}(4t) = 4
$$

$$
\frac{d}{dt}(9t^2) = 18t
$$

Acceleration vector:

$$
\vec a(t) = 4\hat{i} + 18t\hat{j}
$$

---

# 6. Magnitude of Acceleration

$$
|\vec a(t)| = \sqrt{4^2 + (18t)^2}
$$

$$
|\vec a(t)| = \sqrt{16 + 324t^2}
$$

---

# 7. Is the Acceleration Constant?

The acceleration vector is

$$
\vec a(t) = 4\hat{i} + 18t\hat{j}
$$

Since the $y$ component depends on $t$, the acceleration **changes with time**.

Therefore:

**The acceleration is not constant.**