# Range Optimization in Projectile Motion

## Given

The range of a projectile (without air resistance) is

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

where:

- $v_0$ = initial velocity  
- $\theta$ = launch angle  
- $g$ = gravitational acceleration  

We want to **find the value of $\theta$ that maximizes the range**.

---

# 1. Differentiate the Range Function

To find the maximum, take the derivative of $R(\theta)$ with respect to $\theta$.

$$
R(\theta) = \frac{v_0^2}{g}\sin(2\theta)
$$

Since $\frac{v_0^2}{g}$ is constant:

$$
\frac{dR}{d\theta} = \frac{v_0^2}{g}\frac{d}{d\theta}[\sin(2\theta)]
$$

Derivative of $\sin(2\theta)$:

$$
\frac{d}{d\theta}\sin(2\theta) = 2\cos(2\theta)
$$

Therefore:

$$
\frac{dR}{d\theta} = \frac{v_0^2}{g}(2\cos(2\theta))
$$

---

# 2. Find Critical Points

For maximum or minimum values:

$$
\frac{dR}{d\theta} = 0
$$

Thus:

$$
\frac{v_0^2}{g}(2\cos(2\theta)) = 0
$$

Since $\frac{v_0^2}{g} \neq 0$:

$$
\cos(2\theta) = 0
$$

---

# 3. Solve for the Angle

Cosine is zero when:

$$
2\theta = 90^\circ
$$

Therefore:

$$
\theta = 45^\circ
$$

---

# 4. Verification (Maximum)

The range depends on $\sin(2\theta)$.

The maximum value of sine is:

$$
\sin(2\theta) = 1
$$

This occurs when:

$$
2\theta = 90^\circ
$$

which gives:

$$
\theta = 45^\circ
$$

---

# Final Result

The **maximum range** occurs at:

$$
\theta = 45^\circ
$$

The maximum range value is therefore:

$$
R_{\text{max}} = \frac{v_0^2}{g}
$$