# IGCSE Physics 0625 – Topic 5: Nuclear Physics
- 这份笔记由 LG-leo 整理和维护。如果你觉得这份笔记对你有帮助，欢迎在 GitHub 上关注我或给我一个 ⭐，这能帮助我持续产出更多免费的学习资源。
- 我的其他课程笔记：https://github.com/LG-leo?tab=repositories
- This note is maintained by LG-leo. If you find it helpful, feel free to follow me or leave a ⭐ on GitHub. It helps me keep producing more free study resources. Check out my other notes: https://github.com/LG-leo?tab=repositories

## Important Notes

This document follows the **CAIE 0625 Syllabus for 2026, 2027 and 2028** (version 2, published December 2025) point by point, and adds exam keywords and common traps based on Paper 2 and Paper 4 questions.

Points to note compared with older resources:

- **β⁺ (positron) is not included**: "β" means the β⁻ particle (electron).
- **No antineutrino** is required: write β⁻ decay as `n → p + e⁻`.
- **No numerical `E = mc²` calculations**: fission and fusion are examined qualitatively ("mass decreases → energy released").
- **No `intensity ∝ 1/r²` requirement**: safety only requires "increase distance"; the inverse-square relationship is for understanding only.
- Detection only requires **count rate**, not "activity" calculations.

Sources:

