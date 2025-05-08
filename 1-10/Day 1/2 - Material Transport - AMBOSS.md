# Material Transport

## Summary

All processes in the body require the interplay of various cells. For this, they must be able to communicate with each other: Cell communication occurs both electrochemically (that is, through charges) and chemically via signaling molecules (the latter is referred to as signal transduction). Both processes require substance transport. In addition to the non-directed and energy-independent transport forms of diffusion and osmosis, there are also targeted transport processes that require energy expenditure. Generally, transport in cells means that a biological membrane (either the outer shell of the cell or the membrane of the cell compartments) must be overcome.

Biological membranes consist of lipid bilayers, which means that only small lipophilic substances can pass through them unhindered. All other substances (large molecules, hydrophilic or charged particles) require assistance from transmembrane proteins. Transmembrane proteins include channel proteins, which extend tubularly through the membrane, and the so-called "carriers" – transporters that can move back and forth within the membrane.
## Material Transport - Basics

Almost all processes in biological systems occur in aqueous solution. In a solution, each individual molecule or ion is surrounded by solvent. The amount of a dissolved substance can be expressed in several ways.

- Molarity (amount concentration): c = nsolute/Vsolvent
    - Unit: mol/L
    - c = molar concentration, n = number of particles in moles, V = volume
- Molality: b = nsolvent substance/m solvent
    - Unit: mol/kg
    - b = molality, n = number of particles in moles, m = mass
- Activity
    - Has the same properties as the molar concentration
    - Is used for real mixtures

> [!NOTE]
> The molarity is the normal concentration of substance in particles per volume of solvent, while the molality is a concentration in particles per mass of solvent!

#### Solubility Behavior of Molecules in Multiphase Systems

- Multiphase system: Consists of several non-mixed layers (= phases) with different polarity, e.g. water (polar) / oil (nonpolar)
- Concentration of dissolved molecules: Greater in the phase whose polarity better matches the polarity of the molecule.
    - Polar molecules and ions: Dissolve in polar solvents, e.g., water
    - Nonpolar Molecules: Dissolve in nonpolar solvents, e.g., oil
    - Amphiphilic Molecules: Arrange themselves at the interface between two phases, such that the polar part of the molecule extends into the polar phase and the nonpolar part into the nonpolar phase.
    - Can be described using the Nernst distribution coefficient.

> [!note]
> Similia similibus solvuntur – Like dissolves in like!

#### Diffusion

Diffusion is the self-mixing of a solution, that is, the distribution of a dissolved substance in the solvent. Thus, it is a phenomenon of material transport.

- Cause: Undirected, random thermal motion of particles
- 1. Fick's Law: The particle flux is proportional to the size of the concentration gradient and is directed opposite to it. The molecules diffuse along the concentration gradient, with the particle flux being proportional to the size of the concentration gradient.
- Effect
    - Particles diffuse from the area of higher concentration to the area of lower concentration.
    - The larger the concentration gradient, the stronger the particle flow.
- Nernst distribution coefficient: Describes the solubility of a substance in two immiscible phases (e.g. water and oil, or water and ether)
    - Formula: K = c(A in Phase 1) / c(A in Phase 2)
    - K = distribution coefficient, c = concentration of substance A

> [!note]
> In a closed system, diffusion ultimately leads to a complete elimination of concentration differences over the long term!

#### Diffusion through Membranes

Diffusion occurs not only freely in solutions but can also take place through membranes, provided they are permeable.

- Diffusion through a membrane: D = P × A × (Δc / d)
    - Unit: mol/s
    - D = diffusion rate, P = permeability coefficient, A = area of the membrane, Δc = change in concentration, d = layer thickness, Δc/d = concentration gradient
    - Sample calculation
        - A cell membrane has a permeability of 1×10−7 cm/s for the molecule tryptophan.
        - What is the diffusion rate when the concentration difference on both sides of the membrane is 500 μmol/cm3, the membrane has an area of 2 cm2, and its thickness is negligible?
            - Sought: Diffusion rate D
            - Given: Permeability P, membrane area A, concentration difference Δc
                - By substituting into the formula for the diffusion rate, we get D = P × A × Δc = 1 × 10−7 cm/s × 2 cm² × 500 μmol/cm³ = 1 × 10−4 μmol/s
                - Tryptophan is therefore transported through the membrane with a diffusion rate of 1 × 10−4 μmol/s.

