# Chapter 6: Electromagnetic Induction

---

## 📚 Topic: Magnetic Flux

### 📐 Formula: 
```
φ = B⋅A = BA cos θ
```

### 🎯 Use: 
Calculates the magnetic flux through a surface

### 📊 Values:
- φ = Magnetic flux (Weber, Wb)
- B = Magnetic field strength (Tesla, T)
- A = Area of surface (m²)
- θ = Angle between B and normal to surface

### 💡 Notes:
- Maximum flux when θ = 0° (field perpendicular to surface)
- Zero flux when θ = 90° (field parallel to surface)
- SI unit: 1 Weber (Wb) = 1 T·m² = 1 kg·m²·s⁻²·A⁻¹

---

## 📚 Topic: Faraday's Law of Electromagnetic Induction

### 📐 Formula: 
```
ε = -dφ/dt
```

### 🎯 Use: 
Calculates induced EMF due to changing magnetic flux

### 📊 Values:
- ε = Induced EMF (Volts, V)
- φ = Magnetic flux (Weber, Wb)
- t = Time (seconds, s)
- Negative sign indicates direction (Lenz's law)

### 💡 Notes:
- EMF is induced only when flux changes
- Greater rate of change → larger induced EMF
- Direction opposes the change causing it

---

## 📚 Topic: Faraday's Law for N Turns

### 📐 Formula: 
```
ε = -N(dφ/dt)
```

### 🎯 Use: 
Calculates induced EMF in a coil with N turns

### 📊 Values:
- ε = Total induced EMF (Volts, V)
- N = Number of turns in coil
- φ = Magnetic flux through one turn (Wb)
- t = Time (s)

### 💡 Notes:
- EMF increases proportionally with number of turns
- All turns must be in series
- Used in transformers and generators

---

## 📚 Topic: Induced Current

### 📐 Formula: 
```
I = ε/R = -(1/R)(dφ/dt)
```

### 🎯 Use: 
Calculates induced current in a closed loop

### 📊 Values:
- I = Induced current (Amperes, A)
- ε = Induced EMF (V)
- R = Resistance of loop (Ohms, Ω)
- φ = Magnetic flux (Wb)

### 💡 Notes:
- Current flows only in closed circuit
- Direction follows Lenz's law
- Larger resistance → smaller current

---

## 📚 Topic: Motional EMF (Straight Conductor)

### 📐 Formula: 
```
ε = Bvl
```

### 🎯 Use: 
Calculates EMF induced in a moving conductor

### 📊 Values:
- ε = Induced EMF (Volts, V)
- B = Magnetic field strength (T)
- v = Velocity of conductor (m/s)
- l = Length of conductor in field (m)

### 💡 Notes:
- Valid when B, v, and l are mutually perpendicular
- Direction given by Fleming's right-hand rule
- Used in generators and motors

---

## 📚 Topic: Motional EMF (General Case)

### 📐 Formula: 
```
ε = Bvl sin θ
```

### 🎯 Use: 
Calculates EMF when velocity makes angle θ with field

### 📊 Values:
- ε = Induced EMF (V)
- B = Magnetic field (T)
- v = Velocity (m/s)
- l = Length of conductor (m)
- θ = Angle between v and B

### 💡 Notes:
- Maximum when θ = 90° (perpendicular motion)
- Zero when θ = 0° (parallel motion)
- Only perpendicular component contributes

---

## 📚 Topic: EMF in Rotating Coil

### 📐 Formula: 
```
ε = NABω sin(ωt)
```

### 🎯 Use: 
Calculates EMF in a coil rotating in magnetic field

### 📊 Values:
- ε = Instantaneous EMF (V)
- N = Number of turns
- A = Area of coil (m²)
- B = Magnetic field (T)
- ω = Angular velocity (rad/s)
- t = Time (s)

### 💡 Notes:
- Produces alternating (AC) EMF
- Maximum EMF: ε₀ = NABω
- Forms basis of AC generator

---

## 📚 Topic: Self-Inductance

### 📐 Formula: 
```
ε = -L(dI/dt)
```

### 🎯 Use: 
Calculates self-induced EMF in a coil

### 📊 Values:
- ε = Self-induced EMF (V)
- L = Self-inductance (Henry, H)
- I = Current through coil (A)
- t = Time (s)

### 💡 Notes:
- Opposes change in current (back EMF)
- SI unit: 1 Henry (H) = 1 Wb/A = 1 kg·m²·s⁻²·A⁻²
- Property of the coil itself

---

## 📚 Topic: Self-Inductance of Solenoid

### 📐 Formula: 
```
L = μ₀n²Al = μ₀N²A/l
```

### 🎯 Use: 
Calculates self-inductance of a long solenoid

### 📊 Values:
- L = Self-inductance (H)
- μ₀ = Permeability of free space (4π × 10⁻⁷ H/m)
- n = Number of turns per unit length (turns/m)
- N = Total number of turns
- A = Cross-sectional area (m²)
- l = Length of solenoid (m)

### 💡 Notes:
- Valid for long solenoids (l >> radius)
- Inductance ∝ N²
- Independent of current

---

## 📚 Topic: Magnetic Energy in Inductor

### 📐 Formula: 
```
U = (1/2)LI²
```

### 🎯 Use: 
Calculates energy stored in magnetic field of inductor

### 📊 Values:
- U = Magnetic energy (Joules, J)
- L = Self-inductance (H)
- I = Current (A)

### 💡 Notes:
- Energy stored in magnetic field
- Analogous to (1/2)CV² for capacitors
- Released when current decreases

---

## 📚 Topic: Energy Density in Magnetic Field

### 📐 Formula: 
```
u = B²/(2μ₀)
```

### 🎯 Use: 
Calculates magnetic energy per unit volume

### 📊 Values:
- u = Energy density (J/m³)
- B = Magnetic field strength (T)
- μ₀ = Permeability of free space (4π × 10⁻⁷ H/m)

### 💡 Notes:
- Energy distributed throughout magnetic field
- Total energy U = u × Volume
- Independent of inductor geometry

---

## 📚 Topic: Mutual Inductance

### 📐 Formula: 
```
ε₂ = -M(dI₁/dt)
```

### 🎯 Use: 
Calculates EMF induced in coil 2 due to changing current in coil 1

### 📊 Values:
- ε₂ = Induced EMF in coil 2 (V)
- M = Mutual inductance (H)
- I₁ = Current in coil 1 (A)
- t = Time (s)

### 💡 Notes:
- Depends on geometry and relative position
- M₁₂ = M₂₁ (symmetric property)
- Used in transformers

---

## 📚 Topic: Mutual Inductance (Flux Definition)

### 📐 Formula: 
```
M = N₂φ₂/I₁ = N₁φ₁/I₂
```

### 🎯 Use: 
Relates mutual inductance to flux linkage

### 📊 Values:
- M = Mutual inductance (H)
- N₁, N₂ = Number of turns in coils 1 and 2
- φ₁, φ₂ = Flux through one turn of coil (Wb)
- I₁, I₂ = Currents in respective coils (A)

### 💡 Notes:
- Flux linkage determines M
- Maximum when coils are close and aligned
- Zero when coils are perpendicular

---

## 📚 Topic: AC Generator Peak EMF

### 📐 Formula: 
```
ε₀ = NABω
```

### 🎯 Use: 
Calculates maximum EMF produced by AC generator

### 📊 Values:
- ε₀ = Peak EMF (V)
- N = Number of turns in coil
- A = Area of coil (m²)
- B = Magnetic field strength (T)
- ω = Angular velocity (rad/s)

### 💡 Notes:
- Occurs when coil is horizontal (θ = 90°)
- Frequency f = ω/(2π)
- Commercial generators produce 50-60 Hz AC

---

## 📚 Topic: AC Generator Frequency

### 📐 Formula: 
```
f = ω/(2π) = (Number of rotations per second)
```

### 🎯 Use: 
Calculates frequency of generated AC

### 📊 Values:
- f = Frequency (Hertz, Hz)
- ω = Angular velocity (rad/s)
- 2π = Radians in one complete rotation

### 💡 Notes:
- Standard frequencies: 50 Hz (India/Europe), 60 Hz (USA)
- Time period T = 1/f
- Higher rotation speed → higher frequency

---

## 📚 Topic: Eddy Current Power Loss

### 📐 Formula: 
```
P ∝ B²f²t²
```

### 🎯 Use: 
Shows factors affecting eddy current losses

### 📊 Values:
- P = Power loss (W)
- B = Magnetic field strength (T)
- f = Frequency (Hz)
- t = Thickness of conductor (m)

### 💡 Notes:
- Reduced by laminating the core
- Increases with field strength and frequency
- Cause of heating in transformers

---

## 📚 Topic: Lenz's Law

### 📐 Formula: 
```
Direction of induced current opposes the change in flux
```

### 🎯 Use: 
Determines direction of induced current

### 📊 Values:
- Not a mathematical formula
- Qualitative rule for direction

### 💡 Notes:
- Conservation of energy principle
- Represented by negative sign in Faraday's law
- Induced effects oppose the cause

---

## Important Constants

- **Permeability of free space (μ₀)**: 4π × 10⁻⁷ H/m
- **1 Weber (Wb)**: 1 T·m²
- **1 Henry (H)**: 1 Wb/A = 1 V·s/A

---

## Key Concepts

1. **Electromagnetic Induction**: Generation of EMF due to changing magnetic flux
2. **Lenz's Law**: Direction of induced current opposes change
3. **Self-Inductance**: Opposition to change in own current
4. **Mutual Inductance**: Induction between two coils
5. **Motional EMF**: EMF in moving conductor in magnetic field
6. **Eddy Currents**: Circulating currents in bulk conductors
7. **AC Generator**: Converts mechanical energy to electrical energy

---

**Revision Tips:**
- Practice numerical on motional EMF and rotating coils
- Understand direction using Lenz's law and Fleming's rules
- Remember energy formulas for inductors
- Distinguish between self and mutual inductance
