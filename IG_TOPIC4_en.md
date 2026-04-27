# IGCSE Physics 0625 – Topic 4: Electricity and Magnetism

## Complete Learning Edition (Strictly following CAIE 2023–2025 syllabus)

> This document follows the official syllabus order and covers all Core and Supplement (Extended) content.  
> All formulas are written with `$$ ... $$`. Tables are clear and symbols are standard.

---

## Syllabus Structure

| Section | Sub-topic | Level |
|---------|-----------|-------|
| 4.1 | Simple phenomena of magnetism | Core |
| 4.2 | Electrical quantities | Core |
| 4.3 | Electric circuits | Core |
| 4.4 | Digital electronics | Supplement (Extended only) |
| 4.5 | Dangers of electricity | Core |
| 4.6 | Electromagnetic effects | Supplement (Extended only) |

---

## 4.1 Simple Phenomena of Magnetism

### Magnetic and Non‑magnetic Materials

| Category | Examples | Attracted? | Can be magnetised? |
|----------|----------|------------|--------------------|
| Magnetic | iron, steel, nickel, cobalt | Yes | Yes |
| Non‑magnetic | copper, aluminium, plastic, glass, wood | No | No |

> Steel is magnetic; stainless steel may be non‑magnetic depending on composition.

### Properties of Magnets

- Every magnet has a **north (N)** and **south (S)** pole.
- Like poles repel, unlike poles attract.
- A freely suspended magnet aligns N pole to geographic north.

### Magnetisation and Demagnetisation

**Magnetisation methods**:
- **Single stroke**: rub with one pole from one end to the other. **The end where the magnet leaves acquires the opposite polarity**.
- **Double stroke**: rub with two opposite poles together.
- **Electrical**: place inside a DC solenoid.

**Demagnetisation**: heating, hammering, or slowly withdrawing from an AC coil.

**Hard vs soft magnetic materials**:
- **Hard (steel)**: retains magnetism → permanent magnets.
- **Soft (soft iron)**: magnetises easily but loses magnetism easily → electromagnet cores.

### Magnetic Fields

- Field lines go from N to S outside the magnet, never cross, denser where field is stronger.
- Iron filings show pattern; plotting compass shows direction.

---

## 4.2 Electrical Quantities

### Electric Charge

- Two types: positive (+), negative (–).
- Like charges repel, unlike attract.
- **Friction**: electrons transfer – material losing electrons becomes positive, gaining electrons becomes negative.

**Electrostatic induction**: a charged body near a conductor redistributes charges. Grounding allows excess electrons to flow to earth. Remove earth wire *then* the charged body → conductor becomes oppositely charged.

### Electric Current

$$ I = \frac{Q}{t} $$
Unit: ampere (A), 1 A = 1 C/s.  
Measure with ammeter **in series**.

### Electromotive Force (e.m.f.)

$$ \text{e.m.f.} = \frac{W}{Q} $$
Measure with voltmeter connected directly across the source **with the circuit open** (no current). That reading equals e.m.f.

### Potential Difference (p.d.)

$$ V = \frac{W}{Q} $$
Measure with voltmeter **in parallel** across the component.

### Resistance

$$ R = \frac{V}{I} $$
Unit: ohm (Ω).

Factors affecting resistance:
- Length ↑ → Resistance ↑
- Cross‑sectional area ↑ → Resistance ↓
- Material (resistivity)
- Temperature ↑ → Metal resistance ↑

---

## 4.3 Electric Circuits

### Series vs Parallel

| Feature | Series | Parallel |
|---------|--------|----------|
| Current | Same everywhere | Total = sum of branch currents |
| Voltage | Sum of component voltages = total | Same across each branch |
| Resistance | R_total = R₁+R₂+… | 1/R_total = 1/R₁+1/R₂+… |
| Fault | One break → whole circuit off | One branch broken → others work |

### Ohm’s Law

$$ V = I \times R $$
Applies only to **fixed resistors** (ohmic conductors). Filament lamps and diodes are non‑ohmic.

### Electrical Power and Energy

$$ P = V \times I = I^2 \times R = \frac{V^2}{R} $$
Unit: watt (W).

$$ E = P \times t = V \times I \times t $$
Unit: joule (J). 1 kWh = 3.6×10⁶ J.

### Common Circuit Symbols

| Component | Symbol |
|-----------|--------|
| Cell / battery | —|∣— |
| Resistor | ─□─ |
| Variable resistor | ─□─ with arrow |
| Lamp | ○—×—○ |
| Switch | —○— or —∣— |
| Ammeter | circle with A |
| Voltmeter | circle with V |
| Diode | triangle + bar |

