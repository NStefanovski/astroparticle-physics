# Study Guide

## 2.9.5.1 Decay

### Decay of a Particle into Two Particles

- **Scenario:**
  - A particle of mass \( M \) decays spontaneously into two particles with masses \( m_1 \) and \( m_2 \).
  - Analysis is performed in the rest frame of the initial particle.

### Conservation Laws

1. **Energy Conservation:**
   - Total energy before decay equals total energy after decay.
   - Since the initial particle is at rest, its total energy is purely its rest mass energy.
   - **Equation:**
     \[
     M c^2 = E_1 + E_2
     \]
   - \( E_1 \) and \( E_2 \) are the total energies of the decay products.

2. **Momentum Conservation:**
   - Total momentum before decay equals total momentum after decay.
   - Initial particle is at rest, so total initial momentum is zero.
   - **Equation:**
     \[
     \mathbf{p}_1 + \mathbf{p}_2 = 0
     \]
   - This implies the momenta are equal in magnitude and opposite in direction:
     \[
     p_1 = p_2
     \]

3. **Energy-Momentum Relation:**
   - For each decay product, the relation between energy, momentum, and mass is given by:
     \[
     E_i^2 = (p_i c)^2 + (m_i c^2)^2 \quad \text{for } i = 1, 2
     \]
   - Using momentum conservation, we equate the expressions:
     \[
     E_1^2 - m_1^2 c^4 = E_2^2 - m_2^2 c^4
     \]

### Mass Constraints for Decay

- **Condition for Spontaneous Decay:**
  - The initial mass must be greater than or equal to the sum of the masses of the decay products:
    \[
    M \geq m_1 + m_2
    \]
  - If \( M < m_1 + m_2 \), the decay cannot occur spontaneously due to insufficient energy.

- **Binding Energy Concept:**
  - If external energy is supplied, the process can occur with an energy input equal to the "binding energy":
    \[
    E_{\text{binding}} = (m_1 + m_2 - M) c^2
    \]

### Solving for Energies and Momenta

- **Steps to Determine Energies \( E_1 \) and \( E_2 \):**

  1. **From Momentum Conservation:**
     \[
     p_1 = p_2
     \]
     \[
     E_1^2 - m_1^2 c^4 = E_2^2 - m_2^2 c^4
     \]
  
  2. **From Energy Conservation:**
     \[
     E_1 + E_2 = M c^2
     \]

  3. **Substitute \( E_2 \) from Energy Conservation into the Energy-Momentum Relation:**
     \[
     E_1^2 - m_1^2 c^4 = (M c^2 - E_1)^2 - m_2^2 c^4
     \]

  4. **Simplify and Solve for \( E_1 \):**
     - Rearranging and solving the quadratic equation yields \( E_1 \).

- **Final Expressions for Energies:**
  \[
  E_1 = \frac{M^2 + m_1^2 - m_2^2}{2 M} c^2
  \]
  \[
  E_2 = \frac{M^2 + m_2^2 - m_1^2}{2 M} c^2
  \]

- **Expression for Momentum Magnitude:**
  \[
  p = \frac{\sqrt{ [M^2 - (m_1 + m_2)^2][M^2 - (m_1 - m_2)^2] }}{2 M} c
  \]

### Key Points

- **Back-to-Back Emission:**
  - Due to momentum conservation, decay products are emitted in opposite directions.

- **Energy Distribution:**
  - The energy and momentum of the decay products depend on their masses and the mass of the initial particle.

- **Threshold Condition:**
  - Spontaneous decay is only possible when the initial mass satisfies \( M \geq m_1 + m_2 \).

---

# Critical Equations

1. **Energy Conservation:**

   \[
   M c^2 = E_1 + E_2
   \]

   | Variable         | Meaning                                  |
   |------------------|------------------------------------------|
   | \( M \)          | Mass of the initial particle             |
   | \( c \)          | Speed of light in vacuum                 |
   | \( E_1 \)        | Total energy of particle 1 after decay   |
   | \( E_2 \)        | Total energy of particle 2 after decay   |

