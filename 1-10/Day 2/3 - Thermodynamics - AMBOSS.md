# Thermodynamics
## Summary

Thermodynamics (the study of heat) allows for the description of energy transformations based on a few main principles and state equations, and it enables us to make statements about whether processes and chemical reactions can occur for energetic reasons.

In addition to chemical reactions, phase transitions of the same substance can also be described thermodynamically - in the biological-medical context, this is usually water. The ideal gas model has proven effective for the gaseous phase.

## Energy and Entropy

### Energy

Thermodynamics is the technical term for "heat theory." It deals with the conversion of energy and the possibility of doing work through it. There are different types of energy.

- Definition: Form of storage of work
- Unit: J (Joule = N×m)
- Forms
    - Thermal energy: Disordered particle movement in a medium (e.g., from gas particles, see below)
    - Potential Energy: Energy that a body possesses due to its position in an energy field or due to its state (e.g. compression of a spring) (see: Mechanics)
    - Kinetic energy: The energy of motion of a body (see: Mechanics)
    - Chemical energy: Energy that is stored in chemical compounds and can be released during a chemical reaction (e.g., sugar molecules in muscle)

> [!note]
> Law of Conservation of Energy: It is possible to convert energy from one form to another and transfer it from one system to another, but within a closed system, the total energy remains constant. Energy can neither be created nor destroyed!

### Entropy

Entropy is a measure of the disorder of a system at the particle level. The greater the entropy, the greater the disorder.

Formula: ΔS = Qrev / ΔT or ΔS > Qirrev / ΔT

- Unit: J/K
- S = Entropy, Qrev = Amount of heat in a reversible (i.e., reversible) process, Qirrev = Amount of heat in an irreversible (i.e., no longer fully reversible) process, T = Temperature

> [!note]
> In a closed system (i.e., a system in which no energy is absorbed or released), the sum of all entropies can only increase!

## Main Principles of Thermodynamics

There are four main laws in thermodynamics, from which all important relationships can ultimately be derived. Once one has understood the main laws and their significance, one can essentially answer all questions of thermodynamics.

### 0. First Law of Thermodynamics

The 0th law of thermodynamics was discovered after the other three laws, but it is the most fundamental of all. It was called the "0th" law of thermodynamics so that the already existing laws would not have to be renamed. It describes systems that are in thermal equilibrium with each other, that is, systems with the same temperature:

> [!note]
> 0. Main clause: If systems A and B are in thermal equilibrium with each other, just as systems B and C are, then systems A and C are also in equilibrium with each other!

#### Heat conduction

From the 0th law of thermodynamics, it follows that between two systems that are in contact with each other but not in thermal equilibrium, heat will flow until they reach equilibrium. The thermal conductivity of the materials plays a significant role in this process.

- Temperature: Indicates on a temperature scale how "warm" something is compared to a defined "heat."
    - Temperature scales: In Europe, temperatures are typically measured in degrees Celsius (°C) in daily life, but in science, they are measured in Kelvin (K)
        - Conversion factor: T[K] = T[°C] + 273
        - The temperature scales in degrees Celsius and Kelvin run linearly and parallel to each other; they are simply shifted by 273 degrees relative to one another.

##### Thermal Conductivity

This material property indicates the amount of heat that can flow through a layer of material measuring 1×1 meter in one second with a temperature difference of one Kelvin.

Formula: Q = λ × A × ΔT / l

- Unit: W (Watt)
- Q = Heat flow, λ = Thermal conductivity (material constant), A = Cross-sectional area, ΔT = Temperature difference, l = Distance over which heat transfer occurs

### 1. and 2. Law of Thermodynamics

The 1st law of thermodynamics and the 2nd law of thermodynamics describe which processes occur (or can occur) based on energy relationships, and which do not:

> [!note]
> 1. Main clause: In a closed system, energy is constant! (This statement corresponds to the law of conservation of energy.)

> [!note]
> 1. Main principle: Thermal energy cannot be converted into other forms of energy at will! (For example, heat cannot flow from a colder object to a warmer one, even though this would not be forbidden according to the law of conservation of energy.)

To apply the two main laws to thermodynamic processes, one typically needs the following quantities:

- Internal energy: Total energy available for thermodynamic transformation processes
    - Formula: ΔU = Q + W
        - Unit: J (Joule)
        - U = Internal energy, Q = Heat, W = Work done on the system