> [!note]
> Even some substances for which a membrane is not permeable can "diffuse" through it if transporters like carriers or channels assist. In this case, it is referred to as facilitated diffusion. In this type of diffusion, the number of transporters is crucial for the strength of the particle flow, and the diffusion equation no longer applies!

#### Osmosis

- Osmosis: A diffusion phenomenon in semipermeable (i.e., partially permeable) membranes, where a concentration equilibrium through diffusion can only be achieved when water molecules flow from the area of lower concentration to the area of higher concentration of a dissolved substance.
- Osmolarity/osmotic concentration: Number of osmotically active particles relative to the volume of a solution.
    - Formula: $c_{osmotically} = n_{osmotically} / V_{solvent}$
        - Unit: osmol/L
        - cosmotisch = osmotic concentration; nosmotisch = number of osmotically active particles in moles (i.e., number of dissolved particles that cannot diffuse through the membrane); V = volume of the solution
    - The osmolarity of a solution depends on the number of dissolved particles and differs from molarity in its numerical value only when the dissolved substance is present in a dissociated form. For example, NaCl dissociates in solution into Na+ and Cl-, making the osmolarity in this case about twice as large as the molarity.

- Osmolality: Number of osmotically active particles relative to the mass of a solution
    - Formula: osmotic = nosmotic/solvent
        - Unit: osmol/kg
        - bosmotisch = Osmolality; nosmotisch = number of osmotically active particles in moles (i.e., number of dissolved particles that cannot themselves diffuse through the membrane); m = mass
- Osmotic pressure: Pressure of two solutions with different concentrations that are separated by a semipermeable membrane.
    - Formula: osmotic = σ × c × R × T (This equation is also called Van't Hoff's law.)
        - Unit: Pa
        - posmotisch = osmotic pressure, σ = reflection coefficient (see below), c = molar concentration of a dissolved substance, R = gas constant, T = temperature
        - Oncotic pressure: Osmotic pressure of a colloid in solution
    - Reflection coefficient σ: Describes the selectivity of a membrane for a dissolved substance.
        - σ = 0: The membrane is completely permeable
        - σ = 1: Membrane is completely impermeable
            - Semipermeable Membrane: Is permeable to the solvent water, but not to any dissolved substances (σ=1)

#### Osmosis and Cells

Biological membranes are semipermeable, which is why osmosis is an important and recurring phenomenon in medicine. The flow of water molecules to areas with high concentrations of solutes has consequences for cells and entire tissues.

- Tonicity: Measure of the gradient of osmotic pressure in two adjacent systems
    - Isotonic
        - Cell: Osmotic pressure in an isotonic cell is equal to the pressure in the surrounding medium.
        - Environment: The osmotic pressure of an isotonic environment is equal to the pressure inside the cell.
        - Effect: If a cell is placed in an isotonic medium, osmosis does not occur.
    - Hypertonic
        - Cell: Osmotic pressure in a hypertonic cell is greater than the pressure in the surrounding medium.
        - Environment: The osmotic pressure of a hypertonic environment is greater than that inside the cell.
        - Effect: If a cell is placed in a hypertonic medium, water flows out and the cell shrinks.
    - Hypotonic
        - Cell: Osmotic pressure in a hypotonic cell is less than the pressure in the surrounding medium.
        - Environment: Osmotic pressure of a hypotonic medium is lower than that in the cell.
        - Effect: When a cell is placed in a hypotonic medium, water flows into the cell; in extreme cases, the cell may burst.
            - Protective mechanism: The potassium-chloride symporter transports K+ ions and Cl− ions out of the cell, thereby reducing osmotic pressure to prevent lysis.

