---
title: Characterization of the USDA Cucurbita pepo, Cucurbita moschata, and Cucurbita maxima Collections
keywords:
- GRIN
- Cucurbits
- Diversity
- Germplasm collection
- Cucurbita pepo
- Cucurbita moschata
- Cucurbita maxima
lang: en-US
date-meta: '2021-08-25'
author-meta:
- Christopher Owen Hernandez
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="Characterization of the USDA Cucurbita pepo, Cucurbita moschata, and Cucurbita maxima Collections" />
  <meta name="citation_title" content="Characterization of the USDA Cucurbita pepo, Cucurbita moschata, and Cucurbita maxima Collections" />
  <meta property="og:title" content="Characterization of the USDA Cucurbita pepo, Cucurbita moschata, and Cucurbita maxima Collections" />
  <meta property="twitter:title" content="Characterization of the USDA Cucurbita pepo, Cucurbita moschata, and Cucurbita maxima Collections" />
  <meta name="dc.date" content="2021-08-25" />
  <meta name="citation_publication_date" content="2021-08-25" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Christopher Owen Hernandez" />
  <meta name="citation_author_institution" content="Department of Plant Breeding and Genetics, Cornell University" />
  <meta name="citation_author_orcid" content="None" />
  <meta name="twitter:creator" content="@None" />
  <link rel="canonical" href="https://ch728.github.io/cucurbit-usda/" />
  <meta property="og:url" content="https://ch728.github.io/cucurbit-usda/" />
  <meta property="twitter:url" content="https://ch728.github.io/cucurbit-usda/" />
  <meta name="citation_fulltext_html_url" content="https://ch728.github.io/cucurbit-usda/" />
  <meta name="citation_pdf_url" content="https://ch728.github.io/cucurbit-usda/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://ch728.github.io/cucurbit-usda/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://ch728.github.io/cucurbit-usda/v/1aa490f03764d59a6c858dbc5f44cd5f79e49548/" />
  <meta name="manubot_html_url_versioned" content="https://ch728.github.io/cucurbit-usda/v/1aa490f03764d59a6c858dbc5f44cd5f79e49548/" />
  <meta name="manubot_pdf_url_versioned" content="https://ch728.github.io/cucurbit-usda/v/1aa490f03764d59a6c858dbc5f44cd5f79e49548/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://ch728.github.io/cucurbit-usda/v/1aa490f03764d59a6c858dbc5f44cd5f79e49548/))
