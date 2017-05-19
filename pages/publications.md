---
layout: page-fullwidth
title: "Publications"
header:
     image_fullwidth: "dna.jpg"
permalink: "/publications/"
---
<!--more-->


<div class="row t60">
<img src="{{ site.url }}/images/hiring_postdocs.png" style="width:200px;height:126px;">
</div>


<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="http://onlinelibrary.wiley.com/doi/10.1002/humu.23198/epdf">Accurate eQTL prioritization with an ensemble-based framework </a></b></p>
        <p><font size="2">We present a novel ensemble-based computational framework, EnsembleExpr, that achieved the best performance in the Fourth Critical Assessment of Genome Interpretation expression quantitative trait locus "(eQTL)-causal SNPs" challenge for identifying eQTLs and prioritizing their gene expression effects. eQTLs are genome sequence variants that result in gene expression changes and are thus prime suspects in the search for contributions to the causality of complex traits. When EnsembleExpr is trained on data from massively parallel reporter assays, it accurately predicts reporter expression levels from unseen regulatory sequences and identifies sequence variants that exhibit significant changes in reporter expression. Compared with other state-of-the-art methods, EnsembleExpr achieved competitive performance when applied on eQTL datasets determined by other protocols. We envision EnsembleExpr to be a resource to help interpret noncoding regulatory variants and prioritize disease-associated mutations for downstream validation.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/Zeng-2017-Accurate-eQTL.png" alt="">
        <p> <font size="2">Zeng H, Edwards MD, Guo Y, Gifford DK.
        <br> <i>Hum Mutat. 2017 Feb 21</i>, doi:
10.1002/humu.23198. </font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/scm.pdf ">Modular combinatorial binding among human trans-acting factors reveals direct and indirect factor binding.</a></b></p>
        <p><font size="2">BACKGROUND:

The combinatorial binding of trans-acting factors (TFs) to the DNA is critical to the spatial and temporal specificity of gene regulation. For certain regulatory regions, more than one regulatory module (set of TFs that bind together) are combined to achieve context-specific gene regulation. However, previous approaches are limited to either pairwise TF co-association analysis or assuming that only one module is used in each regulatory region.
RESULTS:

We present a new computational approach that models the modular organization of TF combinatorial binding. Our method learns compact and coherent regulatory modules from in vivo binding data using a topic model. We found that the binding of 115 TFs in K562 cells can be organized into 49 interpretable modules. Furthermore, we found that tens of thousands of regulatory regions use multiple modules, a structure that cannot be observed with previous hard clustering based methods. The modules discovered recapitulate many published protein-protein physical interactions, have consistent functional annotations of chromatin states, and uncover context specific co-binding such as gene proximal binding of NFY + FOS + SP and distal binding of NFY + FOS + USF. For certain TFs, the co-binding partners of direct binding (motif present) differs from those of indirect binding (motif absent); the distinct set of co-binding partners can predict whether the TF binds directly or indirectly with up to 95% accuracy. Joint analysis across two cell types reveals both cell-type-specific and shared regulatory modules.
CONCLUSIONS:

Our results provide comprehensive cell-type-specific combinatorial binding maps and suggest a modular organization of combinatorial binding..</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/Guo-2016-Modular-combinatorial.jpg" alt="">
        <p> <font size="2">Kreimer A, Zeng H, Edwards MD, Guo Y, Tian K, Shin S, Welch R, Wainberg M, Mohan R, Sinnott-Armstrong NA, Li Y, Eraslan G, Amin TB, Goke J, Mueller NS, Kellis M, Kundaje A, Beer MA, Keles S, Gifford DK, Yosef N.  
        <br> <i>HBMC Genomics. 2017 Jan 6;18(1):45.</i>, doi:
