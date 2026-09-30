# HSP90 Atlas release-candidate changelog

## Data v6.408 TRAP1 review and PXR alias reconciliation - 2026-09-30

- Added seven unscored TRAP1 assay associations reviewed in v6.407 and the reviewed HSP90AB1–NR1I2 direct-binding finding from PMID 25995454, retaining the source's binding and client limitations.
- Reconciled PXR into NR1I2, combining duplicate discovery rows and database-citation provenance. PXR search and gene navigation resolve to the canonical NR1I2 records; exports retain canonical symbols. The new beta-resolved finding is not copied into the alpha pair.
- The core contains 5,091 tracked pairs, 4,072 source findings, 2,755 reviewed pairs, and 2,272 pairs with pair-specific support. The reviewed network contains 2,270 records. No final reference set or pathway conclusion is added.
- Retained the frozen v6.303 reviewed cycle and v6.301 co-chaperone component; affected HPA CPTAC correlations and older public download archives remain withheld.

## Data v6.403 cumulative organelle and cytosolic source review - 2026-09-29

- Incorporated the v6.402 organelle review and three v6.403 cytosolic observations. The organelle addition retains GRP94/ERGIC1, ITIH3, SEC61B, and TM9SF4, and TRAP1/AFG3L2, DLD, DNAJA3, IARS2, and TIMM44 as assay-level associations with their reported limitations.
- Added HSP90AA1–MAVS as a constrained support-only candidate-client observation, HSP90AA1–USP9X as a disease-model-specific upstream stability mechanism, and extracellular MMP2 association in the compared cytosolic isoform views. The MMP2 result remains an assay association; conditioned-medium co-immunoprecipitation does not establish purified binary binding, HSP90AB1 preference, or client status.
- The core contains 5,093 tracked pairs, 4,064 source findings, 2,748 source-reviewed pairs, and 2,265 pairs with pair-specific support. The reviewed interaction network contains 2,263 links. No final client assignment, isoform-preference claim, ranked reference set, or pathway interpretation was added.
- Retained the v6.301 co-chaperone and v6.303 reviewed-cycle components, and continued withholding the affected HPA CPTAC association coefficients and derived labels.

## Data v6.400 TRAP1 source review - 2026-09-29

- Added ten source-reviewed, unscored assay associations for TRAP1 with DBT, DLST, ETFA, GFM1, LRPPRC, MRPS26, PARK7, SHMT2, TACO1, and TRMT10C. Eight come from HEK293 TRAP1-bait proximity labeling and two from affinity-purification and immunoprecipitation mass spectrometry. None establishes direct binding or client dependence.
- Retained all v6.397 findings and pair-status distinctions. The core contains 5,093 tracked pairs, 4,051 source findings, 2,735 reviewed pairs, and 2,252 pairs with specific support. The reviewed interaction network contains 2,250 links.
- Retained the v6.301 co-chaperone and v6.303 cycle components and continued withholding the affected HPA CPTAC association coefficients and derived labels.

## Data v6.397 organelle source review - 2026-09-29

- Added ten source-reviewed assay observations across nine previously unreviewed gene–isoform pairs: HSP90B1/GRP94 with ERGIC1, ITIH3, SEC61B, and TM9SF4; TRAP1 with AFG3L2, DLD, DNAJA3, IARS2, and TIMM44. DLD has two independent findings. These assays show co-recovery, proximity, or a cross-link in their reported systems; none establishes direct binary binding or client dependence.
- Retained all v6.396 findings and pair-status distinctions. The core contains 5,093 tracked pairs, 4,041 source findings, 2,725 reviewed pairs, and 2,242 pairs with specific support. The reviewed interaction network contains 2,240 links.
- Retained the v6.301 co-chaperone and v6.303 cycle components and continued withholding the affected HPA CPTAC association coefficients and derived labels.

## Data v6.396 pair-status correction - 2026-09-29

