# Biochemical Laboratory Methods
## Summary

In medical and bioscientific basic research, various laboratory methods are employed. Many of these are also used in the diagnosis and therapy of diseases, e.g., for pathogen detection, genotype determination, or for the recombinant production of therapeutic proteins. An important method of molecular biology is the polymerase chain reaction (PCR). It serves the simple and very specific amplification of sections of double-stranded DNA. This allows, for example, the detection of bacteria in patient material during infections. Another example of the application of methods of molecular genetics is the sequence analysis of certain genes: Here, if there is suspicion of a hereditary disease, the genome of a patient can be examined, and a mutation may be detected. This can potentially enable improved therapy or make the risk of disease assessable. Finally, through cloning and overexpression of various therapeutically effective proteins in host cells, these proteins can be purified in large quantities. For example, this can be used to produce recombinant interferon-β for the treatment of multiple sclerosis.

## Molecular Biological Methods

Molecular biology deals with the molecular foundations of biology. It particularly focuses on the flow of genetic information from DNA to RNA and to proteins. The insights gained about the cellular processes behind this flow of information are applied in molecular biological laboratory methods. For example, enzymes responsible for DNA replication in the cell are used in the laboratory to synthesize DNA.

### Polymerase Chain Reaction (PCR)

- Definition: Method for amplification (replication) of specific DNA segments from very small amounts of starting DNA, e.g. for subsequent sequencing or for creating a genetic fingerprint.
- Principle: Cyclical amplification of a double-stranded DNA segment between two oligonucleotide primers using a thermostable polymerase.
- Required materials
    - Heat-stable DNA polymerase (e.g., Taq or Pfu)
    - Two sequence-specific primers (single-stranded DNA, about 15-25 deoxyribonucleotides long, complementary to each end of the DNA region to be amplified)
    - DNA-Template
    - dNTPs (Deoxyribonucleotides, dATP, dGTP, dCTP, and dTTP)
    - MgCl2
    - Buffer solution
- Amplification cycles (approximately 20 to 50 repetitions)
    - Denaturation
        - Double-stranded DNA is separated into single strands by raising the temperature to about 95°C.
    - Annealing (Hybridization)
        - Primers bind to complementary DNA sequence.
        - Temperature approx. 50-60°C
    - Elongation (DNA Synthesis)
        - DNA polymerase extends the primers at their 3'OH ends, resulting in the formation of double-stranded DNA again.
        - Temperature approx. 70°C
- Result: Multiplication of the DNA sequence depending on the number of amplification cycles and the efficiency of the reaction by approximately a factor of 10^6 to 10^12.
- Analyze: Verification of the amplified DNA sequence by gel electrophoresis
- Reverse Transcriptase PCR: Detection of RNA (e.g. from RNA viruses) using reverse transcriptase
    - RNA is transcribed into DNA (so-called cDNA, from English complementary DNA = "complementary DNA") and then amplified using standard PCR.

> [!note]
> To amplify a section of double-stranded DNA by PCR, two specific primers are needed. After the denaturation of the DNA, each primer binds to one of the two DNA strands (annealing) and is extended at its 3' end by the heat-stable polymerase (elongation). These three steps are repeated approximately 30 times.

### DNA Sequencing by Sanger (Chain Termination Method, Dideoxy Method)

- Definition: Decoding the base sequence of a DNA molecule based on in vitro replication.
- Principle
    - A part of the DNA sequence must be known. For this, complementary primers (oligodeoxynucleotides) are synthesized.
    - Four identical reaction approaches with the following content:
        - To be sequenced DNA molecule
        - DNA Polymerase
        - First
        - dNTPs (Deoxyribonucleotides, dATP, dGTP, dCTP, and dTTP)
        - Buffer (with MgCl2)
        - ddNTPs: A 2'-3'-dideoxynucleotide (ddATP, ddGTP, ddCTP or ddTTP) in low concentration
    - The polymerase extends the primers in each reaction as in DNA replication, but the extension of the complementary DNA strand terminates upon the incorporation of a 2'-3'-dideoxynucleotide. Due to the absence of the 3'OH group, no new dNTP can be added.
    - Due to the presence of only low concentrations of 2'-3'-dideoxynucleotides, statistically varying lengths of DNA chains are obtained.
    - Analyze by gel electrophoresis
- By using differently fluorescently labeled ddNTPs, sequencing can be performed in just one step.

### Hybridization Techniques in Molecular Biology

Various methods utilize hybridization, i.e., the specific binding of complementary DNA or RNA fragments through base pairing, for the detection of DNA or RNA molecules.

- Southern Blot: Detection of DNA fragments by transferring the DNA from an electrophoresis gel to a membrane (made of nylon or nitrocellulose) and detection using a labeled oligonucleotide probe.
- Northern Blot: Detection of RNA fragments analogous to Southern Blot
- DNA-Microarray: Detection of specific nucleotide sequences in a high-throughput process

