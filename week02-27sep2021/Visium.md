# Exercise 2b

### Github Usernames

* cell0126 (Wiona Glänzer)
* licrone (Lisa)
* lorenzoguerci (Lorenzo Guerci)

### Circular sequencing (CirSeq)

Summary:

Virual populations are highly diverse and evolve rapidly. As NGS is not accurate enough to detect rare mutations in viruses, CirSeq introduces an additional error correction mechanism. RNA fragments are circulized and then cDNA is produced via rolling circle reverse transcription. As there are now multiple linked repeats for one RNA fragment, their sequences can be compared and sequencing errors can be detected. In this way a consensus sequence for the RNA fragment is determined.

![Scheme](https://www.illumina.com/content/dam/illumina-marketing/images/tools/sequencing/cirseq.png)

Technology:
* virus amplification to increase the viral RNA content
* fragmentation and circularisation of RNA
* rolling-circle reverse transcription creates linked repeats of genomic material from one individual virus in the population
* cloned by stadard mRNA sequencing
* Illumina MiSeq sequencing

Application:
Understanding the rapid evolution of virus populations including low-frequency mutations which are inadequatley detected with NGS. Additionally to traditional sequencing, more complex information can be obtained as for exmaple the link between fitness values and the corresponding mutations or the definition of mutation rates within a population.

Statistics:
* As part of the method: comparing the different repeats helps to differentiate between sequencing errors and low-frequency mutations;  quality score Q=-10log(e), where e is the error probability
* To show the usefulness and accuracy of the method: mutation frequencies and transition-to-transversion ratios of polio viruses was determined and compared to previous and expected results, fitness distributions for mutations
* For the study of the virus population: one-sided binomial test to determine significance of mutations, p value to determine wheter the mutation being beneficial is significant

#### Sources:
* [Original paper](https://www.nature.com/articles/nature12861)
* [Summary by Illumina and image source](https://www.illumina.com/science/sequencing-method-explorer/kits-and-arrays/cirseq.html)


# Exercise 2a

### 10x Visium
10x Visium is a spatial transcriptomics technique that combines tissue visualization and RNA sequencing. The method is based on a slide that provides four capture areas with 5000 barcoded spots containing oligosaccharides. Fresh frozen samples are placed on these capturing areas. The tissue can be stained and imaged by routine histology methods. Afterwards the tissue is fixed and permeabalized and the released RNA binds to the oligonucleotides, cDNA is synthesized and sequenced by standard short sequencing methods.

![Company work flow](https://res.cloudinary.com/dlg7p2kji/image/upload/f_auto,q_auto,w_680,h_510,c_limit/v1578967934/blog/10x_BR060_Visium-Spatial-Brochure_Figures-01.jpg)

### Resources:
* [10x Company Website](https://www.10xgenomics.com/products/spatial-gene-expression)
* [Description by FGZ](https://fgcz.ch/omics_areas/transcriptomics_uc/applications/Spatial-transcriptomics.html)
* [An application of the technique - see supplementary material](https://www.biorxiv.org/content/10.1101/2020.11.17.386458v2)
* [An explanation video by 10x](https://www.youtube.com/watch?v=VwNk4d-0RJc)

(Side note: part a is included here as the team submission method did not work for us)