- Corrected pair-level source-support status so context-only or otherwise non-supportive reviewed findings do not turn a gene–isoform pair into a supported relationship. Of 2,716 reviewed pairs, 2,233 have pair-specific support; 342 have only context or response evidence, four have only scoring-candidate findings, and 137 have only exclusionary findings. Reused the unchanged v6.395 source tables: 5,093 tracked pairs and 4,031 reviewed source findings.
- Preserved source details, caveats, and assay scope, including cases where an HSP90-family or shared-cytosolic result does not identify an individual isoform. No new paper finding, direct-binding claim, or client assignment was added.
- The network now contains 2,231 source-backed links under the corrected support criterion. Retained the reviewed HSP90-cycle and co-chaperone components, and continued withholding the affected HPA CPTAC association coefficients and derived labels.

## Data v6.395 HSP90β source-review update - 2026-09-29

- Added one support-only HSP90AB1–PPM1B cellular co-recovery finding from the article's original HA-PPM1B IP-MS supplement. The separate HSP90B phospho-array labels remain isoform-unresolved; no direct-binding, co-chaperone, or client claim was added.
- Closed ten further exact-PMID cytosolic co-mention routes as reviewed without pair-specific evidence. These do not add HSP90 interaction edges.
- Retained previous source corrections and the reviewed cycle while continuing to withhold the affected HPA CPTAC coefficients and derived labels.

## Data v6.394 GRP94 source-review update - 2026-09-29

- Added three qualified source observations for HSP90B1/GRP94 with DDOST and RPN2: two modeled co-fractionation associations and one RPN2-bait BioID proximity result. Two gene–isoform pairs now have source-reviewed association evidence; neither is promoted to direct binding or client status.
- Retained every v6.391 recheck correction and all previously reviewed findings. Additional cytosolic papers were reviewed without adding unsupported pair claims.
- Rebuilt the public evidence files and network while keeping the affected HPA CPTAC coefficients and derived labels withheld. The reviewed co-chaperone and cycle evidence is unchanged.

## Data v6.391 source-review update - 2026-09-29

- Resolved 155 gene–isoform pairs previously shown with only findings requiring source recheck. Twenty-five retain named-isoform support; 124 lack pair-specific support in the reviewed sources, and six provide biological context without a pair-specific interaction.
- Added nine source-reviewed observations across six gene–isoform pairs, including one newly tracked HSP90AB1–DSCC1 pair. The extracellular HSP90α and IL-6 promoter findings are labeled as signaling or regulatory results, not binding or client maturation.
- Rebuilt the public interactor data, provisional evidence profiles, and interaction network from the corrected source placements. Shared findings used by other pairs were preserved.
- Withheld all coefficients from the older HPA CPTAC association analysis because it used an incorrect value column. The other seven HPA protein-profile datasets remain exploratory associations. The corrected CPTAC analysis remains outside this public release.
- Retained the reviewed co-chaperone network and interactive HSP90-cycle evidence at their prior source horizons. No new client call or final evidence ranking was made.

## v6.303-atlas.1-rc1 cycle-machinery backtrace release - 2026-09-23

- Reconciled the 38-gene HSP90-cycle machinery scope against current BioGRID, IntAct, BioPlex, CORUM, Complex Portal, HPRD, and hu.MAP snapshots, retaining 115 missing focal machinery pairs as source-review candidates rather than automatic interactions.
- Completed thirteen source-specific PIH1D1–RUVBL1/2 reviews across purified R2TP structure, TAP-MS, BioPlex 1.0/2.0/3.0, OpenCell, and a dedicated ZNHIT2/R2TP study.
- Added thirteen source-adjudicated non-client machinery edges to the cycle model: ten cycle-detail relationships and three optional neighborhood-context relationships. No new nodes were required.
- Preserved the directness boundary for PIH1D1–RUVBL1/2 as structural-complex co-membership with replicated cellular co-recovery, not resolved direct binary contact.
- Kept DNAJB11–HSPA1A excluded because the cited evidence did not resolve the Hsp72-family signal to the exact HSPA1A gene.
- Advanced the public Atlas, cycle explorer, downloads, citation, and release metadata together under the v6.303 release identifier.

## v6.301-atlas.1-rc1 BioPlex interaction-map source review - 2026-09-22

