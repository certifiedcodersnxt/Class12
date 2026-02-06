# Chapter 14: Semiconductor Electronics: Materials, Devices and Simple Circuits
## Formula Sheet for CBSE Class 12 Physics

---

## 14.1 Classification of Materials

---

📚 **Topic: Classification Based on Conductivity**

📐 **Formula:** 
```
Conductors: σ > 10⁵ S/m (ρ < 10⁻⁵ Ω·m)
Semiconductors: σ ~ 10⁻⁶ to 10⁴ S/m
Insulators: σ < 10⁻¹¹ S/m (ρ > 10¹¹ Ω·m)
```

🎯 **Use:** Classifies materials based on electrical conductivity.

📊 **Values:**
- σ = Electrical conductivity (S/m)
- ρ = Resistivity (Ω·m)
- Conductor example: Cu, Ag (σ ~ 10⁷ S/m)
- Semiconductor example: Si, Ge (σ ~ 10⁻⁶ to 10⁴ S/m)
- Insulator example: Glass, rubber (σ < 10⁻¹¹ S/m)

💡 **Notes:** 
- Conductivity of semiconductors increases with temperature
- Conductivity of conductors decreases with temperature
- Semiconductor conductivity can be controlled by doping

---

📚 **Topic: Energy Band Classification**

📐 **Formula:** 
```
Conductors: E_g = 0 (overlapping bands) or partially filled
Semiconductors: E_g ~ 0.1 to 3 eV
Insulators: E_g > 3 eV

For Si: E_g = 1.1 eV
For Ge: E_g = 0.7 eV
For Diamond: E_g = 5.4 eV
```

🎯 **Use:** Classifies materials based on energy band gap.

📊 **Values:**
- E_g = Energy band gap
- Valence band: Occupied by valence electrons
- Conduction band: Electrons can conduct electricity
- Forbidden gap: Energy region between bands

💡 **Notes:** 
- At T = 0 K, valence band is full, conduction band is empty (semiconductor)
- Thermal excitation promotes electrons across band gap
- Smaller band gap → Easier excitation → More conductive

---

## 14.2 Intrinsic Semiconductors

---

📚 **Topic: Carrier Concentration in Intrinsic Semiconductor**

📐 **Formula:** 
```
nₑ = n_h = nᵢ (Intrinsic carrier concentration)

nᵢ = AT^(3/2) × e^(-E_g/2kT)

At room temperature (300 K):
Si: nᵢ ≈ 1.5 × 10¹⁶ /m³
Ge: nᵢ ≈ 2.4 × 10¹⁹ /m³
```

🎯 **Use:** Calculates number of charge carriers in pure semiconductor.

📊 **Values:**
- nₑ = Electron concentration
- n_h = Hole concentration
- nᵢ = Intrinsic carrier concentration
- T = Absolute temperature
- k = Boltzmann constant = 1.38 × 10⁻²³ J/K

💡 **Notes:** 
- In intrinsic semiconductor, electrons = holes
- Concentration increases with temperature
- Ge has more carriers than Si (smaller band gap)
- Each excited electron creates one hole

---

📚 **Topic: Conductivity of Intrinsic Semiconductor**

📐 **Formula:** 
```
σ = nᵢe(μₑ + μ_h) = nₑeμₑ + n_heμ_h

ρ = 1/σ = 1/[nᵢe(μₑ + μ_h)]
```

🎯 **Use:** Calculates conductivity of pure semiconductor.

📊 **Values:**
- σ = Conductivity
- nᵢ = Intrinsic carrier concentration
- e = Electron charge = 1.6 × 10⁻¹⁹ C
- μₑ = Electron mobility
- μ_h = Hole mobility
- For Si: μₑ ≈ 0.135 m²/V·s, μ_h ≈ 0.048 m²/V·s

💡 **Notes:** 
- Electrons are more mobile than holes
- Both electrons and holes contribute to conduction
- Conductivity increases exponentially with temperature

---

## 14.3 Extrinsic Semiconductors

---

📚 **Topic: n-type Semiconductor (Pentavalent Doping)**

📐 **Formula:** 
```
Dopants: P, As, Sb (Group 15 - 5 valence electrons)

nₑ >> n_h
nₑ ≈ N_D (donor concentration)

Mass action law: nₑ × n_h = nᵢ²

n_h = nᵢ²/N_D
```

🎯 **Use:** Describes properties of n-type semiconductor.

