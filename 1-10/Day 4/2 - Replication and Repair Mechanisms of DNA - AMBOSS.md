# Replication and Repair Mechanisms of DNA
## Summary

During cell division, the entire DNA must be duplicated so that one cell produces two daughter cells with identical genetic material. The duplication of DNA (DNA replication) requires that the double helix structure of the DNA be locally unwound. On each single strand, specific proteins (including DNA polymerases) can then synthesize a complementary daughter strand. Two double strands are formed, each composed of one old and one new strand.

The DNA is present in the cell nucleus bound to proteins and is very densely packed. For replication, but also for reading the genes, this packaging is temporarily loosened. This process is strictly regulated.

DNA replication involves control mechanisms to keep the genetic information as stable as possible, but errors still occur. For example, incorrect bases can be incorporated. External influences as well as processes within the cell lead to changes in the chemical structure of the DNA. It is therefore important that repair mechanisms exist to ensure a sufficient level of stability of the genome. Mispaired bases are cut out and replaced by specialized enzymes. Even breaks in the double strand can be repaired with a certain degree of accuracy. If a DNA damage is not repaired, it leads to a mutation in the genome.

## Basics of DNA Replication

Before each cell division, the complete set of chromosomes in the nucleus must be exactly duplicated. This process is referred to as DNA replication, during which two identical sister chromatids of each chromosome are formed. The building blocks for DNA synthesis (as well as for RNA synthesis) are nucleoside triphosphates. The energy for the synthesis comes from the cleavage of the phosphoanhydride bond between the α- and β-phosphate groups of these nucleotides.

- Definition: Creation of a copy of a DNA double strand during cell division (in the S phase of the cell cycle)
- Goal: After cell division, each daughter cell contains the identical genetic information.
- Properties of the replication mechanism
    - Semiconservative
        - The DNA double strand is split into two single strands (formation of a replication fork)
        - Each single strand serves as a template for the synthesis of a complementary new strand
        - The result of replication is two identical double-stranded DNA molecules, each consisting of one old (parental strand) and one newly synthesized daughter strand.
    - Bidirectional
        - Replication goes in two directions
        - At the point where the DNA double helix is unwound, two "active" replication forks are formed.

The direction of DNA replication runs from 5'→3'. This means that the next nucleotide is attached to an already existing single strand with a free 3' OH group!

## Process of DNA Replication

The DNA replication is divided into three phases: Initiation, Elongation, and Termination. A variety of different enzymes are involved.

### Proteins Involved in DNA Replication

|Involved Proteins|Function|Prokaryotes|Eukaryotes|
|---|---|---|---|
|Helicase|Unwind local sections of the DNA double helix (ATP-dependent reaction)|DnaB|Mcm complex|
|Topoisomerase|Unwinding supercoiled DNA or altering its spatial structure|Topoisomerases I and II (Gyrases)|Topoisomerases I and II|
|Single-strand binding proteins|Preventing the direct reassociation of separated single strands|SSB (Single Strand Binding Protein)|RPA (Replication Protein A)|
|Primase (DNA-dependent RNA polymerase)|Synthesis of RNA primers|Primase (DnaG)|Primase activity as part of DNA polymerase α|
|DNA-dependent DNA polymerases|Extend the RNA primer by about 50–100 nucleotides|∅|Polymerase α|
|Synthesis of the Lagging Strand|Polymerase III|Polymerase δ|
|Synthesis of the Leading Strand|Polymerase ε|
|Removal of the primer|RNase H and Polymerase I (their 5'→3' exonuclease activity)|RNase H and FEN-1 (Flap Endonuclease 1)|
|Filling the gap after removing the primer|Polymerase I|Polymerase δ|
|Gleitring (Clamp)|Anchoring of Polymerase on DNA|β-Subunit of Polymerase III|PCNA (Proliferating Cell Nuclear Antigen)|
|Ligase|Linking the newly synthesized DNA fragments (ATP- or NAD+-dependent reaction)|DNA ligase|DNA ligase|
|Telomerase|Ensures the complete replication of the ends of linear chromosomes|∅|Telomerase|

> [!note] Gyrase inhibitors
> Gyrase inhibitors are substances that inhibit bacterial topoisomerase II. They inhibit both the initiation of DNA synthesis and the separation of the two daughter chromosomes into the two new cells after termination. Therefore, they are used as antibiotics (e.g., ciprofloxacin, nalidixic acid).

### 1. Initiation