10.1186/s12864-016-3434-3.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/scm.pdf ">Expression of Terminal Effector Genes in Mammalian Neurons Is Maintained by a Dynamic Relay of Transient Enhancers. </a></b></p>
        <p><font size="2">Generic spinal motor neuron identity is established by cooperative binding of programming transcription factors (TFs), Isl1 and Lhx3, to motor-neuron-specific enhancers. How expression of effector genes is maintained following downregulation of programming TFs in maturing neurons remains unknown. High-resolution exonuclease (ChIP-exo) mapping revealed that the majority of enhancers established by programming TFs are rapidly deactivated following Lhx3 downregulation in stem-cell-derived hypaxial motor neurons. Isl1 is released from nascent motor neuron enhancers and recruited to new enhancers bound by clusters of Onecut1 in maturing neurons. Synthetic enhancer reporter assays revealed that Isl1 operates as an integrator factor, translating the density of Lhx3 or Onecut1 binding sites into transient enhancer activity. Importantly, independent Isl1/Lhx3- and Isl1/Onecut1-bound enhancers contribute to sustained expression of motor neuron effector genes, demonstrating that outwardly stable expression of terminal effector genes in postmitotic neurons is controlled by a dynamic relay of stage-specific enhancers.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/Expression-of-Terminal-Effector.jpg" alt="">
        <p> <font size="2">.Rhee HS, Closser M, Guo Y, Bashkirova EV, Tan CG, Gifford DK, Wichterle H.  
        <br> <i>Neuron. 2016 Dec 21;92(6):1252-1265.</i>, doi:
10.1016/j.neuron.2016.11.037.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->





<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/scm.pdf ">Predicting gene expression in massively parallel reporter assays: A comparative study. </a></b></p>
        <p><font size="2">In many human diseases, associated genetic changes tend to occur within noncoding regions, whose effect might be related to transcriptional control. A central goal in human genetics is to understand the function of such noncoding regions: given a region that is statistically associated with changes in gene expression (expression quantitative trait locus [eQTL]), does it in fact play a regulatory role? And if so, how is this role “coded” in its sequence? These questions were the subject of the Critical Assessment of Genome Interpretation eQTL challenge. Participants were given a set of sequences that flank eQTLs in humans and were asked to predict whether these are capable of regulating transcription (as evaluated by massively parallel reporter assays), and whether this capability changes between alternative alleles. Here, we report lessons learned from this community effort. By inspecting predictive properties in isolation, and conducting meta-analysis over the competing methods, we find that using chromatin accessibility and transcription factor binding as features in an ensemble of classifiers or regression models leads to the most accurate results. We then characterize the loci that are harder to predict, putting the spotlight on areas of weakness, which we expect to be the subject of future studies.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/Predicting-gene-express-Kreimer.png" alt="">
        <p> <font size="2">Kreimer A, Zeng H, Edwards MD, Guo Y, Tian K, Shin S, Welch R, Wainberg M, Mohan R, Sinnott-Armstrong NA, Li Y, Eraslan G, Amin TB, Goke J, Mueller NS, Kellis M, Kundaje A, Beer MA, Keles S, Gifford DK, Yosef N.  
        <br> <i>Hum Mutat. 2017 Feb 21.</i>, doi:
10.1002/humu.23197.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/scm.pdf ">Identification of new branch points and unconventional introns in Saccharomyces cerevisiae.</a></b></p>
        <p><font size="2">Spliced messages constitute one-fourth of expressed mRNAs in the yeast Saccharomyces cerevisiae, and most mRNAs in metazoans. Splicing requires 5′ splice site (5′SS), branch point (BP), and 3′ splice site (3′SS) elements, but the role of the BP in splicing control is poorly understood because BP identification remains difficult. We developed a high-throughput method, Branch-seq, to map BPs and 5′SSs of isolated RNA lariats. Applied to S. cerevisiae, Branch-seq detected 76% of expressed, annotated BPs and identified a comparable number of novel BPs. We performed RNA-seq to confirm associated 3′SS locations, identifying some 200 novel splice junctions, including an AT-AC intron. We show that several yeast introns use two or even three different BPs, with effects on 3′SS choice, protein coding potential, or RNA stability, and identify novel introns whose splicing changes during meiosis or in response to stress. Together, these findings show unanticipated complexity of splicing in yeast.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/Gould-Oct-2016-Identification of new branch.jpg" alt="">
        <p> <font size="2">Gould GM, Paggi JM, Guo Y, Phizicky DV, Zinshteyn B, Wang ET, Gilbert WV, Gifford DK, Burge CB.  
        <br> <i>RNA. 2016 Oct;22(10):1522-34.</i>, doi:
