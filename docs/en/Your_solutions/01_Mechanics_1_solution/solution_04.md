# Vector Calculus

The position vector of the object is

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

We want to find:

1. Velocity vector  
2. Acceleration vector  

---

# 1. Velocity Vector

Velocity is the **time derivative of the position vector**.

$$
\vec{v}(t) = \frac{d\vec{r}(t)}{dt}
$$

Differentiate each component.

### x-component

$$
\frac{d}{dt}(3t^2) = 6t
$$

### y-component

$$
\frac{d}{dt}(5t - 8t^2) = 5 - 16t
$$

Therefore,

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

---

# 2. Acceleration Vector

Acceleration is the **time derivative of velocity**.

$$
\vec{a}(t) = \frac{d\vec{v}(t)}{dt}
$$

Differentiate each component again.

### x-component

$$
\frac{d}{dt}(6t) = 6
$$

### y-component

$$
\frac{d}{dt}(5 - 16t) = -16
$$

Therefore,

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$

---

# Final Results

Velocity vector:

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

Acceleration vector:

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$