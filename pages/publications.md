---
layout: page-publications
title: "Publications"
header:
     image_fullwidth: "dna.jpg"
permalink: "/publications/"
---
<!--more-->

<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="https://genome.cshlp.org/content/early/2018/04/12/gr.226852.117">A novel k-mer set memory (KSM) motif representation improves regulatory variant prediction. </a></b></p>
        <p><font size="2">The representation and discovery of transcription factor (TF) sequence binding specificities is critical for understanding gene regulatory networks and interpreting the impact of disease-associated non-coding genetic variants. We present a novel TF binding motif representation, the k-mer set memory (KSM), which consists of a set of aligned k-mers that are over-represented at TF binding sites, and a new method called KMAC for de novo discovery of KSMs. We find that KSMs more accurately predict in vivo binding sites than position weight matrix (PWM) models and other more complex motif models across a large set of ChIP-seq experiments. Furthermore, KSMs outperform PWMs and more complex motif models in predicting in vitro binding sites. KMAC also identifies correct motifs in more experiments than five state-of-the-art motif discovery methods. In addition, KSM derived features outperform both PWM and deep learning model derived sequence features in predicting differential regulatory activities of expression quantitative trait loci (eQTL) alleles. Finally, we have applied KMAC to 1600 ENCODE TF ChIP-seq datasets and created a public resource of KSM and PWM motifs. We expect that the KSM representation and KMAC method will be valuable in characterizing TF binding specificities and in interpreting the effects of non-coding genetic variations.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/ksm.png" alt="">
        <p> <font size="2">Guo Y, Tian K, Zeng H, Guo X, Gifford DK.
        <br> <i>
Genome Res</i>. 2018 Apr 13. pii: gr.226852.117. doi: 10.1101/gr.226852.117</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="http://dx.plos.org/10.1371/journal.pone.0187046">DNase-capture reveals differential transcription factor binding modalities. </a></b></p>
        <p><font size="2">We describe DNase-capture, an assay that increases the analytical resolution of DNase-seq by focusing its sequencing phase on selected genomic regions. We introduce a new method to compensate for capture bias called BaseNormal that allows for accurate recovery of transcription factor protection profiles from DNase-capture data. We show that these normalized data allow for nuanced detection of transcription factor binding heterogeneity with as few as dozens of sites.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/journal.pone.0187046.g001.PNG" alt="">
        <p> <font size="2">Kang D, Sherwood R, Barkal A, Hashimoto T, Engstrom L, Gifford D.
        <br> <i>
PLoS One</i>. 2017 Dec 28;12(12):e0187046. doi: 10.1371/journal.pone.0187046. eCollection 2017.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/humu.23280">Working toward precision medicine: Predicting phenotypes from exomes in the Critical Assessment of Genome Interpretation (CAGI) challenges.  </a></b></p>
        <p><font size="2">Precision medicine aims to predict a patient's disease risk and best therapeutic options by using that individual's genetic sequencing data. The Critical Assessment of Genome Interpretation (CAGI) is a community experiment consisting of genotype-phenotype prediction challenges; participants build models, undergo assessment, and share key findings. For CAGI 4, three challenges involved using exome-sequencing data: Crohn's disease, bipolar disorder, and warfarin dosing. Previous CAGI challenges included prior versions of the Crohn's disease challenge. Here, we discuss the range of techniques used for phenotype prediction as well as the methods used for assessing predictive models. Additionally, we outline some of the difficulties associated with making predictions and evaluating them. The lessons learned from the exome challenges can be applied to both research and clinical efforts to improve phenotype prediction from genotype. In addition, these challenges serve as a vehicle for sharing clinical and research exome data in a secure manner with scientists who have a broad range of expertise, contributing to a collaborative effort to advance our understanding of genotype-phenotype relationships.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/cagi_exome.png" alt="">
        <p> <font size="2">Daneshjou R et al.
        <br> <i>
Hum Mutat</i>. 2017 Sep;38(9):1182-1192. doi: 10.1002/humu.23280. Epub 2017 Jul 7.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/Seq2betterSeq.pdf">Sequence to Better Sequence: Continuous Revision of Combinatorial Structures  </a></b></p>
        <p><font size="2">We present a model that, after learning on observations
of (sequence, outcome) pairs, can be
efficiently used to revise a new sequence in order
to improve its associated outcome. Our framework
requires neither example improvements,
nor additional evaluation of outcomes for proposed
revisions. To avoid combinatorial-search
over sequence elements, we specify a generative
model with continuous latent factors, which is
learned via joint approximate inference using a
recurrent variational autoencoder (VAE) and an
outcome-predicting neural network module. Under
this model, gradient methods can be used to
efficiently optimize the continuous latent factors
with respect to inferred outcomes. By appropriately
constraining this optimization and using the
VAE decoder to generate a revised sequence, we
ensure the revision is fundamentally similar to
the original sequence, is associated with better
outcomes, and looks natural. These desiderata
are proven to hold with high probability under
our approach, which is empirically demonstrated
for revising natural language sentences.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/seq2betterseq.png" alt="">
        <p> <font size="2">Mueller J,  Gifford DK,  Jaakkola T.
        <br> <i>International Conference on Machine Learning</i>, pp. 2536-2544. 2017.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/persistentTrends.pdf">Modeling Persistent Trends in Distributions</a></b></p>
        <p><font size="2">We present a nonparametric framework to model a short sequence of probability distributions