📊 **Values:**
- N_D = Donor atom concentration
- nₑ = Majority carriers (electrons)
- n_h = Minority carriers (holes)
- Donor energy level ≈ 0.01-0.05 eV below conduction band

💡 **Notes:** 
- Pentavalent impurity donates one electron
- Fifth electron is loosely bound (easily ionized)
- Majority carriers: Electrons
- Minority carriers: Holes
- Conductivity mainly due to electrons

---

📚 **Topic: p-type Semiconductor (Trivalent Doping)**

📐 **Formula:** 
```
Dopants: B, Al, Ga, In (Group 13 - 3 valence electrons)

n_h >> nₑ
n_h ≈ N_A (acceptor concentration)

Mass action law: nₑ × n_h = nᵢ²

nₑ = nᵢ²/N_A
```

🎯 **Use:** Describes properties of p-type semiconductor.

📊 **Values:**
- N_A = Acceptor atom concentration
- n_h = Majority carriers (holes)
- nₑ = Minority carriers (electrons)
- Acceptor energy level ≈ 0.01-0.05 eV above valence band

💡 **Notes:** 
- Trivalent impurity accepts one electron (creates hole)
- Hole is the missing electron in covalent bond
- Majority carriers: Holes
- Minority carriers: Electrons
- Conductivity mainly due to holes

---

📚 **Topic: Conductivity of Extrinsic Semiconductor**

📐 **Formula:** 
```
n-type: σ ≈ N_D × e × μₑ

p-type: σ ≈ N_A × e × μ_h

General: σ = e(nₑμₑ + n_hμ_h)
```

🎯 **Use:** Calculates conductivity of doped semiconductor.

📊 **Values:**
- Typical doping: 1 impurity per 10⁶ to 10⁸ Si atoms
- N_D or N_A ~ 10²¹ to 10²⁴ /m³
- Conductivity increases by 10³ to 10⁶ times

💡 **Notes:** 
- Doping dramatically increases conductivity
- Temperature dependence is weaker than intrinsic
- Controlled conductivity enables device design

---

## 14.4 p-n Junction

---

📚 **Topic: Depletion Region**

📐 **Formula:** 
```
Depletion width: W ∝ √(V_bi/N)

W = √[2ε(V_bi + V_R)/eN]

where N = N_AN_D/(N_A + N_D)
```

🎯 **Use:** Describes the width of depletion region at p-n junction.

📊 **Values:**
- W = Depletion width (typically 0.1 to 1 μm)
- V_bi = Built-in potential
- V_R = Applied reverse bias
- ε = Permittivity of semiconductor
- N_A, N_D = Acceptor and donor concentrations

💡 **Notes:** 
- Depletion region has no mobile charges
- Contains fixed ionized donors (+) and acceptors (-)
- Electric field exists across depletion region
- Width increases with reverse bias
- Width decreases with forward bias

---

📚 **Topic: Built-in Potential (Barrier Potential)**

📐 **Formula:** 
```
V_bi = (kT/e) × ln(N_AN_D/nᵢ²)

V_bi = V_T × ln(N_AN_D/nᵢ²)

where V_T = kT/e ≈ 26 mV at 300 K
```

🎯 **Use:** Calculates the potential barrier at p-n junction.

📊 **Values:**
- V_bi ≈ 0.7 V for Si
- V_bi ≈ 0.3 V for Ge
- V_T = Thermal voltage ≈ 26 mV at room temperature

💡 **Notes:** 
- Barrier prevents further diffusion at equilibrium
- Created by charge separation during junction formation
- Must be overcome for forward conduction

🔑 **Derivation Hint:** At equilibrium, drift current = diffusion current. The potential barrier stops net flow of majority carriers.

---

📚 **Topic: p-n Junction Diode Equation**

📐 **Formula:** 
```
I = I₀[e^(eV/kT) - 1] = I₀[e^(V/V_T) - 1]

where V_T = kT/e ≈ 26 mV (at 300 K)
```

🎯 **Use:** Describes I-V characteristics of p-n junction.

📊 **Values:**
- I = Diode current
- I₀ = Reverse saturation current (very small, ~nA to μA)
- V = Applied voltage (+ for forward, - for reverse)
- V_T = Thermal voltage

💡 **Notes:** 
- Forward bias (V > 0): I increases exponentially
- Reverse bias (V < 0): I ≈ -I₀ (saturation current)
- Ideal diode: I = I₀e^(V/V_T) for V >> V_T
- At V = V_T: I ≈ 1.72 × I₀

---

📚 **Topic: Forward and Reverse Bias**