---

## 4.4 Digital Electronics (Supplement)

### Analogue vs Digital Signals

| Type | Characteristic | Noise immunity |
|------|----------------|----------------|
| Analogue | Continuous values | Poor |
| Digital | Only two states (0/1) | Good |

> Convention: high voltage = 1, low voltage = 0.

### Logic Gates

| Gate | Symbol shape | Truth table | Function |
|------|--------------|-------------|----------|
| NOT | triangle + small circle | 0→1, 1→0 | Inverter |
| AND | D‑shape | All 1 → 1 | Series switches |
| OR | shield (curved) | Any 1 → 1 | Parallel switches |
| NAND | AND + circle | All 1 → 0 | AND inverted |
| NOR | OR + circle | All 0 → 1 | OR inverted |

---

## 4.5 Dangers of Electricity

### Risks
- **Electric shock**: current through human body (worse when wet).
- **Fire**: excessive current overheats wires.

### Safety Devices

| Device | Function | Location |
|--------|----------|----------|
| Fuse | Melts when current too high | **Live wire** |
| RCD (residual current device) | Detects leakage and trips | Distribution board |
| Earth wire | Connects metal casing to ground | Metal‑cased appliances |
| Double insulation | No earth needed | Plastic‑cased appliances |

- Choose fuse rating slightly above normal operating current.
- Fuse must be on the **live** wire, never neutral.

---

## 4.6 Electromagnetic Effects (Supplement)

### 4.6.1 Electromagnetic Induction

**Phenomenon**: changing magnetic flux through a closed circuit induces an **induced current** (or e.m.f.).

**Demonstration experiments**:
1. Insert/remove magnet into/from a coil connected to a galvanometer – needle deflects.
2. Move a wire **vertically** (cutting magnetic field lines) between magnet poles – induced current.
3. Vary current in an electromagnet near another coil.

**Factors increasing induced e.m.f.** : faster motion, more turns, stronger magnetic field.

**Lenz’s Law**: induced current flows in a direction that opposes the change causing it.

**AC Generator**:
- Construction: rectangular coil, magnets, two slip rings, brushes.
- Operation: coil rotates, its sides cut field lines → alternating induced e.m.f. (magnitude and direction change).
- Difference from DC motor: generator uses slip rings (output AC), motor uses split‑ring commutator (to keep rotation direction).

### 4.6.2 Magnetic Effect of a Current

**Straight wire**: concentric circular field. **Right‑hand grip rule** (thumb = current, fingers = field direction).

**Solenoid**: uniform strong field inside, behaves like a bar magnet. Polarity: right‑hand grip (fingers along current, thumb = N). Strengthen by: larger current, more turns, soft‑iron core (electromagnet).

**Force on a current‑carrying wire in a magnetic field (motor effect)**:
- Force ∝ current (I), field strength (B), length of wire in field (L).
- Direction: **Fleming’s left‑hand rule** (Index finger = Field, Middle = Current, Thumb = Motion).

**DC motor**: coil experiences torque, **split‑ring commutator** reverses current every half‑turn to keep rotation direction.

### 4.6.3 Transformer

**Construction**: closed soft‑iron laminated core + primary coil + secondary coil.

**Principle**: AC in primary → alternating flux in core → induced e.m.f. in secondary. **Does not work with DC**.

**Voltage ratio**:
$$ \frac{V_p}{V_s} = \frac{n_p}{n_s} $$

**Types**:
- Step‑up: n_s > n_p
- Step‑down: n_p > n_s

**Ideal transformer power**: $$ V_p I_p = V_s I_s $$

**Core functions**: low reluctance path, lamination reduces eddy‑current losses.

---

## Common Mistakes

| Mistake | Correct understanding |
|---------|----------------------|
| Protons move during rubbing | Electrons move; protons are fixed |
| Current direction = electron flow | Current direction is conventional (positive charge) |
| Ammeter in parallel / voltmeter in series | Ammeter series, voltmeter parallel |
| Equal voltage across series components | Only current equal; voltage splits |
| Parallel total resistance > any branch | Total < each branch |
| Fuse on neutral | Fuse must be on live wire |
| Steel core for electromagnet | Use soft iron |
| Transformer with DC | Doesn't work |
| Slip rings vs commutator | Generator: slip rings (AC); motor: commutator (to keep rotation) |
| Logic gate truth tables | AND: all 1 → 1; OR: any 1 → 1; NOT: inverts |

---

> This document strictly follows the CAIE IGCSE Physics 0625 2023–2025 syllabus. Suitable for Extended candidates.
