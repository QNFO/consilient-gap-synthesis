# RESEARCH-CONTINUITY-REGISTRY.md

**Purpose:** Central, machine-readable location for weaving together all QNFO research findings to determine continuing research direction. This is the canonical follow-up surface for every research session — next actions, open questions, predictions/falsifications, and pre-registrations.

**Maintainer:** Any research session touching QNFO publications MUST append/update entries here (Phase Closeout Protocol).
**Version:** 1.0 (2026-07-31)
**Repo:** QNFO/consilient-gap-synthesis (this file)

---

## 1. Next Actions (Prioritized)

| # | Action | Project | Priority | Blocked By | Status | Est. |
|:--|:-------|:--------|:---------|:-----------|:-------|:-----|
| NA-01 | Redeploy `qnfo-hub` Pages from Cloudflare Dashboard (fixes papers.qnfo.org 404 for all papers inserted after last deploy) | infra | 🔴 CRITICAL | User (Dashboard) | BLOCKED | 5 min |
| NA-02 | Audit 463 NULL-DOI papers vs KG properties (C-01) | D1 | 🔴 HIGH | — | PENDING | 2-3 sessions |
| NA-03 | Execute top QNFO.GOV tasks (G-01, 17 tasks) | governance | 🟠 HIGH | — | PENDING | 3-5 sessions |
| NA-04 | Vectorize biophoton paper body (C-03) + create KG Paper node (C-04) | biophoton | 🟠 MEDIUM | — | PENDING | <1 session |
| NA-05 | Infomatics recovery: locate 12 R2 files or reconstruct from Zenodo README (I-02) | infomatics | 🟠 HIGH | Unknown R2 bucket | INVESTIGATED | 1-2 sessions |
| NA-06 | Rebuild KG-D1 bidirectional sync (C-01 root cause) | infra | 🟠 HIGH | NA-02 | PENDING | 3-5 sessions |
| NA-07 | Verify QWAV v2.3 dissemination (Buffer posts) | qwav | 🟢 LOW | Buffer queue | PENDING | <1 session |
| NA-08 | Seed D1 calibration register table with all predictions below (machine-readable) | infra | 🟢 MEDIUM | — | PENDING | 1 session |
| NA-09 | First annual calibration-register audit (check predictions due) | all | 🟢 MEDIUM | — | PENDING | 2027-01 |
| NA-10 | Pre-register next research direction (see §4) | — | 🟢 LOW | User decision | PENDING | — |

---

## 2. Open Questions

| # | Question | Source | Domain | Status |
|:--|:---------|:-------|:-------|:-------|
| OQ-01 | Can a substrate shift be predicted before constraint saturation forces it? (consilience frontier question) | computing-machines | Physics/CS | OPEN |
| OQ-02 | Is the 610-node KG-D1 delta caused by schema mismatch or missing sync job? | audit | Infra | OPEN |
| OQ-03 | Do the 463 NULL-DOI papers have DOIs stored in KG properties that were never propagated to D1? | audit | Data | OPEN |
| OQ-04 | Where are the 12 Infomatics files? (R2 bucket unknown, Zenodo has README only) | audit | Infra | OPEN |
| OQ-05 | Does QWAV's geometry-as-error-correction thesis survive the 2030-2040 falsification timeline? | qwav | Physics | OPEN (testable) |
| OQ-06 | Which of the 7 post-silicon candidates will be first to a commercial inflection? | computing-machines | CS | OPEN |

---

## 3. Predictions & Falsification Register (CHECK-REGISTER)

All dated, falsifiable predictions across QNFO papers. Audit annually (January). Update status → CONFIRMED / DISCONFIRMED / PENDING.

### 3.1 computing-machines (DOI 10.5281/zenodo.21713202) — 12 predictions