10.1261/ma.057216.116.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->





<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/scm.pdf ">A Synergistic DNA Logic Predicts Genome-wide Chromatin Accessibility </a></b></p>
        <p><font size="2">Enhancers and promoters commonly occur in accessible chromatin characterized by depleted nucleosome contact; however, it is unclear how chromatin accessibility is governed. We show that log-additive cis-acting DNA sequence features can predict chromatin accessibility at high spatial resolution. We develop a new type of high-dimensional machine learning model, the Synergistic Chromatin Model (SCM), which when trained with DNase-seq data for a cell type is capable of predicting expected read counts of a genome-wide chromatin accessibility at every base from DNA
sequence alone, with the highest accuracy at hypersensitive sites shared across cell types. We confirm that a SCM accurately predicts chromatin accessibility for thousands of synthetic DNA sequences using a novel CRISPR-based method of highly efficient site-specific DNA library integration. SCMs are directly interpretable and reveal that a logic based on local, non-specific synergistic effects, largely among pioneer TFs, is sufficient to predict a large fraction of cellular chromatin accessibility in a wide
variety of cell types. </font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/scm.png" alt="">
        <p> <font size="2">Hashimoto TB, Sherwood RI, Kang DD, Barkal AA, Zeng H, Emons BJM, Srinivasan S, Rajagopal N, Jaakkola T, and Gifford DK.
        <br> <i>Genome Research</i>, doi:
10.1101/gr.199778.115</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/hashimoto16.pdf ">Learning Population-Level Diffusions with Generative Recurrent Networks</a></b></p>
        <p><font size="2">We estimate stochastic processes that govern thedynamics of evolving populations such as celldifferentiation. The problem is challenging sincelongitudinal trajectory measurements of individualsin a population are rarely available due toexperimental cost and/or privacy. We show thatcross-sectional samples from an evolving populationsuffice for recovery within a class of processeseven if samples are available only at afew distinct time points. We provide a stratifiedanalysis of recoverability conditions, and establishthat reversibility is sufficient for recoverability.For estimation, we derive a natural loss andregularization, and parameterize the processes asdiffusive recurrent neural networks. We demonstratethe approach in the context of uncoveringcomplex cellular dynamics known as the ‘epigeneticlandscape’ from existing biological assays.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/hashimoto16.png" alt="">
        <p> <font size="2">Hashimoto TB, Gifford DK, Jaakkola TS.
        <br> <i>Proceedings of the 33 rd International Conference on MachineLearning (ICML)</i></font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">    
    <div class="medium-8 columns b30">
        <p><b><a href="http://bioinformatics.oxfordjournals.org/content/32/12/i121.long">Convolutional neural network architectures for predicting DNA-protein binding.</a></b></p>
        <p><font size="2">We present a systematic exploration of CNN architectures for predicting DNA sequence binding using a large compendium of transcription factor datasets. We identify the best-performing architectures by varying CNN width, depth and pooling designs. We find that adding convolutional kernels to a network is important for motif-based tasks. We show the benefits of CNNs in learning rich higher-order sequence features, such as secondary motifs and local sequence context, by comparing network performance on multiple modeling tasks ranging in difficulty. We also demonstrate how careful construction of sequence benchmark datasets, using approaches that control potentially confounding effects like positional or motif strength bias, is critical in making fair comparisons between competing methods. We explore how to establish the sufficiency of training data for these learning tasks, and we have created a flexible cloud-based framework that permits the rapid exploration of alternative neural network architectures for problems in computational biology.</font></p>
    </div><!-- /.medium-6.columns -->
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/cnn_structure.png" alt="">
        <p> <font size="2">Zeng H, Edwards MD, Liu G, Gifford DK.
        <br> <i>Bioinformatics</i>. 2016 Jun 15;32(12):i121-i127. doi: 10.1093/bioinformatics/btw255.</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