> [!note] Edema
> Edema is the accumulation of water in the tissue, which occurs when fluid leaks from the capillaries into the interstitium. The flow of fluid is actually controlled by a balance between hydrostatic pressure in the capillaries and oncotic pressure between the vessel and the interstitium: While hydrostatic pressure promotes the release of fluid into the interstitium, oncotic pressure retains the fluid in the vessels. Causes of edema formation are therefore either too high hydrostatic pressure, too low oncotic pressure in the capillaries, or too high oncotic pressure in the tissue. See also: Edema and structure and function of blood vessels.

> [!note] Osmotic Diuresis
> Osmosis principles also play a role in the excretion of fluids from the body. When too many osmotically active substances are dissolved in the urine (e.g., sugar), it leads to dilution through increased excretion of water. This phenomenon is known as a symptom of diabetes mellitus and is also utilized in the context of treatment with diuretics.

## Transport into or out of cells

Biological membranes are lipid bilayers, thus chemically representing a very nonpolar environment. According to the laws of solubility (see above), they are permeable to nonpolar molecules such as carbon dioxide or steroid hormones, but not to charged ions, polar molecules like sugars, or particularly large molecules. For such substances, the cell relies on controlled transport processes. Here, a distinction is made between membrane-displacing transports, in which parts of the cell membrane are co-transported, and membrane protein-mediated transports, in which the transports are carried out by specialized membrane proteins (e.g., channels).


## Membrane-shifting Transport

In membrane-shifting transports, parts of the cell membrane or the membrane of organelles are pinched off as vesicles, containing the substance to be transported. This is also referred to as vesicular transport. The transport into cells is called endocytosis, while the transport out of cells is referred to as exocytosis. In transcytosis, substances are first taken up by endocytosis, passed through the cell, and then released again by exocytosis. These membrane-shifting transport forms are regulated by a specific group of G-proteins, known as Rab proteins, which ensure that the vesicles reach the correct location.

### Endocytosis

Endocytosis is the process by which molecules are engulfed by cells. There are three types: pinocytosis, phagocytosis, and receptor-mediated endocytosis. What they all have in common is that the particles to be taken up ultimately arrive in vesicles inside the cell. However, the mechanisms are each very different.

#### Phagocytosis

Phagocytosis can only be performed by specialized so-called phagocytic cells, such as macrophages or dendritic cells. These have special opsonin receptors that can bind so-called opsonins. During phagocytosis, large molecules and even small cells can be taken up.

- Process
    1. Binding of a particle labeled with opsonins to the opsonin receptor of the phagocytic cell.
    2. Formation of pseudopodia during phagocytosis: Extension of the cell membrane outward until it completely surrounds the particle.
    3. Pinching off the cell membrane and formation of a phagosome, that is, a large endocytic vesicle

#### Pinocytosis

Pinocytosis refers to the uptake of medium-sized dissolved molecules. Unlike phagocytosis and receptor-mediated endocytosis, no receptor is involved in pinocytosis: it occurs spontaneously and can be performed by all cells.

- Process
    1. "Spontaneous" invagination of the cell membrane to engulf the molecule to be taken up
    2. Actin is involved in the invagination of the membrane and the formation of vesicles (so-called actin remodeling) inside the cell.
    3. Tying off the vesicle inward

#### Receptor-mediated endocytosis

In receptor-mediated endocytosis, small to medium-sized particles are taken up into the cell with the help of a membrane-bound receptor. It plays an important role, for example, in cholesterol metabolism, in the uptake of LDL, or in the uptake of transferrin-bound iron.

- Process
    1. Binding of the ligand to specific receptors, which in turn interact with adaptins.
    2. Invagination of the membrane, intracellular accumulation of clathrin molecules
    3. Invagination of the membrane around the ligand to be transported and its receptor
    4. Pinching off a vesicle into the interior of the cell by the protein Dynamin
    5. Fusion of the vesicle with the early endosome
    6. Acidic environment causes the ligand to dissociate from the receptor.
    7. Release of the receptor towards the cell membrane ("Recycling")
    8. Release of the ligand to the lysosome or Golgi apparatus by fusion with the endosome

### Exocytosis

During exocytosis, medium to very large molecules are released into the cell environment.

