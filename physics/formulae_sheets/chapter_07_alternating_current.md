# Chapter 7: Alternating Current

---

## 📚 Topic: Alternating Voltage

### 📐 Formula: 
```
V = V₀ sin(ωt)
```

### 🎯 Use: 
Represents instantaneous value of AC voltage

### 📊 Values:
- V = Instantaneous voltage (Volts, V)
- V₀ = Peak/Maximum voltage (V)
- ω = Angular frequency (rad/s)
- t = Time (seconds, s)

### 💡 Notes:
- Voltage varies sinusoidally with time
- V₀ is also called amplitude
- Can also be written as V = V₀ sin(2πft)

---

## 📚 Topic: Alternating Current

### 📐 Formula: 
```
I = I₀ sin(ωt + φ)
```

### 🎯 Use: 
Represents instantaneous value of AC current

### 📊 Values:
- I = Instantaneous current (Amperes, A)
- I₀ = Peak/Maximum current (A)
- ω = Angular frequency (rad/s)
- t = Time (s)
- φ = Phase difference between V and I

### 💡 Notes:
- φ = 0 for pure resistor
- φ = +90° for pure inductor (I lags V)
- φ = -90° for pure capacitor (I leads V)

---

## 📚 Topic: Angular Frequency

### 📐 Formula: 
```
ω = 2πf
```

### 🎯 Use: 
Relates angular frequency to frequency

### 📊 Values:
- ω = Angular frequency (rad/s)
- f = Frequency (Hertz, Hz)
- 2π = Radians in one cycle

### 💡 Notes:
- Standard frequency in India: 50 Hz
- ω = 2π/T where T is time period
- Higher frequency → faster oscillations

---

## 📚 Topic: RMS (Root Mean Square) Voltage

### 📐 Formula: 
```
Vᵣₘₛ = V₀/√2 ≈ 0.707 V₀
```

### 🎯 Use: 
Calculates effective value of AC voltage

### 📊 Values:
- Vᵣₘₛ = RMS/Effective voltage (V)
- V₀ = Peak voltage (V)
- √2 ≈ 1.414

### 💡 Notes:
- Household supply: 230V RMS (India), 120V RMS (USA)
- Produces same heating effect as DC
- Used in all AC ratings

---

## 📚 Topic: RMS (Root Mean Square) Current

### 📐 Formula: 
```
Iᵣₘₛ = I₀/√2 ≈ 0.707 I₀
```

### 🎯 Use: 
Calculates effective value of AC current

### 📊 Values:
- Iᵣₘₛ = RMS/Effective current (A)
- I₀ = Peak current (A)
- √2 ≈ 1.414

### 💡 Notes:
- Equivalent DC current for same power
- Ammeter readings show RMS values
- Peak current I₀ = √2 Iᵣₘₛ

---

## 📚 Topic: Average Power in AC Circuit

### 📐 Formula: 
```
P = VᵣₘₛIᵣₘₛ cos φ
```

### 🎯 Use: 
Calculates average power consumed in AC circuit

### 📊 Values:
- P = Average power (Watts, W)
- Vᵣₘₛ = RMS voltage (V)
- Iᵣₘₛ = RMS current (A)
- cos φ = Power factor

### 💡 Notes:
- cos φ is called power factor
- Maximum power when φ = 0° (pure resistive)
- Zero power when φ = 90° (purely reactive)

---

## 📚 Topic: Power Factor

### 📐 Formula: 
```
Power Factor = cos φ = R/Z
```

### 🎯 Use: 
Measures efficiency of power transfer

### 📊 Values:
- cos φ = Power factor (dimensionless)
- φ = Phase angle between V and I
- R = Resistance (Ω)
- Z = Impedance (Ω)

### 💡 Notes:
- Range: 0 to 1
- 1 = ideal (pure resistive)
- Low power factor wastes energy

---

## 📚 Topic: Inductive Reactance

### 📐 Formula: 
```
Xₗ = ωL = 2πfL
```

### 🎯 Use: 
Calculates opposition to AC by inductor

### 📊 Values:
- Xₗ = Inductive reactance (Ohms, Ω)
- ω = Angular frequency (rad/s)
- L = Inductance (Henry, H)
- f = Frequency (Hz)

### 💡 Notes:
- Increases with frequency
- DC (f=0) → Xₗ = 0 (short circuit)
- Current lags voltage by 90° in pure inductor

---

## 📚 Topic: Capacitive Reactance

### 📐 Formula: 
```
Xc = 1/(ωC) = 1/(2πfC)
```

### 🎯 Use: 
Calculates opposition to AC by capacitor