- [CAIE 0625 Syllabus 2026–2028 (official PDF)](https://www.cambridgeinternational.org/Images/697209-2026-2028-syllabus.pdf)
- [xtremepape.rs](https://papers.xtremepape.rs/) – past paper index
- [Save My Exams](https://www.savemyexams.com/igcse/physics/cie/23/) – topic-wise questions and answers
- [IITian Academy](https://www.iitianacademy.com/igcse-physics/) – topic-wise questions

---

## Part 1: Syllabus Structure

| No. | Content | Chinese | Tier |
|-----|---------|---------|------|
| 5.1 | The nuclear model of the atom | 原子的核模型 | — |
| 5.1.1 | The atom | 原子 | Core + Supplement |
| 5.1.2 | The nucleus | 原子核 | Core + Supplement |
| 5.2 | Radioactivity | 放射性 | — |
| 5.2.1 | Detection of radioactivity | 放射性的探测 | Core + Supplement |
| 5.2.2 | The three types of nuclear emission | 三种核辐射 | Core + Supplement |
| 5.2.3 | Radioactive decay | 放射性衰变 | Core + Supplement |
| 5.2.4 | Half-life | 半衰期 | Core + Supplement |
| 5.2.5 | Safety precautions | 安全防护 | Core + Supplement |

> Memory hook: **atomic structure (5.1) → radioactivity and decay (5.2) → half-life and applications (5.2.4) → safety (5.2.5)**.

---

## Part 2: Knowledge Points

### 5.1 The Nuclear Model of the Atom

#### 5.1.1 The Atom (Core + Supplement)

**Core**
- An atom consists of a **positively charged nucleus** surrounded by **negatively charged electrons** in orbit.
- **Ion formation**:
  - an atom that **loses electrons** becomes a **positive ion**;
  - an atom that **gains electrons** becomes a **negative ion**.

**Supplement: alpha-particle scattering experiment**
- A beam of alpha particles is directed at a **very thin sheet of metal** (e.g. gold foil); a detector/fluorescent screen records the scattered particles.
- Observations:
  - **most alpha particles pass straight through**;
  - **a few** are deflected through large angles;
  - **very few** bounce back.
- Conclusions (three pieces of evidence):
  1. the atom is **mostly empty space** (most pass straight through);
  2. the nucleus is **very small** but contains **most of the mass** (very few bounce back);
  3. the nucleus is **positively charged** (alpha particles are repelled).

**Common traps**
- "Most pass straight through" shows the atom is mostly empty space, not that the nucleus is positive.
- "Very few bounce back" shows the nucleus is small, massive and positive – do not just say "a nucleus exists".
- Alpha scattering is **Supplement**; Core only requires the structure of the atom.

#### 5.1.2 The Nucleus (Core + Supplement)

**Core**
- The nucleus contains **protons** and **neutrons**.
- Relative charges: proton **+1**, neutron **0**, electron **−1**.
- **Proton number Z (atomic number)**: number of protons; determines the element.
- **Nucleon number A (mass number)**: protons + neutrons.
  - number of neutrons `N = A − Z`.
- **Nuclide notation**: `^A_Z X`.
  - Examples: `^12_6 C` (carbon-12), `^235_92 U` (uranium-235).
- **Isotopes**: atoms of the same element with the **same number of protons but different numbers of neutrons**; an element may have more than one isotope.

**Supplement**
- **Nuclear fission**: a heavy nucleus **splits** into two smaller nuclei, releasing energy (and neutrons).
- **Nuclear fusion**: light nuclei **join** to form a heavier nucleus, releasing energy.
- Both can be represented by **nuclide equations**, which must conserve **A** and **Z**.
- Qualitative mass–energy change: the total mass after the reaction is slightly **less**, and the lost mass is released as energy (no numerical calculation required).
- Relationships:
  - relative charge on the nucleus = **+Z**;
  - relative mass of the nucleus ≈ **A**.

**Common traps**
- Isotopes have the same **proton number** but different **neutron number**, not the same mass number.
- Fission = heavy nucleus splitting; fusion = light nuclei joining.
- Balance both A and Z in nuclear equations.
- A is the number of nucleons, not the mass in kg.

---

### 5.2 Radioactivity

#### 5.2.1 Detection of Radioactivity (Core + Supplement)

**Core**
- **Background radiation**: ionising radiation that is always present in the environment.
- Main sources:
  1. **radon gas** (from rocks and soil);
  2. **rocks and buildings**;
  3. **food and drink**;
  4. **cosmic rays**.
- Ionising radiation can be measured using a **detector (e.g. GM tube) connected to a counter**.
- **Count rate**: counts per unit time, in **counts/s** or **counts/min**.

**Supplement**
- **Corrected count rate = measured count rate − background count rate**.

**Common traps**
- Always **subtract the background** when measuring a source.
- Count rate fluctuates randomly; a single reading is not enough.
- Background radiation is natural, not an instrument fault.

#### 5.2.2 The Three Types of Nuclear Emission (Core + Supplement)

**Core**
- Nuclear emission is **spontaneous** and **random** in direction.
- The three emissions:

| Type | Nature | Charge | Ionising power | Penetrating power |
|---|---|---|---|---|
| **α** | helium nucleus `^4_2 He` (2 protons + 2 neutrons) | +2 | **strongest** | **weakest** (paper / a few cm of air) |
| **β⁻** | fast electron `^0_-1 e` | −1 | medium | medium (a few mm of aluminium) |
| **γ** | high-frequency electromagnetic radiation / photon | 0 | **weakest** | **strongest** (thick lead/concrete) |

> Syllabus note: **β⁺ is not included**; "β" refers to the β⁻ particle.

**Supplement**
- **Deflection in an electric field**:
  - α (positive) → towards the **negative plate**;
  - β (negative) → towards the **positive plate**;
  - γ (uncharged) → **not deflected**.
- **Deflection in a magnetic field**:
  - use Fleming's left-hand rule for a positive charge; α and β are deflected in **opposite** directions;
  - γ is uncharged → no deflection.
- **Why ionising powers differ** (in terms of kinetic energy and charge):
  - α: charge +2, large mass, relatively slow → dense ionisation → **strongest**;
  - β: charge −1, small mass, fast → weaker ionisation;
  - γ: uncharged and highly penetrating → **weakest** ionisation.

**Common traps**
- **Ionising power and penetrating power are usually opposite**: α is most ionising but least penetrating; γ is the reverse.
- γ is uncharged, so it is **not deflected** by electric or magnetic fields.
- α is easily stopped by paper externally, but is dangerous if **inhaled or swallowed**.
- β particles are electrons, but they come from the **nucleus**, not from the electron shells.

#### 5.2.3 Radioactive Decay (Core + Supplement)

**Core**
- **Radioactive decay**: an unstable nucleus spontaneously emits α particles, β particles and/or γ radiation, becoming more stable; the process is **spontaneous** and **random**.
- After **α or β decay**, the nucleus changes into that of a **different element**.

**Supplement**
- An isotope may be radioactive because it has **too many neutrons** and/or a **nucleus that is too heavy**.
- **Alpha decay**: emits `^4_2 He`.
  - `^A_Z X → ^(A−4)_(Z−2) Y + ^4_2 He`
  - **A decreases by 4; Z decreases by 2.**
- **Beta-minus decay**: a neutron in the nucleus changes into a proton and an electron:
  - `n → p + e⁻`
  - `^A_Z X → ^A_(Z+1) Y + ^0_-1 e`
  - **A is unchanged; Z increases by 1.**
- **Gamma emission**: usually follows α/β decay as the nucleus drops from an excited state to a lower energy state:
  - **A and Z are unchanged.**
- Use nuclide notation to write decay equations; **A and Z must be conserved**.
- Effect on the nucleus: **α decay** reduces the number of nucleons; **β⁻ decay** changes a neutron into a proton and reduces the number of excess neutrons; **γ emission** lets the nucleus drop from an excited state to a lower energy state. All three make the nucleus **more stable**.

**Common traps**
- The β electron comes from a **neutron changing into a proton** in the nucleus, not from an orbiting electron.
- Gamma emission alone does **not** change the element (A and Z unchanged).
- In alpha decay, Z decreases by 2, not 4 (A decreases by 4).
- Balance A first, then Z, when writing equations.

#### 5.2.4 Half-life (Core + Supplement)

**Core**
- **Half-life**: the time taken for **half the nuclei** of a particular isotope in any sample to decay.
- After n half-lives:
  - fraction remaining = **(1/2)^n**;
  - the count rate falls by the same factor (after subtracting background).
- Half-life can be found from **tables or decay curves**; Core calculations do **not** include background.

**Supplement**
- Calculate half-life from data or decay curves **from which background radiation has not been subtracted** (deal with the background first).
- The **type of radiation** and the **half-life** determine which isotope is used:
  - **household smoke alarms**: α source with a long half-life (e.g. americium-241);
  - **irradiating food to kill bacteria**: γ;
  - **sterilising equipment**: γ;
  - **measuring and controlling thickness**: choose the radiation according to **penetration and absorption** (β is often used for thin materials);
  - **diagnosis and treatment of cancer**: γ.

**Common traps**
- Half-life is a **statistical** property of a large number of nuclei; it does not mean every nucleus decays exactly at time T.
- After 2 half-lives, **1/4** remains, not 1/2.
- Subtract the background **before** calculating with count rates.
- Half-life is a property of the nucleus and is **not affected** by temperature, pressure or chemical state.

#### 5.2.5 Safety Precautions (Core + Supplement)

**Core**
- Effects of ionising radiation on living things:
  - **cell death**;
  - **mutations**;
  - **cancer**.
  - Fetuses and rapidly dividing cells are more sensitive.
- Safe handling:
  - store and transport in **shielded containers** (e.g. lead);
  - use **remote handling tools** (long tongs, manipulators);
  - store and dispose of radioactive waste safely;
  - wear a **dosimeter** to monitor the accumulated dose.

**Supplement**
- Three principles of radiation protection:
  1. **reduce exposure time**;
  2. **increase distance** from the source;
  3. **use shielding**:
     - α: paper or gloves (most importantly, prevent inhalation/ingestion);
     - β: a few mm of aluminium or perspex;
     - γ: thick lead or concrete.

**Common traps**
- α is not very dangerous externally, but is most dangerous if **inhaled or swallowed**.
- γ is the most penetrating; thin paper is useless – use **thick lead/concrete**.
- The greater the distance, the smaller the dose (for a point source, approximately `∝ 1/r²`, understanding only).
- Match the shielding to the radiation: paper for α, aluminium for β, lead for γ.

---

## Part 2.5: Intuitive understanding (for memory, not examined)

- **Alpha scattering = firing at a hidden target blindfolded**: most balls pass straight through → mostly empty space; a few bounce off → a small, hard target; very few come straight back → the target is massive and has the same (positive) charge, so it repels the alpha particle. Hence: atom mostly empty, nucleus small and heavy, nucleus positive.
- **Nuclide notation = an address**: in `^A_Z X`, the lower Z is the "building number" (element/proton number) and the upper A is the "room number" (total nucleons). Same building (same Z) with different rooms (different A) = isotopes.
- **Fission vs fusion = taking apart vs joining Lego**: fission splits a very large nucleus into two medium ones; fusion joins two light nuclei into a heavier one. Both make the system more stable and turn the "missing mass" into energy.
- **α/β/γ = bowling ball, bullet, light**: α is heavy, slow and highly charged, so it interacts strongly and loses energy quickly → strong ionisation, short range; β is light, fast and singly charged → medium; γ is uncharged, like light, and rarely interacts → most penetrating, weakest ionisation. The key idea: **the more strongly it interacts with matter, the shorter its range.**
- **Random decay = rolling dice**: each nucleus has a certain probability of decaying at any moment; you cannot predict which one or when. With very many nuclei, the statistical pattern is stable → half-life.
- **Half-life = halving**: 800 → 400 → 200 → 100; after n half-lives, `(1/2)^n` remains. It is not "the lifetime of every nucleus is T".
- **Background radiation = background noise**: measure the "noise" without the source, then subtract it → corrected count rate.
- **Protection = less sun, more distance, an umbrella**: reduce time, increase distance, use shielding; paper for α, aluminium for β, lead for γ.
- **Deflection = positive and negative charges go opposite ways**: α is positive, β is negative → in an electric field they go to opposite plates; γ is uncharged → undeflected.
- **Mass defect = a little mass "disappears"**: after fission/fusion the total mass is slightly smaller, and the missing mass becomes energy (`E = mc²`); 0625 only requires the qualitative statement "mass decreases, energy is released" – no calculation.

---

## Part 3: Equations and Relationships

| Quantity | Relationship | Notes |
|---|---|---|
| Nucleon number | `A = Z + N` | N = number of neutrons |
| Alpha decay | `A − 4`, `Z − 2` | emits `^4_2 He` |
| Beta-minus decay | `A` unchanged, `Z + 1` | `n → p + e⁻` |
| Gamma emission | `A`, `Z` unchanged | emits a photon |
| Half-life | remaining `(1/2)^n` | n = number of half-lives |
| Corrected count rate | measured − background | counts/s or counts/min |
| Nuclear charge | relative charge `+Z` | nucleus is positive |
| Nuclear mass | relative mass ≈ `A` | nucleon number approximates mass |

Decay examples:

- α: `^238_92 U → ^234_90 Th + ^4_2 He`
- β⁻: `^14_6 C → ^14_7 N + ^0_-1 e`
- γ: `^60_27 Co* → ^60_27 Co + γ` (* = excited state)

---

## Part 4: Common Traps

| Wrong statement | Correct understanding |
|---|---|
| Most alpha particles passing straight through shows the nucleus is positive | It shows the atom is **mostly empty space**; deflection/rebound shows the positive, massive nucleus |
| Isotopes have the same mass number | Same **proton number**, different **neutron number** |
| Fission is light nuclei joining | Fission is a **heavy nucleus splitting**; fusion is light nuclei joining |
| Alpha is weakly ionising but highly penetrating | Alpha is the **most ionising, least penetrating** |
| Gamma is deflected in an electric field | Gamma is **uncharged**, so it is not deflected |
| Beta particles come from orbiting electrons | They come from a **neutron changing into a proton** in the nucleus |
| Gamma emission changes the element | Gamma leaves **A and Z unchanged** |
| After 2 half-lives, half remains | **One quarter** remains: `(1/2)² = 1/4` |
| Heating a sample changes its half-life | Half-life is a nuclear property, **unaffected** by external conditions |
| Count rate can be used without subtracting background | Always **subtract the background** |
| Alpha is most dangerous externally | Alpha is easily stopped by paper; it is dangerous if **inhaled/swallowed** |
| Paper shields gamma | Gamma needs **thick lead/concrete** |

---

## Part 5: Paper 4 Answer Templates

- **Alpha scattering**: Most alpha particles passed straight through, showing that the atom is mostly empty space. A few were deflected and very few bounced back, showing that the mass and positive charge are concentrated in a very small nucleus.
- **Ion formation**: An atom becomes a positive ion by losing electrons and a negative ion by gaining electrons.
- **Isotopes**: Isotopes are atoms of the same element with the same number of protons but different numbers of neutrons.
- **Fission/fusion**: Nuclear fission is the splitting of a heavy nucleus into lighter nuclei, releasing energy. Nuclear fusion is the joining of light nuclei to form a heavier nucleus, releasing energy.
- **Background radiation**: Background radiation is ionising radiation present in the environment from natural sources such as radon, rocks and buildings, food and drink, and cosmic rays.
- **Corrected count rate**: Corrected count rate = measured count rate − background count rate.
- **Three emissions**: Alpha particles are helium nuclei, beta particles are fast electrons, and gamma radiation is electromagnetic radiation. Alpha is the most ionising and least penetrating; gamma is the least ionising and most penetrating.
- **Electric field deflection**: Alpha particles are deflected towards the negative plate, beta particles towards the positive plate, and gamma radiation is not deflected.
- **Alpha decay**: In alpha decay, the nucleon number decreases by 4 and the proton number decreases by 2.
- **Beta decay**: In beta decay, a neutron in the nucleus changes into a proton and an electron; the nucleon number is unchanged and the proton number increases by 1.
- **Half-life**: The half-life is the time taken for half the nuclei of a radioactive isotope in a sample to decay. After n half-lives, the fraction remaining is `(1/2)^n`.
- **Safety**: Reduce exposure time, increase the distance from the source, and use appropriate shielding (paper for alpha, aluminium for beta, thick lead for gamma).

---

## Part 6: Keyword Glossary

| Keyword | Definition |
|---|---|
| **Atom** | the smallest neutral unit of an element, made of a nucleus and orbiting electrons |
| **Nucleus** | the positively charged centre of an atom, containing protons and neutrons |
| **Proton** | relative charge +1, relative mass 1 |
| **Neutron** | no charge, relative mass 1 |
| **Electron** | relative charge −1, very small mass |
| **Ion** | an atom that has lost or gained electrons |
| **Proton number Z** | number of protons; determines the element |
| **Nucleon number A** | number of protons + neutrons |
| **Nuclide notation** | `^A_Z X` |
| **Isotope** | same proton number, different neutron number |
| **Alpha particle** | helium nucleus `^4_2 He` |
| **Beta particle** | fast electron `^0_-1 e` |
| **Gamma radiation** | high-frequency electromagnetic radiation / photon |
| **Ionising** | removing electrons from atoms to form ions |
| **Penetrating power** | ability to pass through matter |
| **Background radiation** | ionising radiation naturally present in the environment |
| **Count rate** | counts per unit time (counts/s or counts/min) |
| **Corrected count rate** | measured count rate − background count rate |
| **Spontaneous** | happening without external trigger |
| **Random** | impossible to predict which nucleus decays or when |
| **Radioactive decay** | unstable nucleus emits radiation and becomes more stable |
| **Half-life** | time for half the nuclei in a sample to decay |
| **Fission** | splitting of a heavy nucleus |
| **Fusion** | joining of light nuclei |
| **Mutation** | change in genetic material caused by radiation |
| **Shielding** | material used to absorb radiation |
| **Dosimeter** | device that monitors accumulated radiation dose |

---

## Part 7: Final Self-check

1. Can you describe the structure of the atom and how ions form?
2. Can you link the three observations of alpha scattering to the three conclusions?
3. Do you know the relative charges of protons, neutrons and electrons, and how to calculate Z, A and N?
4. Can you write nuclide notation and define isotopes?
5. Can you distinguish fission and fusion and balance nuclear equations?
6. Do you know the four sources of background radiation and how to calculate a corrected count rate?
7. Can you compare α, β and γ in nature, charge, ionising power and penetrating power?
8. Can you describe their deflection in electric and magnetic fields?
9. Can you write decay equations for α, β and γ and state the changes in A and Z?
10. Can you define half-life, use `(1/2)^n`, and find half-life from a curve?
11. Can you choose an isotope for smoke alarms, food irradiation, sterilisation, thickness control and cancer treatment?
12. Can you explain the effects of radiation on living things and the three safety principles (time, distance, shielding)?