- Process
    1. Incorporation of the molecule to be delivered into a vesicle in the Golgi apparatus
        - The vesicles are surrounded by a simple lipid bilayer and additionally contain specific coat proteins depending on the section in the secretory or exocytosis pathway.
            - Example: Vesicles coated with Coat Protein Complex-2 (COP2) proteins transport substances from the rough ER to the cis-Golgi apparatus.
    2. Fusion of this vesicle with the cell membrane
    3. Release of the molecule on the outside of the membrane
- Regulation: Often via an increase in intracellular calcium concentration or receptor-mediated
- Special form of apocytosis (apocrine secretion): Cellular contents are pinched off together with a part of the cell membrane and released as vesicles into the environment (similar to endocytosis)

### Transzytosis

Transcytosis is a receptor-dependent transport of an extracellular molecule through a cell (a combination of endocytosis and exocytosis). It plays a role especially in cell associations where the intercellular spaces are blocked by tight junctions, such as in the enterocytes of the intestine.
## Membrane Protein-Mediated Transport

### Transport through Membrane Proteins

Membrane-displacing transport processes are primarily used when the substances to be transported are very large. The transport of small molecules or ions that need to be relocated quickly typically occurs through membrane proteins. Two different types of membrane proteins are distinguished: channel proteins and carrier proteins.

- Passive Transport: Occurs without expenditure of energy
    - Diffusion
    - Osmosis
- Active Transport: Occurs only with the expenditure of energy
    - Primary: Transport linked to energy carriers like ATP
    - Secondary: Transport coupled to a concentration gradient

#### Channel Proteins

Channels are stationary transmembrane proteins that form a water-filled pore and are responsible for the transport of very small particles.

- Function mechanism
    - Are either permanently open or are opened by a specific stimulus
        - Voltage-dependent channels: Open in response to a change in the membrane potential
            - Are only open for a few milliseconds
            - Then enter a short non-activatable sleep state
            - And finally back into the activatable sleep mode
        - Ligand-dependent channels: Open when a specific ligand binds to them.
    - Selection filter: Narrow sections in the channel that ensure that the channel is specific for certain particles.
        - Example of a voltage-dependent potassium channel
            - Only dehydrated K+ ions fit through the funnel-shaped potassium channel → The energetically costly dehydration of K+ ions is facilitated by interactions with molecules of the potassium channel → Dehydrated K+ ions can pass through the channel
            - Na+ ions with a hydration shell also cannot pass through the potassium channel → Na+ ion is smaller than K+ ion and thus cannot interact with the potassium channel → Dehydration is too energy-consuming → Virtually no passage of Na+ ions
        - Example aquaporins: Transmembrane proteins
            - Speed: Up to 3 billion molecules per second
            - Function: Water transport through biomembranes

#### Carrier proteins

Carrier proteins (also: transporters) are very flexible membrane proteins that take up the substances to be transported and move back and forth in the membrane like a shuttle.

- Classification
    - By the number of materials to be transported and the direction of transport
        - Uniport: Only one substance is transported in a specific direction.
        - Symport: Two substances are transported simultaneously in one direction.
        - Antiport: Two substances are transported in opposite directions.
    - By transport mechanism
        - Primary active transport
        - Secondary Active Transport

##### Primary Active Transport

In primary active transport, energy from energy carrier molecules such as ATP is used to induce the conformational change in ion pumps necessary for transport. These are transmembrane proteins, of which we will present three important representatives below.

- Na+/K+-ATPase (=Sodium-Potassium-ATPase): Antiport
    - Transport process: 3Na+intracellular + 2K+extracellular + ATP + H2O → 3Na+extracellular + 2K+intracellular + ADP + Pi
    - Localization: Outer cell membrane
    - Function
        - Osmotic control: Water content in the cell is regulated by lowering the intracellular Na+ concentration. This prevents the fluid in the intercellular space from becoming hypotonic and water from flowing into the cell.
        - Establishment of a concentration gradient
            - For secondary active transport
            - For electrochemical cell communication (see → resting and action potential)
    - Mechanism
        1. Membrane protein opened inward → binds 3 sodium ions
        2. Intracellularly, ATP binds.
        3. ATP is hydrolyzed to ADP and phosphorylates the sodium-potassium ATPase → Conformational change: Membrane protein is now opened outward
        4. Sodium ions flow out
        5. 2 Potassium ions flow into the membrane protein and dephosphorylate it → Conformational change: Membrane protein is now opened back inward
        6. Potassium ions leave the membrane protein towards the cytosol.
