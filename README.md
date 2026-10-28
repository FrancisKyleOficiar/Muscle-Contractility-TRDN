# Muscle-Contractility-TRDN

Name: Oficiar, Francis Kyle A.
Date Completed: October 28, 2026
Course: Cell and Molecular Biology - B

Gene: 31. TRDN — NM_006073.4:c.53_56del (p.Asp18fs) — ClinVar 66015 [frameshift]
NP accession: NP_006064.2
Protein Length: 729 aa

# Process — R Workflow

<img width="697" height="366" alt="image" src="https://github.com/user-attachments/assets/a88be89e-2573-4c94-8ffa-400bbb86dbf9" />

**Figure 1.** RStudio environment showing complete script execution; no runtime errors, confirming the workflow runs successfully.

# Step 1 — Project Setup
gene_symbol: TRDN 
transcript accession: NM_006073.4
variant protein: c.53_56del (p.Asp18fs) 
ClinVar Id: 66015 [frameshift]

# Step 2 - NCBI gene record
Gene symbol: TRDN
NCBI Gene ID: 10345
Official name: triadin
Chromosome: 6

# Step 3 — Protein Sequence
NP accession: NP_006064.2
FASTA FILE: https://github.com/FrancisKyleOficiar/Muscle-Contractility-TRDN/blob/main/data/TRDN_protein.fasta

# Step 4 - Amino‑Acid Composition

**Table 1.** Full amino-acid composition of human triadin (TRDN; NP_006064.2; 729 amino-acid residues).

<img width="181" height="421" alt="image" src="https://github.com/user-attachments/assets/a4b0654c-9d51-42be-b092-dd3cf8385bef" />

**Top 3 Most Abundant Residues:**
1. Lysine (K): 158 residues
2. Glutamic acid (E): 100 residues
3. Proline (P): 53 residues


<img width="2400" height="1500" alt="image" src="https://github.com/user-attachments/assets/82ca31de-a9c2-4804-b77f-a2bf4bbba40d" />

**Figure 2.** TRDN amino-acid composition showing lysine (K) and glutamic acid (E) as the most abundant residues, followed by proline (P). This composition describes the protein's amino-acid distribution but does not independently establish its structure or function in calcium regulation.

# Step 5 - ClinVar Record (Variation 66015)

<img width="1366" height="676" alt="image" src="https://github.com/user-attachments/assets/b164a14a-5058-40c2-a15a-9f72716d4c37" />

**Figure 3.** ClinVar classification of  TRDN — NM_006073.4:c.53_56del (p.Asp18fs) — ClinVar 66015 [frameshift] - Classified as Pathogenic

# Step 6 — Second Biological Visualization

<img width="2400" height="750" alt="image" src="https://github.com/user-attachments/assets/9e19e77f-bf12-4fc9-b822-5d893ae0a0de" />

**Figure 4.** Variant-position plot showing the TRDN c.53_56del (p.Asp18fs) frameshift near residue 18 of the triadin reference protein (NP_006064.2; 729 amino acids). The deletion occurs near the N-terminus and is predicted to cause premature termination, potentially disrupting normal protein production.

# Step 7 - Explain the Molecular Mechanism

### 1. Normal protein function in muscle

The **TRDN gene encodes triadin**, a protein associated with the sarcoplasmic reticulum in skeletal and cardiac muscle. Triadin participates in the calcium-release complex and helps regulate calcium release during excitation–contraction coupling. Calcium activates the contractile machinery, allowing actin and myosin to interact and produce contraction. Therefore, triadin primarily contributes to calcium regulation rather than directly driving the actin–myosin cycle or maintaining structural integrity.

### 2. What is known about the assigned variant?

The assigned variant, **NM_006073.4(TRDN):c.53_56del (p.Asp18fs)**, is a four-nucleotide deletion that shifts the reading frame near the beginning of the protein-coding sequence. ClinVar classifies it as pathogenic, supporting a clinically significant association with TRDN-related disease. The frameshift is predicted to introduce a premature stop codon, potentially causing nonsense-mediated mRNA decay or production of a severely truncated triadin protein. These molecular consequences are predictions unless directly demonstrated for this specific variant. The clinical classification supports disease association but does not, by itself, establish the exact effects on protein abundance or calcium release.

### 3. Causal chain

**TRDN gene → triadin protein → regulation of calcium release from the sarcoplasmic reticulum → c.53_56del frameshift variant → predicted reduction or loss of functional triadin → potentially disrupted calcium handling and abnormal muscle contraction or relaxation.**

This mechanism is biologically plausible because proper calcium release and reuptake are necessary for coordinated muscle contraction and relaxation. However, the specific downstream effects of this variant require experimental confirmation.

### 4. Proposed experiment

**Calcium imaging in muscle cells** could test whether the variant affects calcium handling. Compare muscle cells expressing wild-type TRDN with cells carrying the c.53_56del variant, then stimulate both groups and measure intracellular calcium changes using a fluorescent calcium indicator. Reduced or abnormal calcium-release responses in variant-bearing cells would support the proposed mechanism. Measuring triadin protein abundance alongside calcium imaging would help determine whether the altered response is associated with reduced protein production.

# Questions to Answer in README.md

### 1. What does your assigned gene encode, and how does this protein contribute to muscle function?

The TRDN gene (NCBI Gene ID: 10345) encodes triadin, a protein associated with the sarcoplasmic reticulum in muscle cells. Triadin participates in the calcium-release complex, where it interacts with proteins involved in regulating calcium release during excitation–contraction coupling. This process allows calcium to trigger muscle contraction, making triadin important for normal skeletal and cardiac muscle function.