### 📊 Values:
- Xc = Capacitive reactance (Ohms, Ω)
- ω = Angular frequency (rad/s)
- C = Capacitance (Farad, F)
- f = Frequency (Hz)

### 💡 Notes:
- Decreases with frequency
- DC (f=0) → Xc = ∞ (open circuit)
- Current leads voltage by 90° in pure capacitor

---

## 📚 Topic: Impedance (R-L Circuit)

### 📐 Formula: 
```
Z = √(R² + Xₗ²)
```

### 🎯 Use: 
Calculates total opposition in R-L circuit

### 📊 Values:
- Z = Impedance (Ω)
- R = Resistance (Ω)
- Xₗ = Inductive reactance (Ω)

### 💡 Notes:
- Vector sum, not algebraic
- Current lags voltage
- Phase angle: tan φ = Xₗ/R

---

## 📚 Topic: Impedance (R-C Circuit)

### 📐 Formula: 
```
Z = √(R² + Xc²)
```

### 🎯 Use: 
Calculates total opposition in R-C circuit

### 📊 Values:
- Z = Impedance (Ω)
- R = Resistance (Ω)
- Xc = Capacitive reactance (Ω)

### 💡 Notes:
- Vector sum, not algebraic
- Current leads voltage
- Phase angle: tan φ = -Xc/R

---

## 📚 Topic: Impedance (R-L-C Circuit)

### 📐 Formula: 
```
Z = √[R² + (Xₗ - Xc)²]
```

### 🎯 Use: 
Calculates total opposition in series RLC circuit

### 📊 Values:
- Z = Impedance (Ω)
- R = Resistance (Ω)
- Xₗ = Inductive reactance (Ω)
- Xc = Capacitive reactance (Ω)

### 💡 Notes:
- Net reactance = Xₗ - Xc
- If Xₗ > Xc: inductive circuit (I lags V)
- If Xc > Xₗ: capacitive circuit (I leads V)

---

## 📚 Topic: Current in AC Circuit

### 📐 Formula: 
```
I = V/Z
```

### 🎯 Use: 
Calculates current using Ohm's law for AC

### 📊 Values:
- I = RMS current (A)
- V = RMS voltage (V)
- Z = Impedance (Ω)

### 💡 Notes:
- Works for RMS or peak values (consistent units)
- Current and voltage may be out of phase
- Z depends on frequency

---

## 📚 Topic: Phase Angle (RLC Circuit)

### 📐 Formula: 
```
tan φ = (Xₗ - Xc)/R
```

### 🎯 Use: 
Calculates phase difference between voltage and current

### 📊 Values:
- φ = Phase angle (degrees or radians)
- Xₗ = Inductive reactance (Ω)
- Xc = Capacitive reactance (Ω)
- R = Resistance (Ω)

### 💡 Notes:
- φ > 0: current lags (inductive)
- φ < 0: current leads (capacitive)
- φ = 0: resonance

---

## 📚 Topic: Resonance Frequency

### 📐 Formula: 
```
f₀ = 1/(2π√(LC))
```

### 🎯 Use: 
Calculates frequency at which XL = XC (resonance)

### 📊 Values:
- f₀ = Resonant frequency (Hz)
- L = Inductance (H)
- C = Capacitance (F)

### 💡 Notes:
- At resonance: Z = R (minimum impedance)
- Current is maximum at resonance
- Used in radio tuning circuits

---

## 📚 Topic: Resonance Angular Frequency

### 📐 Formula: 
```
ω₀ = 1/√(LC)
```

### 🎯 Use: 
Calculates angular frequency at resonance

### 📊 Values:
- ω₀ = Resonant angular frequency (rad/s)
- L = Inductance (H)
- C = Capacitance (F)

### 💡 Notes:
- Relation: ω₀ = 2πf₀
- At resonance: Xₗ = Xc
- Power factor = 1 (purely resistive)

---

## 📚 Topic: Quality Factor (Q-factor)

### 📐 Formula: 
```
Q = ω₀L/R = 1/(ω₀CR) = (1/R)√(L/C)
```

### 🎯 Use: 
Measures sharpness of resonance

### 📊 Values:
- Q = Quality factor (dimensionless)
- ω₀ = Resonant angular frequency (rad/s)
- L = Inductance (H)
- R = Resistance (Ω)
- C = Capacitance (F)

### 💡 Notes:
- Higher Q → sharper resonance peak
- Low R → high Q → better selectivity
- Important in radio receivers

---

## 📚 Topic: Bandwidth

### 📐 Formula: 
```
Δω = ω₀/Q = R/L
```

### 🎯 Use: 
Calculates width of resonance curve

