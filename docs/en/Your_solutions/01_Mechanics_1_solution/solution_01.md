# Projectile Motion

## Given

- Initial velocity: $v_0 = 100 \, m/s$
- Launch angle: $\theta = 37^\circ$
- Gravitational acceleration: $g = 9.81 \, m/s^2$

Velocity components:

$$
v_{0x} = v_0 \cos\theta
$$

$$
v_{0y} = v_0 \sin\theta
$$

---

# 1. Differential Equations of Motion

## Horizontal Motion

No horizontal force acts on the projectile:

$$
m\frac{d^2x}{dt^2} = 0
$$

$$
\frac{d^2x}{dt^2} = 0
$$

Integrating:

$$
\frac{dx}{dt} = v_{0x} = v_0\cos\theta
$$

$$
x(t) = v_0 \cos\theta \, t
$$

---

## Vertical Motion

Gravity acts downward:

$$
m\frac{d^2y}{dt^2} = -mg
$$

$$
\frac{d^2y}{dt^2} = -g
$$

Integrating:

$$
\frac{dy}{dt} = v_{0y} - gt
$$

$$
y(t) = v_{0y}t - \frac{1}{2}gt^2
$$

---

# 2. Time of Flight

The projectile returns to the ground when $y(t)=0$.

$$
T = \frac{2v_0\sin\theta}{g}
$$

Substitute values:

$$
T = \frac{2(100)\sin37^\circ}{9.81}
$$

$$
\sin37^\circ \approx 0.601
$$

$$
T = \frac{200 \times 0.601}{9.81}
$$

$$
T \approx 12.26 \, s
$$

---

# 3. Maximum Height

Maximum height occurs when vertical velocity becomes zero.

$$
H = \frac{v_0^2 \sin^2\theta}{2g}
$$

Substitute values:

$$
H = \frac{100^2 (0.601)^2}{2(9.81)}
$$

$$
H = \frac{10000 \times 0.361}{19.62}
$$

$$
H \approx 184 \, m
$$

---

# 4. Range

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

$$
\sin(74^\circ) \approx 0.961
$$

$$
R = \frac{100^2 \times 0.961}{9.81}
$$

$$
R \approx 979.6 \, m
$$

---

# Final Results

| Quantity | Value |
|---|---|
| Time of Flight | **12.26 s** |
| Maximum Height | **184 m** |
| Range | **979.6 m** |