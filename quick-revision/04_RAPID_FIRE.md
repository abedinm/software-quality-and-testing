# 04 — RAPID FIRE (100 Q&A)

Cover the question, say the answer, then check. Morning-before-exam drill.

## Chapter 1 — Basics of SQA

**1.** Two major types of software?
— Generic (Buy) and Customized (Build).

**2.** What does COTS stand for?
— Commercial off-the-shelf.

**3.** "Bespoke" software is which type?
— Customized (Build).

**4.** Software is composed of what?
— Programs, procedures, documentation, and data.

**5.** Software quality per ISO/IEC 9126?
— Totality of functionality and features that satisfy stated or implied needs.

**6.** Software quality per IEEE Std 610?
— Degree to which a system/component/process meets specified requirements and user needs.

**7.** Three main project challenges?
— Time, Cost, Scope.

**8.** What was Therac-25?
— A radiation-therapy machine (1986) that overdosed patients due to a software bug.

**9.** Which company built Therac-25?
— AECL (Atomic Energy of Canada Ltd).

**10.** When did Ariane 5 fail, and how long after launch?
— 4 June 1996, 37 seconds after launch.

**11.** Why is Ariane 5 famous?
— The most expensive computer bug in history (control-software fault).

**12.** Definition of software testing?
— Executing a system under specified conditions to find defects and verify requirements.

**13.** Two categories of quality assessment?
— Static (manual) analysis and Dynamic (automated) analysis.

**14.** Which analysis executes the program?
— Dynamic analysis.

**15.** Three examples of static analysis?
— Code review, inspection, algorithm analysis.

**16.** SQA is what kind of activity?
— An umbrella activity applied throughout the software process.

**17.** Does SQA execute the program?
— No.

**18.** Does SQC execute the program?
— Yes.

**19.** Who is responsible in SQA vs SQC?
— SQA = all team members; SQC = only the testing team.

**20.** SQA and SQC map to which of Verification/Validation?
— SQA = Verification; SQC = Validation.

**21.** Define Error / Fault / Failure / Defect (one line each)?
— Error = human action producing wrong result; Fault = incorrect step/data in the program; Failure = system can't perform its function; Defect = deviation from spec.

**22.** Three stages of SqE?
— Planning, Execution, Decision.

## Chapter 2 — Software Quality

**23.** External view sees software as?
— A black box.

**24.** Internal view sees software as?
— A white / clear box.

**25.** Who proposed the five views of quality?
— Kitchenham and Pfleeger.

**26.** Name the five views of quality.
— Mystical, User, Manufacturing, Product, Value-based.

**27.** Which view underlies CMM and ISO 9001?
— Manufacturing view.

**28.** Which view says quality is recognized but not defined?
— Mystical view.

**29.** The value-based view merges which two concepts?
— Excellence (quality) and worth (value).

**30.** Product view claim?
— Good internal properties lead to good external properties.

**31.** Three reasons to measure quality?
— Baseline; quality improvement based on cost; know present level for planning.

**32.** What is a quality factor?
— A behavioural characteristic of a system.

**33.** Examples of quality factors?
— Correctness, reliability, efficiency, performance.

**34.** What is a quality criterion?
— An attribute of a quality factor, related to development.

**35.** Examples of quality criteria?
— Modularity, testability, maintainability, reusability.

**36.** Whose model gives factors and criteria?
— McCall's.

**37.** Definition of reliability?
— Probability of executing without failure for a specific period of time.

**38.** Most influential quality framework?
— ISO-9126.

**39.** How many ISO-9126 top-level characteristics, and what are they?
— Six: Functionality, Reliability, Usability, Efficiency, Maintainability, Portability.

**40.** Is security an ISO-9126 top-level characteristic?
— No.

## Chapter 3 — Maturity Models

**41.** What is a software process?
— A set of activities executed to develop products.

**42.** Three benefits of a defined process?
— Repeatable, evaluable (via metrics), improvable.

**43.** Three reasons to improve a process?
— Quality, Lead Time, Cost.

**44.** What does CMM evaluate?
— Software development processes.