that vary both due to underlying effects of sequential progression and confounding
noise. To distinguish between these two types of variation and estimate the sequentialprogression
effects, our approach leverages an assumption that these effects follow a persistent
trend. This work is motivated by the recent rise of single-cell RNA-sequencing
experiments over a brief time course, which aim to identify genes relevant to the progression
of a particular biological process across diverse cell populations. While classical
statistical tools focus on scalar-response regression or order-agnostic differences between
distributions, it is desirable in this setting to consider both the full distributions as well as
the structure imposed by their ordering. We introduce a new regression model for ordinal
covariates where responses are univariate distributions and the underlying relationship re-
flects consistent changes in the distributions over increasing levels of the covariate. This
concept is formalized as a trend in distributions, which we define as an evolution that is
linear under the Wasserstein metric. Implemented via a fast alternating projections algorithm,
our method exhibits numerous strengths in simulations and analyses of single-cell
gene expression data.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/trends.png" alt="">
        <p> <font size="2">Mueller J,  Jaakkola T, Gifford DK.
        <br> <i>Journal of the American Statistical Association</i> 2017</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/journal.pone.0179411">Differential chromatin profiles partially determine transcription factor binding </a></b></p>
        <p><font size="2">We characterize how genomic variants that alter chromatin accessibility influence regulatory factor binding with a new method called DeltaBind that predicts condition specific factor binding more accurately than other methods based on DNase-seq data. Using DeltaBind and DNase-seq experiments we predicted the differential binding of 18 factors in K562 and GM12878 cells with an average precision of 28% at 10% recall, with the prediction of individual factors ranging from 5% to 65% precision. We further found that genome variants that alter chromatin accessibility are not necessarily predictive of altering proximal factor binding. Taken together these findings suggest that DNase-seq or ATAC-seq Quantitative Trait Loci (dsQTLs), while important, must be considered in a broader context to establish causality for phenotypic changes.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/pone.0179411.g001.jpg" alt="">
        <p> <font size="2">Chen R and Gifford DK.
        <br> <i>PLoS One.</i> 2017 Jul 13;12(7):e0179411. doi: 10.1371/journal.pone.0179411. eCollection 2017.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/zeng-2017-NAR.pdf ">Predicting the impact of non-coding variants on DNA
methylation.</a></b></p>
        <p><font size="2">DNA methylation plays a crucial role in the establishment
of tissue-specific gene expression and the
regulation of key biological processes. However, our
present inability to predict the effect of genome sequence
variation on DNA methylation precludes a
comprehensive assessment of the consequences
of non-coding variation. We introduce CpGenie, a
sequence-based framework that learns a regulatory
code of DNA methylation using a deep convolutional
neural network and uses this network to predict the
impact of sequence variation on proximal CpG site
DNA methylation. CpGenie produces allele-specific
DNA methylation prediction with single-nucleotide
sensitivity that enables accurate prediction of methylation
quantitative trait loci (meQTL). We demonstrate
that CpGenie prioritizes validated GWAS SNPs,
and contributes to the prediction of functional noncoding
variants, including expression quantitative
trait loci (eQTL) and disease-associated mutations.
CpGenie is publicly available to assist in identifying
and interpreting regulatory non-coding variants.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/gkx177fig1.jpg" alt="">
        <p> <font size="2">Zeng H and Gifford DK.
        <br> <i>Nucleic Acids Res.</i> 2017 Jun 20;45(11):e99. doi: 10.1093/nar/gkx177.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/Zeng_et_al-2017-Human_Mutation.pdf">Accurate eQTL prioritization with an ensemble-based framework </a></b></p>
        <p><font size="2">We present a novel ensemble-based computational framework, EnsembleExpr, that achieved the best performance in the Fourth Critical Assessment of Genome Interpretation expression quantitative trait locus "(eQTL)-causal SNPs" challenge for identifying eQTLs and prioritizing their gene expression effects. eQTLs are genome sequence variants that result in gene expression changes and are thus prime suspects in the search for contributions to the causality of complex traits. When EnsembleExpr is trained on data from massively parallel reporter assays, it accurately predicts reporter expression levels from unseen regulatory sequences and identifies sequence variants that exhibit significant changes in reporter expression. Compared with other state-of-the-art methods, EnsembleExpr achieved competitive performance when applied on eQTL datasets determined by other protocols. We envision EnsembleExpr to be a resource to help interpret noncoding regulatory variants and prioritize disease-associated mutations for downstream validation.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/Zeng-2017-Accurate-eQTL.png" alt="">
        <p> <font size="2">Zeng H, Edwards MD, Guo Y, Gifford DK.
        <br> <i>Hum Mutat.</i> 2017 Feb 21, doi:
10.1002/humu.23198. </font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/Kreimer_et_al-2017-Human_Mutation.pdf ">Predicting gene expression in massively parallel reporter assays: A comparative study. </a></b></p>
        <p><font size="2">In many human diseases, associated genetic changes tend to occur within noncoding regions, whose effect might be related to transcriptional control. A central goal in human genetics is to understand the function of such noncoding regions: given a region that is statistically associated with changes in gene expression (expression quantitative trait locus [eQTL]), does it in fact play a regulatory role? And if so, how is this role “coded” in its sequence? These questions were the subject of the Critical Assessment of Genome Interpretation eQTL challenge. Participants were given a set of sequences that flank eQTLs in humans and were asked to predict whether these are capable of regulating transcription (as evaluated by massively parallel reporter assays), and whether this capability changes between alternative alleles. Here, we report lessons learned from this community effort. By inspecting predictive properties in isolation, and conducting meta-analysis over the competing methods, we find that using chromatin accessibility and transcription factor binding as features in an ensemble of classifiers or regression models leads to the most accurate results. We then characterize the loci that are harder to predict, putting the spotlight on areas of weakness, which we expect to be the subject of future studies.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/Predicting-gene-express-Kreimer.png" alt="">
        <p> <font size="2">Kreimer A, Zeng H, Edwards MD, Guo Y, Tian K, Shin S, Welch R, Wainberg M, Mohan R, Sinnott-Armstrong NA, Li Y, Eraslan G, Amin TB, Goke J, Mueller NS, Kellis M, Kundaje A, Beer MA, Keles S, Gifford DK, Yosef N.
        <br> <i>Hum Mutat.</i> 2017 Feb 21., doi:
10.1002/humu.23197.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/Guo-Jan-2017-BMC-Genomics-Modular.pdf ">Modular combinatorial binding among human trans-acting factors reveals direct and indirect factor binding.</a></b></p>
        <p><font size="2">BACKGROUND:

