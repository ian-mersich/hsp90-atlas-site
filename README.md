# HSP90 Atlas

The **HSP90 Atlas** is an isoform-specific resource for exploring human genes associated with HSP90AA1 (Hsp90alpha), HSP90AB1 (Hsp90beta), HSP90B1 (GRP94/gp96), and TRAP1.

**[Open the HSP90 Atlas](https://ian-mersich.github.io/hsp90-atlas-site/)**

The Atlas brings together manually reviewed papers, protein-interaction database records, protein and immunohistochemistry correlation analyses, and publication-discovery leads. It keeps these evidence classes separate so that a database association or correlation is not presented as a demonstrated physical interaction or client relationship.

## Current release

- **Atlas website:** v1.6.408
- **Atlas data:** v6.408 public review checkpoint
- **Relationships tracked:** 5,091 gene–isoform pairs
- **Reviewed findings:** 4,072 source-level records
- **Source-reviewed pairs:** 2,755; 2,272 have pair-specific support
- **Coverage:** non-comprehensive, with the largest remaining gaps for GRP94 and TRAP1

The site supports interactor search, four-isoform gene comparison, source-linked findings, an interaction network, a reviewed interactive HSP90-cycle schematic, and downloadable tables. Blank isoform panels mean that the current release has no record for that isoform; they are not negative results and do not establish isoform specificity.

Data v6.408 adds seven reviewed TRAP1 assay associations and the HSP90AB1–NR1I2 finding from PMID 25995454. PXR search resolves to NR1I2; duplicate PXR rows are merged into the canonical gene pairs. The beta-resolved binding finding retains the source's limitations and is not copied into the alpha pair. Organelle assay associations remain unscored and do not establish direct binding or client dependence.

Discovery leads are possible gene–HSP90 relationships suggested by protein-abundance correlations, interaction databases, or publication matches. These signals alone do not establish a direct interaction or client relationship. The affected CPTAC correlations and older download archives containing them are withheld from the active site; seven other HPA protein-profile matrices remain available as exploratory associations. Superseded archives remain recoverable in Git history.

## Repository scope

This repository is the public deployment mirror for the Atlas website. The validated static release is stored under [`site/`](site/) and published automatically through GitHub Pages.

Retrieved papers and supplements, private review queues, and in-progress curation records are not included. The public download bundle contains the release tables, source identifiers and links, relationship classifications, experimental context, and stated caveats.

## Citation and reuse

The contributor list, DOI-backed citation, and final code/data licenses are still being prepared. Until those are approved, use the interim citation provided on the Atlas Downloads page and consult the included license-status file before redistributing the data.

## Status

This is a public release candidate intended for scientific review and usability testing. The Atlas does not publish a final ranked reference set, and analytical associations are not used as stand-alone biological claims.
