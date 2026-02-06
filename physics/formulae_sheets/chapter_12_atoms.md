# Chapter 12: Atoms
## Formula Sheet for CBSE Class 12 Physics

---

## 12.1 Rutherford's Model of Atom

---

📚 **Topic: Distance of Closest Approach**

📐 **Formula:** 
```
r₀ = (1/4πε₀) × (2Ze²/KE) = kZe²/(½mv²)

OR

r₀ = (1/4πε₀) × (4Ze²/mv²)
```

🎯 **Use:** Calculates the minimum distance an alpha particle can approach a nucleus.

📊 **Values:**
- r₀ = Distance of closest approach
- Z = Atomic number of target nucleus
- e = Electron charge = 1.6 × 10⁻¹⁹ C
- KE = Initial kinetic energy of alpha particle
- k = Coulomb's constant = 9 × 10⁹ N·m²/C²
- m = Mass of alpha particle
- v = Initial velocity of alpha particle

💡 **Notes:** 
- At r₀, all KE converts to electrostatic PE
- Gives upper limit for nuclear size
- Alpha particle has charge +2e
- Energy conservation: ½mv² = kZe(2e)/r₀

🔑 **Derivation Hint:** At closest approach, KE = 0, all energy is PE. Initial KE = Final PE. ½mv² = k(2e)(Ze)/r₀

---

📚 **Topic: Impact Parameter**

📐 **Formula:** 
```
b = (Ze²/4πε₀) × cot(θ/2)/(½mv²)

OR

b = (kZe² × 2)/(mv²) × cot(θ/2)
```

🎯 **Use:** Relates the perpendicular distance from the nucleus to the scattering angle.

📊 **Values:**
- b = Impact parameter
- θ = Scattering angle
- Z = Atomic number
- m = Mass of alpha particle
- v = Velocity of alpha particle

💡 **Notes:** 
- b = 0 → θ = 180° (head-on collision, maximum deflection)
- b = ∞ → θ = 0° (no deflection)
- Larger b → Smaller scattering angle
- Most alpha particles pass undeflected (large b)

---

📚 **Topic: Rutherford Scattering Formula**

📐 **Formula:** 
```
N(θ) ∝ 1/sin⁴(θ/2)

N(θ) ∝ Z²/(KE)²

N(θ) ∝ t (thickness of foil)
```

🎯 **Use:** Describes the angular distribution of scattered alpha particles.

📊 **Values:**
- N(θ) = Number of particles scattered at angle θ
- θ = Scattering angle
- Z = Atomic number of target
- KE = Kinetic energy of alpha particles
- t = Thickness of metal foil

💡 **Notes:** 
- Most particles scatter at small angles
- Very few particles scatter at large angles (back-scattering)
- 1 in 8000 particles scattered by > 90°
- Confirmed positive charge concentrated in tiny nucleus

---

## 12.2 Bohr's Model of Hydrogen Atom

---

📚 **Topic: Bohr's Postulates**

📐 **Formula (Concepts):**
```
1. Electrons revolve in discrete orbits without radiating energy
2. Angular momentum is quantized: L = mvr = nh/(2π) = nℏ
3. Energy is emitted/absorbed only during transitions: ΔE = hν
```

🎯 **Use:** Foundation of Bohr's atomic model.

💡 **Notes:** 
- n = Principal quantum number (1, 2, 3, ...)
- Stationary orbits are non-radiating
- Energy is quantized (discrete values)
- Successfully explained hydrogen spectrum

---

📚 **Topic: Radius of Bohr Orbit**

📐 **Formula:** 
```
rₙ = (n²h²ε₀)/(πme²Z) = n²a₀/Z

rₙ = 0.529 × n²/Z Å

For hydrogen (Z=1): rₙ = 0.529 × n² Å
```

🎯 **Use:** Calculates the radius of nth allowed orbit.

📊 **Values:**
- rₙ = Radius of nth orbit
- n = Principal quantum number
- a₀ = Bohr radius = 0.529 Å = 0.529 × 10⁻¹⁰ m
- Z = Atomic number
- h = Planck's constant
- m = Mass of electron
- e = Electron charge