- Specific heat capacity: A material constant that indicates how much heat a substance can store.
    - Formula: c = ΔQ / (m × ΔT)
        - Unit: J/(kg×K)
        - c = specific heat capacity, ΔQ = change in heat quantity, m = mass, ΔT = change in temperature
        - Temperature: The temperature change of a substance can be simplified calculated from this as ΔT = ΔQ/c
- Thermal energy: Can be described like any energy by power and time.
    - Formula: W = P × t
        - Unit: J (Joule)
        - W = thermal energy, P = power, t = time

#### Example Calculation

A freezing person sits next to the heater until their entire body (65 kg) has warmed up by 1°C. Assuming the body has a specific heat capacity of 3,500 J/kgK, how much heat would the person have absorbed?

- Sought: Heat quantity ΔQ
- Given: Temperature difference ΔT, specific heat capacity c, mass m
    - c = ΔQ / m × ΔT => c × m × ΔT = ΔQ
    - => 3.500 J/kgK × 65 kg × 1 K = 227.500 J

### 3. Third Law of Thermodynamics

The 3rd law deals with the movement of particles within a medium and the associated order of the particles.

> [!note]
> 3. Main principle: The absolute zero point (T = 0K, at this point there is no particle movement anymore) is unattainable!


The 3rd law of thermodynamics ultimately means that there is no absolutely error-free ordered system, because particle movement always occurs. Disorder is the natural state in all systems, and energy must always be expended to create order. A measure of disorder is entropy.
## Thermodynamics of Chemical Reactions

Chemical energy is the energy that is stored in chemical compounds (in the bonds) and can be released during chemical reactions. The amount of stored energy strongly depends on the type of interactions between the particles (for a definition of the different interactions see: Structure of Matter).

### Energy Content in Different Types of Bonds

The binding energy (sometimes also called binding enthalpy) describes how strong the forces are that hold two particles together. Depending on the type of forces, expected values for the binding energy can be given.

- Ionic bond: 50–1000 kJ/mol
- Covalent bond: 50–1000 kJ/mol
    - The binding energy correlates directly with the length of a bond: The longer the bond, the lower the binding energy.
    - Single bonds contain less energy than double bonds, and these contain less than triple bonds.
- Hydrogen bond: 1–50 kJ/mol
- Hydrophobic interactions: <20 kJ/mol

> [!note]
> The larger the binding energy, the stronger the bond!

### Absolute Energy Expenditure

In the course of chemical reactions, several bonds and interactions typically change simultaneously, which sum up to an absolute energy change.

- Enthalpy: Heat content; used in various contexts to make statements about heat (bond enthalpy) or a change in heat (reaction enthalpy, heat of fusion, heat of vaporization, etc.)
    - Formula: H = U + p × V
        - Unit: kJ/mol
        - H = Enthalpy, U = internal energy, p = pressure, V = volume
- Reaction enthalpy: ΔHReaction = HProducts - HReactants
    - ΔH < 0: Exothermic
        - HProducts < HEducates
        - Process in which heat is released
    - ΔH > 0: Endothermic
        - HProducts > HEducates
        - Process in which heat is absorbed
        - Example: Evaporation
            - During the evaporation of liquid on the skin, the wetted area becomes cold because the skin transfers thermal energy to the liquid molecules, allowing them to transition into the gas phase. The necessary heat of vaporization can be calculated using the following formula: Specific heat of vaporization Qs (or the enthalpy of condensation) = Thermal energy W / Mass of the quantity to be vaporized m.
- Gibbs energy: It is used like enthalpy, but additionally takes into account the entropy of a system.
    - Formula: ΔG = ΔH – T × ΔS
        - Unit: kJ/mol
        - G = Gibbs energy (also free reaction enthalpy), H = enthalpy, T = temperature, S = entropy
        - ΔG < 0: Exergonic
            - Process that occurs "voluntarily"
            - Process that releases energy
            - Example: ATP → ADP + P => ΔG = -30 kJ/mol
        - ΔG > 0: Endergonic
            - Process that does not occur "voluntarily"
            - Process that absorbs energy
        - ΔG = 0: Equilibrium state
- Hess's law: The enthalpy change of a reaction is the sum of the enthalpy changes of all the subprocesses of the reaction.
    - Consequence: The enthalpy change of a reaction is not dependent on the reaction pathway.
    - Application example: Born-Haber cycle process
        - The formation of NaCl from the elements Na and Cl can be written as follows:
            - Sublimation of Na
            - Dissociation of Cl2
            - Ionization of Na → Na+
            - Electron deposition of Cl → Cl-
            - Formation of the salt girders
        - For the energy, it follows: Lattice energy ) = (Standard formation enthalpy) – (Sublimation energy Na) – (Dissociation energy Cl2) – (Ionization energy Na → Na+) – (Electron affinity Cl → Cl-)
        - Since all values except for the lattice energy can be measured, it can now be calculated: Lattice energy = -410 kJ/mol - 108 kJ/mol - 122 kJ/mol - 496 kJ/mol - (-349 kJ/mol) = (-787 kJ/mol)
