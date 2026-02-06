# Chapter 3: Current Electricity - Formula Sheet

---

## 1️⃣ Electric Current

📚 **Topic:** Rate of flow of charge

📐 **Formula:**
```
I = Q / t
```
or
```
I = dQ / dt
```

🎯 **Use:** Calculate electric current from charge flow

📊 **Values:**
- I = Electric current (Ampere)
- Q = Charge flowing (Coulomb)
- t = Time (second)

💡 **Notes:**
- SI unit: Ampere (A) = Coulomb/second
- Direction: From positive to negative terminal (conventional)
- Scalar quantity but has direction (not a vector)
- 1 mA = 10⁻³ A, 1 μA = 10⁻⁶ A

---

## 2️⃣ Current Density

📚 **Topic:** Current per unit area

📐 **Formula:**
```
J = I / A
```

🎯 **Use:** Calculate current density in a conductor

📊 **Values:**
- J = Current density (A/m²)
- I = Current (Ampere)
- A = Cross-sectional area (m²)

💡 **Notes:**
- Vector quantity, direction of current flow
- Higher J means more current through smaller area
- Related to drift velocity: J = nev_d

---

## 3️⃣ Drift Velocity

📚 **Topic:** Average velocity of charge carriers

📐 **Formula:**
```
v_d = I / (nAe)
```

🎯 **Use:** Calculate drift velocity of electrons in a conductor

📊 **Values:**
- v_d = Drift velocity (m/s)
- I = Current (Ampere)
- n = Number density of charge carriers (per m³)
- A = Cross-sectional area (m²)
- e = Charge of electron = 1.6 × 10⁻¹⁹ C

💡 **Notes:**
- Very small velocity (~10⁻⁴ m/s typically)
- Opposite to electric field direction (for electrons)
- Related to current density: J = nev_d

---

## 4️⃣ Ohm's Law

📚 **Topic:** Relation between voltage, current, and resistance

📐 **Formula:**
```
V = IR
```

🎯 **Use:** Calculate voltage, current, or resistance in a circuit

📊 **Values:**
- V = Potential difference (Volt)
- I = Current (Ampere)
- R = Resistance (Ohm, Ω)

💡 **Notes:**
- Valid for ohmic conductors (linear V-I relationship)
- Temperature should remain constant
- Most fundamental law in circuit analysis

---

## 5️⃣ Resistance of a Conductor

📚 **Topic:** Resistance based on material properties

📐 **Formula:**
```
R = ρL / A
```

🎯 **Use:** Calculate resistance from dimensions and resistivity

📊 **Values:**
- R = Resistance (Ohm, Ω)
- ρ = Resistivity of material (Ω·m)
- L = Length of conductor (meter)
- A = Cross-sectional area (m²)

💡 **Notes:**
- Resistance ∝ Length
- Resistance ∝ 1/Area
- Depends on material (through ρ)

---

## 6️⃣ Resistivity and Conductivity

📚 **Topic:** Material property for electrical conduction

📐 **Formula:**
```
ρ = RA / L
```
and
```
σ = 1 / ρ
```

🎯 **Use:** Calculate resistivity or conductivity of a material

📊 **Values:**
- ρ = Resistivity (Ω·m)
- σ = Conductivity (S/m or Ω⁻¹·m⁻¹)
- R = Resistance (Ohm)
- A = Area (m²)
- L = Length (meter)

💡 **Notes:**
- Resistivity is material property (independent of dimensions)
- Good conductors have low ρ (high σ)
- Silver has lowest resistivity among metals

---

## 7️⃣ Temperature Dependence of Resistance

📚 **Topic:** Variation of resistance with temperature

📐 **Formula:**
```
R_T = R₀(1 + αΔT)
```
or
```
R_T = R₀[1 + α(T - T₀)]
```

🎯 **Use:** Calculate resistance at different temperature

📊 **Values:**
- R_T = Resistance at temperature T (Ohm)
- R₀ = Resistance at reference temperature T₀ (Ohm)
- α = Temperature coefficient of resistance (per °C)
- ΔT = Change in temperature (°C or K)

💡 **Notes:**
- For metals: α is positive (R increases with T)
- For semiconductors: α is negative (R decreases with T)
- α ≈ 4 × 10⁻³ per °C for copper

---

## 8️⃣ Electrical Power

