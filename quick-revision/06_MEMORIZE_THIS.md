# 06 — MEMORIZE THIS (facts you must know cold)

---

## A. NUMBERED LISTS (with mnemonics)

### 5 CMM levels — mnemonic: **"I Really Don't Manage Overtime"**
1. **I**nitial — chaotic, individual effort, not repeatable
2. **R**epeatable — basic project management
3. **D**efined — own standard process
4. **M**anaged — data collection & analysis
5. **O**ptimizing — continuous improvement + innovation

### 5 TMM levels — mnemonic: **"I Prefer Increasingly Mature Orgs"**
1. **I**nitial — testing after code, ad hoc, no tracking
2. **P**hase Definition — testing/debugging goals, initiate test planning
3. **I**ntegration — establish test group, integrate testing into lifecycle
4. **M**anagement and Measurement — org-wide review, test management, evaluate quality
5. **O**ptimization / Defect Prevention & QC — defect prevention, statistical QC, optimization

### 7 Principles of Testing — mnemonic: **"Please Eat Every Delicious Pizza Carefully, Alright"**
1. **P**resence of defects (not absence)
2. **E**xhaustive testing is impossible
3. **E**arly testing
4. **D**efect clustering
5. **P**esticide paradox
6. **C**ontext dependent
7. **A**bsence-of-errors fallacy

### 6 ISO-9126 characteristics — mnemonic: **"Fat Rabbits Usually Eat More Peas"**
**F**unctionality · **R**eliability · **U**sability · **E**fficiency · **M**aintainability · **P**ortability
*(Security is NOT one of them.)*

### 5 Views of quality (Kitchenham & Pfleeger) — mnemonic: **"My Uncle Makes Pretty Vases"**
**M**ystical · **U**ser · **M**anufacturing · **P**roduct · **V**alue-based

### 3 QA categories — mnemonic: **"Prevent, Reduce, Contain" (PRC)**
**P**revention (before injection) · **R**eduction (remove faults) · **C**ontainment (limit failures)

### 4 Testing levels + who — mnemonic: **"U-I-S-A: Devs Test Test Users"**
**U**nit → Developer · **I**ntegration → Tester · **S**ystem → Tester · **A**cceptance → End-user

### 3 SqE stages — mnemonic: **"PED"**
**P**lanning · **E**xecution · **D**ecision
*(SQE generic testing process phases: **Pre-QA → In-QA → Post-QA**.)*

### Other short lists to keep
- **2 ways of defect prevention:** error source removal · error blocking
- **2 ways of defect containment:** software fault-tolerance (NVP, recovery) · safety assurance
- **3 testing team models:** Vertical · Horizontal · Mixed
- **3 project challenges:** Time · Cost · Scope
- **3 reasons to improve a process:** Quality · Lead Time · Cost
- **4 TPI improvement steps:** determine area → evaluate current → identify next → implement
- **4 process variations:** Waterfall · Iterative · Spiral · Agile (+ Maintenance)

---

## B. NAMED PEOPLE / MODELS

| Name / Model | What it is / who |
|---|---|
| **McCall** | Quality **Factors and Criteria** model |
| **Kitchenham & Pfleeger** | The **five views** of software quality |
| **Ilene Burnstein** | Pioneered the **TMM** (Testing Maturity Model) |
| **ISO-9126** | Most influential quality **framework** — 6 characteristics |
| **CMM** | Capability Maturity Model — evaluates **development** process (5 levels) |
| **TMM** | Testing Maturity Model — evaluates **testing** process (5 levels) |
| **TPI** | Test Process Improvement — **improves** the testing process (4 steps) |
| **ISO 9001** | Standard based on the **manufacturing** view (with CMM) |
| **Naik & Tripathy / Jeff Tian** | The two course textbook authors |

---

## C. FAMOUS INCIDENTS

| Incident | What happened |
|---|---|
| **Therac-25** | Radiation-therapy machine by **AECL (1986)**; a **software bug** caused massive radiation **overdoses** and deaths. |
| **Ariane 5** | On **4 June 1996**, the rocket **tore itself apart 37 seconds** after launch due to a **control-software** malfunction — the **most expensive computer bug in history**. |

---

## D. EVERY "HOW MANY" FACT

| Question | Answer |
|---|---|
| CMM levels | **5** |
| TMM levels | **5** |
| Principles of testing | **7** |
| ISO-9126 top-level characteristics | **6** |
| Views of quality (Kitchenham & Pfleeger) | **5** |
| QA categories | **3** |
| Testing levels | **4** |
| SqE stages | **3** |
| Generic testing-process phases | **3** (Pre/In/Post-QA) |
| Ways to do defect prevention | **2** |
| Ways to do defect containment | **2** |
| Testing team models | **3** |
| TPI improvement steps | **4** |
| Software types (Buy/Build) | **2** |
| Project challenges | **3** |
| Ariane 5 seconds to failure | **37** |

---

## E. ONE-LINE DEFINITIONS TO NAIL

- **Error** = human action producing an incorrect result.
- **Fault** = incorrect step/process/data definition in a program.
- **Failure** = inability of a system to perform its required function.
- **Defect** = behavioural deviation from spec (umbrella term = "bug").
- **Reliability** = probability of executing without failure for a specific period of time.
- **Safety** = accident-free. **Accident** = failure with severe consequences. **Hazard** = pre-condition to an accident.
- **Test plan** = high-level; **Test case** = low-level; **Test suite** = collection run until stopping criteria.
- **Regression testing** = reuse existing tests (design none) to check nothing broke.
- **White-box** = structural/implementation; **Black-box** = functional/specification; **Gray-box** = mixed.
- **SQA** = prevent, no execution, verification; **SQC** = detect, executes, validation.
