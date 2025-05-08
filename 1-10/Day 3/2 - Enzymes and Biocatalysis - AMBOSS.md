# Enzymes and Biocatalysis
## Summary

Some chemical reactions do not occur spontaneously, even though they are actually exergonic (see: Thermodynamics). The reason for this is usually that the reactions have a high activation energy that must be overcome. If the reaction is still to take place, then it must be catalyzed: To do this, a substance called a catalyst is added to the reactant, which forms a catalyst-reactant complex for which the activation energy is significantly lower. A catalyst is not consumed during the reaction but can convert an arbitrary amount of reactant over time.

In cells, chemical reactions are catalyzed by biocatalysts, known as enzymes. These are mostly proteins that possess an active site where a substrate can bind and be transformed. They are present in all compartments of the cell and are involved in nearly all metabolic processes.

Enzymes are very specific regarding the substrate they act upon and the reaction they catalyze. Furthermore, these enzymes can be regulated in various ways – along with the entire cellular metabolism. The regulatory strategies range from influencing the transcription and translation of the enzymes (very slowly) to rapid activity-altering conformational changes of the enzymes mediated by certain effectors. Additionally, there are different ways to inhibit enzymes in their activity either long-term or temporarily.

## Theoretical Foundations

### Enabling Chemical Reactions

Even chemical reactions that are not thermodynamically favored (see: Thermodynamics) can occur under suitable conditions. "Suitable" means in the laboratory that sufficient energy is supplied from the outside so that the reaction can take place. For this purpose, external parameters such as temperature or pressure are usually drastically changed. In a living cell, this is of course not (or only very limited) possible. Therefore, thermodynamically unfavorable reactions can only occur under in-vivo conditions if they are facilitated by a catalyst and the energy required for the reaction can be drawn from another (energy surplus producing) process. Such reactions are referred to as "coupled."

- Catalysis: Reduction of the activation energy of a reaction through a more energetically favorable transition state.
    - Function: Makes a reaction energetically favorable, so that it can occur more easily.
    - Catalyst: Substance that makes the reaction energetically more favorable.
        - Principle: The catalyst is not consumed during the reaction itself but is recovered at the end and reused for the same reaction.
        - Example: Enzyme
- Chemical reaction coupling: Combining an energetically unfavorable reaction with an energy-releasing process
    - Function: Ensures that an unfavorable reaction can still occur = Energy transformation.
    - Coupling partners of the reactions
        - Chemiosmotic coupling: concentration gradient across a membrane
        - Chemical coupling: Energy carrier molecules

#### "Energy-rich" compounds as energy carrier molecules

“Energy-rich” compounds are small molecules to which functional groups can be reversibly transferred, thereby turning them into energy carriers. The reaction of the functional group (usually phosphate groups) being cleaved from the energy carrier molecule occurs with the help of water, releasing a large amount of energy. The most important energy carrier is ATP. For details on ATP synthesis, see: electron transport chain.