📚 **Topic:** Rate of energy dissipation

📐 **Formula:**
```
P = VI = I²R = V²/R
```

🎯 **Use:** Calculate power dissipated in a resistor

📊 **Values:**
- P = Power (Watt)
- V = Potential difference (Volt)
- I = Current (Ampere)
- R = Resistance (Ohm)

💡 **Notes:**
- SI unit: Watt (W) = Joule/second
- All three forms are equivalent (use based on given data)
- Power is always positive (energy dissipated as heat)

---

## 9️⃣ Electrical Energy

📚 **Topic:** Total energy consumed

📐 **Formula:**
```
E = Pt = VIt = I²Rt = V²t/R
```

🎯 **Use:** Calculate electrical energy consumed

📊 **Values:**
- E = Energy (Joule or kWh)
- P = Power (Watt)
- t = Time (second)

💡 **Notes:**
- 1 kWh = 3.6 × 10⁶ J
- Commercial unit: kilowatt-hour (kWh)
- Energy = Power × Time

---

## 🔟 Resistors in Series

📚 **Topic:** Equivalent resistance for series combination

📐 **Formula:**
```
R_s = R₁ + R₂ + R₃ + ...
```

🎯 **Use:** Calculate total resistance of resistors in series

📊 **Values:**
- R_s = Equivalent series resistance (Ohm)
- R₁, R₂, R₃ = Individual resistances (Ohm)

💡 **Notes:**
- Same current through all resistors
- Voltages add up: V = V₁ + V₂ + V₃
- Total resistance is greater than any individual resistance

---

## 1️⃣1️⃣ Resistors in Parallel

📚 **Topic:** Equivalent resistance for parallel combination

📐 **Formula:**
```
1/R_p = 1/R₁ + 1/R₂ + 1/R₃ + ...
```

🎯 **Use:** Calculate total resistance of resistors in parallel

📊 **Values:**
- R_p = Equivalent parallel resistance (Ohm)
- R₁, R₂, R₃ = Individual resistances (Ohm)

💡 **Notes:**
- Same voltage across all resistors
- Currents add up: I = I₁ + I₂ + I₃
- Total resistance is less than smallest individual resistance
- For two resistors: R_p = (R₁R₂)/(R₁+R₂)

---

## 1️⃣2️⃣ EMF and Internal Resistance

📚 **Topic:** Terminal voltage of a battery

📐 **Formula:**
```
V = E - Ir
```
or
```
E = V + Ir
```

🎯 **Use:** Calculate terminal voltage considering internal resistance

📊 **Values:**
- V = Terminal voltage (Volt)
- E = EMF of cell (Volt)
- I = Current (Ampere)
- r = Internal resistance (Ohm)

💡 **Notes:**
- EMF (E) is maximum voltage (when I = 0)
- Terminal voltage decreases with current
- Ir is voltage drop across internal resistance

---

## 1️⃣3️⃣ Cells in Series

📚 **Topic:** Combination of cells in series

📐 **Formula:**
```
E_total = E₁ + E₂ + E₃ + ...
```
```
r_total = r₁ + r₂ + r₃ + ...
```

🎯 **Use:** Calculate total EMF and internal resistance for series cells

📊 **Values:**
- E_total = Total EMF (Volt)
- r_total = Total internal resistance (Ohm)

💡 **Notes:**
- EMFs add up if connected in same polarity
- Used to increase voltage
- Current same through all cells

---

## 1️⃣4️⃣ Cells in Parallel

📚 **Topic:** Combination of identical cells in parallel

📐 **Formula:**
```
E_total = E (same as individual)
```
```
r_total = r / n
```

🎯 **Use:** Calculate total EMF and internal resistance for parallel cells

📊 **Values:**
- E_total = Total EMF (Volt)
- E = EMF of each cell (Volt)
- r_total = Total internal resistance (Ohm)
- r = Internal resistance of each cell (Ohm)
- n = Number of identical cells

💡 **Notes:**
- Voltage remains same
- Internal resistance reduces
- Used to increase current capacity

---

## 1️⃣5️⃣ Kirchhoff's Current Law (KCL)

📚 **Topic:** Conservation of charge at a junction

📐 **Formula:**
```
ΣI_in = ΣI_out
```
or
```
ΣI = 0 (at a junction)
```

🎯 **Use:** Apply at junctions to find unknown currents

