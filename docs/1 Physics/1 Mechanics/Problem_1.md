# Problem 1

# 1. Theoretical Foundation

## Governing Equations of Motion

Projectile motion can be understood by analyzing the two-dimensional motion of an object under the influence of gravity (assuming air resistance is negligible). The motion splits into horizontal (x) and vertical (y) components. Let’s derive the equations step by step:

---

### a. Assumptions & Setup

- **Initial velocity**: $\vec{v}_0$  
- **Angle of projection**:  $\theta$  
- **Gravity**:  $g$ (acting downward)  
- **Initial position**:  $(x_0, y_0)$
- **Neglecting air resistance**

Initial velocity components:  
$$
v_{0x} = v_0 \cos \theta, \quad v_{0y} = v_0 \sin \theta
$$

---

### b. Equations of Motion (Derived from Newton's Second Law)

#### Horizontal motion (no acceleration):
$$
\frac{d^2x}{dt^2} = 0 \Rightarrow \frac{dx}{dt} = v_{0x} \Rightarrow x(t) = x_0 + v_0 \cos \theta \cdot t
$$

#### Vertical motion (constant acceleration $-g$):
$$
\frac{d^2y}{dt^2} = -g \Rightarrow \frac{dy}{dt} = v_{0y} - g t \Rightarrow y(t) = y_0 + v_0 \sin \theta \cdot t - \frac{1}{2} g t^2
$$

---

### c. Family of Solutions from Varying Initial Conditions

The general solution describes the path (trajectory) of the projectile:

$$
\begin{cases}
x(t) = x_0 + v_0 \cos \theta \cdot t \\
y(t) = y_0 + v_0 \sin \theta \cdot t - \frac{1}{2} g t^2
\end{cases}
$$

By adjusting **initial conditions**, we generate a **family of parabolic curves**:

- Changing $\theta: affects symmetry and range.
- Changing $v_0$: affects height and distance.
- Changing $y_0$: allows launches from different altitudes.
- Gravity $g$: varies across planets (or in simulations), altering the trajectory.

Each set of parameters yields a unique solution curve — this richness is what makes projectile motion a powerful educational tool in physics.