### Genome Editing (Genom-Editierung)

- Definition: Targeted alteration of the genomes of living organisms at one or more specific sites using endonucleases.
- Goal: To turn off a gene by mutation or removal (deletion, gene knockout) and, if necessary, insert specific DNA sequences (insertion, gene knock-in)

#### Tools

- CRISPR/Cas
    - Definition
        - CRISPR (Clustered regularly interspaced short palindromic Repeats): Nucleic acid sequence in the genome of prokaryotes that serves an adaptive immune response.
        - Cas(CRISPR-associated)-Protein: Endonuclease (e.g. Cas9, Cas12a)
    - Background: Defense mechanism of prokaryotes against infection by phages
        - Initial infection by phages: Integration of viral sequence into the CRISPR region of the bacterial genome
        - Transcription of the CRISPR region and complex formation of the resulting RNA with the Cas protein
        - After re-infection: Binding of viral sequence by the complementary CRISPR transcript and cleavage of the viral sequence by the Cas protein
    - Application principle
        - Inserting Cas protein and specific RNA into the target cell
        - Binding to the target sequence and induction of a double-strand break
        - Self-repair through non-homologous end joining (NHEJ) or homologous recombination (HDR) with the addition of linear DNA as a template
    - Advantages: Very precise, cost-effective, simultaneous cutting of different sequences in one cell possible
    - Outlook: Therapy for oncological or genetic diseases
- More complex and less specific methods for induced strand breakage: zinc finger nucleases, TALEN (Transcription Activator-like Effector Nuclease)

### Cloning

- Definition: Incorporation of a DNA segment into a vector, allowing this DNA segment to be introduced into a host cell and expressed there.
- Goal: Amplification of an exogenous DNA fragment, or expression of the foreign gene in the host cell.
- Tools
    - Plasmid/cloning vector
    - To be amplified/expressed DNA, e.g. synthesized in the laboratory or purified from a donor organism
    - Restriction enzymes, e.g. Eco RI
    - DNA ligase
    - Host cells (e.g. bacteria like E. coli or yeasts like Saccharomyces cerevisiae)
- Approach
    1. Restriction digestion: Cutting plasmid and the DNA fragment to be inserted with the same restriction enzyme.
        - Result: Compatible ends of plasmid and inserted DNA
    2. Ligation: Linking of cut plasmid and inserted DNA with the help of DNA ligases.
    3. DNA transfer in host cells
        - In bacteria: Transformation or transduction
        - In eukaryotes: Transfection (= Introduction of DNA or RNA into a host cell, e.g. through electroporation, chemical reagents, or viruses)
    4. Plating, e.g. the bacterial solution on agar plates and incubation under selection conditions, e.g. in the presence of the antibiotic ampicillin
    5. Selection and propagation of several clones (e.g. each bacterial colony on the agar plate corresponds to a clone) in a growth medium under selection conditions.
    6. Purification of the increased plasmid (from a clone) from the bacterial culture, e.g. directly as a genomic library or for the production of recombinant proteins in suitable host organisms.

#### Production of therapeutic proteins in host organisms

Many proteins used therapeutically are genetically manufactured in bacteria. Examples include growth hormone, insulin, vaccines against hepatitis A and B, therapeutic antibodies, and interferons.

- Principle
    - Cloning of the gene to be expressed into a suitable vector
    - Transfer the vector containing the gene to be expressed into a host organism, e.g., E. coli
    - Cell culture: Propagation of the host organism in a nutrient medium under selection conditions, e.g., presence of ampicillin, and expression of the target gene (protein biosynthesis)
    - Purification of the produced protein (see protein analytics), e.g. via an affinity tag
- Requirements (Choice of Host Organism)
    - Glycosylations cannot be produced in E. coli. If these are essential for protein function, one must switch to eukaryotic cells as the expression system.
    - For expression in E. coli, a bacterial promoter must be present on the expression plasmid to initiate transcription. Additionally, the corresponding gene must not contain introns, as these cannot be spliced in bacteria. Instead, cDNA (DNA generated from spliced mRNA using reverse transcriptase) or synthetic DNA sequences are used.
    - In E. coli, some codons are used that differ from those in eukaryotic cells. Due to the degeneration of the genetic code, the base sequence of the gene to be expressed can be optimized in such a way that a more efficient protein synthesis of the eukaryotic protein occurs in a prokaryote.
- Advantages over extraction from animal or human tissue
    - Production of significantly larger quantities, e.g., of the growth hormone TSH (Thyroid-stimulating hormone)
    - Reducing the risk of allergies, e.g., through recombinant human insulin compared to beef insulin
    - No transmission of infections, as can occur with the isolation of coagulation factors from blood donations.
    - Production of optimized proteins that act more strongly or less strongly than their physiological counterparts, e.g., so-called fast-acting, genetically modified insulins.

