# Top-10-Studied-Genes
![](https://github.com/ahmedtarek26/Top-10-Studied-Genes/blob/main/images/DPUR_NYXcAAv-ns.jpg)
# Comparative Sequence Analysis of Top 10 Studied Genes
+ Compare their DNA sequence and Protein (Amino Acid) sequence
  - GC Content
  - Analysis of protein sequence
  - Freq of Each Amino Acids
+ Find similarity between them
    - Alignment
    - hamming distance

+ 3D structure of each
### The idea
[An article from nature
](https://www.nature.com/articles/d41586-017-07291-9?WT.ec_id=NEWSDAILY-20171124&amp;utm_source=briefing&amp;utm_medium=email&amp;utm_campaign=20171124)
### Datasource
+ [RCSB PDB](https://www.rcsb.org/) 
+ [NCBI](https://www.ncbi.nlm.nih.gov/) 
+ [Biopython](https://biopython.org/) 
+ [Py3Dmol](http://3dmol.csb.pitt.edu/)
#### Fasta Files
+ 1.[TP53](https://www.ncbi.nlm.nih.gov/nuccore/NC_000017.11?report=fasta&from=7668421&to=7687490&strand=true)  
+ 2.[TNF](https://www.ncbi.nlm.nih.gov/nuccore/NC_000006.12?report=fasta&from=31575565&to=31578336)
+ 3.[EGFR](https://www.ncbi.nlm.nih.gov/nuccore/NC_000007.14?report=fasta&from=55019017&to=55211628)
+ 4.[VEGFA](https://www.ncbi.nlm.nih.gov/nuccore/NC_000006.12?report=fasta&from=43770209&to=43786487)
+ 5.[APOE](https://www.ncbi.nlm.nih.gov/nuccore/NC_000019.10?report=fasta&from=44905796&to=44909393)
+ 6.[IL6](https://www.ncbi.nlm.nih.gov/nuccore/NC_000007.14?report=fasta&from=22725889&to=22732002)
+ 7.[TGFB1](https://www.ncbi.nlm.nih.gov/nuccore/NC_000019.10?report=fasta&from=41330323&to=41353922&strand=true)
+ 8.[MTHFR](https://www.ncbi.nlm.nih.gov/nuccore/NC_000001.11?report=fasta&from=11785723&to=11806103&strand=true)
+ 9.[ESR1](https://www.ncbi.nlm.nih.gov/nuccore/NC_000006.12?report=fasta&from=151654148&to=152129619)
+ 10.[AKT1](https://www.ncbi.nlm.nih.gov/nuccore/NC_000014.9?report=fasta&from=104769349&to=104795748&strand=true)
## Comparative Analysis of Top 10 Genes
![](https://github.com/ahmedtarek26/Top-10-Studied-Genes/blob/main/images/newplot.png)
### GC Contents In DNA
+ GC-content (or guanine-cytosine content) is the percentage of nitrogenous bases in a DNA or RNA molecule 
that are either guanine (G) or cytosine (C)
#### Usefulness
+ In polymerase chain reaction (PCR) experiments, the GC-content of short oligonucleotides known as primers is often used to predict their annealing temperature to the template DNA. 
+ A higher GC-content level indicates a relatively higher melting temperature.
+ DNA with low GC-content is less stable than DNA with high GC-content
![](https://github.com/ahmedtarek26/Top-10-Studied-Genes/blob/main/images/newplot_1.png)
**AKT1** have the most number of **GC** **->** **73.07%** then **APOE** with **65.06%**
### Protein Sequence analysis
![](https://github.com/ahmedtarek26/Top-10-Studied-Genes/blob/main/images/newplot_2.png)
**ESR1** have the most protein length with **158.49k**

>


**EGFR** protein length **64.204k**
### Check for the Count of Amino Acids
Most Common amino acids
+ TP53 -> (**L**, 674), (**S**, 616), (**G**, 477), (**P**, 464), (**R**, 421)
---
+ TNF  -> (**L**, 96), (**S**, 91), (**G**, 79), (**R**, 73), (**P**, 72) 
---
+ EGFR -> (**L**, 6982), (**S**, 5916), (**P**, 3914), (**G**, 3695), (**V**, 3457)
---
+ VEGFA -> (**L**, 589), (**G**, 577), (**S**, 567), (**P**, 541), (**R**, 404) 
---
+ APOE -> (**G**, 131), (**P**, 130), (**S**, 127), (**R**, 119), (**A**, 117)
---
+ IL6 ->  (**L**, 226), (**S**, 191), (**P**, 141), (**G**, 130), (**K**, 125)
---
+ TGFB1 ->  (**L**, 806), (**S**, 749), (**G**, 659), (**P**, 637), (**R**, 597)
---
+ MTHFR ->  (**L**, 715), (**S**, 649), (**G**, 609), (**P**, 603), (**A**, 508) 
---
+ ESR1 ->  (**L**, 18225), (**S**, 14142), (**F**, 10419), (**I**, 9754), (*, 8724)
---
+ AKT1 -> (**G**, 1211), (**P**, 1005), (**L**, 846), (**A**, 801), (**R**, 720)

## Find similarity between them
#### Narative
+ similarity between **APOE** and **IL6** is **78.54%**
+ similarity between **TNF** and **APOE** is **71%**
+ similarity between **MTHFR** and **VEGFA** is **70.9%**
+ similarity between **TGFB1** and **AKT1** is **67%**
+ similarity between **TP53** and **MTHFR** is **66.5%**
+ similarity between **TP53** and **VEGFA** is **0.35%**
---
similarity between **EGFR** and **ESR1** for the **first 35000** is **63.82%**
## 3D Structure
you can see them in the code