- Reviewed 59 queued co-chaperone neighborhood pairs from PMID 26186194 against the native Supplementary Table 9 interaction workbook and article methods.
- Added 59 source-specific findings across 57 newly reviewed pairs and two pairs with prior source reviews; the companion now contains 457 findings across 351 reviewed pairs and 72 primary sources.
- Preserved the source table's collapsed, undirected pair semantics: every retained association meets the study's CompPASS-Plus high-confidence threshold, but remains co-purification or shared-complex evidence rather than direct binding, HSP90 dependence, client status, or isoform specificity.
- Reconciled eight source-era gene aliases by exact Entrez Gene and UniProt identifiers; retained all 59 pairs in the queue because each has additional publications awaiting review.
- Advanced the public Atlas, private cycle shell, downloads, and release metadata together under the v6.301 release identifier.

## v6.300-atlas.1-rc1 MAC-tag source review - 2026-09-22

- Reviewed nine co-chaperone neighborhood pairs from PMID 29568061 against the native Supplementary Data 1 workbook, preserving AP-MS co-complex and BioID proximity evidence as distinct assay contexts.
- Added 9 source-specific findings across 8 newly reviewed pairs and one already-reviewed pair; the companion now contains 398 findings across 294 reviewed pairs and 72 primary sources.
- Closed three source-complete pairs and retained six pairs for additional-publication review; row-level BFDR 0.08-0.09 signals remain explicitly threshold-edge and contribute no production score.
- Added PMID 22863883 Supplementary Tables 1-4 to the manual retrieval handoff after a provenance audit found that only its article and supplementary figures are local.
- Advanced the public Atlas, private cycle shell, downloads, and release metadata together under the v6.300 release identifier.

## v6.299-atlas.1-rc1 DUB-landscape source review - 2026-09-22

- Reviewed PMID 19615732 from the main article and complete publisher supplement package, including the claim-bearing DUB-bait and reciprocal HCIP-bait AP-MS matrices.
- Added eight context-qualified cellular association findings across seven newly reviewed pairs; five single-source pairs are now source-review complete and three remain open for additional publications.
- Advanced the co-chaperone companion to 389 source-specific findings across 286 reviewed pairs and 71 primary sources, with 1,892 pairs remaining in the review queue.
- Kept every new association at zero production-score contribution and preserved the boundaries against direct-binding, HSP90-dependence, isoform-specificity, and client-status inference.
- Advanced the public Atlas, private cycle shell, downloads, and release metadata together under the v6.299 release identifier.

## v6.298-atlas.1-rc1 harmonized release - 2026-09-22

- Unified the public Atlas, private cycle shell, downloads, and release metadata under one v6.298 user-facing release identifier.
- Advanced the separately bounded co-chaperone network to 381 source-specific findings across 279 reviewed pairs and 70 primary sources.
- Preserved the 5,092 HSP90 gene–isoform relationships and 3,922 reviewed source–gene findings from the v6.254 core evidence horizon; the version change does not manufacture new core relationships.
- Added a machine-checked release contract so future public and cycle builds fail validation if their current-release identifiers diverge.
- Retained older component horizons as provenance in manifests rather than presenting them as competing current releases.

## v6.292-atlas.1-rc1 public evidence refresh - 2026-09-14

- Updated the public HSP90 gene–isoform browser to the cumulative v6.254 source-gene boundary: 5,092 relationships, 3,922 reviewed source–gene findings, 2,699 supported relationships, and eight reviewed exclusion-only relationships.
- Added structured experimental-system, organism, evidence-origin, cellular-compartment, perturbation, and evidence-basis fields to the public source records and filters.
- Added a separate sanitized v6.292 co-chaperone-network download containing 348 source-specific findings across 259 reviewed pairs and 70 primary sources.
- Preserved the biological boundary between HSP90 isoform–gene evidence and co-chaperone–partner evidence; the latter is not recast as client or isoform-specific evidence.
- Carried forward the validated v6.109 HPA and BioGRID/IntAct analytical profiles over their original v6.104 pair universe, with the coverage boundary stated explicitly.
- Rebuilt the source-backed network and comparison profiles from the refreshed public core without authorizing a final score, rank, pathway interpretation, or scored reference set.
- Left the private interactive HSP90-cycle explorer data and design unchanged for its next dedicated revision.