was automatically generated
from [ch728/cucurbit-usda@1aa490f](https://github.com/ch728/cucurbit-usda/tree/1aa490f03764d59a6c858dbc5f44cd5f79e49548)
on August 25, 2021.
</em></small>

## Authors



+ **Christopher Owen Hernandez**<br><br>
  <small>
     Department of Plant Breeding and Genetics, Cornell University
     · Funded by Grant XXXXXXXX
  </small>



## Abstract {.page_break_before}
The *Cucurbita* genus is home to a number of economically and culturally important species. We present the analysis of genotyping-by-sequencing data generated from sequencing the USDA germplasm collections of *Cucurbita pepo*, *Cucurbita moschata*, and *Cucurbita maxima*. These collections include a mixture of wild, landrace, and cultivated specimens from all over the world. Roughly 4,000 - 40,000 quality SNPs were called in each of the collections, which ranged in size from 314 to 829 accessions. Genomic analyses were conducted to characterize the diversity in each of the species and revealed extensive structure corresponding to a combination of geographical origin and morphotype/market class. GWAS was conducted for each data set using both historical and contemporary data, and signals were detected for several traits, including the bush gene (*Bu*) in *C. pepo*. These data represent the largest collection of sequence *Cucurbita* and can be used to direct the maintenance of genetic diversity, develop breeding resources, and to help prioritize  whole-genome re-sequencing for further GWAS and other genomics studies aimed at understanding the phenotypic and genetic diversity present *Cucurbita*.



## Introduction

The *Cucurbitaceae* (Cucurbit) family is home to a number of vining species 
mostly cultivated for their fruits. This diverse and economically important 
family includes cucumber (*Cucumis sativa*), melon (*Cucumis melo*), 
watermelon (*Citrullus lanatus*), and squash (*Cucurbita ssp.*) 
[@doi:10.1007/978-0-387-30443-4_10]. Like other cucurbits, squash exhibit 
diversity in growth habit, fruit morphology, metabolite content, disease 
resistance, and have a nuanced domestication story 
[@doi:10.21273/HORTSCI.40.6.1620; @doi:10/gsg7]. 
The genomes of *Cucurbita ssp.* are 
small (roughly 500 Mb), but result from complex interactions between ancient
genomes brought together through an allopolyploidization event
[@doi:10.1016/j.molp.2017.09.003]. These factors make squash an excellent model for 
understanding the biology of genomes, fruit development, and domestication.
Within *Cucurbita*, five species are recognized as domesticated. 
Three of these are broadlycultivated: *Cucurbita maxima*, *Cucurbita moschata*, 
and *Cucurbita pepo* [@doi:10.1007/978-0-387-30443-4_10]. 
Few genomic resources have been 
available for working with these species; although, draft genomes and 
annotations, along with  web-based tools and other genomics data are 
emerging [@doi:10.1093/nar/gky944]. Already, these resources have been used to 
elucidate the genetics of fruit quality, growth habit, disease resistance, and 
to increase the efficiency of cucurbit improvement 
[@doi:10.1186/s12864-016-3439-y; @doi:10.1038/s41598-017-13216-3; 
@doi:10.1007/s11032-018-0869-z; @doi:10.3835/plantgenome2018.10.0082; 
@doi:10.1038/s41438-019-0176-9]; however, there has yet to be a 
comprehensive survey of the genetic diversity in large diverse *Cucurbita* 
germplasm panels, such as those maintained by the USDA within the Germplasm 
Resources Information Network (GRIN) system.

Germplasm collections play a vital role in maintaining and preserving 
genetic variation. These collections can be mined by breeders for valuable 
alleles and can by geneticists for mapping studies. Many s. The collections of 
The Cucurbit Coordinated Agricultural Project (CucCap project) has been established 
to help close the knowledge gap in Cucurbits. This collaborative project aims to 
provide genomics resources and tools that can aid in both applied breeding and basic 
research. The genetic and phenotypic diversity present in the USDA watermelon and cucumber 
collections has already been explored as part of the CucCap project, partially
through the sequencing of USDA germplasm collections and development of core collections for 
whole-genome sequencing [@doi:10.1038/s41438-018-0080-8; @doi:10.1111/pbi.13136].
	
The classification system used in squash is complex. Squash from each species can be 
classed as winter or summer squash depending on whether the fruit is consumed at an 
immature or mature stage, the latter is a winter squash [@doi:abs/10.1080/07352680490490733]. 
Squash are considered ornamental if they are used for decoration, and some irregularly shaped, 
inedible ornamental squash are called gourds; however, gourds include members of *Cucurbita* 
as well as some species from *Lagenaria*---not all gourds are squash 
[@doi:10.1007/s10681-015-1605-y]. Many squash are known as pumpkins; 
the pumpkin designation is aculture dependent colloquialism that can refer to jack O' lantern types,
squash used for desserts or, in some Latin American countries, to eating squash from *C. moschata* 
known locally as Calabaza [@doi:10.1007/978-0-387-30443-4_10]. Cultivars deemed as pumpkins can be 
found in all widely cultivated squash species. Unlike the previous groupings, morophotypes/market 
classes are defined within species.For example, a Zucchini is reliably a member of *C. pepo* and a 
Buttercups are from *C. maxima*. Adding to the complexity of their classification, the *Cucurbita* 
species are believed to have arisen from independent domestication events and the 
relationships between cultivated and wild species remains poorly understood [@doi:10.1016/j.ympev.2017.03.002].
	
*C. pepo* is the most economically important of the *Cucurbita* species
and is split into two different subspecies: *C. pepo* subsp. *pepo* 
and *C. pepo* subsp. *ovifera* [@doi:10.1038/s41438-019-0176-9]. Evidence points 
to Mexico as the center of origin for *pepo* and southwest/central United States 
as the origin of *ovifera*. The progenitor of *ovifera* is considered by some 
to be subsp. *ovifera* var. *texana*, whereas subsp. *fraterna* 
is a candidate progenitor for *pepo* [@doi:10.1016/j.ympev.2017.03.002]. Europe played a 
crucial role as a secondary center of diversification for *pepo*, but not 
*ovifera* [@doi:10.1093/aob/mcw080]. Important morphoptypes of *pepo* 
include  Zucchini, Spaghetti squash, Cocozelle, Vegetable marrow, and some 
ornamental pumpkins. *C. pepo* subsp. *ovifera* includes summer 
squash from the Crookneck, Scallop, and Straightneck group, and winter squash 
such as Delicata and Acorn [@doi:10.1007/s12231-012-9186-3]. 
	
The origin of *C. moschata* is more uncertain than *C. pepo*; 
it is unclear whether *C. moschata* has a South or North American origin 
[@doi:10.1111/nph.16015]. Where and when domestication occurred for this species is 
also unknown; however it is known that *C. moschata* had an India-Myanmar 
secondary center of origin where the species was further diversified [@doi:10.1016/j.molp.2017.09.003]. 
*C. moschata* plays an important role in squash breeding as it cross-fertile to 
various degrees with *C. pepo* and *C. maxima*, and can thus be used as a bridge 
to move genes across species  [@doi:10.1016/j.molp.2017.09.003]. Popular market classes 
of *C. moschata* include Cheese types like Dickenson, which is widely used 
for canned pumpkin products, Butternut (neck) types, Japonica, and tropical 
pumpkins known as Calabaza [@doi:10.1007/978-0-387-30443-4_10].
	
*C. maxima* contains many popular winter squash including Buttercup/Kobocha 
types, Kuri, Hubbard, and Banana squash [@doi: @doi:10.1007/978-0-387-30443-4_10]. This 
species also sports the world's largest fruit, the giant pumpkin whose fruit are grown for 
competition and can reach well over 1000 Kg [@doi:10.1111/pce.12502]. Although this 
species exhibits a wide range of phenotypic diversity in terms of fruit characteristics, 
it appears to be the least genetically diverse of the three species described 
[@doi:10.1016/j.ympev.2017.03.002]. *C. maxima* is believed to have a South American origin, 
and was likely domesticated near Peru, with a secondary center of 
domestication in Japan/China [nee_domestication_1990; @doi:10.1016/j.molp.2017.09.003].

 In this study, we set out to characterize the genetic diversity present in 
 the USDA *Cucurbita* germplasm collections for *C. pepo*, *C. moschata*, 
 and *C. maxima*. We present genotyping-by-sequencing data from each of these 
 collections, population genomics analysis, results from genome-wide association 
 using historical and contemporary phenotypes, and develop a core panel for re-sequencing.


## Material and Methods

### Plant Materials and Genotyping
All available germplasm were requested from USDA cooperators for *C. maxima* (534), *C. moschata* (314), and *C. pepo* (829) respectively. Seeds were planted in 50-cell trays and two 3/4 inch punches of tissue (approximately 80-150 mg) was sampled from the first true leaf of each seedling. DNA was extracted using Omega Mag-Bind Plant DNA DS kits (M1130, Omega Bio-Tek, Norcross, GA) and quantified using Quant-iT PicoGreen dsDNA Kit (Invitrogen, Carlsbad, CA). Purified DNA was shipped to Cornell's Genomic Diversity Facility for GBS library preparation using protocols optimized for each species. Libraries were sequenced at either 96, 192, or 384-plex on the HiSeq 2500 (Illumina Inc., USA) with single-end mode and a read length of 101 bp.

### Variant Calling and Filtering

SNP calling was conducted using the TASSEL-GBS V5 pipeline [@doi:10.1371/journal.pone.0090346]. Tags produced by this pipeline were aligned using the default settings of the BWA aligner [@doi:10.1093/bioinformatics/btp324]. Raw variants were filtered using VCFtools [@doi:10.1093/bioinformatics/btr330]. Before filtering SNPs, samples with a total read depth of $$\geq 2$$ standard deviations below the mean of all samples were removed before further analysis. Settings for filtering SNPs were as follows, minor allele frequency (MAF) $$\geq 0.01$$, missingness $$\leq 0.5$$, and biallelic. Three outlier genotypes were found in an initial PCA analysis of the  *C. maxima* data and were removed, as they were likely not *C. maxima*. Variants were further filtered for specific uses as described below.

### Population Genomics Analysis

ADMIXTURE [@doi:10.1186/1471-2105-12-246], which uses a model-based approach to infer ancestral populations ($$k$$) and admixture proportions in a given sample, was used to explore population structure in each dataset. ADMIXTURE does not model linkage disequilibrium; thus, marker sets were further filtered to obtain SNPs in approximate linkage equilibrium using the "--indep-pairwise" option in PLINK \cite{purcell_plink:_2007} with $$r^2$$ set to 0.1, a window size of 50 SNPs, and a 10 SNP step size . All samples labeled as cultivars were removed from the data prior to running ADMIXTURE. Cross-validation was used to determine the best $k$ value for each species. Briefly, ADMIXTURE was run with different $k$ values (1-20) and the cross-validation error was reported for each $$k$$. The $$k$$ value with minimal cross-validation error was chosen for each species (Supplemental Figures \ref{error}). Ancestral populations were then assigned to cultivars using the program's projection feature.

Principal components analysis (PCA) was used as a model-free way of determining population structure. The original filtered marker data, not the LD-pruned data used for ADMIXTURE, were converted to a dosage matrix using VCFtool's "--012" argument. A kinship matrix $$\mathbf{K}$$ was created using the dosage matrix as input to the "A.mat()" function in Sommer \cite{covarrubias-pazaran_genome-assisted_2016}. PCA was conducted using the R function "princomp()" with $$\mathbf{K}$$ supplied as the covariance matrix.

Phylogenetic analysis was conducted in a subset of the *C. pepo* panel with clearly labeled subspecies information or where enough information to unambiguously assign the accession to a subspecies was present. The SNPhylo \cite{lee_snphylo_2014} pipeline was used to infer an unrooted tree using the maximum likelihood method. Default settings were used, except the minimum coverage parameter was decreased to 3 instead of 5 to account for the lower average coverage of GBS data.

### Analysis of Phenotypic Data
Historical data were obtained from the USDA Germplasm Resources Information Network (GRIN; http://www.ars-grin.gov) for \textit{C. maxima}, \textit{C. pepo}, and \textit{C. moschata}. Data included phenotype data as well as narratives/descriptions associated with accessions. Narrative data were parsed into a list of informative words, using a custom Python script, to produce a qualitative snapshot of the diversity present in each collection. All duplicated entries were removed for qualitative traits, where categories are mutually exclusive, leaving only samples with unique entries for analysis. Contemporary phenotypic data were collected from a subset of the \textit{C. pepo} collection grown in the summer of 2018 in Ithaca, NY. Field-grown plants were phenotyped for vining bush habit at three different stages during the growing seasons to confirm bush, semi-bush or vining growth habit. Plants that had a bush habit early in the season but started to vine at the end of the season were considered semi-bush.

Genomic heritability \cite{campos_genomic_2015} ($h_{g}^2$)  was calculated for all phenotypes. The parameter $h_{g}^2$ was calculated for continuous traits using the formula $h_{g}^2 = \frac{\sigma_{g}^2}{\sigma_{g}^2 + \sigma_{e}^2}$, where $\sigma_{g}^2$ and $\sigma_{e}^2$ are genetic and error variances estimated from a whole-genome regression of phenotype on marker data using ASReml-R \cite{butler_asreml-r_2009}. Multi-class categorical traits were converted to one or several different binary traits depending on the number of entries in each category. For binary traits, a Logit model was fit for the binary response and the heritability was estimated as $h_{g}^2 = \frac{\sigma_{g}^2}{\sigma_{g}^2 + \frac{\pi^2}{3}}$ \cite{biscarini_genome-enabled_2014}. In addition to heritability, the amount of phenotypic variance explained by population structure ($R_{pop}^2$) was calculated from a multiple linear regression of phenotype on sturcture inferred by ADMIXTURE. The R function lm was used to regress continuous phenotypes on the $\mathbf{Q}$ matrix obtained from ADMIXTURE. The R glm function was used with "family=binomial" to regress binary traits on population structure. As there is no $R^2$ defined for logistic models, McFadden’s psuedo $R^2$ was used to assess the correlation between binary traits and population structure \cite{hemmert_log-likelihood-based_2018}.

### GWAS
Data were imputed prior to association analysis. LinkImpute \cite{money_linkimpute:_2015}, as implemented by the TASSEL \cite{bradbury_tassel:_2007} "LDKNNiImputatioHetV2Plugin" plugin was used for imputation with default settings. Any data still missing after this process were mean imputed. The GENESIS \cite{gogarten_genetic_2019} R package, which can model both binary and continuous traits, was used for association. All models included the first two PCs of the marker matrix as fixed effects and modeled genotype effect ($u$) as a random effect distributed according to the kinship ($\mathbf{K}$) matrix ($u \sim N(0, \sigma_{u}^2\mathbf{K})$). Binary traits were modeled using the logistic regression feature in GENESIS. 

### Creation of a Core Collection

Subsets representative of each panel's genetic diversity were identified through running GenoCore \cite{jeong_genocore:_2017} on each of the filtered SNP sets. A subset of the \textit{C. pepo} panel and key genotypes from the other two species were combined to form a core collection for the cucurbit community. (Insert criteria here) . These genotypes will be further purified through two additional rounds of selfing and then resequenced using skim-sequecing to produce whole-genome data.


# Results


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