- Free reaction enthalpy: Depends on the products and reactants of a reaction and can therefore be determined from their equilibrium constant using the law of mass action (see also: Chemical reactions).
    - Formula: ΔG = -R × T × ln(k)
        - Unit: kJ/mol
        - G = Gibbs energy (also free reaction enthalpy), R = gas constant, T = temperature, k = equilibrium constant of the reaction
    - Free reaction enthalpy for redox reactions: It strongly depends on the existing charges and is described by the Nernst equation.
        - Formula: ΔG = -z × F × ΔE0
            - Unit: kJ/mol
            - G = Gibbs energy (also known as free reaction enthalpy), z = number of transferred electrons, F = Faraday constant, ΔE0 = difference in standard potentials of the half-reactions
            - For a detailed explanation see: Redox reactions

#### Example Calculation - Gibbs Energy

A chemical reaction occurs at a temperature of 25°C and has a standard entropy S0 = 2 kJ/(molK). The products have an enthalpy of 400 kJ/mol, while the reactants have an enthalpy of 200 kJ/mol. Can the reaction proceed spontaneously?

- Sought: Gibbs energy ΔG
- Given: Enthalpies HEducts, HProducts, Reaction Entropy ΔS
    - ΔHReaction = HProducts - HReactants => ΔHReaction = 400 kJ/mol - 200 kJ/mol = 200 kJ/mol
    - ΔG = ΔH - T × ΔS => ΔG = 200 kJ/mol - 298 K × 2 kJ/(molK) = -396 kJ/mol
    - ΔG < 0 => the reaction occurs spontaneously

#### Sample Calculation - Chemical Equilibrium

A reaction is at chemical equilibrium at 25°C. The equilibrium constant of the reaction is 5 × 10-9 mol2/L2. Determine the Gibbs energy of this reaction.

- Sought: Gibbs energy ΔG
- Given: Temperature T, Equilibrium constant k
    - ΔG = - R × T × ln(k) => ΔG = -8.314 J/molK × 298 K × ln(5 × 10^-9) = -47.356 kJ/mol

#### Example Calculation - Electrochemical Reaction

An electrochemical reaction 2 Na + Cu2+ → 2 Na+ + Cu takes place. The standard potentials of the two half-cells are E0Na = -2.7 V and E0Cu = +0.4 V. What is the Gibbs energy of the reaction?

- Sought: Gibbs energy ΔG
- Given: Standard potential of the half-reactions E, reaction equation
    - 2 Na → 2 Na+ + 2 e- and Cu2+ + 2e- → Cu
    - ΔG = -z × F × ΔE0 => ΔG = -2 × 96485 C/mol × 3.1 V = -598.2 kJ/mol

### Energy Profile of Chemical Reactions

The energy changes during a reaction can also be represented graphically. A diagram where the reaction progress is plotted on the x-axis and the energy G on the y-axis is called the "energy profile" of a reaction. From this, the following facts can be deduced:

- Reaction Types
    - Overall reaction spontaneous: Products are at a lower energy than reactants.
    - Overall reaction involuntarily: Products are at a higher energy level than reactants.
- Activation energy: Energy that must be supplied for the reaction to begin.
- Intermediate states / Transition states: Short-lived molecular states (e.g., charged adducts or molecules where individual atoms exceed or fall below their normal valency) that arise during a reaction but are not stable and therefore typically cannot be isolated because they quickly decay or rearrange.
    - Appearance in the energy profile: Local minima on the curve
    - Stability of Intermediate Stages
        - The lower the energy, the more stable.
        - The higher the activation energies for the transformation, the more stable; that is, the step with the highest activation energy is rate-determining.
    - Alternative reaction pathways: If various reaction pathways are available, the reaction preferentially proceeds through the intermediates that have the lowest energy.

|Reaction Type|Definition|Energy Profile|
|---|---|---|
|Exergonic|ΔG < 0||
|Endergonic|ΔG > 0||

### Catalysis

Catalysis serves in chemical reactions to open an alternative reaction pathway. This can be useful when a reaction is energetically favorable but still kinetically hindered (meaning it proceeds at an almost infinitely slow rate).

