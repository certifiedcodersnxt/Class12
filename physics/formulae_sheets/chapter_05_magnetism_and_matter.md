# Chapter 5: Magnetism and Matter

## Formula Sheet

---

### 1. Magnetic Field Lines

📚 **Topic:** Properties of Magnetic Field Lines

🎯 **Use:** Understanding the behavior and characteristics of magnetic field lines

📊 **Properties:**
- Magnetic field lines form closed loops
- They emerge from North pole and merge at South pole
- They never intersect each other
- The tangent at any point gives the direction of magnetic field
- Crowded lines indicate stronger field

💡 **Notes:**
- Unlike electric field lines, magnetic field lines always form closed loops
- Inside a magnet, field lines go from South to North pole

---

### 2. Magnetic Dipole Moment

📚 **Topic:** Magnetic Dipole Moment

📐 **Formula:** 
```
m = I × A
```

🎯 **Use:** Calculates the magnetic dipole moment of a current loop or a magnet

📊 **Values:**
- m = Magnetic dipole moment (A·m²)
- I = Current flowing through the loop (A)
- A = Area of the current loop (m²)

💡 **Notes:**
- Direction is perpendicular to the plane of the loop (right-hand thumb rule)
- For a bar magnet: m = pole strength × magnetic length

---

### 3. Magnetic Field on Axial Line

📚 **Topic:** Magnetic Field on Axial Line of a Bar Magnet

📐 **Formula:**
```
B = (μ₀/4π) × (2Mr)/(r² - l²)²
```

For r >> l:
```
B = (μ₀/4π) × (2M/r³)
```

🎯 **Use:** Calculates magnetic field at a point on the axial line of a bar magnet

📊 **Values:**
- B = Magnetic field (T)
- μ₀ = Permeability of free space = 4π × 10⁻⁷ T·m/A
- M = Magnetic dipole moment (A·m²)
- r = Distance from center of magnet (m)
- l = Half-length of magnet (m)

💡 **Notes:**
- Valid for points on the axis of the magnet
- Field direction is along the axis
- For short magnets (r >> l), simplified formula is used

---

### 4. Magnetic Field on Equatorial Line

📚 **Topic:** Magnetic Field on Equatorial Line of a Bar Magnet

📐 **Formula:**
```
B = (μ₀/4π) × M/(r² + l²)^(3/2)
```

For r >> l:
```
B = (μ₀/4π) × (M/r³)
```

🎯 **Use:** Calculates magnetic field at a point on the equatorial line of a bar magnet

📊 **Values:**
- B = Magnetic field (T)
- μ₀ = Permeability of free space = 4π × 10⁻⁷ T·m/A
- M = Magnetic dipole moment (A·m²)
- r = Distance from center on equatorial line (m)
- l = Half-length of magnet (m)

💡 **Notes:**
- Valid for points on the perpendicular bisector
- Field direction is opposite to the magnetic moment
- **B_axial = 2 × B_equatorial** at same distance for short magnets

---

### 5. Torque on a Magnetic Dipole

📚 **Topic:** Torque on a Magnetic Dipole in Uniform Magnetic Field

📐 **Formula:**
```
τ = M × B × sin θ
```

Vector form:
```
τ⃗ = M⃗ × B⃗
```

🎯 **Use:** Calculates torque experienced by a magnetic dipole in an external magnetic field

📊 **Values:**
- τ = Torque (N·m)
- M = Magnetic dipole moment (A·m²)
- B = External magnetic field (T)
- θ = Angle between M and B

💡 **Notes:**
- Maximum torque when θ = 90° (τ_max = MB)
- Zero torque when θ = 0° or 180° (equilibrium positions)
- Torque tends to align the dipole with the field

---

### 6. Potential Energy of a Magnetic Dipole

📚 **Topic:** Potential Energy of a Magnetic Dipole in Magnetic Field

📐 **Formula:**
```
U = -M × B × cos θ
```

Vector form:
```
U = -M⃗ · B⃗
```

🎯 **Use:** Calculates potential energy of a magnetic dipole in an external magnetic field

📊 **Values:**
- U = Potential energy (J)
- M = Magnetic dipole moment (A·m²)
- B = External magnetic field (T)
- θ = Angle between M and B

💡 **Notes:**
- Minimum energy when θ = 0° (stable equilibrium): U = -MB
- Maximum energy when θ = 180° (unstable equilibrium): U = +MB
- Work done to rotate dipole: W = MB(cos θ₁ - cos θ₂)