- Definition: Beginning of DNA replication
- Involved enzymes: Including helicase, topoisomerases, single-strand binding proteins
- Process
    1. Specific proteins recognize and bind at the "ori" (Origin of Replication), a specific DNA segment in the genome.
    2. A helicase begins at the ori with the ATP-dependent separation of double-stranded DNA into single strands.
    3. Topoisomerases unwind the DNA and change its spatial structure (the so-called topology)
        - Topoisomerase I
            - Splits one of the two DNA strands
            - Does not require ATP
        - Topoisomerase II
            - Temporarily separates both DNA strands for larger structural changes of the DNA
            - Requires ATP
    4. The Replication Protein A (RPA) binds to the single strand and prevents the two single strands from rejoining.

### 2. Elongation

- Definition: DNA Synthesis Phase
- Involved proteins: Including primase, DNA polymerase, ligase
    - Replisome: Complex at the origin made up of DNA polymerase and other proteins that travels with the replication fork.
    - Clamp: A subunit of DNA polymerase that is responsible for anchoring the DNA polymerase onto the DNA by encircling it.
- Process
    1. Primer synthesis
        - Primer: Short RNA piece, 5–10 nucleotides long, that is synthesized by a primase (DNA-dependent RNA polymerase) complementary to the template strand.
    2. DNA Synthesis
        - Synthesis mechanism
            - Principle: Attaching the next complementary deoxynucleotide (dATP, dGTP, dCTP, or dTTP) to the free 3'OH group of the DNA strand to be extended (formation of an ester bond!)
            - Details
                1. DNA polymerase forms the ester bond: It catalyzes the nucleophilic attack of the 3'OH group on the α-phosphate of the deoxyribonucleoside triphosphate to be added.
                2. The single strand is elongated by one nucleotide.
                3. Pyrophosphate (PPi) is released.
                4. Pyrophosphate is then cleaved by a pyrophosphatase into two phosphates.
            - Consequence of the mechanism and direction of synthesis as well as DNA structure
                - DNA replication occurs continuously only on the single strand that has a free 3'OH end (leading strand).
                    - Only one primer is needed for the main strand.
                - On the other single strand (lagging strand), polymerization also proceeds in the 5'→3' direction!
                - Okazaki fragments: In order for replication to occur simultaneously on both strands, the lagging strand is synthesized discontinuously, i.e., in segments.
                    - A specific primer is required for each of these DNA sections.
                    - The primer is synthesized at the replication fork.
    3. Proofreading: Some polymerases have a 3'→5' exonuclease activity and remove incorrectly paired nucleotides.
    4. Removal of the primers: The activity of RNase H and a 5'→3' exonuclease activity of prokaryotic DNA polymerase I or the enzyme FEN-1 (Flap Endonuclease 1) in eukaryotes are necessary to completely remove the RNA primers.
    5. Filling the gaps: DNA polymerase fills the gaps with nucleotides complementary to the parent strand until the free ends meet.
    6. Connecting the ends
        - A ligase connects (ligates) the free ends of the newly synthesized daughter strand.
        - Ligase reaction
            1. The ligase transfers an AMP residue to the 5'-phosphate end of one of the DNA fragments to be joined.
            2. AMP is cleaved off and the 5'-phosphate end is connected to the 3'OH end of the other fragment.

> [!note]
> Topoisomerase I cleaves one DNA strand and does not require ATP, while Topoisomerase II cleaves both DNA strands and requires ATP for this!

> [!note]
> During DNA synthesis, a nucleophilic attack occurs where the 3'OH group of the existing DNA strand targets the α-phosphate of the incoming deoxyribonucleoside triphosphate!

### 3. Termination

- Definition: Termination of DNA replication when two replication bubbles meet. There are different termination mechanisms for circular and linear DNA molecules.
- Mechanism: The stop of replication is triggered by termination proteins binding to so-called termination sequences.

## Telomere

Telomeres are the ends of linear human chromosomes. They do not code for structural genes but protect against their loss. However, with each cell division, telomere length decreases in somatic cells, resulting in these cells having a limited lifespan. Therefore, telomeres are associated with the process of cellular aging.

- Definition: Non-coding DNA segments consisting of some 1,000 base pairs at the ends of linear chromosomes, which in humans are made up of sequence repeats of six nucleotides.
- Function: Prevent the loss of structural genes during the replication of linear DNA double strands.
    - The guiding strand can be completely synthesized.
    - The 5' end of the complementary strand becomes shorter.