The combinatorial binding of trans-acting factors (TFs) to the DNA is critical to the spatial and temporal specificity of gene regulation. For certain regulatory regions, more than one regulatory module (set of TFs that bind together) are combined to achieve context-specific gene regulation. However, previous approaches are limited to either pairwise TF co-association analysis or assuming that only one module is used in each regulatory region.
RESULTS:

We present a new computational approach that models the modular organization of TF combinatorial binding. Our method learns compact and coherent regulatory modules from in vivo binding data using a topic model. We found that the binding of 115 TFs in K562 cells can be organized into 49 interpretable modules. Furthermore, we found that tens of thousands of regulatory regions use multiple modules, a structure that cannot be observed with previous hard clustering based methods. The modules discovered recapitulate many published protein-protein physical interactions, have consistent functional annotations of chromatin states, and uncover context specific co-binding such as gene proximal binding of NFY + FOS + SP and distal binding of NFY + FOS + USF. For certain TFs, the co-binding partners of direct binding (motif present) differs from those of indirect binding (motif absent); the distinct set of co-binding partners can predict whether the TF binds directly or indirectly with up to 95% accuracy. Joint analysis across two cell types reveals both cell-type-specific and shared regulatory modules.
CONCLUSIONS:
Our results provide comprehensive cell-type-specific combinatorial binding maps and suggest a modular organization of combinatorial binding.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/Guo-2016-Modular-combinatorial.jpg" alt="">
        <p> <font size="2">Guo Y, Gifford DK.
        <br> <i>BMC Genomics.</i> 2017 Jan 6;18(1):45., doi:
10.1186/s12864-016-3434-3.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


### 2016

* <a href="http://groups.csail.mit.edu/cgs/pubs/neuron2016.pdf">Expression of Terminal Effector Genes in Mammalian Neurons Is Maintained by a Dynamic Relay of Transient Enhancers. </a> Rhee HS, Closser M, Guo Y, Bashkirova EV, Tan CG, Gifford DK, Wichterle H.
_Neuron._ 2016 Dec 21;92(6):1252-1265., doi: 10.1016/j.neuron.2016.11.037.

* <a href="http://groups.csail.mit.edu/cgs/pubs/RNA-2016-Gould-1522-34.pdf">Identification of new branch points and unconventional introns in Saccharomyces cerevisiae.</a> Gould GM, Paggi JM, Guo Y, Phizicky DV, Zinshteyn B, Wang ET, Gilbert WV, Gifford DK, Burge CB.
_RNA._ 2016 Oct;22(10):1522-34., doi: 10.1261/ma.057216.116.

* <a href="http://groups.csail.mit.edu/cgs/pubs/Genome%20Res.-2016-Hashimoto-1430-40.pdf">A Synergistic DNA Logic Predicts Genome-wide Chromatin Accessibility</a> Hashimoto TB, Sherwood RI, Kang DD, Barkal AA, Zeng H, Emons BJM, Srinivasan S, Rajagopal N, Jaakkola T, and Gifford DK. 
_Genome Research_, doi: 10.1101/gr.199778.115

* <a href="http://groups.csail.mit.edu/cgs/pubs/hashimoto16.pdf">Learning Population-Level Diffusions with Generative Recurrent Networks</a> Hashimoto TB, Gifford DK, Jaakkola TS. 
_Proceedings of the 33 rd International Conference on Machine Learning (ICML)_. (2016)

* <a href="http://bioinformatics.oxfordjournals.org/content/32/12/i121.long">Convolutional neural network architectures for predicting DNA-protein binding."</a> Zeng H, Edwards MD, Liu G, Gifford DK.
_Bioinformatics._ 2016 Jun 15;32(12):i121-i127. doi: 10.1093/bioinformatics/btw255.

* <a href="http://groups.csail.mit.edu/cgs/pubs/PNAS-2016-Ferreira-5364-9.pdf">A distant trophoblast-specific enhancer controls HLA-G expression at the maternal-fetal interface.</a> Ferreira LM, Meissner TB, Mikkelsen TS, Mallard W, O'Donnell CW, Tilburgs T, Gomes HA, Camahort R, Sherwood RI, Gifford DK, Rinn JL, Cowan CA, Strominger JL. 
_Proc Natl Acad Sci U.S.A ._ 2016 May 10;113(19):5364-9. doi: 10.1073/pnas.1602886113. 

* <a href="http://journals.plos.org/plosone/article/asset?id=10.1371%2Fjournal.pone.0152683.PDF">Cas9 Functionally Opens Chromatin</a> Barkal AA Srinivasan S, Hashimoto T, Gifford DK, Sherwood RI. 
_PLoS One._ 2016 Mar 31;11(3):e0152683. 

* <a href="http://groups.csail.mit.edu/cgs/pubs/nbt.3468.pdf">High-throughput mapping of regulatory DNA</a> Rajagopal, Nisha, Sharanya Srinivasan, Kameron Kooshesh, Yuchun Guo, Matthew D. Edwards, Budhaditya Banerjee, Tahin Syed, Bart JM Emons, David K. Gifford, and Richard I. Sherwood. 
_Nature Biotechnology_ 34, 167–174 (2016) 

* <a href="http://groups.csail.mit.edu/cgs/pubs/Bioinformatics-2015-Zeng-bioinformatics_btv565.pdf">GERV: a statistical method for generative evaluation of regulatory variants for transcription factor binding</a> H. Zeng, T. Hashimoto, D.D. Kang, D.K. Gifford.
_Bioinformatics_ 32 (4): 490-496 (2016)

### 2015

* <a href="http://groups.csail.mit.edu/cgs/pubs/pone.0122420.pdf">High resolution mapping of enhancer-promoter interactions</a> Christopher Reeder, Michael Closser, Huay Mei Poh, Kuljeet Sandhu,Hynek Wichterle, David Gifford.
_PLOS ONE._ doi:10.1371/journal.pone.0122420 May 13, 2015

### 2014

