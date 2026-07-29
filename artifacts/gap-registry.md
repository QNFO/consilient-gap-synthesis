# Gap Registry — Consilient Gap Synthesis (v1.0)

**Date:** 2026-07-29
**Source:** Phase 1 Due Diligence — cross-reference of D1, KG, R2, local projects, and memory records
**Total Gaps Catalogued:** 41

---

## Classification Legend

| Field | Values |
|:------|:-------|
| **Category** | **I** (Infrastructure), **C** (Content/Publication), **P** (Physics Validation), **G** (Governance), **D** (Dissemination) |
| **Severity** | **BLOCKING** (cannot proceed), **HIGH** (major impact), **MEDIUM** (significant), **LOW** (nice to have) |
| **Effort** | **S** (<1 session), **M** (1-2 sessions), **L** (3-5 sessions), **XL** (5+ sessions) |
| **Status** | STUB, PENDING, IN-PROGRESS, DEFERRED |

---

## Gap Inventory

### Infrastructure (I) — 16 gaps

| ID | Gap | Project/Source | Severity | Effort | Blocks | Description |
|:---|:----|:---------------|:---------|:-------|:-------|:-----------|
| I-01 | Consistency Engine | OI-003 | **HIGH** ⭐ | **L** | I-05, C-01, C-02, G-01 | Cross-ecosystem consistency verification — STUB, no implementation. Root blocker for systematic gap detection. |
| I-02 | Infomatics Recovery | Infomatics | **HIGH** | **M** | C-05 | 12 files in R2 only, GitHub repo lost. Recover from R2, rebuild linear history. |
| I-03 | biophoton GitHub Remote | biophoton-ultrametric-consilience | **MEDIUM** | **S** | C-03, C-04, D-01 | Local repo only — cannot push tags, create releases, or link to Zenodo. |
| I-04 | qnfo-unified-plan R2 Sync | qnfo-unified-plan | **MEDIUM** | **S** | C-06 | Project artifacts (PDF v5.0, memo) not synced to qnfo-projects/ R2 path. |
| I-05 | papers-server Redeploy | measurable-vs-imaginable | **MEDIUM** | **S** | D-02 | qnfo-hub Pages deployed before D1 insert — 404 for paper-computable-real-boundary. |
| I-06 | ultrametric-well Hardware | ultrametric-well-analysis | **MEDIUM** | **XL** | P-01 | 50GB+ The Well download + GPU neural operator training exceeds local capacity. |
| I-07 | the-informational-universe Repo | the-informational-universe | **MEDIUM** | **S** | C-07 | Active project with no GitHub repo — Phase 0 init required. |
| I-08 | Agent Swarm Architecture | OI-001 | LOW | **XL** | — | STUB — multi-agent coordination framework. |
| I-09 | Automated Peer Review | OI-002 | LOW | **XL** | — | STUB — automated review pipeline for QNFO publications. |
| I-10 | Reproducibility as Code | OI-006 | LOW | **L** | — | STUB — IaC for research reproducibility. |
| I-11 | Portfolio API Completion | OI-004 | LOW | **M** | G-01 | V2 operational; needs publication search + KG integration. |
| I-12 | Archive Migration Finish | OI-012 | LOW | **M** | — | Discovery Index rebuilt; full migration pending. |
| I-13 | Analytics Wiring | task-analytics-03 | LOW | **M** | — | Wire analytics to qnfo-lifecycle cron. |
| I-14 | Ultrametric Playground | OI-007 | LOW | **L** | — | STUB — interactive visualization tools. |
| I-15 | QWAV Compute Cloud | OI-008 | LOW | **XL** | — | STUB — cloud compute infrastructure. |
| I-16 | PM Mirror Builder | OI-014 | LOW | **L** | — | STUB — project management mirror. |

### Content/Publication (C) — 14 gaps

