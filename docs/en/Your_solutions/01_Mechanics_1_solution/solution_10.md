# Kinematics

The motion of point \(M\) is given by

$$
\vec r(t) = (a\cos(\omega t),\; b\sin(\omega t),\; bt)
$$

where \(a,b,\omega>0\).

---

# a) Equation of the Trajectory

From the parametric equations

$$
x(t)=a\cos(\omega t), \qquad y(t)=b\sin(\omega t), \qquad z(t)=bt
$$

Eliminate \(t\) between \(x\) and \(y\):

$$
\frac{x}{a}=\cos(\omega t), \qquad \frac{y}{b}=\sin(\omega t)
$$

Using the identity \(\cos^2+\sin^2=1\):

$$
\left(\frac{x}{a}\right)^2+\left(\frac{y}{b}\right)^2=1
$$

Thus the projection onto the \(xy\)-plane is an **ellipse**.

From the \(z\)-equation:

$$
z=bt
$$

$$
t=\frac{z}{b}
$$

Substitute into \(x\) and \(y\):

$$
x=a\cos\left(\frac{\omega z}{b}\right)
$$

$$
y=b\sin\left(\frac{\omega z}{b}\right)
$$

Therefore the trajectory is an **elliptical helix** around the \(z\)-axis.

---

# b) Path Length from \(t=0\) to \(t=t_0\)

Path length is

$$
s=\int_0^{t_0} |\vec v(t)|\,dt
$$

Velocity:

$$
\vec v(t)=\frac{d\vec r}{dt}
$$

Differentiate components:

$$
\vec v(t)=(-a\omega\sin(\omega t),\; b\omega\cos(\omega t),\; b)
$$

Speed:

$$
|\vec v(t)|=\sqrt{(-a\omega\sin(\omega t))^2+(b\omega\cos(\omega t))^2+b^2}
$$

$$
|\vec v(t)|=\sqrt{a^2\omega^2\sin^2(\omega t)+b^2\omega^2\cos^2(\omega t)+b^2}
$$

Thus the arc length is

$$
s=\int_0^{t_0}
\sqrt{a^2\omega^2\sin^2(\omega t)+b^2\omega^2\cos^2(\omega t)+b^2}
\,dt
$$

This integral generally **does not simplify to elementary functions** unless special parameter values are chosen.

---

# c) Drawing the Trajectory (Python)

Example using **Matplotlib**:

```python
import numpy as np
import matplotlib.pyplot as plt

a = 3
b = 2
omega = 1

t = np.linspace(0, 10, 500)

x = a * np.cos(omega * t)
y = b * np.sin(omega * t)
z = b * t

fig = plt.figure()
ax = fig.add_subplot(projection='3d')

ax.plot(x, y, z)
ax.set_xlabel("x")
ax.set_ylabel("y")
ax.set_zlabel("z")

plt.show()