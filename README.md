# HSP90 Atlas

The **HSP90 Atlas** is an isoform-specific resource for exploring human genes associated with HSP90AA1 (Hsp90alpha), HSP90AB1 (Hsp90beta), HSP90B1 (GRP94/gp96), and TRAP1.

**[Open the HSP90 Atlas](https://ian-mersich.github.io/hsp90-atlas-site/)**

The Atlas brings together manually reviewed papers, protein-interaction database records, protein and immunohistochemistry correlation analyses, and publication-discovery leads. It keeps these evidence classes separate so that a database association or correlation is not presented as a demonstrated physical interaction or client relationship.

## Current release

- **Atlas website:** v1.6.413
- **Atlas data:** v6.413 public review checkpoint
- **Relationships tracked:** 5,091 gene–isoform pairs
- **Reviewed findings:** 4,099 source-level records
- **Source-reviewed pairs:** 2,781; 2,298 have pair-specific support
- **Coverage:** non-comprehensive, with the largest remaining gaps for GRP94 and TRAP1

The site supports interactor search, four-isoform gene comparison, source-linked findings, an interaction network, a reviewed interactive HSP90-cycle schematic, and downloadable tables. Blank isoform panels mean that the current release has no record for that isoform; they are not negative results and do not establish isoform specificity.

Data v6.413 adds thirteen source-reviewed findings: ten weak, unscored cytosolic HSP90 affinity-purification mass-spectrometry associations (PMID 33961781), two ITGB1BP2 yeast two-hybrid interactions with HSP90alpha and HSP90beta (PMID 23414517), and EP300-mediated HSP90alpha acetylation (PMID 18559531). The yeast assay is explicitly identified in the interface and exports; it does not establish purified mammalian binding or client maturation. EP300 is shown as an upstream regulator, not an HSP90 client. Previously reviewed TRAP1 proximity-labeling findings remain visible, while UQCRFS1 and VWA8 remain held. PXR search continues to resolve to canonical NR1I2, retaining the beta-only PMID 25995454 finding and its limitations.

Discovery leads are possible gene–HSP90 relationships suggested by protein-abundance correlations, interaction databases, or publication matches. These signals alone do not establish a direct interaction or client relationship. The affected CPTAC correlations and older download archives containing them are withheld from the active site; seven other HPA protein-profile matrices remain available as exploratory associations. Superseded archives remain recoverable in Git history.

## Repository scope

This repository is the public deployment mirror for the Atlas website. The validated static release is stored under [`site/`](site/) and published automatically through GitHub Pages.

Retrieved papers and supplements, private review queues, and in-progress curation records are not included. The public download bundle contains the release tables, source identifiers and links, relationship classifications, experimental context, and stated caveats.

## Citation and reuse

The contributor list, DOI-backed citation, and final code/data licenses are still being prepared. Until those are approved, use the interim citation provided on the Atlas Downloads page and consult the included license-status file before redistributing the data.

## Status

This is a public release candidate intended for scientific review and usability testing. The Atlas does not publish a final ranked reference set, and analytical associations are not used as stand-alone biological claims.