### 📊 Values:
- Δω = Bandwidth (rad/s)
- ω₀ = Resonant angular frequency (rad/s)
- Q = Quality factor
- R = Resistance (Ω)
- L = Inductance (H)

### 💡 Notes:
- Smaller bandwidth → more selective
- Higher Q → smaller bandwidth
- Measured at half-power points

---

## 📚 Topic: Transformer Voltage Ratio

### 📐 Formula: 
```
Vₛ/Vₚ = Nₛ/Nₚ
```

### 🎯 Use: 
Relates primary and secondary voltages in ideal transformer

### 📊 Values:
- Vₛ = Secondary voltage (V)
- Vₚ = Primary voltage (V)
- Nₛ = Number of turns in secondary coil
- Nₚ = Number of turns in primary coil

### 💡 Notes:
- Step-up: Nₛ > Nₚ (increases voltage)
- Step-down: Nₛ < Nₚ (decreases voltage)
- Works on mutual induction principle

---

## 📚 Topic: Transformer Current Ratio

### 📐 Formula: 
```
Iₛ/Iₚ = Nₚ/Nₛ
```

### 🎯 Use: 
Relates primary and secondary currents in ideal transformer

### 📊 Values:
- Iₛ = Secondary current (A)
- Iₚ = Primary current (A)
- Nₚ = Number of turns in primary
- Nₛ = Number of turns in secondary

### 💡 Notes:
- Current ratio is inverse of voltage ratio
- Power is conserved: VₚIₚ = VₛIₛ
- Valid for ideal transformer (100% efficiency)

---

## 📚 Topic: Transformer Efficiency

### 📐 Formula: 
```
η = (Output Power/Input Power) × 100%
```

### 🎯 Use: 
Calculates efficiency of transformer

### 📊 Values:
- η = Efficiency (percentage)
- Output Power = VₛIₛ (W)
- Input Power = VₚIₚ (W)

### 💡 Notes:
- Practical transformers: 90-99% efficient
- Energy lost as heat (copper and core losses)
- Ideal transformer: η = 100%

---

## 📚 Topic: Wattless Current

### 📐 Formula: 
```
Iᵥ = Iᵣₘₛ sin φ
```

### 🎯 Use: 
Calculates component of current that does no work

### 📊 Values:
- Iᵥ = Wattless/Reactive current (A)
- Iᵣₘₛ = Total RMS current (A)
- φ = Phase angle

### 💡 Notes:
- Also called reactive current
- Does not contribute to power
- Zero in pure resistive circuits

---

## 📚 Topic: Power Current

### 📐 Formula: 
```
Iₚ = Iᵣₘₛ cos φ
```

### 🎯 Use: 
Calculates component of current that does work

### 📊 Values:
- Iₚ = Power/Active current (A)
- Iᵣₘₛ = Total RMS current (A)
- φ = Phase angle

### 💡 Notes:
- Also called active current
- Contributes to real power
- Maximum when cos φ = 1

---

## 📚 Topic: Peak Power

### 📐 Formula: 
```
Pₘₐₓ = V₀I₀
```

### 🎯 Use: 
Calculates maximum instantaneous power

### 📊 Values:
- Pₘₐₓ = Peak power (W)
- V₀ = Peak voltage (V)
- I₀ = Peak current (A)

### 💡 Notes:
- Occurs twice per cycle
- Average power = Pₘₐₓ/2 for pure resistor
- Not useful for practical calculations

---

## Important Constants

- **Standard frequency (India)**: 50 Hz
- **Standard frequency (USA)**: 60 Hz
- **Household voltage (India)**: 230V RMS
- **√2**: ≈ 1.414

---

## Key Concepts

1. **AC vs DC**: Alternating current reverses direction periodically
2. **RMS Values**: Effective values for power calculations
3. **Reactance**: Frequency-dependent opposition (XL and XC)
4. **Impedance**: Total opposition in AC circuits
5. **Phase Difference**: Time lag between voltage and current
6. **Resonance**: XL = XC, maximum current, minimum impedance
7. **Power Factor**: Efficiency of power transfer (cos φ)
8. **Transformer**: Steps voltage up or down using mutual induction

---

## Memory Tips

- **ELI the ICE man**: In **L**, **I** lags V; In **C**, **I** leads V
- **CIVIL**: In **C**, **I** before V; In **L**, V before I
- At resonance: "LC circuit acts like pure R"
- Higher frequency → Higher XL, Lower XC

---

**Revision Tips:**
- Practice phasor diagrams for phase relationships
- Memorize formulas for impedance in different combinations
- Understand resonance conditions and applications
- Learn transformer calculations for boards
- Remember sign conventions for phase angles