---

### 7. Magnetic Intensity (H)

📚 **Topic:** Magnetic Field Intensity

📐 **Formula:**
```
H = B/μ₀ - M
```

Or in a medium:
```
B = μ₀(H + M)
```

🎯 **Use:** Represents the magnetic field intensity independent of the medium

📊 **Values:**
- H = Magnetic intensity (A/m)
- B = Magnetic field (T)
- μ₀ = Permeability of free space = 4π × 10⁻⁷ T·m/A
- M = Magnetization (A/m)

💡 **Notes:**
- H depends only on external currents, not on magnetic properties of material
- In vacuum: B = μ₀H

---

### 8. Magnetization (M)

📚 **Topic:** Magnetization of a Material

📐 **Formula:**
```
M = magnetic moment/Volume
```

Or:
```
M = (m × n)
```

🎯 **Use:** Represents the degree of magnetization of a material

📊 **Values:**
- M = Magnetization (A/m)
- m = Magnetic moment of individual atom (A·m²)
- n = Number of atoms per unit volume (atoms/m³)

💡 **Notes:**
- Measures the magnetic dipole moment per unit volume
- For paramagnetic and diamagnetic materials, M is proportional to H

---

### 9. Magnetic Susceptibility (χ)

📚 **Topic:** Magnetic Susceptibility

📐 **Formula:**
```
χ = M/H
```

🎯 **Use:** Measures how much a material will become magnetized in an applied magnetic field

📊 **Values:**
- χ = Magnetic susceptibility (dimensionless)
- M = Magnetization (A/m)
- H = Magnetic intensity (A/m)

💡 **Notes:**
- **Diamagnetic:** χ is small and negative (-10⁻⁵)
- **Paramagnetic:** χ is small and positive (+10⁻⁵ to +10⁻³)
- **Ferromagnetic:** χ is large and positive (>1000)

---

### 10. Relative Permeability (μᵣ)

📚 **Topic:** Relative Permeability

📐 **Formula:**
```
μᵣ = μ/μ₀
```

Also:
```
μᵣ = 1 + χ
```

🎯 **Use:** Measures how much more or less magnetic a material is compared to vacuum

📊 **Values:**
- μᵣ = Relative permeability (dimensionless)
- μ = Permeability of material (T·m/A)
- μ₀ = Permeability of free space = 4π × 10⁻⁷ T·m/A
- χ = Magnetic susceptibility

💡 **Notes:**
- **Diamagnetic:** μᵣ < 1 (slightly less than 1)
- **Paramagnetic:** μᵣ > 1 (slightly more than 1)
- **Ferromagnetic:** μᵣ >> 1 (much greater than 1)

---

### 11. Relation Between B, H, and M

📚 **Topic:** Relation in Magnetic Materials

📐 **Formula:**
```
B = μ₀(H + M)
```

Or:
```
B = μ H = μ₀μᵣ H
```

🎯 **Use:** Relates magnetic field (B), magnetic intensity (H), and magnetization (M)

📊 **Values:**
- B = Magnetic field (T)
- H = Magnetic intensity (A/m)
- M = Magnetization (A/m)
- μ = Permeability of material (T·m/A)
- μ₀ = Permeability of free space = 4π × 10⁻⁷ T·m/A
- μᵣ = Relative permeability

💡 **Notes:**
- This is the fundamental relation for magnetic materials
- In vacuum: M = 0, so B = μ₀H

---

### 12. Curie's Law

📚 **Topic:** Curie's Law for Paramagnetic Materials

📐 **Formula:**
```
χ = C/T
```

Or:
```
M = C × (B/T)
```

🎯 **Use:** Describes how magnetic susceptibility varies with temperature in paramagnetic materials

📊 **Values:**
- χ = Magnetic susceptibility
- C = Curie constant (K)
- T = Absolute temperature (K)
- M = Magnetization (A/m)
- B = Magnetic field (T)

💡 **Notes:**
- Susceptibility decreases with increasing temperature
- Valid only for paramagnetic materials
- At high temperatures, thermal agitation reduces alignment

---

### 13. Curie Temperature (Tᶜ)

📚 **Topic:** Curie-Weiss Law for Ferromagnetic Materials

📐 **Formula:**
```
χ = C/(T - Tᶜ)    for T > Tᶜ
```

🎯 **Use:** Describes behavior of ferromagnetic materials above Curie temperature

