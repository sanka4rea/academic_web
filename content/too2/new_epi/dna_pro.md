+++
# Date this page was created.
date = "2018-04-11"

# Project title.
 title = "DNA-Protein Interactions"

weight = 50
# Project summary to display on homepage.
 summary = "Including: HT-SELEX Analysis, DNase-seq Analysis, ChIO-seq Analysis."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "tools/geno/dna_pro.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["epigenomics"]

# Optional external URL for project (replaces project detail page).
#external_link = "https://cityu-bioinformatics.netlify.com/tools/seq_new/sequence alignment/"


# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"


+++
---

<img src="/img/tools/geno/dna_pro.jpg" width="500", height="300" alt="dnastr" align="center">

<span id="top"></span>

{{% toc %}}

<p align="justify">DNA-binding proteins are proteins that have DNA-binding domains and thus have a specific or general affinity for single- or double-stranded DNA. Sequence-specific DNA-binding proteins generally interact with the major groove of B-DNA, because it exposes more functional groups that identify a base pair. However, there are some known minor groove DNA-binding ligands such as netropsin, distamycin, Hoechst 33258, pentamidine, DAPI and others.

# HT-SELEX Analysis

### AptaTools

<p align="justify">Provides a complete and comprehensive analysis pipeline for HT-SELEX data and comprises four fully automated core steps: data preprocessing, sequence analysis, cluster extraction, and data visualization. At the same time, AptaTools is modular enough to be extended with additional features. This pipeline is capable of handling most of the file formats generated by modern high throughput sequencing devices including paired-end data but also supports already pre-partitioned pools as input.

