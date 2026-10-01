# HSP90 Atlas release-candidate changelog

## Data v6.422 — 2026-10-01

This candidate incorporates the canonical v6.422 gene–isoform pair and source-finding tables. Four support-only findings were added: an Hsp90ab1 knockdown response for IL6 in heat-shocked mouse N9 microglia (PMID 30448425); two positive HSP90AB1-labeled HeLa proximity-ligation screen pairs, NFKB1 and TRAF2 (PMID 25241761); and PXR/NR1I2 co-recovery with HSP90AB1 in human LS174T cells (PMID 28077325). The core contains 5,091 pairs and 4,114 source findings; 2,789 pairs have reviewed findings, 2,306 have pair-specific positive support, 137 are exclusion-only, and 2,302 remain discovery leads. The source-backed network contains 2,304 relationships.

The IL6 experiment supports a beta-targeted downstream response in its tested mouse model. The paper's beta/HSP90AA1 naming error was resolved using its published primer sequences, although the esiRNA sequence was unavailable. The NFKB1 and TRAF2 PLA calls remain cytosolic HSP90 associations because the beta-labeled antibody was not tested for alpha cross-reactivity; exact-pair signals and images were not reported. PXR/NR1I2 co-IP supports a cellular co-complex, not direct binding. None of the four additions establishes client dependence, isoform exclusivity, or new score points.

Exact reviews of HSP90AA1–IL6 (PMID 30448425), HSP90AA1–CASP3 (PMID 36209546), and HSP90AB1–IL6 (PMID 41876946) did not add public pair findings. The alpha-targeted intervention did not reproduce the IL-6 response in the tested N9 comparison; the CASP3 study found no significant transcript change after HSP90AA1 overexpression; and the fish hsp90b and goldfish il-6 measurements were made in separate systems without a pair test.

- The public cycle continues to use the reviewed-only v6.303 component horizon; private bulk cycle database observations are excluded.
- Affected HPA/CPTAC association summaries remain withheld.
- No deployment or public mirror update is authorized by this candidate build.
