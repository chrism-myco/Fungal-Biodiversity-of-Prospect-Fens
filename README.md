# Fungal-Biodiversity-of-Prospect-Fens
Bioniformatic analyses of fungal biodiversity using ITS2 sequences

Soil samples were collected from Prospect Basin Fens and the forests immediatelly abutting each fen. Samples were collected in the summer of 2025. DNA was extracted using Omega Biotek's EZNA soil kit. PCR amplification of ITS2 regions was completed by Scripps Research. 

Once ITS2 sequences were obtained, this project combined LotuS2, Funguild, and R data pipelines to assess differences (if any) in soil fungal communities with respect to two variables: _peat accumulation_ (samples within the fen boundary) and _vaccinium presence_

The following analyses were conducted to explore peat and vaccinium's relationship to soil fungal community: 

Abundance and occurrence based **stacked bar charts**
  > absolute and relative counts by phylum
  > absolute and relative counts by 'guild'

Abundance and occurence based **alpha diversity**
  > _Shannon Index_ by peat and vaccinium
  > _Observed Richness_ by peat and vaccinium

Abundance and occurence based **beta diversity**
  > _PCoA_ using weighted and unweighted unifrac distances
  > _NMDS_ using Bray-Curtis and Jaccard distances

**Species accumulation** in total and for all cases
    (Peat=T + Vaccinium=T, Peat=T + Vaccinium=F, etc.)

Species lists and four way **venn diagram** for all cases
