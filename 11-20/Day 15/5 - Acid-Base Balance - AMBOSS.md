# Acid-Base Balance
## Summary

The body fluids are constantly exposed to fluctuating concentrations of proton-releasing acids and proton-accepting bases. The proton content of a solution is indicated by the pH value. Many biochemical processes in the body require pH constancy. Fluctuations in pH lead to denaturation and loss of function of proteins and must therefore be compensated by an interplay of buffer systems dissolved in the blood, lungs, and kidneys. In cases of decompensation of the mechanisms, such as with poorly controlled diabetes mellitus, acidosis can occur due to the excess acidity in the blood. Conversely, an excessive loss of protons, such as through hyperventilation, can lead to alkalosis of the blood.
## Chemical Fundamentals

Many inorganic as well as organic substances react either "acidic" or "basic." There are several definitions for this property of substances, of which the one according to Brønsted will be presented here. The Lewis definition will be covered in the chapter on redox chemistry.

### Acid-Base Definition according to Brønsted

- Acid: Proton donor (from Latin donare = "to give")
    - Ex. HCl (= hydrochloric acid): HCl + H2O ⇄ Cl− + H3O+
- Base: Proton acceptor (from Latin accipere = "to accept")
    - Example: C5H5N (= Pyridine): C5H5N + H2O ⇄ C5H6N+ + OH−
- Corresponding acid-base pairs: When an acid donates a proton, it automatically becomes a base and can now accept protons - this is referred to as a conjugate base. The conjugate base and the original acid form a corresponding acid-base pair.
    - Ex. HCl (= hydrochloric acid): HCl [acid] + H2O [base] ⇄ Cl− [conjugate base of HCl] + H3O+ [conjugate acid of H2O]
- Ampholyte: Compounds that can act as proton donors or proton acceptors depending on the prevailing pH level.
    - Ex. Water: H2O + H2O ⇄ H3O+ + OH-
        - E.g. amino acids, see also: acid-base properties of amino acids

### Acidity and Basicity

Not all acids and bases react equally strongly: They can be divided into strong and weak acids or bases. This division is relevant, among other things, in pH value calculations and the composition of buffers.

- Acid strength: The strength of an acid is defined by the completeness of its proton donation (= dissociation).
    - Measure: Equilibrium constant KS of the law of mass action for the deprotonation reaction of the acid
        - Calculation (e.g. for hydrochloric acid): KS = ([H3O+] × [Cl−]) / [HCl]
        - KS >1: Strong Acid
        - KS <1: Weak Acid
        - pKS value: Negative decimal logarithm of the KS value
            - The larger the KS value, the smaller the pKS value, and the stronger the acid.
            - Example: HCl (hydrochloric acid) has a negative pKa value of −6, making it a stronger acid than H3PO4 (phosphoric acid, pKa = 2)
    - Acid strength of carboxylic acids: The acid strength of a carboxylic acid increases when a strongly electronegative substituent is attached to the carbonyl carbon atom, which helps to stabilize the negative charge of the acid anion. An example of this is trichloroacetic acid.