- Ca2+-ATPase (=Calcium-ATPase): Uniport
    - Localization: Plasma membrane and sarcoplasmic reticulum
    - Function: Lowers the cytosolic Ca2+ concentration
- H+/K+-ATPase (=Proton-Potassium-ATPase): Antiport
    - Transport process: K+Lumen + H+Cytoplasm + ATP + H2O → K+Cytoplasm + H+Lumen + ADP + Pi
    - Localization: Parietal cells in the stomach
    - Function: Acid secretion in the stomach

> [!note]
> Natri out, Kali in – Sodium is transported extracellularly by the Na+/K+-ATPase, potassium into the cell interior!

> [!note] Stomach ulcers (ulcers)
> Stomach ulcers are defects in the stomach wall that can affect all layers of the wall depending on the severity. They arise, for example, from a chronic inflammation or from excessive production of stomach acid. Therapeutically, one targets the H+/K+-ATPase of the parietal cells, which is responsible for the low pH of stomach acid. Active substances such as Omeprazole irreversibly inhibit the H+/K+-ATPase, thereby preventing further production of stomach acid. Therefore, these medications are also referred to as proton pump inhibitors.

#### Secondary Active Transport

In secondary active transport, energy from concentration gradients, which are established by primary active transport processes such as the Na+/K+-ATPase, is converted into transport work.

- Concentration gradient: The concentration difference of a dissolved substance that occurs at membranes between different cellular compartments or between the intra- and extracellular space.
    - A concentration gradient represents an "ordered" system in which energy is stored that can be converted into work (see: entropy).
        - Construction of the gradient
            - Process "requires" energy; this is provided by ATP (primary active transport processes)
        - Decrease of the gradient
            - Process "delivers" energy, i.e. it can be used, for example, for the synthesis of ATP from ADP and Pi.
- Examples of secondary active transporters
    - Glucose transporter (SGLT1): Symport
        - Transport process: GlucoseLumen + 2Na+Lumen → Glucoseintracellular + 2Na+intracellular
            - Energy for transport comes from the breakdown of the Na+-gradient.
        - Localization: intestinal epithelial cells (membrane on the luminal side)
        - Function: Uptake of glucose and galactose from the intestine
    - ATP-Synthase
        - Transport process: ADP + Pi + H+(outside) → ATP + H2O + H+(inside)
            - Energy for the condensation reaction comes from the breakdown of the H+-gradient.
        - Localization: Inner mitochondrial membrane
        - Function: Enzyme that catalyzes the formation of ATP

> [!note]
> Primary active transport requires direct energy in the form of ATP. Secondary active transport utilizes concentration gradients established by primary active transporters, resulting in an indirect ATP consumption!

> [!note] Cystic fibrosis
> There are a variety of diseases caused by channel malfunctions. The most well-known example is cystic fibrosis, which involves a malfunction of the chloride channels. As a result, chloride ions can no longer be transported extracellularly, which also osmotically reduces the secretion of water from the cells. This particularly impairs the function of the excretory cells – resulting in increased secretion viscosity. The secret produced by the glands is therefore far too dry, viscous, and slimy. This is noticeable, for example, in the bronchi, where the slimy secretion cannot be coughed up and constantly causes severe infections of the bronchi and lungs.

#### Tertiary Active Transport

- Definition: Transport using a concentration gradient generated by a secondary active transporter
    - Examples
        - ECaC
        - Peptide transporter 1

## Transport in Cell Clusters

In tissues, there is a continuous substance transport between neighboring cells. This can occur either through the spaces between the cells (paracellular), through gap junctions (intercellular), or through transcytosis.