📐 **Formula:** 
```
Forward bias: p-side positive, n-side negative
- Barrier reduces: V_eff = V_bi - V_F
- Current increases exponentially
- Knee voltage: ~0.7 V (Si), ~0.3 V (Ge)

Reverse bias: p-side negative, n-side positive
- Barrier increases: V_eff = V_bi + V_R
- Only small leakage current flows
- Breakdown at high reverse voltage
```

🎯 **Use:** Describes diode behavior under different bias conditions.

📊 **Values:**
- Forward current: mA to A range
- Reverse current: nA to μA range
- Forward voltage drop: 0.6-0.7 V (Si)

💡 **Notes:** 
- Forward bias: Depletion region narrows, resistance decreases
- Reverse bias: Depletion region widens, high resistance
- Diode conducts primarily in one direction

---

📚 **Topic: Dynamic (AC) Resistance**

📐 **Formula:** 
```
Dynamic resistance: r_d = dV/dI = V_T/I = kT/(eI)

At room temperature: r_d = 26 mV/I (I in mA gives r_d in Ω)
```

🎯 **Use:** Calculates small-signal resistance of diode.

📊 **Values:**
- r_d = Dynamic/AC resistance
- V_T = 26 mV at 300 K
- I = Operating current

💡 **Notes:** 
- Dynamic resistance decreases with increasing current
- At I = 26 mA: r_d = 1 Ω
- Important for AC signal analysis

---

## 14.5 Special Purpose Diodes

---

📚 **Topic: Zener Diode**

📐 **Formula:** 
```
Breakdown mechanisms:
- Zener breakdown: V_Z < 4 V (high doping)
- Avalanche breakdown: V_Z > 6 V (low doping)

Voltage regulation: V_out = V_Z (constant in breakdown)

Current limiting resistor: R = (V_in - V_Z)/I_Z
```

🎯 **Use:** Describes Zener diode for voltage regulation.

📊 **Values:**
- V_Z = Zener breakdown voltage (2 V to 200 V available)
- I_Z(min) = Minimum current for regulation
- I_Z(max) = Maximum current before damage
- P_Z(max) = Maximum power dissipation

💡 **Notes:** 
- Operates in reverse breakdown region
- Maintains constant voltage across it
- Used as voltage regulator, reference voltage
- Sharp breakdown characteristic
- Temperature coefficient: negative for Zener, positive for avalanche

---

📚 **Topic: Photodiode**

📐 **Formula:** 
```
Photocurrent: I_ph ∝ Light intensity

I = I₀ + I_ph = I₀ + ηeΦ/hν

Responsivity: R = I_ph/P = ηeλ/(hc) A/W
```

🎯 **Use:** Converts light to electrical current.

📊 **Values:**
- I_ph = Photocurrent
- Φ = Photon flux (photons/s)
- η = Quantum efficiency
- P = Incident optical power
- R = Responsivity (A/W)

💡 **Notes:** 
- Operates in reverse bias (photovoltaic or photoconductive mode)
- Light creates electron-hole pairs in depletion region
- Fast response time (~ns)
- Applications: Light detection, optical communication
- Materials: Si, Ge, InGaAs for different wavelengths

---

📚 **Topic: Light Emitting Diode (LED)**

📐 **Formula:** 
```
Photon energy: E = hν = hc/λ = E_g

Wavelength: λ = hc/E_g = 1240/E_g(eV) nm

External efficiency: η = (Photons emitted)/(Electrons injected)
```

🎯 **Use:** Converts electrical current to light.

📊 **Values:**
- Forward voltage: 1.5-3.5 V depending on color
- GaAs: IR (λ ~ 900 nm), E_g = 1.4 eV
- GaP: Green/Red, E_g = 2.3 eV
- GaN: Blue/UV, E_g = 3.4 eV
- InGaN: Blue to Green

💡 **Notes:** 
- Operates in forward bias
- Electrons recombine with holes, emitting photons
- Direct bandgap semiconductors (GaAs, GaN) are efficient
- Indirect bandgap (Si, Ge) are poor light emitters
- Applications: Displays, lighting, indicators, communication

---

📚 **Topic: Solar Cell (Photovoltaic Cell)**

📐 **Formula:** 
```
Open circuit voltage: V_oc = (kT/e) × ln(I_L/I₀ + 1)

Short circuit current: I_sc = I_L ∝ Light intensity

Maximum power: P_max = V_mp × I_mp

Fill factor: FF = P_max/(V_oc × I_sc)

Efficiency: η = P_max/P_incident = (FF × V_oc × I_sc)/P_incident
```

