# HSP90 Atlas v6.301 data horizons

The v6.301 Atlas release combines two related but biologically distinct evidence surfaces under one release identifier.

- The core HSP90 isoform atlas remains the cumulative v6.254 evidence layer: 5,092 gene–isoform relationships and 3,922 source-reviewed findings.
- The co-chaperone network download uses the canonical v6.301 review boundary: 457 source-specific findings across 351 reviewed co-chaperone or partner pairs and 72 primary sources.
- PMID 26186194 contributes 59 exact BioPlex HEK293T AP-MS network rows. Every row meets the source's CompPASS-Plus p(Interaction) threshold of at least 0.75.
- BioPlex edges are represented as cellular co-purification or shared-complex context. The collapsed network table is undirected at row level and does not establish direct binding, HSP90 dependence, client status, productive cycle participation, or isoform specificity.
- Eight source-era symbols were reconciled to current pair identifiers using exact Entrez Gene identifiers and corroborating UniProt accessions. No approximate symbol-only matches were accepted.
- All 59 BioPlex findings are zero-weight reviewed context. The affected pairs remain queued because other publications or database routes still require review.
- The analytical-profile sidecar remains the validated v6.109 analysis over the original v6.104 pair universe; it is not silently expanded to the current core universe.
- The private cycle explorer retains its v6.294 cycle-model component and v6.286 reviewed-neighborhood component while presenting the unified v6.301 shell release.

Coverage remains non-comprehensive. Database records and correlations are discovery context unless supported by reviewed primary-source evidence. This release does not create a final score, final rank, pathway interpretation, or scored reference set. All public Atlas surfaces and the private cycle explorer use the same v6.301 release label; older component horizons remain available only as provenance in the release manifest.