- Catalyst: A substance that is added to the reactants in a catalytic reaction and enables an alternative reaction pathway.
    - Special features:
        - Reaction rate increases and equilibrium state of the reaction is reached faster – however, the position of the chemical equilibrium is not(!) changed.
        - Since the catalyst is not consumed in a reaction like a reactant, it can be added in very small amounts.
    - Heterogeneous catalyst: Exists in a different phase than the reaction mixture – typically, the catalyst is a solid and the reaction mixture is a liquid.
    - Homogeneous Catalyst: Exists in the same phase as the reaction mixture – typically, the catalyst and reactants are liquid or dissolved in a liquid.
    - Enzymatic Catalysis: The catalyst is an enzyme.
        - Special feature: Highly substrate-specific and stereoselective (see: Biocatalysis)
- Energetic principle: Catalysts reduce the activation energy of a reaction, allowing it to proceed under appropriate reaction conditions.
- Molecular principle: Catalysts interact with a reactant and form an energetically favorable adduct, which serves as a transition state for an alternative reaction pathway.

> [!note]
> Catalysts are not consumed during a reaction; instead, they emerge unchanged from the reaction and bind again to a reactant molecule. This process occurs repeatedly until there are no more reactant molecules present in the reaction mixture!

## States of Matter and Phase Transitions

In physics and chemistry, a "phase" refers to a spatial section of a material structure in which the physical and chemical properties are homogeneous (i.e., the same everywhere). The three main phases are the three so-called states of matter: solid, liquid, and gas.

### The States of Matter

When comparing the matter particles in the three states of aggregation, it becomes clear what distinguishes them: Essentially, these are the order, mobility, and distance of the particles. The larger a molecule and the stronger the intermolecular forces, the higher the melting and boiling point of the substance.

|State of aggregation|Solid|Liquid|Gaseous|
|---|---|---|---|
|Particle Motion|- Weak|- Medium|- Strong|
|Distance between the particles|- Small|- Medium|- Large|
|Order of Particles|- Order present in the immediate vicinity and also global order<br>- Degree of order correlates with the strength of the attractive forces between the particles|- Order present in the immediate vicinity (so-called short-range order), no global order|- No order present|

### Phase Transitions

Since the same matter can exist in different phases, there are also transformations between phases. Such a process is called a phase transition:

- Melting: Transition solid → liquid
    - Freezing: transition liquid → solid
- Evaporation: Transition from liquid → gaseous
    - Condensation: Transition from gas to liquid
- Sublimation: Transition from solid → gas
    - Resublimation: Transition from gas to solid

#### Phase Diagrams

In which phase a substance exists depends on the external parameters of pressure and temperature: Everyone has observed that water evaporates when it gets sufficiently hot, or that the flammable liquid in a lighter escapes as gas when the pressure is released. Therefore, one can accurately determine in which phase a substance exists in a so-called phase diagram, where temperature and pressure are plotted.

##### Phase Diagram

- X-Axis: Temperature T
- Y-Axis: Pressure p
    - The scientific unit of pressure is Pa (Pascal)!
        - 1 atm = 1.013 bar = 1.013 × 10^5 Pa
- Areas between the lines: Phases
    - Fixed phase: T = small, p = varies from low to high
    - Gaseous phase: T = high, p = varies from low to high
    - Liquid phase: between the other two phases, T = medium, p = medium
- Lines: Phase Transitions
    - Melting curve: Line between solid and liquid phase
    - Siedekurve: Line between liquid and gaseous phase
    - Sublimation curve: Line between solid and gaseous phase
- Special Points
    - Triple point
        - Intersection of the three phase boundaries
        - Here, all three phases are in equilibrium.
    - Critical point
        - Endpoint of the boiling curve
        - Beyond this point, one can no longer distinguish between the liquid and gaseous phases.
    - Boiling point
        - Temperature value of the boiling curve at normal pressure (1.013 bar = 1.013 × 10^5 Pa)
    - Melting point
        - Melting curve temperature value at normal pressure (1.013 bar = 1.013 × 10^5 Pa)

> [!note]
> The phase diagram of water shows the peculiarity that the melting curve tilts towards lower temperatures at high pressures. This results in the density anomaly of water, namely that ice has a lower density than water and therefore floats on the surface of the water! The density anomaly of water is caused by the strong intermolecular interactions between water molecules.

#### Special Influences (Colligative Properties)