[**Official Website**](https://www.ncbi.nlm.nih.gov/CBBresearch/Przytycka/index.cgi)  

**Publications**

* (2015 Nucleic Acids Res) [Large scale analysis of the mutational landscape in HT-SELEX improves aptamer discovery](https://www.ncbi.nlm.nih.gov/pubmed/25870409).  

* (2014 Res Comput Mol Bio)[AptaCluster - A Method to Cluster HT-SELEX Aptamer Pools and Lessons from its Application.](https://www.ncbi.nlm.nih.gov/pubmed/25558474)

**Institution(s)** 

National Center of Biotechnology Information, National Library of Medicine, NIH, Bethesda, MD, USA

---

### SelexGLM

<p align="justify">Determines the binding free energy coefficients. SelexGLM employs a generalized model based on the Poisson distribution. It allows to uncover and characterize intrinsic differences in DNA binding specificity between androgen receptor (AR) and glucocorticoid receptor (GR). This tool is able to take into account offsets within the probe that partially cover the fixed sequences upstream and downstream of the variable region.

[**Official Website**](https://github.com/BussemakerLab/SelexGLM)  

**Publications**

* (2017 Genome Res) [SelexGLM differentiates androgen and glucocorticoid receptor DNA-binding preference over an extended binding site.](https://genome.cshlp.org/content/28/1/111).  


**Institution(s)** 

Department of Biochemistry, Carver College of Medicine, University of Iowa, IA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# DNase-seq Analysis

<p align="justify">Sequencing of DNase I hypersensitive sites (DNase-seq) is a powerful technique for identifying cis-regulatory elements across the genome. Many people currently analyzing DNase-seq data are using tools designed for ChIP-seq work, but may be inappropriate for DNase-seq data.

### HOMER

<p align="justify">Performs peak finding and downstream data analysis for next-generation sequencing analysis. HOMER affords several tools and methods to make use of ChIP-Seq, GRO-Seq, RNA-Seq, DNase-Seq, Hi-C and other types of functional genomics sequencing data sets. This software offers support to UCSC visualization, peaks annotation, quantification of transcripts and repeats or differential features, enrichment and expression.

[**Official Website**](http://homer.ucsd.edu/homer/ngs/index.html) 

**Publications**

* (Heinz et al., 2010) [Simple combinations of lineage-determining transcription factors prime cis-regulatory elements required for macrophage and B cell identities]( https://www.ncbi.nlm.nih.gov/pubmed/20513432). Mol Cell.

**Institution(s)**   

Department of Cellular and Molecular Medicine, University of California, San Diego, La Jolla, CA, USA; Department of Medicine, University of California, San Diego, La Jolla, CA, USA

---

### DFilter

<p align="justify">Detects functional signals in tag profiles from different assays such as histone ChIP-seq, TF ChiP-seq, DNase-seq and FAIRE-seq. DFilter is based on a single receiver operating characteristic – area under the curve (ROC-AUC) optimizing algorithm. This software suits for genomic signals of individual cell types diluted in cellular mixture because the proportion of marginal signals can be mistaken for noise by suboptimal algorithms.

[**Official Website**](http://collaborations.gis.a-star.edu.sg/~cmb6/kumarv1/dfilter/) 

**Publications**

* (2013 Nat Biotechnol) [Uniform, optimal signal processing of mapped deep-sequencing data.](https://www.ncbi.nlm.nih.gov/pubmed/23770639)

**Institution(s)**   

Computational and Systems Biology, Genome Institute of Singapore, Singapore

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

# ChIP-seq Analysis

<p align="justify">Chromatin immunoprecipitation followed by sequencing (ChIP-seq), first described in 2007 (Barski et al., 2007; Johnson et al., 2007; Mikkelsen et al., 2007; Robertson et al., 2007), allows in vivo determination of where a protein binds the genome, which can be transcription factors, DNA-binding enzymes, histones, chaperones, or nucleosomes (Park, 2009; Furey, 2012).

## <font color=#CD5555 face="黑体">De novo assembly</font>

### denovochipseq

<p align="justify">A computational pipeline to extract the transcription factor binding motifs from ChIP-seq data, assuming no reference genome is available. denovochipseq combines de novo assembly with statistical tests enabling motif discovery without the use of a reference genome. We validate the performance of denovochipseq using human and mouse data. Analysis of fly data indicates that denovochipseq outperforms alignment based methods that utilize closely related species.

[**Official Website**](https://github.com/yuhaow/denovochipseq)  

[**Github**]( https://github.com/yuhaow/denovochipseq/issues) 

**Publications**

* (He et al., 2015) [De novo ChIP-seq analysis]( https://www.ncbi.nlm.nih.gov/pubmed/26400819).  Genome Biol.

**Institution(s)** 

Department of Human Genetics, The University of Chicago, CLSC, Chicago, IL, USA; Computational Biology Department, Carnegie Mellon University, Pittsburgh, PA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Peak calling</font>

### HOMER

<p align="justify">Performs peak finding and downstream data analysis for next-generation sequencing analysis. HOMER affords several tools and methods to make use of ChIP-Seq, GRO-Seq, RNA-Seq, DNase-Seq, Hi-C and other types of functional genomics sequencing data sets. This software offers support to UCSC visualization, peaks annotation, quantification of transcripts and repeats or differential features, enrichment and expression.

[**Official Website**](http://homer.ucsd.edu/homer/ngs/index.html) 

**Publications**

* (Heinz et al., 2010) [Simple combinations of lineage-determining transcription factors prime cis-regulatory elements required for macrophage and B cell identities]( https://www.ncbi.nlm.nih.gov/pubmed/20513432). Mol Cell.

**Institution(s)**   

Department of Cellular and Molecular Medicine, University of California, San Diego, La Jolla, CA, USA; Department of Medicine, University of California, San Diego, La Jolla, CA, USA

---

### MACS
<p align="justify">Analyzes data generated by short read sequencers. MACS is a standalone software dedicated to the forecasting of protein-DNA interaction sites from ChIP-Seq. The application is able to: (i) model the distance d and shifting tags by d/2 to enable the spatial resolution of the predicted sites; (ii) capture local biases in the genome by exploiting a dynamic λ local parameter and (iii) evaluate the false discovery rate (FDR) for each detected peak.

[**Official Website**](https://github.com/taoliu/MACS)  

[**Github**]( https://github.com/taoliu/MACS/) 

**Publications**

* (Zhang et al., 2008) [Model-based analysis of ChIP-Seq (MACS)]( https://www.ncbi.nlm.nih.gov/pubmed/18798982).  Genome Biol.

**Institution(s)**   

Department of Biostatistics and Computational Biology, Dana-Farber Cancer Institute and Harvard School of Public Health, Boston, MA, USA.

---

### SICER

<p align="justify">Recognizes ChIP-enriched regions in histone modification data. SCIER is based on a mathematical theory for the score distribution in a genomic background model of random reads. It finds spatial clusters, large and small, unlikely to appear by chance. This tool is able to deal with the enrichment context of a local window in determining its significance. It assists users to reduce the sampling fluctuations in the control library.

[**Official Website**](https://home.gwu.edu/~wpeng/Software.htm) 

**Publications**

* (Zang et al., 2009)[ A clustering approach for identification of enriched domains from histone modification ChIP-Seq data]( https://www.ncbi.nlm.nih.gov/pubmed/19505939). Bioinformatics.

**Institution(s)**  

Department of Physics, The George Washington University, Washington, DC, USA; Laboratory of Molecular Immunology, National Heart Lung and Blood Institute, NIH, Bethesda, MD, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">Differential peak calling</font>

### DiffBind

<p align="justify">Allows processing ChIP-seq data enriched for genomic loci where specific protein/DNA binding occurs. DiffBind is applicable to peak sets identified by ChIP-seq peak callers and aligned sequence read datasets. It is able to find sites that are differentially bound between two sample groups. This tool is useful to manage the results of multiple peak callers. It can serve to merge peak sets and count sequencing reads overlapping intervals in peak sets.

[**Official Website**](http://bioconductor.org/packages/release/bioc/html/DiffBind.html)  

[**Documentation**](http://bioconductor.org/packages/release/bioc/manuals/DiffBind/man/DiffBind.pdf) 

**Publications**

* (Ross-Innes et al., 2012) [Differential oestrogen receptor binding is associated with clinical outcome in breast cancer]( https://www.ncbi.nlm.nih.gov/pubmed/22217937).  Nature.

**Institution(s)**   

Cancer Research UK, Cambridge Research Institute, Li Ka Shing Centre, Cambridge, UK; UCL Cancer Institute, University College London, London, UK.

---

### GenoGAM

<p align="justify">Offers methods dedicated to ChIP-Seq factorial design experiments modelization. GenoGAM is an R package employing generalized additive models to perform statistical analysis of genome-wide data. It provides base-level and region-level significance testing with controlled type I error rate. Additionally, the software is able to fit generalized additive models (GAMs) to very long longitudinal data such as whole chromosomes at base-pair resolution.

[**Official Website**](https://github.com/gstricker/fastGenoGAM)  

[**Documentation**]( https://www.bioconductor.org/packages/release/bioc/vignettes/GenoGAM/inst/doc/GenoGAM.pdf) 

**Publications**

* (Stricker, 2016) [Genome-wide generalized additive models]( https://doi.org/10.1101/047464).  BioRxiv.
* (Stricker et al., 2017) [GenoGAM: genome-wide generalized additive models for ChIP-Seq analysis]( https://www.ncbi.nlm.nih.gov/pubmed/28369277).  Bioinformatics.
* (Stricker et al., 2018) [GenoGAM 2.0: Scalable and efficient implementation of genome-wide generalized additive models for gigabase-scale genomes]( https://doi.org/10.1101/265595). BioRxiv.

**Institution(s)**   

Department of Informatics, Technical University Munich, Munich, Germany

---

### MAnorm

<p align="justify">A simple and effective method for quantitative comparison of ChIP-Seq data sets describing transcription factor binding sites and epigenetic modifications. The quantitative binding differences inferred by MAnorm showed strong correlation with both the changes in expression of target genes and the binding of cell type-specific regulators.

[**Official Website**](http://bcb.dfci.harvard.edu/~gcyuan/MAnorm/MAnorm.htm)

**Publications**

* (Shao et al., 2012) [MAnorm: a robust model for quantitative comparison of ChIP-Seq data sets]( https://www.ncbi.nlm.nih.gov/pubmed/22424423).  Genome Biol.

**Institution(s)**  

Departments of Pediatric Oncology and Computational Biology, Dana-Farber Cancer Institute, Boston, MA, USA, Division of Pediatric Hematology-Oncology, The Karp Family Research Laboratories, Children's Hospital, Boston, MA, USA and Division of Cell and Molecular Biology, Department of Biology, Boston University, Boston, MA, USA

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

---

## <font color=#CD5555 face="黑体">De novo motif discovery</font>

### HOMER

<p align="justify">Performs peak finding and downstream data analysis for next-generation sequencing analysis. HOMER affords several tools and methods to make use of ChIP-Seq, GRO-Seq, RNA-Seq, DNase-Seq, Hi-C and other types of functional genomics sequencing data sets. This software offers support to UCSC visualization, peaks annotation, quantification of transcripts and repeats or differential features, enrichment and expression.

[**Official Website**](http://homer.ucsd.edu/homer/ngs/index.html) 

**Publications**

* (Heinz et al., 2010) [Simple combinations of lineage-determining transcription factors prime cis-regulatory elements required for macrophage and B cell identities]( https://www.ncbi.nlm.nih.gov/pubmed/20513432). Mol Cell.

**Institution(s)**   

Department of Cellular and Molecular Medicine, University of California, San Diego, La Jolla, CA, USA; Department of Medicine, University of California, San Diego, La Jolla, CA, USA

---

### Weeder

<p align="justify">Falls into the motif enumeration family of motif discovery tools in which the occurrence of motifs in the query sequences are counted and, in this case, compared to a pre-calculated set of genome specific background motifs. This has the benefit of not having to construct a background set of sequences (no easy task). Weeder was initially used to identify common motifs in defined promoter regions, but evolved to consider first ChIP-chip and then ChIP-seq data.

[**Official Website**](https://omictools.com/weeder-tool) 

**Publications**

* Pavesi et al., 2004) [Weeder Web: discovery of transcription factor binding sites in a set of sequences from co-regulated genes]( https://www.ncbi.nlm.nih.gov/pubmed/15215380). Nucleic Acids Res.
* (Pavesi et al., 2006) [MoD Tools: regulatory motif discovery in nucleotide sequences from co-regulated or homologous genes]( https://www.ncbi.nlm.nih.gov/pubmed/16845071). Nucleic Acids Res.
* (Zambelli et al., 2014) [Using Weeder, Pscan, and PscanChIP for the Discovery of Enriched Transcription Factor Binding Site Motifs in Nucleotide Sequences]( https://www.ncbi.nlm.nih.gov/pubmed/25199791). Curr Protoc Bioinformatics.

**Institution(s)**   

University of Milan, Italy

---

### kmerHMM

<p align="justify">Discovers DNA motifs on protein binding microarray (PBM) data. kmerHMM is a computational pipeline for PBM motif discovery in which hidden markov models (HMMs) are trained to model DNA motifs, and Belief Propagation is used to elucidate multiple motif models from each trained HMM. The software model the dependence between adjacent nucleotide positions and can also deduce multiple binding modes for a given transcription factor (TF).

[**Official Website**](http://www.cs.toronto.edu/~wkc/kmerHMM/)  

**Publications**

* (Wong et al., 2013) [DNA motif elucidation using belief propagation]( https://www.ncbi.nlm.nih.gov/pubmed/23814189).  Nucleic Acids Res.

**Institution(s)**  

Department of Computer Science, University of Toronto, Toronto, ON, Canada; Terrence Donnelly Centre for Cellular and Biomolecular Research, University of Toronto, Toronto, ON, Canada.

[<i class="fa fa-hand-o-up fa-1x "></i>Top](#top)

# Find more tools: [**OMICTOOLS**](https://omictools.com/genomics2-category)

[*Image Citation*](https://www.slideshare.net/mandeepkaur151/protein-dna-interactions)

---