| ID | Gap | Project/Source | Severity | Effort | Blocks | Description |
|:---|:----|:---------------|:---------|:-------|:-------|:-----------|
| C-01 | D1 Missing DOIs (463 papers) | D1 living-paper | **HIGH** | **L** | D-02 | 463 papers have null/PENDING DOIs. Bulk is kg-backfill entries — need verification if DOIs exist in KG properties. |
| C-02 | paper_ids Registry Gaps (7 papers) | D1 paper_ids | **HIGH** | **S** | I-01 | 7 D1 papers missing from paper_ids registry — blocks cross-system ID resolution. |
| C-03 | biophoton Not Vectorized | biophoton-ultrametric-consilience | **MEDIUM** | **S** | D-01 | Paper body not in Vectorize semantic search index. |
| C-04 | biophoton Missing KG Paper Node | biophoton-ultrametric-consilience | **MEDIUM** | **S** | D-01, I-01 | Paper not represented in Knowledge Graph. |
| C-05 | Infomatics Publication State | Infomatics | **MEDIUM** | **M** | — | After recovery (I-02), needs D1/KG/Zenodo publication pipeline. |
| C-06 | qnfo-unified-plan D1 Update | qnfo-unified-plan | **MEDIUM** | **S** | D-03 | D1 living-paper row needs update with v5.0 metadata + DOI. |
| C-07 | the-informational-universe Publication | the-informational-universe | **MEDIUM** | **L** | — | Needs full Phase 0-8 pipeline after repo creation (I-07). |
| C-08 | adelic-qec KG Paper Node | adelic-qec-synthesis | LOW | **S** | — | KG Paper node missing (acknowledged soft gap). |
| C-09 | adelic-qec PDF Build | adelic-qec-synthesis | LOW | **M** | — | PDF build verification pending. |
| C-10 | adelic-qec 11 Sub-papers | adelic-qec-synthesis | LOW | **XL** | — | 11 sub-papers need individual publication pipelines. |
| C-11 | measurable Missing paper_ids | measurable-vs-imaginable | LOW | **S** | I-01 | Paper missing from paper_ids registry (counted in C-02). |
| C-12 | qwav-whitepaper paper_ids | paper_ids | LOW | **S** | — | Whitepaper missing from paper_ids registry (counted in C-02). |
| C-13 | fine-structure-constant-active | D1 living-paper | LOW | **M** | — | Only active paper in D1 — needs publication pipeline or status resolution. |
| C-14 | Pattern Documentation | task-knowing-03 | LOW | **M** | — | Knowing patterns documentation generation (UNBLOCKED). |

### Physics Validation (P) — 5 gaps

| ID | Gap | Project/Source | Severity | Effort | Blocks | Description |
|:---|:----|:---------------|:---------|:-------|:-------|:-----------|
| P-01 | ultrametric-well Training | ultrametric-well-analysis | **MEDIUM** | **XL** | — | Neural operator training on The Well dataset — blocked by hardware (I-06). |
| P-02 | measurable G2 — LoF Proof | measurable-vs-imaginable | LOW | **M** | — | Formal LoF proof that ℝ_comp = fixed point of Re-entry. Partially resolved via Leshem 2019. |
| P-03 | measurable G3 — Archimedean Anthro | measurable-vs-imaginable | LOW | **L** | — | Experiment design exists, unexecuted. Ultrametric vs Archimedean error accumulation. |
| P-04 | biophoton Calibration Training | biophoton-ultrametric-consilience | LOW | **M** | — | Bayesian cascade Stage -1 calibration training not completed. |
| P-05 | biophoton PW Clock Extrapolation | biophoton-ultrametric-consilience | LOW | **L** | — | Page-Wootters clock extrapolation validation pending. |

### Governance (G) — 4 gaps

