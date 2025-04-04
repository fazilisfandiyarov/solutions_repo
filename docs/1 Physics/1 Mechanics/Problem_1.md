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

# 2. Analysis of the Range

## Horizontal Range and Angle of Projection

The **horizontal range** $R$ of a projectile is the horizontal distance it travels before returning to the same vertical level from which it was launched (i.e., when $y = y_0$).

For a projectile launched from ground level ($y_0 = 0$), the total time of flight $T$ is given by:

$$
T = \frac{2 v_0 \sin \theta}{g}
$$

The horizontal range is then:

$$
R = v_0 \cos \theta \cdot T = v_0 \cos \theta \cdot \frac{2 v_0 \sin \theta}{g}
$$

Simplifying:

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

This formula shows a clear dependency on the **angle of projection**:

- The range is **maximum** when $\sin(2\theta) = 1$, which occurs at $2\theta = 90^\circ \Rightarrow \theta = 45^\circ$.
- The function $\sin(2\theta)$ is symmetric about $\theta = 45^\circ$, meaning:
  - $R(30^\circ) = R(60^\circ)$
  - $R(10^\circ) = R(80^\circ)$, etc.

---

## Influence of Other Parameters

### 1. **Initial Velocity $v_0$**

From the range equation:

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

- The range increases **quadratically** with $v_0$.
- Doubling the velocity **quadruples** the range.
- Higher velocity = longer flight time and faster horizontal travel.

### 2. **Gravitational Acceleration $g$**

- The range is **inversely proportional** to $g$.
- On planets with weaker gravity (e.g., the Moon), the same projectile would travel much farther.
- Example:
  - On Earth: $g \approx 9.8\, \text{m/s}^2$
  - On Moon: $g \approx 1.6\, \text{m/s}^2 \Rightarrow R_{\text{moon}} \approx 6.1 \times R_{\text{earth}}$

---

## Summary

- The range depends on the angle of projection via the term $\sin(2\theta)$.
- It is **maximum at 45°** and symmetric around it.
- Increasing **initial velocity** extends range significantly.
- Decreasing **gravity** also increases range.

These insights show how adjusting launch conditions can precisely control the motion of a projectile — a principle used in everything from sports to space travel.