## Protein Analytics

Protein analytics refers to the biochemical methods for characterizing the structure and function of proteins. This plays a role in both research and clinical settings (see also: Chapter on Protein Analytics).

### Isolation of Proteins

Proteins can be isolated in two steps:

1. Release of proteins from the cells
    1. Destruction of the cell membrane (cell lysis)
    2. Centrifugation of the cell components
    3. If necessary: Determination of the fraction that contains the highest concentration of the desired protein.
2. Separation and purification of the protein mixture
    - For example, they are used.
        - Affinity chromatography: Separation based on specific binding affinities
        - Immunoprecipitation: Separation based on binding affinities to specific antibodies
            - So-called immune precipitates are formed, meaning that the protein to be purified is bound by a specific antibody and sedimented. The antibody molecules are coupled to magnetic or agarose beads and can be separated from the remaining protein mixture by magnetic force or centrifugation.
        - Gel filtration/size exclusion chromatography: Separation by molecular size through diffusion through a so-called molecular sieve.
        - Ion exchange chromatography: Separation by net charge
        - Salting out: The solubility of proteins is affected by the addition of salt to the solvent, and beyond a certain salt concentration, they precipitate.

### Determination of Protein Concentration and Molecular Weight

In the analysis of proteins, there are some parameters that are of particular interest: the molecular weight of a protein in general, as well as the concentration of a protein or protein mixture in a specific solution. To determine these parameters, there are many methods, of which only two are exemplarily selected here.

- Biuret reaction:
    - Detection of peptide bonds, which react in alkaline solution with Cu2+ ions to form a blue color complex.
    - The intensity of the coloration is proportional to the concentration of the protein
- SDS-PAGE (SDS-Polyacrylamide Gel Electrophoresis)
    1. Addition of SDS (sodium dodecyl sulfate) to the protein mixture, this leads to the unfolding (denaturation) of the proteins.
    2. Denatured proteins contain negative charges proportional to their molecular size due to SDS binding.
    3. The proteins migrate through the polyacrylamide gel, which acts as a molecular sieve (similar to above), towards the anode and separate according to their size.
    4. Staining the proteins for visibility
    5. By comparing with a simultaneously separated mixture of standardized marker proteins, an estimation of the molecular weight of the proteins is possible.

> [!note] Serum electrophoresis
> The SDS-PAGE is used in the clinic for laboratory diagnostics to separate and quantify serum proteins by fractions. Changes in the relative protein fractions can be used for the diagnosis of various diseases. For example, the albumin fraction, which normally has the largest share of total protein, is reduced in cases of diminished synthetic capacity of the liver, as seen in liver cirrhosis.
> 

### Specific Detection of Proteins

Known proteins can be detected in various ways. Very often, immunological methods are used for this purpose. In addition to the detection of specific proteins, there are also various staining methods that can nonspecifically stain proteins in gels and/or on membranes (e.g., Coomassie, silver, or Ponceau S staining).

- Western Blot (Immunoblot)
    - Principle: Transfer of proteins from an electrophoresis gel to a membrane (made of nylon or nitrocellulose) by applying an electric voltage perpendicular to the gel.
    - Result: The proteins separated by size in the gel are located on the membrane, while the banding pattern produced in the electrophoresis is preserved.
    - Detection: The proteins are detected using specific antibodies.
        - Approach
            1. The membrane with the transferred proteins is washed in buffer solution. This removes the SDS, allowing the proteins to properly refold. This is important so that they can be recognized by an antibody.
            2. To prevent the nonspecific binding of antibodies, the membrane is blocked with milk powder or bovine serum albumin.
            3. After washing again, the membrane is incubated with a primary antibody against the protein to be detected. The antibody binds to the proteins that contain the antigen recognized by it.
            4. Washing the membrane removes nonspecifically bound antibodies, i.e., those that are not very tightly bound.
            5. Next, the membrane is incubated with a secondary antibody that binds to the Fc region of the primary antibody. The secondary antibody is usually either conjugated to an enzyme (e.g., horseradish peroxidase or alkaline phosphatase) or is itself fluorescently labeled. Since multiple secondary antibodies can bind to a single primary antibody, there is an amplification of the signal compared to the labeling of the primary antibody.
            6. After an additional washing step, the secondary antibody is detected. If it is enzyme-linked, the enzymatic reaction triggers a color reaction or generates chemiluminescence, which can be visualized using X-ray film, for example. Antibodies bound to the membrane, which are fluorescence-labeled, are detected in special scanners.
    - Example: Borrelia serology (Western blot-based detection of antibodies against Borrelia in case of suspected infection)