* <a href="http://groups.csail.mit.edu/cgs/pubs/nbt.3082.pdf">Long-term persistence and development of induced pancreatic beta cells generated by lineage conversion of acinar cells"</a> Weida Li, Claudia Cavelti-Weder, Yinying Zhang, Kendell Clement, Scott Donovan, Gabriel Gonzalez, Jiang Zhu, Marianne Stemann, Ke Xu, Tatsu Hashimoto, Takatsugu Yamada, Mio Nakanishi, Yuemei Zhang, Samuel Zeng, David Gifford, Alexander Meissner, Gordon Weir, and Qiao Zhou. 
_Nat Biotechnol._ 2014 Dec;32(12):1223-30. doi: 10.1038/nbt.3082. Epub 2014 Nov 17

* <a href="http://groups.csail.mit.edu/cgs/pubs/nihms618131.pdf">Gene co-regulation by Fezf2 selects neurotransmitter identity and connectivity of corticospinal neurons</a> S. Lodato, B.J. Molyneaux, E. Zuccaro, L.A. Goff, H.H. Chen, W. Yuan, A. Meleski, E. Takahashi, S. Mahony, J.L. Rinn, D.K., P. Arlotta. 
_Nat Neurosci. _, 2014 Aug;17(8):1046-54. doi: 10.1038/nn.3757. Epub 2014 Jul 6  

* <a href="http://groups.csail.mit.edu/cgs/pubs/PNAS-2014-Edwards-1407126111.pdf">Interactions between chromosomal and nonchromosomal elements reveal missing heritability</a> Matthew D. Edwards, Anna Symbor-Nagrabska, Lindsey Dollard, David K. Gifford, Gerald R. Fink. 
_Proc. Natl. Acad. Sci U.S.A._, 2014, May 13. pii: 201407126

* <a href="http://groups.csail.mit.edu/cgs/pubs/journal.pcbi.1003501.pdf">An integrated model of multiple-condition ChIP-Seq data reveals predeterminants of Cdx2 binding"</a> S. Mahony, M. D. Edwards, E. O. Mazzoni, R. I. Sherwood, A. Kakumanu, C. A. Morrison, H. Wichterle, D. K. Gifford . 
_PLoS Comput Biol._ 2014 Mar 27;10(3):e1003501. doi: 10.1371/journal.pcbi.1003501. eCollection 2014 Mar

* <a href="http://groups.csail.mit.edu/cgs/pubs/journal.pcbi.1003494.pdf">Universal count correction for high-throughput sequencing </a> T.B. Hashimoto, M. D. Edwards, D. K. Gifford  
_PLoS Comput Biol._ 2014 Mar 6;10(3):e1003494. doi: 10.1371/journal.pcbi.1003494. eCollection 2014

* <a href="http://groups.csail.mit.edu/cgs/pubs/pone.0089459.pdf">MARIS: method for analyzing RNA following intracellular sorting </a> S. Hrvatin, F. Deng, C. W. O'Donnell, D. K. Gifford, D. A. Melton. 
_PLoS One._ 2014 Mar 3;9(3):e89459. doi: 10.1371/journal.pone.0089459. eCollection 2014

* <a href="http://groups.csail.mit.edu/cgs/pubs/PNAS-2014-Hrvatin-3038-43.pdf">Differentiated human stem cells resemble fetal, not adult, ß cells.</a> S. Hrvatin, C. W. O'Donnell, F. Deng, J. R. Millman, F. W. Pagliuca, P. DiIorio, A. Rezania, D. K. Gifford, D. A. Melton. 
_Proc Natl Acad Sci U.S.A._, 2014 Feb 25;111(8):3038-43. doi: 10.1073/pnas.1400709111. Epub 2014 Feb 10

* <a href="http://groups.csail.mit.edu/cgs/pubs/nbt.2798.pdf">Discovery of directional and nondirectional pioneer transcription factors by modeling DNase profile magnitude and shape</a> R. I. Sherwood, T. Hashimoto, C. W. O'Donnell, D. Lewis, A. A. Barkal, J. P. van Hoff, V. Karun, T. Jaakkola, D. K. Gifford. 
_Nat Biotechnol._ 2014 Feb;32(2):171-8. doi: 10.1038/nbt.2798. Epub 2014 Jan 19

### 2013

* <a href="http://groups.csail.mit.edu/cgs/pubs/mahony-stem-cell-reports.pdf">A Cdx4-Sall4 Regulatory Module Controls the Transition from Mesoderm Formation to Embryonic Hematopoiesis</a> E.J. Paik, S. Mahony, R. M. White, E.N. Price, A. Dibiase, B. Dorjsuren, C. Mosimann, A. J. Davidson, D. Gifford, L. I. Zon. 
_Stem Cell Reports._ 2013 Nov 7;1(5):425-436

* <a href="http://groups.csail.mit.edu/cgs/pubs/nn-3490.pdf">Saltatory remodeling of Hox chromatin in response to rostrocaudal patterning signals</a>
E. O. Mazzoni, S. Mahony, M. Peljto, T. Patel, S. R. Thornton, S. McCuine, C. Reeder, L. A. Boyer, R. A. Young, D. K. Gifford, H. Wichterle
_Nat Neurosci._ 2013 Sep;16(9):1191-8. doi: 10.1038/nn.3490. Epub 2013 Aug 18

* <a href="http://groups.csail.mit.edu/cgs/pubs/mapping-neuronal-diversity.pdf">Neuroscience. Mapping neuronal diversity one cell at a time</a>
H. Wichterle, D. Gifford, E. Mazzoni
_Science_. 2013 Aug 16;341(6147):726-7. doi: 10.1126/science.1235884.

* <a href="http://groups.csail.mit.edu/cgs/pubs/nn-3467.pdf">Synergistic binding of transcription factors to cell-specific enhancers programs motor neuron identity</a>
E.O. Mazzoni, S. Mahony, M. Closser, C. A. Morrison, S. Nedelec, D. J. Williams, D. An, D. K. Gifford, H. Wichterle
_Nat Neurosci_. 2013 Sep;16(9):1219-27. doi: 10.1038/nn.3467. Epub 2013 Jul 21


* <a href="http://groups.csail.mit.edu/cgs/pubs/sprout.pdf">High Resolution Modeling of Chromatin Interactions</a>
C. Reeder, D. Gifford
_Research in Computational Molecular Biology_, 186-198, 2013

