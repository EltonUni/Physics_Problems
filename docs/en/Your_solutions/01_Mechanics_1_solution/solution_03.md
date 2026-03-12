# Path Intersection

Alice and Bob move along the following parametric paths:

- Alice: $A(t) = (2+t,\; 8-3t)$  
- Bob: $B(t) = (2t-1,\; 2t+2)$  

We want to determine:

1. Whether their paths intersect (collision).
2. If not, the **minimum distance** between them and when it occurs.

---

# 1. Check for Collision

For a collision, their coordinates must be equal **at the same time $t$**.

## X-coordinates

$$
2 + t = 2t - 1
$$

$$
t = 3
$$

## Y-coordinates

$$
8 - 3t = 2t + 2
$$

$$
6 = 5t
$$

$$
t = \frac{6}{5}
$$

Since

$$
t = 3 \neq \frac{6}{5}
$$

the two equations are **not satisfied simultaneously**.

Therefore, **Alice and Bob do not collide**.

---

# 2. Distance Between Them

Distance between two moving points:

$$
d(t) = \sqrt{(x_A - x_B)^2 + (y_A - y_B)^2}
$$

Coordinates difference:

$$
x_A - x_B = (2+t) - (2t-1) = 3 - t
$$

$$
y_A - y_B = (8-3t) - (2t+2) = 6 - 5t
$$

Distance:

$$
d(t) = \sqrt{(3 - t)^2 + (6 - 5t)^2}
$$

---

# 3. Minimize Distance

Minimize the squared distance:

$$
D(t) = (3 - t)^2 + (6 - 5t)^2
$$

Expand:

$$
D(t) = 9 - 6t + t^2 + 36 - 60t + 25t^2
$$

$$
D(t) = 26t^2 - 66t + 45
$$

Take derivative:

$$
\frac{dD}{dt} = 52t - 66
$$

Set to zero:

$$
52t - 66 = 0
$$

$$
t = \frac{66}{52} = \frac{33}{26} \approx 1.27
$$

---

# 4. Minimum Distance

Compute coordinates at $t = \frac{33}{26}$.

### Alice

$$
x_A = 2 + \frac{33}{26} = \frac{85}{26}
$$

$$
y_A = 8 - 3\left(\frac{33}{26}\right) = \frac{109}{26}
$$

### Bob

$$
x_B = 2\left(\frac{33}{26}\right) - 1 = \frac{20}{13}
$$

$$
y_B = 2\left(\frac{33}{26}\right) + 2 = \frac{59}{13}
$$

Distance components:

$$
x_A - x_B = \frac{45}{26}
$$

$$
y_A - y_B = -\frac{9}{26}
$$

Minimum distance:

$$
d_{min} =
\sqrt{\left(\frac{45}{26}\right)^2 + \left(\frac{9}{26}\right)^2}
$$

$$
d_{min} =
\frac{\sqrt{2106}}{26}
\approx 1.76
$$

---

# Final Result

- **Alice and Bob do not collide.**
- The **minimum distance** between them is:

$$
d_{min} \approx 1.76
$$

- This occurs at:

$$
t = \frac{33}{26} \approx 1.27
$$
