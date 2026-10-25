# SSG-28 and RG 1.68 - Study Notes for the KINGS Interview

These notes are a summary of the two main documents about NPP commissioning that I am studying for the KINGS interview:

- **IAEA SSG-28 - Commissioning for Nuclear Power Plants** (IAEA Specific Safety Guide, Vienna, 2014);
- **US-NRC Regulatory Guide 1.68, Revision 4 - Initial Test Programs for Water-Cooled Nuclear Power Plants** (June 2013).

The idea is not to cover every paragraph, but to keep the main spirit of each document. For every topic, the number between parentheses shows where the information came from:

- SSG-28: paragraph number, for example **(2.19)**;
- RG 1.68: section of the guide, for example **(RG C.8)** or **(RG App. A-3)**.

At the end of each part there is a "Summing up" written with my own words. At the end of the file there are possible interview questions with answers.

---

## Contents

- [0. The big picture](#0-the-big-picture)
- [1. IAEA SSG-28](#1-iaea-ssg-28---commissioning-for-nuclear-power-plants)
- [2. US-NRC RG 1.68](#2-us-nrc-rg-168---initial-test-programs-for-water-cooled-npps)
- [3. Comparing the two documents](#3-comparing-the-two-documents)
- [4. Why these documents matter for LABGENE (my view)](#4-why-these-documents-matter-for-labgene-my-view)
- [5. Possible interview questions and answers](#5-possible-interview-questions-and-answers)

---

# 0. The big picture

- **Commissioning** is the process where the plant, after being built, is tested to show that it works as designed and as described in the Safety Analysis Report (SAR). It is a **progressive transition from construction to operation** (2.1).
- The IAEA calls this process **commissioning**. The NRC calls the testing part of it the **Initial Test Program (ITP)**. They describe basically the same thing.
- Both documents are **guides**, not laws:
  - IAEA Safety Guides use "should" statements. They show international good practices (Safety Standards introduction).
  - NRC Regulatory Guides describe one acceptable way to meet NRC regulations. Other methods can be accepted if they are justified (RG A, "Purpose of Regulatory Guides").
- Both documents follow the same logic: **test from the simplest to the most complex, from non-nuclear to nuclear, and never put the plant in a condition that was not analysed and found safe**.

### Vocabulary map (SSG-28 x RG 1.68)

| Idea | IAEA SSG-28 | US-NRC RG 1.68 |
|---|---|---|
| The whole testing process | Commissioning programme | Initial Test Program (ITP) |
| Tests before fuel | Non-nuclear testing (pre-operational tests) | Preoperational testing |
| Tests with fuel | Nuclear testing | Initial startup testing |
| Owner of the plant | Operating organization (licensee) | Applicant / licensee |
| Safety basis document | Safety Analysis Report (SAR) | Final Safety Analysis Report (FSAR), Chapter 14 (ITP) and Chapter 15 (accident analysis) |
| Points where you stop and review | Hold points and milestones | Hold points (power ascension) |
| Transfer of systems | Handover / transfer of systems | Turnover |

---

# 1. IAEA SSG-28 - Commissioning for Nuclear Power Plants

## 1.1 What this document is (1.1 - 1.12)

- (1.1) It supports the IAEA requirements of **SSR-2/2 (Safety of NPPs: Commissioning and Operation), Section 6**. It replaces the old guide **NS-G-2.9 (2003)**.
- (1.3) Objective: give recommendations based on international good practices, so that commissioning is done **safely and with high quality**, and to give assurance that the plant was built according to the design intent and can be operated safely.
- (1.4) The guide may also be used when a plant is **restarted after a long shutdown** or after **big modifications**.
- (1.5) Scope: commissioning of **land-based stationary thermal NPPs** of all types.
- (1.7) It does **not** cover **nuclear security** (this is covered by the IAEA Nuclear Security Series).
- Structure: Section 2 (the process), Section 3 (organization and management), Section 4 (implementation and tests), Section 5 (documentation), Appendix (fuel loading) and Annex (list of typical tests).

## 1.2 The commissioning process and its objectives (2.1 - 2.3)

- (2.1) Commissioning should be carefully developed, planned, executed and regulated.
- (2.2) Good coordination and communication among all participants: designers, construction group, licence holder, regulators, manufacturers, commissioning and operating groups.
- (2.3) The **main objective** is to show that the plant **as constructed** meets the design requirements and safety requirements of the **SAR** and the **licence conditions**. For this, commissioning should:
  - verify that SSCs (structures, systems and components) meet their **acceptance criteria**;
  - collect **baseline data** for the future;
  - **validate operating, surveillance and emergency procedures** by trial use;
  - **familiarize** the operating, maintenance and technical staff with the plant.

## 1.3 The commissioning programme (2.4 - 2.16)

- (2.4) It covers all activities needed to make SSCs operable according to the design intent. It should also allow the verification of **SAR assumptions** and of the **margins** between design and real performance, always keeping the plant in a safe domain.
- (2.5) Tests done **off-site** (for example, factory tests) can be used, but they must be **justified** for the equipment as installed.
- (2.6) It should consider **chemical preconditioning/passivation** before active commissioning (less corrosion products, less dose in the future).
- (2.7) A **detailed list of activities** with clear **responsibilities**.
- (2.9) The programme should guarantee that:
  - all tests needed to show the plant meets the SAR are done;
  - tests are **progressive** (less onerous conditions first, more onerous later);
  - tests are grouped in stages: **non-nuclear -> nuclear**, and **individual systems -> integrated systems -> whole plant**;
  - **hold points** and **milestones** (including those that need regulatory authorization) are defined;
  - personnel are trained and procedures are validated.
- (2.10) The **operating organization** must review and approve the programme, no matter who executes it.
- (2.11) Each test has a **unique identification**, cross-references and provisions for **data collection**.
- (2.12 - 2.13) Normal and emergency operating procedures should be used and validated, with participation of plant staff and designers.
- (2.14 - 2.16) The programme is also a **scheduling framework**, should be easy to understand, and should be inside the **management system** of the operating organization.

## 1.4 Stages of commissioning (2.17 - 2.22)

- (2.17) The programme is divided into **stages**. At the end of each stage there is a **review** before going to the next one. If some test was not done, its impact on safety must be considered.
- (2.18) **Before initial criticality, low power and power ascension tests, all previous tests should be satisfactorily completed.**
- (2.19) Typical stages:

| Stage | Substages |
|---|---|
| **Non-nuclear testing** | Individual pre-operational tests of systems and components; overall pre-operational system tests; structural integrity tests and integrated leakage rate tests (containment, primary and secondary systems) |
| **Nuclear testing** | Initial fuel loading; subcritical tests; initial criticality tests; low power tests; power ascension tests |

- (2.20) The sequence can be adjusted, but with the **same level of review** and agreement between commissioning organization, operating organization and, if necessary, regulator.
- (2.21) Each stage prepares the next one.
- (2.22) Safety system settings and alarm settings are defined at the right stages.

## 1.5 Execution of the programme - the golden rules (2.23 - 2.29)

- (2.23) Testing is the **core** of commissioning. But a test should **not** be done if:
  - it was not analysed and found safe;
  - it is outside the assumptions of the SAR;
  - it may damage the plant or affect safety.
- (2.23) A **risk assessment before each test**.
- (2.25) Sequence: support systems first, so they are available for other tests; simultaneous tests may affect each other.
- (2.26) Long inactive periods during construction can change equipment already tested (mainly standby components).
- (2.27) Test procedures include principles, objectives, **acceptance criteria** and, for safety systems, checks for normal operation, anticipated operational occurrences and accident conditions (as far as possible).
- (2.29) Multi-unit sites: separate programmes for each unit, isolation between commissioning and construction areas.

## 1.6 Regulatory body and operating organization (2.30 - 2.36, 3.48 - 3.49)

- (2.30) **Regulatory body**: oversight of commissioning and issuing (or not) authorizations. It checks that the plant was built according to its design and licensing basis.
- (2.31) In some States, the regulator approves the programme and establishes **hold points**. Typical hold points: **fuel loading, first criticality and power ascension**.
- (2.32) The regulator also checks if the operating organization is ready to move from **supervising construction to supervising operation** (emergency plan, training of operators).
- (3.48) Before authorizing fuel loading and first criticality, the regulator reviews items such as: draft final SAR, as-built design, pre-operational test results, operational limits and conditions (OLCs), emergency procedures, staffing, quality management, radiation protection and emergency preparedness.
- (3.49) Before full power routine operation: results of commissioning tests, updated final SAR and OLCs, and as-built modifications.
- (2.34) **Operating organization** (licensee): bears the **overall responsibility for safety**.
- (2.35) If contractors do the commissioning, the operating organization must review and approve their activities and set hold points.
- (2.36) Operating personnel involved **as early as possible**. Safety culture (questioning attitude, safety consciousness) should become **instinctive** before operation.

## 1.7 Management system (3.1 - 3.12)

- (3.1) The management system should meet IAEA GS-R-3 (*note: GS-R-3 was later replaced by GSR Part 2, 2016*).
- (3.4) Established **before** commissioning starts, using a **graded approach** (more control for items more important to safety).
- (3.5) Topics the management system should cover. Some of them: control of documents and records, purchasing, project management, work planning, **control of contractors**, **configuration management**, plant modification, maintenance, interfaces with the regulatory body, information technology, training, nuclear material accounting.
- (3.6) The **safety classification** of SSCs (from design) defines how much testing, inspection, review and record keeping each SSC needs.
- (3.9) The management system should develop **safety culture** in construction, commissioning and operating groups, and also in designers, manufacturers and contractors.
- (3.12) **Independent oversight** of the quality of ongoing work, when necessary.

## 1.8 Organization: the three groups (3.13 - 3.35)

- (3.14) Commissioning activities involve three groups:
  - **Construction group**: builds and installs SSCs according to the design (3.18, 3.32);
  - **Commissioning group**: tests SSCs to show that the plant is ready for safe operation (3.18, 3.33);
  - **Operating group**: operates and maintains the transferred systems, respecting the OLCs (3.18, 3.34).
- (3.14) Designers, manufacturers and technical support organizations also participate. Designers should **review commissioning data** and help to solve problems.
- (3.15) If commissioning is subcontracted, the **ultimate responsibility for safety remains with the operating organization**.
- (3.16) Operating personnel should participate from the start, to create an **"institutional memory"** of the plant.
- (3.17) Responsibilities must remain clear even when construction, commissioning and operation overlap.
- (3.19) The operating group should be created **early in construction**.
- (3.22 - 3.23) The operating organization coordinates everything: approves programme and procedures, monitors transfers of responsibility, solves interface problems, decides if tests and stages were properly completed, follows the correction of defects, keeps documentation updated (**configuration control**) and talks to the regulator.
- (3.25) The commissioning group is headed by a **commissioning manager**, appointed well in advance.
- (3.33) Some important responsibilities of the commissioning group: test procedures, recording of plant data, verifying prerequisites (flushing, functional checks, logic and interlock checks), **configuration control**, control of **temporary changes**, issuing **test certificates and stage completion certificates**, reporting deficiencies, **lessons learned**.

## 1.9 Interfaces (3.36 - 3.47)

- (3.36 - 3.37) Construction, commissioning, operation and maintenance happen **in parallel**. Their interfaces must be managed for safety.
- (3.39 - 3.40) **Work control processes** and clear lines of authorization and communication.
- (3.42) Construction x commissioning: procedures to transfer SSCs, isolation of areas still under construction, prerequisites, partially installed systems.
- (3.43) Systems that were **partially installed** are only partially commissioned. Later tests must cover the full system.
- (3.44) Commissioning x operation: delineation of responsibilities, baseline data, as-built drawings, control of **temporary equipment** (jumpers, lifted leads, special startup instrumentation), radiation protection, records for future decommissioning.
- (3.46) Operating procedures can be validated in commissioning with success criteria **more numerous or more challenging** than in normal operation.

## 1.10 Transfer of systems and handover of the plant (3.50 - 3.55)

- (3.50) **Handover** = transfer of **responsibilities** for SSCs, equipment, documentation and sometimes personnel. Two paths: construction -> operating group, or construction -> commissioning -> operating group. Everything must be documented.
- (3.52) Before nuclear material arrives, systems are gradually transferred to the operating group after their tests are reviewed. **Before nuclear testing, all systems should be under the control of the operating group.**
- (3.53) Documentation is transferred in **acceptance packages**, one per system.
- (3.54) Each acceptance package contains, for example: pressure test and flushing records, construction acceptance packages (welding inspection records), **as-built** diagrams, pre-nuclear test procedures and data, failure and incident reports, temporary modifications, maintenance records, design change records, **lists of pending items**, vendor manuals and set point books.
- (3.55) The receiving organization reviews the package with qualified people and makes **plant walk-downs**.

## 1.11 Resources, training and continuous improvement (3.56 - 3.77)

- (3.57 - 3.59) Planning of human resources, monitoring of **contractors' resources and competence**, and logistics (for example, demineralized water for flushing and stable electrical power).
- (3.60 - 3.61) Qualification and training. Operators should be trained in a **full scope simulator**.
- (3.67) **Non-conformances**: a robust system to record and solve non-conformances and to approve concessions, corrective and preventive actions.
- (3.68 - 3.69) **Feedback of experience**: report abnormal events, human errors and near misses; use lessons from other plants and other industries.
- (3.70) The plant must be maintained during commissioning, with historical records from the first energization of each system.
- (3.72) Emergency arrangements in place **before fuel arrives on site**, and complete and tested **before fuel loading**.
- (3.77) Each test procedure should define limits and the **actions if the limits are approached** (contingency actions).

## 1.12 Commissioning tests: objectives and acceptance criteria (4.1 - 4.12)

- (4.5) The documentation of tests, results, deviations and dispositions is kept **for the lifetime of the plant**.
- (4.6) Design, operational and safety documentation should be **updated** with test results.
- (4.7) Each test has a clear purpose linked to the **safety criteria of the SAR**.
- (4.8) Factory tests can be used if justified. For **first-of-a-kind** features, the in-plant tests should be identified **early**.
- (4.9) Acceptance criteria must consider **measurement uncertainties**.
- (4.10) At least **two categories** of acceptance criteria: **safety requirements** and **non-safety aspects**.
- (4.11) If safety requirements are verified by calculation, the codes and simulation tools need **verification and validation**.
- (4.12) At the end of each stage, a list of acceptance criteria verified (and those that need to be changed). This is a main input to decide if the next stage can start.

## 1.13 Preparation and prerequisites for testing (4.13 - 4.27)

- (4.13 - 4.16) Written programmes and procedures, verified with the operating organization. Designers and regulator may review the acceptance criteria.
- (4.14) Commissioning programmes at three levels (see also 5.12 - 5.14): whole plant, each system and each stage.
- (4.18) Use of **simulators or computer codes** to develop and validate test procedures.
- (4.19) **Temporary changes** (interlock bypasses, valve line-ups, instrument settings) must be listed, checked and **restored** after the test.
- (4.20) Methods of data analysis and treatment of uncertainties in the procedure.
- (4.21 - 4.24) Calibrated measuring and test equipment, with a register and calibration control.
- (4.25) Typical prerequisites before a test: construction completed and documented, component tests done, instruments calibrated, procedures approved, people trained and briefed, communications checked, written authorization, **safety analysis of the test conditions** done in advance.
- (4.26) A stage starts only after the previous stage is completed and approved. Example: pre-operational tests evaluated and approved **before fuel loading**.

## 1.14 Testing stages and sequences (4.28 - 4.60)

- (4.28) **Support systems first** (compressed air, electrical, service water, demineralized water, ventilation, drainage, radwaste) and systems that protect people and the plant (fire protection, radiation protection, emergency power).
- **Pre-operational tests** (4.29 - 4.38):
  - (4.32) Divided into **cold performance tests** and **hot performance tests**.
  - (4.33) Cold tests: first operational data and functional performance. Usually include the **pressure test** of primary and secondary systems.
  - (4.35 - 4.37) Hot tests: simulate operating temperatures, pressures and flows; check thermal expansion, vibration, insulation and heat removal; reach **steady state**.
  - (4.38) Operators use and validate operating procedures.
- **Initial fuel loading and subcritical tests** (4.39 - 4.49):
  - (4.39) Load fuel safely according to the design loading pattern.
  - (4.42) Train on the fuel machine with **dummy fuel assemblies**.
  - (4.43, 4.46) Continuous **neutron flux monitoring** to avoid inadvertent criticality. **Subcriticality checks** at regular steps. If measurements deviate from predictions, **stop loading** until the reason is understood.
  - (4.44) Fuel loading is only authorized after all pre-operational tests are acceptable to the regulator and the operating organization.
  - (4.47) The position of each fuel assembly is **independently confirmed**.
- **Initial criticality** (4.50 - 4.54):
  - (4.51) Startup instrumentation and automatic shutdown system available.
  - (4.52) Reactivity changes continuously monitored and the predicted critical point continuously checked. **Unanticipated reactivity change -> shut down immediately** and only continue after understanding the reason.
  - (4.54) Successively smaller reactivity additions, to avoid passing criticality with a short period.
- **Low power tests** (4.55 - 4.56): confirm that core performance and reactor physics parameters agree with the core design and with the SAR, at the **lowest power** that gives reliable measurements.
- **Power ascension tests** (4.57 - 4.60):
  - (4.57) **Step by step** to full power. Typical steps: **10, 25, 50, 75, 90 and 100%**.
  - (4.59) Tests in steady state and during anticipated operational occurrences (reactor trips, load rejections).
  - (4.60) At the end, a review to confirm if the **OLCs are adequate**.

## 1.15 Review of results and handling of deviations (4.61 - 4.76)

- (4.61) After each test, results are reviewed. The review should guarantee that **the safety of the plant never depends on SSCs that were not tested**.
- (4.62) Evaluation = comparison with acceptance criteria + design margins + analysis of deviations.
- (4.63 - 4.66) **Stage completion review** by commissioning group and operating organization (and regulator if required). The next stage is only permitted after approval by the operating organization.
- (4.68) Reports: individual test reports, **stage test reports** and a **final plant commissioning report**.
- (4.69 - 4.75) **Modifications**: consider regulatory requirements, effects on other systems and safety; temporary modifications must be controlled; changing the test sequence needs a review.
- (4.76) **Unexpected results**: immediate actions defined in procedures, then a review of causes and corrective/preventive actions.

## 1.16 Documentation (5.1 - 5.40)

- (5.2) Documentation gives continuity, evidence that the design intent was met, assurance to the operating organization and to the regulator, and **lifetime records**.
- (5.6 - 5.9) **Commissioning manual**: organization, responsibilities, programme, safety aspects, change management and documentation process.
- (5.12 - 5.14) Three types of programmes:
  - **Overall plant commissioning programme** (whole plant and overall schedule);
  - **System commissioning programmes** (objectives, test conditions and acceptance criteria for each system);
  - **Stage commissioning programmes** (prior conditions, chronology of tests, procedures to be validated in the stage).
- (5.19 - 5.32) Typical content of a **test procedure**: introduction, objectives and methods, OLCs, prerequisites and initial conditions, step by step procedure with expected values, **acceptance criteria and their origin**, instruments, staffing, special precautions/contingency plan, completion and restoration, permanent records, unique identification, **data collection** (standard forms, signed, chronological), non-conformance management.
- (5.33) **Test report**: method, conduct of the test, problems and actions, data and plots, evaluation against acceptance criteria, conclusions.
- (5.34) **Stage report**: summary of the stage and changes to the programme or plant.
- (5.35) **Records of deficiencies and reservations** (tests not fully carried out or not closed).
- (5.36 - 5.37) **Test certificate** and **stage completion certificate**.
- (5.38 - 5.39) **Handover certificate + handover acceptance package**.

## 1.17 Appendix (fuel loading) and Annex (typical tests)

- (A.2) Prerequisites for fuel loading, for example: startup instrumentation calibrated and tested with a neutron source, **shutdown margin** confirmed, fuel handling equipment tested with dummy fuel, high flux trip set at a **low level (about 1% of full power)**, emergency core cooling status, and **approval of the regulatory body**.
- (A.3) Fuel loading procedure: loading sequence, **inverse multiplication (1/M) plots** using at least two channels, limits for loading increments, **criteria to stop loading**, communication between control room and loading station.
- (Annex) List of typical tests for each stage and system (valves, pumps, electrical systems, reactor protection, containment, engineered safety features, power tests such as turbine trip and loss of off-site power). The list is **illustrative, mainly based on water reactors** (A-1).

<details>
<summary><b>🔍 Click here to see a summing up of SSG-28</b></summary>

## 📝 Summing Up (SSG-28)

SSG-28 is, in the end, a document about **management and safety at the same time**. The tests are the core of commissioning, but the document spends a lot of time on organization, interfaces, documentation and responsibilities.

The main ideas I want to keep are:

- Commissioning proves that the plant **as built** matches the **SAR** and the licence. If it is not in the SAR or was not analysed, it is not tested.
- Testing is **progressive**: non-nuclear before nuclear, components before systems, systems before the whole plant. Each stage ends with a **review** (hold point) before the next one.
- The **operating organization** is always responsible for safety, even if contractors do the work.
- There are three groups (**construction, commissioning, operating**). Most problems in commissioning happen at their **interfaces**, so handover, work control and communication are critical.
- **Handover** is done system by system, with **acceptance packages** and lists of pending items. Before nuclear testing, everything is under the operating group.
- Every test has **acceptance criteria** linked to safety, considering uncertainties. Deviations, modifications and unexpected results follow a controlled process.
- Commissioning produces a huge amount of **documents and data** (test reports, stage reports, certificates, deficiency records, baseline data) that must be kept for the **lifetime of the plant**.
- Commissioning is also the moment to build **safety culture** and the "institutional memory" of the operating staff.

</details>

---

# 2. US-NRC RG 1.68 - Initial Test Programs for Water-Cooled NPPs

## 2.1 What this document is (RG A. Introduction)

- (RG A) It describes the **scope and depth** of the Initial Test Program (ITP) that the NRC considers acceptable for **light water reactors**. It has three appendices:
  - **Appendix A**: specific tests for each ITP phase;
  - **Appendix B**: NRC inspections of the ITP;
  - **Appendix C**: content of test procedures.
- (RG A) The legal basis: 10 CFR Part 50 and Part 52. The FSAR must include **plans for preoperational testing and initial operations** (FSAR **Chapter 14**). **10 CFR 50 Appendix B, Criterion XI (Test Control)** requires a test program with written procedures and acceptance limits from design documents.
- (RG A) For new plants under Part 52, **ITAAC** (Inspections, Tests, Analyses and Acceptance Criteria) must be met before fuel load. Many ITAAC tests are also preoperational tests. Some requirements can only be verified **after fuel load** (for example, 100% load rejection), so they are part of the ITP.
- (RG A) **Graded approach** and **defense in depth**: all SSCs important to safety are tested, but not all with the same strictness. Testing and documentation should be **commensurate with the safety importance** of the item.
- (RG A) Regulatory guides are **not mandatory**. Different methods can be accepted if they are justified.

## 2.2 The six objectives of the ITP (RG B. Background)

1. Provide additional assurance that the facility has been **adequately designed**.
2. **Validate the analytical models**, as far as practical.
3. Verify the **correctness or conservatism of assumptions** used to predict responses to transients and accidents.
4. Provide assurance that **construction and installation** were done according to the design.
5. **Familiarize** the operating and technical staff with the plant.
6. Verify by **trial use** that operating and emergency procedures are adequate.

## 2.3 Key ideas of the Discussion (RG B)

- (RG B) **Preoperational testing**: tests after construction inspections and tests, but **before fuel loading**.
- (RG B) **Initial startup testing**: tests **during and after fuel loading** (pre-critical, initial criticality, low power and power ascension).
- (RG B) Startup tests must be sequenced so that **plant safety is never entirely dependent on untested SSCs**.
- (RG B) Power ascension should be **orderly and expeditious**. If it takes too long, it may show problems in operation, maintenance or design. Problems found early are easier to fix while fission products are still low.
- (RG B) **Baseline data** obtained early allow early identification of degradation and trends.
- (RG B) Early planning should consider five points:
  1. responsibilities of the organization (including design organizations in test objectives and acceptance criteria);
  2. **realistic schedules** relative to the fuel loading date;
  3. resources and **contract management** (if service contracts are used, the licensee needs enough trained staff to manage them);
  4. administrative controls, including **orderly turnover** of systems from construction to the preoperational test group, and prerequisites;
  5. use of **operating experience** from other plants.
- (RG B) **First-of-a-kind (FOAK)** features: in-plant tests should be identified **early**.
- (RG B) **Prototype plant**: a reactor used to test design features. It is similar to a FOAK or standard plant, but may have **additional safety features** to protect the public and the staff during the testing period.
- (RG B) **Harmonization**: RG 1.68 is consistent with the IAEA commissioning guide **NS-G-2.9** (the predecessor of SSG-28).

## 2.4 Staff regulatory guidance (RG C.1 - C.9)

- **(RG C.1) Which SSCs must be tested** - SSCs that:
  1. shut down and cool down the reactor in normal conditions;
  2. shut down and cool down the reactor in transients and accidents;
  3. establish conformance with **safety limits** or **limiting conditions for operation** (Technical Specifications);
  4. are **engineered safety features (ESF)** or support them;
  5. are credited in the **accident analysis (FSAR Chapter 15)**;
  6. process, store, control or limit the release of **radioactive materials**;
  7. must keep **structural integrity** to avoid damage to safety-related SSCs.
  - Non-safety-related but **risk significant** SSCs should also be tested (graded approach).
- **(RG C.2) Prerequisites**: construction essentially complete; construction inspections and tests done; **retest** systems that were returned to construction, maintained or modified.
- **(RG C.3) Scope and length**: simulate failures and malfunctions when practical; tests long enough to reach **equilibrium conditions** and to reveal **"run-in" (early burn-in) failures**.
- **(RG C.4) Procedures**: checklists and signature blocks; developed by technical people and approved by management; **acceptance criteria account for uncertainties** used in transient and accident analyses; design organizations participate; procedures available to the NRC about **60 days** before use; preoperational results evaluated **before fuel loading**, with retesting if criteria are not met.
- **(RG C.5) Schedule**: typical minimum of about **9 months for preoperational testing** and **3 months for initial startup testing**. Shorter periods need justification.
- **(RG C.6) Participation** of plant operating and technical staff.
- **(RG C.7) Trial testing** of emergency, operating and surveillance procedures, preferably before fuel load, and also in the plant simulator.
- **(RG C.8) Hold points** in power ascension: at least at about **25%, 50% and 75%** power for PWRs.
- **(RG C.9) Test reports**: retained as plant historical records. A **startup report** summarizes: method and objectives, comparison with acceptance criteria (including responses to scram and turbine trip), deficiencies and corrective actions, **justification for accepting non-conforming systems**, and conclusions.

## 2.5 Appendix A - The five phases of the ITP

- **(RG App. A-1) Preoperational testing**
  - Only after construction is essentially complete. Construction tests include calibration, flushing, cleaning, wiring checks, hydrostatic tests.
  - Tests include manual and automatic operation, alternate modes, **loss of power** and degraded modes, interlocks and protective devices.
  - Pre-service testing of pumps and valves follows the **ASME OM Code**.
  - Representative systems (A-1.a to A-1.p): reactor coolant system, reactivity control, reactor protection and ESF actuation, residual heat removal, power conversion, electrical systems, containment, ESF, instrumentation and control, radiation protection, fuel handling, auxiliary systems, among others.
- **(RG App. A-2) Initial fuel loading and pre-critical tests**
  - Cautious loading to avoid inadvertent criticality: Tech Spec prerequisites, **continuous neutron flux monitoring**, periodic data taking, **independent verification** of fuel positions.
  - Predictions of core reactivity prepared in advance, with actions defined if measurements deviate.
  - Loading **directly supervised by a senior licensed operator with no other concurrent duties**.
- **(RG App. A-3) Initial criticality**
  - Same rod withdrawal sequences that will be used later.
  - At least **1/2 count per second** on startup channels and signal to noise ratio **greater than 2**.
  - Approach slow enough to avoid a period shorter than about **30 seconds** (less than one decade per minute).
- **(RG App. A-4) Low-power testing** (normally **below 5% power**)
  - Confirm the design, validate models, verify safety analysis assumptions.
  - Examples: reactivity coefficients, **control rod worth** (shutdown margin with the most reactive rod stuck out), overlap of source and intermediate range instruments, flux distribution, radiation surveys, natural circulation.
- **(RG App. A-5) Power-ascension tests**
  - Start only after low power results are evaluated and approved.
  - Demonstrate operation in **steady state** and during **anticipated transients** (reactor scram, turbine trip, reactor coolant pump trip, loss of feedwater heaters).
  - Predicted responses use **real expected values**, not the conservative values of accident analysis. The goal is to validate the models.
  - No test outside the range analysed in the FSAR.
- **(RG App. A-6) FOAK tests** and **(RG App. A-7) Design qualification tests for advanced reactors** (passive or innovative safety features). These can be met with separate effects tests, integral tests, **prototype tests** or a combination with analysis and operating experience.

## 2.6 Appendix B - NRC inspections

- (RG App. B) The NRC inspects on a **risk-informed sample basis** whether the ITP is properly implemented and whether the plant, procedures and personnel are ready.
- (RG App. B) Inspectors examine procedures, **witness tests**, verify results against acceptance criteria and check FOAK tests. Having the procedures does **not** mean the NRC approved them.

## 2.7 Appendix C - Content of test procedures

- (RG App. C-1) Typical sections of a preoperational test procedure: **a. prerequisites**, **b. test objectives**, **c. special precautions**, **d. initial system conditions**, **e. environmental conditions**, **f. acceptance criteria** (with tolerances and uncertainties), **g. data collection** (permanent entries), **h. detailed step by step procedures** (with restoration of non-standard arrangements, jumper logs) and **i. documentation of test results**.
- (RG App. C-2) Fuel loading procedure: prerequisites, crew duties, nuclear instrument checks with a neutron source, **criteria to stop loading**, emergency boron injection and containment evacuation criteria.
- (RG App. C-4) Power ascension in **discrete steps**, with major testing at about **25, 50, 75 and 100%**. At each plateau: heat balance and calibration of nuclear instruments, check flux symmetry, **reset high flux trip** to no more than 20% above the next level, leak checks, vibration monitoring, and **management approval before going to the next level**.

<details>
<summary><b>🔍 Click here to see a summing up of RG 1.68</b></summary>

## 📝 Summing Up (RG 1.68)

RG 1.68 is more **technical and objective** than SSG-28. It tells **what** must be tested, **when** and **how the procedure should look**, and it connects everything to the US licensing documents (FSAR Chapter 14 and Chapter 15, Technical Specifications, ITAAC).

The main ideas I want to keep are:

- The ITP has **two big parts** (preoperational and initial startup) and **five phases**: preoperational, fuel loading and pre-critical, initial criticality, low power, power ascension.
- The ITP has **six objectives**. For me, the most important are: validate the **analytical models**, verify the **assumptions of the safety analysis**, and **validate procedures** while training the staff.
- Tests are selected by **safety function** (7 criteria) and with a **graded approach**.
- The plant should **never depend on untested SSCs**.
- **Acceptance criteria** must consider the **uncertainties** of the safety analysis, and design organizations should help define them.
- There are concrete numbers I should remember: about **9 months** of preoperational testing and **3 months** of startup testing; procedures to the NRC **60 days** before; low power **< 5%**; power hold points at about **25/50/75%**; criticality approach with a period of at least about **30 s**.
- The guide recognizes **first-of-a-kind** features and **prototype plants**, which need special tests identified early.

</details>

---

# 3. Comparing the two documents

| Aspect | IAEA SSG-28 | US-NRC RG 1.68 |
|---|---|---|
| Type | International Safety Guide (good practices, "should") | National regulatory guide (one acceptable method) |
| Year | 2014 (replaced NS-G-2.9, 2003) | Revision 4, 2013 |
| Scope | Land-based stationary thermal NPPs of all types | Light water reactors (PWR and BWR) |
| Focus | Whole commissioning process: organization, management, interfaces, handover, documentation and tests | The test program itself: which tests, phases, procedures, NRC inspection |
| Stages | Non-nuclear (pre-operational) and nuclear (fuel loading, subcritical, criticality, low power, power ascension) | Preoperational and initial startup (fuel loading/pre-critical, criticality, low power, power ascension) |
| Power steps | Typical 10, 25, 50, 75, 90, 100% (4.57) | Hold points at about 25, 50, 75% (C.8); major testing at 25, 50, 75, 100% (App. C-4) |
| Organization | Detailed (construction, commissioning and operating groups; handover packages) | Short (responsibilities, turnover, staff participation) |
| Link to licensing | SAR and licence conditions | FSAR Chapter 14 and 15, Tech Specs, ITAAC |
| Security | Not covered (1.7) | Not the focus |

**What they have in common:**

- Commissioning demonstrates that the **as-built plant matches the design and the safety analysis**.
- **Progressive** testing with **reviews/hold points** between stages.
- **Graded approach** based on safety importance.
- Test procedures with clear **acceptance criteria** that consider **uncertainties**.
- **Validation of procedures** and **training of operators** during commissioning.
- **Baseline data** and **records** for the whole plant life.
- Never test a condition that was **not analysed** in the safety analysis report.

---

# 4. Why these documents matter for LABGENE (my view)

*This section is my personal interpretation, not content from the documents.*

- **SSG-28 (1.5)** applies to **land-based stationary** thermal nuclear power plants. LABGENE is a **land-based prototype** of a PWR propulsion plant, so the principles of SSG-28 can be used as a reference, even though the final application is a submarine.
- **RG 1.68** is written for **light water reactors**. LABGENE is a **PWR**, so the test phases and many of the test types are directly comparable.
- RG 1.68 recognizes **first-of-a-kind** features and **prototype plants** (RG B, App. A-6, A-7). LABGENE is the first facility of this kind built in Brazil, so identifying FOAK tests early and validating analytical models will be very important.
- Both documents show that commissioning is a **huge information management challenge**: test procedures, results, deficiency lists, acceptance packages, certificates and baseline data, all with traceability. This is where my background in governance, risk and data engineering can contribute.
- The definition of how each document applies to LABGENE is a decision of the **national regulatory framework** and of the **operating organization**, not mine. I use these guides as **international references** for good practices.

---

# 5. Possible interview questions and answers

> Tip for myself: answer in a short and direct way first, then give one example. If I do not know something, I should say it honestly and explain how I would find the answer.

### Q1. What is commissioning of a nuclear power plant?

Commissioning is the process where the plant, after being built, is tested to demonstrate that it works according to the design and to the safety analysis report. The IAEA describes it as a progressive transition from construction to operation. During commissioning, we verify that structures, systems and components meet their acceptance criteria, we collect baseline data for the future, we validate operating and emergency procedures, and we train the operating staff. In summary, commissioning is the proof that the plant as built is the plant that was licensed.

### Q2. Why is commissioning so important for safety?

Because it is the last opportunity to find design, construction or installation problems before the plant starts operating with nuclear fuel and producing fission products. RG 1.68 also mentions that problems found during commissioning are easier to fix while the radioactive inventory is still low. Besides that, commissioning validates the analytical models and the assumptions of the safety analysis. If the real plant does not behave as predicted, the safety margins we believe we have may not exist.

### Q3. What are the main stages of commissioning?

According to SSG-28, there are two big stages. The first one is non-nuclear testing, which includes individual pre-operational tests of components, overall system tests, and structural integrity and leakage rate tests. The second one is nuclear testing: initial fuel loading, subcritical tests, initial criticality, low power tests and power ascension tests. RG 1.68 calls these phases preoperational testing and initial startup testing. The important idea is that each stage ends with a review before the next one starts.

### Q4. What is the difference between preoperational tests and startup tests?

Preoperational tests are performed after construction is essentially complete but before fuel loading. They demonstrate that systems meet their performance requirements, for example pumps, valves, electrical systems and the reactor protection system. Startup tests are performed during and after fuel loading: pre-critical tests, initial criticality, low power and power ascension. In startup tests we can finally test things that need nuclear heat, like reactivity coefficients, control rod worth and the plant response to transients.

### Q5. What is a hold point?

A hold point is a moment in the commissioning programme where the work stops until the results are reviewed and approved. SSG-28 says that commissioning stages are typical hold points, especially fuel loading, first criticality and power ascension. In some countries, the regulatory body defines these hold points. RG 1.68 recommends hold points during power ascension at about 25, 50 and 75 percent power for PWRs. I see hold points as a risk management tool: we only accept more risk after we prove that the previous step was safe.

### Q6. Why do we test support systems first?

Because other systems depend on them. SSG-28 mentions systems such as compressed air, electrical supply, service water, demineralized water and ventilation. If these systems are not working, we cannot properly test the systems that depend on them. In addition, some systems, like fire protection, radiation protection and emergency power, must be operational to protect people and the plant during the other tests. It is a logical sequence, like building a house from the foundation.

### Q7. What is an acceptance criterion and how should it be defined?

An acceptance criterion is the value or condition that defines if a test was successful. SSG-28 says acceptance criteria should be linked to safety and design requirements, should consider measurement uncertainties, and should be separated into at least two categories: criteria for safety requirements and criteria for non-safety aspects. RG 1.68 adds that the uncertainties used in the transient and accident analyses should be considered, and that the design organizations should participate in defining these criteria. The origin of each criterion should be documented.

### Q8. What is handover, and what is an acceptance package?

Handover is the formal transfer of responsibility for systems from one group to another: from construction to commissioning, and from commissioning to the operating group. SSG-28 recommends that documentation is transferred in acceptance packages, one for each system. A package includes, for example, test records, as-built diagrams, maintenance records, design change records, vendor manuals and a list of pending items. Before nuclear testing starts, all systems should be under the control of the operating group. From my governance experience, I believe the list of pending items is one of the most critical parts, because it is where problems can be forgotten.

### Q9. Who is responsible for safety during commissioning?

The operating organization, as the licensee. SSG-28 is very clear that even when commissioning is done by contractors, the ultimate responsibility for commissioning and for safety remains with the operating organization. For this reason, the operating organization must review and approve the commissioning programme, the test procedures and the contractors' activities, and it must establish its own hold points. The regulatory body has the role of oversight and authorization, not execution.

### Q10. What is the role of the regulatory body during commissioning?

The regulatory body oversees the commissioning activities and issues, or not, the authorizations to proceed. It reviews documents, inspects and witnesses tests. Before fuel loading and first criticality, it reviews items such as the draft final safety analysis report, the as-built design, the pre-operational test results, the operational limits and conditions, and emergency preparedness. Before routine operation at full power, it reviews the commissioning test results and the updated safety analysis report. RG 1.68 adds that the NRC inspects using a risk-informed sample, so it does not inspect everything.

### Q11. What are the main differences between SSG-28 and RG 1.68?

SSG-28 is an international guide and covers the whole commissioning process: organization, management system, interfaces, handover, documentation and tests. RG 1.68 is a US regulatory guide focused on the test program itself: which systems must be tested, the five test phases, the content of procedures and NRC inspections. RG 1.68 is also more specific to light water reactors and to US licensing documents, such as FSAR Chapter 14 and ITAAC. In my opinion, they are complementary: SSG-28 tells me how to organize commissioning, and RG 1.68 tells me in more detail what to test.

### Q12. What is a graded approach?

It means that the level of control is proportional to the importance to safety. Not every component needs the same level of testing, documentation and review. SSG-28 uses the safety classification of SSCs, defined in the design, to determine commissioning requirements. RG 1.68 says the same: all SSCs important to safety must be tested, but the most safety significant ones, like engineered safety features, receive the greatest attention. This is similar to what I do in risk management: we focus resources where the risk is higher.

### Q13. How should initial fuel loading be performed safely?

Fuel loading should be done carefully to avoid inadvertent criticality. The main measures are: all pre-operational tests completed and accepted, startup neutron instrumentation calibrated and checked with a neutron source, continuous monitoring of the neutron flux, subcriticality checks at regular steps using inverse multiplication plots, and clear criteria to stop loading if measurements deviate from predictions. The position of each fuel assembly must be independently confirmed. RG 1.68 also says the loading should be directly supervised by a senior licensed operator with no other duties.

### Q14. Why is power ascension done in steps?

Because at each power level we can compare the real plant behaviour with the predictions before accepting more risk. At each step, the team performs the scheduled tests, calibrates the nuclear instruments with a heat balance, checks flux symmetry, leakages and vibrations, and then management approves the next step. SSG-28 mentions typical steps of 10, 25, 50, 75, 90 and 100 percent. RG 1.68 recommends hold points at about 25, 50 and 75 percent. It is the same idea of progressive testing.

### Q15. What do you do if a test gives an unexpected result?

First, follow the immediate actions defined in the test procedure, which should already describe what to do if limits are approached or exceeded. Then, the event must be recorded and reviewed to understand the cause and decide the corrective and preventive actions. If it is a non-conformance, it follows the non-conformance process of the management system. During fuel loading or the approach to criticality, the rule is even stricter: if reactivity behaves differently than predicted, we stop or shut down and only continue after understanding the reason. The result should also be shared as lessons learned.

### Q16. What are baseline data and why are they important?

Baseline data are the reference values of equipment and systems measured during commissioning, when the plant is new. Both documents say they should be collected and kept. They are important because, during the plant lifetime, we compare new measurements with this baseline to detect degradation and trends early, for example in pumps, valves or vibration levels. In my view, this is a clear example of how data organization during commissioning creates value for decades of operation.

### Q17. What is a first-of-a-kind test, and why is it relevant?

A first-of-a-kind, or FOAK, test is a test for a new, unique or special design feature that has no previous operating experience. RG 1.68 and SSG-28 say that these tests should be identified early, so they can be considered in the final test design. RG 1.68 also defines a prototype plant as a reactor used to test design features, which may have additional safety features during the testing period. I believe this is very relevant for LABGENE, because it is the first facility of this kind in Brazil.

### Q18. These guides are for commercial power plants. Why do you think they apply to LABGENE?

SSG-28 applies to land-based stationary thermal nuclear power plants, and LABGENE is a land-based prototype of a pressurized water reactor plant. RG 1.68 is written for light water reactors, so the test phases and many of the tests are comparable. Of course, the formal application is a decision of the national regulatory framework and of the operating organization. But the principles are universal: progressive testing, clear acceptance criteria, independent review, handover control and good documentation. For a first-of-a-kind facility, I believe following international good practices is even more important.

### Q19. How can your background help in commissioning?

Commissioning is a technical activity, but it is also a big management and information challenge. There are thousands of test procedures, results, deficiencies, acceptance packages and certificates, and they must be traceable for the whole plant life. In my current work in governance and compliance, I deal with risk assessment, internal processes, stakeholders and large amounts of data. With my data engineering experience, I can help build tools to track test progress, pending items and handover status. And with the technical knowledge from KINGS, I can understand what is behind each test.

### Q20. What is the role of safety culture during commissioning?

SSG-28 says the commissioning stage should foster a safety culture that continues during operation. Attributes like a questioning attitude, safety consciousness and personal responsibility should become instinctive before the plant starts operating. In practice, this means that schedule pressure should never be more important than acceptance criteria and hold points. It also means that everyone, including contractors, should understand the safety significance of their work and report problems and near misses.

### Q21. Does SSG-28 cover nuclear security?

No. Paragraph 1.7 says SSG-28 does not cover nuclear security during commissioning, and that guidance on security is in the IAEA Nuclear Security Series. It is important to separate the two concepts: safety is about protecting people and the environment from accidents and radiation, while security is about preventing and responding to malicious acts, like theft or sabotage. The IAEA says they should be integrated so that one does not compromise the other.

---

*References:*

- *INTERNATIONAL ATOMIC ENERGY AGENCY, Commissioning for Nuclear Power Plants, IAEA Safety Standards Series No. SSG-28, IAEA, Vienna (2014).*
- *U.S. NUCLEAR REGULATORY COMMISSION, Regulatory Guide 1.68, Revision 4, Initial Test Programs for Water-Cooled Nuclear Power Plants (June 2013).*