* <a href="http://groups.csail.mit.edu/cgs/pubs/gks1034.pdf">A multi-parametric flow cytometric assay to analyze DNA-protein interactions</a>
M. Arbab, S. Mahony, H. Cho, J. M. Chick, P. A. Rolfe, J. P. van Hoff, V. W. Morris, S. P. Gygi, R. L. Maas, D. K. Gifford, R. I. Sherwood
_Nucleic Acids Res._ 2013 Jan. 41(2)



### 2012

* <a href="http://groups.csail.mit.edu/cgs/pubs/science-sep-12.pdf">Global gene deletion analysis exploring yeast filamentous growth</a>
O. Ryan, R. S. Shaprio, C. F. Kurat, D. Mayhew, A. Baryshnikova, B. Chin, Z. Y. Lin, M. J. Cox, F. Vizeacoumar, D. Cheung, S. Bahr, K. Tsui, F. Tebbji, A. Sellam, F. Istel, T. Schwarzmuller T, T. B. Reynolds, K. Kuchler, D. K. Gifford, M. Whiteway, G. Giaever, C. Nislow, M. Costanzo, A. C. Gingras, R. D. Mitra, B. Andrews, G. R. Fink, L. E. Cowen, C Boone
_Science_,  2012 Sep 14'337(6100):1353-6.



* <a href="http://groups.csail.mit.edu/cgs/pubs/journal.pcbi.1002638.pdf">High resolution genome wide binding event finding and motif discovery reveals transcription factor spatial binding constraints.</a>
Y. Guo, S. Mahony, D. K. Gifford.
_PLoS Comput Biol_. 2012 Aug;8(8):e1002638.


* <a href="http://groups.csail.mit.edu/cgs/pubs/pone-0043210.pdf">Ruler arrays reveal haploid genomic structural variation</a>
P. A. Rolfe, D. A. Bernstein, P. Grisafi, D. K. Gifford
_PLoS One_, 2012;7(8):e43210


* <a href="http://groups.csail.mit.edu/cgs/pubs/bts204.pdf">Lineage-based identification of cellular states and expression programs</a>
T. Hashimoto,  T. Jaakkola, R. Sherwood, E.O. Mazzoni, H. Wichterle, D. Gifford
_Bioinformatics_, 2012 Jun 15;28(12):i250-7


* <a href="http://groups.csail.mit.edu/cgs/pubs/1471-2105-13-S6-S8.pdf">High Resolution genetic mapping with pooled sequencing</a>
M. D. Edwards, D. K. Gifford
_BMC Bioinformatics_, 2012 Apr 19l13 Suppl 6:S8

### 2011

* <a href="http://groups.csail.mit.edu/cgs/pubs/nmeth.1775.pdf">Embryonic stem cell-based mapping of developmental transcriptional programs</a>
E. O. Mazzoni, S. Mahony, M. Iacovino, C. A. Morrison, G. Mountoufaris, M. Closser, W. A. Whyte, R. A. Young, M. Kyba, D. K. Gifford, H. Wichterle H.
_Nat Methods_, 2011 Nov 13;8(12):1056-8. doi: 10.1038/nmeth.1775


* <a href="http://groups.csail.mit.edu/cgs/pubs/1471-2105-12-278.pdf">ReadDB provides efficient storage for mapped short reads</a>
P. A. Rolfe, D. K. Gifford
_BMC Bioinformatics_, 2011 Jul 7;12:278.


* <a href="http://groups.csail.mit.edu/cgs/pubs/DowellRecomb2010.pdf">Discovering regulatory overlapping RNA transcripts</a>
T. Danford, R. Dowell,  S Agarwala, P. Grisafi, G. Fink, D. Gifford
_J Comput Biol._, 2011 Mar;18(3):295-303


* <a href="http://groups.csail.mit.edu/cgs/pubs/gb-2011-12-1-r2.pdf">Ligand-dependent dynamics of retinoic acid receptor binding during early neurogenesis</a> S. Mahony, E. O. Mazzoni, S. McCuine, R. A. Young, H. Wichterle, D. K.Gifford.
_Genome Biol._, 2011;12(1):R2. Epub 2011 Jan 13

### 2010

* <a href="http://groups.csail.mit.edu/cgs/pubs/gb-2010-11-10-r108.pdf">Rapid haplotype inference for nuclear families</a>
A. L. Williams, D. E. Housman, M. C. Rinard, D. K. Gifford
_Genome Biol._, 2010;11(10):R108. Epub 2010 Oct 29

* <a href="http://groups.csail.mit.edu/cgs/pubs/btq590.pdf">Discovering homotypic binding events at high spatial resolution</a>
Y. Guo, G. Papachristoudis, R. C. Altshuler, G. K. Gerber, T. S. Jaakkola, D. K. Giffo, S. Mahony
_Bioinformatics_, 2010 Dec 15;26(24):3028-34. Epub 2010 Oct 21

* <a href="http://groups.csail.mit.edu/cgs/pubs/nihms-236928.pdf">Global control of motor neuron topography mediated by the repressive actions of a single hox gene</a>
H. Jung, J. Lacombe, E.O. Mazzoni, K. F. Liem Jr, J. Grinstein, S. Mahony, D. Mukhopadhyay,  D. K.  Gifford, R. A. Young, K. V. Anderson, H. Wichterle, J. S. Dasen
_Neuron_, 2010 Sep 9;67(5):781-96


* <a href="http://groups.csail.mit.edu/cgs/pubs/pbio.1000523.pdf">Control of transcription by cell size</a>
C. Y. Wu, P. A. Rolfe, D. K. Gifford
_PLoS Biol._, 2010 Nov 2;8(11):e1000523


* <a href="http://groups.csail.mit.edu/cgs/pubs/469.pdf">Genotype to Phenotype: A Complex Problem</a>
R. D. Dowell, O. Ryan, A. Jansen, D. Cheung, S. Agarwala, T. Danford, D. A. Bernstein, P. A. Rolfe, L. E. Heisler, B. Chin, C. Nislow, G. Giaever, P. C. Phillips, G. R. Fink, D. K. Gifford, and C. Boone
_Science_ , 23, April, 2010, p. 469