💡 **Notes:** 
- r₁ = 0.529 Å (ground state of hydrogen)
- rₙ ∝ n² (radius increases as n²)
- rₙ ∝ 1/Z (smaller for higher Z)
- Ground state (n=1) has smallest radius

🔑 **Derivation Hint:** Balance centripetal force with electrostatic force: mv²/r = kZe²/r². Use quantization: mvr = nh/2π. Eliminate v to get r.

---

📚 **Topic: Velocity of Electron in Bohr Orbit**

📐 **Formula:** 
```
vₙ = Ze²/(2ε₀nh) = (Z/n) × v₁

vₙ = 2.18 × 10⁶ × Z/n m/s

For hydrogen: v₁ = 2.18 × 10⁶ m/s ≈ c/137
```

🎯 **Use:** Calculates the orbital velocity of electron in nth orbit.

📊 **Values:**
- vₙ = Velocity in nth orbit
- Z = Atomic number
- n = Principal quantum number
- v₁ = Velocity in first Bohr orbit

💡 **Notes:** 
- vₙ ∝ Z/n (inversely proportional to n)
- Velocity decreases in outer orbits
- v₁ = c/137 (where α = 1/137 is fine structure constant)
- Non-relativistic since v << c

---

📚 **Topic: Energy of Electron in Bohr Orbit**

📐 **Formula:** 
```
Eₙ = -13.6 × Z²/n² eV

OR

Eₙ = -me⁴Z²/(8ε₀²h²n²) = -13.6Z²/n² eV

For hydrogen (Z=1): Eₙ = -13.6/n² eV
```

🎯 **Use:** Calculates the total energy of electron in nth orbit.

📊 **Values:**
- Eₙ = Total energy in nth orbit
- Z = Atomic number
- n = Principal quantum number (1, 2, 3, ...)
- 13.6 eV = -E₁ for hydrogen (ground state binding energy)

💡 **Notes:** 
- Negative sign indicates bound state
- E₁ = -13.6 eV (ground state, most stable)
- E∞ = 0 (ionization, electron free)
- Eₙ ∝ Z²/n² 
- |Eₙ| decreases with increasing n (less tightly bound)

🔑 **Derivation Hint:** Total energy E = KE + PE = ½mv² - kZe²/r. Use v and r from Bohr's conditions. E = -kZe²/2r = -13.6Z²/n² eV.

---

📚 **Topic: Kinetic and Potential Energy Relations**

📐 **Formula:** 
```
KE = -E = |Eₙ| = 13.6Z²/n² eV

PE = 2E = -27.2Z²/n² eV

Relation: KE = -E = -PE/2

OR: E = -KE = PE/2
```

🎯 **Use:** Relates kinetic, potential, and total energy.

📊 **Values:**
- KE = Kinetic energy (always positive)
- PE = Potential energy (always negative)
- E = Total energy = KE + PE

💡 **Notes:** 
- |KE| = |E| (magnitude of total energy)
- |PE| = 2|KE| = 2|E|
- Total energy is negative (bound system)
- Virial theorem: Average KE = -½ × Average PE

---

📚 **Topic: Time Period and Frequency of Revolution**

📐 **Formula:** 
```
Time period: Tₙ = 2πrₙ/vₙ = n³T₁/Z²

T₁ = 1.52 × 10⁻¹⁶ s (for hydrogen)

Frequency: fₙ = vₙ/(2πrₙ) = Z²f₁/n³

f₁ = 6.6 × 10¹⁵ Hz
```

🎯 **Use:** Calculates orbital period and frequency of electron.

📊 **Values:**
- Tₙ = Time period in nth orbit
- fₙ = Frequency of revolution
- rₙ = Orbital radius
- vₙ = Orbital velocity

💡 **Notes:** 
- Tₙ ∝ n³/Z² (period increases rapidly with n)
- fₙ ∝ Z²/n³ (frequency decreases with n)
- This is orbital frequency, not radiation frequency

---

📚 **Topic: Current and Magnetic Field Due to Orbiting Electron**