🎯 **Use:** Converts sunlight directly to electricity.

📊 **Values:**
- V_oc ≈ 0.5-0.6 V (for Si solar cell)
- Fill factor: 0.7-0.85 for good cells
- Efficiency: 15-25% (commercial Si cells)
- I_L = Light-generated current

💡 **Notes:** 
- No external bias needed (self-powered)
- Operates in fourth quadrant of I-V curve
- Multiple cells in series for higher voltage
- Materials: Si (most common), GaAs, CdTe, perovskites
- Efficiency limited by band gap and recombination

---

## 14.6 Junction Transistor

---

📚 **Topic: Transistor Configurations and Current Relations**

📐 **Formula:** 
```
I_E = I_B + I_C (Current conservation)

α = I_C/I_E (Common base current gain) ~ 0.95 to 0.99

β = I_C/I_B (Common emitter current gain) ~ 20 to 500

Relations:
α = β/(1 + β)
β = α/(1 - α)
I_C = βI_B = αI_E
```

🎯 **Use:** Relates currents in different transistor terminals.

📊 **Values:**
- I_E = Emitter current (largest)
- I_C = Collector current
- I_B = Base current (smallest)
- α < 1 (always)
- β >> 1 (typically 50-300)

💡 **Notes:** 
- npn transistor: Electrons are majority carriers
- pnp transistor: Holes are majority carriers
- Emitter is heavily doped, base is thin and lightly doped
- Most emitter current reaches collector (α close to 1)

🔑 **Derivation Hint:** From I_E = I_B + I_C, divide by I_E: 1 = I_B/I_E + α, so α = 1 - I_B/I_E. Similarly, β = I_C/I_B = αI_E/I_B.

---

📚 **Topic: Transistor Biasing for Active Region**

📐 **Formula:** 
```
Active region conditions:
- Emitter-Base junction: Forward biased
- Collector-Base junction: Reverse biased

For npn:
- V_BE > 0 (≈ 0.7 V for Si)
- V_CB > 0 (or V_CE > V_CE(sat) ≈ 0.2 V)
```

🎯 **Use:** Establishes conditions for transistor amplification.

📊 **Values:**
- V_BE ≈ 0.7 V (Si), 0.3 V (Ge)
- V_CE(sat) ≈ 0.2 V
- V_CE should be > V_CE(sat) for active region

💡 **Notes:** 
- Saturation: Both junctions forward biased (switch ON)
- Cutoff: Both junctions reverse biased (switch OFF)
- Active: Amplification region
- Transistor as switch: Cutoff ↔ Saturation
- Transistor as amplifier: Active region

---

📚 **Topic: Common Emitter Amplifier**

📐 **Formula:** 
```
Voltage gain: A_v = -β × R_C/r_i = -g_m × R_C

where g_m = I_C/V_T = Transconductance

Input resistance: r_i = βr_e = β(V_T/I_E) ≈ β × 26/I_E(mA) Ω

Output resistance: r_o ≈ R_C

Power gain: A_p = A_v × A_i = A_v × β
```

🎯 **Use:** Calculates gain parameters of CE amplifier.

📊 **Values:**
- A_v = Voltage gain (can be > 100)
- g_m = Transconductance (mA/V)
- r_i = Input impedance
- r_o = Output impedance
- r_e = Dynamic emitter resistance = V_T/I_E

💡 **Notes:** 
- Negative sign indicates phase inversion (180°)
- High voltage and current gain
- Moderate input and output impedance
- Most commonly used configuration
- Phase inversion: Output inverted w.r.t. input

---

📚 **Topic: Load Line Analysis**

📐 **Formula:** 
```
DC load line: V_CE = V_CC - I_C × R_C

At I_C = 0: V_CE = V_CC (X-intercept)
At V_CE = 0: I_C = V_CC/R_C (Y-intercept)

Operating point (Q-point): Intersection of load line and base current curve
```

🎯 **Use:** Determines DC operating point of transistor.

📊 **Values:**
- V_CC = Supply voltage
- R_C = Collector resistance
- Q-point should be in middle of load line for maximum swing

💡 **Notes:** 
- Load line is straight line on output characteristics
- Q-point determines DC bias conditions
- For amplifier: Q-point in active region
- Proper biasing ensures linear operation

---

## 14.7 Digital Electronics

---

📚 **Topic: Logic Gates - Basic Operations**