## App 0.11.0 public-language and repository-readiness update - 2026-08-24

- Replaced internal queue, version, reviewer, and triage language in visitor-facing summaries, limitations, and experimental-context fields with concise scientific descriptions.
- Reorganized gene-page source records into reader-facing states: source reviewed, evidence unclear, or source does not support the relationship.
- Improved the mobile paper browser with larger isoform controls, a horizontal source selector, and one full-width source-detail panel.
- Added an automated public-language check across all 1,407 displayed source assertions while preserving the underlying curation records and identifiers.
- Added private-GitHub continuous validation and documented a staged move to durable GitHub-connected hosting.
- Kept the frozen v6.104 scientific dataset, non-comprehensive coverage status, and exploratory-analysis boundaries unchanged.

## App 0.10.0 visitor information architecture - 2026-07-22

- Replaced the statistic-heavy overview with a searchable four-isoform homepage and one exact relationship-coverage bar.
- Consolidated Methods and coverage documentation under About with standardized count terminology.
- Reorganized Downloads around a core release ZIP, common tables, GraphML, and expandable analytical/audit groups.
- Added shareable Interactor filters plus network edge previews, focus mode, label controls, and PNG export.
- Kept the frozen v6.104 scientific dataset, exploratory-analysis boundaries, and non-comprehensive coverage status unchanged.

## App 0.7.1 database-source reconciliation repair - 2026-07-15

- Rebuilt the analytical sidecar after restricting publication IDs to true PubMed identifiers; DOI suffixes and MINT/IMEx record numbers no longer appear as PMIDs.
- Added downloadable decisions for 444 reviewed database-to-paper routes and admission-priority triage for all 2,640 database-only pairs outside the master universe.
- Kept the frozen v6.104 source-gene assertions unchanged. Route-review and triage tables do not automatically admit pairs, create client calls, or contribute score points.

## App 0.7.0 full analytical profiles and direct database reconciliation - 2026-07-15

- Added a separately validated v6.107 analytical sidecar without changing the frozen v6.104 evidence contract.
- Exposed 28,107 HPA 25.1 protein/IHC dataset-level correlation rows across 4,177 current master pairs, including adjusted q values, context counts, directions, and source links.
- Added 7,665 direct BioGRID 5.0.259 and IntAct-current records; 3,962 map to 1,377 current master pairs, while 2,640 outside-master pairs remain downloadable audit/triage leads.
- Reconciled database-cited PMIDs against same-gene/same-isoform source review and made same-pair-reviewed, reviewed-elsewhere, unreviewed, and no-PMID states visible.
- Replaced the compact analytical summary with a fixed-height isoform master-detail workbench and internal HPA/database scrolling.

All analytical fields remain exploratory context with zero evidence-score contribution. No database row or correlation creates a reviewed assertion, interaction/client call, final score, pathway interpretation, or promoted reference set.

## App 0.6.0 evidence workbench and analytical associations - 2026-07-15

- Replaced the expanding gene-page evidence-card archive with a fixed-height review workbench: a compact, isoform-filterable source list on the left and one complete selected assertion on the right.
- Added a separate per-isoform analytical-association table for HPA protein/IHC correlation summaries, PPI database resources, and PubMed co-mention counts.
- Explicitly labels analytical associations as source-review leads that contribute no evidence-score points and do not establish interaction, binding, or client dependence.
- Replaced 20 known Europe PMC navigation captures in public claim summaries with conservative audit notices while preserving the raw curated source TSV and flagging each public presentation cleanup.

Scientific guardrails remain unchanged: the app does not promote analytical associations into reviewed evidence, final scores, client calls, pathway interpretation, or scored reference sets.

## App 0.5.1 network hover-preview usability patch - 2026-07-15

- Added mouse-hover previews for every visible gene and isoform-hub node in the Analysis Lab network.
- Gene previews show implicated isoforms, the best provisional evidence profile, shown edge count, article-key links, strict/support/recheck assertion counts, and relationship classes before selection.
- Cards flip above or below the node according to its visible browser-window position and clamp horizontally within the network canvas.
- Click-to-inspect behavior and the keyboard-accessible edge selector remain unchanged.