### 2. What was the exact protein accession and length retrieved with R?

The retrieved protein accession was NP_006064.2, corresponding to the human triadin protein. Based on the amino-acid composition data, the protein contains 729 amino-acid residues. The 20 amino-acid counts in the supplied table sum to 729, consistent with this length.

### 3. What did the amino-acid composition chart show? What can it NOT tell you?

The amino-acid composition chart shows that lysine (K) is the most abundant residue, with 158 residues, followed by glutamic acid (E), with 100 residues. Cysteine (C) and tryptophan (W) are among the least abundant, with two and three residues, respectively. However, amino-acid composition alone cannot establish the protein's three-dimensional structure, exact functional domains, subcellular interactions, or the functional consequences of a particular variant.

### 4. What is your fixed ClinVar variant, and what is its current classification and evidence strength?

The fixed variant is NM_006073.4(TRDN).53_56del (p.Asp18fs), ClinVar Variation ID 66015. It is a four-base-pair deletion that causes a frameshift beginning at amino-acid position 18. ClinVar currently classifies the variant as Pathogenic, with multiple submitters and no classification conflicts; seven of eight submissions contribute to the aggregate classification. The aggregate record has a two-star review status, indicating criteria were provided by multiple submitters without conflicts, but it is not an expert-panel classification.

### 5. What is the scientifically supported mechanism linking this variant to muscle function, and what remains uncertain?

The deletion shifts the reading frame and introduces a premature termination codon, predicted to produce a severely truncated triadin protein or cause the transcript to undergo nonsense-mediated decay. This is consistent with a loss-of-function mechanism. Reduced or absent functional triadin could disrupt calcium handling during excitation–contraction coupling and impair normal muscle contraction. The variant has been reported in individuals with serious cardiac arrhythmias, including catecholaminergic polymorphic ventricular tachycardia. However, the precise molecular consequences in a particular muscle-cell context, including the extent of transcript degradation and the residual function of any resulting protein, cannot be established from the sequence change alone.

### 6. What additional experiment would help test the proposed mechanism?

A useful experiment would compare wild-type and variant TRDN expression in an appropriate muscle-cell model. RT-qPCR could measure TRDN transcript abundance, while Western blotting with an appropriate triadin antibody could assess protein abundance and size. Calcium-imaging experiments following controlled stimulation could then test whether the variant is associated with altered intracellular calcium release. Together, these experiments would help distinguish transcript degradation, protein loss, and impaired calcium handling.

# Discussion 

  The TRDN gene encodes triadin, a protein associated with the sarcoplasmic reticulum and the calcium-release complex in muscle cells. Triadin participates in excitation–contraction coupling, the process through which electrical stimulation leads to calcium release and muscle contraction. Although its precise functions within the calcium-release complex are not completely defined, research supports its importance in normal muscle physiology (Marty, 2004). The amino-acid composition analysis identified 729 residues in the retrieved reference protein, NP_006064.2. Lysine was the most abundant amino acid, with 158 residues, followed by glutamic acid, with 100 residues. These results describe the protein's composition but do not directly establish its structure, interactions, or functional activity. Similarly, the variant-position figure locates the alteration near the N-terminus but cannot independently demonstrate its biological effects.

The selected variant, NM_006073.4(TRDN):c.53_56del (p.Asp18fs), is a four-base-pair deletion that shifts the reading frame beginning at amino-acid position 18. ClinVar classifies this variant as pathogenic, with supporting submissions and no classification conflicts. It has been reported in individuals with catecholaminergic polymorphic ventricular tachycardia and related cardiac arrhythmia phenotypes. Clinical reports also describe individuals with TRDN-associated disease who have variable skeletal muscle involvement. Therefore, the clinical association is supported, although the severity of muscle symptoms may differ between individuals.

The proposed molecular mechanism is loss of triadin function. Because the frameshift occurs near the beginning of the coding sequence, it is predicted to introduce a premature termination codon, potentially leading to nonsense-mediated mRNA decay or production of a severely truncated protein. Reduced functional triadin could disrupt calcium handling and impair excitation–contraction coupling. Experimental research in triadin-deficient animal models has demonstrated reduced muscle strength, supporting the importance of triadin in skeletal muscle function. However, these findings do not directly establish the exact molecular effects of this particular human variant.

Further experiments could test this mechanism by measuring TRDN transcript abundance using RT-qPCR and triadin protein abundance using Western blotting in an appropriate muscle-cell model. Calcium imaging after controlled stimulation could determine whether calcium release is altered. Comparing wild-type and variant cells would help distinguish predicted effects from experimentally observed changes. Overall, the variant has an established clinical classification, while the precise relationship between transcript disruption, triadin deficiency, calcium handling, and muscle dysfunction requires further experimental investigation.

# References
1. NCBI ClinVar. NM_006073.4(TRDN):c.53_56del (p.Asp18fs), Variation ID 66015. ClinVar variant record
2. Marty, I. (2004). Triadin: a multi-protein family for which purpose? Cellular and Molecular Life Sciences, 61, 1850–1853. PubMed article
3. Roux-Buisson, N., et al. (2012). Absence of triadin, a protein of the calcium release complex, is responsible for cardiac arrhythmia with sudden death in human. Human Molecular Genetics, 21(12), 2759–2767. PubMed article
4. Triadin deletion induces impaired skeletal muscle function. Physiological study of triadin-deficient animal models. PubMed article