📊 **Values:**
- χ = Magnetic susceptibility
- C = Curie constant (K)
- T = Absolute temperature (K)
- Tᶜ = Curie temperature (K)

💡 **Notes:**
- Above Tᶜ, ferromagnetic material becomes paramagnetic
- Below Tᶜ, material shows ferromagnetic properties
- **Examples:** Iron (Tᶜ = 1043 K), Cobalt (Tᶜ = 1394 K), Nickel (Tᶜ = 631 K)

---

### 14. Earth's Magnetic Field Components

📚 **Topic:** Components of Earth's Magnetic Field

📐 **Formulas:**

**Horizontal Component:**
```
Bₕ = B cos δ
```

**Vertical Component:**
```
Bᵥ = B sin δ
```

**Relation:**
```
B = √(Bₕ² + Bᵥ²)
```

**Angle of Dip:**
```
tan δ = Bᵥ/Bₕ
```

🎯 **Use:** Analyzes the components of Earth's magnetic field at any location

📊 **Values:**
- B = Total magnetic field of Earth (T)
- Bₕ = Horizontal component (T)
- Bᵥ = Vertical component (T)
- δ = Angle of dip/inclination (degrees)

💡 **Notes:**
- At magnetic equator: δ = 0°, Bᵥ = 0, Bₕ = B
- At magnetic poles: δ = 90°, Bₕ = 0, Bᵥ = B
- Earth's average field ≈ 0.5 × 10⁻⁴ T

---

### 15. Magnetic Declination

📚 **Topic:** Magnetic Declination

🎯 **Use:** Angle between geographic north and magnetic north

📊 **Definition:**
- Angle between geographic meridian and magnetic meridian
- Varies from place to place on Earth
- Changes slowly with time (secular variation)

💡 **Notes:**
- Positive (eastward) or negative (westward)
- Important for navigation using compass
- Not constant at a given location (changes over years)

---

### 16. Time Period of Oscillation of a Magnetic Dipole

📚 **Topic:** Oscillation of Magnetic Dipole in Uniform Field

📐 **Formula:**
```
T = 2π√(I/MB)
```

🎯 **Use:** Calculates the time period of oscillation of a freely suspended magnetic dipole

📊 **Values:**
- T = Time period (s)
- I = Moment of inertia of dipole (kg·m²)
- M = Magnetic dipole moment (A·m²)
- B = Magnetic field strength (T)

💡 **Notes:**
- Valid for small angular displacements
- Analogous to simple pendulum motion
- Used in magnetometers

---

## Classification of Magnetic Materials

### 1. Diamagnetic Materials

**Properties:**
- Weakly repelled by magnets
- χ < 0 (negative susceptibility)
- μᵣ < 1 (slightly less than 1)
- Independent of temperature

**Examples:** Bismuth, Copper, Gold, Water, Mercury

---

### 2. Paramagnetic Materials

**Properties:**
- Weakly attracted by magnets
- χ > 0 (small positive susceptibility)
- μᵣ > 1 (slightly greater than 1)
- Obey Curie's law (χ ∝ 1/T)

**Examples:** Aluminum, Platinum, Chromium, Oxygen

---

### 3. Ferromagnetic Materials

**Properties:**
- Strongly attracted by magnets
- χ >> 1 (large positive susceptibility)
- μᵣ >> 1 (much greater than 1)
- Show hysteresis
- Have Curie temperature
- Can be permanently magnetized

**Examples:** Iron, Cobalt, Nickel, Gadolinium

---

## Important Constants

| Constant | Symbol | Value |
|----------|--------|-------|
| Permeability of free space | μ₀ | 4π × 10⁻⁷ T·m/A |
| Earth's magnetic field (avg) | B_Earth | ~0.5 × 10⁻⁴ T |
| Bohr magneton | μ_B | 9.27 × 10⁻²⁴ A·m² |

---

## Key Concepts to Remember

1. **Bar Magnet as Equivalent Solenoid:** A bar magnet is equivalent to a solenoid carrying current
2. **Gauss's Law for Magnetism:** ∮ B⃗·dA⃗ = 0 (no magnetic monopoles)
3. **Hysteresis:** Energy loss in ferromagnetic materials during magnetization cycle
4. **Magnetic Shielding:** Using materials with high permeability to protect from magnetic fields
5. **Permanent Magnets:** Made from ferromagnetic materials with high retentivity and coercivity

---

*This formula sheet covers all major topics from NCERT Class 12 Physics Chapter 5: Magnetism and Matter*