📐 **Formula:** 
```
Current: I = e/T = ef = eZ²f₁/n³

Magnetic field at nucleus: B = μ₀I/(2r) = μ₀eZ³v₁/(4πn⁴a₀)
```

🎯 **Use:** Calculates equivalent current and magnetic field.

📊 **Values:**
- I = Equivalent current due to orbiting electron
- T = Time period of revolution
- B = Magnetic field at center of orbit

💡 **Notes:** 
- Electron orbit acts like a current loop
- Current flows opposite to electron motion
- Magnetic moment: μ = IA = eωr²/2

---

## 12.3 Hydrogen Spectrum

---

📚 **Topic: Wavelength/Frequency of Emitted Radiation**

📐 **Formula:** 
```
1/λ = RZ²[1/n₁² - 1/n₂²] (n₂ > n₁)

OR

ν = RcZ²[1/n₁² - 1/n₂²]

hν = 13.6Z²[1/n₁² - 1/n₂²] eV
```

🎯 **Use:** Calculates wavelength of spectral lines during electron transition.

📊 **Values:**
- λ = Wavelength of emitted photon
- R = Rydberg constant = 1.097 × 10⁷ m⁻¹
- Z = Atomic number
- n₁ = Lower energy level (final)
- n₂ = Upper energy level (initial)
- ν = Frequency of radiation

💡 **Notes:** 
- n₂ → n₁ transition (emission)
- n₁ → n₂ transition (absorption)
- Energy of photon = |E₂ - E₁|
- R = 13.6 eV/(hc) = me⁴/(8ε₀²h³c)

🔑 **Derivation Hint:** Energy of photon hν = E₂ - E₁ = 13.6Z²(1/n₁² - 1/n₂²). Divide by hc to get 1/λ.

---

📚 **Topic: Spectral Series of Hydrogen**

📐 **Formula:** 
```
Lyman series (UV): n₁ = 1, n₂ = 2, 3, 4, ...
1/λ = R[1/1² - 1/n²]

Balmer series (Visible): n₁ = 2, n₂ = 3, 4, 5, ...
1/λ = R[1/2² - 1/n²]

Paschen series (IR): n₁ = 3, n₂ = 4, 5, 6, ...
1/λ = R[1/3² - 1/n²]

Brackett series (IR): n₁ = 4, n₂ = 5, 6, 7, ...
1/λ = R[1/4² - 1/n²]

Pfund series (Far IR): n₁ = 5, n₂ = 6, 7, 8, ...
1/λ = R[1/5² - 1/n²]
```

🎯 **Use:** Identifies different spectral series in hydrogen emission spectrum.

📊 **Values:**
- R = 1.097 × 10⁷ m⁻¹
- Each series has a series limit (n₂ → ∞)

💡 **Notes:** 
- Lyman: All transitions ending at n=1 (UV)
- Balmer: Visible lines (Hα, Hβ, Hγ, Hδ...)
- First line: Smallest transition (n₂ = n₁ + 1)
- Series limit: Maximum frequency (n₂ = ∞)

---

📚 **Topic: Important Wavelengths in Hydrogen Spectrum**

📐 **Formula:** 
```
Lyman series:
- First line (Lα): n=2→1, λ = 1216 Å
- Series limit: λ = 912 Å

Balmer series:
- First line (Hα): n=3→2, λ = 6563 Å (Red)
- Second line (Hβ): n=4→2, λ = 4861 Å (Blue-green)
- Series limit: λ = 3646 Å

Paschen series:
- First line: n=4→3, λ = 18750 Å
- Series limit: λ = 8204 Å
```

🎯 **Use:** Provides reference wavelengths for hydrogen lines.

💡 **Notes:** 
- Hα is most prominent Balmer line (red)
- Balmer series visible to human eye
- Series limit = ionization from that level

---

📚 **Topic: Maximum and Minimum Wavelength in a Series**

📐 **Formula:** 
```
Maximum wavelength (first line): n₂ = n₁ + 1
λₘₐₓ = n₁²(n₁+1)²/R(2n₁+1)

Minimum wavelength (series limit): n₂ = ∞
λₘᵢₙ = n₁²/R
```