* <a href="http://groups.csail.mit.edu/cgs/pubs/513.full.pdf">Feed-forward Regulation of a Cell Fate Determinant by an RNA-binding Protein Generates Asymmetry in Yeast</a>
J. Wolff, R. D. Dowell, S. Mahony, M. Rabani, D. K. Gifford, and G. R. Fink.
_Genetics_ 2010


### 2009 and Earlier

* <a href="http://groups.csail.mit.edu/cgs/pubs/18321.full.pdf">Toggle involving <em>cis</em>-interfering noncoding RNAs controls variegated gene expression in yeast</a>
S.  L. Bumgarner, R. D. Dowell, P. Grisafi, D. K. Gifford, and G. R. Fink
_PNAS_ 106(43), October, 2009, pp18321-18326

* <a href="http://groups.csail.mit.edu/cgs/pubs/gb-2008-9-8-r126.pdf">Analysis of the mouse embryonic stem cell regulatory networks obtained by ChIP-chip and ChIP-PET</a>
D. Mathur, T. W. Danford, L. A. Boyer, R. A. Young, D. K. Gifford, and R. Jaenisch
_Genome Biol._, 2008;9(8)

* <a href="http://groups.csail.mit.edu/cgs/pubs/divergence-ng-gifford-2007.pdf">Tissue-specific transcriptional regulation has
	        diverged significantly between human and mouse</a>
D. T. Odom, R. D. Dowell, E. S. Jacobsen, W. Gordon,
	        T. W. Danford, K. D. MacIsaac, P. A. Rolfe,
	        C. M. Conboy, D. K. Gifford, and E. Fraenkel
_Nature Genetics_, 39:6, 730-732, June, 2007

* <a href="http://groups.csail.mit.edu/cgs/pubs/plos-comp-bio-2007.pdf">Automated Discovery of Functional Generality of
		   Human Gene Expression Programs</a>
G. K. Gerber, R. D. Dowell, T. S. Jaakkola, and D. K. Gifford
_PLOS Computational Biology_, 3:8, August 2007


* <a href="http://groups.csail.mit.edu/cgs/pubs/e417.pdf">Semi-supervised analysis of gene expression
		   profiles for lineage-specific development in the
		   Caenorhabditis elegans embryo</a>
Y. Qi, P. E. Missiuro, A. Kapoor, C. P. Hunter, T. S. Jaakkola
		   D. K. Gifford,and  H. Ge
_Bioinformatics_, 15;22(14), July 2006, pp. 417-423


* <a href="http://groups.csail.mit.edu/cgs/pubs/cell-2006.pdf">Control of developmental regulators by Polycomb
		  		   in human enbryonic stem cells</a>
T. I. Lee, R. G. Jenner,
		  		   L. A. Boyer, M. G. Guenther,
		  		   S. S. Levine, R. M Kumar,
		  		   B. Chevalier, S. E. Johnstone,
		  		   M. F. Cole, K. Isono, H. Koseki,
		  		   T. Fuchikami, K. Abe, H. L. Murray,
		  		   J. P. Zucker, B. Yuan, G. W. Bell,
		  		   E. Herbolsheimer, N. M. Hannett,
		  		   K. Sun, D. T. Odom, A. P. Otte,
		  		   T. L. Volkert, D. P. Bartel,
		  		   D. A. Melton, D. K. Gifford,
		  		   R. Jaenisch, and R. A. Young
_Cell_,
		  		   125(2), April, 2006, pp 301-313.


* <a href="http://groups.csail.mit.edu/cgs/pubs/1471-2105-7-113.pdf">An improved map of conserved regulatory sties for Saccharomyces cerevisiae</a>
K. D. MacIsaac, T. Wang, D. B. Gordon, D. K. Gifford, G. D. Stormo, and E. Fraenkel
_BMC Bioinformatics_,  March, 2006


* <a href="http://groups.csail.mit.edu/cgs/pubs/423.pdf">A hypothesis-based approach for identifying the
		  binding specificity of regulatory proteins from chromatin
		  immunoprecipitation data</a>
K. D. MacIsaac,
		  D. B. Gordon, L. Nekludova, D. T. Odom,
		  J. Schreiber, D. K. Gifford, R. A. Young, and
		  E. Fraenkel
_Bioinformatics_, Feb., 2006.


* <a href="http://groups.csail.mit.edu/cgs/pubs/Boyer_Nature2006.pdf">Polycomb complexes repress developmental
                           regulators in murine embryonic stem
                           cells</a>
L. A. Boyer, K. Plath,
                           J. Zeitlinger, T. Brambrink,
                           L. A. Medeiros, T. I Lee., S. S. Levine,
                           M. Wernig, A. Tajonar, M. K. Ray,
                           G. W. Bell, A. P. Otte, M. Vidal,
                           D. K. Gifford, R. A. Young, and
                           R. Jaenisch.
_Nature_, 441:349-353, May 2006

* <a href="http://groups.csail.mit.edu/cgs/pubs/schreiber_pnas06.pdf">Coordinated binding of NF-kB family members in the
		    response of human cells to lipopolysaccharide</A>
J. Schreiber,
		    R. G. Jenner, H. L. Murray, G. K. Gerber, D. K. Gifford and
		    R. A. Young
_Proceedings of the National Academy of Sciences (PNAS)_,
		    103(10):5899-5904, 2006


* <a href="http://groups.csail.mit.edu/cgs/pubs/binding-model-paper.pdf">High-resolution computational models of
	        genome binding events</a>
A. Qi, P.A. Rolfe,
	        K. MacIsaac, G.K. Gerber, D. Pokholok, J. Zeitlinger,
	        T. Danford, R.D. Dowell, E. Fraenkel, T.S. Jaakkola, R.A. Young,
	        and D.K. Gifford