<div class="row t60">
    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/PNAS-2016-Ferreira-5364-9.pdf">A distant trophoblast-specific enhancer controls HLA-G expression at the maternal-fetal interface.</a></b></p>
        <p><font size="2">HLA-G, a nonclassical HLA molecule uniquely expressed in the placenta, is a central component of fetus-induced immune tolerance during pregnancy. The tissue-specific expression of HLA-G, however, remains poorly understood. Here, systematic interrogation of the HLA-G locus using massively parallel reporter assay (MPRA) uncovered a previously unidentified cis-regulatory element 12 kb upstream of HLA-G with enhancer activity, Enhancer L Strikingly, clustered regularly-interspaced short palindromic repeats (CRISPR)/Cas9-mediated deletion of this enhancer resulted in ablation of HLA-G expression in JEG3 cells and in primary human trophoblasts isolated from placenta. RNA-seq analysis demonstrated that Enhancer L specifically controls HLA-G expression. Moreover, DNase-seq and chromatin conformation capture (3C) defined Enhancer L as a cell type-specific enhancer that loops into the HLA-G promoter. Interestingly, MPRA-based saturation mutagenesis of Enhancer L identified motifs for transcription factors of the CEBP and GATA families essential for placentation. These factors associate with Enhancer L and regulate HLA-G expression. Our findings identify long-range chromatin looping mediated by core trophoblast transcription factors as the mechanism controlling tissue-specific HLA-G expression at the maternal-fetal interface. More broadly, these results establish the combination of MPRA and CRISPR/Cas9 deletion as a powerful strategy to investigate human immune gene regulation.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/HLA-G.png" alt="">
        <p> <font size="2">Ferreira LM, Meissner TB, Mikkelsen TS, Mallard W, O'Donnell CW, Tilburgs T, Gomes HA, Camahort R, Sherwood RI, Gifford DK, Rinn JL, Cowan CA, Strominger JL.
        <br> <i>Proc Natl Acad Sci U.S.A </i>. 2016 May 10;113(19):5364-9. doi: 10.1073/pnas.1602886113. </font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">
    
    <div class="medium-8 columns b30">
        <p><b><a href="http://journals.plos.org/plosone/article/asset?id=10.1371%2Fjournal.pone.0152683.PDF">Cas9 Functionally Opens Chromatin</a></b></p>
        <p><font size="2">Using a nuclease-dead Cas9 mutant, we show that Cas9 reproducibly induces chromatin accessibility at previously inaccessible genomic loci. Cas9 chromatin opening is sufficient to enable adjacent binding and transcriptional activation by the settler transcription factor retinoic acid receptor at previously unbound motifs. Thus, we demonstrate a new use for Cas9 in increasing surrounding chromatin accessibility to alter local transcription factor binding.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/journal.pone.0152683.g001.PNG" alt="">
        <p> <font size="2">Barkal AA Srinivasan S, Hashimoto T, Gifford DK, Sherwood RI.
        <br> <i>PLoS One</i>. 2016 Mar 31;11(3):e0152683.  </font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">
    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/nbt.3468.pdf">High-throughput mapping of regulatory DNA</a></b></p>
        <p><font size="2">Quantifying the effects of cis-regulatory DNA on gene expression is a major challenge. Here, we present the multiplexed editing regulatory assay (MERA), a high-throughput CRISPR-Cas9–based approach that analyzes the functional impact of the regulatory genome in its native context. MERA tiles thousands of mutations across ~40 kb of cis-regulatory genomic space and uses knock-in green fluorescent protein (GFP) reporters to read out gene activity. Using this approach, we obtain quantitative information on the contribution of cis-regulatory regions to gene expression. We identify proximal and distal regulatory elements necessary for expression of four embryonic stem cell–specific genes. We show a consistent contribution of neighboring gene promoters to gene expression and identify unmarked regulatory elements (UREs) that control gene expression but do not have typical enhancer epigenetic or chromatin features. We compare thousands of functional and nonfunctional genotypes at a genomic location and identify the base pair–resolution functional motifs of regulatory elements.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/nbt.3468-F1.png" alt="">
        <p> <font size="2">Rajagopal, Nisha, Sharanya Srinivasan, Kameron Kooshesh, Yuchun Guo, Matthew D. Edwards, Budhaditya Banerjee, Tahin Syed, Bart JM Emons, David K. Gifford, and Richard I. Sherwood. 
        <br> <i>Nature Biotechnology</i> 34, 167–174 (2016) </font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->