Phase transitions can be influenced by external factors. For water, these phenomena, which are also referred to as colligative properties, are partly known from everyday life and therefore play an important role. Below, all colligative properties of water are presented, except for osmotic pressure (see: Fundamentals of Cell Communication/Osmotic Pressure).

- Melting point depression
    - External factors: By dissolving salts
    - Reason: Increase of entropy in the liquid phase
    - Result: The melting point decreases at a given pressure.
    - Everyday example: sprinkling salt on ice
- Boiling point elevation
    - External factors: By dissolving salts
    - Reason: Increase in entropy in the liquid phase
    - Result: The boiling point rises at a given pressure.
    - Everyday example: Salt water boils at higher temperatures than pure water
- Decreased steam pressure
    - External factors: By dissolving salts
    - Reason: The evenly dissolved substance displaces water molecules from the surface, thus reducing the number of water molecules that evaporate at a given temperature.
    - Consequence: The saturation vapor pressure at a given temperature decreases.

## Gas

Gas as a state of matter has already been described in the section "Phases and Phase Transitions" as a state where particles move quickly and completely freely, thus being completely disordered. With the help of a few assumptions for an idealized model, many more statements about gases can be made.

### Ideal Gas

The ideal gas is a pure model concept. There is no real gas that behaves like an ideal gas. Nevertheless, many statements can be made approximately using the ideal gas:

- Particles are mass points without their own volume.
- There are no interactions between the particles.
- Properties
    - Avogadro's law: Equal volumes of an ideal gas contain the same number of particles at the same pressure and temperature.
    - Gay-Lussac's Law: At constant pressure, the volume expands linearly with temperature.
    - Boyle-Mariotte Law: At constant temperature, the volume decreases as pressure increases.
- General gas equation: Summarizes the three relationships above and mathematically describes the properties of ideal gases.
    - Formula: p × V = n × R × T
        - p = Pressure, V = Volume, n = Amount of substance, R = Gas constant, T = Temperature
        - The gas constant is R = 8.314 J/(mol×K)
        - The official unit of pressure is Pa = Pascal; however, old units are also still used.
            - 1 Torr = 133 Pa
            - 1 bar ≈ 100,000 Pa = 1,000 cmH2O ≈ 760 mmHg
        - The standard air pressure is 1 bar = 101 kPa = 1.013 hPa
        - Under standard conditions, 1 mole of gas particles has a volume of 22.4 L
    - Simplified formula: p1 × V1 = p2 × V2
        - For cases where the amount of substance (n) and the temperature (T) of the gas do not change, the product of volume and pressure of two states can be equated.

> [!note] Diving
> In water, the ambient pressure increases by about 1 bar (= 100 kPa) for every 10 m of water depth. This leads, according to Boyle's Law, to a decreasing lung volume (p × V = constant) at constant temperature. Another consequence of the increasing ambient pressure is the physical dissolution of an increasing amount of gas, regardless of which gas it is. This can lead to a high concentration of nitrogen when scuba diving and to the so-called deep-sea narcosis, which is associated with severe cognitive impairments and euphoria. Additionally, a rapid ascent can result in decompression sickness (gas embolism due to the outgassing of previously dissolved gas in tissues and vessels). This occurs when the ambient pressure decreases so quickly during ascent that the large amount of dissolved gas cannot be reduced by exhalation but instead transitions abruptly into the gaseous state. Therefore, when diving deeper than 10 m, it is essential to pay attention to a slow ascent.

#### Example Calculation 1 - Standard Conditions

What is the volume of 1 mole of an ideal gas at standard conditions?
	Standard conditions are defined as T = 273.15 K; p = 1.013 × 10^5 Pa
- Sought: Volume V
- Given: Amount of substance n, Temperature T, Pressure p
    - Formula: (p × V) = (n × R × T) => V = (n × R × T) / p
    - => V = (1 mol × 8.314 J/mol×K × 273.15 K) / 1.013 × 10^5 Pa = 0.0224 m³ ≈ 22L

#### Example Calculation 2 - Pressure Change