📊 **Values:**
- I = Currents entering or leaving junction (Ampere)

💡 **Notes:**
- Based on conservation of charge
- Algebraic sum of currents at junction is zero
- Take one direction as positive, other as negative

---

## 1️⃣6️⃣ Kirchhoff's Voltage Law (KVL)

📚 **Topic:** Conservation of energy in a closed loop

📐 **Formula:**
```
ΣV = 0 (around a closed loop)
```
or
```
ΣEMF = ΣIR
```

🎯 **Use:** Apply in loops to find unknown voltages or currents

📊 **Values:**
- V = Voltage rises and drops (Volt)

💡 **Notes:**
- Based on conservation of energy
- Sum of voltage rises = Sum of voltage drops
- Choose direction and be consistent with signs

---

## 1️⃣7️⃣ Wheatstone Bridge (Balanced Condition)

📚 **Topic:** Bridge circuit for resistance measurement

📐 **Formula:**
```
P/Q = R/S
```
or
```
PS = QR
```

🎯 **Use:** Find unknown resistance using Wheatstone bridge

📊 **Values:**
- P, Q, R, S = Resistances in bridge arms (Ohm)

💡 **Notes:**
- When balanced, no current through galvanometer
- Used for precise resistance measurement
- If balanced: R_unknown = (R_known × Q) / P

---

## 1️⃣8️⃣ Meter Bridge Formula

📚 **Topic:** Practical form of Wheatstone bridge

📐 **Formula:**
```
X/R = l₁/l₂
```
or
```
X = R × (l₁/l₂)
```

🎯 **Use:** Calculate unknown resistance using meter bridge

📊 **Values:**
- X = Unknown resistance (Ohm)
- R = Known resistance (Ohm)
- l₁ = Length on one side of null point (cm)
- l₂ = Length on other side of null point (cm)

💡 **Notes:**
- l₁ + l₂ = 100 cm (total wire length)
- Most accurate when l₁ ≈ l₂ (null point near center)
- Practical application of Wheatstone bridge

---

## 1️⃣9️⃣ Potentiometer Principle

📚 **Topic:** Measurement of potential difference

📐 **Formula:**
```
V₁/V₂ = l₁/l₂
```
or
```
V = kl
```

🎯 **Use:** Compare EMFs or measure potential difference

📊 **Values:**
- V = Potential difference (Volt)
- l = Length of wire (cm or m)
- k = Potential gradient (V/m)

💡 **Notes:**
- Based on zero deflection method
- No current drawn at balance point
- More accurate than voltmeter

---

## 2️⃣0️⃣ Combination of Resistances (Mixed)

📚 **Topic:** Simplifying complex circuits

📐 **Formula:**
Series: R = R₁ + R₂
Parallel: 1/R = 1/R₁ + 1/R₂

🎯 **Use:** Reduce complex networks to single equivalent resistance

📊 **Values:**
- R = Equivalent resistance (Ohm)

💡 **Notes:**
- Identify series and parallel groups step by step
- Simplify from inside out
- Check if resistances are actually in series or parallel

---

## Important Constants to Remember 📝

| Constant | Symbol | Value |
|----------|--------|-------|
| Charge of electron | e | 1.6 × 10⁻¹⁹ C |
| Resistivity of copper | ρ_Cu | 1.7 × 10⁻⁸ Ω·m |
| Resistivity of silver | ρ_Ag | 1.6 × 10⁻⁸ Ω·m |
| Temperature coefficient (Cu) | α | ~4 × 10⁻³ per °C |
| 1 kWh | - | 3.6 × 10⁶ J |

---

## Quick Tips for Revision 💡

1. **Power Formulas:** Memorize all three forms (VI, I²R, V²/R) - use based on given data
2. **Series vs Parallel:** Series adds directly, parallel adds reciprocals
3. **Kirchhoff's Laws:** KCL at junctions, KVL in loops - master sign conventions
4. **Wheatstone Bridge:** Product of opposite arms equal when balanced
5. **Internal Resistance:** Always reduces terminal voltage (V = E - Ir)
6. **Units:** Check units in numerical problems (mA to A, kΩ to Ω, etc.)
7. **Meter Bridge:** Most accurate when null point is near 50 cm mark

---

*Pro tip: Practice circuit problems daily - patterns repeat in exams! Good luck! 🍂*