<div class="row t60">
    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/Bioinformatics-2015-Zeng-bioinformatics_btv565.pdf">GERV: a statistical method for generative evaluation of regulatory variants for transcription factor binding</a></b></p>
        <p><font size="2">The majority of disease-associated variants identified in genome-wide association studies reside in noncoding regions of the genome with regulatory roles. Thus being able to interpret the functional consequence of a variant is essential for identifying causal variants in the analysis of genome-wide association studies. We present GERV (generative evaluation of regulatory variants), a novel computational method for predicting regulatory variants that affect transcription factor binding. GERV learns a k-mer-based generative model of transcription factor binding from ChIP-seq and DNase-seq data, and scores variants by computing the change of predicted ChIP-seq reads between the reference and alternate allele. The k-mers learned by GERV capture more sequence determinants of transcription factor binding than a motif-based approach alone, including both a transcription factor's canonical motif and associated co-factor motifs. We show that GERV outperforms existing methods in predicting single-nucleotide polymorphisms associated with allele-specific binding. GERV correctly predicts a validated causal variant among linked single-nucleotide polymorphisms and prioritizes the variants previously reported to modulate the binding of FOXA1 in breast cancer cell lines. Thus, GERV provides a powerful approach for functionally annotating and prioritizing causal variants for experimental follow-up analysis.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/gerv-img.jpg" alt="">
        <p> <font size="2">H. Zeng, T. Hashimoto, D.D. Kang, D.K. Gifford.
        <br> <i>Bioinformatics</i>  32 (4): 490-496 (2016)</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->