**45.** What does TMM evaluate?
— A testing process.

**46.** What does TPI do?
— Improves the testing process.

**47.** How many CMM levels?
— 5.

**48.** Name the five CMM levels.
— Initial, Repeatable, Defined, Managed, Optimizing.

**49.** CMM Level 1?
— Initial.

**50.** CMM Level 4?
— Managed.

**51.** CMM Level 5?
— Optimizing.

**52.** Which CMM level uses data collection and analysis?
— Level 4 (Managed).

**53.** How many TMM levels?
— 5.

**54.** Who pioneered TMM?
— Ilene Burnstein.

**55.** Name the five TMM levels.
— Initial, Phase Definition, Integration, Management and Measurement, Optimization.

**56.** How many steps to improve a test process (TPI)?
— 4.

## Chapter 4 — Software Quality Assurance

**57.** Three generic QA categories?
— Defect Prevention, Defect Reduction, Defect Containment.

**58.** Two ways to do defect prevention?
— Error source removal and error blocking.

**59.** Error source removal is done via?
— Education and training (people-based).

**60.** Most common static defect-reduction technique?
— Inspection.

**61.** Two forms of inspection formality?
— Informal walkthroughs/reviews and formal inspections.

**62.** Two ways to do defect containment?
— Software fault-tolerance and safety assurance.

**63.** What is NVP?
— N-Version Programming (a fault-tolerance technique).

**64.** Recovery in fault tolerance means?
— Rollback and redo.

**65.** Define safety / accident / hazard.
— Safety = accident-free; Accident = failure with severe consequences; Hazard = pre-condition to an accident.

**66.** Is defect prevention 100% effective?
— No.

**67.** Name the four development process variations.
— Waterfall, Iterative, Spiral, Agile (plus Maintenance).

**68.** In the DC→V&V mapping, unit testing maps to?
— Verification.

## Chapter 5 — Software Quality Engineering

**69.** What does SQE minimize while meeting quality?
— Cost and project risks.

**70.** Three phases of the generic testing process?
— Pre-QA, In-QA, Post-QA.

**71.** When are most key testing decisions made?
— Pre-QA / planning.

**72.** Test plan is which level?
— High-level.

**73.** Test case is which level?
— Low-level.

**74.** What is a test suite?
— A collection of test cases run until stopping criteria (macro-level).

**75.** Reusing earlier test cases is called?
— Regression testing.

**76.** Does "Post-QA" mean after QA finishes?
— No; it runs parallel to QA.

**77.** Three testing team models?
— Vertical, Horizontal, Mixed.

**78.** The horizontal model does what?
— One kind of testing for many different products.

## Chapter 6 — Software Testing

**79.** How many principles of testing?
— 7.

**80.** Principle 1?
— Testing shows presence of defects, not their absence.

**81.** Principle 2?
— Exhaustive testing is impossible.

**82.** Principle 3?
— Early testing (defects are cheaper to fix early).

**83.** Principle 4?
— Defect clustering.

**84.** Principle 5?
— Pesticide paradox.

**85.** Principle 6?
— Testing is context dependent.

**86.** Principle 7?
— Absence-of-errors fallacy.

**87.** Four testing levels?
— Unit, Integration, System, Acceptance.

**88.** Who does unit testing?
— Developer.

**89.** Who does integration and system testing?
— Tester.

**90.** Who does acceptance testing?
— End-user.

**91.** Does regression testing design new tests?
— No; it selects, prioritizes, and executes existing ones.

**92.** White-box testing is also called?
— Structural / implementation-based testing.

**93.** Black-box testing is also called?
— Functional / specification-based testing.

**94.** Two things white-box examines?
— Control flow and data flow.

**95.** Who performs white-box testing?
— Developers.

**96.** Who performs black-box testing?
— Professional / third-party testers (IV&V).

**97.** What is gray-box testing?
— Mixed black-box and white-box (middle levels).

**98.** Is "no more defects found" a valid stopping criterion?
— No.

**99.** Two types of exit criteria?
— Resource-based and quality-based.

**100.** Can automation replace manual testing?
— No.