🎯 **Use:** Identifies the range of wavelengths in each series.

📊 **Values:**
- λₘₐₓ = Longest wavelength (first line)
- λₘᵢₙ = Shortest wavelength (series limit)

💡 **Notes:** 
- First line has minimum energy transition
- Series limit corresponds to ionization
- All wavelengths in series lie between λₘᵢₙ and λₘₐₓ

---

📚 **Topic: Number of Spectral Lines**

📐 **Formula:** 
```
Maximum number of emission lines from nth level:

N = n(n-1)/2

Or using combination: N = ⁿC₂ = n!/(2!(n-2)!)
```

🎯 **Use:** Calculates total possible emission lines when electron de-excites.

📊 **Values:**
- N = Number of spectral lines
- n = Initial excited level

💡 **Notes:** 
- From n=4: N = 4×3/2 = 6 lines
- From n=3: N = 3×2/2 = 3 lines
- Counts all possible transitions to lower levels

---

📚 **Topic: Ionization Energy and Potential**

📐 **Formula:** 
```
Ionization energy = -E₁ = 13.6 Z² eV (from ground state)

Ionization energy from nth state = 13.6 Z²/n² eV

Ionization potential = 13.6 Z² V (from ground state)
```

🎯 **Use:** Calculates energy required to remove electron completely.

📊 **Values:**
- For hydrogen (Z=1): Ionization energy = 13.6 eV
- Ionization potential = 13.6 V

💡 **Notes:** 
- Ionization means transition to n = ∞
- Less energy needed to ionize from excited states
- 1 eV = 1.6 × 10⁻¹⁹ J

---

📚 **Topic: Excitation Energy and Potential**

📐 **Formula:** 
```
Excitation energy = E_final - E_initial

First excitation energy (n=1 to n=2):
E = E₂ - E₁ = -13.6/4 - (-13.6) = 10.2 eV

Excitation potential = Excitation energy/e
```

🎯 **Use:** Calculates energy needed to excite electron to higher level.

📊 **Values:**
- First excitation energy (H) = 10.2 eV
- Second excitation energy (n=1 to n=3) = 12.09 eV
- First excitation potential = 10.2 V

💡 **Notes:** 
- Excitation energy always positive
- First excitation potential for H = 10.2 V
- Electron remains bound after excitation

---

## 12.4 Hydrogen-like Ions

---

📚 **Topic: Hydrogen-like Ions (He⁺, Li²⁺, Be³⁺)**

📐 **Formula:** 
```
For hydrogen-like ion with atomic number Z:

rₙ = 0.529 × n²/Z Å
vₙ = 2.18 × 10⁶ × Z/n m/s
Eₙ = -13.6 × Z²/n² eV
1/λ = RZ²[1/n₁² - 1/n₂²]
```

🎯 **Use:** Applies Bohr model to single-electron ions.

📊 **Values:**
- He⁺: Z = 2
- Li²⁺: Z = 3
- Be³⁺: Z = 4

💡 **Notes:** 
- Bohr model works exactly for one-electron systems
- Higher Z means:
  - Smaller orbits (r ∝ 1/Z)
  - Higher velocities (v ∝ Z)
  - More tightly bound (E ∝ Z²)
- Ground state energy of He⁺ = -54.4 eV

---

📚 **Topic: Reduced Mass Correction**

📐 **Formula:** 
```
μ = mₑM/(mₑ + M) ≈ mₑ(1 - mₑ/M)

Corrected Rydberg constant:
R' = R × μ/mₑ = R × M/(mₑ + M)
```

🎯 **Use:** Accounts for nuclear motion in atomic calculations.

📊 **Values:**
- μ = Reduced mass
- mₑ = Electron mass
- M = Nuclear mass
- R' = Corrected Rydberg constant

💡 **Notes:** 
- For hydrogen: μ ≈ 0.99946 mₑ
- For heavier nuclei: μ → mₑ
- Explains slight difference in spectra of H and D (deuterium)

---

*End of Chapter 12 Formula Sheet*
