---
layout: default
section: Genomic Research
---

[← Back to Genomic Research]({{ "/genomics/" | relative_url }})

## Pharmacogenetic GWAS of Bone Mineral Density
*Multi-site randomized controlled clinical trial · HPC pipeline*

### Overview

[EDIT] Beta-blockers are widely prescribed, and there is evidence they may affect bone health, but genetic differences in that response are poorly understood. Using data from a multi-site randomized controlled clinical trial, I am running a genome-wide association study of beta-blocker response and bone mineral density change on Northeastern's Explorer HPC cluster. The pipeline covers genotype QC, association testing with PLINK and REGENIE, and a post-GWAS workflow: fine-mapping, functional annotation and eQTL mapping, pathway and tissue enrichment, and colocalization and Mendelian randomization.

### Figures

![Pipeline: QC → association → fine-mapping → annotation → enrichment → MR]({{ "/images/gwas-1.png" | relative_url }})
*Pipeline: QC → association → fine-mapping → annotation → enrichment → MR*

![Demonstration Manhattan plot using public summary statistics]({{ "/images/gwas-2.png" | relative_url }})
*Demonstration Manhattan plot using public summary statistics*

![Demonstration QQ plot using public summary statistics]({{ "/images/gwas-3.png" | relative_url }})
*Demonstration QQ plot using public summary statistics*

### Skills Demonstrated

GWAS QC and association (PLINK, REGENIE) · HPC computing · Post-GWAS analysis · Reproducible pipelines

<!-- After publication: add the paper link here, and replace demo figures with real results. -->