<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/pone.0122420.pdf">High resolution mapping of enhancer-promoter interactions</a></b></p>
        <p><font size="2">RNA Polymerase II ChIA-PET data has revealed enhancers that are active in a profiled cell type and the genes that the enhancers regulate through chromatin interactions. The most commonly used computational method for analyzing ChIA-PET data, the ChIA-PET Tool,discovers interaction anchors at a spatial resolution that is insufficient to accurately identify individual enhancers. We introduce Germ, a computational method that estimates the likelihood that any two narrowly defined genomic locations are jointly occupied by RNA Polymerase II. Germ takes a blind deconvolution approach to simultaneously estimate the likelihood of RNA Polymerase II occupation as well as a model of the arrangement of read alignments relative to locations occupied by RNA Polymerase II. Both types of information are utilized to estimate the likelihood that RNA Polymerase II jointly occupies any two genomic locations. We apply Germ to RNA Polymerase II ChIA-PET data from embryonic stem cells to identify the genomic locations that are jointly occupied along with transcription start sites. We show that these genomic locations align more closely with features of active enhancers measured by ChIP-Seq than the locations identified using the ChIA-PET Tool. We also apply Germ to RNA Polymerase II ChIA-PET data from motor neuron progenitors. Based on the Germ results, we observe that a combination of cell type specific and cell type independent regulatory interactions are utilized by cells to regulate gene expression.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/germ-germ.png" alt="">
        <p> <font size="2">Christopher Reeder, Michael Closser, Huay Mei Poh, Kuljeet Sandhu,Hynek Wichterle, David Gifford. 
        <br><i>PLOS ONE</i>. doi:10.1371/journal.pone.0122420 May 13, 2015</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/nbt.3082.pdf">Long-term persistence and development of induced pancreatic beta cells generated by lineage conversion of acinar cells</a></b></p>
        <p><font size="2">Direct lineage conversion is a promising approach to generate therapeutically important cell types for disease modeling and tissue repair. However, the survival and function of lineage-reprogrammed cells in vivo over the long term has not been examined. Here, using an improved method for in vivo conversion of adult mouse pancreatic acinar cells toward beta cells, we show that induced beta cells persist for up to 13 months (the length of the experiment), form pancreatic isletlike structures and support normoglycemia in diabetic mice. Detailed molecular analyses of induced beta cells over 7 months reveal that global DNA methylation changes occur within 10 d, whereas the transcriptional network evolves over 2 months to resemble that of endogenous beta cells and remains stable thereafter. Progressive gain of beta-cell function occurs over 7 months, as measured by glucose-regulated insulin release and suppression of hyperglycemia. These studies demonstrate that lineage-reprogrammed cells persist for >1 year and undergo epigenetic, transcriptional, anatomical and functional development toward a beta-cell phenotype.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/nbt.png" alt="">
        <p> <font size="2">Weida Li, Claudia Cavelti-Weder, Yinying Zhang, Kendell Clement, Scott Donovan, Gabriel Gonzalez, Jiang Zhu, Marianne Stemann, Ke Xu, Tatsu Hashimoto, Takatsugu Yamada, Mio Nakanishi, Yuemei Zhang, Samuel Zeng, David Gifford, Alexander Meissner, Gordon Weir, and Qiao Zhou.
        <br> <i> Nat Biotechnol </i>. 2014 Dec;32(12):1223-30. doi: 10.1038/nbt.3082. Epub 2014 Nov 17</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/nihms618131.pdf">Gene co-regulation by Fezf2 selects neurotransmitter identity and connectivity of corticospinal neurons</a></b></p>
        <p><font size="2">The neocortex contains an unparalleled diversity of neuronal subtypes, each defined by distinct traits that are developmentally acquired under the control of subtype-specific and pan-neuronal genes. The regulatory logic that orchestrates the expression of these unique combinations of genes is unknown for any class of cortical neuron. Here, we report that Fezf2 is a selector gene able to regulate the expression of gene sets that collectively define mouse corticospinal motor neurons.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/gene-co2.png" alt="">
        <p> <font size="2">S. Lodato, B.J. Molyneaux, E. Zuccaro, L.A. Goff, H.H. Chen, W. Yuan, A. Meleski, E. Takahashi, S. Mahony, J.L. Rinn, D.K., P. Arlotta.
        <br> <i> Nat Neurosci </i>. 2014 Aug;17(8):1046-54. doi: 10.1038/nn.3757. Epub 2014 Jul 6 </font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/PNAS-2014-Edwards-1407126111.pdf">Interactions between chromosomal and nonchromosomal elements reveal missing heritability</a></b></p>
        <p><font size="2">The measurement of any nonchromosomal genetic contribution to the heritability of a trait is often confounded by the inability to control both the chromosomal and nonchromosomal information in a population. We have designed a unique system in yeast where we can control both sources of information so that the phenotype of a single chromosomal polymorphism can be measured in the presence of different cytoplasmic elements. With this system, we have shown that both the source of the mitochondrial genome and the presence or absence of a dsRNA virus influence the phenotype of chromosomal variants that affect the growth of yeast. Moreover, by considering this nonchromosomal information that is passed from parent to offspring and by allowing chromosomal and nonchromosomal information to exhibit non-additive interactions, we are able to account for much of the heritability of growth traits. Taken together, our results highlight the importance of including all sources of heritable information in genetic studies and suggest a possible avenue of attack for finding additional missing heritability.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/PNAS-2014-Edwards.png" alt="">
        <p> <font size="2">Matthew D. Edwards, Anna Symbor-Nagrabska, Lindsey Dollard, David K. Gifford, Gerald R. Fink. 
        <br> <i>Proc. Natl. Acad. Sci U.S.A.</i>, 2014, May 13. pii: 201407126</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/journal.pcbi.1003501.pdf">An integrated model of multiple-condition ChIP-Seq data reveals predeterminants of Cdx2 binding</a></b></p>
        <p><font size="2">Regulatory proteins can bind to different sets of genomic targets in various cell types or conditions. To reliably characterize such condition-specific regulatory binding we introduce MultiGPS, an integrated machine learning approach for the analysis of multiple related ChIP-seq experiments. MultiGPS is based on a generalized Expectation Maximization framework that shares information across multiple experiments for binding event discovery. We demonstrate that our framework enables the simultaneous modeling of sparse condition-specific binding changes, sequence dependence, and replicate-specific noise sources. MultiGPS encourages consistency in reported binding event locations across multiple-condition ChIP-seq datasets and provides accurate estimation of ChIP enrichment levels at each event. MultiGPS’s multi-experiment modeling approach thus provides a reliable platform for detecting differential binding enrichment across experimental conditions. We demonstrate the advantages of MultiGPS with an analysis of Cdx2 binding in three distinct developmental contexts. By accurately characterizing condition-specific Cdx2 binding, MultiGPS enables novel insight into the mechanistic basis of Cdx2 site selectivity. Specifically, the condition-specific Cdx2 sites characterized by MultiGPS are highly associated with pre-existing genomic context, suggesting that such sites are pre-determined by cell-specific regulatory architecture. However, MultiGPS-defined condition-independent sites are not predicted by pre-existing regulator  signals, suggesting that Cdx2 can bind to a subset of locations regardless of genomic environment.  A summary of this paper appears in the proceedings of the RECOMB 2014 conference, April 2.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/journal.pcbi2.jpg" alt="">
        <p> <font size="2">S. Mahony, M. D. Edwards, E. O. Mazzoni, R. I. Sherwood, A. Kakumanu, C. A. Morrison, H. Wichterle, D. K. Gifford . 
        <br><i> PLoS Comput Biol</i>. 2014 Mar 27;10(3):e1003501. doi: 10.1371/journal.pcbi.1003501. eCollection 2014 Mar</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/journal.pcbi.1003494.pdf">Universal count correction for high-throughput sequencing </a></b></p>
        <p><font size="2">We show that existing RNA-seq, DNase-seq, and ChIP-seq data exhibit overdispersed per-base read count distributions that are not matched to existing computational method assumptions. To compensate for this overdispersion we introduce a nonparametric and universal method for processing per-base sequencing read count data called FIXSEQ. We demonstrate that FIXSEQ substantially improves the performance of existing RNA-seq, DNase-seq, and ChIP-seq analysis tools when compared with existing alternatives.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/journal.pcbi.1003494.png" alt="">
        <p> <font size="2">T.B. Hashimoto, M. D. Edwards, D. K. Gifford
        <br> <i>PLoS Comput Biol</i>. 2014 Mar 6;10(3):e1003494. doi: 10.1371/journal.pcbi.1003494. eCollection 2014</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/pone.0089459.pdf">MARIS: method for analyzing RNA following intracellular sorting </a></b></p>
        <p><font size="2">Transcriptional profiling is a key technique in the study of cell biology that is limited by the availability of reagents to uniquely identify specific cell types and isolate high quality RNA from them. We report a Method for Analyzing RNA following Intracellular Sorting (MARIS) that generates high quality RNA for transcriptome profiling following cellular fixation,intracellular immunofluorescent staining and FACS. MARIS can therefore be used to isolate high quality RNA from many otherwise inaccessible cell types simply based on immunofluorescent tagging of unique intracellular proteins. As proof of principle, we isolate RNA from sorted human embryonic stem cell-derived insulin-expressing cells as well as adult human b cells. MARIS is a basic molecular biology technique that could be used across several biological disciplines.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/maris.png" alt="">
        <p> <font size="2">S. Hrvatin, F. Deng, C. W. O'Donnell, D. K. Gifford, D. A. Melton. 
        <br><i>PLoS One</i>. 2014 Mar 3;9(3):e89459. doi: 10.1371/journal.pone.0089459. eCollection 2014</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/PNAS-2014-Hrvatin-3038-43.pdf">Differentiated human stem cells resemble fetal, not adult, ß cells.</a></b></p>
        <p><font size="2">Human pluripotent stem cells (hPSCs) have the potential to generate any human cell type, and one widely recognized goal is to make pancreatic β cells. To this end, comparisons between differentiated cell types produced in vitro and their in vivo counter-parts are essential to validate hPSC-derived cells. Genome-wide transcriptional analysis of sorted insulin-expressing (INS+) cells derived from three independent hPSC lines, human fetal pancreata, and adult human islets points to two major conclusions: (i) Different hPSC lines produce highly similar INS+cells and (ii) hPSC-derived INS+(hPSC-INS+) cells more closely resemble human fetal β cells than adult β cells. This study provides a direct comparison of transcriptional programs between pure hPSC-INS+ cells and true β cells and provides a catalog of genes whose manipulation may convert hPSC-INS+ cells into functional β cells.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/PNAS-2014-Hrvatin.png" alt="">
        <p> <font size="2">S. Hrvatin, C. W. O'Donnell, F. Deng, J. R. Millman, F. W. Pagliuca, P. DiIorio, A. Rezania, D. K. Gifford, D. A. Melton. 
        <br> <i>Proc Natl Acad Sci U.S.A. </i>, 2014 Feb 25;111(8):3038-43. doi: 10.1073/pnas.1400709111. Epub 2014 Feb 10</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">

    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/nbt.2798.pdf">Discovery of directional and nondirectional pioneer transcription factors by modeling DNase profile magnitude and shape </a></b></p>
        <p><font size="2">We describe protein interaction quantitation (PIQ), a computational method for modeling the magnitude and shape of genome-wide DNase I hypersensitivity profiles to identify transcription factor (TF) binding sites. Through the use of machine-learning techniques, PIQ identified binding sites for >700 TFs from one DNase I hypersensitivity analysis followed by sequencing (DNase-seq) experiment with accuracy comparable to that of chromatin immunoprecipitation followed by sequencing (ChIP-seq). We applied PIQ to analyze DNase-seq data from mouse embryonic stem cells differentiating into prepancreatic and intestinal endoderm. We identified 120 and experimentally validated eight ‘pioneer’ TF families that dynamically open chromatin. Four pioneerTF families only opened chromatin in one direction from their motifs. Furthermore, we identified ‘settler’ TFs whose genomic binding is principally governed by proximity to open chromatin. Our results support a model of hierarchical TF binding in which directional and nondirectional pioneer activity shapes the chromatin landscape for population by settler TFs.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/nbt-2.png" alt="">
        <p> <font size="2">R. I. Sherwood, T. Hashimoto, C. W. O'Donnell, D. Lewis, A. A. Barkal, J. P. van Hoff, V. Karun, T. Jaakkola, D. K. Gifford. 
        <br> <i>Nat Biotechnol</i>. 2014 Feb;32(2):171-8. doi: 10.1038/nbt.2798. Epub 2014 Jan 19</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->