- ELISA (enzyme-linked immunosorbent assay)
    - Principle: An antigen is immobilized on a solid surface and detected by an enzyme-linked antibody (direct detection). In the so-called sandwich ELISA, a capture antibody is bound to a solid surface that binds the antigen to be detected, which can then be detected by an enzyme-linked detection antibody.
    - Result: Detection and quantification of antigens (proteins, e.g. antibodies and hormones) in mixtures
    - Approach
        - Most often, microtiter plates (with 96 wells, so-called 96-well plates) are used, whose polystyrene bottoms are coated (furnished) with a corresponding antibody (or with an antigen in the case of direct detection).
        - As with the Western blot, nonspecific antibody bindings are also prevented here in the following steps by blocking with milk powder or comparable protein mixtures.
        - After a washing step, the coated plate is incubated with the sample, meaning the sample is applied to the prepared plate. In this step, the protein that is recognized by the antibody bound to the plate binds to this antibody and is thus retained.
        - By adding the detection antibody, the bound protein is detected. The detection antibody is (as is partly the case with Western Blot) coupled to an enzyme (hence the name ELISA).
        - A suitable substrate is added so that the enzyme can convert the substrate. The resulting signal is then detected through color reaction or by emitting fluorescence or luminescence. The intensity of the signal is proportional to the amount of protein.
    - Examples: Pregnancy test (detection of human chorionic gonadotropin), anti-HIV antibody screening test

### Determination of Amino Acid Composition and Sequence

Often one wants to know which amino acids make up a protein or what its amino acid sequence is. This allows proteins to be compared and mutations to be detected. The following methods are used:

- Analysis of the amino acid composition using the ninhydrin reaction
    1. Hydrolysis of proteins through acid addition
    2. Separation of amino acids by ion exchange chromatography
    3. Determination of concentration by the Ninhydrin reaction
        - Ninhydrin reacts with the primary amino groups of amino acids to form a blue-violet dye, with the intensity of the color corresponding to the concentration of amino acids.
- Analysis of the amino acid sequence: Using Edman degradation
    1. Marking of the amino acid at the N-terminus
    2. Cleavage and determination of this amino acid by the properties of its side chain

## Review Questions on the Chapter Biochemical Laboratory Methods
### Molecular Biological Methods

What is the purpose of the polymerase chain reaction (PCR)?
- The polymerase chain reaction (PCR) is a laboratory method used for the amplification (multiplication) of specific DNA segments from very small amounts of starting DNA. The amplified DNA can subsequently be used, for example, for sequencing or creating a genetic fingerprint.

Describe the process of a PCR amplification cycle! How many times is this typically repeated?
- The amplification cycle of PCR can be divided into three steps: denaturation, annealing (hybridization), and elongation (DNA synthesis). During denaturation, the (double-stranded) DNA is separated into two single strands by raising the temperature to about 95°C. Then, two sequence-specific primers are added, each binding to complementary sequences at the 5'OH end of the DNA segment to be amplified on each single strand (annealing). Next, a thermostable DNA polymerase extends the two primers at their 3'OH ends, resulting in double-stranded DNA again (elongation). This cycle is typically repeated about 20–50 times.

What is meant by hybridization in molecular biology? Name examples of laboratory methods based on this!
- Hybridization refers to a process in which DNA or RNA fragments specifically bind to each other through their complementary bases. This can be used in the laboratory to detect DNA and RNA sequences. Hybridization techniques include Southern blot, Northern blot, and DNA microarray. In PCR as well, hybridization of the primer with the DNA recognizes the DNA fragment to be amplified.

What are so-called agar plates used for?
- Agar, a carbohydrate derived from algae, can convert a liquid into a gel. This is particularly utilized in microbiology, where agar plates made of agar and a nutrient medium can be used as a growth substrate for bacteria.

How is a DNA segment inserted into a vector during cloning?
- To insert a specific DNA segment into a vector (e.g., plasmid) during cloning, both are first cut with the same restriction enzyme so that their ends match. Then, they are joined together using DNA ligases. In this form, the DNA transfer into the host cell can then take place.

### Protein Analytics

Ninhydrin is used for the detection of amino acids as well as for determining the concentration of amino acids within a protein. Which functional group does ninhydrin react with and what is produced in the process?
- Ninhydrin serves as a reagent for detecting amino acids because it reacts with their primary amino groups (-NH2) to form a blue-violet dye. The color intensity correlates with the concentration of amino acids.

According to which properties are protein mixtures separated in the following biochemical methods: ion exchange chromatography, affinity chromatography, gel filtration chromatography?
- When separating protein mixtures, the different size, solubility, charge, and specific binding affinity of proteins are utilized. Ion exchange chromatography separates proteins based on their net charge; affinity chromatography separates them based on their specific binding affinities. Gel filtration chromatography (also called size exclusion chromatography) separates the mixture according to molecular size by passing it through a molecular sieve made of small beads.