- Telomerase
    - Synthesizes DNA based on the template of an RNA
    - Special DNA polymerase with its own RNA template (ribonucleoprotein), found in rapidly dividing cells (e.g., a large proportion of tumor cells) that can extend telomeres.
    - Reverse Transcriptase: It extends the 3' end of the parent strand, so that the 5' end does not shorten during replication.

## Mechanisms of DNA Damage

During DNA replication, errors occur. Furthermore, DNA is not completely chemically stable: some bonds are susceptible to spontaneous changes. Additionally, DNA damage can occur from external influences (chemical or physical noxae). All of this can be causes of mutations, i.e., changes in the genome of a cell. The stored genetic information is altered, resulting in a changed phenotype. For the individual, mutations are undesirable and are repaired when possible. However, on the other hand, mutations are also the basis for evolution. They allow a population to better adapt to external circumstances when more adapted individuals arise.

### Endogenous Causes of Errors in the DNA Sequence

- Replication errors
    - Repetitive Sequences: DNA polymerase is prone to errors when reading repetitive DNA sequences. In particular, in so-called triplet repeats, it occurs that the repetitive region is read multiple times.
    - Keto-Enol Tautomerism: The very rarely occurring enol form of thymine pairs with guanine instead of adenine.
- Chemical instability
    - Depurination: Thermal cleavage of the N-glycosidic bond between deoxyribose and purine base even at body temperature.
        - An AP site is created (a general term for an apurinic site, but also an apyrimidinic site)
        - AP sites are among the most common physiologically occurring DNA lesions (their number is estimated to be >10,000 per day per cell in eukaryotes)
    - Damage caused by radicals: For example, highly reactive oxygen or hydroxyl radicals that induce oxidative stress.
        - Example: Guanosine → 8-Oxo-Guanosine
            - Consequence: During replication, 8-Oxo-Guanosine pairs with Adenine instead of Cytosine.
    - Spontaneous oxidative desamination
        - Examples
            - Deamination of 5-methylcytosine to thymine
                - As a result: During replication, thymine pairs with adenine instead of 5-methylcytosine with guanine.
            - Deamination of cytosine to uracil (e.g., as a result of nitrite intake from food)
                - Follow
                    - Normally, uracil is recognized as incorrect and is replaced by cytosine through base excision repair.
                    - If this does not happen, uracil pairs with adenine instead of cytosine with guanine during the next replication.

> [!note] Huntington's Chorea (Dance of Veit)
> Huntington's chorea is a trinucleotide repeat disorder in which the nucleotide sequence -CAG- in the gene for the protein huntingtin is increased well beyond the average number (9 to 35 repeats of the triplet). The genetic alteration can be detected using PCR. The longer the DNA replicated in the PCR, the more triplets are present on the gene. CAG encodes for the amino acid glutamine, which is often incorporated consecutively into the protein in affected individuals, leading to protein aggregation in the brain. The most striking symptoms of this neurological disorder are sudden, uncontrollable movements, such as those of the fingers (piano-playing movements) and of the face.

### Exogenous Causes of Errors in the DNA Sequence

- Chemical Noxious Substances
    - Alkylating substances
        - Chemical compounds that covalently modify DNA by alkylating (methylating or ethylating) bases so that they pair with different bases than usual.
            - For example, O6-ethylguanine is formed by alkylation from guanine and pairs with thymine instead of cytosine.
        - For example, many components of tobacco smoke have a carcinogenic effect in this way.
        - Other examples: mustard gas, dimethylnitrosamine, dimethyl sulfate
    - Intercalating substances: Chemical compounds that insert themselves between the stacked bases in DNA.
        - Consequence
            - Replication stops
            - Risk of strand breaks increases
        - Examples: Ethidium bromide, Acridine dyes, Actinomycin D
- Physical Noxae
    - UV radiation
        - Energetic radiation, e.g. UVB radiation, which can cause adjacent pyrimidine bases to form dimers.
        - Most of the time, these are thymine dimers, between which a cyclobutane ring forms.
        - Replication stops at this point
    - Ionizing radiation
        - High-energy radiation that can lead to single and double strand breaks in DNA
        - Furthermore, there is an increased formation of radicals, such as oxygen and hydroxyl radicals, which can chemically alter the bases.

> [!note]
> Typical causes of DNA damage:  
> Deamination of cytosine to uracil → Uracil then pairs with adenine!
> UV radiation → thymine dimers!  
> Ionizing radiation → Radical formation → DNA damage!