<div class="row t60">
    
    <div class="medium-8 columns b30">
        <p><b><a href="http://groups.csail.mit.edu/cgs/pubs/mahony-stem-cell-reports.pdf">A Cdx4-Sall4 Regulatory Module Controls the Transition from Mesoderm Formation to Embryonic Hematopoiesis</a></b></p>
        <p><font size="2">Deletion of caudal / cdx genes alters hox gene expression and causes defects in posterior tissues and hematopoiesis. Yet, the defects in hox gene expression only partially explain these phenotypes. To gain deeper insight into Cdx4 function, we performed chromatin immuno-precipitation sequencing (ChIP-seq) combined with gene-expression profiling in zebrafish, and identified the transcription factor spalt-like 4 (sall4 ) as a Cdx4 target. ChIP-seq revealed that Sall4 bound to its own gene locus and the cdx4 locus. Expression profiling showed that Cdx4 and Sall4 coregulate genes that initiate hematopoiesis, such as hox,scl, and lmo2. Combined cdx4 /sall4 gene knock-down impaired erythropoiesis, and overexpression of the Cdx4 and Sall4 target genes scl and lmo2 together rescued the erythroid program. These findings suggest that auto- and cross-regulation of Cdx4 and Sall4 establish a stable molecular circuit in the mesoderm that facilitates the activation of the blood-specific program as development proceeds.</font></p>
    </div><!-- /.medium-6.columns -->
    
    <div class="medium-4 columns b30">
        <img src="{{ site.url }}/images/mahony-stem-cell-reports-3.png" alt="">
        <p> <font size="2">E.J. Paik, S. Mahony, R. M. White, E.N. Price, A. Dibiase, B. Dorjsuren, C. Mosimann, A. J. Davidson, D. Gifford, L. I. Zon. 
        <br> <i>Stem Cell Reports</i>. 2013 Nov 7;1(5):425-436</font></p>
    </div><!-- /.medium-6.columns -->
</div><!-- /.row -->

### 2013

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





