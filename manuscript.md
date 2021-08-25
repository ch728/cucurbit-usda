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
  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />
  <meta name="twitter:creator" content="@None" />
  <link rel="canonical" href="https://ch728.github.io/cucurbit-usda/" />
  <meta property="og:url" content="https://ch728.github.io/cucurbit-usda/" />
  <meta property="twitter:url" content="https://ch728.github.io/cucurbit-usda/" />
  <meta name="citation_fulltext_html_url" content="https://ch728.github.io/cucurbit-usda/" />
  <meta name="citation_pdf_url" content="https://ch728.github.io/cucurbit-usda/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://ch728.github.io/cucurbit-usda/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://ch728.github.io/cucurbit-usda/v/e4bde9c3f4fe1e75de588967d3c8e4b6789dd3a0/" />
  <meta name="manubot_html_url_versioned" content="https://ch728.github.io/cucurbit-usda/v/e4bde9c3f4fe1e75de588967d3c8e4b6789dd3a0/" />
  <meta name="manubot_pdf_url_versioned" content="https://ch728.github.io/cucurbit-usda/v/e4bde9c3f4fe1e75de588967d3c8e4b6789dd3a0/manuscript.pdf" />
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
([permalink](https://ch728.github.io/cucurbit-usda/v/e4bde9c3f4fe1e75de588967d3c8e4b6789dd3a0/))
was automatically generated
from [ch728/cucurbit-usda@e4bde9c](https://github.com/ch728/cucurbit-usda/tree/e4bde9c3f4fe1e75de588967d3c8e4b6789dd3a0)
on August 25, 2021.
</em></small>

## Authors



+ **Christopher Owen Hernandez**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [ch728](https://github.com/ch728)<br>
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
emerging \cite{zheng_cucurbit_2019}. Already, these resources have been used to 
elucidate the genetics of fruit quality, growth habit, disease resistance, and 
to increase the efficiency of cucurbi
t improvement \cite{montero-pau_snp-based_2017, zhong_high-density_2017, kazminska_genetic_2018, wu_genomic_2019,xanthopoulou_whole-genome_2019}; however, there has yet to be a 
comprehensive survey of the genetic diversity in large diverse *Cucurbita* 
germplasm panels, such as those maintained by the USDA within the Germplasm 
Resources Information Network (GRIN) system.

Germplasm collections play a vital role in maintaining and preserving genetic variation. These collections can be 
mined by breeders for valuable alleles and can by geneticists for mapping studies. Many s. The collections of 
The Cucurbit Coordinated Agricultural Project (CucCap project) has been established to help close the knowledge 
gap in Cucurbits. This collaborative project aims to provide genomics resources and tools that can aid in both 
applied breeding and basic research. The genetic and phenotypic diversity present in the USDA watermelon and cucumber 
collections has already been explored as part of the CucCap project, partially through the sequencing of USDA germplasm 
collections and development of core collections for whole-genome sequencing \cite{wang_usda_2018, wu_genome_2019}. 
	
The classification system used in squash is complex. Squash from each species can be classed as winter or summer squash 
depending on whether the fruit is consumed at an immature or mature stage, the latter is a winter squash \cite{loy_morpho-physiological_2004}. 
Squash are considered ornamental if they are used for decoration, and some irregularly shaped, inedible ornamental squash are 
called gourds; however, gourds include members of *Cucurbita* as well as some species from *Lagenaria*---not all gourds
are squash \cite{liberty_hyde_bailey_garden_1937, paris_germplasm_2016}. Many squash are known as pumpkins; the pumpkin designation is a
culture dependent colloquialism that can refer to jack O' lantern types, squash used for desserts or, in some Latin American countries, 
to eating squash from *C. moschata* known locally as Calabaza \cite{ferriol_pumpkin_2008}. Cultivars deemed as pumpkins can be 
found in all widely cultivated squash species. Unlike the previous groupings, morophotypes/market classes are defined within species.
For example, a Zucchini is reliably a member of *C. pepo* and a Buttercups are from *C. maxima*. Adding to the complexity 
of their classification, the *Cucurbita* species are believed to have arisen from independent domestication events and the 
relationships between cultivated and wild species remains poorly understood \cite{kates_evolutionary_2017}.
	
*C. pepo* is the most economically important of the *Cucurbita* species and is split into two different 
subspecies: *C. pepo* subsp. *pepo* and *C. pepo* subsp. *ovifera* \cite{xanthopoulou_whole-genome_2019}.
Evidence points to Mexico as the center of origin for *pepo* and southwest/central United States as the origin of *ovifera*. 
The progenitor of *ovifera* is considered by some to be subsp. \textit{ovifera} var. \textit{ texana}, 
whereas subsp. \textit{fraterna} is a candidate progenitor for \textit{pepo} \cite{kates_evolutionary_2017}. Europe played a 
crucial role as a secondary center of diversification for \textit{pepo}, but not \textit{ovifera} \cite{lust_italian_2016}. 
Important morphoptypes of \textit{pepo} include  Zucchini, Spaghetti squash, Cocozelle, Vegetable marrow, and some ornamental pumpkins. 
\textit{C. pepo} subsp. \textit{ovifera} includes summer squash from the Crookneck, Scallop, and Straightneck group, and winter squash 
such as Delicata and Acorn \cite{paris_parallel_2012}. 
	
The origin of *C. moschata* is more uncertain than *C. pepo*; it is unclear whether *C. moschata* 
has a South or North American origin \cite{chomicki_origin_2019}. Where and when domestication occurred for this species is 
also unknown; however it is known that *C. moschata* had an India-Myanmar secondary center of origin where the species was 
further diversified \cite{sun_karyotype_2017}. *C. moschata* plays an important role in squash breeding as it cross-fertile to 
various degrees with *C. pepo* and *C. maxima*, and can thus be used as a bridge to move genes across species 
\cite{sun_karyotype_2017}. Popular market classes of *C. moschata* include Cheese types like Dickenson, which is widely used 
for canned pumpkin products, Butternut (neck) types, Japonica, and tropical pumpkins known as Calabaza \cite{ferriol_pumpkin_2008}.
	
*C. maxima* contains many popular winter squash including Buttercup/Kobocha types, Kuri, Hubbard, and Banana squash 
\cite{ferriol_pumpkin_2008}. This species also sports the world's largest fruit, the giant pumpkin whose fruit are grown for 
competition and can reach well over 1000 Kg \cite{savage_making_2015}. Although this species exhibits a wide range of phenotypic
diversity in terms of fruit characteristics, it appears to be the least genetically diverse of the three species described \cite{kates_evolutionary_2017}. 
*C. maxima* is believed to have a South American origin, and was likely domesticated near Peru, with a secondary center of 
domestication in Japan/China\cite{nee_domestication_1990, sun_karyotype_2017}.

 In this study, we set out to characterize the genetic diversity present in the USDA \textit{Cucurbita} germplasm collections 
 for *C. pepo*, *C. moschata*, and *C. maxima*. We present genotyping-by-sequencing data from each of these 
 collections, population genomics analysis, results from genome-wide association using historical and contemporary phenotypes, and 
 develop a core panel for re-sequencing.


## Material and Methods


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