2. **Momentum Conservation:**

   \[
   \mathbf{p}_1 + \mathbf{p}_2 = 0
   \]
   \[
   \Rightarrow p_1 = p_2
   \]

   | Variable          | Meaning                                 |
   |-------------------|-----------------------------------------|
   | \( \mathbf{p}_1 \)| Momentum vector of particle 1           |
   | \( \mathbf{p}_2 \)| Momentum vector of particle 2           |
   | \( p_1, p_2 \)    | Magnitudes of the momenta (since \( \mathbf{p}_1 \) and \( \mathbf{p}_2 \) are equal and opposite) |

3. **Energy-Momentum Relation:**

   \[
   E_i^2 = (p_i c)^2 + (m_i c^2)^2 \quad \text{for } i = 1, 2
   \]

   | Variable         | Meaning                                  |
   |------------------|------------------------------------------|
   | \( E_i \)        | Total energy of particle \( i \)         |
   | \( p_i \)        | Momentum magnitude of particle \( i \)   |
   | \( m_i \)        | Mass of particle \( i \)                 |
   | \( c \)          | Speed of light in vacuum                 |

4. **Mass Constraint for Decay:**

   \[
   M \geq m_1 + m_2
   \]

   | Variable         | Meaning                                  |
   |------------------|------------------------------------------|
   | \( M \)          | Mass of the initial particle             |
   | \( m_1 \)        | Mass of particle 1 after decay           |
   | \( m_2 \)        | Mass of particle 2 after decay           |

5. **Relation Between Energies and Masses:**

   From the energy-momentum relations and momentum conservation:

   \[
   E_1^2 - m_1^2 c^4 = E_2^2 - m_2^2 c^4
   \]

   Using energy conservation \( E_2 = M c^2 - E_1 \):

   \[
   E_1^2 - m_1^2 c^4 = (M c^2 - E_1)^2 - m_2^2 c^4
   \]

   Simplifying and solving for \( E_1 \):

   \[
   E_1 = \frac{M^2 + m_1^2 - m_2^2}{2 M} c^2
   \]

   | Variable         | Meaning                                  |
   |------------------|------------------------------------------|
   | \( E_1 \)        | Total energy of particle 1 after decay   |
   | \( M \)          | Mass of the initial particle             |
   | \( m_1 \)        | Mass of particle 1 after decay           |
   | \( m_2 \)        | Mass of particle 2 after decay           |
   | \( c \)          | Speed of light in vacuum                 |

6. **Momentum of Decay Products:**

   \[
   p = \frac{\sqrt{ [M^2 - (m_1 + m_2)^2][M^2 - (m_1 - m_2)^2] }}{2 M} c
   \]

   | Variable         | Meaning                                  |
   |------------------|------------------------------------------|
   | \( p \)          | Magnitude of momentum of decay products  |
   | \( M \)          | Mass of the initial particle             |
   | \( m_1 \)        | Mass of particle 1 after decay           |
   | \( m_2 \)        | Mass of particle 2 after decay           |
   | \( c \)          | Speed of light in vacuum                 |

7. **Binding Energy (if \( M < m_1 + m_2 \)):**

   External energy required to induce the process:

   \[
   E_{\text{binding}} = (m_1 + m_2 - M) c^2
   \]

   | Variable             | Meaning                                  |
   |----------------------|------------------------------------------|
   | \( E_{\text{binding}} \) | Binding energy (energy input required)|
   | \( M \)              | Mass of the initial particle             |
   | \( m_1 \)            | Mass of particle 1 after decay           |
   | \( m_2 \)            | Mass of particle 2 after decay           |
   | \( c \)              | Speed of light in vacuum                 |

---

This study guide covers the essential principles and calculations involved in the decay of a particle into two products, focusing on energy and momentum conservation, mass constraints, and the determination of the energies and momenta of the decay products. Understanding these concepts is fundamental in particle physics, as they apply to a wide range of decay processes and reactions.