| Check Year | Prediction | Strength | Anchor | Status |
|:-----------|:-----------|:---------|:-------|:-------|
| 2030 | AI accelerators >50% datacenter compute spending | STRONG | Empirical base rate | PENDING |
| 2032 | Quantum advantage on non-contrived problem | STRONG | Reference class | PENDING |
| 2032 | Hardware-agnostic AI training frameworks | WEAK | Calibrated subjective | PENDING |
| 2032 | G7-mandated post-quantum cryptography migration | STRONG | Reference class | PENDING |
| 2033 | $100M+ quantum optimization savings documented | WEAK | Calibrated subjective | PENDING |
| 2035 | CMOS scaling effectively ended | STRONG | Empirical base rate | PENDING |
| 2035 | Material discovered primarily via quantum simulation | STRONG | Calibrated subjective | PENDING |
| 2035 | Datacenter 10× throughput at <2× energy | STRONG | Koomey's law | PENDING |
| 2038 | Post-von Neumann architecture >1% market share | WEAK | Calibrated subjective | PENDING |
| 2040 | 100× improvement in operations/joule | STRONG | Empirical base rate | PENDING |
| 2040 | Reversible computing 100× efficiency demo | WEAK | Calibrated subjective | PENDING |
| 2040 | Drug candidate identified via quantum simulation | STRONG | Calibrated subjective | PENDING |

### 3.2 consilient-gap-synthesis (DOI 10.5281/zenodo.21711000) — 5 predictions

| Check Year | Prediction | Strength | Status |
|:-----------|:-----------|:---------|:-------|
| 2026-10-01 | KG-D1 delta shrinks from 610 to ≤200 nodes with focused effort | STRONG | PENDING |
| 2026-10-01 | ≥15 of 30 NULL-DOI papers get Zenodo DOIs | STRONG | PENDING |
| 2026-12-31 | Lifecycle Worker /status → HTTP 200 + automated monitoring | WEAK | PENDING |
| 2026-12-31 | Cross-layer 4-D verification executable in ≤60s | WEAK | PENDING |
| 2027-06-30 | Gap registry shrinks from 42 to ≤20 active gaps | STRONG | PENDING |

### 3.3 Falsification conditions (paper-level)

| Paper | Falsification condition | Status |
|:------|:------------------------|:-------|
| consilient-gap-synthesis | Classification fails to converge to 5 categories; dependency graph shows a cycle; Phase 1-2 resolves <40% of transitively blocked gaps | PENDING |
| computing-machines | CMOS scaling does not effectively end by 2035; AI accelerators <50% of datacenter spend by 2030 | PENDING |

---

## 4. Registries & Pre-registrations

| # | Item | Type | Status | Link |
|:--|:-----|:-----|:-------|:-----|
| REG-01 | OSF preregistration for next major research program | Pre-registration | NOT-CREATED | — |
| REG-02 | QNFO.GOV unified data governance framework (3/6 phases) | Governance registry | IN-PROGRESS | qnfo.org |
| REG-03 | paper_ids registry (925 entries) | ID registry | ACTIVE | D1 living-paper |
| REG-04 | Calibration training Brier score log (0.12, research skill KIF-31) | Calibration log | ACTIVE | research skill |
| REG-05 | Candidate pre-registration: "substrate-shift predictability" (OQ-01) | Pre-registration | PROPOSED | §2/OQ-01 |

**Pre-registration protocol:** Before launching any new research program, create a dated pre-registration entry here with hypothesis, falsification condition, and check date — then execute. This satisfies the user's requirement for central registry/pre-registration tracking.

---

## 5. Session Closeout Checklist (MANDATORY for every research session)

- [ ] Updated §1 Next Actions (add new, mark completed)
- [ ] Updated §2 Open Questions (resolve or refine)
- [ ] Updated §3 Predictions (new predictions from this session's forecast protocols)
- [ ] Updated §4 Registries (pre-registrations created/advanced)
- [ ] Committed + pushed to QNFO/consilient-gap-synthesis
- [ ] Logged memory with pointer to this registry

---

## 6. How This Weaves With KG + Papers DB

- **KG:** Every prediction (§3) and open question (§2) SHOULD have a corresponding KG node (label: `Prediction` / `OpenQuestion`) for topological discovery. Use `remember_fact` (category: heuristic/task_outcome) to auto-create KG nodes.
- **Papers DB (D1):** Every paper's DOI resolves via paper_ids. This registry is keyed by DOI so any session can jump from registry → paper → full forecast protocol artifact.
- **Next session start:** Read this file FIRST, then check §1 for NA-01..NA-10 priorities, then continue.
