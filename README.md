# MHCpLogics 
**MHCpLogics version 1.0 (Sep 2023)**

**MHCpLogics: an interactive machine learning-based tool for unsupervised data visualization and cluster analysis of immunopeptidomes**

***ABSTRACT***
The major histocompatibility complex (MHC) encodes a range of immune response genes, including
the human leukocyte antigens (HLAs) in humans. These molecules bind peptide antigens and present
them on the cell surface for T cell recognition. The repertoires of peptides presented by HLA molecules
are termed immunopeptidomes. The highly polymorphic nature of the genres that encode the HLA
molecules confers allotype-specific differences in the sequences of bound ligands. Allotype-specific
ligand preferences are often defined by peptide-binding motifs. Individuals express up to six classical
class I HLA allotypes, which likely present peptides displaying different binding motifs. Such complex
datasets make the deconvolution of immunopeptidomic data into allotype-specific contributions and
further dissection of binding-specificities challenging. Herein, we developed MHCpLogics as an
interactive machine learning-based tool for mining peptide-binding sequence motifs and visualization
of immunopeptidome data across complex datasets. We showcase the functionalities of MHCpLogics
by analyzing both in-house and published mono- and multi-allelic immunopeptidomics data. The
visualization modalities of MHCpLogics allow users to inspect clustered sequences down to individual
peptide components and to examine broader sequence patterns within multiple immunopeptidome data
sets. MHCpLogics can deconvolute large immunopeptidome data sets enabling the interrogation of
clusters for the segregation of allotype-specific peptide sequence motifs, identification of sub-peptidome
motifs, and the exportation of clustered peptide sequence lists. The tool facilitates rapid inspection of
immunopeptidomes as a resource for the immunology and vaccine communities. MHCpLogics is a
standalone application available via an executable installation at: https://github.com/PurcellLab/MHCpLogics.

***Key Points:***
 MHCpLogics enables unsupervised analysis of HLA peptide ligands with the flexibility to use
different machine-learning algorithms.
 An interactive and new visualization tool for immunopeptidomics data.
 Rapid cluster analysis of immunopeptidomes into allotype-specific motifs and sub-motifs.
 Multi-data comparative analysis aids antigen discovery across multiple datasets.



***Contact***
For technical support or any question, please send an email to the following developers:

Mohammad Shahbazy: mohammad.shahbazy@monash.edu 

Dr Nathan Croft: nathan.croft@monash.edu   

Dr Chen Li: chen.li@monash.edu 


***Please cite***

Mohammad Shahbazy, Sri H. Ramarathinam, Chen Li, Patricia T. Illing, Pouya Faridi, Nathan P. Croft, and Anthony W. Purcell (2023) MHCpLogics: an interactive machine learning-based tool for unsupervised data visualization and cluster analysis of immunopeptidomes.


***Instructions***

Please refer to the Tutorial file: "Tutorial_MHCpLogics_ver1.0_052023.pdf"


***PRIDE Data repository:*** 

The peptide datasets as HLA-A*02:01 (PRIDE accession code: PXD017824 and PXD034429) [ref. 1,2], HLA-B*57:01 (PXD034429) [ref. 2], and HLA-C*04:01 [ref. 2,3]. 
Two datasets of HLA-B*57:01 immunopeptidomes from cells cultured with or without abacavir (ABC) drug without PRIDE repository [ref. 4]. 
Micro-ploymorphism dataset: HLA-B*57:01 (PXD008570), -B*57:03 (PXD008571), and -B*58:01 (PXD008572) immunopeptidomes [ref. 5]. 
LM-MEL-33 dataset (PXD014397) consisting of HLA-bound peptides isolated from a Melanoma cancer cell line [ref. 6].

***Peptide data references*** 
The peptide datasets provided as examples showcasing the usage of MHCpLogics are from the following publications:

1) Jappe, E.C., Garde, C., Ramarathinam, S.H., Passantino, E., Illing, P.T., Mifsud, N.A., Trolle, T., Kringelum, J.V., Croft, N.P. and Purcell, A.W. (2020) Thermostability profiling of MHC-bound peptides: a new dimension in immunopeptidomics and aid for immunotherapy design. Nature Communications, 11, 6305.
2) Shahbazy, M., Ramarathinam, S.H., Illing, P.T., Jappe, E.C., Faridi, P., Croft, N.P. and Purcell, A.W. (2023) Benchmarking Bioinformatics Pipelines in Data-Independent Acquisition Mass Spectrometry for Immunopeptidomics. Molecular & Cellular Proteomics, 22, 100515.
3) Schittenhelm, R.B., Dudek, N.L., Croft, N.P., Ramarathinam, S.H. and Purcell, A.W. (2014) A comprehensive analysis of constitutive naturally processed and presented HLA-C*04:01 (Cw4) – specific peptides. Tissue Antigens, 83, 174-179.
4) Illing, P.T., Vivian, J.P., Dudek, N.L., Kostenko, L., Chen, Z., Bharadwaj, M., Miles, J.J., Kjer-Nielsen, L., Gras, S., Williamson, N.A. et al. (2012) Immune self-reactivity triggered by drug-modified HLA-peptide repertoire. Nature, 486, 554-558.
5) Illing, P.T., Pymm, P., Croft, N.P., Hilton, H.G., Jojic, V., Han, A.S., Mendoza, J.L., Mifsud, N.A., Dudek, N.L., McCluskey, J. et al. (2018) HLA-B57 micropolymorphism defines the sequence and conformational breadth of the immunopeptidome. Nature Communications, 9, 4693.
6) Faridi, P., Woods, K., Ostrouska, S., Deceneux, C., Aranha, R., Duscharla, D., Wong, S.Q., Chen, W., Ramarathinam, S.H., Lim Kam Sian, T.C.C. et al. (2020) Spliced Peptides and Cytokine-Driven Changes in the Immunopeptidome of Melanoma. Cancer Immunology Research, 8, 1322-1334.
