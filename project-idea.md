# Project Idea: CRISPR Simulation and Chimera Maker

## The Idea

### Introduction

This is the project idea document of our CRISPR simulation and chimera maker tool that aims tosupport genetic engineering efforts using AI algorithms, 3D modelingand bioinformatics tools. It will help researchers design DNA and predict the functions and effects of genetic modifications andnon-existent creations. With its advanced features, this tool has thepotential to significantly improve the accuracy and efficiency ofgenetic engineering and contribute to our understanding of genetics.
In short, it isdeveloping a comprehensive CRISPR simulation tool using AI. It canconvert DNA or parts of it into a 3D model. Moreover, it can estimate what happens if you change a certain gene or introduce a piece ofanother creature. The tool is also a Chimera maker and can thereforemerge DNA from different creatures into a new creature. With the tool we want to determine how a cell works and make better estimates.
CRISPR is a powerfultool that allows researchers to edit DNA with precision andefficiency. However, the process can still be time-consuming and can yield unpredictable results. Therefore, it is crucial to have asimulation tool that can accurately predict the outcomes of CRISPR modifications.
Bioinformatics toolshave been used to for the analysis of genes, genomes, and biological pathways, but there is still a need for a comprehensive simulationtool that combines AI, 3D modeling, and bioinformatics. Our projectaims to fill this gap and provide a platform for researchers todesign and simulate genetic modifications.

### Features

Here are some keyfeatures that will be included in our CRISPR simulation and chimeramaker tool:

- **AI-basedprediction of CRISPR outcomes:** Using machine learning algorithms,our tool will be able to accurately predict the outcomes of CRISPR modifications, including targeted mutations, insertions or deletions.This will save time and resources for researchers, as they canevaluate the potential effects of modifications before conductingexperiments.
- **3D modeling fromDNA:** The tool will be able to convert DNA sequences into 3D models,providing a visual representation of the outcome of the geneticstructure. This will allow researchers to better predict thepossible outcome of the modification.
- **Chimera maker:**Our tool will have the ability to merge DNA from different speciesand create chimeric DNA sequences. This feature can aid in thecreation of new organisms with specific traits and functions,advancing the capabilities of genetic engineering.
- **Identificationof gene functions:** By analyzing the DNA sequence and usingbioinformatics tools, our tool will be able to predict the functions of genes and help researchers identify potential targets for modifications.
- **Virtual CRISPRexperiments:** The tool will have a built-in virtual laboratory where researchers can perform simulated CRISPR experiments and observe theoutcomes. This will provide a safe and efficient way to test andoptimize modifications before conducting experiments in a real laboratory.

### How It Works

* Users inputparameters for organisms, such as size, complexity, and known geneticdata.
* The simulationgenerates virtual organisms based on these parameters.
* The AI analyzessimulated organism data, learning patterns of cell development,genetic sequences, and relative complexity.
* As users provideunfinished genetic sequences, the AI predicts potential completionsbased on known evolutionary paths.
* Users can selectorganisms from the simulation or input external genetic data.
* The AI assessescompatibility and potential outcomes, guiding users in creatingchimeras with predicted characteristics.

### PotentialApplications

* *Research Aid*: Scientists can use the tool to explore evolutionary relationshipsbetween organisms; Assess the feasibility of creating novel organismsthrough genetic modifications.
* *BiomedicalInnovation*: Aid in understanding genetic diseases by simulatingaffected organisms and potential gene therapies; Explore the creationof synthetic organisms for medical purposes.
* *Educational Tool*: Universities and students can use the tool to understand complexgenetic concepts through interactive simulations; Demonstrate theimpact of genetic modifications and evolution on organismdevelopment.

### Target Users

Our project aims tobe a valuable tool for genetic engineers, molecular biologists,bioinformaticians, and researchers working in the field of genetics.It will also be beneficial for students and educators in biology andbiotechnology fields.

### Technology Stack (Yet to be Determined)