## Mechanisms of DNA Repair

Despite errors in DNA repair and DNA damage from endogenous and exogenous toxins, the spontaneous mutation rate is only 1×10-9, meaning that on average one in a billion bases is altered per cell division. The reason for this is, on one hand, the proofreading function of some DNA polymerases, which directly correct errors during DNA replication in the vast majority of cases. On the other hand, there are specific DNA repair mechanisms that ensure that the base sequence remains relatively stable. The cell's/organism's ability to repair DNA damage is largely based on the sequence information from the intact DNA strand.

### Mismatch Repair

Mismatch = Base pairing error, i.e., an incorrect nucleotide has been incorporated

- Definition: The mismatch repair system corrects errors that were not fixed by the proofreading function of the polymerase during DNA replication, even while replication is taking place.
- Enzyme: MSH, MLH, Exonuclease I, DNA Polymerase δ, DNA Ligase
- Mechanism
    1. Recognition of mismatch (by MSH in eukaryotes, by MutS and MutL in E. coli)
    2. Cutting of the defective DNA daughter strand by an endonuclease (MLH in eukaryotes, MutH in E. coli)
    3. Removal of the erroneous nucleotides by exonuclease
    4. Filling the gap with the polymerase
    5. Connecting the ends with the ligase

### Direct Repair of Bases

- Definition: Repair of damaged base (not its replacement)
- Mechanism 1
    - Photolyase cleaves UV light and FADH-dependent thymine dimers.
    - This enzyme is not found in mammalian cells, but only in certain bacteria and lower eukaryotes.
- Mechanism 2
    - O6-Alkylguanine-DNA-alkyltransferase is capable of converting O6-alkylguanines (O6-methylguanine and O6-ethylguanine) back into guanine.
    - The enzyme is irreversibly inactivated.

### Base Excision Repair

- Definition: Removal of deaminated or oxidized bases by cutting out the erroneous deoxyribonucleotide.
- Enzyme: DNA glycosylase, AP endonuclease, phosphodiesterase, DNA polymerase β, DNA ligase
- Mechanism
    1. Recognition of the damaged base by DNA glycosylase and removal of the base (by cleavage of the N-glycosidic bond between the base and deoxyribose) → AP site
    2. Removal of the deoxyribose phosphate by AP endonuclease and phosphodiesterase (by cleaving the phosphodiester bonds with which the deoxyribonucleotide is incorporated into the DNA backbone at the 3' and 5' ends)
    3. Filling the gap by the polymerase
    4. Connecting the ends with the ligase

### Nucleotide Excision Repair

- Definition: Repair of DNA damage that alters the spatial structure of DNA (e.g., in the formation of thymine dimers) by excising several nucleotides.
- Enzyme: Protein complex for the recognition of DNA damage, transcription factor TFIIH (helicase activity), endonucleases, DNA polymerase δ and ε, DNA ligase
- Mechanism
    1. Detection of the altered DNA structure
    2. Separation of the double-stranded DNA into single strands by TFIIH (approximately over a sequence of 25 base pairs)
    3. Cutting out an approximately 30 base pair long oligonucleotide from the faulty DNA daughter strand by endonucleases
    4. Filling the gap by the polymerase
    5. Connecting the ends with the ligase

> [!note] Xeroderma pigmentosum
> In this rare skin disease, due to a defect in the nucleotide excision repair system, the skin is extremely sensitive to light. If sunlight is not completely avoided, it leads to pigmentation shifts and eventually the development of tumors.

### Repair of Double Strand Breaks

- Definition: Repair of breaks in both DNA strands that threaten the stability of the genome, e.g., due to ionizing radiation or the formation of radicals in cellular metabolism.
- Prerequisite: Binding of a protein complex to the exposed chromosome ends → Activation of the protein kinase ATM (Ataxia Telangiectasia Mutated) → Activation of p53 → Halting of the cell cycle

|Mechanisms|Homologous Recombination|Non-homologous End Joining|
|---|---|---|
|Definition|Repair by exchange of homologous segments between two DNA molecules (sister chromatids)|Repair by joining two DNA fragment ends|
|Time Point in the Cell Cycle|Late S-Phase or G2 Phase|Possible at Any Time|
|Flawless Repair|Yes, because the defect can be repaired using the complementary strand in the sister chromatid|No, highly error-prone, as there is no error-free template available|