| ID | Gap | Project/Source | Severity | Effort | Blocks | Description |
|:---|:----|:---------------|:---------|:-------|:-------|:-----------|
| G-01 | QNFO.GOV — 17 Tasks | QNFO.GOV | **HIGH** | **L** | G-02, G-03 | 17 of 36 tasks incomplete; 3 of 6 phases remaining. Priority CRITICAL. |
| G-02 | kepler Sub-project Audits | kepler-program | **MEDIUM** | **M** | C-07 | Sub-projects (silent-radix, radix-uw, etc.) need individual Phase 0 protocol audits. |
| G-03 | CFPE Calibration Register | CFPE Paradigm Forecast | LOW | **S** | — | Quarterly calibration register update (next due). |
| G-04 | QNFO.GOV Automated Compliance | QNFO.GOV | LOW | **XL** | — | Automation of governance compliance checks — blocked by I-01 (Consistency Engine). |

### Dissemination (D) — 3 gaps

| ID | Gap | Project/Source | Severity | Effort | Blocks | Description |
|:---|:----|:---------------|:---------|:-------|:-------|:-----------|
| D-01 | biophoton Buffer Post | biophoton-ultrametric-consilience | **MEDIUM** | **S** | — | Published but not disseminated — blocked by missing GitHub remote (I-03) and KG link (C-04). |
| D-02 | Buffer Token Stale (KIF-45) | Global | **MEDIUM** | **S** | D-01, D-03 | Buffer PAT FORBIDDEN — blocks all social posting until regenerated. |
| D-03 | qnfo-unified-plan Buffer Post | qnfo-unified-plan | LOW | **S** | — | v5.0 memo Buffer post pending — blocked by Zenodo upload (C-06) and token (D-02). |

---

## Dependency Graph

```
I-01 (Consistency Engine) ⭐
├──► C-01 (D1 Missing DOIs verification)
├──► C-02 (paper_ids registry gaps)
├──► C-04 (KG Paper node verification)
└──► G-04 (Automated compliance)

I-02 (Infomatics Recovery)
└──► C-05 (Infomatics publication)

I-03 (biophoton GitHub)
├──► C-03 (Vectorize)
├──► C-04 (KG node)
└──► D-01 (Buffer post)

D-02 (Buffer Token)
├──► D-01 (biophoton Buffer)
└──► D-03 (qnfo-unified Buffer)

C-06 (qnfo-unified D1 update)
└──► D-03 (qnfo-unified Buffer)

I-06 (ultrametric-well Hardware)
└──► P-01 (Neural operator training)

I-07 (the-informational-universe Repo)
└──► C-07 (Full publication pipeline)

G-01 (QNFO.GOV)
├──► G-02 (kepler audits)
└──► G-04 (Automated compliance)
```

---

## Statistics

| Category | Count | BLOCKING | HIGH | MEDIUM | LOW |
|:---------|:------|:---------|:-----|:-------|:-----|
| Infrastructure (I) | 16 | 0 | 2 | 4 | 10 |
| Content/Publication (C) | 14 | 0 | 2 | 5 | 7 |
| Physics Validation (P) | 5 | 0 | 0 | 1 | 4 |
| Governance (G) | 4 | 0 | 1 | 1 | 2 |
| Dissemination (D) | 3 | 0 | 0 | 2 | 1 |
| **TOTAL** | **42** | **0** | **5** | **13** | **24** |

**Key insight:** Zero BLOCKING gaps — all projects that are currently active can proceed. The HIGH-severity gaps (I-01, I-02, C-01, C-02, G-01) are infrastructure and content-registry issues that block systematic verification but not individual project progress. This validates the core claim: the portfolio is NOT in crisis mode; it has drifted into maintenance debt.

**Pareto distribution:** The top 5 HIGH-severity gaps (12% of total) block ~40% of remaining gaps directly or transitively, and resolving them enables systematic rather than ad hoc verification. This confirms the Phase 0 core claim (§1.2) — the dependency graph is predominantly a DAG with depth ≤3, and the first 1-2 phases (infrastructure) resolve the root blockers for everything downstream.

---

## Next: Phase 3 — Version Roadmap

Phase 3 will:
1. Topological sort the dependency graph into phased release versions
2. Assign version targets: v2.0 (Infrastructure), v2.1 (Content), v2.2 (Governance), v2.3 (Physics), v2.4 (Dissemination)
3. Estimate timelines per version