- Base strength: The strength of a base is defined by the completeness of its proton uptake (= protonation).
    - Measure: Equilibrium constant KB of the law of mass action for the protonation of the base
        - Calculation (e.g. for ammonia): KB = (OH−] × [NH4+]) / [[NH3]
        - KB > 1: Strong Base
        - KB < 1: Weak Base
        - pKB value: Negative decimal logarithm of the KB value
            - Example: OH− (hydroxide ion) has a negative pKB value of −2, making it a stronger base than NH3 (ammonia, pKB = 5)

> [!NOTE]
> The larger the Ks or the smaller/negative the pKS, the stronger an acid is – the larger the KB or the smaller/negative the pKB, the stronger a base is!

## pH Value

- Definition: The pH value is the negative decimal logarithm of the H3O+ concentration in a solution. It is a dimensionless quantity and is therefore expressed without a corresponding unit.
- Formula: pH = −lg[H3O+]
    - Example: In pure water, the concentration of hydronium ions is 10−7mol/L. From this, the pH value of 7 is derived using the negative decimal logarithm.
- pH scale: 0 (strongly acidic) – 7 (neutral) – 14 (strongly basic)
- Interpretation: The pH value indicates whether a solution is acidic or basic.

> [!NOTE]
> When an acid is added to a solution, it becomes acidic (the acid transfers its protons to H2O molecules, thus there are more H3O+ ions than OH− ions present)!

> [!NOTE]
> When a base is added to a solution, it becomes basic (the base receives protons from H2O molecules, thus there are more OH− ions than H3O+ ions present)!

### pH Value Calculation

Depending on the strength of an acid or base, different formulas are used to calculate the pH value. Concentration values will be abbreviated as c [in mmol/L] in the following.

- Strong acids
    - Examples: Hydrochloric acid (HCl), Sulfuric acid (H2SO4), Nitric acid (HNO3), Perchloric acid (HClO4), Trichloroacetic acid (Cl3CCOOH)
    - pH formula: pH = −lg([Acid] × Valence)
    - Example calculation: What is the pH of a 0.05 molar HCl solution?
        - pH = −lg (0.05 × 1)
        - pH ≈ 1.3
- Weak acids
    - Examples: Carbonic acid (H2CO3), Citric acid (C6H8O7), Acetic acid (CH3COOH), Ammonium ion (NH4+), Phosphate anions (H2PO4−, HPO42−), Propionic acid (CH3CH2COOH)
    - pH formula: pH = ½ (pKa – log[acid])
    - Example calculation: What is the pH value of a 0.1 molar acetic acid solution (pKS = 4.8)?
        - pH = ½ (4.8 – lg(0.1))
        - pH = ½ (4.8 + 1) = 2.9
- Strong Bases
    - Example: Hydroxide ion (OH−) as found in potassium hydroxide (KOH) and sodium hydroxide (NaOH)
    - pOH formula: –log ([Base] × valence)
    - pH formula: pH = 14 – pOH = 14 + log ([Base] × valence)
    - Example calculation: What is the pH of a 0.01-molar potassium hydroxide solution (KOH)?
        - pH = 14 + lg (0.01 × 1)
        - pH = 14 + (−2) = 12
- Weak bases
    - Examples: Ammonia (NH3), Amines
    - pH formula: pH = 14 − ½ (pKB − log[Base])
    - Example calculation: What is the pH value of a 0.1 molar ammonia solution (pKB = 4.75)?
        - pH = 14 – ½ (4.75 – lg(0.1))
        - pH = 14 – ½ (4.75 + 1) = 14 – 2.88 = 11.12

### Autoprotolysis and the pH Value of Water

Since water is an ampholyte, one H2O molecule can transfer a proton to a second H2O molecule. One water molecule acts as an acid while the other acts as a base. This process is also known as the autoprotolysis of water.

- Definition
    - Protonation: A chemical reaction in which a proton (H+) is transferred from one reactant to another (proton transfer reaction)
    - Autoprotolysis of water: One H2O molecule transfers a proton (H+) to a second H2O molecule.
- Reaction equation: H2O + H2O ⇄ H3O+ + OH-
    - From the law of mass action for this equation, the so-called ion product of water (KW) can be calculated.
        - It reflects the ratio of OH– and H3O+ ions in highly diluted solutions.
        - KW= (H3O+] × [OH−]) = 10−7 [mol/L × 10−7 mol/L = 10−14 mol2/L2
    - In pure water, the number of OH– and H3O+ ions is equal, both having a concentration of 10−7 mol/L (1 L of water contains about 55 mol of water molecules)
    - The ion product of water can be used to calculate the pK values of a corresponding acid-base pair: pKW = pKS + pKB = 14

The following table illustrates the relationship between the excess of either hydronium or hydroxide ions in a solution and the pH value:

| Relationship between the concentration of hydronium and hydroxide ions and the pH value |                                                                                            |                                                                                            |                                                                                   |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| Type of solution                                                                                                                                                                                                                                          | H3O+]                                                                                     | [OH−]                                                                                      | [pH |
| Water                                                                                                                                                                                                                                                   | 10−7 mol/L  | 10−7 mol/L  | 7                                                                                 |
| Sour solution                                                                                                                                                              | >10−7 mol/L | <10−7 mol/L | <7                                                                                |
| Basic solution                                                                                                                                                           | <10−7 mol/L | >10−7 mol/L | >7                                                                                |

### Neutralization and the pH value of salt solutions

- Neutralization: Reaction of equal amounts of acid (H+-equivalents) and base (OH−-equivalents) with each other, resulting in a pH of 7 (neutral).
    - Products: Water and salt
    - Example: HCl + KOH ⇄ H2O + KCl

> [!NOTE]
> When salts are dissolved in water, the pH value of the resulting solution is not always neutral (pH = 7), but depends on the strength of the acids and bases of the ions!

| pH Value Calculation of Various Salt Solutions |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ---------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Reaction partner                                                                                                             | Weak acid                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Strong acid                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Weak Base                                   | - Results in nearly neutral salt solution<br>    - Formula: pH = (pKS1 + pKS2) / 2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | - Results in weakly acidic salt solution<br>    - Formula: pH = ½ (pKS – lg[Acid]) (corresponds to the pH formula for a weak acid)<br>    - Example: An ammonium chloride solution (NH4Cl) reacts weakly acidic (ammonium chloride is formed from the weak base NH3 and the strong acid HCl) |
| Strong Base                                   | - Results in a weakly basic salt solution<br>    - Formula: pH = 14 − ½ (pKB – lg[Base]) (corresponds to the pH formula for weak bases) | - Results in a neutral salt solution<br>    - pH value is not changed                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |

###### Calculation example (sodium acetate):

In the reaction of NaOH (= strong base) with acetic acid (= weak acid), sodium acetate (= a weakly basic salt) is formed. Therefore, the pH value is calculated using the formula for weak bases:

- Given are: Concentration of sodium acetate = 0.1 mol/L and pKB (acetate) = 9.25
- Substituting into the formula (pH = 14 – ½ (pKB – log[Base]))
- The following is: pH = 14 – ½ (9.25 – lg 0.1) = 14 – ½ (9.25 + 1) = 14 – 5.125 = 8.875 (weakly basic pH value)

### Titration

Titration is a procedure for the experimental determination of an unknown amount of acid or base in a solution: For this, exact amounts of a base or acid are added, and the change in pH value is measured using an indicator.

- Definition: There are two different forms of titration.
    - Acidimetry: Addition of a known amount of acid to an unknown amount of base
        - Function: Calculation of the base quantity
    - Alkalimetry: Addition of a known amount of base to an unknown amount of acid
        - Function: Calculation of the amount of acid
- Implementation
    1. A suitable indicator is selected.
    2. A vessel containing the acid (or base) to be examined has the titrant added drop by drop.
    3. The color change indicates the attainment of the equivalence point.
- Titration curve
    - Creation
        - y-axis: After each addition of a drop of the titrant, the pH value is measured and recorded on the y-axis.
        - x-axis: The amount of titration agent that has already been consumed is recorded on the x-axis.
    - Special turning points
        - Equivalence point
            - Definition: Here, identical (= equivalent) amounts of an acid (or a base) and titrant are present in the solution.
            - Function: The equivalence point allows for the calculation of the required amount of acid (or base).
            - Determination: Color change of the indicator, identifiable in the titration curve as a point with a significant pH jump (inflection point in the nearly vertical region)
            - pH value: Depends on the strength of the acid and base
                - In the titration of a weak acid with a strong base, the equivalence point lies in the basic range.
                - In the titration of a weak acid with a weak base or a strong acid with a strong base, the equivalence point is at a neutral pH value of 7.
        - Half-equivalence point
            - Definition: When titrating weak acids or bases, at this point half of the respective acid or base is neutralized.
            - Determination: Half-equivalence point readable at half the titration volume of the equivalence point
            - pH: For weak acids or bases, the pH value at the half-equivalence point corresponds to the pKa or pKb value of the acid or base.
        - Neutral point
            - Definition: The neutral pH value is reached here.
            - Function: The neutral point indicates the amount of titrant consumed until a neutral pH value is reached.
            - Determination: pH measurement
            - pH value: 7
## Puffer

Buffer substances stabilize the pH level of liquids. The body makes use of this in the form of endogenous buffers (e.g., bicarbonate buffer) to keep the pH level of the blood largely constant.

- Definition: Aqueous solution of weak(!) corresponding acid-base pairs (e.g., acetic acid/acetate; ammonium/ammonia)
    - The mixture of acid and base can absorb small changes in pH. So, if you add some acid or base to a buffer solution, the pH initially does not change.
- pH value calculation of a buffer solution
    - Henderson-Hasselbalch equation: pH = pKa + log(cB / cS)
        - pKS = negative decimal logarithm of the acid's equilibrium constant, cB = concentration of the base = [Base], cS = concentration of the corresponding acid = [Acid]
    - Example: Acetic acid (HAc)/Acetate (Ac-)-buffer
        - Given
            - pKS(HAc) = 4.7
            - [HAc] = 1 mmol/L
            - [Ac−] = 1.3 mmol/L
        - Puffer system: HAc + H2O ⇄ Ac− + H3O+
        - Calculation
            - pH = pKS + lg([Ac−]/[HAc])
            - It follows: pH = 4.7 + lg(1.3 mmol/L / 1 mmol/L)
            - ⇔ pH = 4.7 + lg(1.3) = 4.7 + 0.11 ≈ 4.8
- Buffer capacity: Corresponds to the amount of an acid or base required to change the pH of 1 L of buffer solution by ±1.
- pH-Optimum (Buffer): pH value at which the buffer solution reaches its maximum buffering capacity; occurs when equal amounts of acid and base are present in the mixture, in this case, pH = pKa also applies.
## Physiological pH Values and Their Fluctuations

Function and survival of an organism are dependent on the condition of a constant pH value. The reason for this is mainly the pH-sensitive spatial structure of proteins. The term "acid-base balance" refers to the totality of regulatory mechanisms that are intended to prevent or compensate for deviations from the desired pH value.

### pH Norm Values in the Body

The secretions and compartments of the body are sorted in the following list according to increasing pH value.

| pH Normal Values in the Body |                                                                                               |
| ----------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Secret / Compartment                                                                                 | pH Normal Range |
| Gastric juice          | 1.0–4.0                                                                                       |
| Vaginal secret                                                                                     | 4.0–5.0                                                                                       |
| Sweat                 | 4.5                                                                                           |
| Urine                                                                                                | 4.5–7.9                                                                                       |
| Skin                   | 4.1–5.8                                                                                       |
| Saliva                | 5.5–7.8                                                                                       |
| Galle                  | 6.5–8.2                                                                                       |
| Chair                                                                                                 | 7.0                                                                                           |
| Cytoplasm              | 7.0–7.3                                                                                       |
| Blood plasma           | 7.35–7.45                                                                                     |
| Sperm                  | 7.2–8.0                                                                                       |
| Cervical mucus                                                                                       | 7.0–8.5                                                                                       |

> [!NOTE]
> A decreased arterial blood pH value (pH <7.35) is referred to as acidosis, while an increased arterial blood pH value (pH >7.45) is referred to as alkalosis.

### Influences on the pH Level in the Body

There are various physiological causes for fluctuations in the pH level in the body, for example, volatile acid CO2 is produced in the citric acid cycle among others. The formation and excretion of acidic and basic metabolic products can be maintained in balance by different regulatory mechanisms.

| Influences on the pH Level in the Body |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |                                                                                                                                                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                                                                                                                    | Acids                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Bases                                                                                                                                                     |
| Increase in Concentration                                                                                                  | - Nutrition<br>    - Metabolism of carbohydrates, fats, and amino acids to CO2 (CO2 = "volatile" acid)<br>    - Breakdown of sulfur-containing amino acids (e.g., methionine) from protein-rich diet to SO42− and H+ (fixed acids)<br>- Food deprivation<br>- Heavy physical labor | - Vegetarian diet with a high soybean content                                                                                                                       |
| Decrease in concentration                                                                                              | - Exhalation of CO2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | - Neutralization of acidic gastric and intestinal secretions<br>- Synthesis of urea |
## Regulation of Acid-Base Balance through Buffer Systems

To ensure the constancy of the pH value in the body, the body has several permanently active regulatory systems, which can be divided into the buffer solutions of body fluids and the organ-related systems. Humans have several buffer systems that compensate for acute pH fluctuations in the blood and maintain its pH value consistently around 7.4. 99.99% of all suddenly occurring protons are captured by the buffer systems.

### Open Buffer Systems

Open buffer systems are characterized by the ability to remove a reaction partner from the system (e.g., through the lungs or the kidneys), thereby increasing the buffer capacity. The two most important open buffer systems in humans are the bicarbonate and ammonium buffer systems.

#### Bicarbonate buffering system

The bicarbonate buffer is the most important buffering system in humans. It acts as an open buffering system in the excretion of acidic valences through the lungs by exhaling CO2. With 20-28 mmol/L, the bicarbonate buffer system accounts for about 50% of the total buffering capacity of the blood.

- Buffer system: H2O + CO2 ⇄ H2CO3 (≈ HCO3− + H+)
- Example
    - Given
        - pKS(H2CO3) = 6.1
        - [HCO3−] = 24 mmol/L
        - [CO2] = 1.2 mmol/L
    - Puffer system: CO2 + H2O ⇄ H2CO3 (≅ HCO3− + H+)
    - Calculation
        - pH = pKS + lg([Base]/[Acid])
        - It follows: pH = pKa + log([HCO3−]/[[CO2])
        - pH = 6.1 + lg(24 mmol/L / 1.2 mmol/L)
        - pH = 6.1 + lg(20) = 6.1 + 1.3 = 7.4
- Properties during concentration change
    - If the concentration of the corresponding base HCO3− increases, then the pH value increases.
    - If the concentration of CO2, which acts as a weak acid, increases, the pH value decreases.
- Function: Buffering of the blood pH value through dissolved CO2 in the blood
    - Excess of acids: HCO3− increasingly absorbs protons and is exhaled as CO2.
    - Excess of bases: Dissolved CO2 converts to its deprotonated form (HCO3−) through H2CO3, resulting in less CO2 being exhaled.
    - Increased CO2 partial pressure in the blood: The total concentration of buffer bases remains constant.

> [!NOTE]
> Effectiveness of the buffer: Increases in alkalosis (pH↑) and decreases in acidosis (pH↓)

#### Ammonium buffer system

The ammonium buffer system is an important regulatory system for renal acid-base excretion, allowing for the excretion of acidic substances in small amounts, but in a continuous manner. Additionally, the system is involved in renal gluconeogenesis, the de novo synthesis of bicarbonate, and the regulation of intracellular pH.

- Reaction: NH3 + H+ ⇄ NH4+
- Function
    - Enables H+ excretion via urine in the form of NH4+
    - HCO3−-sparing method of NH3 excretion

### Closed Buffer Systems

Closed buffer systems have a lower buffer capacity than open buffer systems. They are characterized by the fact that the sum of the concentrations of acid and conjugate base remains constant.

#### Protein puffersystem

Proteins in the blood can act as buffers through ionizable side groups. The hemoglobin of erythrocytes and albumin play the largest role due to their high concentration.

- Reaction: H+-uptake via reactive groups of the amino acids (see also: acid-base properties of the amino acids)
    - Basic imidazole ring of histidine: The imidazole ring of histidine has a pKa value of 6.0, which is close to the physiological pH range, making histidine particularly important for the buffering function of plasma proteins.
    - Amino and carboxyl groups of all amino acids
- Function: Regulation of blood pH value (provides 50% of the total buffering capacity of the blood)
- Main representative
    - Albumin
    - Hemoglobin: Deoxygenated hemoglobin (= Hb) has a lower acidity than oxygenated Hb → Deoxy-Hb tends to absorb H+ more readily than Oxy-Hb at the same pH level.
        - This also explains the relationship between pH value and the Hb-oxygen binding curve: pH↓ → Promotes deoxy-Hb → Right shift; pH↑ → Promotes oxy-Hb → Left shift.

#### Phosphate Buffer System

The phosphate buffer system is important for the regulation of both the intracellular pH of all body cells and the urine pH.

- Reaction: PO43− + 3 H+ ⇄ HPO42− + 2 H+ ⇄ H2PO4− + H+ ⇄ H3PO4
    - Henderson-Hasselbalch equation
        - pH = pKS + lg ([Base] / [Acid])
        - pH = 6.8 + log ([HPO42−] / [H2PO4−])
- Function
    - Regulation of intracellular pH value
    - Regulation of urine pH value in the form of HPO42– and H2PO4– (see proton secretion in the chapter on tubular transport processes)

## Regulation of Acid-Base Balance in the Organs

The body's buffer systems can only compensate for pH shifts in the short term and to a limited extent. Without the intact function of the lungs and kidneys, the acid-base balance breaks down and life-threatening conditions can occur.

### The Role of the Lungs in pH Regulation

The task of the lungs within the acid-base balance is to exhale the "volatile acid" CO2, which is constantly produced in the body as a byproduct of energy metabolism. Only when the arterial CO2 partial pressure is kept constant does the blood pH value remain unchanged.

- Mechanism: Elimination of the volatile acid CO2 through exhaled air
    - CO2-producing reactions in the body
        - Physiological: Metabolism → Oxidation of C-atoms from carbohydrates, fats, and proteins/amino acids → CO2
        - Pathological: In compensation for metabolic acidoses through the bicarbonate buffer system → HCO3− + H+ ⇄ H2O + CO2
    - Balance: Elimination of an average of 16,000 mmol CO2 per day
- Regulation
    - CO2 respiratory drive: increase in blood pCO2 → stimulation of respiration
    - pH-Respiratory Drive: pH decrease in the blood → Stimulation of breathing
    - Mechanoreceptors: The degree of physical activity is measured in skeletal muscles/joints.
        - High activity associated with increased occurrence of CO2 → Stimulation of respiration

> [!NOTE]
> Hyperventilation leads to an increase in pH (alkalosis) by exhaling the weak acid CO2, while in hypoventilation, more CO2 remains in the body, resulting in a decrease in pH (acidosis)!

### The Role of the Kidneys in pH Regulation

The kidneys regulate the pH level through two mechanisms: On one hand, they excrete excess H+-ions mostly in the form of NH4+ and HPO42−. On the other hand, they maintain the HCO3− concentration in the blood by reabsorbing it from the urine and performing HCO3− de novo synthesis. If interested, also see proton secretion and bicarbonate reabsorption.

- Elimination of acidic valences
    - Proton secretion: Via the Na+/H+ antiporter in the proximal tubule and a H+-ATPase as well as H+/K+-ATPase of the intercalated cells in the late distal tubule and collecting duct.
        - Buffering in urine through binding to ammonia and phosphate
    - Regulation
        - In acidosis: The excretion of NH4+ and PO43− increases due to increased ammonia production in the kidney (glutaminase activity↑) and reduced phosphate reabsorption in the proximal tubule.
            - Enzyme induction: Chronic acidosis → Renal glutaminase and glutamate dehydrogenase are expressed more strongly.
- Production and reabsorption of basic valences
    - HCO3– De novo synthesis of the kidney: By converting one molecule of glutamine to one molecule of α-ketoglutarate (see NH4+ excretion, process), the body gains two molecules of HCO3–
    - HCO3–-Reabsorption: Indirect reabsorption in the proximal tubule through conversion to CO2 with proton consumption
        - Regulation
            - In acidosis: HCO3− is reabsorbed to almost 100%
            - In alkalosis: HCO3− reabsorption↓ and stimulation of the Cl−/HCO3− exchanger

### The Role of the Liver in pH Regulation

The role of the liver in pH regulation is directly linked to its NH3 detoxification function. The liver has two methods of NH3 detoxification: through the urea cycle and through glutamine synthesis. Under normal circumstances, 95% of the produced NH3 is metabolized in the urea cycle and 5% through glutamine synthesis. In the case of blood pH deviation, for example, glutamine synthesis can be increased while the urea cycle is inhibited to conserve HCO3−.

- Mechanisms of ammonia detoxification
    - Urea cycle
        - Process: From one molecule of NH3, one molecule of HCO3−, and the amino group of an aspartate, urea is synthesized in five reactions.
        - Significance for the organism: Main mechanism of NH3 detoxification (= toxic breakdown product of amino acid metabolism)
        - Influence on acid-base balance: Requires the base HCO3−
    - Glutamine synthesis
        - Process: The synthesis of the amino acid glutamine from the precursor glutamate incorporating NH3 is one method of NH3 detoxification without consuming HCO3-.
            1. In the liver: Glutamate + NH3 → Glutamine (Enzyme: Glutamine synthetase)
            2. Glutamine reaches the kidneys through the blood.
            3. In the kidneys: Separation of NH3 from glutamine → NH3 + H+ are excreted in the form of the acid NH4+, without consuming HCO3− (for the exact process in the kidneys see proton secretion)
        - Influence on acid-base balance: Does not require HCO3− → Mechanism of base conservation in acidosis
- Regulation of ammonia detoxification in case of pH deviation
    - Acidosis: Decreased urea synthesis and increased glutamine synthesis
        - Urea synthesis is reduced to save HCO3− (e.g., for buffering blood pH),
        - In the liver, glutamine is increasingly produced and released into the blood to the kidney → NH3 is excreted renally in the form of the acid NH4+.
    - Alkalosis: Increased urea synthesis and decreased glutamine synthesis
        - Urea synthesis is increased as HCO3− is sufficiently available → NH3 is more frequently excreted in the form of urea.
        - Glutamine synthetase is inhibited, resulting in less glutamine reaching the kidney → Renal NH4+-excretion decreases
## Disturbances of Acid-Base Balance

pH deviations alter the spatial structure of proteins, which in turn regulate many bodily functions. In cases of pH disturbances, a distinction is made between a decrease in arterial pH value <7.35 (= acidosis) or an increase in pH value >7.45 (= alkalosis).

### Consequences of pH Deviation

Most effects of a pH shift occur due to the influence on enzymes or ion-selective transmembrane channels.

| Effects of a pH deviation on the organism |                                                                                                                                 |                                                       |                               |                                         |                                                             |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | ----------------------------- | --------------------------------------- | ----------------------------------------------------------- |
| pH deviation                              | Metabolism                                                                                                                      | Electrolytes                                          |                               | Blood circulation                       | O2 affinity of hemoglobin                                   |
| Potassium                                 | Other                                                                                                                           |                                                       |                               |                                         |                                                             |
| Acidosis                                  | - Glycolysis: Inhibited<br>- Hexosemonophosphate pathway: Stimulated<br>- DNA synthesis/cell division: Inhibited                | - Hyperkalemia (known as redistribution hyperkalemia) | - Inhibition of Na+-K+-ATPase | - Vasodilation increases blood flow     | - Decreases (= Right shift of the oxygen binding curve)     |
| Alkalosis                                 | - Glycolysis: Is stimulated<br>- Lactate synthesis: Is stimulated (see anaerobic glycolysis)<br>- Gluconeogenesis: Is inhibited | - Hypokalemia                                         | - Hypocalcemia                | - Vasoconstriction decreases blood flow | - Increased (= Left shift of the oxygen dissociation curve) |

> [!NOTE]
> A blood pH level of <6.8 or >7.8 is typically not compatible with life!

### Respiratory and metabolic disorders

For a pH disturbance, usually only one of the two regulatory systems is responsible: the lungs (respiratory disturbance) or the metabolism (metabolic disturbance). The intact system then tries to compensate for the pH deviation.

#### Characterization of Disorders in Acid-Base Balance

The clinical characterization of a pH disorder includes statements about the direction of H+ deviation, its trigger, and its course.

- According to the type of pH deviation
    - Acidosis: pH <7.35
    - Alkalosis: pH >7.45
- After trigger
    - Respiratory: The cause is a ventilation disorder.
        - Representative parameter: paCO2 (= CO2 partial pressure in arterial blood)
    - Metabolic: The cause is a metabolic disorder.
        - Representative parameters: Standard-HCO3− and Base Excess (= BE = Base surplus)
- After course
    - Acute: pH value changed, pCO2 or standard HCO3− changed
    - Partially compensated: pH value changed, pCO2 and standard HCO3− changed
    - Compensated: pH value normal, pCO2 and standard HCO3− altered

> [!NOTE]
> In compensation, the other still intact system counteracts the pH deviation, so that both the parameters for the respiratory and metabolic systems are altered: For example, in the case of metabolic acidosis, there would be a respiratory compensation in the form of hyperventilation!

#### Parameters and Causes of Disturbances in Acid-Base Balance

Based on triggers (respiratory or metabolic) and the course of compensation, five types of disorders are distinguished. All the diagnostic parameters listed in the table are clinically determined in an arterial blood gas analysis (ABG).

| Parameters and Causes of Disorders in Acid-Base Balance |        |                                                                                                                                                                                                                                                                                         |                                               |                                                                                                                          |                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Disorder                                                                                                                                     |        | pH (Acidosis: pH <7.35; Alkalosis: pH >7.45) | paCO2 (Normal range: 32–45 mmHg (4.3–6.0 kPa)) | Standard-HCO3−(Normal range: 22–26 mmol/L) | BE (Normal range: −2 to +3 mmol/L) | Causes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Respiratory Acidosis                                      | Acute   | ↓                                                                                                                                                                                                                                                                                       | ↑                                             | ↔︎                                                                                                                       | ↔︎                                 | - Hypoventilation e.g. asthma attack, airway obstruction, weakened respiratory muscles, pulmonary emphysema, pulmonary edema, sedatives/opioids                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| (Partially) compensated                                                                                                                       | ↓ / ↔︎ | ↑                                                                                                                                                                                                                                                                                       | ↑                                             | ↑                                                                                                                        |                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Metabolic Acidosis                                         | Acute   | ↓                                                                                                                                                                                                                                                                                       | ↔︎                                            | ↓                                                                                                                        | ↓                                  | - Ketoacidosis (e.g. in decompensated type 1 diabetes mellitus)<br>- Lactic acidosis (e.g. in severe physical labor)<br>- Fasting<br>- Diarrhea<br>- Hyperkalemia<br>- Kidney failure<br>- Renal tubular acidosis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| (Partially) compensated                                                                                                                       | ↓ / ↔︎ | ↓                                                                                                                                                                                                                                                                                       | ↓                                             | ↓                                                                                                                        |                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Respiratory Alkalosis                                       | Acute  | ↑                                                                                                                                                                                                                                                                                       | ↓                                             | ↔︎                                                                                                                       | ↔︎                                 | - Hyperventilation e.g. psychogenic (excitement/stress), hypoxemia (staying at high altitude, pulmonary embolism)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| (Partially) compensated                                                                                                                       | ↑ / ↔︎ | ↓                                                                                                                                                                                                                                                                                       | ↓                                             | ↓                                                                                                                        |                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Metabolic Alkalosis                                        | Acute   | ↑                                                                                                                                                                                                                                                                                       | ↔︎                                            | ↑                                                                                                                        | ↑                                  | - Hyperaldosteronism (Conn's syndrome)<br>    - Mechanism<br>        1. Increased aldosterone concentration causes increased potassium excretion by the kidneys → hypokalemia<br>        2. Compensatorily, potassium is released from the cells into the blood in exchange for protons → metabolic alkalosis<br>        3. Additionally: Increase in bicarbonate concentration<br>- Hypokalemia<br>- Vomiting<br>- Medication<br>    - Antacids<br>    - Loop diuretics |
| (Partially) compensated                                                                                                                       | ↑ / ↔︎ | ↑                                                                                                                                                                                                                                                                                       | ↑                                             | ↑                                                                                                                        |                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Combined Acidosis                                                                                                                         |        | ↓                                                                                                                                                                                                                                                                                       | ↑                                             | ↓                                                                                                                        | ↓                                  | - Multiorgan failure (liver and kidney failure)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Legend: / = or, ↓ = decreased, ↑ = increased, ↔︎ = normal value                                                                              |        |                                                                                                                                                                                                                                                                                         |                                               |                                                                                                                          |                                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |

> [!NOTE]
> Standard bicarbonate is always measured at a defined pCO2; in respiratory disorders without metabolic compensation, the standard HCO3− remains unchanged! The current (!) bicarbonate concentration, on the other hand, is always in equilibrium with the pCO2. Therefore, if the pCO2 changes, the current bicarbonate changes in the same direction!

> [!NOTE]
> Through (partial) compensation, multiple systems can deviate from the normal values (for example, in the case of a decreased BE, both a (partial) compensated respiratory alkalosis and a metabolic acidosis can exist). Therefore, an assessment should always be made based on multiple parameters!

> [!NOTE] Hyperventilation
> In some people, extreme stress situations can trigger hyperventilation. The tidal volume of the affected individuals exceeds the requirements of their metabolism; they exhale increased amounts of CO2 and their arterial CO2 partial pressure decreases. Respiratory alkalosis develops and, due to cerebral vasoconstriction, cerebral blood flow decreases – the affected individuals may "see black." Further effects of alkalosis can include increased neuromuscular excitability and impaired O2 release from hemoglobin to the tissue. The consequences of hyperventilation can be addressed therapeutically in a straightforward manner: By inhaling and exhaling into a plastic bag, CO2 is re-breathed, thus correcting the blood pH level.

#### Anion gap and its significance in metabolic acidosis

The so-called anion gap helps in identifying the causes of metabolic acidosis and can be easily determined using the concentrations of Na+, Cl−, and HCO3−.

- Anion gap: A measure of the anions in the blood that are not routinely determinable, especially negatively charged proteins and metabolic products.
    - In the blood, the number of positive and negative charges is equal (= electrical neutrality). Na+ ions make up the majority of the positive charges, while Cl− and HCO3− ions account for the majority of the negative charges. However, negatively charged proteins and metabolic products also contribute to the negative charge.
    - Determination of the anion gap: Measurement of sodium, bicarbonate, and chloride concentrations in the blood and calculation of the difference from cations and anions.
- Calculation
    - Anion gap = [Na+] − ([HCO3−] + [Cl−])
        - Normal range: 7 ± 4 mmol/L (also 3–11 mmol/L), possibly also dependent on laboratory methods 12 ± 4 mmol/L (also 8–16 mmol/L)
    - Alternative (taking potassium into account): ([Na+] + [K+]) − ([HCO3−] + [Cl−])
        - Normal range: 11 ± 4 mmol/L or 16 ± 4 mmol/L
- Meaning and Interpretation: It serves to identify the causes of metabolic acidosis.
    - Acidosis with a physiological anion gap = "Bicarbonate loss"
        - Possible causes
            - Endogenous: Diarrhea, bile or pancreatic fistula, renal tubular acidosis
            - Exogen: Medications (carbonic anhydrase inhibitors), supply of acids whose anion is chloride (e.g., HCl)
    - Acidosis with increased anion gap = "Addition acidosis"
        - Possible causes
            - Endogenous: Lactic acidosis, Ketoacidosis, Kidney insufficiency/Uremia
            - Exogen: Poisoning by salicylic acid, ethanol, methanol, ethylene glycol (contained in antifreeze)
    - Disturbing factors: Hypoalbuminemia (decrease in the anion gap), Hyperphosphatemia (increase in the anion gap)

> [!NOTE]
> Keyword for causes of an increased anion gap "Kussmaul": ketoacids, uremia, salicylic acid, methanol, ethylene glycol, (uremia), lactate

## Review Questions on the Chapter Acid-Base Balance
### Chemical Fundamentals

What is referred to as a corresponding acid-base pair?  
- Acids are proton donors. When an acid donates a proton, it thereby becomes a base that can accept protons. This is called the conjugate base and forms a corresponding acid-base pair with the original acid.  
How is the pH value defined? Name the pH value of water as an example and explain where the protons come from!  
- The pH value is the negative decimal logarithm of the H3O+ concentration in a solution (pH = −lg[H3O+]). Water has a pH of 7, i.e., the concentration of protons is 10^-7 mol/L. The protons come from the autoprotolysis of water, in which a proton is transferred from one H2O molecule to a second H2O molecule. In pure water, the number of OH− and H3O+ ions is equal.  
Depending on the strength of an acid/base, different formulas are used to calculate the pH value. How is the pH value of phosphate anions (H2PO4−, HPO42−, PO43−) calculated, as well as that of hydroxide ions (OH−)?  
- Phosphoric acid anions are weak acids; accordingly, their pH value is calculated using the formula pH = ½ (pKS – lg[acid]). The hydroxide ion (OH−), on the other hand, is a strong base; the pH value is calculated using the formula pH = 14 + lg[base].  
What does the pH value of salt dissolved in water depend on? Explain, for example, how a weakly basic salt solution or a weakly acidic salt solution is formed and how its pH value can be determined!  
- When salts are dissolved in water, the pH value depends on the acid and base strength of the ions. For example, a weakly basic salt (in this case sodium acetate) is formed by the reaction of a strong base (e.g., NaOH) with a weak acid (e.g., acetic acid). When this salt is dissolved in water, the pH value of the weakly basic solution can be determined using the formula for weak bases: pH = 14 − ½ (pKB − lg[base]). A weakly acidic salt solution (e.g., ammonium chloride solution) forms when the salt from the reaction of a weak base (e.g., NH3) with a strong acid (e.g., HCl) is dissolved in water. The formula to calculate the pH value corresponds here to the pH formula for a weak acid: pH = ½ (pKS − lg[acid]).  
Are the neutral point and the equivalence point in the titration of a weak acid with a strong base synonymous?  
- In titration, known amounts of a base or acid are added to an unknown acid or base, and the changes in pH value are measured using an indicator. This allows the experimentally determination of the unknown acid or base quantity in the solution. At the equivalence point, the solution contains exactly the same amount of acid (or base) and titrant. The equivalence point does not necessarily correspond to the neutral point (= point at which the neutral pH value is reached). For example, the equivalence point in the titration of a weak acid with a strong base lies in the basic range.  
What principle do buffer substances operate on and how do you calculate their pH value?  
- Buffer substances stabilize the pH value of liquids. They are an aqueous solution of weak (!) corresponding acid-base pairs (e.g., acetic acid/acetate; ammonium/ammonia). Due to this mixture of acid and base, small changes in pH value can be absorbed, i.e., even if a little acid or base is added to a buffer solution, the pH initially does not change. The pH value of a buffer solution is calculated using the Henderson-Hasselbalch equation: pH = pKS + lg(cB / cS). The concentrations of the buffering substances must therefore be known.  
### Physiological pH Values and Their Fluctuations

What influence does nutrition have on the body's pH level?  
- During the breakdown of carbohydrates, fat, and amino acids, the "volatile" acid CO2 is produced, which is exhaled. In addition, during the degradation of sulfur-containing amino acids from protein-rich food, “fixed” acids SO42− and H+ are formed, which cannot be eliminated immediately. But fasting also leads to the production of acidic valences in the body, since lipolysis produces free fatty acids and ketone bodies.  
### Regulation of Acid-Base Balance through Buffer Systems

How does the protein buffer system work?  
- The protein buffer system consists primarily of hemoglobin and albumin and serves to regulate the blood pH value. Its buffering effect is enabled by ionizable side groups of the proteins (the reactive groups of the amino acids take up H+ or release it as needed). Of particular importance here is the amino acid histidine, which at a pKS value of about 6.0 is only partially protonated at physiological pH and thus is a good buffer.  
What is the function of the phosphate buffer system? State the reaction equation!  
- The phosphate buffer system is important for regulating the intracellular pH value and contributes via HPO42− to H+ excretion through the urine. It works through proton uptake or release by a corresponding acid-base pair: PO43− + H+ ⇄ HPO42− + H+ ⇄ H2PO4− + H+ ⇄ H3PO4.  
### Regulation of Acid-Base Balance in the Organs

How does H+-excretion occur through the kidneys and how can it be increased in the case of acidosis?  
- Since the number of free H+ ions in the urine cannot be increased arbitrarily, the buffer systems are of great importance (especially in the case of acidosis). The acidic valences are secreted via the Na+/H+ antiporter in the proximal tubule as well as via an H+-ATPase and an H+/K+-ATPase of the type A intercalated cells in the late distal tubule and collecting duct. They are then bound in the urine to ammonia and phosphate and thereby buffered. Therefore, the urine pH value does not fall below 4.5. In acidosis, the excretion of NH4+ and PO43− can be increased by increased ammonia production in the kidney (increased glutaminase activity) and reduced phosphate reabsorption in the proximal tubule.  
### Disturbances of Acid-Base Balance

How are the disturbances of acid-base balance classified?  
- Disorders of the acid-base balance are classified according to the type of pH deviation (acidosis: pH <7.35, alkalosis: pH >7.45), the cause (respiratory, metabolic, or combined), and the course (acute, partially compensated, or compensated).  
What can compensate for a deviation in pH value? And how do partially compensated disorders differ from compensated disorders of the acid-base balance?  
- In compensation, the respectively other still intact system counteracts the pH deviation, so that both the parameters for the respiratory and the metabolic system are changed. In full compensation, the pH value is back within the normal range at changed pCO2 and standard bicarbonate; in partially compensated disorders, all three parameters are altered.  
What laboratory chemical constellation would one expect in a respiratory acidosis that is metabolically partially compensated?  
- A respiratory acidosis is characterized by an increased partial pressure of CO2 (>45 mmHg) and a reduced pH value (pH <7.36). In the course of metabolic partial compensation, a positive base surplus or Base Excess (BE) arises due to increased renal bicarbonate and phosphate reabsorption.  
Through which laboratory chemical parameters can metabolic acidosis be recognized? How is it compensated?  
- Metabolic acidosis is caused by a metabolic disorder, so besides the pH value drop, evidence of the underlying disease would be found. Representative parameters for metabolic acidoses are standard bicarbonate and the base excess (BE, Base Excess). The base excess is defined as a change in the total available buffer bases, which consist of bicarbonate and the non-bicarbonate buffer (= protein and phosphate buffer). Over the course, respiratory compensation occurs in the form of hyperventilation, through which more CO2 is exhaled. This typical deep breathing for acidosis is also called “Kussmaul respiration.”  
What laboratory chemical constellation would one expect in a diabetic ketoacidosis?  
- In diabetic ketoacidosis, due to insulin deficiency, glucose available cannot be utilized, which leads to hyperglycemia. Instead, ketone body production is increased (ketogenesis) to cover energy demand, which results in metabolic acidosis (pH value <7.35).  
What disturbance of the acid-base balance does primary hyperaldosteronism (Conn's syndrome) lead to?  
- Primary hyperaldosteronism (= Conn's syndrome) is the most common cause of primary metabolic alkalosis with consecutive HCO3− increase. Aldosterone causes an increase in bicarbonate via two mechanisms. First, it activates the proton pump in the type A intercalated cells of the renal collecting duct, which indirectly leads to enhanced bicarbonate reabsorption. Furthermore, renal hypokalemia occurs, which also stimulates the apical proton pump in type A intercalated cells.  
What laboratory chemical constellation would one expect in cases of severe vomiting?  
- In severe vomiting, through the loss of acid-containing gastric juice, metabolic alkalosis (pH value increase) occurs. The accompanying chloride loss leads to a bicarbonate secretion disorder in the kidney and thus to an increase of bicarbonate in the plasma and consequently to a positive base excess. In respiratory (partial) compensation, an increase of pCO2 would also be expected since acidic-acting CO2 is supposed to compensate the base excess.  
What characterizes a combined respiratory and metabolic acidosis?  
- In a combined respiratory and metabolic acidosis, a low pH value, an increased pCO2, and a negative base excess (too few bases in the blood) are evident. Combined acidoses (pCO2↑, BE↓) occur, e.g., in liver failure and respiratory insufficiency and are medical emergencies.  
Describe the consequences of severe hyperventilation! How does the standard bicarbonate change in this process?  
- During hyperventilation, more CO2 is exhaled. The majority of CO2 transported in the blood is converted by erythrocyte carbonic anhydrase into easily soluble bicarbonate: H2O + CO2 ⇄ HCO3− + H+. If the arterial CO2 partial pressure falls, less HCO3− and thus less H+ can be formed, resulting in respiratory alkalosis. The laboratory-determined current (!) bicarbonate concentration is always in equilibrium with the pCO2 and is therefore lower in respiratory alkalosis. In contrast, standard bicarbonate is a value always measured at a defined or standardized pCO2 and thus remains unchanged in respiratory disorders without metabolic compensation.  
What does the so-called anion gap refer to? When is it increased, and when does it remain the same?  
- The anion gap is a measure of the anions in the blood that are not routinely determined, especially negatively charged proteins and metabolic products. It can be calculated using certain ion concentrations in blood plasma: Anion gap = Na+ + K+ − Cl− − HCO3− (difference between cations and anions). Practically, determining the anion gap is used to find the cause of metabolic acidosis. When bases are lost (bicarbonate loss), the anion gap remains the same or physiological due to compensation by chloride, e.g., in diarrhea. When acids increase, the anion gap enlarges (“addition acidosis”); possible causes include lactate or ketoacidosis.