_Nature Biotechnology_, 24, 963-960 (2006)
[[Supplemental material]](pubs/binding-model-paper-supp.pdf) [[software]](http://groups.csail.mit.edu/cgs/jbd)


* <a href="http://groups.csail.mit.edu/cgs/pubs/msb410 0059.pdf">Core Transcriptional Regulatory Circuitry in
                 Human Hepatocytes.</a>
D.T. Odom, R.D. Dowell, E.S. Jacobsen,
                 L. Nekludova, P.A. Rolfe, T.W. Danford, D.K. Gifford,
                 E. Fraenkel, G.I. Bell, and R.A. Young.
_Nature/EMBO Molecular Systems Biology_, msb4100059, 2 May 2006.


* <a href="http://groups.csail.mit.edu/cgs/pubs/genome-wide.pdf">Genome-wide map of nucleosome acetylation and
		 methylation in yeast</a>
D. K. Pokholok,
		 C. T. Harbison, S. Levine, M. Cole, N. M. Hannett,
		 T. I. Lee, G. W. Bell, K. Walker, P. A. Rolfe,
		 E. Herbolsheimer, J. Zeitlinger, F. Lewitter,
		 D. K. Gifford, and R. A. Young
_Cell_, 122(4), August, 2005. pp. 517-527.


* <a href="http://groups.csail.mit.edu/cgs/pubs/es-cell-2005.pdf">Core Transcriptional Regulatory
                 Circuitry in Human Embryonic Stem Cells</a>
L. A. Boyer, T. I. Lee, M. F. Cole, S. E. Johnstone,
                 S. S. Levine, J. P. Zucker, M. G. Guenther,
                 R. M. Kuman, H. L. Murray, R. G. Jenner,
                 D. K. Gifford, D. A. Melton , R. Jaenisch, and
                 R. A. Young
_Cell_, Vol. 122, 1-20, September, 2005

* <a href="http://groups.csail.mit.edu/cgs/pubs/sdarticle.pdf">Global postition and recruitment of HATS and
		 HDACS in the yeast genome</a>
F. Robert,
		 D.K. Pokholok, N. M Hannett, N. J. Rinaldi,
		 M. Chandy, A. Rolfe, J. L. Workman, D. K. Gifford,
		 and R. A. Young
_Mol. Cell_, 16(2), October, 2004, pp. 199-209


* <a href="http://groups.csail.mit.edu/cgs/pubs/ziv-ismb2004.pdf">Deconvolving cell cyle expression data
                with complementary information</a>
Z. Bar-Joseph,
                S. Farkash, D. K. Gifford, I. Simon, R. Rosenfeld
_Bioinformatics_,  Vol. 20 Suppl. 1, 2004. pp i23-i30

* <a href="http://groups.csail.mit.edu/cgs/pubs/nature-2004.pdf">Transcriptional
                regulatory code of a eukaryotic genome</a>
C. Harbison,
                D. B. Gordon, T. I Lee, N. J. Rinaldi, K. D. MacIsaac, T. W. Danford,
                N. M. Hannett, J.B. Tagne, D. B. Reynolds, J. Yoo, E. G. Jennings,
                J. Zeitlinger, D. K. Pokholok, M. Kellis, P. A. Rolfe, K. T. Takusagawa,
                E. S. Lander, D. K. Gifford, E. Fraenkel, and R. A. Young
                _Nature_,
                431:99-104, September, 2004


* <a href="http://groups.csail.mit.edu/cgs/pubs/science-1-04.pdf">Control
                of Pancreas and Liver Gene Expression by HNF Transcription Factors.</a>
                Odom, D. T., Zizlsperger, N., Gordon, D. B., Bell, G. W., Rinaldi,
                N. J., Murray, H. L., Volkert, T. L., Schreiber, J., Rolfe, P.
                A., Gifford, D. K., Fraenkel, E., Bell, G. I., Young, R. A.
_Science_,
                303:1378-1381, February, 2004

* <a href="http://groups.csail.mit.edu/cgs/pubs/barjoseph_pnas03.pdf">Comparing the Continuous Representation
		of Time Series Gene Expression Profiles to Identify
		Differentially Expressed Genes</a>  Z. Bar-Joseph,
		G.K. Gerber, I. Simon, D.K. Gifford, and
		T.S. Jaakkola
_Proceedings of the National Academy of
		Sciences_, 2003 Sept. 2; 100(18):10146-10151


* <a href="http://groups.csail.mit.edu/cgs/pubs/takusagawa-psb.pdf">Negative Information for Motif
		Discovery</a>
Takusagawa, K. T., Gifford, D. K.
_Pacific Symposium on Biocomputing_, 9:360-371, 2004


* <a href="http://groups.csail.mit.edu/cgs/pubs/nature-biotech-11-03.pdf">Computational discovery of gene modules
                and regulatory networks</a>
Bar-Joseph, Z., Gerber,
                G. K., Lee, T. I., Rinaldi, N. J., Yoo, J. Y., Robert,
                F., Gordon, D. B., Fraenkel, E., Jaakkola, T. S.,
                Young, R. A., Gfford D. K.
_Nature Biotechnology_, 21,
                pp. 1337-1342 November, 2003

* <a href="http://groups.csail.mit.edu/cgs/pubs/10665270360688057.pdf">Continuous Representations of Time
                Series Gene Expression Data</a>
Z. Bar-Joseph, Gerber, D. Gifford, T Jaakkola and I. Simon
                G. Gerber, D. Gifford, T. Jaakkola and I. Simon.
_J Comput Biol._, 2003;10(3-4):341-56


* <a href="http://groups.csail.mit.edu/cgs/pubs/k-aryBio.pdf">K-ary Clustering
                with Optimal Leaf Ordering for Gene Expression
                Data</a>
Ziv Bar-Joseph, Erik D. Demaine,
                David K. Gifford, Angèle M. Hamel, Tommy S. Jaakkola
                and Nathan Srebro
_Bioinformatics_, Vol. 19, No. 9,
                2003


* <a href="http://groups.csail.mit.edu/cgs/pubs/science-2002.pdf">Transcriptional Regulatory Networks In
                Saccharomyces cerevisiae</a>
T.I.  Lee,
                N. J. Rinaldi, F. Robert, D. T. Odom, Z. Bar-Joseph,
                G. K.  Gerber, D. K Gifford and
                R. A. Young
_Science_, 298:799-804
                (2002)

* <a href="http://groups.csail.mit.edu/cgs/pubs/k-aryWABI.pdf">K-ary Clustering with Optimal Leaf
                Ordering for Gene Expression Data</a>
Ziv Bar-Joseph, Erik D. Demaine, David
                K. Gifford, Angèle M. Hamel, Tommi S. Jaakkola and
                Nathan Srebro
_Proceedings of the 2nd
                Workshop on Algorithms in Bioinformatics (WABI 2002)_,
                Rome, Italy, September 17-11

* <a href="http://groups.csail.mit.edu/cgs/pubs/hartemink.final.pdf">Combining Location and Expression Data
                for Principled Discovery of Genetic Regulatory Network
                Models.</a>
Alexander J. Hartemink, David K. Gifford,
                Tommi S. Jaakkola, and Richard A. Young
_Pacific
                Symposium on Biocomputing_, 2002, Kauai, January
                2002

* <a href="http://groups.csail.mit.edu/cgs/pubs/ieeepaper.pdf">Bayesian Methods for Elucidating Genetic
                Regulatory Networks</a>
Hartemink, A. J., Gifford,
                D. K., Jaakkola, T. S., Young, R. A.
_IEEE
                Intelligent Systems in Biology_, Vol. 17, No. 2, March, 2002,
                pp. 37-43

* <a href="http://groups.csail.mit.edu/cgs/pubs/CELL.106_6_697.530.pdf">Serial Regulation of Transcriptional
                Regulators in the Yeast Cell Cycle</a>
Simon, I.,
                Barnett, J., Hannett, N., Harbison, C. T., Rinaldi,
                N. J., Volkert, T. L. Wyrick, J. J., Zeitlinger, J.,
                Gifford., D. K., Jaakkola, T. S., Young, R. A.
_Cell_, 106, Sept., 2001, p. 667-708

* <a href="http://groups.csail.mit.edu/cgs/pubs/BarGerGifJaa-recomb02.pdf">A new approach to analyzing gene expression time series
                data.</a>
Z. Bar-Joseph, G. Gerber, D. Gifford,
                T. Jaakkola and I. Simon
_Proceedings of The
                Sixth Annual International Conference on Research in
                Computational Molecular Biology (RECOMB)_, 2002, pp
                39-48

* <a href="http://groups.csail.mit.edu/cgs/pubs/science9-01.pdf">Blazing pathways through genetic
                mountains</a>
Gifford, D. K.
_Science_,  2001 Sep 14;293(5537):2049-51

* <a href="http://groups.csail.mit.edu/cgs/pubs/BarGifJaa-ismb01.pdf">Fast
                optimal leaf ordering for hierarchical
                clustering.</a>
Z. Bar-Joseph, D. Gifford, and
                T. Jaakkola
_Bioinformatics (Proceedings
                of ISMB 2001)_, 17(S1), 2001, pp 22-19

* <a href="http://groups.csail.mit.edu/cgs/pubs/psbcamera.pdf">Using
                Graphical Models and Genomic Expression Data to Statistically
                Validate Models of Genetic Regulatory Networks</a>
Alexander
                J. Hartemink, David K. Gifford, Tommi S. Jaakkola, and Richard
                A. Young
_Pacific Symposium on Biocomputing_, 2001, Hawaii, January
                2001


* <a href="http://groups.csail.mit.edu/cgs/pubs/spie.pdf">Maximum
                Likelihood Estimation of Optimal Scaling Factors for Expression
                Array Normalization</a>
Alexander J. Hartemink, David K. Gifford,
                Tommi S. Jaakkola, and Richard A. Young
_SPIE BiOS 2001_, San Jose,
                California, January 2001

* <a href="http://groups.csail.mit.edu/cgs/pubs/ngc20-3.pdf">Experimental Efficiency
                of Programmed Mutagenesis</a>
Julia Khodor and David K. Gifford
_New Generation Computing_ 20:3, pp 307-315, 2002

* <a href="http://groups.csail.mit.edu/cgs/pubs/prog-muta-universal.pdf">Programmed Mutagenesis is Universal</a>
Julia Khodor, and David K. Gifford
_Theory of Computing Systems_, 255, pp 483-499, 2002.


* <a href="http://groups.csail.mit.edu/cgs/pubs/biosim.pdf">Simulating
                Biological Reactions: A Modular Approach</a>
Alexander
                J. Hartemink, Tarjei S. Mikkelsen, and David K. Gifford
5th Annual
                _DIMACS Workshop on DNA-Based Computers_, Boston, Massachusetts,
                June 1999


* <a href="http://groups.csail.mit.edu/cgs/pubs/scan.pdf">Automated
                Constraint-Based Nucleotide Sequence Selection for DNA Computation</a>
Alexander J. Hartemink, David K. Gifford, and Julia Khodor
 _4th Annual DIMACS Workshop on DNA-Based Computers_, Philadelphia, Pennsylvania,
                June 1998


* <a href="http://groups.csail.mit.edu/cgs/pubs/paper">Design
                &amp; Implementation of Computational Systems Based on Programmed
                Mutagenesis</a>
Khodor, J. and Gifford, D. K.
_DIMACS Workshop
                on Nucleic Acid Selection and Computing_, Princeton University,
                March, 1998


* <a href="http://groups.csail.mit.edu/cgs/pubs/bind.pdf">Thermodynamic
		  Simulation of Deoxyoligonucleotide Hybridization for DNA Computation</a>
Alexander J. Hartemink and David K. Gifford
_3rd Annual DIMACS
                Workshop on DNA-Based Computers_, Philadelphia, Pennsylvania, June
                1997


* <a href="http://groups.csail.mit.edu/cgs/pubs/sep-3.pdf">The Efficiency
                of Sequence-Specific Separation of DNA Mixtures for Biological
                Computing</a>
Julia Khodor and David K. Gifford
_3rd Annual DIMACS
                Workshop on DNA-Based Computers_, Philadelphia, Pennsylvania, June
                1997