The following is alist of technologies that may be used in the development of ourCRISPR simulation and chimera maker tool:

- **Programminglanguage:** Python will be the primary language used for this projectdue to its extensive libraries for AI, 3D modeling, andbioinformatics.
- **AI and machinelearning:** Libraries such as TensorFlow, Keras, and Scikit-learnwill be used to implement AI-based prediction algorithms.
- **3D modeling:** Libraries such as PyMOL, Biopython, and Moltemplate will be used toconvert DNA sequences into 3D models and visualize them.
- **Bioinformatics:** Libraries such as Biopython, BLAST, and Clustalwill be used for gene analysis and prediction of gene functions.
- **Virtuallaboratory:** Unity or any other game engine can be used to create avirtual laboratory environment where the CRISPR experiments can besimulated and observed.

### Conclusion

In conclusion, our CRISPR simulation and chimera maker project aims to provide acomprehensive tool for genetic engineering and research purposes. Bycombining AI, 3D modeling, and bioinformatics, it will be able toaccurately predict the outcomes of CRISPR modifications, aid in thecreation of chimeric DNA sequences, and provide a virtual laboratoryfor safe and efficient experimentation. We believe that this tool hasthe potential to significantly improve the efficiency and accuracy ofgenetic engineering and contribute to our understanding of genetics. 

## Appendix A: DNA Format Proposal

There are four DNA nucleotides: Adenine (A); Cytosine (C); Guanine (G); Thymine (T).Four possibilities can be stored into two bits. Since we want to read DNA as a condon as a packet of three, we need six bits to store onecondon. There are 8 bits in a byte, so 2 bytes are left for anothertask as error checking or something else.

### The Condons

