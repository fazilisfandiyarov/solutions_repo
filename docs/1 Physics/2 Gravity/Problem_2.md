# Problem 2

# Cosmic Velocities: First, Second, and Third

The concept of cosmic velocities is central to spaceflight. These velocities—**first**, **second**, and **third cosmic velocity**—define the speeds required to enter orbit, escape a planet’s gravity, and ultimately leave the solar system. Understanding them is key to mission design for satellites, planetary exploration, and interstellar probes.

---

## 1. First Cosmic Velocity — Orbital Velocity

**Definition**:  
The **first cosmic velocity** is the minimum speed an object must have to enter a **stable circular orbit** around a celestial body **without further propulsion**.

**Physical Meaning**:
- At this speed, the object "falls around" the planet.
- The orbit is circular and sustained due to the balance between gravity and inertia.
- This speed **does not depend** on the object's mass.

**Formula**:  
$$
v_1 = \sqrt{\frac{GM}{R}}
$$

Where:  
- $G$: gravitational constant = $6.674 \times 10^{-11} \, \text{m}^3/\text{kg} \cdot \text{s}^2$  
- $M$: mass of the celestial body  
- $R$: distance from the center of the body  

**On Earth**:
- Speed: ~**7.9 km/s** (~28,400 km/h)
- Used For: Satellites (ISS, GPS), space telescopes

---

## 2. Second Cosmic Velocity — Escape Velocity

**Definition**:  
The **second cosmic velocity** is the minimum speed required to **escape the gravitational field** of a celestial body **without additional propulsion**.

**Physical Meaning**:
- The kinetic energy of the object equals the gravitational potential energy needed to escape.
- No return unless additional force is applied.

**Formula**:  
$$
v_2 = \sqrt{\frac{2GM}{R}} = \sqrt{2} \cdot v_1
$$

**On Earth**:
- Speed: ~**11.2 km/s** (~40,320 km/h)
- Used For: Moon missions, Mars missions, deep space probes

---

## 3. Third Cosmic Velocity — Heliocentric Escape

**Definition**:  
The **third cosmic velocity** is the minimum speed required to **escape the Sun’s gravitational field**, starting from Earth’s orbit.

**Formula**:  
$$
v_3 = \sqrt{\frac{2GM_{\odot}}{r}} - v_{\text{Earth orbit}}
$$

Where:  
- $M_{\odot}$: mass of the Sun  
- $r$: Earth's orbital radius (~1 AU)  
- $v_{\text{Earth orbit}}$: Earth’s orbital speed (~29.78 km/s)

**From Earth’s Orbit**:
- Speed: ~**16.7 km/s**
- Used For: Voyager, Pioneer, New Horizons

---

## Summary Table

| Velocity     | Purpose                           | Speed from Earth | Applications                      |
|--------------|-----------------------------------|------------------|-----------------------------------|
| **1st**      | Stable orbit around Earth         | ~7.9 km/s        | Satellites, ISS                   |
| **2nd**      | Escape Earth’s gravity            | ~11.2 km/s       | Moon, Mars, interplanetary probes|
| **3rd**      | Escape Solar System               | ~16.7 km/s       | Voyager 1, interstellar missions |

---

##  Comparative Cosmic Velocities on Planets

### Formulae Recap:
- $v_1 = \sqrt{\frac{GM}{R}}$
- $v_2 = \sqrt{2GM/R}$

### Constants:

| Body     | Mass (kg)             | Radius (m)          |
|----------|-----------------------|---------------------|
| Earth    | $5.972 \times 10^{24}$ | $6.371 \times 10^6$ |
| Mars     | $6.417 \times 10^{23}$ | $3.390 \times 10^6$ |
| Jupiter  | $1.898 \times 10^{27}$ | $6.9911 \times 10^7$ |

### Calculated Velocities:

| Planet   | $v_1$ (km/s) | $v_2$ (km/s) |
|----------|------------------|------------------|
| Earth    | 7.91             | 11.19            |
| Mars     | 3.55             | 5.03             |
| Jupiter  | 42.1             | 59.5             |

---

### Visualization

![alt text](Cosmic%20velocities%20bar.png)

##  Real-World Applications

###  Satellite Launches — First Cosmic Velocity
- **Goal**: Insert into orbit
- **Example**: ISS orbits at ~7.66 km/s
- **Notes**: Insufficient speed = falling back to Earth

###  Planetary Missions — Second Cosmic Velocity
- **Goal**: Leave Earth to reach Moon, Mars, or beyond
- **Example**: Mars Rover launches exceed 11.2 km/s

### Interstellar Missions — Third Cosmic Velocity
- **Goal**: Exit Solar System
- **Examples**:  
  - **Voyager 1**: Exceeded third velocity via gravity assists  
  - **New Horizons**: Fastest launch to date (~16.26 km/s)

---

##  Engineering and Strategy Considerations

| Factor             | Influence on Velocities         |
|--------------------|---------------------------------|
| Mass of central body | ↑ mass → ↑ velocity required  |
| Radius from center   | ↑ radius → ↓ velocity required|
| Launch direction     | Prograde (with orbit) helps   |
| Atmosphere (real world) | Requires more than ideal velocity due to drag |

**Note**: Gravity assists and multi-stage propulsion systems help mitigate these energy demands.

---

##  Conclusion

The **cosmic velocities** provide a roadmap for the stages of space exploration:
- **First**: Staying in orbit
- **Second**: Leaving Earth
- **Third**: Leaving the Solar System

Understanding and achieving these velocities remains a foundation of both current and future space missions, from launching satellites to exploring interstellar frontiers.

---