📐 **Formula:** 
```
NOT gate: Y = Ā (Inversion)
- 0 → 1, 1 → 0

OR gate: Y = A + B (Logical OR)
- Output 1 if any input is 1

AND gate: Y = A · B (Logical AND)
- Output 1 only if all inputs are 1

NAND gate: Y = (A · B)' = NOT(A AND B)

NOR gate: Y = (A + B)' = NOT(A OR B)

XOR gate: Y = A ⊕ B = A'B + AB'
- Output 1 if inputs are different
```

🎯 **Use:** Defines basic logic operations.

📊 **Values:**
- Binary: 0 (LOW/FALSE) and 1 (HIGH/TRUE)
- Positive logic: High voltage = 1, Low voltage = 0

💡 **Notes:** 
- NAND and NOR are universal gates
- Any logic function can be built using only NAND or only NOR
- XOR gives 1 for odd number of 1s
- XNOR gives 1 for even number of 1s (including zero)

---

📚 **Topic: Boolean Algebra Laws**

📐 **Formula:** 
```
Basic laws:
- Identity: A + 0 = A, A · 1 = A
- Null: A + 1 = 1, A · 0 = 0
- Complement: A + A' = 1, A · A' = 0
- Idempotent: A + A = A, A · A = A
- Involution: (A')' = A

De Morgan's Theorems:
(A + B)' = A' · B'
(A · B)' = A' + B'

Commutative: A + B = B + A, A · B = B · A
Associative: (A + B) + C = A + (B + C)
Distributive: A · (B + C) = A·B + A·C
```

🎯 **Use:** Simplifies logic expressions.

💡 **Notes:** 
- De Morgan's theorems are crucial for circuit simplification
- NAND = AND followed by NOT
- NOR = OR followed by NOT
- Used to convert between gate types

---

📚 **Topic: NAND as Universal Gate**

📐 **Formula:** 
```
NOT using NAND: Y = (A · A)' = A'

AND using NAND: Y = ((A · B)')' 
- Two NAND gates

OR using NAND: Y = (A' · B')' = A + B
- Three NAND gates (two inverters + one NAND)
```

🎯 **Use:** Implements all gates using only NAND.

💡 **Notes:** 
- NAND gate is universal (can build any circuit)
- Economical for IC fabrication
- TTL logic primarily uses NAND gates
- Similar constructions possible with NOR

---

📚 **Topic: NOR as Universal Gate**

📐 **Formula:** 
```
NOT using NOR: Y = (A + A)' = A'

OR using NOR: Y = ((A + B)')'
- Two NOR gates

AND using NOR: Y = (A' + B')' = A · B
- Three NOR gates (two inverters + one NOR)
```

🎯 **Use:** Implements all gates using only NOR.

💡 **Notes:** 
- NOR gate is also universal
- CMOS logic often uses NOR gates
- Both NAND and NOR are complete sets

---

📚 **Topic: Truth Tables**

📐 **Formula:** 
```
NOT:          OR:           AND:
A | Y         A B | Y       A B | Y
0 | 1         0 0 | 0       0 0 | 0
1 | 0         0 1 | 1       0 1 | 0
              1 0 | 1       1 0 | 0
              1 1 | 1       1 1 | 1

NAND:         NOR:          XOR:
A B | Y       A B | Y       A B | Y
0 0 | 1       0 0 | 1       0 0 | 0
0 1 | 1       0 1 | 0       0 1 | 1
1 0 | 1       1 0 | 0       1 0 | 1
1 1 | 0       1 1 | 0       1 1 | 0
```

🎯 **Use:** Shows input-output relationships for logic gates.

💡 **Notes:** 
- Truth table completely defines gate behavior
- n inputs → 2ⁿ rows in truth table
- NAND = inverted AND output
- NOR = inverted OR output

---

## 14.8 Important Device Equations Summary

---

📚 **Topic: Key Semiconductor Equations**

📐 **Formula:** 
```
1. Mass action law: nₑ × n_h = nᵢ²

2. Conductivity: σ = e(nₑμₑ + n_hμ_h)

3. Diode equation: I = I₀[e^(V/V_T) - 1]

4. Transistor current: I_E = I_B + I_C

5. Current gains: α = I_C/I_E, β = I_C/I_B

6. Relation: β = α/(1-α)

7. CE voltage gain: A_v = -β(R_C/r_i)
```

🎯 **Use:** Quick reference for important equations.

💡 **Notes:** 
- These equations form the basis of semiconductor device analysis
- Understanding physical meaning is more important than memorization
- V_T = kT/e ≈ 26 mV at room temperature

---

*End of Chapter 14 Formula Sheet*