- *UUU (0x55)*:Phenylalanine (ASCII: U)
- *UUC (0x56)*:Phenylalanine (ASCII: V)
- *UUA (0x57)*:Leucine (ASCII: W)
- *UUG (0x58)*:Leucine (ASCII: X)
- *UCU (0x59)*:Serine (ASCII: Y)
- *UCC (0x5A)*:Serine (ASCII: Z)
- *UCA (0x5B)*:Serine (ASCII: \[)
- *UCG (0x5C)*:Serine (ASCII: \\)
- *UAU (0x65)*:Tyrosine (ASCII: e)
- *UAC (0x66)*:Tyrosine (ASCII: f)
- *UAA (0x6A)*:Stop (Termination codon) (ASCII: j)
- *UAG (0x6B)*:Stop (Termination codon) (ASCII: k)
- *UGU (0x75)*:Cysteine (ASCII: u)
- *UGC (0x76)*:Cysteine (ASCII: v)
- *UGA (0x7A)*:Stop (Termination codon) (ASCII: z)
- *UGG (0x7B)*:Tryptophan (ASCII: {)
- *CUU (0x95)*:Leucine (ASCII: •)
- *CUC (0x96)*:Leucine (ASCII: –)
- *CUA (0x97)*:Leucine (ASCII: —)
- *CUG (0x98)*:Leucine (ASCII: ˜)
- *CCU (0x99)*:Proline (ASCII: ™)
- *CCC (0x9A)*:Proline (ASCII: š)
- *CCA (0x9B)*:Proline (ASCII: ›)
- *CCG (0x9C)*:Proline (ASCII: œ)
- *CAU (0xA5)*:Histidine (ASCII: ¥)
- *CAC (0xA6)*:Histidine (ASCII: ¦)
- *CAA (0xA7)*:Glutamine (ASCII: §)
- *CAG (0xA8)*:Glutamine (ASCII: ¨)
- *CGU (0xA9)*:Arginine (ASCII: ©)
- *CGC (0xAA)*:Arginine (ASCII: ª)
- *CGA (0xAB)*:Arginine (ASCII: «)
- *CGG (0xAC)*:Arginine (ASCII: ¬)
- *AUU (0xB5)*:Isoleucine (ASCII: µ)
- *AUC (0xB6)*:Isoleucine (ASCII: ¶)
- *AUA (0xB7)*:Isoleucine (ASCII: ·)
- *AUG (0xB8)*:Methionine (Start codon; also codes for Methionine) (ASCII: ¸)
- *ACU (0xB9)*:Threonine (ASCII: ¹)
- *ACC (0xBA)*:Threonine (ASCII: º)
- *ACA (0xBB)*:Threonine (ASCII: »)
- *ACG (0xBC)*:Threonine (ASCII: ¼)
- *AAU (0xC5)*:Asparagine (ASCII: Å)
- *AAC (0xC6)*:Asparagine (ASCII: Æ)
- *AAA (0xC7)*:Lysine (ASCII: Ç)
- *AAG (0xC8)*:Lysine (ASCII: È)
- *AGU (0xC9)*:Serine (ASCII: É)
- *AGC (0xCA)*:Serine (ASCII: Ê)
- *AGA (0xCB)*:Arginine (ASCII: Ë)
- *AGG (0xCC)*:Arginine (ASCII: Ì)
- *GUU (0xD5)*:Valine (ASCII: Õ)
- *GUC (0xD6)*:Valine (ASCII: Ö)
- *GUA (0xD7)*:Valine (ASCII: ×)
- *GUG (0xD8)*:Valine (ASCII: Ø)
- *GCU (0xD9)*:Alanine (ASCII: Ù)
- *GCC (0xDA)*:Alanine (ASCII: Ú)
- *GCA (0xDB)*:Alanine (ASCII: Û)
- *GCG (0xDC)*:Alanine (ASCII: Ü)
- *GAU (0xE5)*:Aspartic Acid (ASCII: å)
- *GAC (0xE6)*:Aspartic Acid (ASCII: æ)
- *GAA (0xE7)*:Glutamic Acid (ASCII: ç)
- *GAG (0xE8)*:Glutamic Acid (ASCII: è)
- *GGU (0xE9)*:Glycine (ASCII: é)
- *GGC (0xEA)*:Glycine (ASCII: ê)
- *GGA (0xEB)*:Glycine (ASCII: ë)
- *GGG (0xEC)*:Glycine (ASCII: ì)

### Unused Values

0x00, 0x01,0x02, 0x03, 0x04, 0x05, 0x06, 0x07 0x08, 0x09,0x0A, 0x0B, 0x0C, 0x0D, 0x0E, 0x0F 0x10, 0x11,0x12, 0x13, 0x14, 0x15, 0x16, 0x17 0x18, 0x19,0x1A, 0x1B, 0x1C, 0x1D, 0x1E, 0x1F 0x6A, 0x6B,0x7A, 0x7B 0x90, 0x91,0x92, 0x93, 0x94, 0x95, 0x96, 0x97 0x98, 0x99,0x9A, 0x9B, 0x9C, 0x9D, 0x9E, 0x9F 0xA0, 0xA1,0xA2, 0xA3, 0xA4, 0xA9, 0xAA, 0xAB 0xAC, 0xAD,0xAE, 0xAF 0xB0, 0xB1,0xB2, 0xB3, 0xB4, 0xB9, 0xBA, 0xBB 0xBC, 0xBD,0xBE, 0xBF 0xC0, 0xC1,0xC2, 0xC3, 0xC4, 0xC9, 0xCA, 0xCB 0xCC, 0xCD,0xCE, 0xCF 0xD0, 0xD1,0xD2, 0xD3, 0xD4, 0xD9, 0xDA, 0xDB 0xDC, 0xDD,0xDE, 0xDF 0xE0, 0xE1,0xE2, 0xE3, 0xE4, 0xE9, 0xEA, 0xEB 0xEC, 0xED,0xEE, 0xEF 0xF0, 0xF1,0xF2, 0xF3, 0xF4, 0xF5, 0xF6, 0xF7 0xF8, 0xF9,0xFA, 0xFB, 0xFC, 0xFD, 0xFE, 0xFF
