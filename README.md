# Thesis
This readme file will contain text that will edited and inserted into the thesis later.

# 2. The basic biology of proteomics.
Proteomics is the study of proteins and thier part in the biological systems. In modern medicin the field of proteomics has a great importance to understanding disease markers for diagnosis and therapy monitoring, as the proteome reflect more accurately on the dynamic state of a cell, tissue or organsm than the genome ([Cho. W. 2007](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5054093/)). The advent of proteomics technology and bioinformatics techniques has presented novel opportunities to explore biological systems and further understanding of diseases. In this chapter, a background in the field of molecular biology related to proteomics will be presented.

## Genome, transcriptome and thier relationship to the proteome
The central dogma of molecular biology explains the flow of genetic information from DNA (the genome), to RNA (the transcriptome) to the functional product, a protein ([Crick F. 1970](https://www.nature.com/articles/227561a0)). It states that DNA contains all the information needed to make all our proteins and that RNA is the messenger that carries the information to the ribosomes (small organelles in our cell, which are responsible for assembling amino acids into proteins during protein synthesis). Gene expression, is the process by which DNA is converted into functional products. It consist of two stages, the transcription and translation. The transcription is the first stage of protein synthesis where the DNA in a gene is replicated to produce an messenger RNA (mRNA). This mRNA is taken to a ribosome and a protein is constructed with the help of the transfer RNA (tRNA), which carry the amino acids to the ribosomes during protein synthesis. A overview of the process is shown below.

 <!---![The_centra_dogma_of_molecular_biology_img](https://cdn1.byjus.com/wp-content/uploads/2018/11/Central-Dogma-DNA-to-RNA-to-Protein.png)-->
![The_centra_dogma_of_molecular_biology_img](https://www.yourgenome.org/sites/default/files/illustrations/diagram/dna_central_dogma_yourgenome.png)


## Proteins

## Proteoform 
Protein variation account for a substantial amount of complexity in a biological system. These variations are called proteoforms. It has been shown that a lot of the complexity in biology us caused by protein rather than only genes. 

# The field of proteomics and its technology.
[EDIT ITS COPY PASTED]
Mass spectrometry plays a vital role in proteomics and has become an indispensable tool for molecular and cellular biology ([Cho. W. 2007](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5054093/)).

# Challenges in proteomics
[EDIT ITS COPY PASTED, Cho. W 2007 is about the challenges read it!]
While the potential is great, many challenges and issues remain to be solved, such as mining low abundant proteins and integration of proteomics with genomics and metabolomics data. Nevertheless, proteomics is the foundation for constructing and extracting useful knowledge to biomedical research. In this review, a snapshot of contemporary issues in proteomics technologies is discussed.([Cho. W. 2007](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5054093/))

# Retention time 
Retention time (RT) is the time it takes for a solute to pass through a chromatography column. It is the time from injection to detection...


# Mass spectrometry based proteomics

## Peptide identification
Peptide identification from MS/MS is an important area the bottom-up proteomics methodology. The three methods for identifying peptides are presented below.

Good links:
[Griss, Johannes, 2015](Spectra library searching in proteomics.](https://onlinelibrary.wiley.com/doi/full/10.1002/pmic.201500296)
### Sequence database searching
A search engine generates theoretical spectra of all possibly existing peptides based on theoretical spectra - even those never observed using MS. Sequence database search engines mostly only predict pcanonical fragment ions.  

#### Sequence database scoring approach
(Is is a dot product multiplication of our data peaks and a boolean vector, where the boolean vector contains a peptide sequence.)

### De-novo sequencing
In de-novo seuqencing algorithms attempt to derive peptide's sequence directly from the MS/MS spectrum by taking all possible amino acid combinations into consideration. This results in considerably larger search space sequence database searching. De-novo sequencing algorithms are therefore considerably slower than other approaches and generally derive multiple seuqnces per spectrum at equal probability. Currently, de-novo sequencing is not suited to be used as a primary means to identify MS/MS spectra [Griss, J. 2015](https://onlinelibrary.wiley.com/doi/full/10.1002/pmic.201500296).

### Spectral database searching
Spectral library searching use spectra libraries of identified, generally experimental MS/MS spectra to identify observed MS/MS spectra. It has been shown that spectral database search engines are able to identify significantly more peptides and is faster than sequence data base searches [Zhang et al. 2011](https://onlinelibrary.wiley.com/doi/10.1002/pmic.201000492).

#### Spectral database searching scoring approach
All of the current search engines (SpectraST, Trans-proteomic Pipeline, X!Hunter, Bibliospec and MSPepSearch) use dot-product based scoring approach to combine the experimental spectra against the library spectra. 