- Paracellular Transport
    - Mechanism
        - Transport within an epithelium exclusively through the spaces between the cells
        - Primarily plays a role in epithelia
    - Regulation: Is regulated by the density of the closing strands of the tight junctions between the cells.
        - Epithel tissues: Poorly developed tight junctions, paracellular transport is quite possible
            - Occurrence: Proximal tubule of the kidney, small intestine
            - Special driving force: Solvent Drag: In paracellular water transport, dissolved particles are "dragged along".
        - Relative density epithelia: Paracellular transport plays a rather minor role.
            - Occurrence: Blood-brain barrier
        - Impermeable barriers: Paracellular transport is not possible
            - Occurrence: Epidermis
- Intercellular Transport: Transport between adjacent cells via Gap Junctions
    - Occurrences: e.g. cardiac muscle cells (see also: cardiac electricity), epithelial cells (see also: regulation of gastrointestinal motility), and glial cells
- Transcellular Transport: Transport through a cell via transcytosis

## Substance Transport in the Body

The transport of substances between different organs in the body relies on the systems of the circulatory system, lymphatic system, and lungs (for gases). The transport functions are discussed there; see: Structure and function of blood vessels (Function: substance exchange), Lymphatic system (The lymphatic vessel system), and lungs (Function of the lungs).
## Review Questions for the Chapter on Material Transport
### Material Transport - Basics

The diffusion rate of a molecule across a membrane depends on which three physical quantities?
- The diffusion rate of a molecule through a membrane depends on the permeability (= permeability) of the membrane for this molecule, the membrane area, and the concentration gradient of the molecule across the membrane. Numerical values for the diffusion rate can therefore be calculated as the product of these three quantities.

How does osmosis work?
- Osmosis refers to the transport of liquids across a semipermeable membrane to equalize different concentrations of dissolved, osmotically active substances on both sides of this membrane. The transport takes place from the side with the lower concentration to the side with the higher concentration of the dissolved substance.

What is the so-called "osmotic pressure" and how can it be calculated?
- Osmotic pressure describes the pressure that arises when two solutions of different concentration are separated from each other by a semipermeable membrane. It originates from the dissolved particles that cannot diffuse through the membrane and serves as the driving force for osmosis. The osmotic pressure is proportional to the concentration of the particles: the higher the concentration on one side of the membrane, the higher the osmotic pressure. It can be calculated using Van't Hoff's equation as the product of the reflection coefficient (indicating the permeability of the membrane), the concentration of the osmotically active substance, the gas constant, and the temperature prevailing in the system.

Describe the biochemical significance of the K+/Cl− symporter.
- The potassium-chloride symporter transports K+ and Cl− ions out of the cell and thus reduces the osmotic pressure to prevent cell lysis.

### Membrane-Transport

How does receptor-mediated endocytosis proceed?
- In receptor-mediated endocytosis, the substance to be taken up first binds externally to a specific receptor. The membrane invaginates, and intracellularly, clathrin molecules attach to the corresponding membrane section. The membrane completely folds inward there and encloses the substance to be transported. With the help of the protein Dynamin, the invagination is pinched off as a vesicle. The vesicle can now migrate as an endosome within the cell to the target location of the substance and release it there.

Name two examples of particles that are taken up through receptor-mediated endocytosis.
- Medium-sized particles such as LDL and transferrin-iron complexes are taken up into the cell via receptor-mediated endocytosis.

What is transcytosis and in which cells can it be found, for example?
- Transcytosis is described as the receptor-dependent transport of an extracellular molecule through a cell. Transcytosis thus includes both endo- and exocytosis of the respective substance. Transcytosis is primarily found in cell associations whose cells are isolated from each other by tight junctions. An example is the enterocytes of the intestine.

### Membrane Protein-Mediated Transport

What physiological functions are performed by the sodium-potassium ATPase?
- The sodium-potassium ATPase maintains the concentration gradient of sodium and potassium ions at biomembranes. This gradient is needed, on the one hand, for electrochemical signal transmission in nerve cells and, on the other hand, serves as an energy source for secondary active transport processes in many different cells of the body. Additionally, among other things, the intracellular Na+ concentration controls the osmotic regulation of cell tonicity to prevent cells from bursting.