> [!note] BRCA1 and BRCA2
> Many proteins are involved in the repair of double-strand breaks. Important for homologous recombination are, among others, the proteins BRCA1 and BRCA2. Mutations in the genes for these proteins are associated with a significantly increased risk of developing breast cancer.

## Review Questions on the Chapter Replication and Repair Mechanisms of DNA
### Basics of DNA Replication

What is meant by DNA replication and what principles underlie it?
- DNA replication refers to the doubling of a cell's chromosome set. For each chromosome, an identical DNA double strand is synthesized. DNA replication proceeds semi-conservatively, meaning the double strand is separated into two single strands and each single strand serves as a template. The resulting strand, therefore, consists of one old so-called parent strand and one new so-called daughter strand. Additionally, replication occurs bidirectionally on the leading and lagging strands respectively in the 5'→3' direction.

### Process of DNA Replication

In what phases can replication be divided?
- Replication begins at the so-called replication origin – the "ori" (Origin of Replication).

At which point in the genome does replication begin?
- Replication begins at the so-called replication origin – the "ori" (Origin of Replication).

What is the role of Proliferating Cell Nuclear Antigen (PCNA) during DNA replication?
- Proliferating Cell Nuclear Antigen (PCNA) is a subunit of DNA polymerase. It encircles the DNA double strand ring-like and thus anchors the polymerase onto the DNA, which speeds up the replication process.

Which enzyme catalyzes the separation of the DNA double strand during DNA replication?
- Helicase binds at the ori and begins the ATP-dependent breaking of hydrogen bonds, whereby the double strand is separated into two single strands.

What is the difference between Topoisomerase I and II?
- Both classes of topoisomerases change the spatial structure of DNA by, for example, unwinding it so that the torsional stress in the molecule does not become so great that strand breaks occur. Topoisomerase I cleaves one DNA strand ATP-independently, whereas Topoisomerase II cleaves both DNA strands temporarily in an ATP-dependent manner. The latter becomes active during larger structural changes.

Describe the DNA synthesis mechanism!
- After the formation of an RNA primer by primase, DNA polymerase catalyzes the nucleophilic attack of the free 3'OH group on the α-phosphate of the deoxyribonucleoside triphosphate to be attached, thereby extending the single strand by one nucleotide and releasing pyrophosphate. This is subsequently split into two phosphates by pyrophosphatases.

What are Okazaki fragments?
- DNA replication always proceeds in the 5'→3' direction. Since both DNA strands are replicated simultaneously and the replication fork only moves in one direction, one DNA strand must be replicated discontinuously. Individual, disconnected fragments (so-called Okazaki fragments) are formed, which are later joined by a ligase.

How are the missing ester bonds in the DNA backbone formed at the end of DNA replication?
- After DNA polymerase has filled the gaps caused by the removal of RNA primers, ligase transfers an AMP residue to the 5'-phosphate end of one of the DNA strands to be joined. By splitting off AMP, the energy to connect the 5'-phosphate end with the 3'OH end is provided, thus forming an ester bond.

### Telomere

What are telomeres?
- Telomeres are non-coding DNA segments of a few thousand base pairs at the ends of chromosomes. They prevent the coding regions for structural genes from being shortened and lost when the primer at the daughter strand (5'-end) is removed.

What is the function of telomerase?
- Telomerase is a special DNA polymerase that has a short RNA bound to it. This RNA is complementary to the telomere sequence and serves as a template for its extension after replication. It is thus a reverse transcriptase because it synthesizes DNA based on an RNA template.

### Mechanisms of DNA Damage

How can UV radiation cause damage to the DNA sequence?
- High-energy radiation, including UV radiation, can lead to the formation of dimers between two adjacent pyrimidine bases. Thymines are commonly affected, between which a cyclobutane ring forms.

What happens during the oxidative deamination of DNA bases? Name examples!
- Spontaneous oxidative deamination represents an endogenous cause of DNA sequence errors. For example, the deamination of cytosine to uracil (by nitrite) leads to incorrect base pairing: uracil pairs with adenine instead of cytosine pairing with guanine.

### Mechanisms of DNA Repair

What role does DNA glycosylase play in base excision repair?
- DNA glycosylase recognizes and removes defective or "damaged" bases caused by deamination or oxidation during base excision repair. Subsequently, further enzymes remove the remaining deoxyribose phosphate and fill the gap with the correct base.

Which repair mechanism is activated for pyrimidine dimers?
- Pyrimidine dimers, like other DNA damages that alter the spatial structure, are repaired by nucleotide excision, i.e., several nucleotides are cut out and replaced.