Scientific guardrails remain unchanged: hover summaries reflect the same integrated source-gene assertions already available in the selected-evidence panel; they do not add discovery-only evidence, final scores, client calls, or pathway interpretation.

## App 0.5.0 release-gate validation tranche - 2026-07-15

- Reconciled the frozen 100-pair network sample against all integrated Atlas assertions: 100 passed, with no unresolved audit failures.
- Made mixed assertion profiles explicit: strict, support, and recheck counts are shown separately, while relationship labels and provisional profiles disclose that they summarize all positive reviewed assertions.
- Added a keyboard-accessible edge selector and retained the Cytoscape canvas as a visual exploration surface.
- Fixed shared text-contrast, compact-navigation naming, ARIA-role, and narrow-layout failures; eight representative routes now report zero automated axe violation or incomplete groups.
- Added a synthetic 250-node/500-edge CoSE performance benchmark; median 1,743.96 ms and p95 1,784.74 ms passed the provisional thresholds.

Scientific and human guardrails:

- The curator pass reconciled Atlas assertions and UI provenance; it was not a new primary-paper rereview or independent second-curator review.
- Five external usability sessions, manual accessibility review, and independent curator review remain pending.
- No pathway interpretation, final score, final rank, confidence tier, client call, or scored-reference-set promotion was created.

## App 0.4.0 sensitivity and audit tranche - 2026-07-14

- Added three explicit ORA background universes for every isoform and evidence preset, expanding the private preview from 8 to 24 profiles.
- Added balanced, mechanism-forward, provenance-forward, and caveat-stress score lenses with within-isoform rank and delta reporting.
- Added a deterministic 100-edge curator queue: 25 rows per isoform with strict, support-only, and recheck-only strata.
- Added a five-participant structured usability protocol and blank session log; no human results are claimed.
- Added shareable Analysis Lab control state for isoform, preset, gene query, recheck visibility, background, score lens, and edge limit.

Scientific guardrails:

- Background and weight differences are sensitivity warnings, not biological findings.
- Human usability and curator fields remain pending.
- No pathway interpretation, final score, final rank, confidence tier, client call, or scored-reference-set promotion was created.

## App 0.3.0 private usability lab - 2026-07-14

- Added an owner-only Analysis Lab with bounded, assertion-backed HSP90 isoform-gene networks.
- Added a Reactome V97 over-representation preview with versioned pathway data, a review-universe background, one-sided hypergeometric testing, and Benjamini-Hochberg correction.
- Added transparent provisional evidence profiles that keep physical interaction, complex membership, client mechanism, chaperone-cycle role, perturbation, isoform specificity, source quality, corroboration, and caveat penalties separate.
- Added deterministic lab-sidecar build/validation and standard, compact, and wide browser checks.

Scientific guardrails:

- The lab is private usability testing, not part of the frozen core data release.
- Coverage remains non-comprehensive and the ORA universe is discovery-biased.
- No pathway interpretation, final score, final rank, confidence tier, or scored-reference-set promotion was created.
- Database/PPI, HPA, and PubMed discovery context cannot create network edges or contribute score points.

## v6.104-atlas.1-rc1 - 2026-07-14

- Frozen source checkpoint: v6.104.
- Added 4,325 isoform-gene browse rows and 1,407 source-gene assertions.
- Preserved 1,174 positive/source-supported pairs and 6 reviewed exclusion-only pairs as distinct states.
- Added stable gene evidence URLs and four-isoform comparison views.
- Added filtered evidence-table and gene-level TSV exports.
- Added release-candidate citation and license-decision scaffolding.
- Added a deterministic 80-page curator spot-check queue and automated preflight validation.

Scientific guardrails:

- Coverage remains non-comprehensive.
- Database/PPI, HPA, and PubMed co-mention observations remain discovery context.
- No ORA, pathway enrichment, pathway interpretation, final scoring, or scored-reference-set promotion is included.
