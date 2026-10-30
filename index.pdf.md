---
title: "Introduction"
subtitle: "Module 2 computer laboratory"
execute:
  echo: true
---

::: {.callout-note title="**Intended Learning Outcomes**"}
By the end of this practical, you should be able to:

- navigate aligned short-read sequencing data in IGV
- interpret genes, exons, introns, reading frames, repeats and regulatory annotations
- identify candidate sequence variants and distinguish them from likely sequencing or alignment artefacts
- assess Mendelian inheritance in a parent-child trio
- phase nearby variants into haplotypes using family information and paired reads
- investigate population frequency and predicted functional consequences using Ensembl, VEP and gnomAD
:::

The advent of short-read sequencing technologies, allowing high-throughput DNA sequencing at relatively low cost, has revolutionised genetics over the last fifteen years or so. In particular the ability to sequence whole human exomes, genomes and transcriptomes, has transformed how we conduct human genetics, yielding radical new approaches to human disease gene identification and allowing us to ask questions largely unimaginable just a few years ago. However, although in many areas it is relatively straightforward to generate DNA sequence data, interpreting the masses of data generated remains a major logistical and bioinformatic challenge. Fortunately, data analysis and interpretation are still largely based on fundamental genetic principles and our knowledge of the molecular pathway from DNA to RNA to protein.

In this session we will familiarise ourselves with a web app version of the Integrated Genome Viewer (IGV). This app allows us to visualise aligned NGS data, to identify sequence variants and to sort neighbouring variants into haplotypes. To do this we will use publicly accessible whole genome sequence data from a parent-child trio derived from the ‘Platinum genomes’, described in:

- Eberle, M.A., Fritzilas, E., Krusche, P., Kallberg, M., Moore, B.L., Bekritsky, M.A., Iqbal, Z., Chuang, H.Y., Humphray, S.J., Halpern, A.L., Kruglyak, S., Margulies, E.H., McVean, G. and Bentley, D.R. (2017) A reference data set of 5.4 million phased human variants validated by genetic inheritance from sequencing a three-generation 17-member pedigree. *Genome Res. 27, 157-164.* [https://doi.org/10.1101/gr.210500.116](https://genome.cshlp.org/content/27/1/157){target="_blank" rel="noopener noreferrer"}

These short-read data were obtained using whole genome sequencing via paired-end 2x100 bp reads on an Illumina HiSeq2000 platform. Sequencing was performed to an average depth of 50x.
