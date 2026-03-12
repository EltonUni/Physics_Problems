# Variable Velocity

The velocity of the object is

$$
v(t) = t^2 + 2t - 5
$$

Initial condition:

- Position at $t=0$ is $x(0) = 4$

We want to find:

1. Position function $x(t)$
2. Position at $t=3$
3. Acceleration at $t=3$

---

# 1. Find the Position Function

Velocity is the derivative of position:

$$
v(t) = \frac{dx}{dt}
$$

Thus,

$$
\frac{dx}{dt} = t^2 + 2t - 5
$$

Integrate to find $x(t)$:

$$
x(t) = \int (t^2 + 2t - 5)\,dt
$$

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + C
$$

---

# 2. Determine the Constant $C$

Using the initial condition $x(0)=4$:

$$
4 = \frac{0^3}{3} + 0^2 - 5(0) + C
$$

$$
C = 4
$$

So the position function becomes:

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

---

# 3. Position at $t=3$

Substitute $t=3$:

$$
x(3) = \frac{3^3}{3} + 3^2 - 5(3) + 4
$$

$$
x(3) = \frac{27}{3} + 9 - 15 + 4
$$

$$
x(3) = 9 + 9 - 15 + 4
$$

$$
x(3) = 7
$$

---

# 4. Acceleration Function

Acceleration is the derivative of velocity:

$$
a(t) = \frac{dv}{dt}
$$

Differentiate:

$$
a(t) = 2t + 2
$$

---

# 5. Acceleration at $t=3$

$$
a(3) = 2(3) + 2
$$

$$
a(3) = 8
$$

---

# Final Results

| Quantity | Value |
|---|---|
| Position function | $x(t) = \frac{t^3}{3} + t^2 - 5t + 4$ |
| Position at $t=3$ | $x(3) = 7$ |
| Acceleration function | $a(t) = 2t + 2$ |
| Acceleration at $t=3$ | $a(3) = 8$ |