A diver inhales a volume of 3 L from a gas tank at a depth of 50 m underwater. If he then ascends immediately without equalizing pressure, how much does the air expand at atmospheric pressure? (It is assumed that air behaves as an ideal gas and that the temperature at 50 m depth is the same as the temperature at the water's surface. Pressure increases by 1 bar for every 10 m of diving depth.)

- Sought: Volume VWater surface
- Given: Volume V50m; Pressure pWaterSurface, p50m; R = Gas constant
    - Formula: (p × V) = (n × R × T); during the ascent, the total number of particles remains constant and the temperature also remains constant.
    - pWater surface = 1 bar; therefore p50m = 6 bar
    - => p50m × V50m = pWaterSurface × VWaterSurface
    - => p50m = 6 × 1 bar = 6 bar
    - => Water surface = (p50m × V50m) / pWater surface = (6 bar × 3 L) / 1 bar = 18 L
    - Since the total capacity of the human lung is about 7 liters in volume, in this case, the diver's lung tissue would tear.

> [!note]
> The higher the temperature and the lower the pressure, the more real gases resemble ideal gases!

### Particle Velocity in Gas

The particles in a gas can move completely freely and without a specific direction. This so-called "Brownian motion" is a real phenomenon and not part of the model of an ideal gas. The speed of particle movement depends mainly on 2 factors:

- Mass: The larger the mass of a gas particle, the lower the speed.
- Temperature: The higher the temperature, the higher the speed of the gas particles.

However, not all particles in the gas have the same speed! The speeds of the gas particles can best be described by a distribution curve.

- Average speed: v = √(8 × R × T / π × M)
    - Unit: m/s
    - v = average speed, R = gas constant, T = temperature, M = molar mass
- Average kinetic energy: Ekin = ½ × m × v2 = 3/2 × kb × T
    - Unit: J (Joule)
    - Ekin = kinetic energy, m = mass, v = average speed, T = temperature, kb = Boltzmann constant (gas constant R / Avogadro's number NA = 1.38 × 10−23 J/K)

> [!note]
> From the velocity distribution, it follows that there are always very fast and very slow particles in a phase. The fast particles can transition into the gas phase at untypically low temperatures (that's why laundry dries on the balcony even at temperatures well below 100°C) and the slow particles can condense at high temperatures. This is therefore a phase equilibrium!

### Partial Pressure

Gases often occur in mixtures, as is the case with the air that surrounds us. The total air pressure is thus composed of the "partial pressures" of the individual gases. The partial pressure is defined as the pressure that a gas would exert if it were alone in the considered volume.

- Dalton's Law: The total pressure p_total of a gas mixture is equal to the sum of the partial pressures.
- Formula: ptotal = p1 + p2 + p3 + … = ((ptotal × V1)/Vtotal) + ((ptotal × V2)/Vtotal) + ((ptotal × V3)/Vtotal) + ...
    - Unit: Pa
    - ptotal = pressure of the gas mixture, p1, p2, p3 ... = partial pressures of components 1, 2, 3 …
    - The following applies to the partial pressure pi: pi = (ptotal × Vi)/Vtotal
- Example air
    - Main components: Consists of about 78% nitrogen, 21% oxygen, 1% argon, and 0.04% CO2
    - Air pressure: approx. 1 bar (≈ 100 kPa ≈ 760 mmHg) at sea level
    - Atmospheric O2 partial pressure 760 mmHg × 21% ≈ 160 mmHg

#### Example Calculation

What is the partial pressure of nitrogen in air?
- Sought: Partial pressure p
- Given: total pressure p, molar fraction
    - => Air consists of 78% nitrogen
    - => Our atmosphere has a pressure of 1 bar
    - pN2 = 78% × 1 bar = 0.78 bar

#### Gases and Liquids

Gases can also be present dissolved in liquids. Their concentration then also depends on the partial pressure. This is especially relevant medically for gas transport in the blood. At the same time, water molecules can also be part of a gas mixture in the gaseous state. This is particularly important in the context of breathing air (see humidity, BTPS, and STPD).

### Humidity

The humidity is a measure of how many water molecules are present in the gaseous state in the air mixture.

Humidity:

- Absolute: f = mWater vapor / V
    - Unit: g/m3
    - f = humidity, mWaterVapor = mass of water vapor, V = volume
- Maximal: pWater vapor = pSaturation
    - Unit: g/m3
    - pVapor = Partial pressure of water vapor in the air, pSaturation = Saturation vapor pressure of water at a given temperature
- Relative: frel = pWater vapor / pSaturation
    - Unit: %
    - frel = relative humidity, pWasserdampf = partial pressure of water vapor in the air, pSättigung = saturation vapor pressure of water at a given temperature

#### BTPS and STPD

In medicine, the values BTPS (body temperature, pressure, saturated) are often used for conditions in the body and STPD (standard temperature, pressure, dry) for room air. In this context, the following applies:

- BTPS: T = 310.15 K (= 37 °C)
    - Partial pressure of water vapor: pH2O = 6.25 kPa (= saturation vapor pressure at 37 °C)
- STPD: T = 273.15 K (= 0 °C)
    - Total air pressure: pges = 101kPa
    - Water vapor partial pressure: pH2O = 0 kPa

> [!note]
> If it is assumed that the amount of substance and pressure remain constant, then according to the ideal gas law (see above), volume and temperature are related to each other as follows: V(STPD)/V(BTPS) = T(STPD)/T(BTPS)!

> [!note]
> For invoices with BTPS and STPD, the international standard unit for temperature (Kelvin) must be used: 0 °C = 273 K!

##### Example Calculation

Under standard conditions (BTPS), the saturation vapor pressure of water is 6.25 kPa at 37 °C. This corresponds to the conditions in the lungs. What is the difference in water content between the inhaled and exhaled air, if the inhaled outside air has a temperature of 15 °C (where the saturation vapor pressure is 1.7 kPa) and a humidity of 20%?

- Sought: Δair humidity
- Given: Temperatures T1 and T2, saturation vapor pressures p15 and p37, relative humidity frel
    - frel = pVapor / pSaturation => pVapor = frel × pSaturation
    - => pVaporPressure= 20% × 1.7 kPa = 0.34 kPa
    - ΔpLuftfeuchtigkeit= 6,25 kPa - 0,34 kPa = 5,91 kPa

## Review Questions on the Chapter Thermodynamics
### Main Principles of Thermodynamics

Explain how the temperature scales in degrees Celsius [°C] and Kelvin [K] relate to each other, what distinguishes them, and what their respective advantages are.
- One degree on the Celsius scale is the same size as one degree on the Kelvin scale; only the reference points of the two scales are shifted relative to each other: 0 °C corresponds to the temperature at which water freezes, while 0 K corresponds to the temperature at absolute zero (only theoretically attainable). Therefore, 0 °C equals 273.15 K. The advantage of the Celsius scale is that it is based on reference points observable in nature. The advantage of the Kelvin scale is that there is no negative temperature range and at zero there is no more particle motion (ultimately an equivalent of temperature).

What is heat and with which scientific quantities can it be described?
- Heat is the energy stored in a system in the form of particle motion. It can be described using various scientific quantities. The amount of heat Q describes a specific measure of heat. The so-called internal energy U is the total energy available for thermal transformations. It thus includes, besides the actual heat, the work done by a system. Often, the so-called specific heat capacity c is used, indicating how much heat a substance can store – it is therefore a material constant. The specific heat capacity is the quotient of heat and the product of mass and temperature change (c = ΔQ / m × ΔT). Another important quantity is the so-called enthalpy H, which corresponds to the heat content of a substance and is calculated as the sum of internal energy and the product of pressure and volume (H = U + p × V).

### Thermodynamics of Chemical Reactions

What is the difference between the statements: "The reaction is exothermic (endothermic)" and "The reaction is exergonic (endergonic)"?
- The terms "exothermic" and "endothermic" refer to whether a reaction releases heat (ΔH<0) or absorbs heat (ΔH>0) during its course. The terms "exergonic" and "endergonic" also take into account the order of the reactants and products of a reaction besides the heat balance. An exergonic reaction proceeds spontaneously, whereas an endergonic reaction does not.

What is Gibbs energy and how can it be calculated? Which part of the formula is based on the 2nd law and which on the 3rd law of thermodynamics?
- Gibbs energy G describes the heat content and the order state of a system. It is calculated as the difference between enthalpy and the product of entropy and temperature (ΔG = ΔH - T × ΔS). The enthalpy part of the equation is derived from the 2nd law of thermodynamics, which states that heat energy cannot be converted arbitrarily into other forms of energy. The entropy part of the equation is derived from the 3rd law of thermodynamics, which states that at absolute zero no particle motion occurs.

What is a catalyst and how does it work?
- A catalyst is a substance added to the reactants of a reaction that enables an alternative reaction pathway, thereby lowering the activation energy of a reaction. This allows a reaction to proceed under conditions (pressure, temperature) where it would normally not occur or occur negligibly slowly. The catalyst itself does not participate in the reaction and is therefore not consumed.

Why do damp compresses have a soothing effect when having a fever?
- The water contained in the compresses evaporates more due to the increased temperature (liquid water turns into gaseous water). Since gaseous water has a higher energy content than liquid water (faster particle motion), it must absorb energy from its surroundings during evaporation, resulting in a cooling effect known as evaporative cooling.

### States of Aggregation and Phase Transitions

What are the three biologically relevant states of matter and how do they differ at the molecular level?
- The three biologically relevant states of aggregation are: solid, liquid, and gas. They differ in how densely packed and thus freely movable the molecules of the aggregate are. In solids, the particles are packed most densely, can move the least, and therefore have the highest order. In gases, the particles are farthest apart and move the most. Consequently, the order in gases is minimal.

Name all phase transitions you know and explain how they are characterized.
- Melting is the transition from solid to liquid, solidification is the reverse process. Both are characterized by the melting temperature. Boiling is the transition from liquid to gas, condensation refers to the reverse transition from gas to liquid. Both transformations occur at the so-called boiling temperature. Sublimation is the direct transition from solid to gas, and deposition (resublimation) is the reverse process. In both cases, the so-called sublimation temperature is used for characterization.

On which molecular properties does the height of the boiling temperature of a liquid depend? Why is the disinfectant isopropanol for example volatile, but water is not?
- In the solid and liquid state, the particles composing a substance come very close and can form interactions. For example, water molecules form so-called hydrogen bonds due to the high polarity of the molecule, which hold the molecules together. When a substance transitions into a state where the particles are farther apart (e.g., during boiling), all existing attractive forces must be overcome to separate the particles. The stronger the interactions, the more energy is needed and the higher the required boiling temperature. Isopropanol is significantly less polar than water and therefore forms much weaker interactions in the liquid state. Hence, the boiling temperature of isopropanol is lower than that of water.

### Gases

What is meant by an ideal gas?
- The ideal gas is actually just a model system, but it is sufficiently accurate that many considerations in the natural sciences are made based on the ideal gas. A gas would be ideal if it consisted of particles with mass but no volume (= mass points) and if no interactions occurred between the individual particles.

What three statements are used to describe gases, and what formula ultimately results from them?
- The three statements used to describe gases are Avogadro's law ("If pressure and temperature of a gas remain constant, the same number of particles are always present in the same volume"), Gay-Lussac's law ("At constant pressure, volume expands linearly with temperature") and Boyle-Mariotte's law ("At constant temperature, volume decreases with increasing pressure"). From these arises the formula for the ideal gas (also called gas law), which reads: pV = nRT, where R = gas constant = 8.314 J/(mol×K), p = pressure, T = temperature in K, and n = amount of substance.

What is the volume of one mole of gas at standard conditions?
- Under standard conditions, 1 mole of gas has a volume of 22.4 L.

With which simplified formula can one calculate how the volume of a gas changes with pressure?
- The ideal gas law states: p × V = n × R × T. Therefore, for two gases or two states of a gas with the same amount of substance and at the same temperature, p1 × V1 = p2 × V2. The equation can be rearranged arbitrarily to solve for pressure or volume.

How does the ambient pressure change when diving?
- At sea level the atmospheric pressure is 1 bar. When diving, the ambient pressure increases by about 1 bar every 10 meters.

What is meant by partial pressure and how is it calculated?
- Partial pressure refers to the partial pressure of a gas within a gas mixture. The partial pressure corresponds to the pressure that the gas would exert if it alone occupied the volume of the gas mixture. The total pressure of a gas mixture is the sum of all partial pressures; a partial pressure is therefore calculated from the total pressure minus all other partial pressures.

Name the four main components of air. In what ratio do they exist?
- The four most important gases in air are nitrogen N2 (78%), oxygen O2 (21%), argon Ar (1%), and carbon dioxide CO2 (0.04%).

What is humidity and how is its relative value calculated?
- Humidity indicates how many gaseous (!) water molecules are present in the air mixture. Relative humidity is given as a percentage. To calculate it, the actual water vapor pressure is divided by the saturation vapor pressure, i.e., the actual partial pressure of the water divided by the maximum possible water vapor pressure.

In medicine, the values BTPS and STPD are used. What conditions do each of them refer to?
- BTPS conditions (from Body Temperature, Pressure, Saturated) always refer to a temperature of 310.15 K (= 37 °C, i.e., body temperature), where the water vapor partial pressure corresponds to the saturation vapor pressure (= 6.25 kPa). STPD conditions (from Standard Temperature, Pressure, Dry) refer to a temperature of 273.15 K (= 0 °C) and an air pressure of 101 kPa, with water vapor partial pressure of 0.
### Open Questions about the Chapter on Thermodynamics

What do the three main laws of thermodynamics state?

What is binding energy?

Describe the energy profiles a) of a chemical reaction with activation energy, b) of a chemical reaction with an intermediate, and c) of a catalyzed chemical reaction.

Beschreibe und erkläre das Phasendiagramm von Wasser.

Describe what a gas is. Use formulas as well.