|Starting molecule (without transferred group)|Transferred group|Energy carrier molecule|Energy released during hydrolysis|Medical significance|Molecular structure|
|---|---|---|---|---|---|
|ADP|Phosphate|ATP (Adenosine triphosphate)|−31 KJ/mol|Ubiquitous energy carrier||
|GDP|Phosphate|GTP (Guanosine Triphosphate)|−31 KJ/mol|Citric Acid Cycle||
|Creatine|Phosphate|CP (Creatine Phosphate)|−43 KJ/mol|Glycolysis, Glycogen breakdown, Citric acid cycle, oxidative phosphorylation||
|CoA|Thioester|Acetyl-CoA (= Cysteamine group (binding site for the acetyl group), which binds to pantothenic acid, which in turn binds to an ADP molecule that is additionally phosphorylated at the 3' position)|−36 KJ/mol|Citric acid cycle, β-oxidation||
|Pyruvate|Phosphate|PEP (Phosphoenolpyruvate)|−62 KJ/mol|Glycolysis||

Energy carrier molecules are not energy storage! Energy storage must have a particularly high energy density. Fatty acids, for example, have an energy content of about 37 KJ/g, whereas in 1 mol (= 507 g) of ATP, only 31 KJ/mol of energy is stored!

### Enzyme – Definition and Structure

Enzymes are molecules that catalyze reactions in biochemical systems, so they are "biocatalysts." Enzymes are almost exclusively proteins, with ribozymes being the only exception. However, the number of protein enzymes that also have non-protein components (the so-called holoenzymes) is large.

#### Structure

For the general structure of proteins see: Amino acids and proteins.

- Active Center
    - Area of the enzyme where the reaction takes place
    - Often a bag or cavity inside the protein
- Regulatory Center
    - Some enzymes have an additional binding site alongside the active center that serves to regulate enzyme activity.

#### Types

- Ribozyme (see here: RNA: structure and properties)
- Pure protein enzymes
- Holoenzyme: Always consist of apoenzyme and cofactor
    - Apoenzyme: Protein part of the enzyme
    - Cofactor (also coenzyme): Non-protein part of the enzyme
        - Prosthetic group
            - Definition: A tightly (often covalently) bound organic molecule attached to a protein
            - Examples
                - Biotin (Carboxylases): Serves the CO2 transfer
                - Häm (Cytochrome c) : Serves in electron transfer with its central iron atom.
                - Flavin (Flavoprotein): Serves the purpose of hydrogen transfer
        - Metallion
            - Definition: A metal ion that is coordinatively bound in the active site involved in the catalytic reaction
            - Examples: Fe3+, Cu2+, Ni2+, Zn2+
        - Cosubstrate: Cofactors that dissociate from the enzyme after the catalytic reaction.

#### Overview of Selected Holoenzymes and Their Non-Protein Cofactors

| Cofactor                   | Molecular Structure | Functional Group                                 | Enzymes                    | Enzyme Reaction                                     |
| -------------------------- | ------------------- | ------------------------------------------------ | -------------------------- | --------------------------------------------------- |
| Thiamine diphosphate       |                     | Thiazolium ylid                                  | Pyruvate dehydrogenase     | Oxidative decarboxylation                           |
| FMN                        |                     | Isoalloxazin                                     | Oxidoreductases            | Electron transfer                                   |
| FAD                        |                     | Isoalloxazin                                     | Oxidoreductases            | Electron transfer                                   |
| NAD(P)+                    |                     | Pyridine                                         | Oxidoreductases            | Electron transfer                                   |
| Pyridoxalphosphate         |                     | Aldehyde function                                | Aspartate aminotransferase | Transamination, Decarboxylation, Dehydration        |
| Biotin                     |                     | Urea or carbamic acid diamide                    | Carboxylases               | Carboxylation                                       |
| Cobalamin                  |                     | Co2+-Ion                                         | Methylmalonyl-CoA-Mutase   | Alkyltransfer                                       |
| S-Adenosylmethionine (SAM) |                     | Sulfonamide                                      | Methyltransferases         | Methylation (SAM is a so-called methyl group donor) |
| Liponamide                 |                     | Disulfide                                        | Pyruvate Dehydrogenase     | Oxidative Decarboxylation                           |
| Tetrahydrofolate           |                     | Amines                                           | Methyltransferases         | Methylation                                         |
| Coenzyme A                 |                     | Thiol                                            | Citrate synthase           | Acyltransfer                                        |
| Ascorbic acid              |                     | Endiol structure with adjacent carbonyl function | Prolyl-4-hydroxylase       | Redox chemistry, hydroxylation                      |
| Phylloquinone              |                     | Quinone                                          | Carboxylase                | Oxidative Carboxylation                             |
| Tetrahydrobiopterin        |                     | Pterin                                           | Hydroxylases               | Hydroxylation                                       |

> [!note] Enzyme Diagnostics
> Since enzymes are involved in all metabolic processes, their distribution and the available amount can be used to check whether the respective metabolic process in the body is functioning normally. This is currently utilized in a large number of enzyme diagnostic procedures, particularly within liver and heart diagnostics. For example, an elevated concentration of creatine kinase in the blood indicates a heart attack, as the death of myocardial cells leads to the release of creatine kinase, which can still be detected in the serum for up to 4 hours.

> [!note]
> Enzymes are usually proteins; however, proteins are not necessarily enzymes!

### Enzyme Classification

The suffix “-ase” in the name already indicates that a molecule is an enzyme. Furthermore, there is also an internationally recognized classification of enzymes based on their respective function or substrate:

||The seven main classes of enzymes|   |   |
|---|---|---|---|
|Class|Name|Catalyzed Reaction|Examples|
|---|---|---|---|
|1|Oxidoreductases|Redox reactions|- (De-)hydrogenases<br>- Oxidases<br>- Oxygenases|
|2|Transferases|Transfer functional groups from one substrate to another|- Kinases (transfer phosphate residues, e.g., from ATP to another molecule and cleave the phosphoanhydride bond between two phosphate groups in ATP)<br>- Aminotransferases<br>- Glycosyltransferases|
|3|Hydrolases|Hydrolytic cleavage of covalent bonds|- Phosphatases<br>- Esterases|
|4|Lyasen|Formation and splitting of all covalent bonds that do not fall into classes 1 and 3|- Aldolase<br>- Fumarase|
|5|Isomerases|Conversion of substrates into their isomers|- Mutases<br>- Epimerases|
|6|Ligasen|Formation of covalent bonds and coupling of the reaction to the hydrolysis of an energy carrier molecule (see above)|- Carboxylases<br>- DNA ligase|
|7|Translocases|Movement of ions or molecules across a membrane|- ATP synthase<br>- H+/K+-ATPase|

> [!note]
> The suffix "-ase" in the name already indicates that a molecule is an enzyme!

> [!note]
> Isoenzymes catalyze the same reaction, even though they are structurally different!

## Biocatalysis

Biocatalysts accelerate reactions in biochemical systems by lowering the activation energy or enabling alternative reaction pathways. Biocatalysts are extremely effective and far superior to synthetic catalysts in terms of selectivity and activity, as they have evolved precisely to suit their substrate and reaction.

### Enzyme Specificity

A catalytic reaction in living cells is a catalysis under challenging conditions: A variety of substances are present simultaneously, some of which are very similar. Nevertheless, it must be ensured that an enzyme acts on the correct substrate and that only the desired product is produced, as the production of other substances can be toxic and would disrupt the finely tuned metabolism of the cell.

- Substrate specificity
    - Definition: Enzymes selectively recognize "their" substrate.
    - Cause: Complementary structures of enzyme and substrate
- Reaction specificity
    - Definition: Enzymes only convert a substrate in a specific way
    - Cause: The substrate is always aligned the same way in the active center, so the involved functional group of the enzyme can always attack in the same manner.
- Stereospecificity
    - Definition: A reaction in which only one of several possible stereoisomers is formed (details on isomerism see: Fundamentals of Organic Chemistry)
    - Cause: Proteins are made up of chiral amino acids and are therefore chiral themselves; the chiral environment of the active center ensures that:
        - That only a specific isomer can be bound and converted.
        - That (when a non-chiral molecule becomes chiral) the substrate is transformed in such a way that only one of the possible stereoisomers can be formed spatially.

### Catalytic Enzyme Activity

To specify the catalytic activity of an enzyme, there are various reference measures that relate to the volume, mass, amount of substance, or amount of substance considering the number of active sites of an enzyme. The SI unit of enzyme activity is the "katal" (kat; 1 kat = the amount of enzyme that converts 1 mol of substrate into product in 1 s under defined conditions). The historical unit "unit" (U; 1 U = the amount of enzyme that converts 1 μmol of substrate into product in 1 min under standard conditions) can still be found in some studies.

- Volume activity: Enzyme activity per volume
    - Unit: kat/L or U/mL
- Specific catalytic activity: Activity related to the mass of the enzyme
    - Unit: kat/kg or U/mg
- Molar catalytic activity: Activity related to the amount of substance of the enzyme
    - Unit: kat/mol
- Turnover number: Molar catalytic activity relative to the number of active sites of the enzyme
    - Is used very often in biochemical practice
    - It is also known by the English term "turnover rate"

> [!note]
> Information about enzymes is not always provided under standard conditions: In the laboratory, a reference temperature of 25°C or 30°C is often used, whereas clinical studies almost exclusively use 37°C!

> [!note] Measurement of enzyme activity
> The enzymatic activity can be measured through the conversion of metabolic products. Enzymatic processes, in which NAD(P)+ is converted to NAD(P)H (or vice versa), can be tracked optically: The absorption maximum of NAD(P)+ is significantly lower at 260 nm compared to that of NAD(P)H with a second absorption maximum at 340 nm, which can be quantified photometrically (so-called simple optical test). The activity of enzymes that do not convert NAD(P)+ or NAD(P)H can also be determined photometrically. For this, an indicator reaction is coupled to the reaction to be measured, in which NAD(P)+ or NAD(P)H is involved (so-called coupled optical test). This method is commonly used in the diagnostics of liver diseases, for example: In this case, the reaction of alanine aminotransferase (Alanine + α-Ketoglutarate ⇄ Pyruvate + Glutamate) is coupled with the reaction of lactate dehydrogenase (Pyruvate + NADH ⇄ Lactate + NAD+). The decrease in NADH concentration directly indicates the activity of alanine aminotransferase.

#### Dependence on Physical Factors

The activity of an enzyme depends on external factors.

- Temperature
    - Behavior: Within a small range of fluctuation, enzyme activity increases with temperature; however, beyond the optimum, enzyme activity decreases drastically.
        - Reason: Denaturation of the enzymes at too high a temperature
    - Optimum: Temperature at which the highest activity of the enzyme is observed
- pH value
    - Behavior: Most proteins exhibit an activity maximum between pH 4 and pH 9.
    - Reasons
        - Reversible dissociation and ionization of functional groups of the enzyme
        - Reversible dissociation and ionization of the substrate
        - Denaturation of the enzyme at an extreme pH
- Salt concentration
    - Structural prerequisites: A certain amount of salts may be necessary to stabilize the spatial structure or even the chemical function of proteins (tolerance range).
    - Reason: Denaturation of enzymes outside the tolerance range
- Oxidative environment
    - Influence: Oxidizing agents such as atmospheric oxygen and transition metal ions in the vicinity of the enzyme can inactivate (or selectively activate) the enzyme.
    - Reason: Change in the spatial structure of an enzyme or its stability
    - Example: Sulfhydryl groups of the enzyme, which are involved in the catalytic reaction, are oxidized to form disulfide bridges, causing the enzyme to change its conformation.

### Proximity Effect

Through the binding of the substrate to the enzyme, a reaction formally shifts from an interaction between different particles (intermolecular reaction) to a reaction within a single particle (intramolecular reaction). Due to the spatial proximity of all components involved in the reaction and their spatial "pre-organization," their effective concentration at the site of the reaction is significantly increased – thereby increasing the likelihood of the reaction occurring. Additionally, the speed at which the reaction takes place is enhanced. This effect is referred to as the "proximity effect."

### Enzyme Kinetics

The kinetics describes the rate of chemical reactions and processes. In an enzymatic reaction, the rate depends on both the amount of available enzyme and the concentration of the substrate. If the concentration of the enzyme is kept constant, the rate shows a saturation curve depending on the substrate concentration.

#### Michaelis-Menten Model

Enzyme-catalyzed reactions have a special kinetics that is described using the Michaelis-Menten model. It is assumed that an enzyme-substrate complex is formed during the reaction:

Michaelis-Menten reaction

This enzyme-substrate complex (ES) is in a dynamic equilibrium with the other components of the reaction mixture (the enzyme (E), the substrate (S), and the product (P)). A dynamic equilibrium is a state in which substances continuously flow in at the same rate as they flow out. This is a consequence of the fact that cells are open systems that are in constant exchange with their environment.

- Michaelis-Menten equation: v = vmax × c(S) / (KM + c(S))
    - v = reaction rate, vmax = maximum reaction speed (with a large excess of substrate compared to the enzyme), c(S) = concentration of the substrate in the mixture, KM = Michaelis-Menten constant
- Michaelis-Menten constant: KM = (k+2 + k−1) / k+1
    - Unit: mol/L
    - KM = Michaelis-Menten constant, k+2 = rate constant of the reaction ES → E + P, k−1 = rate constant of the reaction ES → E + S, k+1 = rate constant of the reaction E + S → ES
    - Definition: Substrate concentration at which half of the active sites of the enzymes involved in the reaction are occupied by substrate.
        - Describes how strong the affinity of an enzyme for a substrate is
        - Corresponds to the substrate concentration at which the initial reaction rate is half-maximal.
        - Is always the same for an enzyme-substrate combination.
- Maximum speed: vmax = k+2 × c(ET)
    - vmax = maximum speed, k+2 = rate constant of the reaction ES → E + P, c(ET) = total concentration of the enzyme in the mixture
    - vmax is the maximum reaction rate that is achieved with a defined amount of enzyme (by definition, the enzyme concentration assumed here is the one needed to convert 1 mol of substrate in 1 s)
    - Unit: m/s
- Rate constant k+2: Switching number
    - k+2 = rate constant of the reaction ES → E + P
    - Number of substrate molecules converted to product per enzyme per second
- Maximum catalytic activity: k+2/KM
    - Catalytic effectiveness is limited by the diffusion-related encounter of enzyme and substrate.
    - In aqueous solution approximately 109 × 1/sM

###### Derivation of the Michaelis-Menten Equation

Michaelis-Menten reaction

- The reaction E + S → ES is a second-order reaction (see: reaction order), therefore the rate of the reaction is
    - v = k1 × [E] × [S]
- At the same time, however, two first-order reactions are taking place that decrease the concentration of the enzyme-substrate complex:
    - ES → E + S with the speed v = k−1 × [ES]
    - ES → E + P with the speed v = k+2 × [ES]
- In the equilibrium state, the reactions that lead to the formation of ES occur at the same speed as the reactions that lead to the breakdown of ES:
    - 0 = (k1 × [E] × [S]) − (k−1 × [ES]) − (k+2 × [ES])
- Because the concentration of E is unknown and cannot be easily measured, one tries to replace it in the equation and first introduces the total concentration of the enzyme E0: [E]0 = [E] + [ES] or [E] = [E0] – [ES]
    - ⇔ 0 = (k1 × ([E0] – [ES]) × [S]) − (k−1 × [ES]) − (k+2 × [ES])
- Expanding the bracket:
    - ⇔ 0 = (k1 × [E0] × [S]) – (k1 × [ES] × [S]) − (k−1 × [ES]) − (k+2 × [ES])
- Factoring out – [EN]:
    - ⇔ 0 = (k1 × [E0] × [S]) – [ES] × (k1 × [S] + k−1 + k+2)
- [EN] to bring to one page:
    - k1 × [E0] × [S] = [ES] × (k1 × [S] − k−1 − k+2)
    - ⇔ (k1 × [E0] × [S]) / (k1 × [S] − k−1 − k+2) = [ES]
    - ⇔ ([E0] × [S]) / (((k−1 + k+2)/k1) + [S]) = [ES]
- For the term (k−1 + k+2)/k1, the constant KM, the Michaelis-Menten constant, is now introduced.
    - ⇔ ([E0] × [S]) / (KM + [S]) = [ES]
- If you now set the initial velocity v0 = k2 × [ES] => [ES] = v0 / k2, it follows
    - v0 = (k2 × [E0] × [S]) / (KM+[S])
- Since k2 × E0] is the maximum [speed vmax of the reaction, this can also be replaced:
    - ⇔ v0 = (vmax × [S])/(KM+[S])

#### Lineweaver-Burk Plot

For the practical determination of the Michaelis-Menten constant KM and the maximum velocity vmax, the plot of velocity against substrate concentration proposed by Michaelis and Menten is not very suitable. Instead, a linear plot is chosen, which is named after its developers the Lineweaver-Burk plot:

- Graphic representation
    - Equation of the line: 1/v = 1/vmax + KM/vmax × 1/c(S)
        - The slope of the line is therefore KM/vmax
    - Important points
        - Intersection of the line with the y-axis: Here 1/vmax can be read off
        - Point of intersection of the line with the x-axis: Here, -1/KM can be read off

## Enzyme Regulation

To coordinate processes in cells and control them precisely, not all enzymes should always catalyze their reactions with full activity. Therefore, there are various mechanisms for the regulation of enzymes that increase, decrease, or even completely inactivate (for a certain period) their activity.

### Inhibition of Enzymes

Reduction of enzyme activity through the action of so-called inhibitors.

#### Reversible Inhibition of Enzymes

Temporary inhibition of an enzyme that can be reversed.

|Overview of Mechanisms of Reversible Inhibition|   |   |   |   |   |
|---|---|---|---|---|---|
||Inhibitor|Mechanism|Reaction Scheme|Termination of Inhibition|Example|
|---|---|---|---|---|---|
|Competitive Inhibition|- A substance that is similar to the substrate and binds to the same site on the enzyme|- Inhibitor competes with the actual substrate<br>- Binds reversibly to the active site, thus only temporarily blocking the enzyme<br>- => vmax of the enzyme remains the same, KM increases||- Removal of the inhibitor<br>- Increase in substrate concentration until it is significantly greater than that of the inhibitor|- ACE inhibitors|
|Non-competitive inhibition|- A substance that is not similar to the substrate and binds to a different site on the enzyme|- Inhibitor binds to the enzyme and inactivates it<br>- Lowers the concentration of active enzymes in the mixture<br>- => vmax of the enzyme decreases, KM remains the same||- Removal of the inhibitor|- Heavy metals like mercury or lead|
|Non-competitive inhibition|- A substance that is not similar to the substrate and binds to a different site on the enzyme|- Inhibitor binds only to the enzyme-substrate complex, not to the free enzyme<br>- => vmax of the enzyme decreases, KM also decreases||- Removal of the inhibitor|- Lithium chloride as an inhibitor of inositol monophosphatase|

> [!note] ACE inhibitor
> ACE inhibitors are substrate analogs of Angiotensin I and thus competitive inhibitors. They prevent the synthesis of Angiotensin II by inhibiting the enzyme ACE (Angiotensin Converting Enzyme, Kininase II) by interacting with a zinc ion from the active center of ACE via a thiol group. As a medication, ACE inhibitors are used in the treatment of hypertension.

#### Irreversible Inhibition of Enzymes

Inhibition of an enzyme that permanently inactivates it and cannot be reversed. To restore activity, the enzyme must be resynthesized. An example of irreversible inhibition is monoamine oxidase inhibitors, which are primarily used in Parkinson's therapy.

- Transition state analogs: Inhibitors that resemble the transition state of the substrate during the reaction, but usually bind much more tightly than the actual substrate.
- Suicide substrate: An inhibitor that is transformed at the active site and binds so tightly to the enzyme that the product cannot be released again.
    - Example: Penicillin
        - Binds to the bacterial enzyme D-Alanine transpeptidase, which is important for the construction of the bacterial cell wall.
        - Hydrolysis of penicillins is very slow, so the active site of the enzyme remains blocked.

> [!note] Cyclooxygenase Inhibitor
> Cyclooxygenase is an enzyme that occurs in two isoforms (COX-I and COX-II) and is involved, among other things, in the synthesis of prostaglandins. While the isoform COX-I is primarily responsible for the production of mucus in the gastric mucosa and renal blood flow, COX-II primarily promotes inflammatory processes, pain sensitization, and an increase in body temperature. To mitigate the negative effects of COX-II, non-selective non-steroidal anti-inflammatory drugs (NSAIDs) can be administered, which inhibit both COX-II and COX-I. A well-known example is acetylsalicylic acid, whose acetate group is transferred to a serine residue of COX, thereby blocking the active site of the enzyme. However, side effects can include bleeding of the gastric mucosa and a decrease in kidney function. Due to these side effects, selective COX-II inhibitors (so-called coxibs) were developed, which were intended to specifically reduce inflammation. Over time, however, it was found that these also cause serious side effects, as they influence the thromboxane production of cyclooxygenase and thus promote coagulation in narrow vessels. As a result, several COX-II inhibitors were withdrawn from the market.

### Allosteric

Allostery is an important mechanism for changing the activity of an enzyme.

- Effector: A substance that is not similar to the substrate of an enzyme but can bind to the enzyme at a different site.
    - Negative effector: Inhibits enzyme activity
    - Positive effector: Increases enzyme activity
- Mechanism
    - The effector binds reversibly to the enzyme at a regulatory binding site outside the active center.
    - The enzyme changes its conformation and then binds more easily or less easily to the substrate.
    - The effector can detach from the enzyme once the achieved effect is to be reversed.
    - The allosterically regulated enzyme oscillates between an active form and an inactive form.
- Function: Allosterically influenced enzymes hold a central switching position in branched biosynthetic pathways.
- Example: Phosphofructokinase 1
    - Phosphofructokinase exists in five isoforms and has a regulatory binding site at the C-terminus of the protein. Here, it acts:
        - Inhibitory Effectors: ATP (substrate inhibition, see below), NADH/H+ and Citrate
        - Activating effectors: Fructose-2,6-bisphosphate, AMP, and ADP

> [!note]
> Allosteric effects also occur in proteins that are not enzymes!

#### Negative Feedback

A special type of allosteric inhibition is substrate inhibition, where the effector is the product of an enzyme that occurs later in the biosynthesis pathway. If the concentration of this substance rises above a certain level (i.e., enough of this substance has been produced and the cell does not need this substance in greater amounts), then the cell can automatically limit the production of the substance.

### Chemical Modification of Enzymes (Interconversion)

Even through covalent modification, which is the permanent binding of molecules or functional groups to an enzyme, its activity can vary. Enzymes that transition into different active forms through covalent modification are referred to as "interconvertible."

- Phosphorylation: A phosphate group is transferred from ATP to the enzyme, for example.
- Dephosphorylation: A phosphate group is hydrolytically removed by the enzyme.
    - Function: Both forms of the enzyme have different activities; it depends on the specific case which of the two forms is more active.
    - Examples
        - Glycogen synthase (the active form is dephosphorylated)
        - Phosphorylase kinase (active form is phosphorylated)
- ADP-ribosylation: Transfer of one or more ADP-ribose units from NAD to a protein
    - Function: Occurs, for example, in DNA repair mechanisms, gene regulation, and apoptosis.
    - Example: Poly-(ADP-ribose)-Polymerase 1 (PARP-1)
- Limited proteolysis: Proteins are activated by the removal of a specific inhibiting peptide residue.
    - Zymogen/Proenzyme: Inactive protein precursor
    - Example: Trypsinogen is converted into trypsin by the enzyme enteropeptidase.

> [!note]
> Phosphorylation cascades can lead to a tremendous increase in regulated metabolism!

> [!note] Choleratoxin
> The toxic effect of cholera toxin, produced by a bacterium and causing severe diarrhea in humans, is based on the ADP-ribosylation of a subunit of a heterotrimeric G-protein. This inhibits the GTPase activity of that subunit while the G-protein itself remains in an active state. As a result, there is a continuous activation of adenylate cyclase, which produces cAMP. Due to the resulting excess of cAMP, the activities of membrane channels change, leading to an increased efflux of water into the intestinal lumen.

### Control of the total concentration of an enzyme

The speed of an enzymatic reaction depends significantly on the concentration of that enzyme (see above). Therefore, the regulation of the total concentration (that is, the concentration of the enzyme independent of its activity) can also be used to regulate the catalytic process. However, since this concentration can only be achieved through the influence of translation and transcription (see: Regulation of Gene Expression), this is not a short-term effective strategy.

### Protein-Protein Interactions

Protein-protein interactions can influence the activity of enzymes in various ways and thus contribute to regulation:

- Oligomeric Enzyme: Enzymes that consist of multiple subunits and whose function depends on the cooperative behavior of these subunits.
    - Example: Protein kinase A
- Adapter proteins: Not enzymes themselves, but proteins that have various protein binding sites and thus bring protein binding partners spatially close to each other and facilitate their linkage.
    - Example: Growth factor receptor 2 (Grb2)
- Chaperone: Not enzymes themselves, but protein complexes that prevent the aggregation of proteins and thus ensure, for example, the activity of enzymes.
    - Example: Heat shock protein 60 (Hsp60)


### Spatial separation of enzyme and substrate

The spatial separation of enzymes and substrate is also referred to as "sequestration." An example of this is glucokinase regulation:

- Enzyme: Glucokinase
    - Function: Phosphorylates D-Glucose to Glucose-6-Phosphate.
- Effector: Glucokinase Regulatory Protein
    - Effect
        - Controlled by intracellular glucose concentration
        - Inactivates glucokinase by binding when glucose levels are low
        - Complex of enzyme and effector is transported into the cell nucleus.
        - If the glucose level rises, the effector dissociates and the enzyme is transported back into the cytosol.
    - Advantage: Quick response to fluctuating glucose concentration

## Review Questions on the Chapter Enzymes and Biocatalysis
### Theoretical Foundations

What components make up the molecule Acetyl-CoA?
- The molecule Acetyl-CoA consists of an acetyl group and a coenzyme A (CoA). The coenzyme A consists of 3-phospho-ADP, to which a molecule of pantothenic acid binds via the diphosphate group, to which in turn the amino group of a cysteamine (β-mercapto-ethylamine) binds. The SH group of this molecular component can then bind acetyl as a thioester.

What is an enzyme and what components can it be made of?
- Enzymes accelerate chemical reactions that would either not occur or only occur very slowly on their own. They act as catalysts, meaning they themselves remain unchanged. They are almost always proteins; only the group of ribozymes consists of RNA.

What is the difference between prosthetic groups and cosubstrates?
- Prosthetic groups and cosubstrates are both cofactors necessary for the function of the associated enzyme. A prosthetic group is an organic molecule that is tightly (often covalently) bound to the protein (e.g., biotin, heme), whereas a cosubstrate only remains with the enzyme for the catalytic reaction and then dissociates again.

What cofactor does cytochrome C require?
- Cytochrome C requires heme as a prosthetic group. "Heme" refers to an organic porphyrin ring, in whose center an Fe(II) ion is bound.

For which cofactor does the abbreviation SAM stand, and in which reactions in the human body does it play a role?
- The abbreviation SAM stands for S-adenosylmethionine. SAM is one of the most important cofactors for methylation reactions in the human body.

How many main classes of enzymes are there? List the names!
- The seven main classes of enzymes include oxidoreductases, transferases, hydrolases, lyases, isomerases, ligases, and translocases.

Oxidoreductases, hydrolases, and lyases can all cleave bonds. How do their reaction mechanisms differ?
- Oxidoreductases cleave bonds by electron transfer (redox reaction), hydrolases cleave covalent bonds by the incorporation of a water molecule (hydrolysis). Lyases are all enzymes that achieve bond cleavage through other chemical means (e.g., by creating double bonds in one of the cleavage products).

What distinguishes isoenzymes like hexokinase and glucokinase in general, and what do they have in common?
- Isoenzymes differ in their structure but catalyze the same reaction; in the case of glucokinase and hexokinase, for example, the phosphorylation of glucose to glucose-6-phosphate.

### Biocatalysis

What does enzymatic specificity mean?
- Enzymatic specificity generally describes the property of an enzyme to convert the correct substrate from the numerous present substances in the correct manner. There are three aspects of enzymatic specificity: 1. substrate specificity (selective conversion of a substrate by the "lock and key principle"), 2. reaction specificity (substrate conversion only in a specific way), and 3. stereospecificity (substrate conversion only into a specific stereoisomer).

How can the activity of enzymes be indicated and what external factors does it depend on?
- The katal (kat) is the SI unit for enzyme activity. 1 kat corresponds to the amount of enzyme that converts 1 mol of substrate in 1 s under defined conditions. For enzyme activity, there are various reference quantities (e.g., the volume activity, given in kat/L). The activity of an enzyme depends on temperature, pH value, salt concentration, and the oxidative environment (e.g., molecular oxygen or transition metal ions).

Explain the Michaelis-Menten model: What does it describe and what is the formula for calculation?
- The Michaelis-Menten model describes the kinetics of enzymatic reactions. It is assumed that in the reaction enzyme (E) and substrate (S) initially form a complex (ES), which then in a second step breaks down into enzyme and product (P). The velocity of such a reaction is calculated with the formula v = vmax × c(S) / (KM + c(S)) with v = reaction velocity, vmax = maximum velocity of the reaction, c(S) = concentration of the substrate in the mixture, KM = Michaelis-Menten constant.

What is the Michaelis-Menten constant and what does it indicate?
- Quantitatively, the Michaelis-Menten constant is the quotient of the rate constants describing the breakdown of the enzyme-substrate complex divided by the rate constant describing the formation of this complex. Qualitatively, it corresponds to the substrate concentration at which half of the active sites of the enzymes involved in the reaction are occupied by substrate.

What does it mean when the vmax of an enzyme is 15 μM/s?
- vmax is by definition the enzyme concentration required to convert 1 mol of substrate in 1 s. If it is 15 μM/s, then 15 μM of the enzyme is required to convert 1 mol of substrate in 1 s.

What is a Lineweaver-Burk plot and what can be read from it?
- The Lineweaver-Burk plot is the plotting of the reciprocal of the initial reaction velocity (1/v0) against the substrate concentration (S). This relationship is always linear, so two important values can be read directly from the axis intercepts: the intersection of the line with the y-axis corresponds to the reciprocal of vmax, the intersection with the x-axis corresponds to the negative reciprocal of KM. The Lineweaver-Burk plot is therefore usually used for the practical determination of the Michaelis-Menten constant KM and the maximum velocity vmax.

### Enzyme Regulation

What is the difference between competitive and non-competitive inhibition, and what consequences arise for the inhibited enzyme in each case (argue with KM and Vmax)?
- A competitive inhibitor competes with the substrate for the same binding site on the enzyme, while a non-competitive inhibitor binds to a different site on the enzyme than the substrate. In competitive inhibition, the maximum velocity of the enzyme remains the same (vmax →), but a higher substrate concentration is needed to achieve (complete) occupancy of the active sites (KM ↑). In non-competitive inhibition, the opposite is true: the maximum velocity of the enzyme decreases (vmax ↓), but the substrate concentration required for (complete) occupancy of the active site remains the same (KM →).

How does a negative allosteric effector interact with an enzyme and what effect does it have?
- A negative allosteric effector can be seen as a subtype of non-competitive inhibitors, as it binds to the enzyme via a regulatory subunit outside the active site. The particularity of allosteric inhibition is that this binding leads to a conformational change of the enzyme, thereby reducing its reactivity.

What is generally understood by the interconversion of enzymes?
- Interconversion refers to covalent, chemical modifications of enzymes that convert them into their active form.

What are the four most important chemical enzyme modifications?
- The most important chemical modifications of enzymes are phosphorylation (transfer of Pi to the enzyme), dephosphorylation (removal of Pi from the enzyme), ADP-ribosylation (transfer of ADP-ribose groups from NAD to the enzyme), and limited proteolysis (removal of inhibitory peptide residues from the so-called proenzyme/zymogen).

What type of interconversion of the stimulatory G-protein (Gs) does cholera toxin exert its effect on?
- Cholera toxin ADP-ribosylates one of the subunits of the heterotrimeric stimulatory G-protein (Gs).