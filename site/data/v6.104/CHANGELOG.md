# HSP90 Atlas release-candidate changelog

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
