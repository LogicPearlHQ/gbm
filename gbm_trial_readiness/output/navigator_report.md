# GBM Treatment And Trial Navigator

- Program ID: `gbm_treatment_navigator_v1`
- Subtitle: Synthetic-patient navigation for standard care, advanced options, and trial screening
- Source note: This build uses public oncology sources to structure synthetic patient navigation. It is designed for clinician-review workflows rather than autonomous treatment decisions.

## Case Navigation

### Completed Initial Workup
- Case ID: `case_newly_diagnosed_fit_adult`
- Patient: `synthetic-001`
- Evidence package: 7 ready / 1 missing
- Standard-care paths to discuss: 3
- Trial candidates for review: 157
- Trials needing more evidence: 3
- Bitmask: `64`

#### Recommended Care Pathways
- Postoperative Radiation Plus Temozolomide: Standard newly diagnosed postoperative pathway after surgery in a fit adult with GBM.
  Reasons: Patient state matched: newly_diagnosed, Patient state matched: post_surgery, Patient state matched: adult_patient, Patient state matched: performance_status_good
- Tumor Treating Fields: Device-based therapy to discuss alongside standard treatment in appropriate newly diagnosed GBM settings.
  Reasons: Patient state matched: newly_diagnosed, Patient state matched: adult_patient, Patient state matched: performance_status_good
- Molecular Tumor Board Review: Escalate to a molecular review when sequencing data exists and the patient is being screened for advanced options.
  Reasons: Patient state matched: advanced_option_search, Patient state matched: performance_status_good

#### Candidate Trials
- NCT07488754 - Medical Experiment - Assessment of Efficacy & Safety of Local, Targeted Therapy With Neuropeptide Labelled With Alpha Emitter [225Ac]Ac-DOTA-SP (TAT) as Supplementary Therapy Following Standard Treatment Of Glioma (WHO G3-G4) (NA, RECRUITING): Brain tumors account for 1.35% of all cancers and cause 2.2% of cancer-related deaths. Gliomas are the most common type, comprising 40-90% of central nervous system tumors in different age groups. The incidence of malignant gliomas is approximately 0.5-2 per 100,000 people annually. Standard treatments include surgical resection, radiotherapy, and chemotherapy, yet overall survival remains low, typically 1-3 years post-diagnosis. The study highlights the pressing need for novel treatment strategies, particularly given the infiltrative nature of gliomas and the potential for targeted therapies using neuropeptides.The aim of this study is to assess the efficacy and safety of local targeted therapy with \[225Ac\]Ac-DOTA-SP in newly diagnosed glioblastoma following standard treatment.It is an interventional study without a control group, initiated by the researcher. Patients included are aged 18-80 with WHO G3-G4 glioma post-first-line treatment, not requiring immediate surgery and meeting specific MRI criteria.Patients will receive a maximum of six cycles of \[225Ac\]Ac-DOTA-SP, involving pre-treatment assessments, local administration of the agent after ensuring catheter patency, and continuous monitoring. Blood tests and neurological evaluations will be performed regularly.Outcome will be assessed by measuring overall survival (OS) and progression-free survival (PFS). The study anticipates improvements in both OS and PFS when compared to current treatments, contributing to critical insights into targeted alpha therapy's effectiveness in glioblastoma.Treatment with \[225Ac\]Ac-DOTA-SP previously indicated few significant side effects, primarily transient issues like seizures. Patients will be closely monitored throughout the study to identify any adverse effects promptly.The estimated study duration is three years, with biological material collected for histopathological and genetic analysis during surgical reoperation.Data will be anonymized to protect patient confidentiality, stored securely, and made available only for the scope of the study.Led by Prof. Przemysław Kunert, the research team includes multiple co-investigators from neurosurgery and nuclear medicine departments.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07488754
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07485049 - A Phase 0/2 Study of BGB-58067, an MTA Cooperative PRMT5 Inhibitor, in Newly Diagnosed Glioblastoma Patients With Methylthioadenosine Phosphorylase (MTAP) Deleted Tumors Scheduled for Resection to Evaluate Central Nervous System (CNS) Penetration With Pharmacodynamic (PD)-Triggered Expansion Cohorts (EARLY_PHASE1, NOT_YET_RECRUITING): This is an open-label, multi-center, Phase 0/2 trial designed to enroll up to 78 total participants with suspected newly diagnosed glioblastoma (nGBM) who are scheduled for surgical resection to accrue at least 14 participants in Arm A and 10 participants in Arm B. The trial will evaluate the pharmacokinetics (PK), pharmacodynamics (PD), and safety of BGB-58067. The study is composed of a Phase 0 and expansion Phase 2 component. The Phase 0 primary endpoint will be suppression of symmetric dimethylarginine (SDMA) in tumor tissue measured by immunohistochemistry (IHC). The Phase 2 primary endpoint will be 12-month overall survival rate (OS12). The Phase 0 secondary endpoint will be to characterize the PK of BGB-58067 in tumor tissue, plasma, and cerebrospinal fluid (CSF). The Phase 2 secondary endpoints will include assessing the safety profile of BGB-58067 and evaluating clinical efficacy of BGB 58067 using overall survival (OS) and the 6-month progression-free survival rate (PFS6) estimated by Kaplan-Meier (K-M) methods.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07485049
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07455045 - An Open-Label, Multicenter, Phase I Study of FZ-AD005 Antibody-Drug Conjugate in Patients With Recurrent/Refractory High-Grade Glioma (HGG) (PHASE1, NOT_YET_RECRUITING): An Open Label, Phase I Study to Evaluate the Safety, Tolerability, Pharmacokinetics, and Preliminary Antitumor Activity of FZ-AD005 in Patients with HGG, especially in DMG and other Recurrent HGG.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07455045
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07452458 - A Randomized Phase III Study Comparing Temporally-Modulated Pulsed Radiation Therapy (TMPRT) Versus Standard Radiation Therapy With Temozolomide for Adults With Newly Diagnosed MGMT-Unmethylated Glioblastoma (PHASE3, NOT_YET_RECRUITING): This phase III trial compares temporally-modulated pulsed radiation therapy versus standard radiation therapy in treating patients with newly diagnosed, IDH wildtype, MGMT-unmethylated glioblastoma. After completion of surgery, the standard of care for glioblastoma is radiation therapy. Radiation therapy uses high energy x-rays, particles, or radioactive seeds to kill cancer cells and shrink tumors. For older and frail patients, standard treatment also includes the chemotherapy drug temozolomide. Temozolomide is in a class of medications called alkylating agents. It works by damaging the cell's DNA and may kill tumor cells and slow down or stop tumor growth. Approximately 70% of glioblastoma patients have MGMT-unmethylated status. MGMT unmethylated tumors are less likely to respond to temozolomide chemotherapy, so there is more reliance on radiation therapy to kill the tumor cells. Recent clinical trials studying new therapies for MGMT-unmethylated glioblastoma have failed to improve outcomes over temozolomide. These recent studies also indicate that 80% of patients experience a decline in memory and thinking function after treatment. TMPRT differs from standard radiation therapy by delivering the same amount of radiation dose in 10-13 "pulses" with 3-minute breaks between pulses. TMPRT with temozolomide may work better than standard radiation therapy with temozolomide in increasing survival, as well as improving memory and thinking function in patients with newly diagnosed, IDH wildtype, MGMT-unmethylated glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07452458
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07422896 - A Phase I First-in-human Trial of Bvax (B-cell Vaccination) in Addition to Standard of Care Chemoradiotherapy for Newly Diagnosed Glioblastoma (PHASE1, NOT_YET_RECRUITING): The objectives of this phase I first-in-human trial are to evaluate safety, feasibility, and preliminary efficacy of an individualized Bvax vaccine in addition to standard of care chemoradiation in patients with newly diagnosed glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07422896
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07389278 - A Phase 1/2 Study of Pegylated Arginine Deiminase (ADI-PEG 20) Plus Radiotherapy (RT) and Temozolomide (TMZ) in Children, Adolescents, and Young Adults With Newly Diagnosed High-grade Glioma (HGG) (PHASE1, PHASE2, NOT_YET_RECRUITING): This is an open label, intra-patient dose escalation, to evaluate ADI-PEG 20, in combination with Temozolomide (TMZ) and radiation therapy (RT) in children, adolescents and young adult patients with newly diagnosed high grade glioma (HGG).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07389278
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07387666 - A Prospective, Open-label Phase 0 Single-center Study to Assess the Effect of Acetadote on Metabolism in Newly Diagnosed Glioblastoma (EARLY_PHASE1, NOT_YET_RECRUITING): This goal of this clinical trial is to evaluate how Acetadote affects metabolism in patients with glioblastoma. Drugs like Acetadote, which affect the level of damage in a cell (oxidative stress), may impact brain tumor metabolism and slow the growth of brain tumors. The investigators are evaluating how Acetadote affects glioblastoma metabolism by using MRI-based methods and by determining the changes in metabolism in brain tumor tissue resected from patients with a new diagnosis of glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07387666
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07386002 - A Phase II, Open-Label, Multicenter Study With a Safety Run-In to Evaluate the Safety, Tolerability, Efficacy, Pharmacokinetics and Pharmacodynamics of MT027 Administrated Intracerebroventricularly in Patients With Recurrent or Progressive Glioblastoma (WHO Grade 4) (PHASE2, NOT_YET_RECRUITING): This is a Phase II trial to evaluate the safety, tolerability, efficacy, and PK/ pharmacodynamic profiles of MT027 injected via ICV in participants with recurrent or progressive IDH-wildtype glioblastoma (WHO 2021 CNS Grade 4), who have previously received standard of care (SOC) therapy. Each participant will undergo screening, treatment (receiving MT027 at a dose of 3×10\^7 cells), safety follow-up, and long-term follow-up periods. MT027 will be given via ICV injection on Day 1 \& Day 15 of the first 28-day cycle. If the participant does not experience any unacceptable toxicities and disease progress in the first cycle, additional treatment may be continued bi-weekly in a 28-day cycle (Days 1 \& Day 15 of the 28-day cycle) until intolerable toxicity, disease progression, withdrawal from the study, or death, whichever comes first. After the last dose, there will be a safety follow-up period lasting for 1 year and then a long-term follow-up up to 15 years.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07386002
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=0 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07365280 - An Open-Label, Multicenter, Randomized Phase II Study to Evaluate the Efficacy and Safety of Personalized Dendritic Cell Vaccine ZSNeo-DC1.1 in Combination With Temozolomide as Adjuvant Therapy in Patients With Newly Diagnosed Glioblastoma After Surgery and Concurrent Chemoradiotherapy (PHASE2, NOT_YET_RECRUITING): This is a multicenter, open-label, randomized Phase II clinical study designed to evaluate the efficacy and safety of a personalized dendritic cell (DC) vaccine, ZSNeo-DC1.1, in combination with temozolomide (TMZ) as adjuvant therapy in patients with newly diagnosed glioblastoma (GBM). Eligible patients with histologically confirmed, IDH1/IDH2 wild-type newly diagnosed glioblastoma who have undergone tumor debulking surgery followed by standard concurrent chemoradiotherapy will be enrolled. After confirmation of tumor neoantigens and eligibility, patients will be randomized in a 1:1 ratio to receive either ZSNeo-DC1.1 in combination with TMZ or TMZ alone. The primary objective is to evaluate progression-free survival (PFS) as assessed by an Independent Radiological Review Committee (IRRC) according to RANO 2.0 criteria. Secondary objectives include overall survival (OS), survival rates, tumor response outcomes, and safety. Exploratory objectives include assessment of antigen-specific T-cell immune responses induced by ZSNeo-DC1.1.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07365280
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07356973 - Open-label Phase 2 Safety and Efficacy Trial of Irinotecan-ChemoSeed Administered Directly Into the Resection Margin in Patients With Surgically Resectable Glioblastoma (PHASE2, NOT_YET_RECRUITING): Part 1 (dose escalation, safety, and preliminary efficacy) Part 1 is a non-randomised, single-arm design in 12 participants with recurrent GBM suitable for maximal safe surgical resection. Part 1 will evaluate safety, determine the MTD of irinotecan-ChemoSeed and the RP2D (corresponding to coverage of as much of the resection cavity as possible, up to the MTD) and evaluate efficacy. All Part 1 participants will be administered irinotecan- ChemoSeed concurrent to Standard of Care (SoC) treatment. Part 1 dose- escalation will start at 72 mg of IRN Part 2, in 135 participants with newly diagnosed GBM suitable for maximal safe surgical resection, will assess the efficacy of irinotecan-ChemoSeed. The actual number of irinotecan-ChemoSeeds administered into the resected tumour margin of the tumour cavity after surgical resection will be at the discretion of the neurosurgical consultant up to the MTD, to cover as much of the resection cavity as possible. Participants will be randomised in a 2:1 ratio: * Arm 1: Irinotecan-ChemoSeed +SoC: Irinotecan-Chemoseeds administered into the resection margin following maximal safe surgical resection, with fractionated RT, concomitant and maintenance TMZ (based on Stupp protocol) starting 4 to 6 weeks after surgery per institution standard practice. * Arm 2: SoC treatment only: maximal safe surgical resection with fractionated RT, concomitant and maintenance TMZ (based on Stupp protocol) starting 4 to 6 weeks after surgery per institution standard practice.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07356973
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07347210 - Evaluation of UCPVax Vaccine +/- Pembrolizumab Combined With Standard Treatment as Adjuvant Therapy in Patients With Unmethylated MGMT Glioblastoma: a Randomized Phase II Trial (PHASE2, NOT_YET_RECRUITING): Glioblastomas (GBM) are the most frequent brain tumors and one of the most lethal adult cancers despite maximal multimodal therapy. Despite maximal safe resection followed by radiotherapy and temozolomide (TMZ) ± tumor-treating fields, median overall survival for newly diagnosed GBM remains around 18 months and long-term survival is rare, and recurrence is nearly universal. So, the development of new therapeutic strategies is a critical unmet need in GBM. Despite the limited success of anti-PD(L)-1 therapy, immunotherapy remains a promising option in GBM. Current challenge supports to develop combinatorial therapy approaches considering the particular immune tumor microenvironment in GBM. Anticancer vaccines have shown promising signs of efficacy in GBM but critical factors challenge their efficacy. CD4 T help is of major interest for cancer vaccine effectiveness and for immune checkpoint inhibitors success. We previously designed UCPVax a CD4 T helper-targeted cancer vaccine derived from telomerase (TERT), a very attractive GBM-associated antigen (Adotévi O, J Clin Oncol 2023 ; Laheurte C, Cell Report Med 2025). The induction of robust tumor reactive CD4 T cell response with UCPVax together with TMZ-mediated immune effects will promote recruitment of effectors immune cells into tumor bed creating a more suitable microenvironment for anti-PD-1 action. This is a proof-of-concept phase II trial to evaluate the efficacy of maintenance therapy evaluating UCPVax +/- pembrolizumab combined to standard treatment in newly diagnosed unmethylated MGMT glioblastoma. A translational research network will be implemented to better understand the therapeutic efficacy of this combination.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07347210
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07346144 - A Phase I/II Study of an AAV-1 Mediated Dual-Payload Gene Therapy in Patients With High Grade Glioma (PHASE1, PHASE2, NOT_YET_RECRUITING): The goal of this clinical trial is to first define the Safety and Optimal Biological Dose (OBD) of study drug TGX-007 and to then further investigate the safety and efficacy in patients with newly diagnosed or recurrent Glioblastoma. TGX-007 is a gene therapy drug delivered by a harmless adeno-associated virus (AAV) vector which delivers two combined therapeutic payloads to enable killing of proliferative cells and activation of an anti-tumour immune response. One is herpes simplex virus thymidine kinase (HSV-tk), which converts the pro-drug valaciclovir into an active drug that can kill tumour cells and the other is interleukin 12 (IL-12), which activates the body's immune system to recognise and fight the tumour. Patients newly diagnosed with glioblastoma suitable for standard of care surgery and chemoradiotherapy or patients with recurrent glioblastoma suitable for further surgery may be eligible for the study. Patients will receive TGX-007 by a direct intratumoural injection and will then take the pro-drug valacyclovir orally for up to 21 days before proceeding to standard of care surgery. The study is split into two phases. Phase I will treat patients at different dose levels of TGX-007 to identify the Optimal Biological Dose that will be used to further expand the study into Phase II. Phase II will expand the number of patients treated at the selected OBD to investigate how effective TGX-007 is at treating newly diagnosed and recurrent GBM. Approximately 68 people aged 18-70 will take part in the study.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07346144
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07343986 - Phase I Clinical Trial of Anti-CD3 × Anti-EGFR Bispecific-armed T Cells (EGFR BATs) and Low-Intensity Focused Ultrasound (LIFU) Blood-brain Barrier Opening in Patients With MGMT Unmethylated Glioblastoma (GBM) (PHASE1, RECRUITING): This is a phase 1 study for patients with newly diagnosed MGMT unmethylated IDH wild-type glioblastoma utilizing autologous activated T-cells armed with bispecific antibody (EGFR-BATs) that recognize the tumor. The investigators hypothesized that the combination of infusions of EGFR BATs and low-intensity focused ultrasound would induce blood-brain barrier opening and increase the permeability of the adoptive immunotherapy. The investigators will radiolabel the EGFR BATs with 89Zr-oxine for subsequent PET imaging to determine the trafficking and uptake of this approach. There is a concern that several infusions of EGFR BATs before BBB opening could change the immune tumor microenvironment that would not allow a permissive BBB after LIFU. Therefore, Arm A will have two LIFU with BBB opening after the 4th and the 8th infusion, and Arm B will have three LIFU with BBB opening after the 1st, 4th, and 8th infusions. This study will determine the safety and feasibility of the combination of low-intensity focused ultrasound (LIFU) with microbubbles BBB opening and EGFR BATs and the access of the adoptive cell immunotherapy to the tumor microenvironment to inform future studies.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07343986
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07284628 - A Phase II Drug Repurposing Trial of Vortioxetine for the Treatment of Patients With Newly Diagnosed Glioblastoma (PHASE2, NOT_YET_RECRUITING): There is a very urgent need to improve on the currently limited treatment options for patients with glioblastoma. Despite extensive knowledge on the molecular pathogenesis of glioblastoma obtained through genomic, transcriptional and proteomic profiling, targeted therapy efforts have not yielded major advances, likely because of interindividual and intraindividual tumor heterogeneity and redundant oncogenic pathway activation. Accordingly, there is a strong rationale to approach the challenge of glioblastoma from a different angle, e.g., by ex vivo drug sensitivity profiling which is agnostic to the molecular profile of a tumor. This approach that we have termed "pharmacoscopy", has previously been explored in liquid cancers and probably led to improved patient outcomes. Using pharmacoscopy, the antidepressant drug, vortioxetine, has been identified as a lead candidate for further exploration in patients with glioblastoma. Vortioxetine also demonstrated synergistic anti-glioma activity in combination with temozolomide or lomustine. The ReVoGlio trial aims at demonstrating that vortioxetine, a drug selected based on ex vivo drug profiling (pharmacoscopy), is of benefit for patients with newly diagnosed glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07284628
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07284069 - Phase 0/1 Randomized Clinical Trial of SENIcapoc and PERAmpanel Mono- and Combination Therapy of Newly Diagnosed Glioblastoma (EARLY_PHASE1, RECRUITING): Glioblastoma is the most common and aggressive form of brain cancer in adults. Despite surgery, radiotherapy, and chemotherapy, most patients only live about one year after diagnosis. There is an urgent need for new and better treatments. Recent research has shown that glioblastoma cancer cells communicate with surrounding brain cells through electrical signals that help the tumor grow and resist treatment. Two existing drugs, perampanel (used for epilepsy) and senicapoc (previously tested for blood disorders), may block these harmful signals. Laboratory studies suggest that combining these two drugs could slow tumor growth and make cancer cells more sensitive to standard therapy. The SENIPERA trial will test whether perampanel and senicapoc, alone and in combination, are safe and well tolerated when added to standard treatment for newly diagnosed glioblastoma. The study will also measure how well these drugs reach the brain and tumor, and how they affect tumor biology. The study has two parts: Part A: Tests different doses of senicapoc alone to find the maximum tolerable dose. Part B: Randomly assigns patients to receive either perampanel alone or perampanel together with senicapoc. Participants will all receive standard therapy, including surgery, radiochemotherapy, and adjuvant chemotherapy. During surgery, small samples of tumor and fluid will be collected safely to study how the drugs act in the body and how tumor cells respond. Participants will be closely monitored for side effects and followed with regular clinical visits and MRI scans. The trial will take place at Aarhus University Hospital, Denmark, from February 2026 to November 2028 and will enroll 27-36 adult patients. The study aims to identify safe and biologically active treatment combinations that could be tested in larger trials to improve future glioblastoma care.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07284069
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07225621 - Multi-Center, Randomized, Double-Blind, Placebo-Controlled Trial Comparing Standard of Care Adjuvant Temozolomide With or Without 5-Aminolevulinic Acid (5-ALA) With Concomitant Low Intensity Diffuse Ultrasound (LIDU) Sonodynamic Therapy (SDT) System In Patients With Newly Diagnosed Glioblastoma After Completion of Chemoradiotherapy (PHASE2, RECRUITING): The purpose of this research is to test an investigational device using ultrasound along with an investigational drug to see if it is useful in treating glioblastoma following standard of care therapy surgery and chemoradiation. This study is evaluating an experimental treatment for glioblastoma that uses an investigational drug (5-ALA) combined with a non-invasive ultrasound device (LIDU) to target tumor cells. Patients meeting the entry requirements to be in the study, will be equally randomly assigned to receive the study device plus the active study drug plus active ultrasound, or to a "sham" procedure where the ultrasound is not being activated and the study drug is a placebo (looks the same but does not contain active drug). Neither the patient or the investigator will know who is in the active group or not. Both groups will continue to receive the standard therapy of oral Temozolomide.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07225621
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_chemoradiation, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07195591 - Randomized Study of Resection and GammaTile® Followed by Concurrent External Beam Radiation Therapy (EBRT) and Temozolomide (TMZ) and Adjuvant TMZ Versus Standard of Care in Newly Diagnosed Glioblastoma (GBM) (PHASE3, RECRUITING): This is a Phase 3 prospective, randomized, superiority, open-label, multi-site study. The overview of this study is as follows: * A Screening/Baseline Period of 21 days. During this time, patients will be randomized into a 1:2 allocation of Arm A:Arm B. * A Perioperative/Operative Phase where patients will undergo tumor resection (Arm A) or tumor resection plus GammaTile implantation (Arm B). * An EBRT Prior to Start Period. This occurs within 10 business days prior to EBRT and Concurrent TMZ Phase. * An EBRT and Concurrent TMZ Phase, which will begin 30 ±10 days post-surgery. EBRT (30 fractions) and TMZ will be administered up to 5 days a week for 6 weeks in Arm A, and EBRT (20 fractions) and TMZ will be administered for up to 5 days a week for 4 weeks in Arm B. TMZ will be administered at a dose of 75 mg/m2/day orally for each Arm. * An Adjuvant TMZ Phase, which begins 28 ±7 days following the EBRT and Concurrent TMZ Phase, and is comprised of six 28-day cycles. TMZ (150-200 mg/m2/day orally) will be administered for the first 5 days of each 28-day cycle for each Arm. Tumor treating fields are allowed but are not mandated during this phase. Up to 6 additional cycles (for a total of 12) can be completed at the discretion of the Investigator. * An Early Discontinuation/Follow-Up Phase will occur 28 ±7 days after completion of Cycle 6 of the Adjuvant TMZ Phase, regardless of the total number of cycles completed or any delays in cycle start. If fewer than six cycles are completed, the first follow-up assessment will occur 28 ±7 days after the last administered dose of adjuvant TMZ. If patient has a qualifying event requiring entrance to Early Discontinuation Phase, the first follow-up assessment will occur as soon as feasible, but within 28 days. For any unscheduled visits, data collected should be documented in the case report form (CRF) and must include, but are not limited to, safety evaluations, survival status, and disease status.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07195591
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07193654 - Stupp Regimen Combined With Intrathecal Injection of Thiotepa for the Treatment of Glioblastoma With Ventricular Invasion or Meningeal Metastasis：a Prospective, Single-Arm, Exploratory Study (PHASE2, RECRUITING): The goal of this clinical trial is to learn if a combined treatment approach can treat glioblastoma (GBM) with ventricular invasion or meningeal metastasis in adults. The main questions it aims to answer are: Does the combined treatment of radical radiotherapy, the Stupp regimen (oral temozolomide), and intrathecal injection of thiotepa improve progression-free survival compared to standard treatment alone? Does the combined treatment improve overall survival compared to standard treatment alone? Participants will: * Undergo maximal surgical resection of the tumor； * Receive radical radiotherapy； * Take oral temozolomide according to the Stupp regimen； * Receive intrathecal injections of thiotepa。
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07193654
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07185880 - A Phase 1 Dose Escalation and Randomized Expansion Study of the Safety, Tolerability, and Pharmacokinetics of MT-125 Monotherapy With Radiation in Patients With Newly Diagnosed Glioblastoma (PHASE1, NOT_YET_RECRUITING): The purpose of the study is to determine the recommended dose and further understand the safety of MT-125 in participants who have been diagnosed with glioblastoma, a primary brain tumor, when administered in combination with your standard of care treatment. Initially, participants with newly diagnosed glioblastoma will be given different doses of MT-125 in combination with radiotherapy (RT) with the goal of identifying the highest tolerated dose. Up to 36 people with glioblastoma who are at least18 years old are being invited to join this study. MT-125 is a type of study treatment which acts on cancer cells in the brain to destroy them. It will be administered on the same day as your standard of care radiotherapy because it is also designed to help radiotherapy work better. However, this is the first time MT-125 will be studied in humans. Therefore, the use is considered investigational. If you would like more details about MT-125 in glioblastoma participants, please ask the Study Doctor. You will be among the first participants with glioblastoma to receive this study treatment. Its safety and effectiveness have not yet been established in humans. Thus, we do not know whether it will work for you. Your condition may improve, may get worse, or there may be no change. The selected participant population-individuals newly diagnosed with histologically and/or molecularly confirmed IDH wild-type, MGMT-unmethylated glioblastoma-represents those least likely to experience safety concerns or adverse events related to the study treatment, and most likely to derive therapeutic benefit. There are certain tests/questions you must complete to find out if you meet the requirements to be in the study. If you do not meet these requirements, you cannot take part in the study. If this happens, you can talk to your Study Doctor about other options.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07185880
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07143812 - Clinical Research of Suicide Gene Expressing Allogenic Bone Marrow Derived Mesenchymal Stem Cells(MSC11FCD) in Patients With Newly Diagnosed Glioblastoma (PHASE1, RECRUITING): This is a phase I clinical trial evaluating the safety, tolerability, and maximum tolerated dose of MSC11FCD, an investigational allogeneic bone marrow-derived mesenchymal stem cell therapy expressing a suicide gene, in patients with newly diagnosed glioblastoma. The investigational product is administered intratumorally following surgical resection. This study aims to explore whether MSC11FCD can provide a targeted, localized treatment option during the postsurgical period, potentially addressing residual tumor cells and reducing early recurrence.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07143812
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07141732 - Pilot Prospective Single-center Non-comparative Study: Combined Treatment of Patients With Newly Diagnosed Glioblastoma Using the Xoft® Axxent® Electronic Brachytherapy (eBx®) System for Intraoperative Balloon Electronic Brachytherapy (PHASE1, RECRUITING): Glioblastoma is the most aggressive primary brain tumor due to its highly infiltrative growth pattern, strong proliferative potential, and multiple mechanisms of resistance to treatment . Based on results from multicenter studies, English oncologist Roger Stupp proposed in 2005 a new treatment approach involving initial tumor resection followed by conformal external beam radiation therapy combined with temozolomide, plus subsequent cycles of monochemotherapy with this drug. This approach extended median survival by only 2 months, yet remains the standard of care due to lack of better alternatives. Consequently, recent protocols for malignant CNS tumors in Russia and internationally recommend prioritizing clinical trial enrollment over "standard" treatment. Numerous studies demonstrate that the extent of resection of contrast-enhancing GB volume on MRI positively correlates with progression-free and overall survival. This is explained by the fact that adjuvant chemoradiation methods and the body's immune responses show efficacy only with small residual tumor volumes. The interval between surgery and adjuvant therapy negatively correlates with survival outcomes, potentially because the mitotic cycle of GB stem cells lasts only 24 hours. From this perspective, intraoperative radiation therapy (IORT) may improve treatment results. Attempts to use various IORT technologies for malignant brain gliomas span several decades. Some studies reported better survival with IORT compared to controls, but most involved small patient groups without reliable resection control or dosimetric assessment due to technological limitations. Early IORT methods used bulky linear accelerators producing high-energy electron beams. With portable systems, renewed interest emerged first in breast cancer, then neurosurgery. Neuroimaging and software now enable precise treatment planning. Bensaleh S. et al. evaluated balloon brachytherapy (MammoSite®) for early breast cancer in 2009. The device featured a dual-lumen catheter with a balloon inserted into the resection cavity. After contrast inflation and CT planning, 192Ir delivered 34 Gy in 10 fractions over 5 days to 1 cm depth. While comparable to conventional radiotherapy in 3-5 year survival, the 16% infection rate from prolonged implantation was a major drawback. A case report described using a similar breast cancer system (Contura balloon applicator) for recurrent malignant glioma in a 47-year-old patient. A single 20 Gy fraction showed no complications at 6-month follow-up. The Zeiss INTRABEAM system uses a miniature 50 kV linear accelerator with rigid spherical applicators producing low-energy x-rays for high surface doses with limited penetration. The 2018 INTRAGO phase I/II trial by Giordano et al. evaluated dose escalation (20→40 Gy) in 15 newly diagnosed GB patients. No complications (wound healing issues, bleeding, ischemia, or radionecrosis requiring surgery) occurred. Median PFS was 17.7 months (95% CI 9.7-25.9) in protocol-compliant patients, with distant progression remaining challenging. A recent advancement is electronic brachytherapy using the Xoft Axxent eBx System, combining a 50 kV x-ray source with a silicone balloon applicator conforming to resection cavities. Initially successful in breast and gynecologic cancers, its application expanded to neuro-oncology. In 2016, the European Medical Center (EMC) initiated a pilot study using Axxent eBx for recurrent GB post-standard chemoradiation. Twenty-nine patients received 20 Gy to the balloon surface after maximal safe resection. Median OS was 28.7 months (range 14-104) from first surgery. In patients with ≤2.5 cm³ residual tumor (n=16), median local PFS was 14.5 months (8-94), with 6- and 12-month PFS rates of 68.9% and 31% respectively. One grade 3 radionecrosis case occurred (CTCAE), with no infections or CSF leaks. Study Rationale: * Demonstrated survival benefits with gross-total resection of contrast-enhancing tumor * Negative survival impact of delayed adjuvant therapy initiation * Promising preliminary results of resection plus electronic brachytherapy in recurrent GB from EMC research This is a pilot, prospective, single-center, non-comparative study. Patients (N=15) with newly diagnosed glioblastoma will undergo intraoperative balloon-based electronic brachytherapy (IOBT) using the Xoft® Axxent® eBx® System immediately following gross total resection of the contrast-enhancing tumor. A single fractional dose of 20 Gy will be delivered to the balloon surface. Subsequently, patients will receive standard chemoradiotherapy according to the Stupp protocol (2005): * Concurrent phase (initiated 2-4 weeks postoperatively): * Radiotherapy: Conformal external beam radiation therapy (EBRT) to a total dose of 60 Gy (2 Gy/fraction over 6 weeks). * Chemotherapy: Daily oral temozolomide (75 mg/m²) during EBRT. * Adjuvant phase: * Monotherapy: 6-12 cycles (6-12 months) of adjuvant temozolomide (150-200 mg/m², days 1-5 of each 2
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07141732
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: newly_diagnosed
- NCT07138001 - A Randomized, Controlled, Open-label, Multicenter Phase 2 Clinical Trial to Evaluate the Efficacy and Safety of KH617 in Combination With Temozolomide Versus Investigator's Choice Treatment or KH617 Monotherapy for Recurrent Glioblastoma (PHASE2, NOT_YET_RECRUITING): To evaluate the efficacy and safety of KH617 for injection in combination with temozolomide versus investigator's choice therapy or KH617 monotherapy for recurrent glioblastoma
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07138001
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07130149 - Clinical Investigation of Sonodynamic Therapy in Conjunction With Chemoradiotherapy for Glioblastoma Management (PHASE2, ENROLLING_BY_INVITATION): This Phase II trial tests if sonodynamic therapy (SDT)-a non-invasive treatment using ultrasound to activate a cancer-killing drug-improves outcomes for newly diagnosed glioblastoma patients. Who? 230 adults (\<75 years) with confirmed glioblastoma, adequate organ function, no major health issues. Groups: Test Group: SDT + standard therapy (radiation, chemo, bevacizumab). Control Group: Standard therapy alone. Procedure: SDT uses the drug Hiporfin® followed by focused ultrasound sessions. Patients avoid sunlight for 1 month. Study Duration: Treatment: \~6-8 weeks. Follow-up: 24 months (monthly MRIs). Key Goal: Compare progression-free survival (time until tumor worsens) between groups. Secondary goals: overall survival, safety.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; limited-enrollment.
  Source: https://clinicaltrials.gov/study/NCT07130149
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07091864 - Phase II Randomized Trial Of Glucose Monitoring In Glioblastoma (NA, RECRUITING): This clinical trial studies whether continuous glucose monitoring (CGM) can be used to help patients with glioblastoma manage their blood sugar (glucose) levels and improve survival. Glioblastoma is the most common malignant primary brain tumor in adults, with an average survival time of approximately 15-18 months despite therapy. Studies have shown that having a higher-than-normal amount of glucose in the blood (hyperglycemia) during radiation therapy is associated with poorer survival outcomes in glioblastoma patients. Hyperglycemia in glioblastoma patients is often driven by steroids that are commonly used during treatment. CGM uses a device that places a sensor under the skin that monitors glucose levels at regular intervals, providing real-time, or near real-time, glucose information. This can help to identify when a patient has changes in their glucose levels so they may receive necessary interventions or medications sooner. CGM may be an effective way for glioblastoma patients to manage their glucose levels, which may improve survival.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07091864
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07047066 - A Phase II Clinical Study to Evaluate the Efficacy and Safety of Flazoparib Combined With Temozolomide After the Completion of Standard Concurrent Chemoradiotherapy (CCRT) in Newly Diagnosed Glioblastoma (PHASE2, NOT_YET_RECRUITING): A Phase II clinical study is planned to evaluate the efficacy and safety of fluzoparib combined with temozolomide in newly diagnosed glioblastoma patients after completing standard concurrent chemoradiotherapy (CCRT), explore the effectiveness and safety of this regimen, and find a better treatment option for glioblastoma patients
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07047066
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07029100 - Feasibility of ORGAnoids in Routine Clinical Practice for Molecular Analysis of the GLIOvascular Niche in Patients With Primary Brain Tumors. (NA, NOT_YET_RECRUITING): The main goal of ORGA-GLIO trial is to establish the feasibility in routine clinical practice of ex-vivo organoid cultures composed of tumor cells within their microenvironment (glioblastoma organoid - GBO) and intra- and peri-tumoral blood vessels (blood vessel organoid - BVO), derived from perioperative samples obtained during complete or partial surgical resection in patients with newly diagnosed glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07029100
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06973096 - Phase 1 Open-label Study Evaluating the Safety of CART-EGFR-IL13Rα2 Cells in Patients With Newly Diagnosed, EGFR-Amplified, MGMT-unmethylated Glioblastoma Following Completion of Initial Radiotherapy (PHASE1, RECRUITING): This is an open-label phase 1 study to assess the safety, feasibility, pharmacokinetics and preliminary efficacy of autologous T cells co-expressing two CARs targeting the cryptic EGFR epitope 806 and IL3Ra2 (referred to as "CART-EGFR-IL13Ra2 cells"). Patients with newly diagnosed, EGFR-amplified, MGMT-unmethylated glioblastoma who have undergone maximal safe surgical resection will be approached for initial study participation. A two-step screening/eligibility process will be utilized. Following informed consent, subjects who meet Step #1 Eligibility Criteria will remain on study and complete a course of radiotherapy (60 Gy) without temozolomide as per their routine cancer care. If there is no overt evidence of disease recurrence/progression following radiotherapy, additional screening tests/procedures will be performed. Subjects who then meet Step #2 Eligibility Criteria will undergo apheresis collection to initiate cell product manufacturing and surgical placement of a CSF-Ventricular Reservoir to allow for intracerebroventricular injection of the CART-EGFR-IL13Ra2 cells. All subjects will receive a single fixed dose of CART-EGFR-IL13Ra2 cells on Day 0 via intracerebroventricular delivery.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06973096
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06936046 - Enhanced Adjuvant Therapy for Newly Diagnosed Glioblastoma With Partial Surgical Resection or Short-term Progression: a Bayesian Adaptive Randomized Phase II Study (PHASE2, RECRUITING): This study is a prospective Bayesian adaptive randomized phase II clinical trial of enhanced adjuvant therapy for newly diagnosed glioblastoma with partial surgical resection or short-term progression. The Stupp regimen is the standard treatment regimen (control group), while the experimental group receives enhanced treatment by combining different drugs or increasing the radiation dose based on the Stupp standard treatment regimen. Participants will undergo screening and evaluation according to the inclusion and exclusion criteria of the protocol, within 28 days prior to randomization. Patients who agree to participate in this study will sign an informed consent form (ICF) prior to the screening process. After completing all screening activities, those who meet the criteria can start receiving study treatment. Based on sample size estimation, a total of 210 patients are planned to be enrolled. Among the first 28 patients, an average of 7 patients will be allocated to each group for initial randomization to ensure the balance of each group in the early stages of the trial. Starting from the 29th patient, the 12-month PFS rate will be re estimated for every 15 patients enrolled, and the subsequent randomization probability will be calculated based on the observed data. On the first day of self adjuvant therapy, the PD-1/VEGF bispecific group received intravenous administration of PD-1/VEGF bispecific antibody 20mg/kg treatment, with 21 days per cycle, is expected to be administered for a total of 8 cycles. The PD-1/CTLA-4 dual antibody group received intravenous infusion of 6mg/kg PD-1/CTLA-4 dual antibody once on the first day of self adjuvant therapy, with 14 days per cycle. It is expected to be administered for a total of 12 cycles. The dose adjusted Stupp regimen group (mStupp) administered PGTV locally to residual or short-term recurrent lesions after surgery 66Gy/30Gy high-dose irradiation, PTV1 60Gy/30F in high-risk areas around the tumor bed, and 54Gy/30F radiotherapy in low-risk areas. Each group will have weekly blood routine, liver and kidney function, myocardial enzyme spectrum, thyroid function, electrocardiogram, and head MR every 4 weeks to evaluate the efficacy and toxic side effects. Follow up observation will be conducted. The study will start on January 1, 2025 and end on December 31, 2027, to explore the efficacy of enhanced adjuvant therapy for newly diagnosed glioblastoma with partial surgical resection or short-term progression.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06936046
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06831526 - A Window-of-opportunity Early Phase I Randomized Study of Neoadjuvant Chemoradiotherapy With or Without Concurrent Azeliragon in Patients With Newly Diagnosed Glioblastoma (EARLY_PHASE1, RECRUITING): Preclinical data have demonstrated the combination of azeliragon, a RAGE inhibitor, with radiation therapy (RT) can effectively reduce immune-suppressive myeloid cells and restore T-cell activation to improve tumor control in murine glioma models. Ongoing clinical studies of azeliragon with RT alone and RT plus temozolomide (TMZ) to treat patients with newly diagnosed glioblastoma (GBM) have demonstrated safety and tolerability. The purpose of this window-of-opportunity study is to validate that the combination of azeliragon with RT and TMZ would modulate immune-suppressive myeloid and T cells in the tumor microenvironment in patients with GBM.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06831526
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06816927 - A Multi-Center, Randomized, Phase 2 Trial of Glioblastoma Immunotherapy Advancement With Nivolumab and Relatlimab (GIANT) (PHASE2, RECRUITING): GIANT is an open-label, multi-center, randomized, perioperative (neoadjuvant followed by adjuvant), phase 2 trial with a safety lead-in phase to investigate the feasibility, safety and tolerability, and establish the biological activity of nivolumab with or without relatlimab in patients with isocitrate dehydrogenase (IDH) wildtype newly diagnosed glioblastoma (ndGBM).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06816927
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06805305 - Randomized Study of DOC1021 Dendritic Cell Immunotherapy in Combination With Standard of Care for Newly Diagnosed Adult Glioblastoma (PHASE2, RECRUITING): The goal of this clinical trial is to learn if DOC1021 + pIFN alongside standard of care (SOC) will improve survival in adult patients newly diagnosed with glioblastoma (IDH-wt). It will also evaluate the safety of DOC1021 + pIFN. Researchers will compare DOC1021 dendritic cell immunotherapy regimen added to SOC compared to SOC treatment alone. Participants in the DOC1021 + pIFN + SOC arm will: * Take filgrastim subcutaneously x 5 doses and subsequently undergo a leukapheresis collection * Undergo ultrasound guided perinodal DOC1021 injections every 2 weeks for a total of 3 doses * Receive subcutaneous pIFN injections weekly for a total of 6 doses in parallel with the DOC1021 injections Both arms of the trial will: \- Visit the clinic regularly to assess quality of life, symptoms, medication use, imaging, bloodwork, and to receive SOC treatment with surgery, temozolomide chemotherapy and radiation
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06805305
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: newly_diagnosed
- NCT06780592 - The Efficacy of Vebreltinib Combined With Temozolomide for Glioblastoma (GBM) After Surgery: a Study Protocol for a Prospective, Open-label ,Multi-center, Randomized, Controlled Trial in China (PHASE2, NOT_YET_RECRUITING): The purpose of this study is to explore the effects of Vebreltinib in primary glioblastoma patients receiving a combination therapy of chemotherapy (temozolomidel) and MET-TKI.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06780592
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06740955 - A Randomized, Open, Controlled, Multi-center Clinical Trial of Hypofractionated Postoperative Radiotherapy for Adult Glioblastoma (NA, RECRUITING): This study was a multicenter, open-label, randomized, controlled, phase Ⅲ clinical trial to evaluate the efficacy and safety of hypofractionated concurrent radiotherapy followed by sequential temozolomide after surgery in patients with newly diagnosed glioblastoma. A total of 420 subjects were enrolled in this study, randomized 1:1. According to the changes in overall survival time after postoperative concurrent chemoradiotherapy with different radiation doses, the stratification factors included the extent of surgical resection (total resection vs subtotal resection); The time of postoperative concurrent chemoradiotherapy (less than 28 days or more than 28 days); MGMT promoter methylation expression (positive or negative). The study design was as follows: Participants were required to undergo a screening period within 14 days before randomization to determine eligibility. Subjects who met the inclusion criteria were randomly divided into two groups at a 1:1 ratio: trial group, hypofractionated concurrent chemoradiotherapy followed by at least 6 cycles of adjuvant temozolomide; The control group was treated with the existing standardized treatment (standard dose of concurrent chemoradiotherapy and at least 6 cycles of temozolomide adjuvant chemotherapy). Experimental group: subjects randomly assigned to the experimental group were required to start treatment within 7 working days. The experimental group received hypofractionated radiotherapy with a total dose of 52.5Gy, 3.5 Gy/ fraction, 15 fractions, 5 fractions per week, and temozolomide was given for 21 days. Sequential temozolomide chemotherapy was started 4 weeks after the end of chemoradiotherapy. Sequential chemotherapy was given 5 days before each 28-day cycle. During the study period, the experimental group was required to complete the vital signs, physical examination, laboratory examination and other examinations within the specified period. After randomization, the experimental group underwent radiologic response assessments (or as deemed necessary by the investigator based on clinical symptoms) and QOLs at the end of radiotherapy, 3-4 weeks after the end of radiotherapy, and every 12 weeks (±7 days). Radiologic response assessments required plain and contrast-enhanced magnetic resonance imaging. If there were residual lesions after surgery, measurable lesions were evaluated according to RANO standard case criteria. Control group: subjects randomly assigned to the experimental group were treated within 7 working days. The control group received conventional fractionated radiotherapy with a dose of 60Gy, 2Gy per fraction, 30 fractions, 5 fractions per week, and temozolomide was given for a total of 42 days. Sequential temozolomide chemotherapy was started 4 weeks after the end of chemoradiotherapy. Sequential chemotherapy was given 5 days before each 28-day cycle. During the study period, the experimental group was required to complete the vital signs, physical examination, laboratory examination and other examinations within the specified period. After randomization, the experimental group underwent radiologic response assessments (or as deemed necessary by the investigator based on clinical symptoms) and QOLs at the end of radiotherapy, 3-4 weeks after the end of radiotherapy, and every 12 weeks (±7 days). Radiologic response assessments required plain and contrast-enhanced magnetic resonance imaging. Measurable lesions assessed according to RANO criteria were required if residual lesions were present after surgery.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06740955
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06649851 - A Phase 2 Randomized Open-Label Pilot Study of Granulocyte Colony Stimulating Factor (G-CSF) to Preserve Brain Structure and Function Following Standard Chemoradiation in Patients With Newly Diagnosed MGMT-Methylated Glioblastoma (PHASE2, RECRUITING): This research study involves the study of granulocyte colony stimulating factor (G-CSF) in patients with MGMT-methylated glioblastoma multiforme (GBM) that are undergoing standard chemoradiation. The study aims to evaluate G-CSF's effects on brain health and cognitive function. The name of the study drugs involved in this study are: * G-CSF (also called Filgrastim) * Temozolomide (TMZ), a standard of care chemotherapy drug
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06649851
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06595186 - A Multicenter, Single Arm, Open-label, Dose-escalation Phase 2 Study of JK-1201I Combined with Adjuvant Temozolomide in Patients with Newly Diagnosed Glioblastoma Multiforme (GBM) After Surgery and Concomitant Radio-chemotherapy (PHASE2, RECRUITING): This study was designed to evaluate the safety, tolerability, efficacy and pharmacokinetics of JK-1201I combined with adjuvant temozolomide in patients with newly diagnosed glioblastoma multiforme after surgery and concomitant radio-chemotherapy.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06595186
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: newly_diagnosed
- NCT06556563 - A Phase 3, Randomized, Double-Blind, Placebo-Controlled Study of Optune® (TTFields, 200 kHz) Concomitant With Maintenance Temozolomide and Pembrolizumab Versus Optune® Concomitant With Maintenance Temozolomide and Placebo for the Treatment of Newly Diagnosed Glioblastoma (EF-41/KEYNOTE D58). (PHASE3, RECRUITING): This is a multicenter, two-arm, randomized, double-blind, placebo-controlled study of Optune® (Tumor Treating Fields at 200 kHz) together with maintenance Temozolomide (TMZ) chemotherapy agent and pembrolizumab compared to Optune® together with maintenance TMZ and placebo in newly diagnosed Glioblastoma (GBM) patients. The primary objective of the study is to evaluate the Overall Survival (OS).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06556563
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs True (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: post_chemoradiation, Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06533163 - Low-Intensity Oscillatory Magnetic Therapy in Patients With Newly Diagnosed Glioblastoma Multiforme (GBM) - An Exposure-time Escalation Pilot Trial (NA, RECRUITING): The clinical investigation is a non-randomized, multicenter, open-label, prospective, exposure-time escalation clinical investigation. The clinical investigation is designed to assess the clinical safety and performance of the Oncomagnetic Device.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06533163
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06524063 - Phase I Clinical Study of Targeted Survivin DC Cell Injection for the Treatment of Newly Diagnosed Primary Glioblastoma Multiforme (GBM) (PHASE1, NOT_YET_RECRUITING): Primary Objective: To evaluate the safety and tolerability of targeted Survivin DC cell injection for postoperative treatment of newly diagnosed primary glioblastoma multiforme. Secondary Objectives: Utilize progression-free survival (PFS) and overall survival (OS) to preliminarily assess the effectiveness of targeted Survivin DC cell injection for postoperative treatment of newly diagnosed primary glioblastoma multiforme in China. Evaluate the immunological effects of targeted Survivin DC cell injection. Explore the impact of targeted Survivin DC cell injection on human DC cell activity and in vivo processes. Patients will undergo a combined treatment of radiotherapy and temozolomide (TMZ) for a duration of 6 weeks, with concurrent chemotherapy. After completing this phase, there will be a 4-week interval (28 days) before entering multiple cycles of adjuvant TMZ chemotherapy. Each cycle will last 28 days, involving daily oral administration of temozolomide at a dose of 150-200mg/m2 for 5 consecutive days, followed by a 23-day drug-free period. This entire cycle will be repeated every 28 days. Nine days after completing the standard 6-week concurrent chemoradiotherapy, targeted Survivin DC cell injections will be administered. The injections will be given on days 0, 14, and 28. The administration will involve both intradermal (ID) and intravenous (IV) routes. Four hours before the administration, the injection sites will be pre-treated with lidocaine cream. The injection procedures will be conducted sequentially, starting with ID injection. After completing the ID injection, a 30-minute observation will be conducted. If no adverse reactions are observed, IV infusion will be initiated. Both IV infusion and ID injection will be performed on the same side. Intradermal Injection: Draw 1ml of cell suspension with a 1ml syringe, and the remaining cell product will be stored at 2-8℃. Administer the drug immediately after preparation. Intravenous Infusion: Before administration, infuse 20ml of normal saline through IV.Extract 25ml of normal saline, dilute the remaining cell product (5ml), and administer it through IV infusion. Control the room temperature during infusion and complete it within 30 minutes. After administration, inject 50ml of normal saline into the cell bag to ensure all cell products are returned to the patient's body.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06524063
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06512311 - Personalized Targeted Glioblastoma Therapies by ex Vivo Drug Screening: Advanced Brain Tumor TheRApy Clinical Trial (ATTRACT) (NA, RECRUITING): Patient derived cell line (PDC) -based drug screening will be applied to formulate a personalized treatment approach.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06512311
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06504381 - A Phase I/IIa Study to Evaluate the Efficacy of DB107-RRV (Formerly Toca511), Administered to Subjects at Time of Resection and Intravenously Thereafter, in Combination With DB107-FC (Formerly Toca FC) and Radiation Therapy or DB107-FC, Temozolomide (TMZ) and Radiation Therapy in Patients With Newly Diagnosed High Grade Glioma (PHASE1, PHASE2, RECRUITING): This is a multicenter, open-label study of DB107-RRV (formerly Toca 511) and DB107-FC (formerly Toca FC) when administered following surgical resection in newly diagnosed High Grade Glioma (HGG) patients. The study is designed to evaluate whether treatment with DB107-RRV in combination with DB107-FC when added to standard of care provides clinical benefit to newly diagnosed HGG when compared to historical performance previously determined in well controlled clinical trials published in the peer reviewed literature. This study is going to be conducted in newly diagnosed HGG patients receiving with maximum surgical resection treatment followed by radiation and temozolomide treatment using the established Stupp Protocol for O6-methylguanine-DNA methyl-transferase (MGMT) methylated patients or radiation therapy for MGMT unmethylated patients.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06504381
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06477939 - Phase III Randomized Study of Adding or Not Liposomal Transcrocetin (L-TC) With Concomitant HypoFractionated Radiation ThErapy and TEmozolomide in Newly Diagnosed GLioblastoma (GBM) Patients to Evaluate Efficacy and Safety (PHASE3, NOT_YET_RECRUITING): This is phase III randomized, multicenter study adding or not intra-venous Liposomal Trasncrocetin (L-TC) to hypofractionated radiotherapy and concomitant Temozolomide followed by adjuvant Temozolomide in patients with histologically confirmed diagnosis of glioblastoma (GBM).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06477939
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06448286 - PH Weighted Chemical Exchange Saturation Transfer Based Surgical Resections of Glioblastoma (PHASE3, NOT_YET_RECRUITING): This phase III trial compares pH weighted chemical exchange saturation transfer (CEST) magnetic resonance imaging (MRI)-based surgical resections to standard of care surgical resections for the treatment of patients with glioblastoma. Standard of care therapy for glioblastoma is surgery to remove tumor tissue that enhances on standard MRI imaging, however, it has been shown that significant tumor burden exists in the region around the tumor tissue that does not enhance with standard MRI. MRI is a procedure in which radio waves and a powerful magnet linked to a computer are used to create detailed pictures of areas inside the body. These pictures can show the difference between normal and tumor tissue. CEST MRI is a technique that uses differences in the tissue environment, like protein concentration or intracellular pH, to generate contrast differences. CEST MRI may identify tumor tissue that does not enhance with standard of care MRI. PH weighted CEST MRI based surgical resection may be more effective compared to standard of care surgical resection in treating patients with glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06448286
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06419946 - Phase III Trial of Temozolomide/Lomustine (TMZ/LOM) Combination Therapy vs. Standard TMZ Therapy for Newly Diagnosed MGMT Promoter Methylated Glioblastoma (IDHwt) Patients +/- Tumor Treating Fields (Optune) (PHASE3, NOT_YET_RECRUITING): Background: Glioblastoma (GBM) is notoriously difficult to treat, with current therapies often extending life by only a few months. The standard treatment involves surgery followed by radiation and chemotherapy with Temozolomide (TMZ). The efficacy of TMZ, however, is significantly enhanced when the tumor's o6-methylguanine-DNA-methyltransferase (MGMT) gene is methylated. Recent studies, such as the NOA-09 trial, have suggested that adding Lomustine (LOM) to TMZ could improve outcomes for patients with this specific tumor profile. Hypothesis: The investigators hypothesize that the addition of LOM to the TMZ regimen will lead to significantly improved survival rates among patients with newly diagnosed glioblastoma who have a methylated MGMT promoter compared to those receiving only TMZ. Treatment Plans: The study will randomly assign participants to two groups: * Control Group: Standard treatment with TMZ during and after radiation therapy. * Experimental Group: TMZ combined with LOM, starting on the first day of radiation therapy. Outcome Measures: The primary outcome measure will be survival. Other outcomes will include progression-free survival (time from randomization until tumor progression or death), safety profiles (adverse effects of the treatments), and quality of life measures as well as neurocognitive outcomes.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06419946
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06319027 - Phase II Glioblastoma Accelerated Biomarkers Learning Environment Trial (GABLE) (PHASE2, RECRUITING): This phase II trial studies whether different imaging techniques can provide additional and more accurate information than the usual approach for assessing the activity of tumors in patients with newly diagnosed glioblastoma. The usual approach for this currently is magnetic resonance imaging (MRI). This study is trying to learn more about the meaning of changes in MRI scans after treatment, as while the appearance of some of these changes may reflect progressing tumor, some may be due the treatment. Dynamic susceptibility contrast (DSC)-MRIs, along with positron emission tomography (PET) and/or magnetic resonance (MR) spectroscopy, may help doctors tell which changes are a reflection of the treatment and which changes may be due to progressing tumor.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06319027
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06222138 - Study of Biologic Tumor and Plasma Biomarkers of Response to TTFields in Patients Treated for Newly Diagnosed Glioblastoma (NA, RECRUITING): This trial is a translational, open-label, monocentric prospective study of 80 patients aiming to study resistance mechanisms as well as biomarkers of resistance or sensitivity to TTFields. The study will be conducted on a population of patients with newly diagnosed glioblastoma treated with radio-chemotherapy followed by TTFields in the context of either routine care or a clinical trial. In this study, the Optune® system (battery operated device which delivers TTFields to the brain) will not be under investigation. For each included patient, blood samples will be collected during baseline visit (before initiation of radio-chemotherapy), then before initiation of TTFields and every 3 months during TTFields treatment. Additional blood samples will be scheduled at recurrence (if applicable). Moreover, tumor samples (formalin paraffin embedded (FFPE) tumor block and fresh samples) will be collected from surgery specimen on primary tumor by the sponsor for analysis. In case of recurrence, and if a second surgery is possible, tumor samples will also be collected. Tumor samples will be collected from biopsies taken in the course of routine practice and from surgical specimens collected during surgical procedure. No additional biopsies will be performed for the study. Patients will be followed-up for time to progression and overall survival for a maximum duration of 24 months from the TTFields initiation. MRI performed by patients during the course of the study will be collected by the sponsor for additional future research purposes.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06222138
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06176066 - PH Weighted Chemical Exchange Saturation Transfer Based Surgical Resections of Glioblastoma (PHASE1, RECRUITING): Current standard of care therapy and all FDA approved adjuvant therapy for glioblastoma continue to provide less than 12 months of progression free survival (PFS) and less than 24 months of overall survival (OS). There is an extreme need for any novel therapy against glioblastoma that increases progression free survival and overall survival in patients diagnosed with this invasive form of cancer. A significant reason for such a poor prognosis is the infiltrative nature of this tumor in non-enhancing regions (NE) beyond the central contrast-enhancing (CE) portion of tumor, which is difficult to visualize and treat with surgical, medical, or radiotherapeutic means. Since tumor cells exhibit abnormal metabolic behavior leading to extracellular acidification, we theorize a newly developed pH-sensitive MRI technique called amine chemical exchange saturation transfer echoplanar imaging (CEST-EPI) may identify infiltrating NE tumor beyond what is clear on standard MRI with gadolinium contrast. This phase I safety study will use use intraoperative CEST-EPI guided resections in glioblastoma at increasing distances from areas of CE tumor to test whether this technique is safe and can remove additional areas of infiltrative NE tumor. The primary objective of this study is to assess the safety of pH-sensitive amine CEST-EPI guided resections for glioblastoma.The secondary objectives of this study include: 1. A preliminary efficacy analysis of CEST-EPI guided resections in extending progression free and overall survival. 2. To confirm that resected tissue obtained from pH-sensitive amine CEST-EPI guided resections contain infiltrating NE tumor. The primary endpoint for this study will be safety of resecting "CEST positive", acidic regions within T2 hyperintense regions of glioblastoma thought to contain active NE tumor at increasing distances from contrast enhancing tumor with development of a recommended maximal tolerated resection. 1. At the maximal tolerated resection, a preliminary efficacy study with endpoints of progression free survival (as defined by RANO Resect 2.0) 1 and overall survival. 2. Quantitation of infilitrating tumor burden on CEST-EPI resected tissue using immunohistochemical staining. 12 patients up to 24 patients based on resection limiting toxicities with potential expansion of up to 16 patients at the maximum tolerated resection. Inclusion Criteria: 1. Must be able to provide written informed consent 2. Male or female \> 18 years of age 3. Karnofsky Performance Scale (KPS) \> 70 (indicating good performance status). 4. Individuals with suspected, newly diagnosed or recurrent IDH wild type WHO IV glioblastoma (intraxial, expansile contrast-enhancing mass without evidence of metastatic disease. This will be reviewed by UCLA neuroradiology to only include patients with high likelihood of GBM) Exclusion Criteria: 1. Pediatric patients 2. Diagnostic uncertainty (reviewed by UCLA neuroradiology history extracranial malignancy or autoimmune disease) 3. Medical conditions that make patients a poor candidate for anesthesia and/or surgery (decision for surgery will follow standard pre-operative clearance guidelines and will not differ for this specific study from standard of care treatment plan) 4. Involvement of eloquent areas (as defined by MRI signal clearly involving areas that would lead to a qualifying neurologic deficit as defined in surgical limiting toxicity - this will specifically include: 1) primary motor cortex, 2) primary sensory cortex, 3) sensorimotor fibers as defined on pre-operative diffusion tensor imaging, 4) primary language areas (Broca, Wernicke), 5) arcuate fasiculus as defined on pre-operative diffusion tensor imaging Pre-operative: Standard of care pre-operative MRI including perfusion and pH-weighted amine CEST-EPI (which will add up to 15 minutes of scan time) for a single pre-operative exam prior to surgery. Surgery: 1 day (subjects to be admitted to the hospital) Follow-up: inpatient stay (1-3 days), 2 week clinical assessment (outpatient post-op clinic visit). MRI and clinical assessment at 4 weeks (end of resection limited toxicity window). Following this, there will be standard of care follow up with MRI and clinical assessment starting at 8 weeks +/- 4 weeks (per RANO 2.0). 1 Total study duration for recruitment, enrollment, and study completion of all subjects is up to 2 years. Single-arm, surgical resection escalation safety trial with a preliminary efficacy study at the maximal tolerated resection This safety evaluation will mimic a phase 1 dose escalation safety study using a rule based approach on based on a i3+3 design.2 Using standard of care resection of contrast enhancement as the baseline, we will begin with 3 subjects with maximal resection + "CEST positive" areas 0.7 cm from the contrast enhancing boundary within areas of T2 hyperintensity. If there is not \> 1 pre-determined resection limiting toxicity (RLT, defined below) in this cohort, the r
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06176066
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06140875 - Amplitude Modulated Radiofrequency Electromagnetic Field Treatment Combined With Radiochemotherapy and Maintenance Chemotherapy in Patients With Glioblastoma (Brain-RF) (NA, RECRUITING): Combined chemoradiation and radiofrequency electromagnetic field treatment for patients with glioblastoma
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06140875
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: newly_diagnosed
- NCT06132438 - Immunotherapy Targeting of Cytomegalovirus Antigens in Glioblastoma (INTERROGATE-GBM) (PHASE1, NOT_YET_RECRUITING): In Australia, glioblastoma (GBM) has a higher annual fatality rate than a variety of other cancers, such as melanoma, bladder, and kidney tumors. While the 5-year survival rate for other cancers, such as breast and prostate cancer, has increased, there have been no notable advancements in GBM during the past ten years, and the incidence and mortality patterns have barely changed between 1982 and 2011. In particular, GBM poses a challenging therapeutic dilemma for patients and physicians due to its aggressive biology and resistance to available treatments. Recent studies showed that cytomegalovirus (CMV) is expressed in GBM tumors, making it a good target for immunotherapy trials. This phase I trial aims to determine the safety and tolerability of the PEP-CMV vaccine in patients with newly diagnosed MGMT-unmethylated GBM in combination with one cycle of adjuvant temozolomide.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06132438
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06090903 - Exploration Into the Association Between Decorin (DCN) Expression and MR Phenotypes in GBM (NA, RECRUITING): This clinical trial uses a type of imaging scan called magnetic resonance imaging (MRI) to study brain tumor biology in patients with glioblastoma that can be removed by surgery (resectable). Malignant gliomas are the second leading cause of cancer mortality in people under the age of 35 in the United States. Glioblastoma is a type of malignant glioma with very poor patient prognosis. There are currently only about 3 drugs approved by the Food and Drug Administration (FDA) for the treatment of glioblastoma, one of them being administration of bevacizumab, which is very expensive. It is the most widely used treatment for glioblastoma with dramatic results. However, previous clinical trials have not demonstrated an overall survival benefit across all patient populations with glioblastoma that has returned after treatment (recurrent). The study aims to identify which patients who will benefit from bevacizumab therapy by observing MRI images and corresponding imaging biomarkers.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06090903
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06072586 - A Phase 0/1 Study of BDTX-1535 in Recurrent High-Grade Glioma (HGG) and Newly Diagnosed Glioblastoma (nGBM) Participants With EGFR Alterations or Fusions Scheduled for Resection to Evaluate Central Nervous System (CNS) Penetration With PK-triggered Expansion Cohort (EARLY_PHASE1, RECRUITING): This study will administer the investigational drug, BDTX-1535 to eligible patients with recurrent high-grade glioma (HGG) and newly-diagnosed glioblastoma (nGBM). BDTX-1535 was designed to block a growth signal important to some cancers. BDTX-1535 is being tested in this study to see if it can be given safely to people who have tumors that can be dependent on that growth signal because of changes in a protein called EGFR. These gene changes are called amplifications, mutations, fusions or alterations and are found only in the tumors. The study design includes a Phase 0 component with PK/PD-trigger for participant enrollment into an Expansion Phase 1 component. The primary objective of the Phase 0 component is to evaluate the PK endpoints of BDTX-1535. The primary objective of the Phase 1 component is to establish the safe dose of BDTX-1535 to be used in participants with a specified treatment regimen, three of which include standard of care radiotherapy for nGBM participants.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06072586
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_chemoradiation, Matched inclusion factor: newly_diagnosed
- NCT05904119 - Lomustine With and Without Reirradiation for First Progression of Glioblastoma: a Randomized Phase III Study (PHASE3, RECRUITING): Despite comprehensive multimodal treatment of newly diagnosed glioblastoma, almost all patients suffer from tumour relapse. Currently, no standard of care exists to treat these tumour relapses. Treatment options include repeated surgery (if feasible), systemic therapy (bevacizumab, lomustine, temozolomide re-challenge), reirradiation and best supportive care. Currently, the superiority of combined chemoradiation versus chemotherapy alone remains unproven. Given that lomustine is the standard chemotherapeutic agent for the treatment of recurrent glioblastoma in Europe and the unclear efficacy of reirradiation, we want to explore whether combining lomustine and reirradiation may be a better treatment than lomustine alone. The results of the prospective randomized trial proposed here should demonstrate a significant improvement in overall survival when lomustine is combined with reirradiation in patients with recurrent glioblastoma compared to lomustine alone without adversely affecting quality of survival. The trial will be stopped based on overall survival in a preplanned futility and efficacy interim analysis.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05904119
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05879250 - A Multi-Arm, Open Label, Phase II Trial of WP1066 and Radiation Therapy in Patients With Newly Diagnosed Glioblastoma (PHASE2, RECRUITING): This phase II trial tests how well the combination of WP1066 and radiation therapy works in treating newly diagnosed glioblastoma. Glioblastoma is difficult to treat effectively because the cells within the tumor vary widely and are controlled by factors within and around the tumor, requiring multiple approaches to treat the tumor. The study drug WP1066 targets a specific pathway, known as STAT3, which is responsible for promoting tumor growth and causing the body's immune system to avoid attacking the tumor. Radiation therapy prevents glioblastoma from growing. Giving WP1066 with radiation therapy may prevent glioblastoma from growing and prolong survival.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05879250
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05768919 - Phase I/II Study of the Tolerability, Safety, and Efficacy of Liposomal Curcumin in Combination With Radiation and Temozolomide in Patients With Newly Diagnosed High-Grade Gliomas (PHASE1, PHASE2, RECRUITING): The objective of this study is to assess the tolerability, safety, and efficacy of Liposomal Curcumin (LC) in combination with radiotherapy (RT) and Temozolomide (TMZ) in patients with newly diagnosed High-Grade Gliomas (HGG).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05768919
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05768087 - Escalated Dose Proton Therapy Within the Multimodality Treatment of Glioblastoma Patients - A Phase 1 Proton Dose Finding Trial - (NA, RECRUITING): The goal of this phase 1 dose finding study is to to assess the clinical tolerability and safety of escalated dose proton therapy in glioblastoma patients treated with multimodality treatment, according to treatment volume. The main questions it aims to answer are: * what is the maximum tolerated proton dose in glioblastoma patients? * is the maximum tolerated proton dose in glioblastoma patients dependent on treatment volume? * what is the recommended phase 2 proton dose in glioblastoma patients? Patients will be asked to undergo radiotherapy to step-wise escalated doses using proton therapy as part of their multimodality treatment. Patients will be monitored closely for treatment effects.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05768087
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05736406 - An Interventional, Multicenter, and International Phase 1/2, Light-dose-escalation Study to Investigate the Safety and Feasibility of Intraoperative Photodynamic Therapy (PDT) With Pentalafen® Drug and Heliance® Solution Device in Male and Female Patients 18 to 75 Years of Age With Grade IV Glioblastoma. (PHASE1, PHASE2, RECRUITING): The primary objective of this clinical trial is to determine the safety and tolerability of two doses of light in intraoperative PDT added to standard of care; temozolomide-based chemotherapy in male and female patients aged 18 to 75 with newly diagnosed glioblastoma. This treatment will be carried out in addition to the maximal surgical resection. Data collected during this trial will be used to design the upcoming pivotal study . The study will utilize an independent Data and Safety Monitoring Board (iDSMB) that will review safety data to allow dose escalation.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05736406
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05734560 - Delivery of D2C7-IT and 2141-V11 Combination Immunotherapy in Residual Disease for Adult Patients With Newly Diagnosed MGMT Unmethylated Glioblastoma and Perilymphatic Subcutaneous Injections of 2141-V11 (PHASE1, PHASE2, RECRUITING): The purpose of this research study is to determine the safety and efficacy of administering a single intracerebral (within the brain) dose of investigational compounds called D2C7-immunotoxin (IT) and 2141-V11 in residual disease (within tumor margins) after surgery, followed by later repeated injections of 2141-V11 in the subcutaneous area (under the skin) around the lymph nodes of the head and neck for adults newly diagnosed with a type of cancerous brain tumor called glioblastoma. The word "investigational" means the study drugs are still being tested in research studies and are not approved by the U.S. Food and Drug Administration (FDA).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05734560
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05708352 - A Randomized Controlled Phase 2 Study of the Ketogenic Diet Versus Standard Dietary Guidance for Patients With Newly Diagnosed Glioblastoma in Combination With Standard-of-care Treatment (PHASE2, RECRUITING): This is a Phase 2, randomized two-armed, multi-site study of 170 patients with newly diagnosed glioblastoma multiforme. Patients will be randomized 1:1 to receive Keto Diet, or Standard Anti-Cancer Diet. All patients will receive standard of care treatment for their glioblastoma. The Keto Diet intervention will be for an 18-week period and conducted by trained research dietitians. Daily ketone and glucose levels will be recorded to monitor Keto Diet adherence. This two-armed randomized multi-site study aims to provide evidence to support the hypothesis that a Keto Diet vs. Standard Anti-Cancer Diet improves overall survival in newly diagnosed glioblastoma multiforme patients who receive standard of care treatment.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05708352
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05664464 - A Phase Ib/II Randomized, Open Label Drug Repurposing Trial of Glutamate Signaling Inhibitors in Combination With Chemoradiotherapy in Patients With Newly Diagnosed Glioblastoma (PHASE1, PHASE2, RECRUITING): The goal of this 1:1 randomized, multi-center, open-label phase Ib/II clinical trial is to explore the efficacy of the add-on of the anti-glutamatergic drugs gabapentin, sulfasalazine and memantine to standard chemoradiotherapy with temozolomide compared to chemoradiotherapy alone in patients with newly diagnosed glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05664464
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05660369 - INCIPIENT: INtraventricular CARv3-TEAM-E T Cells for PatIENTs With GBM (PHASE1, RECRUITING): The goal of this research study is to determine the best dose of CARv3-TEAM-E T Cells for treating participants with glioblastoma. The name of the treatment intervention used in this research study is: -CARv3-TEAM-E T Cells (or Autologous T lymphocytes).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05660369
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), recurrence_max=0 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05439278 - Randomized Phase III Study of Conventional Versus Hypofractionated Radiotherapy Combined With Temozolomide in Elderly Glioblastoma Patients (PHASE3, RECRUITING): In newly diagnosed glioblastoma patients aged 70 years or older who are suitable for concurrent temozolomide, the optimal dose of radiation therapy is controversial . The purpose of this study is to compare conventional radiotherapy of 60 Gy (6 weeks) versus hypofractionated radiotherapy of 40 Gy (3 weeks) in terms of overall survival as the primary endpoint along with progression-free survival, toxicity, quality of life, and prognostic biomarkers.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05439278
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05380349 - A Phase 1 Study of Combination Drug Therapy Based on Personalized Cancer Stem Cell (CSC) High-Throughput Drug Screening (HTS) With Standard of Care for Newly Diagnosed Glioblastoma (EARLY_PHASE1, RECRUITING): Proposed treatment of subjects with newly diagnosed glioblastoma with novel personalized drug regimens identified to be effective in vitro using cancer stem cells derived from their individual tumors, alongside standard of care radiation and TMZ.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05380349
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05281731 - Sonobiopsy for Noninvasive and Sensitive Detection of Glioblastoma (NA, RECRUITING): This clinical study to evaluate sonobiopsy is significant because sonobiopsy will fundamentally enhance the clinician's insight into the molecular features of an intracranial lesion to tailor treatment approaches and optimize outcomes. In addition to the standard diagnostics of anatomic imaging and surgical histology, sonobiopsy has the potential to become the third pillar for brain tumor management by radically advancing the ability to easily and regularly acquire tumor genetic and molecular signatures. This enhanced capability will have a dramatic impact on patient survival and quality of life.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05281731
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05235737 - A Single Center, Open-Label, Randomized Study to Evaluate the Safety and Efficacy of Neoadjuvant and Adjuvant Pembrolizumab on Top of Standard Chemo-Radiotherapy (Stupp Protocol) in Treatment of Patients With Newly Diagnosed Glioblastoma Multiforme (GBM). (PHASE4, RECRUITING): To evaluate the short-term and longer-term safety, tolerability, and effectiveness of neoadjuvant and adjuvant Pembrolizumab on top of standard therapy (Stupp protocol) in patients with Glioblastoma Multiforme (GBM). Randomized comparison of safety, tolerability, and clinical efficacy of (1) neoadjuvant and adjuvant Pembrolizumab (on top of Stupp protocol, n=12 patients), (2) neoadjuvant Pembrolizumab (on top of Stupp protocol, n=12 patients), and (3) standard of care (Stupp protocol only, n=12 patients). Immuno-PET examination will be performed before and after surgery in all patients.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05235737
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 8 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05100641 - Randomized Phase 3 Trial of Standard Care Plus AV-GBM-1 vs Autologous Monocytes as Adjunctive Therapy Following Primary Surgery Plus Concurrent Radiation-temozolomide in Patients With Newly Diagnosed Glioblastoma (PHASE3, NOT_YET_RECRUITING): This is a multi-center, double-blind, 2:1 randomized phase III trial to determine whether the addition of AV-GBM-1, a therapeutic, patient-specific dendritic cell vaccine, to standard therapy increases OS of patients with a recent diagnosis of primary GBM. The intent is to enroll approximately 726 patients for tumor collection to enroll 690 who are eligible for treatment at the time of randomization and who have granted consent for participation. Because of the lack of toxicity, there are no restrictions related to performance status or blood tests at the time of treatment. The key endpoint is OS from date of first injection after RT/TMZ; secondary endpoints are PFS from date of first injection, and OS and PFS from date of randomization prior to RT/TMZ. Date of PFS will be determined by the principal investigator at each site.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05100641
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 90 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT04945148 - Oxidative Phosphorylation Targeting In Malignant Glioma Using Metformin Plus Radiotherapy Temozolomide (PHASE2, RECRUITING): Tailored approaches targeting crucial oncogenes and pathways have shown successful results in a number of cancer types and offer exciting perspective in neuro-oncology. IDH (Isocitrate dehydrogenase) wild-type (IDHwt) glioblastoma (GBM) (10%) present a unique and homogenous energetic metabolism which is specifically dependent on the oxidative phosphorylation (OXPHOS) rather than on the aerobic glycolysis. OXPHOS+ IDHwt GBMs overexpress mitochondrial markers and can be specifically inhibited by mitochondrial inhibitors in vitro and in vivo. Metformin is an oral inhibitor of mitochondrial complex I and is a widely used drug in diabetic and non-diabetic patients, safe and well tolerated in association with radiotherapy and chemotherapy. Basing on drastic effect, the investigators have observed in vivo (reduction of \>50% of tumor growth) and hypothesize that metformin could be specifically efficient to treat up-front patients affected by OXPHOS+ GBM, in association with the standard first-line treatment with radiotherapy and temozolomide (RT-TMZ). The investigators set up a dedicated molecular analysis including RNA assay and expression of OXPHOS markers for formalin-fixed paraffin-embedded tumors (FFPE), which allows to detect OXPHOS+ GBM at diagnosis. Here a phase II, open label, non-randomized multicenter trial including five French neurooncology centers (H. Foch-Suresnes, Pitié-Salpêtrière-Paris, Saint Louis-Paris, Lyon, Marseille) and one in Italy (Istituto Besta, Milan) is proposed. Newly diagnosed IDH wild-type GBM patients with the OXPHOS+ signature will be eligible for inclusion in this trial. The investigators expect to screen 640 patients and to include 64 patients over a period of 24 months with 24 months of follow-up.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04945148
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT04903795 - A Phase 1 Study of Bispecific T Cell Engager (BRiTE) in Patients With Newly Diagnosed or Recurrent Glioblastoma (PHASE1, NOT_YET_RECRUITING): This Phase 1 study will assess the safety of a novel brain Bispecific T cell engager (BRiTE) in patients with newly diagnosed or recurrent World Health Organization (WHO) Grade 4 glioblastoma (GBM). Owing to its short half-life, the study drug, BRiTE, will be continuously infused intravenously (IV) for 4 days (96 hours) in a 28-day cycle. Given that BRiTE specifically exerts its effects on tumor cells expressing the Epidermal Growth Factor Receptor variant III (EGFRvIII) mutation, we will only enroll patients with EGFRvIII-positive tumors in this study. The primary objective is to evaluate the safety and tolerability of continually infused BRiTE in ndGBM and rGBM patients and determine the maximum tolerated dose (MTD) for continuously infused BRiTE.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT04903795
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_chemoradiation, Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT04443010 - A Study to Evaluate the Safety and Efficacy of the Tumor-targeting Human Antibody-cytokine Fusion Protein L19TNF Plus Standard Temozolomide Chemoradiotherapy in Patients With Newly Diagnosed Glioblastoma (PHASE1, PHASE2, RECRUITING): The purpose of this study is to explore the safety profile and establish a recommended dose (RD) for phase II of the antibody-cytokine fusion protein L19TNF plus standard TMZ chemoradiotherapy in patients with newly diagnosed glioblastoma. The study will be conducted in three consecutive parts: a dose finding part to determine the RD of L19TNF in combination with chemoradiotherapy, followed by a signal seeking part that investigates first signs of activity and then an activity evaluation part that studies the efficacy of L19TNF in combination with chemoradiotherapy against chemoradiotherapy alone.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04443010
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT04373785 - A Multi-Center Pilot/Phase I and Phase II Clinical Trial of NG101m Adjuvant Therapy in Newly Diagnosed Glioblastoma Patients (PHASE1, PHASE2, NOT_YET_RECRUITING): The purpose of this clinical trial is to evaluate the addition of NG101m adjuvant therapy to standard of care treatment of glioblastoma multiforme. All subjects will receive NG101m capsules along with the standard treatment of temozolomide and radiation.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT04373785
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT04115761 - A Phase II, Randomized, Open-Label, Parallel-Group Study to Evaluate the Efficacy and Safety of Autologous Dendritic Cell Vaccination (ADCV01) As an Add-On Treatment for Primary Glioblastoma Multiforme (GBM) Patients (PHASE2, RECRUITING): This study is designed with open-label and randomized parallel group to evaluate the efficacy and safety of autologous dendritic cell vaccination (ADCV01) as an add-on treatment for primary glioblastoma multiforme
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04115761
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT03970447 - GBM AGILE: Global Adaptive Trial Master Protocol: An International, Seamless Phase II/III Response Adaptive Randomization Platform Trial Designed To Evaluate Multiple Regimens In Newly Diagnosed and Recurrent GBM (PHASE2, PHASE3, RECRUITING): Glioblastoma (GBM) adaptive, global, innovative learning environment (GBM AGILE) is an international, seamless Phase II/III response adaptive randomization platform trial designed to evaluate multiple therapies in newly diagnosed (ND) and recurrent GBM.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03970447
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 60 (match), recurrence_max=0 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT02704858 - An Open-Label, Phase 1/2A Dose Escalation Study of Safety and Efficacy of NEO100 in Recurrent or Progressive Grade III or Grade IV Gliomas With IDH1 Mutation (PHASE1, PHASE2, RECRUITING): This multi-site, Phase 1/2a clinical trial is an open-label study to identify the safety, pharmacokinetics, and efficacy of a repeated dose regimen of NEO100 (perillyl alcohol) for the treatment of patients with radiographically-confirmed progression of Grade IV glioma or recurrent primary or secondary Grade IV glioma. The study will have two phases, Phase 1 and Phase 2a. Phase 1 is a standard cohort dose escalation 3+3 design used to determine the maximum tolerated dose for Phase 2a. There will be up to 24 patients enrolled in Phase 1. There will be 25 patients enrolled in Phase 2a. For both phases of the study, NEO100 will be self-administered four times daily for a 28-day treatment cycles until disease progression, death or patient withdraw from study for any reason, whichever occurs first. Version 10 of the protocol changed the inclusion criteria for Phase 2a to limit inclusion to those patients with progressive or recurrent primary or secondary Grade IV gliomas expressing IDH1 mutations. Prior to the protocol amendment, 4 patients were enrolled who were IDH1 wild-type. Therefore, an additional 28 patients will be recruited for a total of 32 patients enrolled into Phase 2a of this study to have 35 evaluable cases. Version 12 of the protocol expanded the inclusion criteria for Phase 2a to include those patients with progressive or recurrent Grade III Astrocytoma expressing IDH1 mutations. Review of the literature specific to these patients found the same expected time to progression and death. As a result, the number of patients to enroll remains 32 to have 35 evaluable cases.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02704858
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 60 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT02613988 - Early Response Assessment Using on 3T Advanced MR Imaging as Predictor of Long-term Treatment Response in Newly Diagnosed Glioblastomas (NA, RECRUITING): This clinical trial studies advanced MR imaging techniques in measuring early response of standard treatment may become predictors of long-term treatment response in patients with newly diagnosed glioblastomas.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02613988
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT02331498 - A Phase I/II Study of Pazopanib in Combination With Temozolomide in Patients With Newly Diagnosed Glioblastoma Multiforme After Surgery and RT-CT (PHASE1, PHASE2, RECRUITING): A phase I/II study of pazopanib in combination with temozolomide in patients with newly diagnosed glioblastoma multiforme after surgery and RT-CT (PAZOGLIO study)
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02331498
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: newly_diagnosed
- NCT02287428 - A Phase I Study of a Personalized NeoAntigen Cancer Vaccine With Radiotherapy Plus Pembrolizumab/MK-3475 Among Newly Diagnosed Glioblastoma Patients (PHASE1, RECRUITING): This research study is studying a new type of vaccine as a possible treatment for patients with glioblastoma. This research study is a Phase I clinical trial, which tests the safety of an investigational intervention and also tries to define the appropriate dose of the intervention to use for further studies. "Investigational" means that the intervention is being studied and that research doctors are trying to find more about it. It also means that the FDA (U.S. Food and Drug Administration) has not approved the Personalized NeoAntigen Cancer Vaccine for any use in patients, including people with glioblastoma. The purpose of the initial study cohort (Cohort 1) is to determine if it is possible to make and administer safely a vaccine against glioblastoma by using information gained from specific characteristics of the participants tumor. It is known that glioblastomas have mutations (changes in genetic material) that are specific to an individual patient's tumor. These mutations can cause the tumor cells to produce proteins that appear very different from the body's own cells. It is possible that these proteins used in a vaccine may induce strong immune responses, which may help the body fight any tumor cells that could cause the glioblastoma to come back in the future. Three additional cohorts (1a, 1b, \& 1c) were added to the study following completion of accrual to the original study cohort (cohort 1). Each new cohort receives NeoVax and radiation therapy as administered to cohort 1 and will also receive pembrolizumab: cohort 1a patients will start pembrolizumab w/in 2 weeks after start of RT, and continue every 3 weeks for up to 2 years; cohort 1b patients will start pembrolizumab 2-4 weeks after completion of NeoVax priming, and continue every 3 weeks for up to 2 years; cohort 1c patients will receive a single dose of pembrolizumab administered within 2 weeks after start of RT, re-start 2-4 weeks after completion of NeoVax priming, and continue every 3 weeks for up to 2 years. The rationale for adding these new cohorts is: 1) to assess the safety and feasibility of NeoVax when administered with pembrolizumab; and 2) to determine if the timing of anti-PD-1 administration impacts the immunogenicity of NeoVax. An additional sub-study cohort (1d) is being added for patients whose tumor is MGMT-methylated. Cohort 1d will enroll patients with tumors for which the MGMT status is methylated or partially methylated; patients on cohort 1d will receive standard daily temozolomide during radiation and as adjuvant therapy for up to six cycles following completion of radiation therapy. The rationale for adding cohort 1d is to determine the safety and feasibility of NeoVax when administered with pembrolizumab and temozolomide.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02287428
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_chemoradiation, Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT01777919 - A PHASE II CLINICAL TRIAL FOR THE EVALUATION OF THE EFFICACY OF DISULFIRAM/COPPER COMBINATION AS AN ADJUVANT AND CONCURRENT CHEMOTHERAPY IN THE TREATMENT OF NEWLY DIAGNOSED GLIOBLASTOMA MULTIFORM (PHASE2, NOT_YET_RECRUITING): Glioblastoma multiform (GBM) is the most common malignant primary brain tumor in adults. Despite maximal treatment tumor relapse occurs regularly accompanied by unfavourable prognosis. Among other reasons, it is believed that this could be in part due to the existence of the so-called tumor stem cells (TSCs), a cellular subfraction within GBM which escape therapy by being highly resistant to irradiation and chemotherapy and thus constituting the source of tumor recurrence. GBM, like many other cancers, show a sub-population of aldehyde dehydrogenase (ALDH) overexpressing TSCs. More specifically, ALDH1A1, a cytoplasmatic isoform of ALDH, proved to be a novel stem cell marker in human GBM. In addition, ALDH1A1 has been shown to be a mediator for resistance of GBM to temozolomide (TMZ) and a reliable predictor of clinical outcome; prognosis of patients with a high level of ALDH1A1 expression was poor compared with that of patients with low levels. Consequently, ALDH1A1 may serve as a potential target to improve treatment of human GBM through inhibition of the enzyme. Disulfiram (DSF) has been used for more than sixty years in the treatment of chronic alcoholism because of the unpleasant symptoms it provokes after ethanol intake. The underlying mechanism is believed to be the accumulation of acetaldehyde in the blood, due to inhibition of the liver ALDHs. Actually, DSF is a strong inhibitor of ALDH1A1 and relatively non-toxic at therapeutic (for chronic alcoholism) doses that can penetrate the blood-brain barrier. In addition, DSF has been shown to be cytotoxic on GBM stem-like cells, inhibiting the growth of TMZ resistant GBM cells and blocking self-renewal by \~100% , while it has been identified as an inhibitor of human GBM stem cells in high-throughput chemical screens. Interestingly, a number of these actions were copper-dependent. In the current Phase II clinical trial, DSF/copper combination will be tested as an adjunctive and concurrent chemotherapy in the treatment of newly diagnosed GBM. According to our hypothesis, initiation of DSF chemotherapy after the resection of the tumor and before the introduction of the standard radio-chemotherapy will inhibit ALDH1A1 of GBM TSCs making them more susceptible to radio-chemotherapy and possibly reducing the recurrence rate of GBM. On the other hand, the addition of copper will probably enhance the cytotoxic effects of DSF possibly through augmentation of its pro-apoptotic and proteasomal inhibitory actions.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT01777919
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07492836 - Prospective, Pilot Study to Evaluate Hypofractionated Radiotherapy Associated With Temozolomide in Patients Aged 18 to 70 Years With Glioblastoma (HypoGBM) (NA, NOT_YET_RECRUITING): The goal of this clinical trial is to evaluate the feasibility, safety and effectiveness of radiotherapy with fewer days of treatment and a higher dose of radiation each day in patients under 70 years of age diagnosed with a brain tumor known as glioblastoma.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07492836
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07461948 - Advanced MRI for Visualization and Quantification of the Tumor Immune Microenvironment (TIME) in Glioblastoma (PHASE3, RECRUITING): This phase III trial is evaluating whether a combination of three advanced magnetic resonance imaging (MRI) techniques, including chemical exchange saturation transfer (CEST) MRI, diffusion-relaxation correlation spectrum imaging (DR-CSI), and ferumoxytol-enhanced magnetic resonance imaging (Fe-MRI) are effective as non-invasive methods for assessing the cells and proteins that surround and interact with tumor cells (the tumor immune microenvironment) in patients with glioblastoma. Researchers understand that some types of brain tumors are harder to treat than others, but the reasons for this are not known in many cases. CEST MRI uses differences in the tissue microenvironment, like protein concentration or intracellular pH, to generate contrast differences. DR-CSI detects microstructural changes in tissue associated with immune cells infiltrating the tumor. Fe-MRI uses ferumoxytol as a contrast agent with MRI. Contrast agents are substances that are injected into the body and taken up by certain tissues, making the tissues easier to see in imaging scans. More advanced imaging techniques like CEST, DR-CSI, and Fe-MRI may offer less invasive methods than surgery or biopsy for helping researchers understand the tumor immune microenvironment in patients with glioblastoma, which may help researchers determine why some tumors are more resistant to treatment.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07461948
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07391215 - 5G-PEARL: Paxalisib in Combination With Temozolomide in Patients With High Grade Malignant Brain Tumours Within the 5G Platform (PHASE1, PHASE2, RECRUITING): The purpose of this clinical trial is to evaluate the safety and tolerability of paxalisib in combination with temozolomide and to determine the preliminary antitumour activity of the combination therapy. In the Phase 1b of this study parallel biomarker defined arms will be opened in the front-line unmethylated MGMT setting, enrolling 10 patients onto each arm. These patients will be treated with paxalisib in combination with temozolomide (TMZ). The starting dose of paxalisib will be 45mg once a day (OD) with the option of increasing to 60 mg (30 mg BD) in Cycle 2. TMZ will be administered once daily by mouth on days 1 to 5 in a 28-day cycle, with a starting dose of 150mg/m2 during cycles 1 and 2, and subsequent dose escalation to 200mg/m2 at the start of cycle 3 if cycles 1 and 2 have been well tolerated with no significant toxicity.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07391215
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low
- NCT07368283 - A Single-arm Phase II Non-inferiority Clinical Study of Limited Target Volume Radiotherapy After Glioblastoma Surgery (NA, NOT_YET_RECRUITING): Research on radiotherapy target volumes for glioblastoma is increasingly focused on exploring more limited yet effective irradiation fields, aiming to achieve local control while minimizing acute and long-term neurotoxicity. Previous retrospective analysis by investigators revealed that local recurrences of glioblastoma are predominantly confined to a narrow margin around the original lesion: 98.3% of recurrences occurred within 0.5 cm of the original T2-FLAIR abnormality, 94.8% within 1 cm of the original T1-enhanced region. These findings have been cited in the ESTRO-EANO treatment guidelines. Building on this evidence, investigators plan to conduct a single-arm, phase II clinical trial to systematically evaluate the efficacy and safety of a 1 cm radiotherapy target volume in post-operative glioblastoma patients.Eligible patients with glioblastoma who have undergone surgical resection will be selected to receive limited-field radiotherapy. The target volume will be defined based on the postoperative MRI enhancing lesion: a 1 cm margin will be added to form the clinical target volume (CTV), followed by a further 0.3 cm margin to create the planning target volume (PTV). A total dose of 60 Gy will be delivered in 30 fractions (2 Gy per fraction, 5 fractions per week). Concurrent and adjuvant chemotherapy will be administered per standard guidelines. The primary efficacy endpoints are the 6-month progression-free survival rate and the incidence of symptomatic radiation-induced brain necrosis of grade 3 or higher. Secondary endpoints include overall survival, patterns of recurrence, neurocognitive function, and quality of life.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07368283
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07144735 - Allogeneic Gamma Delta (γδ) T Cells for the Treatment of Glioblastoma (NA, RECRUITING): This first-in-human clinical study aims to evaluate the safety and feasibility of locally delivered, allogeneic γδ T cells (genetically edited with ARIH1 and BCL11b knockout, designated ABOUT γδT cells) in patients with glioblastoma multiforme (GBM). The engineered effector cells are delivered via localized administration to selectively target and eliminate residual GBM cells. ABOUT: ARIH1 and BCL11b knockOUT γδ T cells.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07144735
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07089758 - A Pilot Feasibility Study for Cerebral Open Flow Microperfusion in Patients Undergoing Planned Neurosurgical Resection of Diseased Parenchyma. (NA, NOT_YET_RECRUITING): The purpose of this study is to evaluate the safety and feasibility of intra-operative microperfusion during a planned neurosurgical resection of diseased brain parenchyma, including either an epileptic focus requiring temporal lobectomy or a glioma. Devices used for microperfusion are Joanneum Research cerebral open flow microperfusion (OFM) catheters, push and pull tubing, and MPP102-II pump.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07089758
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07067905 - Clinical Evaluation of [68Ga]Ga-XT771 PET for Diagnosis in Patients With Glioblastoma and Clear Cell Renal Cell Carcinoma (EARLY_PHASE1, RECRUITING): A prospective, open-label, phase 1 study. This clinical trial aims to evaluate the diagnostic value of 68Ga-XT771, a CAIX/CAXII protein-specific probe, in PET/CT imaging for patients with clear cell renal cell carcinoma and glioblastoma. Safety, tolerability, and biodistribution characteristics of 68Ga-XT771 will also be assessed.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07067905
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06781372 - Development and Characterization of Patient's Derived Organoids as a Platform for the Screening of Novel Therapeutic Treatments for Glioblastoma Multiforme (NA, NOT_YET_RECRUITING): The study will enroll patients suffering from glioblastoma, a malignant brain tumor. Intervention is intended as a laboratory intervention and not as a clinical intervention. In fact, tumor removed from patients' brains will be sent to a dedicated laboratory to obtain an "avatar" of the tumor, named patient-derived organoid (PDO). A number of experimental antitumor approaches will be studied on PDOs. Results of these experiments will be correlated to the prognosis of patients.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06781372
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06764537 - Evaluation of in Vitro Antitumor Activity of GD2 CAR-T Cells Generated From Blood of Glioblastoma Patients (NA, NOT_YET_RECRUITING): Glioblastoma is a brain tumor with a very poor prognosis, affecting around 2,400 new patients every year. Current treatments do not provide good control of the disease. In view of the therapeutic impasse, it is necessary to develop new strategies. CAR-T cells (Chimeric antigen receptor T cells) represent a highly promising therapy for the treatment of incurable cancers, including glioblastoma. This treatment aims to destroy cancer cells by relying on the patient's own immune system. CAR-T cells are generated from the patient's own immune cells, more specifically T lymphocytes, which are genetically modified to express a tumor-specific receptor on their surface. CAR-T cells bind to tumor cells and cause their destruction. However, these cells have shown limited therapeutic power in the treatment of brain tumors. This is mainly due to the microenvironment surrounding the tumor, which is composed of immunosuppressive cells. These cells, and the molecules they secrete, help to reduce the activity of CAR-T cells that would otherwise reach the tumor. Little is currently known about these resistance mechanisms. The aim of this research is therefore to better understand these resistance mechanisms in order to propose a strategy for enhancing the therapeutic action of CAR-T cells in the treatment of glioblastoma. The main objective of this research is to evaluate the impact of the tumor environment on the antitumor efficacy of anti-GD2 CAR-T therapeutic cells in an in vitro glioblastoma model. Both tumor environment cells and CAR-T therapeutic cells will be generated from glioblastoma patient cells. The secondary objectives of this research are to * Evaluate the impact of tumor environment targeting on the in vitro antitumor efficacy of anti-GD2 CAR-T therapeutic cells. * Evaluate the quality/quantity of generated cells (CAR-T cells and tumor environment cells) in relation to glioblastoma patients. * Evaluate the efficiency of the cell isolation technique (CAR-T cells and tumor environment cells)
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06764537
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06749925 - Phase III Randomized, Double-Blind, Placebo-Controlled Clinical Trial Assessing the Efficacy and Safety of Dendritic Cell-Based Immunotherapy for Glioblastoma (PHASE3, NOT_YET_RECRUITING): This Phase III, multicenter, placebo-controlled clinical trial with sequential randomization is designed to evaluate the efficacy and safety of an experimental vaccine composed of hybrid dendritic cells (DCs) for the treatment of glioblastoma. Conducted at the Hospital das Clínicas of the University of São Paulo Medical School (HCFMUSP) and the Institute of Biomedical Sciences of the University of São Paulo (ICB/USP), the study is led by Professor José Alexandre Marzagão Barbuto. A multidisciplinary team of researchers specializing in neurosurgery, pathology, hematology, and other fields will contribute to a comprehensive approach. The trial aims to determine whether the hybrid DC vaccine can increase overall survival in adult patients with glioblastoma who have completed standard treatment, including surgery, chemotherapy, and radiotherapy. Secondary objectives include evaluating progression-free survival, quality of life, immune response, and the safety of the intervention. The study will enroll 186 patients, who will be randomized into three groups: (1) a control group receiving placebo, (2) a group receiving the DC vaccine, and (3) a group receiving the DC vaccine combined with pembrolizumab.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06749925
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06687681 - Efficacy of the Intrathecal Injection of Active Allogeneic Natural Killer Cells in Patients With High-grade Gliomas; A Multi-center Phase II Clinical Trial (PHASE2, RECRUITING): Gliomas are the most common malignant brain tumors, which are often associated with high-grade tumors characterized by an inferior prognosis and low patient survival rates in both children and adults. Surgical removal and tumor resection are the primary treatment approaches for gliomas. In such cases, whole-brain radiation therapy is also employed as a therapeutic option, which itself has significant side effects, and studies have shown limited impact on improving patient survival. Targeted therapy and recently investigated approaches such as targeted therapy have shown some tumor regression, but in most cases, tumor recurrence has been observed after initial regression. Therefore, they have a limited impact on prolonging patient survival. Immunotherapy, particularly immunotherapy with specific immune cells, can effectively identify and eliminate cancer cells and has been utilized as a new approach in the past two decades, especially in cancers where conventional methods have limited success. Among the effective immunotherapy methods, using natural killer cells (NK cells) can be one of the promising approaches. Currently, phase I clinical trials have been conducted by our research group in patients with gliomas.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06687681
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06632236 - 5G-EMERALD: A Phase 1 Trial of Amivantamab in High Grade Malignant Brain Tumours Within the 5G Platform (PHASE1, RECRUITING): The purpose of this clinical trial is to evaluate the safety and tolerability of amivantamab and to determine the preliminary antitumour activity of amivantamab administered at the recommended Phase 2 dose (RP2D). In the Phase 1b of this study a biomarker defined arm will be opened, initially in the relapsed GMB setting, enrolling 12 patients. These patients will be treated with amivantamab monotherapy. Amivantamab will be administered intravenously (IV) weekly for the first 4 weeks, then every 2 weeks thereafter until disease progression or unacceptable toxicity. The first dose will be given as a split infusion, 350 mg IV over 4 hours on cycle 1 day 1 and 1400 mg IV over 6 hours on cycle 1 day 2. Subsequent infusions are given at a dose of 1750 mg IV over 2-5 hours in cycle 1 and between 2-3 hours from cycle 2 onwards if the first dose was well-tolerated with no significant toxicity. Progression to Phase 2 is dependent on emergent data and funding.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06632236
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low
- NCT06617208 - Prognostic IntraOperative Biomarkers ideNtification in Tumor rElatEd suRgery (PIONEER Study) (NA, NOT_YET_RECRUITING): INTRODUCTION AND RATIONALE Aggressive brain tumors like glioma have the ability to infiltrate the surrounding healthy brain tissue, disrupting normal neuronal activities and leading to impaired motor and cognitive functions, as well as causing epilepsy. This malignant brain tumor is considered one of the most challenging cancers to treat, with a median survival of 12 to 15 months. Recent findings on direct neuron-tumor interactions indicate that abnormal brain activity in the regions surrounding brain tumors may contribute to develop epilepsy and accelerating tumor growth. Tumors tend to 'fuel' themselves with neurotransmitters released during its 'daily' neuronal firing. Hyperactive neurons in the peritumoral cortex can form excitatory electrochemical synapses with surrounding tumor cells, creating direct communication pathways within the peritumoral microenvironment, which aids in the progression and proliferation of tumor cells via direct and paracrine signalling pathways. However, the specific features of this abnormal brain activity in the peritumoral cortex have not been fully clarified and information on the pathological changes of neuronal activity in glioma patients is largely lacking. To advance more effective treatment strategies, it is crucial to better understand the complex interactions between the tumor and the brain. This is especially important for the group of patients of which many perceive diminished quality of life because of epilepsy, cognitive functioning and language problems after tumor surgery. Furthermore, a thorough understanding is lacking of what tumor resection does to the original hyperactive peritumoral cortex and if resecting this is beneficial for improving postoperative outcome both for epilepsy as well as regarding survival. Therefore, identifying the hyperactive peritumoral cortex and directly addressing its impacts on the brain function and long-term surgical outcome could be a promising novel therapeutic strategy for treating glioma patients. STUDY AIM The measurement focuses on capturing neuronal activity at single-neuron resolution in the peritumoral cortex of glioma patients using cortical depth electrodes. It is well-established that gliomas can remodel the surrounding brain tissue, leading to abnormal neuronal hyperactivity, which contributes to tumor progression and epilepsy. However, the specific neuronal patterns and underlying mechanisms of these changes are not yet fully understood. This study will aim to collect detailed single-neuron recordings in this context, enabling us to map the precise neurophysiological disruptions caused by gliomas. On the long term, this research could lay the groundwork in identifying novel therapeutic approaches by providing critical in-sights into how gliomas alter brain function.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06617208
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06551909 - Radioimmunotherapy in Solid Tumors (Aim 2- Stereotactic Neoadjuvant Radiotherapy for Glioblastoma) (NA, RECRUITING): This is a prospective multicenter study of hypofractionated radiotherapy for the radiation treatment (RT) of solid tumors and in particular for Glioblastoma (in Aim 2). It is based on the results of ongoing studies at our Institute to validate the efficacy of extremely hypofractionated RT in neoadjuvant settings, which observed immunostimulatory effects of RT and the synergy with immune components. The collaboration between San Raffaele Hospital (Milan), the IRCCS Istituto Nazionale dei Tumori Fondazione G. Pascale (Naples) and the San Giuseppe Moscati Hospital of National Relief and High Specialty (Avellino) will ensure that patient recruitment, treatment and monitoring can be translated into facilities of the National Health System using common procedures. The various departments involved will treat patients with the same methods synergistically exploring the immuno/biological factors related to efficacy (and/or toxicity), based on new radioimmunotherapeutic approaches. Clinical and research activity will be developed jointly, drawing on the expertise in radiotherapy, radiomics, oncology, imaging and immunotherapy skills already available.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06551909
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06336291 - A Dose Optimization Study for L19TNF in Combination With Lomustine in Patients With Glioblastoma at Progression or Recurrence (PHASE2, RECRUITING): The trial aims to collect safety, efficacy, exposure, dose- response, pharmacokinetic and pharmacodynamic information of the combination of L19TNF and lomustine at different dose levels in patients with Glioblastoma at progression or recurrence
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06336291
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low
- NCT06297512 - Interventional, Single-arm, Open-label Open-label, Phase II Trial to Evaluate the Role of Anthracycline Infusion After Radio Therapy (RT) in Pediatric and Young Adults With Glioblastoma (pGBM). (PHASE2, RECRUITING): Glioblastoma (GBM) and diffuse intrinsic bridge gliomas (DIPG) only the most aggressive forms of cancer, and their prognosis remains bleak. Currently, the standard of treatment is TMZ concomitant with radiotherapy, and, at the end of combined treatment, as adjuvant therapy. In vitro and in vivo experimental studies have suggested that anthracyclines are effective antineoplastics for the treatment of gliomas. In patients with solid tumors treated with anthracyclines, continuous infusion administration compared with bolus administration has been shown to provide a better safety profile especially with regard to cardiotoxicity. Based on this evidence, this study aims to evaluate the safety and antitumor activity of combined treatment with Dox, WBRT (whole body radiotherapy), and TMZ in pediatric and young adult patients affected by GMB
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06297512
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06136611 - Preoperative Preradiotherapy TTFields (PORTRAIT) (NA, NOT_YET_RECRUITING): PreOperative PreRAdIotherapy Tumour Treating Fields (PORTRAIT) is a Phase I study that will test the safety and feasibility of Optune administered preoperatively and preradiotherapy in patients with a new radiological diagnosis of glioblastoma (GBM). Participants will be required to undergo additional MRI sequencing scans and provide blood, tear fluid and tissue samples over a maximum of 6 months. After the study patients will follow their standard treatment pathway.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06136611
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06102525 - A Phase 1/2a, Open-label, Multicenter, Dose Escalation and Dose Expansion Study Evaluating the Safety, Tolerability, and Efficacy of RZ-001 in Combination With Valganciclovir in Subjects With Glioblastoma (PHASE1, PHASE2, RECRUITING): This is a Phase 1/2a, open-label study to evaluate the safety, tolerability, immunogenicity, and preliminary clinical activity of RZ-001 administered in combination with VGCV in subjects with hTERT-positive GBM.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06102525
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 60 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05842746 - Efficacy and Safety of Elemene Plus Stupp Protocol Versus Stupp Protocol Alone for Newly-diagnosed Glioblastoma: A Multi-center Phase II Randomized Controlled Trial (PHASE2, NOT_YET_RECRUITING): The goal of this phase II randomized clinical trial is to compare the safety and efficacy of Elemene plus Stupp Protocol (the new protocol) and Stupp Protocol alone (the standard protocol) in patients with newly-diagnosed glioblastomas (ndGBMs). The main questions to answer are: * Whether the new treatment protocol (Elemene plus Stupp Protocol) is clinically safe for ndGBM patients. * Whether the new treatment protocol (Elemene plus Stupp Protocol) brings better survival benefits for ndGBM patients compared to the standard-of-care Stupp Protocol. Study participants will be enrolled in 5 hospitals in China and randomly assigned to receive either the new protocol or the standard protocol. The overall survival (OS) rate in the 12th month, the progression-free survival (PFS) rate in the 6th month, OS, PFS, and adverse events assessed by the CTCAE (Common Terminology Criteria for Adverse Events) will be evaluated for all patients.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05842746
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05820191 - B-amyloid as a Marker for GBM Bioimaging (PHASE2, NOT_YET_RECRUITING): This project is aimed at improvement of glioblastoma (GBM) diagnostic strategies for discrimination of tumor progression and chemo- and radiotherapeutic treatment-related changes in brain tissue. The study will elucidate the diagnostic value of PET imaging with use of amyloid-β radioisotope tracer Amyvid (Florbetapir F18) for GBM. The results of the study will provide data for development of new approach for GBM diagnostics.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05820191
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05720078 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-3 (UNITED-3): Applying a Two Phase, Personalized Margin, Reduced Clinical Target Volume Approach (NA, RECRUITING): The goal of this study is to test whether an adaptive radiation therapy (RT), two-phase approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive, two-phase RT approach compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05720078
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05653622 - Simultaneous Integrated Boost FDOPA PET Guided in Patients With Partially- or Non-operated Glioblastoma (PHASE2, RECRUITING): Glioblastoma (GBM) is the most common primary brain cancer in adults. Surgery, chemoradiotherapy (temozolomide TMZ) and then adjuvant TMZ is the standard treatment. But, most patients relapse in a median time of 8-9 months; the median overall survival (OS) ranged from 15 to 18 months. Some frail patients received hypofractionated radiation and concomitant and adjuvant TMZ. For some, the radiation dose is not optimal. Moreover, recurrences develop mainly in the initial tumor site. These two reasons justify increasing the dose. To limit the movements of these fragile patients, the method consists of increasing the dose without increasing the number of sessions by using the Simultaneous Integrated Boost (SIB) which increases the dose in targeted volumes while the rest of the volume receives a minimum dose. A phase I trial showed the possibility of increasing the dose in SIB up to 80 Gy in a part of the GBM enhanced on MRI. FDOPA PET detects certain more aggressive tumor areas, areas likely to recur. Integrating them into the SIB seems appropriate. A phase II trial showed the interest of SIB guided by FDOPA PET in terms of progression-free survival but without impact on OS. This study differed from the one the investigators propose, because a dose and conventional fractionation, identical to that of the European Organization for Research and Treatment of Cancer/National Cancer Information Center (NCIC/EORTC) protocol were delivered, the gliomas were unmethylated MGMT, less likely to respond. Studies with SIB and hypofractionation are often retrospective and for others, hypofractionation was debatable and the dose increase was not based on PET capture but on MRI. However, a prospective phase II study, with SIB and hypofractionation, not integrating FDopa PET has demonstrated the relevance of SIB. In this project, the investigators propose to use the integrated boost technique (SIB) guided by PET FDOPA to increase the radiation dose in GBM, in patients either fragile and partially operated, or only biopsied and for whom the prognosis is the most pejorative.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05653622
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery
- NCT05607407 - Targeting Transsulfuration Via Suppression of Thyroid Hormone Signaling in Progressive Glioblastoma: Phase 2 and Pharmacodynamic Trial of Methimazole in Patients With Progressive Glioblastoma (PHASE2, RECRUITING): The purpose of this study is to test the effectiveness, safety, and tolerability of a drug called Methimazole. The investigational drug, Methimazole is not FDA approved for brain tumors, but it is used to treat thyroid illnesses. Different doses of Methimazole will be given to several study participants with glioblastoma. The first several study participants will receive the lowest dose. If the drug does not cause serious side effects, it will be given to other study participants at a higher dose. The doses will continue to increase for every group of study participants until the side effects occur that require the dose to be lowered. The procedures in this study are research blood draws, physical exams, collection of medical history, MRI scans, and study drug administration.
  Quick read: GBM-specific treatment study for GBM or glioma patients; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05607407
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05502991 - Phase 2 Study to Evaluate the Clinical Efficacy and Safety of Sintilimab Plus Low-dose Bevacizumab in Patients With Glioblastoma of Different Relapse Stages (PHASE2, NOT_YET_RECRUITING): This is an ongoing Phase 2, open-label, single-center, non-randomized study of sintilimab (one anti-PD-1 antibody same as nivolumab approved in China) plus bevacizumab administered in a low dosage schedule in adult (≥ 18 years) participants with a clinical relapse or circulating tumor DNA (ctDNA)-level relapse of glioblastoma (GBM). This study has two non-comparative study groups. Both cohorts will receive the same study drug sintilimab 200mg and bevacizumab 3mg/kg every 3 weeks. A stringent two-step non-randomized process will be used to assign participants to one of the study groups. Neither participants nor doctors but the researcher can choose which group participants are in. No one knows if one study group is better or worse than the other. 60 total participants are expected to participate in this study (30 participants in each cohort). Grouping process: After enrollment, under the standard of care, participants will receive regular tumor in situ fluid (fluid within the surgical cavity, TISF) sampling for ctDNA analysis and recceive regular MRI. The researcher will study the TISF ctDNA and imaging dynamics to determine whether the tumor reaches to ctDNA-level (Cohort 1) or clinical relapse (Cohort 2). At the first step, all timely identified as ctDNA-level relapse tumors will be assigned into the Cohort 1 and receive the study drug immediately, those failed to be timely identified will be assigned into the Cohort 2 and receive the study drug after the clinical relapse. At the second step, once either group reaches the target number, the new participants will be all assigned into the other Cohort.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05502991
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05370079 - Control Cohort CTRL COH (NA, RECRUITING): Autoimmune encephalitis (AE) and paraneoplastic neurological syndromes (PNS) are rare disease that could be difficult to diagnose. So it necessary to obtain numerous sample from different disease to develop more specific diagnosis kit It could be possible through the characterisation of new genetic biomarkers.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05370079
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04752280 - Glioblastoma Radiotherapy Using IMRT or Proton Beams (NA, RECRUITING): Radiation therapy is an integral part of the multimodal primary therapy of glioblastomas. As the overall prognosis in this tumor entity remains unfavorable, current research is focused on additional drug therapies, which are often accompanied by increases in toxicity. By using proton beams instead of photon beams, it is possible to protect large parts of the brain which are not affected by the tumor more effectively. An initial retrospective matched-pair analysis showed that this theoretical physical benefit is also clinically associated with a reduction in toxicity during therapy and in the first few months thereafter. The aim of the GRIPS study is to prospectively test this clinical benefit in a randomized, open-label Phase III study. Patients are treated in the study using either modern photon radiation techniques (standard arm) or proton beams (experimental arm). The primary endpoint is the cumulative toxicity CTC grade 2 and higher in the first 4 months. Secondary endpoints include overall survival, progression-free survival, quality of life, and neurocognition.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04752280
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03548571 - Open Label Randomized Phase II/III Trial of Dendritic Cell Immunotherapy Against Cancer Stem Cells in Glioblastoma Patients Receiving Standard Therapy (DEN-STEM) (PHASE2, PHASE3, RECRUITING): Open, randomized study of a trivalent dendritic cell therapy compared to standard therapy in primary treated patients with IDH wild-type, MGMT-promotor methylated glioblastoma. The IMP is dendritic cells transfected with mRNA of survivin, hTERT og autologous tumor stem cells derived from tumorspheres.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03548571
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT02977780 - INdividualized Screening Trial of Innovative Glioblastoma Therapy (INSIGhT) (PHASE2, RECRUITING): This research study is studying several investigational drugs as a possible treatment for Glioblastoma (GBM). The drugs involved in this study are : * Abemaciclib (arm is currently closed to accrual) * Temozolomide (temodar) * Neratinib (arm is currently closed to accrual) * CC115 (arm is currently closed to accrual) * QBS10072S
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02977780
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07457307 - INSIGHT MRL: INtegrating Biology for Safe Intensification of Glioblastoma Hypofractionated Treatment on the MR-Linac (PHASE1, NOT_YET_RECRUITING): This is a phase 1 study to examine the safety and tolerability of biology-guided dose intensified hypofractionated radiation therapy (RT) using MR-Linac for patients with high grade glioma (HGG). Investigators will enroll 20 patients with Grade 3 or 4, IDH wild-type (IDHwt), HGG. Intraoperative assessment of residual tumor burden will be performed at 6 surgical margins (anterior, posterior, superior, inferior, medial, lateral) using FastGlioma. Each margin will be graded on a scale of 0 to 3, with 0 being no tumor, 1 atypical cell, 2 sparse tumor infiltration, and 3 dense tumor infiltration.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07457307
  Review priority: 150
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07472387 - Impact of Androgen Signaling on the Composition of the Immune Microenvironment in Glioblastomas (NA, NOT_YET_RECRUITING): Glioblastoma (GBM) is the most common and most aggressive primary brain cancer in adults. GBM is more common in men than in women, with a male-to-female ratio of 1.6. Furthermore, being male is associated with a poorer prognosis. These data suggest that sex and/or sexual hormones and more specifically androgens may play a role in the initiation, the growth, and the resistance to treatments of GBM.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07472387
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07218367 - Targeting Infiltrating Glioblastoma Via pH Sensitive Visualization of Tumor and pH Modulation Through Bicarbonate Transporter SLC4A4 (PHASE1, NOT_YET_RECRUITING): Glioblastoma is an infiltrating tumor that is difficult to visualize in surgery and on standard images. A special pH (acid-base) related magnetic resonance imaging (MRI) has been developed to better see infiltrating tumor. In this safety study, the investigators will carry out increased levels of pH based resections of infiltrating tumor to assess the tolerability in VA populations.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07218367
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06368934 - Sub-lobectomy for IDH Wild-type and TERT Promoter Mutant Glioblastoma: A Prospective, Interventional, Multicenter, Randomized Controlled Trial (NA, NOT_YET_RECRUITING): Glioblastoma is recognized as the most common and aggressive form of primary malignant brain tumor, with treatment options that are limited and prognosis that is extremely poor, showing median progression-free survival of 12 months and median overall survival of less than 18 months. Surgical resection plays a critical role in the treatment, with the extent of resection significantly impacting patient outcomes. Historical approaches to surgical resection have evolved, moving from radical strategies to more conservative ones that aim to preserve normal brain function while removing the tumor as completely as possible. Recent studies have suggested that increasing the extent of surgical resection, particularly along the T2 FLAIR border rather than the traditional T1-enhanced border, can significantly improve patient prognosis. There is, however, a lack of consensus on the optimal surgical approach, and the heterogeneity of tumors presents challenges in standardizing surgical strategies. Extended resection has been shown to prolong survival, and novel intraoperative molecular diagnostics have emerged to improve accuracy in tumor classification and prognosis. Building on these advancements, a multicenter, prospective, randomized controlled trial is proposed to evaluate the efficacy of sub-lobectomy in treating IDH wild-type/TERTp-mutant glioblastoma, aiming to improve evidence levels and establish standardized surgical practices for this devastating disease.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06368934
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05669820 - Antisecretory Factor During Concomitant and Adjuvant Therapy of Primary Glioblastoma, a Randomised, Prospective and Double Blinded Study (PHASE2, PHASE3, RECRUITING): This is a randomised, double blinded and multiple center , Phase 2 study in patients with newly diagnosed glioblastoma. Participants will receive an egg powder enriched for antisecretory factor (AF), Salovum, or a placebo egg powder daily from 2 days before concomitant radio-chemo therapy or chemotherapy until 14 days after finalisation plus during adjuvant chemotherapy.The primary aims of are overall survival at 6 and 12 months after diagnosis
  Quick read: GBM-specific treatment study for newly diagnosed GBM; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05669820
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07326566 - A Phase 2 Randomized, Multicenter Study to Evaluate the Efficacy and Safety of Silevertinib, an Oral EGFR Inhibitor, in Combination With Temozolomide in Patients With Newly Diagnosed Glioblastoma With Unmethylated MGMT Promoter and EGFRvIII (PHASE2, RECRUITING): The purpose of this study is to see if combining silevertinib with temozolomide after surgery and radiotherapy helps treat newly diagnosed glioblastoma (GBM) better than using temozolomide alone in the maintenance setting. Specifically, this study is being done to find answers to the following questions: * How much of the study drugs (silevertinib combined with temozolomide) should be given to participants with GBM? * What are the side effects participants have when taking the study drug (silevertinib combined with temozolomide)? * Can the study drug (silevertinib combined with temozolomide) help participants with GBM live longer without disease progression compared to treatment with temozolomide alone?
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07326566
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07134842 - Window Studies in Glioblastoma: A Phase I Trial Investigating Neoadjuvant Ipilimumab in Newly Diagnosed Glioblastoma (PHASE1, RECRUITING): WinGlio is a phase I study investigating neoadjuvant (before surgery) ipilimumab ( a type of immunotherapy drug) in patients with newly diagnosed glioblastoma (a form of brain cancer). Participants will receive up to 2 cycles of ipilimumab prior to the standard of care treatments for this patient group which can include debulking surgery and chemoradiation. The aim of giving the ipilimumab to the participants is to see if it is safe to treat patients with this condition with ipilimumab and also to see if the drug helps to reduce or control the patient's disease.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07134842
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06047379 - An Open-label Phase 1/2 Dose Finding, Safety and Efficacy Study of Oral NEO212 in Patients With Astrocytoma IDH-mutant, Glioblastoma IDH-wildtype or Uncontrolled Brain Metastasis in Patients With Select Solid Tumors. (PHASE1, PHASE2, RECRUITING): This multi-site, Phase 1/2 clinical trial is an open-label study to identify the safety, pharmacokinetics, and efficacy of a repeated dose regimen of NEO212 alone for the treatment of patients with radiographically-confirmed progression of Astrocytoma IDH- mutant, Glioblastoma IDH-wildtype, and the safety, pharmacokinetics and efficacy of a repeated dose regimen of NEO212 when given with select SOC for the treatment of solid tumor patients with radiographically confirmed uncontrolled metastases to the brain. The study will have three phases, Phase 1, Phase 2a and Phase 2b.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06047379
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05911230 - Advanced Diffusion MRI to Differentiate Tumor Recurrence From Pseudoprogression in Patients With Glioblastoma and Brain Metastases- AiD GLIO Pilot Trial (NA, RECRUITING): This pilot study investigates whether advanced diffusion-weighted MRI (ADW-MRI) can differentiate between true tumor progression (TP) and a pseudoprogression (PsP) in patients with glioblastoma (GBM) or brain metastases.
  Quick read: GBM-specific treatment study for GBM or glioma patients; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05911230
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05765812 - A Phase 1/2 Open-label Study of Debio 0123 in Combination With Temozolomide in Adult Participants With Recurrent or Progressive Glioblastoma and of Debio 0123 in Combination With Temozolomide and Radiotherapy in Adult Participants With Newly Diagnosed Glioblastoma (PHASE1, PHASE2, RECRUITING): The primary purpose of the Phase 1 (Dose Escalation) of this study is to identify the dose-limiting toxicities (DLTs) of Debio 0123 combined with temozolomide (TMZ) (Arm A) and with TMZ and radiotherapy (RT) (Arms B and C) and to characterize the safety and tolerability of these combinations in adult participants with glioblastoma (GBM). Arm B which was previously added to the protocol, has been permanently halted per the safety monitoring committees' decision on the safety findings of this arm. The primary purpose of Phase 1 (Dose expansion) of the study is to assess the doses studied under Phase 1 (Dose Escalation) Arm A and identify the recommended dose (RD) for further development. The Phase 2 will start once the RD Phase 1 has been defined. The primary objective of Phase 2 is to assess the efficacy of Debio 0123 at the RD for further development in combination with TMZ, compared to the standard of care (SOC) in adult participants with GBM.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05765812
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 60 (match), recurrence_max=0 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05450744 - A Phase 1 Safety and Dose Finding Study of 131I -TLX101 Plus Standard of Care in Patients With Newly Diagnosed Glioblastoma (PHASE1, RECRUITING): This is an open label, single arm, parallel-group, multicentre, and dose finding study to evaluate the safety of ascending radioactive dose levels of 131I-TLX101 administered intravenously in combination with best standard of care in newly diagnosed GBM patients.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05450744
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT04188535 - RELAY: Repeated Magnetic Resonance Imaging Examinations to Analyze and Assess Your Cancer: A Prospective Study on the Use of Serial Magnetic Resonance Imaging in the Assessment of Changes During Treatment With Radiation Therapy (NA, RECRUITING): This is a phase 1 study to determine the feasibility and utility of using serial magnetic resonance imaging (MRI) to assess treatment response during and after radiation therapy (standard of care cancer treatment) for participants with advanced esophageal cancer, glioblastoma, prostate cancer, vulvar cancer or pediatric glioma. The research study procedures include three MRI scans (one before, one during, and one after standard of care cancer radiation therapy) for participants with advanced esophageal cancer, glioblastoma, prostate cancer, vulvar cancer or pediatric glioma. The research study procedures include: * Screening for eligibility * Three MRI scans
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04188535
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT03603405 - Phase I-II Study Evaluating HSV-tK + VALACYCLOVIR GENE THERAPY Combination With Radiotherapy and Chemotherapy for Newly Diagnosed Anaplastic Astrocytoma and Glioblastoma Multiforme. (PHASE1, PHASE2, RECRUITING): Study to assess the safety and efficacy of HSV-tk (gene therapy), valacyclovir, radiotherapy and chemotherapy in newly diagnosed glioblastoma multiforme (GBM) or anaplastic astrocytoma (AA).
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03603405
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07179328 - Assessment of Safety and Feasibility of Focused Ultrasound Next Generational Dome Helmet Mediated Blood-Brain Barrier Disruption for the Treatment of High-Grade Glioma in Patients Undergoing Standard Chemotherapy (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and feasibility of focused ultrasound (FUS)-mediated blood-brain barrier (BBB) disruption using the Next Generation Dome Helmet (NGDH) in adults with glioblastoma (GBM) undergoing the maintenance phase of the standard "Stupp protocol". Participants will: * Undergo repeated FUS BBB disruption treatments during the maintenance phase of temozolomide (TMZ) chemotherapy. * Receive intravenous ultrasound contrast (DEFINITY®) prior to each FUS session to facilitate targeted BBB disruption. * Undergo serial MRI scans and clinical assessments to evaluate safety and the extent of BBB opening. * Provide blood samples (and tumor tissue if available) for biomarker analysis related to BBB permeability, tumor presence, and treatment response. * Be followed for progression-free survival (PFS) and overall survival (OS) during routine neuro-oncology visits until end of life.
  Quick read: GBM-related treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07179328
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04523688 - Vaccination With Autologous Dendritic Cells Loaded With Autologous Tumour Homogenate in Glioblastoma: a Phase II Study (PHASE2, RECRUITING): Single arm, monocentric trial to assess the safety and the progression-free survival related to the combined treatment of dendritic cell vaccine loaded with autologous tumor homogenate and temozolomide in patients operated for glioblastoma and then treated with standard radiochemotherapy (according to Stupp regimen).
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04523688
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03861299 - The SAFE-Trial: Safe Surgery for Glioblastoma Multiforme: Awake Craniotomy Versus Surgery Under General Anesthesia. A Multicenter Prospective Randomised Controlled Study (NA, RECRUITING): The trial is designed as a multicenter randomized controlled study. 246 patients with presumed Glioblastoma Multiforme in eloquent areas on diagnostic MRI will be selected by the neurosurgeons according the eligibility criteria (see under). After written informed consent is obtained, the patient will be randomized for an awake craniotomy (AC) (+/-123 patients) or craniotomy under general anesthesia (GA) (+/-123 patients), with 1:1 allocation ratio. Under GA the amount of resection of the tumour has to be performed within safe margins as judged by the surgeon during surgery. The second group will be operated with an awake craniotomy procedure where the resection boundaries for motor or language functions will be identified by direct cortical and subcortical stimulation. After surgery, the diagnosis of GBM will have to be histologically confirmed. If GBM is not histologically confirmed, patients will be considered off-study and withdrawn from the study. These patients will be followed-up according to standard practice. Thereafter, patients will receive the standard treatment with concomitant Temozolomide and radiation therapy and standard follow up. Total duration of the study is 5 years. Patient inclusion is expected to take 4 years. Follow-up is 1 year after surgery. Statistical analysis, cost benefit analysis and article writing will take 3 months.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03861299
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 80 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07439172 - A Multi-Centered Evaluation of Pre-Radiation Chemotherapy for Newly Diagnosed High-Grade Glioma (HGG): An Approach to Drug Screening That Requires Confirmation (PHASE2, NOT_YET_RECRUITING): Better treatments are needed for high-grade gliomas (HGG), and new ways of treating this disease should be tested. The investigators want to see if giving medicine before radiation works well. After radiation, MRI scans can be harder to understand because radiation changes how the brain looks on the scan. If new medicines are given before radiation, the scans are easier to read. First, the investigators need to find out if giving chemotherapy early works using a drug we already know can treat gliomas. The investigators will start with temozolomide, which is the only chemotherapy approved by the FDA for HGG. If this approach is successful, the investigators can then test new drugs using this screening method.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07439172
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07021339 - Randomized, Controlled Trial of Anterior Temporal Lobectomy Versus Gross Total Resection in Newly-diagnosed Temporal Glioblastoma (ATLAS/NOA-29) (PHASE3, RECRUITING): The ATLAS/NOA-29 trial is a prospective, multicenter, phase III randomized controlled study evaluating whether anterior temporal lobectomy (ATL), a standardized resection technique adapted from epilepsy surgery, improves clinical outcomes in patients with newly diagnosed glioblastoma of the anterior temporal lobe compared to conventional gross-total resection (GTR). The rationale is based on the concept of glioblastoma as a diffusely connected tumor network, with infiltrative spread extending beyond MRI-detectable tumor margins. ATL offers a reproducible supramarginal resection approach within anatomical boundaries that are routinely respected in epilepsy surgery. Patients are randomized intraoperatively in a 1:1 ratio following histopathological confirmation via intraoperative frozen section procedure. The trial's primary objective is to demonstrate superiority of ATL in overall survival (OS), while confirming non-inferiority in health-related quality of life (QoL), measured by the global health status scale of the European Organisation for Research and Treatment of Cancer (EORTC) - Quality of Life Questionnaire Core 30 (QLQ-C30). Secondary outcomes include progression-free survival (PFS), seizure control, neurocognitive functioning, and longitudinal assessments of selected EORTC QLQ-C30 and BN20 domains. A total of 178 patients will be enrolled over three years, with a minimum follow-up of three years. An interim safety analysis after inclusion of 57 patients will assess functional outcome differences using the modified Rankin Scale (mRS) at 6 months postoperatively. The study is powered (\>80%) to detect a survival benefit assuming a median OS increase from 17 to 27.5 months. If proven superior to GTR, ATL could emerge as the preferred surgical strategy for isolated temporal lobe glioblastoma, offering robust evidence in favor of extending supramarginal resection principles to the broader context of glioblastoma care.
  Quick read: GBM-related treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07021339
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06991101 - Randomized Phase 2 Trial of Ruxolitinib in Combination With Radiation and Temozolomide Compared to Radiation and Temozolomide for Newly Diagnosed Glioblastoma. (PHASE2, RECRUITING): The purpose of this research is to test the safety and effectiveness of the investigational drug ruxolitinib when it is combined with standard of care treatment (radiation therapy and temozolomide) for the treatment of newly diagnosed glioblastoma. Half the people in the study will be assigned to take the study drug ruxolitinib in addition to the standard of care temozolomide and radiation therapy and the other half will be assigned to the standard of care temozolomide and radiation therapy only. This assignment will be randomized in a 1-to-1 ratio, like the flip of a coin.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06991101
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06017063 - Coaching for Coping in Glioblastoma Patients and Caregivers and Its Association With Compliance to TTFields (NA, NOT_YET_RECRUITING): The aim is to improve patients' compliance to TTFields therapy by a psychological video intervention in a multi-center, randomized controlled trial.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06017063
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05929495 - Phase 2, Open-label, Single-arm Study on the Use of Metformin as Adjunctive Therapy in High-grade Glioma (PHASE2, RECRUITING): About 75% of CNS malignant tumors are classified as gliomas and the IDH-wildtype glioblastoma (GBM) represents the most aggressive form among CNS malignancies. This is a nationwide single-center phase II drug clinical trial with an approximate duration of 32 months. The clinical trial will be single-arm to evaluate the biological activity and effects of metformin in combination with TMZ in patients with GBM.
  Quick read: GBM-related treatment study for newly diagnosed GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05929495
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05909618 - An Open Label Phase 2 Study of Intravenously Administered Crizanlizumab Alone or in Combination With Nivolumab for Glioblastoma and Melanoma With Brain Metastases (PHASE2, RECRUITING): A single-center, open-label, non-randomized phase I/II study to evaluate the efficacy, safety and tolerance of crizanlizumab monotherapy and in combination with nivolumab in patients with advanced glioblastoma (GB) who exhausted standard of care (SOC) therapy, patients with metastatic brain melanoma (MBM) and patients with newly diagnosed unmethylated GB. Subjects will be screened for up to 28 days prior to treatment initiation. Eligible subjects will be allocated to one of 3 cohorts: Cohort 1: Patients with metastatic melanoma with primarily diagnosed or newly progressing brain metastases who failed immunotherapy. Cohort 2: Patients with recurrent or progressing GB following primary radiation therapy and temozolomide. Patients may have failed up to 2 prior systemic treatment lines (including temozolomide as adjuvant therapy) and are candidates for further treatment. Cohort 3: Patients with newly diagnosed GB who were evaluated for methylguanine-DNA methyltransferase(MGMT) methylation status and have un-methylated MGMT promotor-therefore, they are not candidates for maintenance temozolomide therapy.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05909618
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05879367 - An Open-label, Phase 1b Study to Evaluate the Safety and Tolerability of Eflornithine Plus Temozolomide in Patients With Newly Diagnosed Glioblastoma or Astrocytoma (PHASE1, RECRUITING): The purpose of this study is to establish the recommended phase 2 dose of eflornithine in combination with temozolomide in patients whose glioblastoma or astrocytoma is newly diagnosed, and to evaluate safety and tolerability of this combination at that dose.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05879367
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05864534 - A Phase 2a Trial of Immune Modulation in Combination With Ultrasound-mediated Blood Brain Barrier Opening in Patients With Newly Diagnosed Glioblastoma (PHASE2, RECRUITING): Brain tumor treatment is hampered by the blood-brain barrier (BBB). This barrier prevents drugs carried in the bloodstream from getting into the brain. If the BBB can be opened, making it temporarily more permeable, drugs may able to better reach the brain tumor. In this trial we will implant a novel device with 9 ultrasound emitters, allowing temporary and reversible opening of the BBB to maximize brain penetration of drugs that modulate the immune system. The device will be implanted after radiation is completed. Immune modulating drugs will be given every 3 weeks in conjunction with activation of the device to open the BBB. The objectives of this trial are to establish whether it is safe and feasible to administer immune modulating drugs in this manner, and identify whether the treatment is effective in treating glioblastoma.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05864534
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05271240 - A Phase III Randomized Trial of Repeated Superselective Intraarterial Cerebral Infusion (SIACI) of Bevacizumab (Avastin) With Temozolomide and Radiation Compared to Temozolomide and Radiation Alone in Newly Diagnosed Glioblastoma (GBM) (PHASE3, RECRUITING): Primary brain cancer kills up to 10,000 Americans a year. These brain tumors are typically treated by surgery, radiation therapy and chemotherapy, either individually or in combination. Present therapies are inadequate, as evidenced by the low 5-year survival rate for brain cancer patients, with median survival at approximately 12 months. Glioma is the most common form of primary brain cancer, afflicting approximately 7,000 patients in the United States each year. These highly malignant cancers remain a significant unmet clinical need in oncology. The investigators have completed a Phase I clinical trial that has shown that Superselective Intraarterial Cerebral Infusion (SIACI) of Bevacizumab (BV) is safe up to a dose of 15mg/kg in patients with recurrent malignant glioma. Additionally, the investigators have shown in a recently completed Phase I/II clinical trial, that SIACI BV improves the median progression free survival (PFS) from 4-6 months to 11.5 months and overall survival (OS) from 12-15 months to 23 months in patients with newly diagnosed GBM. Therefore, this two-arm, randomized trial (2:1) is a follow up study to these trials and will ask simple questions: Will this repeated SIACI treatment regimen increase progression free survival (PFS-primary endpoint) and overall survival (OS-secondary endpoint) when compared with standard of care in patients with newly diagnosed GBM? Exploratory endpoints will include adverse events and safety analysis as well as quality of life (QOL) assessments. The investigators expect that this project will provide important information regarding the utility of repeated SIACI BV therapy for newly diagnosed GBM and may alter the way these drugs are delivered to our patients in the near future.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05271240
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05084430 - A Phase I/II Study of Pembrolizumab and M032 (NSC 733972), a Genetically Engineered HSV-1 Expressing IL-12, in Patients With Recurrent/Progressive and Newly Diagnosed Glioblastoma Multiforme, Grade 3 or Grade 4 Astrocytoma, or Gliosarcoma (PHASE1, PHASE2, RECRUITING): This Phase I (Cohort I and Cohort II) and Phase II trial is designed to confirm the safety and tolerability of Pembrolizumab when given in conjunction with M032, an Oncolytic Herpes Simplex Virus (oHSV) that expresses IL-12 and perform the Phase II portion using a Recommended Phase 2 Dose (RP2D) of M032 (provided by the Phase I) when given in conjunction with Pembrolizumab for recurrent malignant glioma (glioblastoma multiforme, anaplastic astrocytoma, or glio-sarcoma).
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05084430
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05052957 - Phase II Trial O6-benzylguanine(BG) and Temozolomide(TMZ) Therapy of Glioblastoma Multiforme (GBM) With Infusion of Autologous P140K MGMT+Hematopoietic Progenitors to Protect Hematopoiesis (PHASE2, RECRUITING): This phase II trial studies the effect of P140K MGMT hematopoietic stem cells, O6-benzylguanine, temozolomide, and carmustine in treating participants with supratentorial glioblastoma or gliosarcoma who have recently had surgery to remove most or all of the brain tumor (resected). Chemotherapy drugs, such as 6-benzylguanine, temozolomide, and carmustine, work in different ways to stop the growth of tumor cells, either by killing the cells, by stopping them from dividing. Placing P140K MGMT, a gene that has been created in the laboratory into bone marrow making the bone more resistant to chemotherapy, allowing intra-patient dose escalation which kills more tumor cells while allowing bone marrow to survive.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05052957
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT04555577 - Phase I Trial of DNA-PK Inhibitor (M3814) in Combination With Radiation and Adjuvant Temozolomide in Newly Diagnosed MGMT Unmethylated Glioblastoma (PHASE1, RECRUITING): This phase I trial investigates the side effects and best dose of Peposertib, and to see how well it works in combination with radiation therapy in treating patients with newly diagnosed MGMT unmethylated glioblastoma or gliosarcoma. Radiation therapy uses high energy x-rays to kill tumor cells and shrink tumors. Peposertib may further stop the growth of tumor cells by blocking some of the enzymes needed for cell growth. Chemotherapy drugs, such as temozolomide, work in different ways to stop the growth of tumor cells, either by killing the cells, by stopping them from dividing, or by stopping them from spreading. Giving Peposertib with radiation therapy may work better than radiation therapy alone in treating patients with glioblastoma or gliosarcoma.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04555577
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 3 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT03213002 - Phase I/II Study of Oral Capecitabine and Temozolomide (CAPTEM) for Newly Diagnosed Glioblastoma (GBM) (PHASE1, PHASE2, RECRUITING): The purpose of this study is to evaluate the safety and efficacy of administering the medication capecitabine along with temozolomide when you start your monthly regimen of oral temozolomide for the treatment of your newly diagnosed glioblastoma multiforme (GBM). Capecitabine is an oral chemotherapy that is given to patients with other types of cancer. The study will evaluate whether the dosage of 1500 mg/m2 of capecitabine is tolerable after radiation, when taken along with temozolomide. It will also try to determine if the medication capecitabine helps patients respond to treatment for a longer period of time compared to just temozolomide alone, which is the standard of care.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03213002
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT02861898 - Phase I/II Trial of Super-selective Intra-arterial Repeated Infusion of Cetuximab for the Treatment of Newly Diagnosed Glioblastoma (PHASE1, PHASE2, RECRUITING): Primary brain cancer kills up to 10,000 Americans a year. These brain tumors are typically treated by surgery, radiation therapy and chemotherapy, either individually or in combination. Present therapies are inadequate, as evidenced by the low 5-year survival rate for brain cancer patients, with median survival at approximately 12 months. Glioma is the most common form of primary brain cancer, afflicting approximately 7,000 patients in the United States each year. These highly malignant cancers remain a significant unmet clinical need in oncology. GBM often has a high expression EFGR (Epidermal Growth Factor Receptor) which is blocked by Cetuximab (CTX). The investigators have recently completed a separate Phase I clinical trial using superselective intra-arterial cerebral infusion (SIACI) of CTX after blood brain barrier disruption (BBBD) for recurrent GBM (Chakraborty et al, in revision, Journal of Neurooncology). The investigators found that intra-arterial infusion of CTX is well tolerated with few adverse effects. The investigators hypothesize that in patients with newly diagnosed GBM, repeated SIACI of this drug after BBBD will be safe and efficacious for our patients when combined with standard chemoradiation (STUPP protocol). This trial will be a non-randomized open label Phase I/II clinical trial. In addition to standard chemotherapy and radiation therapy (STUPP protocol) the patient will be given CTX intra-arterially after BBBD for a total of three doses at approximately post surgery days 30, 120 and 210.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02861898
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07211841 - Correlative Analysis Between Magnetic Resonance Spectroscopy (MRS) and Essential Clinicobiological Data in Glioblatoma Multiforme (GBM) (NA, NOT_YET_RECRUITING): Glioblastoma multiforme (GBM) is the most common primary brain tumor, and it is well-known to be associated with a poor prognosis. MRI is the key medical technique for the diagnosis and the follow-up of GBM. By allowing for MRS studies, MRI permits a non-invasive characterization of the TME of GBM, including their metabolic characterization. The investigators propose to address the link between the MRS profile of GBM and basic clinical and biological parameters, with the aim of : i) identifying correlations between these parameters, ii) attempting to integrate clinical, biological and spectroscopic profiles of GBM. The investigators plan to recruit 30 newly diagnosed GBM patients for which surgery / radiochemotherapy will be proposed in the Medical oncology unit of Amiens University Hospital. Following inclusion of patients with probable GBM, MRS study will be performed during the first (pre-therapeutic) MRI examination. Basic clinical and biological parameters of the blood (CRP, complete blood count, fibrinogen, lactate and choline) will be assessed. A metabolomic study will also be performed on the plasma of GBM patients before any therapeutics. A second biological, post-therapeutic assesment (one month after surgery/radiochemotherapy) will allow the same analyses (basic biological parameters + plasma metabolomics), in order to examine the stability of the blood parameters.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07211841
  Review priority: 143
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07459101 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-4 (UNITED-4): Prospective Evaluation of FLAIR-Guided Clinical Target Volume Reduction (NA, RECRUITING): This study builds on the results of prior studies (UNITED and UNITED-3). The goal of UNITED-4 is to test whether an adaptive radiation therapy (RT) therapy approach ('dose painting'), with reduced margins, impacts approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive RT approach with reduced margins compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life * Longitudinal imaging features
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07459101
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07003542 - Targeting Macrophage Migration Inhibitory Factor: A Phase 2 and Pharmacodynamic Study of Sitagliptin in Patients With Progressive Grade 4 Gliomas (PHASE2, RECRUITING): The purpose of this study is to evaluate whether treating glioblastoma patients with sitagliptin can improve immune response against the tumor by targeting specific immune cells called myeloid-derived suppressor cells (MDSCs) that suppress your body's natural immune response against cancer. Sitagliptin is an investigational drug for this condition that works by inhibiting an enzyme called dipeptidyl peptidase 4 (DPP-4), which MDSCs rely on to enter the brain and function. While sitagliptin is FDA-approved for diabetes treatment, its use in glioblastoma is investigational (experimental).
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07003542
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low
- NCT06418113 - Neoadjuvant Radio-chemotherapy Safety Pilot Study in Patients With Glioblastoma (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and efficacy of neoadjuvant radiochemotherapy in the surgical resection of glioblastoma (GBM). The main questions it aims to answer are: * What is the safety profile of neoadjuvant radiochemotherapy in terms of neurological deficit, radionecrosis, edema, headache, wound dehiscence, infection, and cerebrospinal fluid fistula? * What is the efficacy of neoadjuvant radiochemotherapy in terms of progression-free survival, overall survival, cognitive function, and quality of life? Participants will undergo the following tasks and treatments: * Stereotactic biopsy and diagnosis confirmation. * Conformal hypofractionated stereotactic radiotherapy with concurrent temozolomide. * Supramarginal resection guided by 5-ALA under intraoperative neurophysiological monitoring. * Maintenance temozolomide administration for 6 months. Researchers will compare the group receiving neoadjuvant radiochemotherapy to the control group following the standard Stupp protocol to assess safety and efficacy outcomes.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06418113
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06388733 - A Phase 3, Open-label, Randomized 2-arm Study Comparing the Clinical Efficacy and Safety of Niraparib With Temozolomide in Adult Participants With Newly-diagnosed, MGMT Unmethylated Glioblastoma (PHASE3, RECRUITING): The goal of this Phase 3 clinical trial is to compare the efficacy of niraparib versus temozolomide (TMZ) in adult participants with newly-diagnosed, MGMT unmethylated glioblastoma multiforme (GBM). The main question it aims to answer is: Does niraparib improve overall survival (OS) compared to TMZ? Participants will be randomly assigned to one of two treatment arms: niraparib or TMZ. * study drug (Niraparib) or * comparator drug (Temozolomide - which is the standard approved treatment for MGMT unmethylated glioblastoma). The study medication will be taken daily while receiving standard of care radiation therapy (RT) for 6-7 weeks. Participants may continue to take the niraparib or TMZ adjuvantly as long as the cancer does not get worse or completion of 6 cycles of treatment (TMZ). A total of 450 participants will be enrolled in the study. Participants' tasks will include: * Complete study visits as scheduled * Complete a diary to record study medication
  Quick read: GBM-related treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06388733
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low
- NCT06356883 - A Randomized Phase II Study on Intraarterial Carboplatin Combined With Caelyx Compared to Intraarterial Carboplatin Combined With Etoposide Phosphate for Progressing Glioblastoma at First or Second Relapse (PHASE2, RECRUITING): The standard of care for glioblastoma (GBM) treatment involves maximal resection followed by concomitant radiotherapy and temozolomide. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is inevitable. At relapse, there is no consensus regarding the optimal therapeutic strategy. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which impedes drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, can produce responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival (OS) 23 months. How can the OS and PFS be improved? By combining chemotherapeutic agents with different mechanisms of action. Study design: In this phase II trial, treatment will be offered at relapse. Surgery will be performed for cytoreduction if it is warranted, followed with a combination IA carboplatin + IA Cealyx (liposomal doxorubicin) or IA carboplatin + IA etoposide phosphate. Toxicity will be assessed according to the NCIC common toxicity criteria. Treatment will consist in either IA carboplatin (400 mg/m\^2) + IA Cealyx (30 mg/m\^2) or IA carboplatin (400 mg/m\^2) + IA etoposide phosphate (400 mg/m\^2) every 4-6 weeks (1 cycle). Up to twelve cycles will be offered. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. Primary outcome will PFS and tumor response. Secondary outcome will include median OS, toxicity, quality of life (QOL), neurocognition (NC). Putting together these data will allow to correlate clinical and radiological response to QOL and NC.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06356883
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06186401 - Phase 1 Study of Autologous Anti-EGFRvIII synNotch Receptor Induced Anti-EphA2/IL-13R alpha2 CAR (E-SYNC) T Cells in Adult Participants With EGFRvIII+ Glioblastoma (PHASE1, RECRUITING): This phase I trial tests the safety, side effects, and best dose of E-SYNC chimeric antigen receptor (CAR) T cells after lymphodepleting chemotherapy in treating patients with EGFRvIII positive (+) glioblastoma. Chimeric antigen receptor (CAR) T-cell therapy is a type of treatment in which a patient's T cells (a type of immune system cell) are changed in the laboratory so the CAR T cells will attack cancer cells. T cells are taken from a patient's blood. Then the gene for a special receptor that binds to a certain protein on the patient's cancer cells is added to the T cells in the laboratory. The special receptor is called a chimeric antigen receptor. Large numbers of the CAR T cells are grown in the laboratory and given to the patient by infusion for treatment of certain cancers. Lymphodepleting chemotherapy with cyclophosphamide and fludarabine before treatment with CAR T cells may make the CAR T cells more effective.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06186401
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05106296 - Repurposing Ibrutinib for Chemo-Immunotherapy in a Phase 1b Study of Ibrutinib With Indoximod Plus Metronomic Cyclophosphamide and Etoposide for Pediatric Patients With Brain Cancer (PHASE1, RECRUITING): Recent lab-based discoveries suggest that IDO (indoleamine 2,3-dioxygenase) and BTK (Bruton's tyrosine Kinase) form a closely linked metabolic checkpoint in tumor-associated antigen-presenting cells. The central clinical hypothesis for the GCC2020 study is that combining ibrutinib (BTK-inhibitor) with indoximod (IDO-inhibitor) during chemotherapy will synergistically enhance anti-tumor immune responses, leading to improvement in clinical response with manageable overlapping toxicity. The GCC2020 trial is a prospective open-label phase 1 trial to determine the best safe dose of the BTK-inhibitor ibrutinib to use in combination with previously studied chemo-immunotherapy regimens comprised of the investigational IDO-inhibitor indoximod plus oral palliative chemotherapy for participants, age 6 to 25 years, with relapsed or refractory primary brain cancer. Those previously treated with indoximod-based therapy may be eligible, including prior treatment via the phase 2 indoximod study (GCC1949, NCT04049669), the now closed phase 1 study (NLG2105, NCT02502708), or any expanded access (compassionate use) protocols. Ibrutinib will be combined with either indoximod plus oral cyclophosphamide and etoposide (Regimen A) or indoximod plus oral temozolomide (Regimen B). No cross-over between these two regimens will be allowed. Dose-escalation cohorts will determine the best safe dose of ibrutinib for each of these regimens. This will be followed by expansion cohorts, using ibrutinib at the best safe dose for each regimen, to allow assessment of preliminary evidence of efficacy.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05106296
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04678648 - A Phase Ia/Ib, Open Label, Multi-center, Non-randomized Dose Escalation and Dose Expansion Study of RSC-1255 Alone or in Combination With Hydroxychloroquine in Patients With Advanced Solid Tumor Malignancies (PHASE1, RECRUITING): RSC-101 is a Phase 1a/1b clinical trial of RSC-1255 in adult study participants with advanced solid tumor malignancies who are intolerant of existing therapies known to provide clinical benefit, have disease that has progressed after standard therapy, or have previously failed other therapies. The study has two phases. The purpose of Phase 1a (Dose Escalation) is to confirm the appropriate treatment dose and Phase 1b (Dose Expansion) is to characterize the safety and efficacy of RSC-1255.
  Quick read: GBM-related treatment study for GBM or glioma patients; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04678648
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04623931 - Phase II Trial of Treatment Intensification for IDH Wildtype, Non-Histological Glioblastoma, Gliomas (IDH Wildtype Lower Grade Glioma Treatment Intensification) (PHASE2, RECRUITING): This phase II trial studies how well temozolomide and radiation therapy work in treating patients with IDH wildtype historically lower grade gliomas or non-histological molecular glioblastomas. Radiation therapy uses high-energy x-rays to kill tumor cells and shrink tumors. Giving chemotherapy with radiation therapy may kill more tumor cells. Drugs used in chemotherapy, such as temozolomide, work in different ways to stop the growth of tumor cells, either by killing the cells, by stopping them from dividing, or by stopping them from spreading. The goal of this clinical research study is to compare receiving new radiation therapy doses and volumes to the prior standard treatment for patients with historically grade II or grade III IDH wild-type gliomas, which may now be referred to as IDH wildtype molecular glioblastomas at some institutions. Receiving temozolomide in combination with radiation therapy may also help to control the disease.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04623931
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03672721 - A Phase II Study in Relapsing Glioblastoma of Intraarterial Concurrent Chemoradiation Therapy Using IA Carboplatin (PHASE1, PHASE2, RECRUITING): Treatment of glioblastoma involves an optimal surgery, followed by a combination of radiation and temozolomide chemotherapy. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is the norm. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which limits drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, the investigators have observed responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival 23 months. How can this be improved? By coupling radiation with a chemotherapeutic which is also a potent radiosensitizer such as carboplatin. Study design: In this phase I/II trial, patients will be treated at recurrence; a surgery will be performed for cytoreduction and to obtain tumor sample, followed with a combination of re-irradiation and IA carboplatin chemotherapy. A careful escalation scheme from 1.5Gy/fraction up to 3.5Gy/fraction will allow the investigators to determine the optimal re-irradiation dose (10 fractions of radiation over 2 weeks). Toxicity will be assessed according to the NCIC common toxicity criteria. Combined with radiation, patients will receive 2 treatments of IA carboplatin, 400 mg/m2, 4 hours prior to the first and the sixth radiation fraction. IA treatments will then be continued on a monthly basis, up to a total of 12 months, or until progression. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. The investigators will also acquire a sequence that enables the measurement of cerebral blood flow, cerebral blood volume and blood vessel permeability that are all relevant to understand the delivery of therapeutics to the CNS. Primary outcome will be OS and PFS. Secondary outcome will be QOL, neurocognition, and carboplatin delivery. In vitro intracellular carboplatin accumulation: Tumor samples from re-operation will be be analyzed for intracellular Pt concentration by ICP-MS. The amount of Pt bound to DNA will be measured. The level of apoptosis will be determined for each of the sample. Putting together these data will allow to correlate clinical and radiological response to QOL, NC (MOCA), and to delivery surrogates for the IA infusion and intracellular penetration of carboplatin.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03672721
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06623565 - Multimodal Image-guided Resection of IDH Wildtype Glioblastoma and Grade IV IDH-mutant Astrocytoma (NA, RECRUITING): Rationale: Patients with IDH-wildtype glioblastoma or grade IV IDH-mutant astrocytoma have a very poor prognosis despite standard treatment consisting of surgery, radiotherapy, and chemotherapy. Diffuse infiltration of the brain by the tumor is thought to be one of the main causes of this therapy-resistance. In order to improve the surgical treatment, tumor regions with lower infiltration percentages need to be identified and resected during surgery, a so-called supramarginal resection. Currently, pre-operative T1 contrast enhanced weighted (T1c) MRI is used to identify the tumor for resection. We recently found the combination of apparent diffusion coefficient MRI and O-(2-\[ 18F\]fluoroethyl-)-L-tyrosine positron emission tomography (ADC/FET) to be significantly more accurate than T1c MRI alone in the detection of tumor infiltration. This makes ADC/FET a suitable candidate to guide supramarginal resection. Since FET PET is not as accessible and widely available as MRI, identification of an MRI based alternative could result in a more widespread implementation. Amide proton transfer chemical exchange saturation transfer (APT-CEST) MRI is a novel potential alternative for FET PET, since both measures are related to protein content. Objective: In this project we aim to develop a safe and effective technique for ADC/FET guided resection of IDH-wildtype glioblastoma and grade IV IDH-mutant astrocytoma. The safety concerns neurological deficits and time to start of adjuvant therapy, while the effectiveness is aimed at the extent of resection. Our secondary aim is to evaluate the diagnostic accuracy of APT-CEST MRI and to assess whether APT-CEST MRI can serve as an alternative for FET PET for the detection of tumor infiltration. Study design: prospective observational intervention study Study population: 30 patients with clinical and radiological diagnosis of an untreated high grade glioma (suspected for glioblastoma (IDH wildtype) or grade IV astrocytoma (IDH mutant)), who are eligible for a supramarginal surgical resection and adjuvant treatment according two neurosurgeons in consensus and who are in relatively good condition (Karnofsky Performance Score (KPS) ≥70). Intervention (if applicable): supramarginal ADC/FET-guided resection. To make sure that the standard treatment is always guaranteed, T1c MRI abnormalities will be included in the surgical target. Main study parameters/endpoints: the main study endpoint is the optimization of ADC/FET-guided resection. Volumetric and percentual extent of resection, as measured with MRI and PET imaging, combined with surgery-induced morbidity will be used as outcome parameters. The secondary study parameters will be the histopathology-based diagnostic accuracy of APT-CEST MRI in comparison with FET PET, cognitive performance over time and progression free survival. Nature and extent of the burden and risks associated with participation, benefit and group relatedness: participants will undergo pre- and postoperative MRI scanning. This is also part of regular clinical care, except there are additional MRI sequences including APT CEST in the pre-operative and pre-radiotherapy MRI. There are no risks associated with MRI acquisition after MRI safety screening. Participants will furthermore undergo a pre- and postoperative FET PET. The risks associated with PET scanning are limited, and the radiation burden will remain below 10 mSv (ICRP62 category intermediate risk (level IIb)). During surgery, biopsies are performed from areas that will be resected, so these biopsies will not introduce any extra risk. A potential benefit is the possibility of the removal of more tumor tissue. A potential risk is the additional removal of healthy brain tissue with the risk of neurological damage, which is controlled by pre- and intraoperative techniques such as visualization of white matter tracts and mapping (both asleep and awake) of critical functions such as language and control of strength.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06623565
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05990556 - Research on the Safety and Efficacy of Blocking Dural Blood Supply in Glioblastoma Patients (NA, RECRUITING): Glioblastoma is the most common primary malignancy of the central nervous system with a very poor prognosis. Most of the immunotherapies that have made significant breakthroughs in the treatment of other tumors in recent years are unsatisfactory in the application of glioblastoma, which is mainly inseparable from the highly inhibitory immune microenvironment formed by the latter. Therefore, how to change this "immune desert" and better activate immune effector cells to play an anti-tumor effect is currently a hot spot in glioma immune research. In recent years, there has been continuous research support that the myeloid cells of the central nervous system are partly derived from the bone marrow of the skull, and there is a special channel connection between the skull and the dura mater, through which immune cells can be transported. This suggests that some of the tumor-associated macrophages recruited in the glioblastoma microenvironment may be passed through the dura mater. In previous animal experiments, we blocked the main blood supply to the dura mater by ligating the bilateral external carotid arteries of mice, cutting off the potential supply of dura mater to suppressor myeloid cells in the lesion. The results showed that after ligation of bilateral external carotid arteries, the survival period of tumor-forming mice was significantly prolonged and the prognosis was improved. The proportion of myeloid cells in the tumor microenvironment of mice decreased significantly, and the expression of tumor suppressor molecules such as arginase Arg1 decreased, indicating that the improvement of mouse prognosis was closely related to the proportion and phenotypic changes of myeloid cells after dural blood supply blockade. The meningeal lymphatic system of the human central nervous system has been shown to be an important part of the immune system, while the external carotid artery system, the main source of blood supply to the dura, carries abundant immune cells that ooze out to the dura mater through the endothelial window hole of the dural blood vessel, which is an important source of dural immune cells. In the glioblastoma immune microenvironment, the source of immune cells includes dural branches from the external carotid artery system in addition to branches of the internal carotid artery system. Therefore, for patients diagnosed with glioblastoma, this study involves embolization of the dural branch of the external carotid artery system (bilateral middle meningeal artery) to block the dural blood supply before craniotomy. At the same time, microsurgery under multimodal image navigation was used to remove the tumor. It is expected to be effective in reducing the proportion of myeloid suppressor cells in the tumor microenvironment, slowing the growth rate of residual tumor cells, and prolonging the tumor-free progression and survival of patients.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05990556
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03958240 - Deciphering Mechanisms Underlying Cancer Immunogenicity (NA, RECRUITING): This trial is a translational, open-label, multicentric, prospective cohort study of 1100 patients aiming to describe the PD-1 (programmed death) expression in T cells (T lymphocytes) in different solid tumors. The study will be conducted on a population of patients with local and/or metastatic malignant solid tumor and who are followed within a standard of care procedure or clinical trial. Patients with any of the following tumor types may be enrolled in the trial: * Head and neck cancer, * Ovarian cancer, * Cervical cancer, * Pre-invasive CIN III cervical cancer (Cervical Intra-epithelial Neoplasia III cervical cancer), * Other solid tumor types (including glioblastoma, NSCLC (Non-small cell lung cancer), anal cancer) Each tumor type will be considered as an independent cohort. For each included patient, biological specimen (tumor sample, blood samples and ascites samples if applicable) will be collected. Study participation of each patient will be 5 years.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03958240
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06719440 - Impact of Reducing the Irradiation Volume on Survival, Toxicity, and Quality of Life in Patients With Glioblastoma Treated With Radiochemotherapy: a Prospective Multicenter Randomised Study (NA, RECRUITING): The objective of the BELGICA trial is to evaluate if radiotherapy could be given in a more focused manner in patients with glioblastoma in order to reduce side effects and improve quality of life. The glioblastoma (GBM) is the most common and aggressive tumour originating from the brain, affecting approximately 600 patients per year in Belgium. The treatment consists in surgical resection of the tumour (when feasible), followed by a combination of radiotherapy and chemotherapy. Despite multimodal treatment (surgery, radiotherapy, and chemotherapy), the life expectancy of patients with GBM remains limited, with an average survival of 12-18 months and only 5% of patients surviving more than 5 years. In addition to limited survival, most patients with GBM experience impaired quality of life, both because of the disease and treatments. Radiotherapy is a treatment where radiation is used to kill cancer cells. In GBM, radiotherapy is targeted at the tumour (or tumour bed if the tumour was resected) with a safety margin around it (the "Clinical Target Volume" or CTV) to account for potential microscopic spread of the tumour. The downside of this safety margin is that a substantial amount of brain tissue is irradiated, which can lead to treatment toxicity. Reducing the CTV margin would enable to decrease the volume of brain being irradiated and could thereby allow to reduce the side effects of brain irradiation. The BELGICA trial (Achieving a BEtter outcome through Limiting the GlIoblastoma Clinical tArget volume) is a national multicentre trial which will evaluate if reducing the irradiation volume in glioblastoma is safe and allows for lowering side effects and improving quality of life.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06719440
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06059690 - Biologic Association Between Metabolic MR-PET and Tissue Measures of Glycolysis in Brain Tumors Visualization, Quantitation, and Targeting of Infiltrating Glioblastoma Cells With pH Sensitive Amine Chemical Exchange Saturation Transfer Magnetic Resonance Imaging-KL2TR001882 (PHASE1, PHASE2, RECRUITING): The purpose of this project is to validate a new combined MRI and PET imaging technique as a biomarker or measure of glycolysis in brain tumors. To accomplish this, the investigators propose obtaining image-guided measures of tissue pH and biopsied tissue in tumor areas selected for bulk resection surgery. Investigators will then correlate the imaging measurements with pH, RNA expression, protein expression, and bioenergetics measurements of key glycolytic enzymes.
  Quick read: GBM-related treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06059690
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05954858 - Tissue Autograft to Bypass the Blood Brain Barrier (BBB) in Human Glioblastoma Multiforme (GBM) (NA, RECRUITING): This single center, single arm, open-label, phase 2 study will assess the safety and efficacy of a pedicled temporoparietal fascial (TPF) or pericranial flap into the resection cavity of newly diagnosed glioblastoma multifome (GBM) patients. The objective of the Phase 2 study is to demonstrate that this surgical technique is safe and effective in a human cohort of patients with resected newly diagnosed AA or GBM and may improve progression-free survival (PFS) and overall survival (OS).
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05954858
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05683808 - Venous Thromboembolism Prevention in Outpatients With Glioma (PHASE2, RECRUITING): This is an open label study of apixaban for venous thromboembolism prevention in patients with newly diagnosed grade 4 glioma.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05683808
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT04266977 - Restrictive Use of Dexamethasone in Glioblastoma (NA, RECRUITING): The administration of steroids, most commonly dexamethasone (DEX), has established as standard of care during treatment of glioblastoma (GBM) and is widely used during the entire course of the disease including pre- and postoperative management, chemo- and radiotherapy. The primary purpose is to reduce tumor-associated vasogenic edema and to prevent or treat increased intracranial pressure. However, steroids are also linked to a multitude of adverse side effects that may affect survival of GBM patients such as major immunosuppression. The use of steroids during radiotherapy is associated with reduced overall- and progression-free survival and has been identified as an independent poor prognostic factor. Despite these findings, the suspicion of GBM often triggers the administration of DEX in routine clinical practice, regardless of neurological symptoms, tumor size, or extension of cerebral edema. The purpose of this study is to assess whether selected GBM patients can be treated safely with a restrictive DEX regimen from referral to the neurosurgical center until discharge. The primary objective is to determine the failure rate of a restrictive DEX regimen defined as edema or mass effect leading to any of the following: GCS deterioration ≥ 2 points, NIHSS increase ≥ 3 points, increase of midline Shift ≥ 2mm, or any surgical rescue procedure for increasing mass effect.
  Quick read: GBM-related treatment study for newly diagnosed GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04266977
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07493447 - Pilot Study Evaluating Panitumumab-IRDye800 as an Optical Imaging Agent to Detect Intracranial Lesions During Neurosurgical Procedures (EARLY_PHASE1, NOT_YET_RECRUITING): This pilot clinical study evaluates the safety and imaging performance of panitumumab-IRDye800 (pan800), a fluorescent, EGFR-targeted imaging agent - in patients undergoing neurosurgical resection of intracranial lesions.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07493447
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=46 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07410494 - A Phase 1/2, Open-Label, Biomarker-Driven Study of Allogeneic Donor-Derived CAR-NK Cells With Antigen Selection by Tissue Biopsy and/or Liquid Biopsy Profiling in Participants With Relapsed/Refractory Advanced Solid Tumors (Single-Target vs Dual-Target Strategy) (PHASE1, PHASE2, RECRUITING): This Phase 1/2 study evaluates the safety, feasibility, and preliminary anti-tumor activity of allogeneic donor-derived CAR-NK cells in participants with advanced solid tumors. The CAR target antigen is selected for each participant after tumor profiling using a tissue biopsy and/or liquid biopsy. Participants will receive either a single-target or dual-target CAR-NK product based on the antigen profile.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07410494
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT06929819 - Research on the Safety and Efficacy of Intraoperative Radiation Therapy in Malignant Cerebral Tumor (NA, NOT_YET_RECRUITING): According to the latest national cancer statistics released by the National Cancer Center in February 2022, intracranial tumors account for about 60%-70% of the more than 3.5 million cancer patients, and the morbidity and mortality remain high. Intracranial malignant tumors have become a problem that needs to be solved urgently because of their early recurrence, rapid progression, and short survival, and intracranial malignant tumors include high-grade gliomas, metastases, lymphomas, etc. Glioblastoma (GB) is the most common primary malignancy in the adult central nervous system, accounting for about 57% of all gliomas and 48% of all primary weighted nervous system malignancies. At present, the standard treatment for glioblastoma is mainly surgical treatment, supplemented by postoperative concurrent chemoradiotherapy and adjuvant chemotherapy, but the prognosis of patients is still poor, with a one-year survival rate of 40.6%, a five-year survival rate of only 5.6%, and an average survival time of 12-15 months. For patients diagnosed with intracranial malignancies (including high-grade glioma, metastases, lymphoma, etc.), multimodal image-guided microsurgery combined with postoperative chemoradiotherapy recommended by the guidelines, and intraoperative radiotherapy with tumor bed radiation therapy to achieve targeted and precise tumor treatment, thereby improving the prognosis of patients (including progression-free survival and median overall survival, etc.)
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06929819
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT06492486 - Glioma Adaptive Radiotherapy With Development of an Artificial Intelligence Workflow (PHASE2, NOT_YET_RECRUITING): Gliomas are common primary brain tumors in adults. Gliomas can be classified into different types based on tumor grade, histopathological features, and molecular characteristics. The common types of diffuse gliomas include glioblastoma, astrocytoma, and oligodendroglioma. The standard treatment for diffuse gliomas includes surgery followed by radiation and chemotherapy. As per standard institutional practice, a uniform dose of radiation is delivered to the disease area and MRI is done before and after the treatment. In this study, MRI and PET scan will be done before starting the treatment and standard dose of radiation will be delivered. The interval imaging will be done twice during the course of treatment with MRI and PET, followed by dose modifications. The CT, MRI, and PET will be combined. Based on PET imaging, specific dose will be altered and delivered to specific areas. Dose modification will be done with the help of artificial intelligence. Participant's assessment will be done at regular intervals. Modifications in radiation plans are done based on the changes in disease seen in scans is likely to improve the accuracy of RT treatments. Dose modifications based on imaging to resistant areas will help achieve better tumor control, reduce treatment-related toxicities, precise delivery of the RT and adjusting doses to the organs at risk (OAR) and changes in disease leading to better treatment compliance. Creating an artificial intelligence framework in radiation oncology promises to improve quality of workflow, treatment planning and RT delivery. The aim of the study is to develop an artificial intelligence workflow for treatment of glioma with adaptive radiotherapy. This study will be conducted in Tata Memorial Centre on a population of 60 patients for a duration of 2 years. The total study duration is 4 years.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06492486
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=90 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07384884 - Surgery and Laser Interstitial Thermal Therapy for Bilateral Glioblastomas (NA, NOT_YET_RECRUITING): Butterfly glioblastomas (bGBM), defined as tumours crossing the midline to involve hemispheres bilaterally, have a dismal prognosis with a median survival of 3.3-6 months and only 9% of patients with bGBM survive 2-years. These figures put bGBM in the worst end of the spectrum of GBM prognosis, significantly inferior to the survival figures quoted in the literature with standard of care - 14.6 months - particularly when 5-aminolevulinic acid is used as surgical adjuvant - 17.47 months. Despite the poor outcome of this disease, there is preliminary evidence suggesting that active oncology treatment can impact the survival of patients with this condition.With particular regards to surgical resection versus biopsy, there is a suggestion that resection improves overall survival at 6 months with no clear difference at 12 and 18 months of follow up. Laser-induced thermal therapy (LITT) is a minimally invasive laser ablation technique used in a range of brain tumours, including glioblastomas, with similar overall survival to the ones reported for open surgery in patients with lesions not amenable to open resection. The minimally invasive nature of this technique, significantly reducing the collateral damage to the surrounding brain structures, suggests Its potential in the treatment of this bGBM \[14\] with significant implications as a deficit-sparing technique, particularly if associated with preoperative and intraoperative monitoring and mapping techniques. The SLITT-GBM study will combine unilateral open surgery for maximal tumour resection with contralateral LITT to the smaller component/residual.
  Quick read: GBM-related treatment study for GBM or glioma patients; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07384884
  Review priority: 134
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none

#### Related Papers
- PMID:34898238 - Therapy for Diffuse Astrocytic and Oligodendroglial Tumors in Adults: ASCO-SNO Guideline.
  Quick read: Guideline-style reference for GBM-specific, newly_diagnosed, focused on radiation, temozolomide in Journal of clinical oncology : official journal of the American Society of Clinical Oncology (2022). Linked to NCT06504381.
  Source: https://pubmed.ncbi.nlm.nih.gov/34898238/
- PMID:37059335 - ESTRO-EANO guideline on target delineation and radiotherapy details for glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2023).
  Source: https://pubmed.ncbi.nlm.nih.gov/37059335/
- PMID:35426875 - Congress of Neurological Surgeons Systematic Review and Evidence-Based Guidelines on the Management of Progressive Glioblastoma in Adults: Update of the 2014 Guidelines.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Neurosurgery (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35426875/
- PMID:35246769 - Congress of neurological surgeons systematic review and evidence-based guidelines update on the role of cytoreductive surgery in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35246769/
- PMID:35195819 - Congress of Neurological Surgeons systematic review and evidence-based guidelines update on the role of cytotoxic chemotherapy and other cytotoxic therapies in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35195819/
- PMID:29086250 - SEOM clinical guidelines for diagnosis and treatment of glioblastoma (2017).
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Clinical & translational oncology : official publication of the Federation of Spanish Oncology Societies and of the National Cancer Institute of Mexico (2018).
  Source: https://pubmed.ncbi.nlm.nih.gov/29086250/
- PMID:27907278 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of oncology practice (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27907278/
- PMID:27893327 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of clinical oncology : official journal of the American Society of Clinical Oncology (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27893327/
- PMID:26777122 - ESTRO-ACROP guideline "target delineation of glioblastomas".
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2016).
  Source: https://pubmed.ncbi.nlm.nih.gov/26777122/
- PMID:25079102 - EANO guideline for the diagnosis and treatment of anaplastic gliomas and glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in The Lancet. Oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/25079102/
- PMID:24756348 - The role of cytoreductive surgery in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24756348/
- PMID:24740195 - The role of targeted therapies in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24740195/

#### Related Datasets
- gdc_tcga_gbm - NCI GDC TCGA-GBM
  Quick read: Core GBM tumor-genomics program with somatic variants, copy-number, expression, methylation, and linked clinical metadata; open and controlled-access layers.
  Source: https://gdc.cancer.gov/about-data/publications/gbm_2013
- gdc_tcga_lgg_gbm - NCI GDC TCGA Pan-Glioma Cohorts
  Quick read: Combined glioma genomics across lower-grade glioma and GBM for broader IDH, MGMT, and progression-context comparisons.
  Source: https://portal.gdc.cancer.gov/
- ivy_gap - Ivy Glioblastoma Atlas Project
  Quick read: Region-resolved glioblastoma atlas with anatomic and molecular context across tumor subregions.
  Source: https://glioblastoma.alleninstitute.org/
- cbioportal_gbm - cBioPortal GBM Studies
  Quick read: Searchable GBM and glioma genomics knowledgebase spanning TCGA and many published studies with mutation, CNA, and outcome views.
  Source: https://www.cbioportal.org/
- cptac_gbm - CPTAC Brain / Glioblastoma Proteogenomic Resources
  Quick read: Proteomic and proteogenomic tumor data relevant to GBM biology and pathway activation beyond DNA-only signals.
  Source: https://proteomics.cancer.gov/programs/cptac

#### Missing Evidence
- HLA typing available: HLA typing lab result.
  Missing artifact types: hla_typing_result

### Recurrent Molecular Candidate
- Case ID: `case_recurrent_molecular_candidate`
- Patient: `synthetic-002`
- Evidence package: 8 ready / 0 missing
- Standard-care paths to discuss: 2
- Trial candidates for review: 165
- Trials needing more evidence: 0
- Bitmask: `0`

#### Recommended Care Pathways
- Recurrent Disease Salvage Therapy Review: Recurrent GBM prompts review of re-resection, re-irradiation, systemic options, and clinical-trial fit.
  Reasons: Patient state matched: recurrent_disease, Patient state matched: adult_patient
- Molecular Tumor Board Review: Escalate to a molecular review when sequencing data exists and the patient is being screened for advanced options.
  Reasons: Patient state matched: advanced_option_search, Patient state matched: performance_status_good

#### Candidate Trials
- NCT07501559 - A Phase Ib/II Clinical Trial to Evaluate the Safety and Efficacy of JL15003 Injection in Patients With Recurrent Glioblastoma (rGBM) (PHASE1, PHASE2, RECRUITING): The goal of this clinical trial is to evaluate the safety and efficacy of JL15003 Injection in subjects with recurrent glioblastoma (rGMB).
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07501559
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT07480941 - A Phase 1, First-in-Human, Biomarker-Guided, Dose-Escalation and Expansion Study of Locoregional Dual-Targeting CAR-NK Cells Directed Against IL13Rα2, EGFR/EGFRvIII, and/or B7-H3 (CD276) in Adults With Recurrent or Progressive Glioblastoma or High-Grade Glioma (PHASE1, RECRUITING): This is a draft, ClinicalTrials.gov-style example record for a first-in-human Phase 1 study evaluating locoregional administration of dual-targeting chimeric antigen receptor natural killer (CAR-NK) cells in adults with recurrent or progressive glioblastoma (GBM) or other high-grade glioma (HGG). Participants will undergo tumor antigen profiling for IL13Rα2, EGFR/EGFRvIII, and B7-H3 (CD276). Based on this assessment, each participant will receive the most suitable dual-target CAR construct to reduce antigen-escape risk.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07480941
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT07464925 - An Open-Label Phase 1 Safety and Dose Finding Study of Orally Administered GLIX1 in Adults With Recurrent or Progressive High-grade Glioma (PHASE1, NOT_YET_RECRUITING): This is an open-label, multicenter dose-escalation study to be followed by a dose expansion to define the optimal dose of GLIX1 as monotherapy by reviewing safety and tolerability, disease characteristics and pharmacokinetic profiles and preliminary clinical activity in participants with a high grade diffuse glioma that progressed during or recurred after prior standard of care therapies or investigational therapies as clinically indicated. Patients will be treated daily with GLIX1 capsules until disease progression or unacceptable safety.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07464925
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT07431216 - A Phase 1b/2a Study to Evaluate the Safety, Pharmacokinetics, and Objective Response of STAR-001 (LP-184) in Combination With Spironolactone in Supratentorial Glioblastoma at First Progression (PHASE1, PHASE2, NOT_YET_RECRUITING): Approximately 58-68 total subjects will be enrolled. In the first stage, 10 response evaluable subjects (either IDHwt or IDHm Grade 4 astrocytoma) will be enrolled. If 1 or more of the first 10 response evaluable subjects achieve an objective response, 19 further subjects may be accrued in the second stage (for a total of 29 response evaluable subjects). Subjects enrolling in the study will provide fresh (in subjects who undergo a planned tumor resection) or archival (all subjects) tumor tissue sample (at least 10 unstained slides of 5-micron thickness) at screening for retrospective exploratory biomarker analysis and determination of intertumoral PTGR1 levels. STAR-001 (LP-184) will be administered via IV infusion over 30 minutes on Day 1 and Day 8 of each 21-day cycle. The STAR-001 dose for this study is 0.39 mg/kg. Spironolactone will be administered orally on Day (-2), Day (-1), and between 4-8 hours before the STAR-001 infusion on D1 (Day of STAR-001 IV infusion) and on Day 6, Day 7, and between 4-8 hours before the STAR-001 infusion on Day 8 . The spironolactone dose for this study is 100 mg given 3 times prior to STAR-001 infusion.
  Quick read: GBM-specific treatment study for first-recurrence GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07431216
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT07392957 - A Phase IB/II Open-label Study of the Safety and Preliminary Efficacy of CTX-009 Administered Either as a Monotherapy or in Combination With CTX-471 in Patients With Recurrent Glioblastoma (PHASE1, PHASE2, NOT_YET_RECRUITING): This is a phase IB/II, open-label study evaluating CTX-009 as monotherapy and in combination with CTX-471. The study evaluates the safety and efficacy of the monotherapy and the combination in patients with recurrent glioblastoma. The study tests the hypothesis that treatment with CTX-009 alone or in combination with CTX-471 will lead to enhanced tumor control and prolongation of overall survival of patients with recurrent glioblastoma. CTX-009 expands on existing anti-angiogenic therapies by ablating key compensatory and resistance mechanisms to bevacizumab, CTX-471 restores local immune reactivity through activation of costimulatory immune mediators. Combination of these two agents may further impair tumor proliferation through synergistic effects on the tumor microenvironment
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07392957
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs True (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT07349693 - A Randomized Trial to Assess the Efficacy and Safety of Cerebraca Wafer Plus Temozolomide Versus Temozolomide Alone in Recurrent Glioblastoma (PHASE2, PHASE3, NOT_YET_RECRUITING): This study is designed as a multi-center, randomized, open-label trial to evaluate the efficacy of Cerebraca Wafer in patients with recurrent glioblastoma. Cerebraca Wafer is intended for use in recurrent glioblastoma as an adjunct to surgery (followed by standard-of-care temozolomide), demonstrating potential to improve outcomes in this serious and life-threatening condition
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07349693
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), recurrence_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07318818 - A Phase I/II Clinical Study to Evaluate the Safety and Efficacy of P134 Cells in the Treatment of Recurrent Glioblastoma (PHASE1, PHASE2, RECRUITING): This is an open-label, single-arm, dose-escalation and expansion Phase 1/2 clinical trial designed to evaluate the safety, tolerability and efficacy of P134 cells in patients with recurrent glioblastoma, to explore the maximum tolerated dose (MTD)and recommended Phase 2 dose (RP2D), and to characterize the cytokinetic profile of CAR-T cells in the cerebrospinal fluid of patients. Eligible participants are adults diagnosed with recurrent or progressive glioblastoma who are confirmed as grade 4 glioblastoma (IDH wild-type) by histopathology or molecular pathology. P134 cells are CD44/CD133 dual-targeting CAR-T cells developed by the research team led by Academician Jiang Tao and Professor Zhang Wei from the Beijing Neurosurgical Institute and the Department of Neurosurgery, Beijing Tiantan Hospital. This study is spearheaded by Professor Zhang Wei of the Department of Neurosurgery, Beijing Tiantan Hospital, Capital Medical University, China, with scientific oversight and guidance provided by Academician Jiang Tao of the Chinese Academy of Engineering.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07318818
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07297212 - A Phase II, Multi-site, Open-label Trial Evaluating the Safety and Efficacy of Pumitamig and Bevacizumab as Monotherapy and Pumitamig in Combination With Temozolomide in Patients With Recurrent Glioblastoma (PHASE2, RECRUITING): This multi-site Phase II study will enroll adults with histologically confirmed diagnosis of World Health Organization (WHO) Grade IV glioblastoma (GBM), isocitrate dehydrogenase (IDH)-wildtype consistent with WHO central nervous system (CNS) 2021 criteria who have received prior first-line treatment including with at least radiotherapy and temozolomide, with a Karnofsky performance status (KPS) ≥60, adequate organ function, and at least one measurable lesion according to the response assessment in neuro-oncology (RANO) 2.0 criteria.
  Quick read: GBM-specific treatment study for first-recurrence GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07297212
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT07274787 - An Open Label, Prospective, Pilot Study To Evaluate The Safety And Effectiveness Of The NaviFUS System In Conjunction With A Standard Treatment Regimen Of Bevacizumab (BEV) In Patients With Recurrent Glioblastoma (NA, NOT_YET_RECRUITING): This study will evaluate the safety and early effectiveness of the NaviFUS system with concomitant microbubble administration in conjunction with BEV in recurrent GBM patients.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07274787
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07244666 - Safety and Preliminary Efficacy of a Metabolically Armed Chimeric Antigen Receptor T Cell Therapy Targeting EGFRvIII for Recurrent Glioblastoma (EARLY_PHASE1, NOT_YET_RECRUITING): A Study of Metabolically Armed EGFRvII CAR-T Cells Therapy for Patients With Recurrent Glioblastoma
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07244666
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT07209241 - Phase Ib, Open-Label Study of CART-EGFR-IL13Rα2 Cells Administered Following Lymphodepleting Chemotherapy or Prior to Surgical Resection in Patients With EGFR-Amplified Recurrent Glioblastoma (PHASE1, RECRUITING): This is an open-label, phase 1b study to evaluate different approaches for CART-EGFR-IL13Ra2 dosing and further characterize the safety, feasibility, preliminary efficacy, and pharmacokinetics of CART-EGFR-IL13Ra2 cells in patients with EGFR-amplified glioblastoma that has recurred following prior radiotherapy.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07209241
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07193628 - An Open-label, First-in-human, Dose-escalation and Dose-expansion, Phase I Study of Fully Human B7H3/IL13Ra2 Bispecific Armored Chimeric Antigen Receptor T-Cell Therapy for Treatment of Recurrent or Refractory Glioblastoma (PHASE1, RECRUITING): This study is an investigator-initiated, open-label Phase I clinical trial designed to evaluate the safety and efficacy of EPC-003 fully human anti-B7H3/IL13Ra2 armored Chimeric Antigen Receptor T-Cell Therapy (CAR-T) cell injection in patients with recurrent or refractory glioblastoma. Approximately 14 patients with relapsed or refractory glioblastoma are planned to be enrolled in this trial. During the screening period (Days -28 to -15), subjects will undergo relevant examinations or observations to confirm the disease status, treatment history, and other related information. Subjects who meet the screening criteria will be enrolled in the clinical trial to receive EPC-003 treatment. Specifically, they will receive intraventricular injection of EPC-003 via Ommaya reservoir on Day 0 (D0), Day 7 (D7), Day 14 (D14), Day 21 (D21), Day 28 (D28), and Day 35 (D35), once a week, totaling 6 administrations. All CAR-T cell infusions will be delivered via intraventricular injection. This trial comprises two phases: the first phase is the dose-escalation phase, and the second phase is the dose-expansion phase.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07193628
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07180927 - 4sCAR-DLL3 CAR-T Therapy Targeting Brain Tumors (PHASE1, PHASE2, RECRUITING): The purpose of this study is to assess the feasibility, safety and efficacy of Delta-like ligand 3 (DLL3)-specific CAR-T cell therapy in patients with DLL3 positive brain tumors including glioblastomas and diffused intrinsic pontine or midline gliomas (DIPG or DMG). Another goal of the study is to learn more about the function of the anti-DLL3 CAR-T cells and their persistency in patients.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07180927
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT07145112 - A Phase 1 Safety and Feasibility Study of Laser Interstitial Thermal Therapy (LITT) Followed by Lomustine (CCNU) for Recurrent Glioblastoma in Adults (PHASE1, RECRUITING): This is a phase 1 study evaluating the safety and feasibility of laser interstitial thermal therapy (LITT) followed by lomustine (CCNU) for recurrent glioblastoma in adults. The primary aim is to evaluate the safety of the combination of LITT plus lomustine based on the assessment of treatment-related adverse events and the feasibility of completing LITT + lomustine in the proposed timeframe. The secondary aim is to assess overall survival for up to 2 years after the first dose of lomustine.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07145112
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 50 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07145047 - Clinical Study on the Application of Oncolytic Virus in Recurrent Glioblastoma (PHASE1, PHASE2, RECRUITING): This clinical trial aims to evaluate whether an oncolytic viral agent can treat recurrent glioblastoma. It will also assess the safety and tolerability of the oncolytic viral agent. The primary question it seeks to answer is: What medical problems do participants experience when injected with the oncolytic viral agent? Researchers will administer the oncolytic viral agent via intratumoral injection to determine its efficacy in treating recurrent glioblastoma. Participant Procedures: Receive the initial injection, followed by additional injections every 2-4 weeks for a total of 6 injections. Undergo physical examinations and tests every 2 to 4 weeks. Record their symptoms, hematological test results, and imaging findings.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07145047
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07093814 - A Phase I/II Study to Evaluate the Safety, Tolerability, and Preliminary Efficacy of VRT106 for Injection in Patients With Recurrent/Progressive Glioblastoma (PHASE1, PHASE2, RECRUITING): This study is an open-label, single-arm Phase I/II clinical trial with the primary objective of evaluating the safety, tolerability, and efficacy of VRT106 in patients with recurrent/progressive glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07093814
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07076472 - MC240704 Pilot Dose Escalation and Expansion Study of Sonodynamic Therapy With Aminolevulinic Acid Hydrochloride (5-ALA HCl Or SONALA-001) in Combination With Exablate 4000 Type 2.0 MR-Guided Focused Ultrasound (MRgFUS) in Patients With Progressive or Recurrent Glioblastoma Multiforme (RGBM) (EARLY_PHASE1, RECRUITING): This early phase I trial tests the safety, best dose, and effectiveness of SONALA-001 or 5-ALA HCL in combination with magnetic resonance imaging-guided focused ultrasound (MRgFUS), also called sonodynamic therapy, in treating patients with glioblastoma that is growing, spreading, or getting worse (progressive) or that has come back after a period of improvement (recurrent). Sonodynamic therapy is a non-invasive combination therapy that uses low-intensity ultrasound, such as MRgFUS, to activate a drug, such as SONALA-001 or 5-ALA HCL, to kill tumor cells. SONALA-001 or 5-ALA HCL binds to the tumor and may help the sonodynamic therapy target the tumor. MRgFUS is an image-guided, non-invasive technique that uses high energy ultrasound from the Exablate 4000 Type 2.0 device to kill tumors without damaging surrounding healthy tissue. Giving sonodynamic therapy using SONALA-001 or 5-ALA HCL with MRgFUS may be safe, tolerable, and/or effective in treating patients with progressive or recurrent glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07076472
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06910306 - A Study to Assess the Feasibility and Safety of Intratumoral Diffusing Alpha Emitters for the Treatment of Recurrent Glioblastoma (NA, RECRUITING): A unique approach for cancer treatment employing intratumoral diffusing alpha radiation emitter device for the treatment of recurrent Glioblastoma
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06910306
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06894225 - Proof-of-Concept Study of ACT001 in Adult Patients With Recurrent Glioblastoma Harbouring STAT3-High Signature (PHASE2, NOT_YET_RECRUITING): This trial will study the effectiveness of ACT001 in adult patients whose Glioblastoma have recurred with a STAT3-high signature after standard-of-care treatment with at least radiation therapy.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06894225
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06883747 - A Phase 0/1 Study of BMS-986504, a MTA Cooperative PRMT5 Inhibitor in Recurrent Glioblastoma Participants With MTAP Deleted Tumors Scheduled for Resection to Evaluate Central Nervous System (CNS) Penetration With PK-Triggered Expansion Cohort (EARLY_PHASE1, RECRUITING): This is an open-label, multi-center, Phase 0/1 dose-escalation trial designed to enroll up to 9 total recurrent glioblastoma (rGBM) participants with confirmed MTAP loss/deletion in their archival or pretreatment biopsy tissue, who are scheduled for surgical resection. MTAP loss/deletion will be determined by next-generation sequencing (NGS). The trial will include a dose escalation design to evaluate the pharmacokinetics (PK) and safety and tolerability of BMS-986504 (MRTX1719). The trial will be composed of a Phase 0 component and an Expansion Phase 1 component. Participants with tumors demonstrating a positive PK response in the Phase 0 component of the study will be eligible to enroll into the the Phase 1 component that will include 21-day cycles of therapeutic dosing of BMS-986504.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06883747
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06815432 - GPC-3 Chimeric Antigen Receptor T Cells FOR Recurrent GPC-3 Positive Glioblastoma (PHASE1, RECRUITING): The body has different ways of fighting infection and disease. No single way seems perfect for fighting cancers. This research study combines two different ways of fighting cancer: antibodies and T cells. Antibodies are types of proteins that protect the body from infectious diseases and possibly cancer. T-cells, also called T lymphocytes, are special infection-fighting blood cells that can kill other cells, including cells infected with viruses and tumor cells. Both antibodies and T cells have been used to treat participants with cancers. They have shown promise, but have not been strong enough to cure most participants. The study team has found from previous research that we can put a new gene (a tiny part of what makes-up DNA and carries the participants traits) into T cells that will make them recognize cancer cells and kill them. In the lab, the study team has made several genes called a chimeric antigen receptor (CAR), from an antibody called GC33. The antibody GC33 recognizes a protein found on the participants brain tumor. This CAR is called GPC3-CAR. To make this CAR more effective, the study has also added a gene that includes IL15. IL15 is a protein that helps CAR T cells grow better and stay in the blood longer so that they may kill tumors better. The mixture of GPC3-CAR and IL15 killed tumor cells better in the laboratory when compared with CAR T cells that did not have IL15. This study will test T cells with the IL15 GPC3-CAR (GO-CART T cells) in participants with GPC3-positive brain tumors. T cells made to carry a gene called iCasp9 can be killed when they encounter a specific drug called AP1903. The study team will insert the iCasp9 and IL15 together into the T cells using a virus that has been made for this study. The drug (AP1903) is an experimental drug that has been tested in humans with no bad side-effects. The study team will use this drug to kill the T cells if necessary due to side effects. This study will test T cells genetically engineered with a GPC3-CAR and IL15 (GO-CART T cells) in participants with GPC3-positive brain tumors. The GO-CART T cells are an investigational product not approved by the Food and Drug Administration.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06815432
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06773481 - A Phase I Clinical Study to Evaluate the Safety and Preliminary Efficacy of BC008-1A Injection in Subjects With Recurrent CNS WHO Grade 4 Glioma. (PHASE1, RECRUITING): The purpose of this Phase I clinical study is to evaluate the safety, preliminary efficacy and pharmacokinetic characteristics of BC008-1A injection in subjects with recurrent CNS WHO grade 4 glioma. This is a randomized and open-label study, with two dose groups set up, and 10 to 20 subjects will be enrolled in each group.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06773481
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06757153 - Clinical Study on the Safety and Efficacy of NRG-103 Injection in the Treatment of Recurrent Glioblastoma Patients (EARLY_PHASE1, RECRUITING): The goal of this clinical trial is to learn if NRG103 works to treat recurrent GBM in adults. It will also learn about the safety of NRG103. The main questions it aims to answer are: Does NRG103 prolong overall survival or disease-free survival in patients with GBM? What medical problems do participants have when receiving NRG103 treatment? Researchers will give patients with NRG103 to see if NRG103 works to treat recurrent GBM. Participants will: Receive NRG103 twice in 14 days Visit the clinic once every 2 weeks for checkups and tests Keep a diary of their symptoms
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06757153
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06672575 - A Phase I/II Study of IVONESCIMAB in Recurrent Glioblastoma (PHASE1, PHASE2, RECRUITING): The goal of Phase 1 of this clinical research study is to find the highest tolerable dose and the recommended Phase 2 dose of ivonescimab that can be given to patients who have recurrent glioblastoma. The goal of Phase 2 of this clinical research study is to learn if the recommended Phase 2 dose of ivonescimab found in Phase 1 can help to control the disease.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06672575
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), recurrence_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_chemoradiation, Matched inclusion factor: prior_radiation, Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06630260 - A Phase 1/2 Trial of the Doublet Combination of Avutometinib and Defactinib and as a Triplet in Combination With Temozolomide in Patients With High Grade Malignant Brain Tumours Within the 5G Platform (PHASE1, PHASE2, RECRUITING): The purpose of this clinical trial is to evaluate the safety and tolerability of avutometinib and defactinib and to determine the preliminary antitumour activity of avutometinib and defactinib administered at the recommended Phase 2 dose (RP2D). In the Phase 1b of this study parallel biomarker defined arms will be opened, initially in the relapsed GMB setting, enrolling 12 patients onto each arm. These patients will be treated with avutometinib and defactinib double therapy. Avutometinib will be administered orally at 3.2mg twice a week (e.g., on Monday / Thursday or Tuesday / Friday) with or without a meal. The total weekly dose of avutometinib is 6.4mg. Defactinib will be administered orally, at 200mg, twice a day within 30 min after a meal. The total daily dose of defactinib is 400mg. Once a treatment in any biomarker arm has met the "GO" decision (≥3 successes/12 patients) for relapsed GBM in Phase 1b, that arm can progress to Phase 2. The primary objective of Phase 2 is to determine the antitumour activity of investigational agents administered at the RP2D in patients with molecularly defined malignant brain tumours.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06630260
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06616727 - A Phase I Study to Evaluate the Safety, Tolerability and Pharmacokinetics of SNC109 in Patients With Recurrent Glioblastoma (PHASE1, ENROLLING_BY_INVITATION): A phase I study to evaluate the safety, tolerance and pharmacokinetics of SNC109 in patients with rGBM
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; limited-enrollment.
  Source: https://clinicaltrials.gov/study/NCT06616727
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 50 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06613841 - Pilot Study to Evaluate Multitracer [18F]Fluciclovine and 18F-FDG PET, and Advanced MRI Methods at 7Tesla Metabolic Profiling of Glioblastoma (EARLY_PHASE1, RECRUITING): * To perform metabolic phenotyping of treatment naïve and recurrent GBM by multitracer \[18F\]Fluciclovine and 18F-FDG PET. * To compare uptake measures of 18F-Fluciclovine and 18F-FDG and MRI quantification of glutamate and lactate levels to tumor tissue laboratory assays (RNA seq and proteomics) of glutamine/glutamate, glucose, and lactate metabolism. * To perform metabolic phenotyping of treatment naïve and recurrent GBM by advanced MRI methods at 7 Tesla
  Quick read: GBM-specific treatment study for recurrent GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06613841
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06598787 - A Phase II Clinical Study to Evaluate the Efficacy and Safety of BL-B01D1 for Injection in Patients With Recurrent Glioblastoma (PHASE2, RECRUITING): This is an open-label, multicenter, phase II study to evaluate the safety, efficacy, and pharmacokinetic characteristics of BL-B01D1 for Injection in patients with recurrent glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06598787
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06585527 - A Clinical Study of the Safety and Efficacy of Third-generation Oncolytic TS-2021 in the Treatment of Recurrent Malignant Gliomas (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and efficacy of oncolytic virus TS-2021 in the treatment of recurrent malignant glioma.About 30 eligible participants with recurrent malignant glioma will : * Be intratumoral injected the TS-2021 oncolytic virus to study its safety and efficacy. * Be followed for 1 year after the injection to complete imaging studies, neurological function tests, and report adverse events. Using the data obtained during the follow-up period, researchers will conduct statistical analyses and evaluate the safety and efficacy of oncolytic virus TS-2021.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06585527
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06558214 - OPTIMUS PRIME: Safety and Feasibility of OPTune GIO® Integrated With MRI-gUided Laser Ablation Surgery and Pembrolizumab for Recurrent GlIoblastoMa, A randomizEd Trial (PHASE2, RECRUITING): In this study we are evaluating the safety and feasibility of the triple combination (TTFields, MLA, pembrolizumab) in adult patients diagnosed with recurrent or progressive glioblastoma (GBM) WHO Grade IV, IDH wild type or recurrent or progressive astrocytoma WHO grade IV.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06558214
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06455605 - Clinical Trial of D2C7-IT + 2141-V11 Combination Immunotherapy Administered Via Convection Enhanced Delivery in Non-enhancing Tumor Post-resection of Recurrent Glioblastoma, Followed by Cervical Perilymphatic Subcutaneous Injections of 2141-V11 (PHASE1, RECRUITING): The purpose of this study is to assess the safety and efficacy of the combination of D2C7-IT+2141-V11 administered in the non-enhancing tumor of patients with resected recurrent glioblastoma (rGBM) via convection enhanced delivery (CED), followed by subcutaneous cervical perilymphatic injections (CPLIs) of 2141-V11 2 and 4 weeks post infusion, then every 3 weeks for a year, and every 4-6 weeks thereafter if patients benefit from therapy.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06455605
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06327451 - Evaluate the Efficacy and Safety of Atorvastatin Combined With Temozolomide in the Treatment of Glioblastoma (PHASE2, RECRUITING): Glioblastoma (GBM) is the primary intracranial malignant tumor with the highest morbidity and mortality, and the 5-year survival rate is less than 10%. The number of primary diagnostic patients and deaths of GBM in China ranks first in the world every year, which seriously threatens people's life and health. At present, the clinical treatment strategy of maximum surgical resection combined with concurrent chemo- and radio-therapy and TTF treatment is still not satisfactory, and the median survival time of GBM patients is only 14.4 months. Statins inhibit cholesterol production with few side effects and are widely used for cholesterol control in patients with hyperlipidemia. In recent years, statins have shown good anti-tumor effect. Our previous study found that statins can block the malignant progression of glioma mediated by EGFR pathway. Therefore, the investigators report a clinical study protocol designed to evaluate the clinical efficacy of a comprehensive treatment strategy of atorvastatin (ATO) combined with temozolomide (TMZ) in primary and recurrent glioblastomas with high EGFR expression. The investigators designed a multicenter, single-arm, double-blind, phase II clinical trial to evaluate the efficacy and safety of oral ATO combined with TMZ in EGFR-high expressing GBM. After informed consent was signed by the patient or authorized family members, the patients were treated with the current STUPP regimen and ATO (20mg, qn) orally. The patients were regularly followed up for 52 weeks after treatment. The primary endpoint was progression-free survival (PFS), which was defined as the time from the start of GBM surgery to tumor progression (recurrence) or death. The secondary end point was the rate of tumor control, which was defined as the proportion of patients with a complete response, a partial response, or a stable disease that had shrunk or remained stable for a given period of time. Safety will be assessed during the study by monitoring of regular MRI scans, laboratory tests (liver function, lipid profile, blood routine), electrocardiography, vital signs (blood pressure, pulse, temperature), and weight. The results of this clinical trial will provide key information on whether the oral combination of atorvastatin and temozolomide prolongs PFS in EGFR-high GBM patients with efficacy and safety.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06327451
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06325683 - Randomized Phase II Trial of Anti-Lag-3 and Anti-PD-1 Blockade vs. SOC in Patients With Recurrent Glioblastoma (PHASE2, RECRUITING): This phase II trial compares the safety, side effects and effectiveness of anti-lag-3 (relatlimab) and anti-PD-1 blockade (nivolumab) to standard of care lomustine for the treatment of patients with glioblastoma that has come back after a period of improvement (recurrent). Relatlimab is a monoclonal antibody that may interfere with the ability of tumor cells to grow and spread. A monoclonal antibody is a type of protein that can bind to certain targets in the body, such as molecules that cause the body to make an immune response (antigens). Immunotherapy with monoclonal antibodies, such as nivolumab, may help the body's immune system attack the tumor, and may interfere with the ability of tumor cells to grow and spread. Lomustine is a chemotherapy drug and in a class of medications called alkylating agents. It damages the cell's deoxyribonucleic acid and may kill tumor cells. Giving relatlimab and nivolumab may be safe, tolerable, and/or effective compared to standard of care lomustine in treating patients with recurrent glioblastoma.
  Quick read: GBM-specific treatment study for first-recurrence GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06325683
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT06271421 - Application of Nanoparticles for Cyclic Hyperthermia In Adjuvant Therapy of gLioblastoma Multiforme (ANCHIALE) (NA, RECRUITING): Glioblastoma multiforme (GBM), the most common and malignant primary brain tumor in adults is classified as a World Health Organisation (WHO) grade 4. Surgical removal of the tumor is the primary method of treatment. Unfortunately, because GBM is a disease of the entire brain, total resection is not possible. Therefore, the use of radiotherapy and/or chemotherapy is considered as Stupp protocol. Patients with recurrent GBM will be included in the ANCHIALE study. The goal of the trial is to evaluate the efficacy and tolerance of using the NanoTherm therapy system in recurrent GBM. The main questions it aims to answer are: 1. how NanoTherm therapy influences overall survival, and progression free survival; 2. what is the tolerance of NanoTherm therapy in terms of side effects (allergies, intracranial bleeding, infections, brain edema, increased intracranial pressure) and quality of life. Participants will undergo: * initial visit, considering the inclusion/exclusion criteria, neurological examination, and surveys regarding daily functioning and quality of life; * standard neurosurgical operation aimed, if possible, complete removal of the recurrent GBM and administration of NanoTherm ASI - a sterile suspension of iron oxide nanoparticles. A catheter will be implanted allowing for measurement of temperature during the first activation in the magnetic field; * between the 6th and 10th day after tumor resection, a standard computerized tomography (CT) scan of the head will be performed for routine postoperative evaluation; * after the first activation (10th day), the catheter will be removed; * subsequently, for 6 times, the patient will be subjected to the variable magnetic field of the NanoActivator® to induce hyperthermia - activations will be conducted on the 10th, 14th, 17th, 21st, 24th, and 28th day; * for up to 2 years post-procedure, a CT scan with an evaluation of treatment efficacy will be performed; * during follow-up visits for up to 2 years after the surgical procedure, a neurological examination, assessment of adverse symptoms, number of hospitalizations, number of medical visits, clinimetric assessment regarding quality of life, neurological deficit and degree of disability will be conducted. Researchers will compare NanoTherm group with patients undergoing Stupp protocol treatment for the abovementioned effects.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06271421
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06220552 - Low-dose Radiotherapy Combined With Sintilimab and Temozolomide in Recurrent Glioblastoma: A Single-arm, Prospective Phase II Clinical Study (PHASE2, RECRUITING): This is an open-label, single-arm, phase II clinical trial to explore the efficacy and safety of low-dose radiotherapy combined with programmed death 1 (PD-1) inhibitor (sintilimab) and temozolomide in recurrent glioblastoma. The eligible patients are scheduled to administered sintilimab 200mg D1 Q3W temozolomide 50mg/m2 QD and radiotherapy 1Gy/1F D1/D2/D8/D15 Q3W for 4-6 cycles, then sintilimab for maintenance. The overall primary study hypothesis is that the combination regimen of low-dose radiotherapy, sintilimab and temozolomide is safe and feasible in the treatment of recurrent glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06220552
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06218524 - Clinical Study for Evaluating the Effectiveness of Haloperidol and Temozolomide Synergism on Adult Recurrence Glioblastoma (PHASE2, NOT_YET_RECRUITING): The study of investigators indicated that TMZ can up-regulate dopamine D2 receptor (DRD2) expression, and mediates Ferroptosis inhibition and chemoresistance of GBM. The clinical data also proved that the DRD2 expression in recurrent GBM is significantly higher than that in primary GBM. Moreover, the DRD2 antagonist haloperidol can attenuate the above function of DRD2, and increase the sensitivity of GBM to the TMZ by inducing fatal autophagy and ferroptosis. In xenograft mice, the combined usage of haloperidol and Temozolomide (TMZ) can significantly inhibit tumor growth and increase overall survival. The investigators' findings have been published in Clinical cancer research. Haloperidol known as a butylbenzene antipsychotic drug, has been widely used in several kinds of mental illnesses, such as depression, schizophrenia, and Bipolar disorder. And the safe dosage of the haloperidol is clear so far. So in this study, the investigators will recruit the patients who suffered from recurrent GBM, and evaluate the effectiveness of single TMZ chemotherapy or combined with haloperidol.
  Quick read: GBM-specific treatment study for recurrent GBM; drug-treatment; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06218524
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06183983 - Hitting the Mark: Introducing State-of-the-art MRI for Precision Radiotherapy of Glioblastoma (NA, RECRUITING): The goal of this prospective cohort study is to assess the potential of advanced MRI for improved radiotherapy target delineation in patients diagnosed with glioblastoma. The main questions it aims to answer are: * How does the coverage of the recurrence volume by a radiotherapy plan based on advanced MRI compare to the coverage by the clinical radiotherapy plan? * How does the distribution of the dose to organs at risk by a radiotherapy plan based on advanced MRI compare to the distribution by the clinical radiotherapy plan? Participants will undergo an extended MRI-protocol prior to radiotherapy. This extended MRI-protocol includes the clinical brain tumor imaging protocol plus additional advanced MRI-sequences. Radiation treatment and patient follow-up will occur according to the clinical standard.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06183983
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06177964 - Randomized Phase 2 Clinical Trial of Repeated Intratumoral and Cervical Perilymphatic Lerapolturev Injections Versus Lomustine in Recurrent Glioblastoma (GBM) (PHASE2, RECRUITING): The purpose of this research study is to determine the safety and efficacy of administering two doses of lerapolturev in residual disease (within tumor margins) after surgery, followed later by repeated injections of lerapolturev in the subcutaneous area (under the skin) around the lymph nodes of the head and neck for adult patients diagnosed with recurrent glioblastoma at the Preston Robert Tisch Brain Tumor Center (PRTBTC) at Duke.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06177964
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06160206 - A Phase II Open Label, Randomized Study Testing the Efficacy of Retifanlimab in Combination with Bevacizumab and Hypofractionated Radiotherapy in Patients with Recurrent GBM (PHASE2, RECRUITING): This phase II trial tests how well retifanlimab with bevacizumab and hypofractionated radiotherapy, compared to bevacizumab and hypofractionated radiotherapy alone, works in treating patients with glioblastoma that has come back after a period of improvement (recurrent). A monoclonal antibody is a type of protein that can bind to certain targets in the body, such as molecules that cause the body to make an immune response (antigens). Immunotherapy with monoclonal antibodies, such as retifanlimab, may help the body's immune system attack the cancer, and may interfere with the ability of tumor cells to grow and spread. Bevacizumab is in a class of medications called antiangiogenic agents. It works by stopping the formation of blood vessels that bring oxygen and nutrients to tumor. This may slow the growth and spread of tumor. Hypofractionated radiation therapy delivers higher doses of radiation therapy over a shorter period of time and may kill more tumor cells and have fewer side effects. Giving retifanlimab with bevacizumab and hypofractionated radiotherapy may work better in treating patients with recurrent glioblastoma than bevacizumab and hypofractionated radiotherapy alone.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06160206
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06097975 - A Phase I Clinical Trial on Combined (Neo-)Adjuvant Intravenous Plus Intracranial Administration of Ipilimumab and Nivolumab in Recurrent Glioblastoma (PHASE1, RECRUITING): The goal of this phase I interventional study is to determine the safety and feasibility of the proposed investigational (neo-)adjuvant treatment regimen in patients with resectable reccurent glioblastoma. Participants will: * receive neo-adjuvant administration of intravenous immunotherapy * followed by a maximal safe neurosurgical resection * afterwards, immunotherapy will be injected into the brain tissue * followed by insertion of an Ommaya reservoir * postoperatively, administration of immunotherapy will be continued
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06097975
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06069726 - A Multicenter Trial to Identify Optimal Atezolizumab Biomarkers in the Setting of Recurrent Glioblastoma. The MOAB Trial (PHASE2, RECRUITING): This is to study if neoadjuvant atezolizumab therapy is beneficial for patients with recurrent glioblastoma and a low mutational burden.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06069726
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), recurrence_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06061809 - Open-Label, Single-Arm Phase 2 Study of Nogapendekin Alfa Inbakicept, PD-L1 t-haNK, Bevacizumab and Randomized Phase 2B Study of Nogapendekin Alfa Inbakicept, Bevacizumab, and Tumor Treatment Fields With or Without PD-L1 t-haNK in Participants With Recurrent or Progressive Glioblastoma (PHASE2, RECRUITING): This study consists of 2 portions. The phase 2 portion is an open-label, single-arm study to evaluate the safety and efficacy of NAI, PD-L1 t-haNK, and bevacizumab combination therapy in participants with recurrent or progressive GBM. The phase 2B portion is an open-label, randomized study to evaluate the efficacy and safety for the following 2 experimental arms in participants with recurrent or progressive GBM: NAI, bevacizumab, and TTFields combination therapy (Arm A) or NAI, PD-L1 t-haNK, bevacizumab, and TTFields combination therapy (Arm B). Phase 2 Treatment for all enrolled participants will consist of repeated cycles of 28 days for a maximum treatment period of 76 weeks (19 cycles) as follows: Every 2 weeks (Days 1 and 15 of a 28-day cycle) Fourteen (14) participants were enrolled in the phase 2 portion of this study as of the date of this v02 protocol. No additional participants will be administered therapy in phase 2. Phase 2B Participants will be randomized 1:1 to 1 of 2 experimental arms (Arm A or Arm B). Treatment for all enrolled participants will consist of repeated 8-week cycles for a maximum treatment period of up to 80 weeks (10 cycles). Experimental Arm (A): Every 2 weeks (Days 1, 15, 29, and 43 of an 8-week cycle) Up to twenty (20) participants will be randomized in phase 2B (up to 10 participants/arm. Duration of Treatment: Participants will receive study treatment for up to 76 weeks during phase 2 (up to 19 repeated 28-day cycles) and for up to 80 weeks (up to 10 repeated 8-week cycles) during phase 2B or until they report unacceptable toxicity (not corrected with dose reduction), withdraw consent, or if the Investigator feels it is no longer in the participant's best interest to continue treatment. Treatment may also be discontinued if the participant has confirmed PD per iRANO, unless the participant is clinically stable and is considered potentially deriving benefit per Investigator's assessment. Duration of Follow-up: Participants who discontinue study treatment should remain in the study for follow-up. Participants should be followed for collection of survival status, posttreatment therapies (phase 2 and phase 2B), and medical history (phase 2B only) every 12 weeks (± 2 weeks) for the first 2 years then yearly thereafter for an additional 3 years. The maximum duration of follow-up is 5 years (260 weeks).
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06061809
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06039709 - Pilot Study of Sonodynamic Therapy With 5-ALA for the Treatment of Recurrent Glioblastoma Using Neuronavigation-Guided Low-Intensity Focused Ultrasound (PHASE1, RECRUITING): Patients diagnosed with glioblastoma (GBM) are faced with limited treatment options. This pilot study will evaluate the safety and feasibility of combining an investigational drug called 5-ALA with neuronavigation-guided low-intensity focused ultrasound (LIFU) for patients who have recurrent GBM. Focused ultrasound (FUS) can be used to non-invasively destroy tumor tissue while preserving normal tissue. When FUS is combined with 5-ALA, this combinatorial approach is called sonodynamic therapy (SDT), and this investigational therapy is being tested for its ability to cause damage to GBM cells. SDT will take place prior to surgery for recurrent GBM.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06039709
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06011109 - A Pilot Study of APG-157 With Bevacizumab for Patients With Recurrent High-Grade Glioma (PHASE1, PHASE2, RECRUITING): The goal of this interventional study is to evaluate the efficacy of APG-157 in combination with Bevacizumab in subjects with recurrent high-grade glioma. The main questions the study aims to answer are: * Progression-free and overall survival of patients receiving this combination; * Quality of Life (QOL); and * Tumor response on imaging The participants will take APG-157 daily by dissolving two pastilles in their mouth at around breakfast, lunch and dinner time (total of six pastilles per day). The pastilles dissolve in the mouth. The participants will continue to receive Bevacizumab as standard of care.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06011109
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 3 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05941234 - Improving Personalised Glioblastoma Care by Stem Cell Analysis, Omics (Including Immunomics) and Artificial Intelligence Approaches (NA, RECRUITING): The study aims at: 1. Perform a multilayer analysis relying on tight integration of in-depth multi-omics approaches with clinical data to discover immune markers, with attention to age and sex differences, predicting prognosis and defining key life/environmental elements, to guide AI-driven personalised treatments and ensure improved care and QoL of glioblastoma patients. 2. To deepen glioblastoma knowledge through the study of glioblastoma stem cell cultures and to assess the sensitivity of glioblastoma stem cell cultures to a number of chemotherapeutics in different experimental conditions. 3. To create a comprehensive, stakeholder-generated guidelines for the ethical use of patient data for artificial intelligence-assisted prediction systems in glioblastoma, including an online, easily accessible patient information brochure to increase patient empowerment in the field.
  Quick read: GBM-specific treatment study for first-recurrence GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05941234
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05917145 - Phase 0/I Clinical Trial of the ATM-Inhibitor WSD0628 in Combination With Radiation Therapy for Recurrent High-Grade Glioma (PHASE1, RECRUITING): The purpose of this study is to test WSD0628 in combination with radiation therapy for recurrent brain tumors.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05917145
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT05871021 - A Phase IIa, Open-label, Multicenter Study of Radiochemotherapy With Isotoxic Dose Escalation and Protective VEGF Inhibition Using Bevacizumab in the Treatment of Patients With First Diagnosis of IDH Wild-type, MGMT Unmethylated Glioblastoma (PHASE2, RECRUITING): Glioblastoma is the most aggressive brain tumor and often recurs locally despite intensive treatment. Standard chemoradiotherapy with 60 Gy may not be sufficient to control the tumor, and dose escalation seems to be warranted, but causes more toxicity. To address this, the multicentric PRIDE trial employs two cycles of bevacizumab to achieve dose escalation isotoxically. The goal is improved survival without significantly increasing side effects. The study uses a simultaneous integrated boost with a total dose of 75 Gy in 2.5 Gy per fraction.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05871021
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05773326 - A Phase 0, Single-center, Open-label, Dose-escalating Trial Using Super-selective Intra-arterial Infusion of a Single Dose of Temsirolimus for the Treatment of Recurrent High-grade Glioma (EARLY_PHASE1, RECRUITING): This is a single-center, open-label, dose-escalating Phase 0 trial that will enroll participants with a confirmed diagnosed recurrent high-grade glioma (grade 3 or 4 per WHO criteria) targeting the mTOR pathway. Eligible participants will be administered a single infusion of temsirolimus through super-selective intra-arterial infusion or intravenous infusion. Participants will receive the study drug administration on the same day as the planned surgical resection of the tumor.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05773326
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05769660 - An Open-label, Phase I Clinical Trial to Assess the Maximum Tolerated Dose (MTD), Safety and Efficacy of BEY1107 in Combination with Temozolomide in Patient with Recurrent or Progressive Glioblastoma Multiforme (GBM) (PHASE1, RECRUITING): This is a Phase 1 study to evaluate the maximum tolerated dose, safety and efficacy of BEY1107 in combination with Temozolomide in Patients with Recurrent or Progressive Glioblastoma Multiforme (GBM)
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05769660
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05653635 - Contribution From PET-DOPA in Glioblastoma Re-irradiation - A Randomized Phase II Study (PHASE2, RECRUITING): ReciDOPA is a phase II, single-stage randomized, multicenter, prospective trial assessing the efficacy of an irradiation protocol based on Intensity-modulated radiation therapy with simultaneous-integrated boost guided by FDOPA-PET in patient with recurrent glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05653635
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05590689 - Phase I/II Dose Escalation Trial of Radiodynamic Therapy (RDT) With 5-Aminolevulinic Acid in Patients With First Recurrence of Glioblastoma (PHASE1, PHASE2, RECRUITING): The investigational drug 5-ALA (known under the trade name Gliolan®) is an approved drug for the surgical removal of malignant glioma (WHO grade III and IV). In this trial, the drug is being tested outside of its actual approval as a radiosensitizer in combination with conventional radiotherapy for first-time recurrence (relapse) of malignant glioma. In this clinical trial, the investigational drug 5-ALA is being used for the first time in a multiple dose escalation regimen in combination with radiotherapy following surgical removal of a recurrent malignant glioma in humans. The investigational drug, 5-ALA, has been used as a single dose to date as a standard of care for visualization of malignant tissue in the surgical removal of gliomas. The planned clinical trial will first and foremost investigate how well repeated administration of the investigational drug 5-ALA is tolerated in combination with radiotherapy. At the same time, the design of the trial serves to optimize this novel therapeutic procedure with regard to the frequency of administration of the investigational drug 5-ALA in combination with radiotherapy for future clinical trials. As a secondary objective, the efficacy of additional 5-ALA administration will also be investigated.
  Quick read: GBM-specific treatment study for first-recurrence GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05590689
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05577091 - Phase 1 Study of Autologous Tris-CAR-T Cell Locoregional Immunotherapy for Recurrent Glioblastoma (PHASE1, RECRUITING): This is a Phase 1 study of recurrent glioblastoma locoregional adoptive therapy with autologous peripheral blood T cells lentivirally transduced to express a dual-target, truncated IL7Ra modified chimeric antigen receptor (CAR), delivered by Ommaya reservoir, a pre-indwelled catheter in the tumor resection cavity or ventricle. Patients with pathological confirmation of glioblastoma and radiological evidence of recurrence are candidates for this clinical trial. If the patient meets all other eligibility criteria, and meets none of the exclusion criteria, will have leukapheresis, and a subsequent Ommaya reservoir implantation. T cells will be isolated from the PBMC sample and then be bioengineered into a 4th generation CAR-T cell, Tris-CAR-T cells. Recipients will be assigned to three courses in the order of enrollment. The first 2 patients will be assigned to the low-dose group. The second 2 patients will be assigned to the high dose group. The first 4 patients will have at least one dose of autologous Tris-CAR-T cells delivery via the Ommaya reservoir, at a maximum of 6 doses. The interval between the first and the second dose is 28 days, and the rest doses will be administered weekly. The last 6 patients will be assigned to the consecutive multidose group, and will receive a weekly dose of autologous Tris-CAR-T cells for a maximum of 8 weeks. All patients will undergo studies including MRI to evaluate the effect of the CAR-T cells, physical examination, and cerebrospinal fluid cytokine assays to evaluate side effects. All patients will undergo a long-term follow-up. The hypothesis is that an adequate amount of Tris-CAR-T cells can be manufactured to complete all the three courses. The other hypothesis is that Tris-CAR-T cells can safely and effectively be administered through the Ommaya reservoir to allow the CAR-T cells to directly interact with the tumor cells for each patient enrolled in the study. The primary aim of the study will be to evaluate the safety of Tris-CAR-T administration. Secondary aims of the study will include evaluating CAR-T cell distribution within cerebrospinal fluid and peripheral blood, tumor progress post-CAR-T cell infusion, and, if tissue samples from multiple time points are available, also evaluate the degree of target expression, biological characteristics of samples at diagnosis versus at recurrence or progression.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05577091
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05557292 - A Phase I/Ib, Open-Label, Dose-Escalation Study of RMC-5552 Monotherapy in Adult Subjects With Recurrent Glioblastoma (PHASE1, RECRUITING): This phase I/Ib trial tests the side effects, best dose, tolerability, and effectiveness of RMC-5552 in treating patients with glioblastoma that has come back (recurrent). RMC-5552 is a type of medicine called an mechanistic target of rapamycin (mTOR) inhibitor. These types of drugs prevent the formation of a specific group of proteins called mTOR. This protein controls cancer cell growth, and the study doctors believe stopping mTOR from forming may help to kill tumor cells.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05557292
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05540275 - Phase 2 Study to Evaluate the Clinical Efficacy and Safety of Tislelizumab Plus Low-dose Bevacizumab in Bevacizumab Refractory Recurrent Glioblastoma With PTEN or TERT Gene Mutations (PHASE2, NOT_YET_RECRUITING): The purpose of this study is to evaluate the clinical efficacy and safety of Tislelizumab (one anti-PD-1 antibody same as nivolumab approved in China) in combination with bevacizumab in patients with recurrent or progressive glioblastoma (GBM) who have progressed on bevacizumab with or without PTEN or TERT gene mutations.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05540275
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05463848 - A Surgical "Window-of-Opportunity" and Phase II Trial of Pembrolizumab, Olaparib and Temozolomide in Recurrent Glioblastoma (PHASE2, RECRUITING): This research study is studying a combination therapy as a possible treatment for recurrent glioblastoma (GBM), a brain tumor that is growing or progressing despite earlier treatment. The names of the study interventions involved in this study are/is: * Pembrolizumab * Olaparib * Temozolomide (Temodar)
  Quick read: GBM-specific treatment study for first-recurrence GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05463848
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), ecog_max=1 vs 1 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05366179 - Phase I Study of Intraventricular Infusion of T Cells Expressing B7-H3 Specific Chimeric Antigen Receptors (CAR) in Subjects With Recurrent or Refractory Glioblastoma (PHASE1, RECRUITING): The purpose of this study is to test the safety of using T lymphocyte chimeric antigen receptor cells against the B7-H3 antigen (CAR.B7-H3T cells) in patients with glioblastoma. CAR.B7-H3T cells treatment has not been tested in humans and is not an approved treatment by the Food and Drug Administration for glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05366179
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05363826 - Phase I Study of the Safety of Intracavitary Photodynamic Therapy (PDT) of the Brain Bordering Resected Recurrent Glioblastoma or Gliosarcoma Using Intravenous Photobac® and a Balloon Light Applicator (PHASE1, RECRUITING): This study is the first step in testing the hypothesis that adding Photobac® Photodynamic Therapy to surgical removal of a glioblastoma or gliosarcoma will be both safe and effective. Photodynamic Therapy (PDT) combines light and a photosensitizer. PDT has been used to treat a variety of cancers with varying degrees of success. For the past thirty years Photolitec has been working to develop a treatment for glioblastoma or gliosarcoma using light and a photosensitizer. Photolitec's scientists were looking for a photosensitizer that: 1. has no significant systemic toxicity apart from some temporary skin photosensitivity, 2. crosses the blood brain barrier, 3. accumulates to a high level in glioblastoma and minimally in the brain, 4. is activated by the wavelength of light that penetrates most deeply into the brain, 5. minimizes any temporary skin photosensitivity. Preliminary testing indicates the Photolitec team has achieved these five goals. Photolitec is now able to offer a clinical trial based on the results of this work.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05363826
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_chemoradiation, Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05303467 - FRONTIER: A Feasibility Study to Evaluate the Safety of the TheRaSphere GliOblastoma (GBM) Device iN PaTIEnts With Recurrent GBM (PHASE1, RECRUITING): The FRONTIER Study is a prospective, interventional, single-arm, multi-center, study to assess the safety and technical feasibility of TheraSphere GBM in patients with recurrent GBM.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05303467
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT05284643 - Pilot Trial of Spectroscopic MRI-guided, Dose-Escalated Proton Radiation Therapy and Bevacizumab for Recurrent Glioblastoma (NA, RECRUITING): The purpose of this research is to find hidden cancer with an experimental magnetic resonance imaging (MRI) scan called spectroscopic magnetic resonance imaging (sMRI). That spectroscopic MRI scan will be used to increase the area of the brain receiving radiation and then the dose of radiation in attempt to kill more of the cancer. Proton radiotherapy and bevacizumab (Avastin) are used to minimize the possible side effects of this approach.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05284643
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05186064 - Glioblastoma Targeted Treatment Option Maximization by Whole Genome Sequencing (NA, RECRUITING): In Dutch centers performing neurosurgery on and/or treating GBM, all recurrent GBM patients are discussed in local tumor boards and this setup will be used to effectively identify possible GLOW study candidates. 160 patients that will undergo re-resection in the GLOW study will be presented with WGS results leading to added treatment options.
  Quick read: GBM-specific treatment study for first-recurrence GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05186064
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05083754 - A Randomized, Open-label Pilot Trial to Evaluate the Safety and Efficacy of Carmustine Wafer in Combination With Retifanlimab and Standard Radiation With or Without Temozolomide in Newly-Diagnosed Adult Subjects With Glioblastoma (PHASE1, RECRUITING): The purpose of the study is to evaluate the safety and survival of carmustine wafers and radiation and retifanlimab with or without temozolomide (TMZ) in newly-diagnosed adult subjects with glioblastoma multiform after carmustine wafer placement.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05083754
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05043701 - Individualized Systems Medicine Strategy for Targeting Cancer Stem Cells in Patients With Recurrent Glioblastoma (ISM-GBM) (EARLY_PHASE1, RECRUITING): A study to determine the feasibility and safety of individualized cancer stem cell targeted therapy based on high-throughput functional profiling of FDA/EMA-approved drugs in patients with GBM that has recurred or progressed following standards-of-care (RT, TMZ).
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05043701
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT04977375 - Phase Ib/II Trial of Anti-PD-1 Immunotherapy and Stereotactic Radiation in Patients With Recurrent Glioblastoma (PHASE1, PHASE2, RECRUITING): The purpose of this study is to assess the safety/tolerability/feasibility of pembrolizumab and radiation therapy before surgical resection in patients with recurrent glioblastoma as defined by treatment-related AEs and the number of patients who do not necessitate a delay in surgical resection, and to assess overall survival. The secondary objectives are to assess progression free survival, and to assess the T cell clonality, CD8 T cell activation and Tumor Infiltrating Lymphocyte (TIL) score after treatment
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04977375
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT04933422 - Phase 1 Study Evaluating the Safety, Pharmacokinetics, Pharmacodynamics and Clinical Effects of CM93 in Subjects With Recurrent Glioblastoma (rGBM) Characterized by Epidermal Growth Factor Receptor (EGFR) Mutation or Amplification (PHASE1, NOT_YET_RECRUITING): This is a first-in-human study of CM93, an oral investigational drug, in adults with Epidermal Growth Factor Receptor-modified glioblastoma. The study is designed in three parts consisting of a dose-escalation phase, a dose-expansion phase and a window-of-opportunity surgical trial. The trial objectives are to evaluate the safety, pharmacokinetics, pharmacodynamics and clinical effects of CM93 in this patient population.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT04933422
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT04863950 - A Phase II, Investigator-Initiated Study of Imipramine Hydrochloride and Lomustine in Recurrent Glioblastoma (PHASE2, RECRUITING): This study is designed as a single center, prospective, open label, single-arm therapeutic trial with both surgical and non-surgical cohorts.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04863950
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04765098 - A Randomized Controlled Trial of Tamoxifen Versus Etoposide for Patients With First Recurrence of Glioblastoma Multiforme (PHASE2, RECRUITING): The investigator propose a single-center randomized phase II controlled study designed to compare the management of first recurrence of GBM using etoposide versus tamoxifen.
  Quick read: GBM-specific treatment study for first-recurrence GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04765098
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs True (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT04590664 - A Phase 1 / 2 Study of Visudyne (Liposomal Verteporfin) in Persons with Recurrent High Grade EGFR-Mutated Glioblastoma (PHASE1, PHASE2, RECRUITING): This phase I/II trial studies the side effects and best dose of Visudyne (liposomal verteporfin) and to see how well it works in treating patients with high grade EGFR-mutated glioblastoma that has come back (recurrent). Visudyne is FDA approved in combination with light to treat eye diseases. In this study we use Visudyne by itself like chemotherapy to kill tumor cells which may be sensitive to verteporfin.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04590664
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04573192 - A Study to Evaluate the Safety and Efficacy of the Tumor-targeting Human Antibody-cytokine Fusion Protein L19TNF Plus Lomustine in Patients With Glioblastoma at First Progression (PHASE1, PHASE2, RECRUITING): Glioblastomas are the most common and most aggressive primary brain tumors in adults. The prognosis is poor despite multimodal therapy with surgery, radiotherapy and chemotherapy. Therefore, novel treatments are urgently needed. L19TNF is a fully human fusion protein consisting of human tumor necrosis factor (TNF)-α fused to the L19 antibody in scFv format, specific to the extra-domain B of fibronectin. TNF not only induces apoptosis or necrosis in certain target cells, but also exerts inflammation and immunity. L19TNF selectively delivers TNF to the tumor site to spare normal tissues from undesired toxicity. Preclinical experiments with L19TNF have demonstrated tumor growth retardation in various mouse tumor models including models of glioma.
  Quick read: GBM-specific treatment study for first-recurrence GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04573192
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT04559230 - A Phase II, Multicenter, Prospective Study of Sacituzumab Govitecan in Recurrent Glioblastoma (PHASE2, RECRUITING): This is an open-label single arm study. All patients will receive the study drug. The aim of the study is to compare overall survival (OS) of patients with recurrent brain tumor, known as Glioblastoma (GBM) having high levels of a protein, Trophoblast cell surface antigen 2 (Trop-2), expression on treatment with Sacituzumab Govitecan (SG) versus lomustine only which has been used in the past.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04559230
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04323046 - A Single Arm, Pilot of Neoadjuvant Checkpoint Inhibition Followed by Adjuvant Checkpoint Inhibition in Children and Young Adults With Recurrent or Progressive High Grade Glioma (HGG) (PHASE1, RECRUITING): This phase I trial studies the side effects of nivolumab before and after surgery in treating children and young adults with high grade glioma that has come back (recurrent) or is increasing in scope or severity (progressive). Immunotherapy with monoclonal antibodies, such as nivolumab, may help the body's immune system attack the cancer, and may interfere with the ability of tumor cells to grow and spread.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04323046
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT04267978 - Open-label Prospective Study of Recombinant Human Endostatin Combined with Cytotoxic Chemotherapy Regimen in the Treatment of Recurrent Gliomas (PHASE2, RECRUITING): Almost all gliomas relapse. After temozolomide rechallenge or combination with irinotecan, the progression-free survival rate at 6 months (PFS-6%) of recurrent glioblastoma was about 21%. After treatment with irinotecan-based chemotherapy regimen, the PFS-6% of recurrent lower-grade gliomas was 40%. The optimal chemotherapeutics of recurrent gliomas has yet to be determined. Anti-angiogenesis is a promising therapeutic strategy. Vascular endothelial growth factor-A (VEGF) is the primary driver of angiogenesis in tumors. Bevacizumab, a humanized monoclonal antibody directed against VEGF, is the prototypical anti-angiogenic drug and received accelerated approval of the United States Food and Drug Administration (FDA) for the treatment of recurrent glioblastoma. Bevacizumab inproved the PFS-6% (36%), but had no effect on the overall survival (OS) (9.2 months). Moreover, the effects of bevacizumab are transient and most patients' tumors progress just after a median time of 3-5 months. Recombinant human endostatin (rh-ES) is an endogenous broad-spectrum angiogenesis inhibitor that has been shown to significantly improve therapeutic efficacy when combining with conventional chemotherapy agents in non-small-cell lung cancer, breast cancer and melanoma. In our previous study, we retrospectively analyzed the effect and toxicity of rh-ES when combined with temozolomide and irinotecan on adult recurrent disseminated glioblastoma. After combined treatment, PFS-6% was 23.3%; the median PFS and OS were 3.2 and 6.9 months, respectively, which were promising compared with that in other studies. Once patients get radiographic remission in a short time (4 months), they may get a long PFS.The combined regimen did not reduce the sensitivity of tumor to bevacizumab. After tumor progression from the combined chemotherapy, bevacizumab usage could help to prolong the survival time (5.1 months versus 2.4 months). Moreover, the toxicities of the combination therapy in this study were manageable. On the basis of prior clinical experience, we carry out this prospective trial to confirm the efficacy and safety of the combination of rh-ES, temozolomide and irinotecan in patients with recurrent gliomas.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04267978
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT04003649 - A Phase 1 Study to Evaluate IL13Rα2-Targeted Chimeric Antigen Receptor (CAR) T Cells Combined With Checkpoint Inhibition for Patients With Resectable Recurrent Glioblastoma (PHASE1, RECRUITING): This phase I trial studies the side effects and how well IL13Ralpha2-CAR T cells work when given alone or together with nivolumab and ipilimumab in treating patients with glioblastoma that has come back (recurrent) or does not respond to treatment (refractory). Biological therapies, such as IL13Ralpha2-CAR T cells, use substances made from living organisms that may attack specific glioma cells and stop them from growing or kill them. Immunotherapy with monoclonal antibodies, such as nivolumab and ipilimumab, may help the body's immune system attack the cancer, and may interfere with the ability of tumor cells to grow and spread. It is not yet known whether giving IL13Ralpha2-CAR T cells and nivolumab together may work better in treating patients with glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04003649
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT03382977 - A Three-part, Phase I/II Dose-Escalation Study to Define the Safety, Tolerability, and Optimal Dose of Candidate GBM Vaccine VBI-1901 With Subsequent Extension of Optimal Dose in Recurrent GBM Subjects (PHASE1, PHASE2, RECRUITING): The purpose of this study is to assess the safety and tolerability of VBI-1901 in subjects with recurrent malignant gliomas (glioblastoma, or GBM).
  Quick read: GBM-specific treatment study for first-recurrence GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03382977
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT02394626 - RESURGE - Randomized Controlled Comparative Phase II Trial on Surgery for Glioblastoma Recurrence (PHASE2, RECRUITING): Patients with glioblastoma face a grim prognosis. Despite recent advancement in neurosurgical technology and neuro-oncology glioblastomas almost invariably progress or recur after a median of 4-8 months. The strategy to repeat tumor resection at recurrence in order to minimize tumor load and thus to facilitate subsequent second-line therapy has been shown to be feasible and safe. However, evidence for a survival benefit of surgery for recurrent glioblastoma is scarce and relies entirely on retrospective analyses. While most retrospective analyses report an apparent survival benefit, an EORTC meta-analysis on second-line therapies found no survival difference in patients with or without surgery at recurrence. With regard to the risks and costs inherent to surgery for glioblastoma, a randomized controlled trial is required. The purpose of the study is to compare the effect of craniotomy and tumor resection followed by adjuvant second-line therapy to no surgery followed by second-line therapy on overall survival, neurological status, and quality of life. Analysis of overall survival will be used to improve sample size estimation of a subsequent phase III trial for craniotomy and tumor resection of glioblastoma recurrence in cooperation with the EORTC.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02394626
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07492836 - Prospective, Pilot Study to Evaluate Hypofractionated Radiotherapy Associated With Temozolomide in Patients Aged 18 to 70 Years With Glioblastoma (HypoGBM) (NA, NOT_YET_RECRUITING): The goal of this clinical trial is to evaluate the feasibility, safety and effectiveness of radiotherapy with fewer days of treatment and a higher dose of radiation each day in patients under 70 years of age diagnosed with a brain tumor known as glioblastoma.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07492836
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07461948 - Advanced MRI for Visualization and Quantification of the Tumor Immune Microenvironment (TIME) in Glioblastoma (PHASE3, RECRUITING): This phase III trial is evaluating whether a combination of three advanced magnetic resonance imaging (MRI) techniques, including chemical exchange saturation transfer (CEST) MRI, diffusion-relaxation correlation spectrum imaging (DR-CSI), and ferumoxytol-enhanced magnetic resonance imaging (Fe-MRI) are effective as non-invasive methods for assessing the cells and proteins that surround and interact with tumor cells (the tumor immune microenvironment) in patients with glioblastoma. Researchers understand that some types of brain tumors are harder to treat than others, but the reasons for this are not known in many cases. CEST MRI uses differences in the tissue microenvironment, like protein concentration or intracellular pH, to generate contrast differences. DR-CSI detects microstructural changes in tissue associated with immune cells infiltrating the tumor. Fe-MRI uses ferumoxytol as a contrast agent with MRI. Contrast agents are substances that are injected into the body and taken up by certain tissues, making the tissues easier to see in imaging scans. More advanced imaging techniques like CEST, DR-CSI, and Fe-MRI may offer less invasive methods than surgery or biopsy for helping researchers understand the tumor immune microenvironment in patients with glioblastoma, which may help researchers determine why some tumors are more resistant to treatment.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07461948
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07391215 - 5G-PEARL: Paxalisib in Combination With Temozolomide in Patients With High Grade Malignant Brain Tumours Within the 5G Platform (PHASE1, PHASE2, RECRUITING): The purpose of this clinical trial is to evaluate the safety and tolerability of paxalisib in combination with temozolomide and to determine the preliminary antitumour activity of the combination therapy. In the Phase 1b of this study parallel biomarker defined arms will be opened in the front-line unmethylated MGMT setting, enrolling 10 patients onto each arm. These patients will be treated with paxalisib in combination with temozolomide (TMZ). The starting dose of paxalisib will be 45mg once a day (OD) with the option of increasing to 60 mg (30 mg BD) in Cycle 2. TMZ will be administered once daily by mouth on days 1 to 5 in a 28-day cycle, with a starting dose of 150mg/m2 during cycles 1 and 2, and subsequent dose escalation to 200mg/m2 at the start of cycle 3 if cycles 1 and 2 have been well tolerated with no significant toxicity.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07391215
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low
- NCT07368283 - A Single-arm Phase II Non-inferiority Clinical Study of Limited Target Volume Radiotherapy After Glioblastoma Surgery (NA, NOT_YET_RECRUITING): Research on radiotherapy target volumes for glioblastoma is increasingly focused on exploring more limited yet effective irradiation fields, aiming to achieve local control while minimizing acute and long-term neurotoxicity. Previous retrospective analysis by investigators revealed that local recurrences of glioblastoma are predominantly confined to a narrow margin around the original lesion: 98.3% of recurrences occurred within 0.5 cm of the original T2-FLAIR abnormality, 94.8% within 1 cm of the original T1-enhanced region. These findings have been cited in the ESTRO-EANO treatment guidelines. Building on this evidence, investigators plan to conduct a single-arm, phase II clinical trial to systematically evaluate the efficacy and safety of a 1 cm radiotherapy target volume in post-operative glioblastoma patients.Eligible patients with glioblastoma who have undergone surgical resection will be selected to receive limited-field radiotherapy. The target volume will be defined based on the postoperative MRI enhancing lesion: a 1 cm margin will be added to form the clinical target volume (CTV), followed by a further 0.3 cm margin to create the planning target volume (PTV). A total dose of 60 Gy will be delivered in 30 fractions (2 Gy per fraction, 5 fractions per week). Concurrent and adjuvant chemotherapy will be administered per standard guidelines. The primary efficacy endpoints are the 6-month progression-free survival rate and the incidence of symptomatic radiation-induced brain necrosis of grade 3 or higher. Secondary endpoints include overall survival, patterns of recurrence, neurocognitive function, and quality of life.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07368283
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07144735 - Allogeneic Gamma Delta (γδ) T Cells for the Treatment of Glioblastoma (NA, RECRUITING): This first-in-human clinical study aims to evaluate the safety and feasibility of locally delivered, allogeneic γδ T cells (genetically edited with ARIH1 and BCL11b knockout, designated ABOUT γδT cells) in patients with glioblastoma multiforme (GBM). The engineered effector cells are delivered via localized administration to selectively target and eliminate residual GBM cells. ABOUT: ARIH1 and BCL11b knockOUT γδ T cells.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07144735
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07089758 - A Pilot Feasibility Study for Cerebral Open Flow Microperfusion in Patients Undergoing Planned Neurosurgical Resection of Diseased Parenchyma. (NA, NOT_YET_RECRUITING): The purpose of this study is to evaluate the safety and feasibility of intra-operative microperfusion during a planned neurosurgical resection of diseased brain parenchyma, including either an epileptic focus requiring temporal lobectomy or a glioma. Devices used for microperfusion are Joanneum Research cerebral open flow microperfusion (OFM) catheters, push and pull tubing, and MPP102-II pump.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07089758
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07067905 - Clinical Evaluation of [68Ga]Ga-XT771 PET for Diagnosis in Patients With Glioblastoma and Clear Cell Renal Cell Carcinoma (EARLY_PHASE1, RECRUITING): A prospective, open-label, phase 1 study. This clinical trial aims to evaluate the diagnostic value of 68Ga-XT771, a CAIX/CAXII protein-specific probe, in PET/CT imaging for patients with clear cell renal cell carcinoma and glioblastoma. Safety, tolerability, and biodistribution characteristics of 68Ga-XT771 will also be assessed.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07067905
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06781372 - Development and Characterization of Patient's Derived Organoids as a Platform for the Screening of Novel Therapeutic Treatments for Glioblastoma Multiforme (NA, NOT_YET_RECRUITING): The study will enroll patients suffering from glioblastoma, a malignant brain tumor. Intervention is intended as a laboratory intervention and not as a clinical intervention. In fact, tumor removed from patients' brains will be sent to a dedicated laboratory to obtain an "avatar" of the tumor, named patient-derived organoid (PDO). A number of experimental antitumor approaches will be studied on PDOs. Results of these experiments will be correlated to the prognosis of patients.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06781372
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06764537 - Evaluation of in Vitro Antitumor Activity of GD2 CAR-T Cells Generated From Blood of Glioblastoma Patients (NA, NOT_YET_RECRUITING): Glioblastoma is a brain tumor with a very poor prognosis, affecting around 2,400 new patients every year. Current treatments do not provide good control of the disease. In view of the therapeutic impasse, it is necessary to develop new strategies. CAR-T cells (Chimeric antigen receptor T cells) represent a highly promising therapy for the treatment of incurable cancers, including glioblastoma. This treatment aims to destroy cancer cells by relying on the patient's own immune system. CAR-T cells are generated from the patient's own immune cells, more specifically T lymphocytes, which are genetically modified to express a tumor-specific receptor on their surface. CAR-T cells bind to tumor cells and cause their destruction. However, these cells have shown limited therapeutic power in the treatment of brain tumors. This is mainly due to the microenvironment surrounding the tumor, which is composed of immunosuppressive cells. These cells, and the molecules they secrete, help to reduce the activity of CAR-T cells that would otherwise reach the tumor. Little is currently known about these resistance mechanisms. The aim of this research is therefore to better understand these resistance mechanisms in order to propose a strategy for enhancing the therapeutic action of CAR-T cells in the treatment of glioblastoma. The main objective of this research is to evaluate the impact of the tumor environment on the antitumor efficacy of anti-GD2 CAR-T therapeutic cells in an in vitro glioblastoma model. Both tumor environment cells and CAR-T therapeutic cells will be generated from glioblastoma patient cells. The secondary objectives of this research are to * Evaluate the impact of tumor environment targeting on the in vitro antitumor efficacy of anti-GD2 CAR-T therapeutic cells. * Evaluate the quality/quantity of generated cells (CAR-T cells and tumor environment cells) in relation to glioblastoma patients. * Evaluate the efficiency of the cell isolation technique (CAR-T cells and tumor environment cells)
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06764537
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06749925 - Phase III Randomized, Double-Blind, Placebo-Controlled Clinical Trial Assessing the Efficacy and Safety of Dendritic Cell-Based Immunotherapy for Glioblastoma (PHASE3, NOT_YET_RECRUITING): This Phase III, multicenter, placebo-controlled clinical trial with sequential randomization is designed to evaluate the efficacy and safety of an experimental vaccine composed of hybrid dendritic cells (DCs) for the treatment of glioblastoma. Conducted at the Hospital das Clínicas of the University of São Paulo Medical School (HCFMUSP) and the Institute of Biomedical Sciences of the University of São Paulo (ICB/USP), the study is led by Professor José Alexandre Marzagão Barbuto. A multidisciplinary team of researchers specializing in neurosurgery, pathology, hematology, and other fields will contribute to a comprehensive approach. The trial aims to determine whether the hybrid DC vaccine can increase overall survival in adult patients with glioblastoma who have completed standard treatment, including surgery, chemotherapy, and radiotherapy. Secondary objectives include evaluating progression-free survival, quality of life, immune response, and the safety of the intervention. The study will enroll 186 patients, who will be randomized into three groups: (1) a control group receiving placebo, (2) a group receiving the DC vaccine, and (3) a group receiving the DC vaccine combined with pembrolizumab.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06749925
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06687681 - Efficacy of the Intrathecal Injection of Active Allogeneic Natural Killer Cells in Patients With High-grade Gliomas; A Multi-center Phase II Clinical Trial (PHASE2, RECRUITING): Gliomas are the most common malignant brain tumors, which are often associated with high-grade tumors characterized by an inferior prognosis and low patient survival rates in both children and adults. Surgical removal and tumor resection are the primary treatment approaches for gliomas. In such cases, whole-brain radiation therapy is also employed as a therapeutic option, which itself has significant side effects, and studies have shown limited impact on improving patient survival. Targeted therapy and recently investigated approaches such as targeted therapy have shown some tumor regression, but in most cases, tumor recurrence has been observed after initial regression. Therefore, they have a limited impact on prolonging patient survival. Immunotherapy, particularly immunotherapy with specific immune cells, can effectively identify and eliminate cancer cells and has been utilized as a new approach in the past two decades, especially in cancers where conventional methods have limited success. Among the effective immunotherapy methods, using natural killer cells (NK cells) can be one of the promising approaches. Currently, phase I clinical trials have been conducted by our research group in patients with gliomas.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06687681
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06632236 - 5G-EMERALD: A Phase 1 Trial of Amivantamab in High Grade Malignant Brain Tumours Within the 5G Platform (PHASE1, RECRUITING): The purpose of this clinical trial is to evaluate the safety and tolerability of amivantamab and to determine the preliminary antitumour activity of amivantamab administered at the recommended Phase 2 dose (RP2D). In the Phase 1b of this study a biomarker defined arm will be opened, initially in the relapsed GMB setting, enrolling 12 patients. These patients will be treated with amivantamab monotherapy. Amivantamab will be administered intravenously (IV) weekly for the first 4 weeks, then every 2 weeks thereafter until disease progression or unacceptable toxicity. The first dose will be given as a split infusion, 350 mg IV over 4 hours on cycle 1 day 1 and 1400 mg IV over 6 hours on cycle 1 day 2. Subsequent infusions are given at a dose of 1750 mg IV over 2-5 hours in cycle 1 and between 2-3 hours from cycle 2 onwards if the first dose was well-tolerated with no significant toxicity. Progression to Phase 2 is dependent on emergent data and funding.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06632236
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low
- NCT06622434 - New Adjuvant Vaccine in Glioblastoma, a Phase 1/2a Study (NAVIG-1) (PHASE1, PHASE2, RECRUITING): This phase I/II trial evaluates the safety and the immunological efficacy of a cancer vaccine against 2 glioma-associated antigens in newly-diagnosed glioblastomas. The objectives of this study are as follows: Primary objective * phase 1: * to assess the maximum tolerated dose (MTD) and select the recommend Phase 2a dose * phase 2a: * to assess anti- TERT specific T cell responses at 2 months at the selected dose level Secondary objectives: * To assess Short and long-time immunological safety * To assess Evolution of anti-PTPRZ1 and anti-TERT immune T cell responses over time * To assess Progression free survival (RANO 2.0 criteria) * To assess Overall survival * To assess Quality of life by EORTC QLQ30 and BN20 questionnaires as well as objective of ancillary study: to determine the mechanism of action of potential tumour escape in GBM (T-cell lymphocyte phenotype; antigen expression and checkpoint inhibitors on tumour cells at relapse, if available), analysis of circulating antibodies against TERT epitope and/or melanin, and identification of predictive biomarkers of response. Ultimately, this trial together will lead to the implementation of future phase III trial in GBM. All patients enrolled in the study will receive standard treatment consisting of surgical resection of the tumor followed by radio-chemotherapy. Immunotherapy will begin 4 weeks after the completion of radiotherapy.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06622434
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT06617208 - Prognostic IntraOperative Biomarkers ideNtification in Tumor rElatEd suRgery (PIONEER Study) (NA, NOT_YET_RECRUITING): INTRODUCTION AND RATIONALE Aggressive brain tumors like glioma have the ability to infiltrate the surrounding healthy brain tissue, disrupting normal neuronal activities and leading to impaired motor and cognitive functions, as well as causing epilepsy. This malignant brain tumor is considered one of the most challenging cancers to treat, with a median survival of 12 to 15 months. Recent findings on direct neuron-tumor interactions indicate that abnormal brain activity in the regions surrounding brain tumors may contribute to develop epilepsy and accelerating tumor growth. Tumors tend to 'fuel' themselves with neurotransmitters released during its 'daily' neuronal firing. Hyperactive neurons in the peritumoral cortex can form excitatory electrochemical synapses with surrounding tumor cells, creating direct communication pathways within the peritumoral microenvironment, which aids in the progression and proliferation of tumor cells via direct and paracrine signalling pathways. However, the specific features of this abnormal brain activity in the peritumoral cortex have not been fully clarified and information on the pathological changes of neuronal activity in glioma patients is largely lacking. To advance more effective treatment strategies, it is crucial to better understand the complex interactions between the tumor and the brain. This is especially important for the group of patients of which many perceive diminished quality of life because of epilepsy, cognitive functioning and language problems after tumor surgery. Furthermore, a thorough understanding is lacking of what tumor resection does to the original hyperactive peritumoral cortex and if resecting this is beneficial for improving postoperative outcome both for epilepsy as well as regarding survival. Therefore, identifying the hyperactive peritumoral cortex and directly addressing its impacts on the brain function and long-term surgical outcome could be a promising novel therapeutic strategy for treating glioma patients. STUDY AIM The measurement focuses on capturing neuronal activity at single-neuron resolution in the peritumoral cortex of glioma patients using cortical depth electrodes. It is well-established that gliomas can remodel the surrounding brain tissue, leading to abnormal neuronal hyperactivity, which contributes to tumor progression and epilepsy. However, the specific neuronal patterns and underlying mechanisms of these changes are not yet fully understood. This study will aim to collect detailed single-neuron recordings in this context, enabling us to map the precise neurophysiological disruptions caused by gliomas. On the long term, this research could lay the groundwork in identifying novel therapeutic approaches by providing critical in-sights into how gliomas alter brain function.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06617208
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06551909 - Radioimmunotherapy in Solid Tumors (Aim 2- Stereotactic Neoadjuvant Radiotherapy for Glioblastoma) (NA, RECRUITING): This is a prospective multicenter study of hypofractionated radiotherapy for the radiation treatment (RT) of solid tumors and in particular for Glioblastoma (in Aim 2). It is based on the results of ongoing studies at our Institute to validate the efficacy of extremely hypofractionated RT in neoadjuvant settings, which observed immunostimulatory effects of RT and the synergy with immune components. The collaboration between San Raffaele Hospital (Milan), the IRCCS Istituto Nazionale dei Tumori Fondazione G. Pascale (Naples) and the San Giuseppe Moscati Hospital of National Relief and High Specialty (Avellino) will ensure that patient recruitment, treatment and monitoring can be translated into facilities of the National Health System using common procedures. The various departments involved will treat patients with the same methods synergistically exploring the immuno/biological factors related to efficacy (and/or toxicity), based on new radioimmunotherapeutic approaches. Clinical and research activity will be developed jointly, drawing on the expertise in radiotherapy, radiomics, oncology, imaging and immunotherapy skills already available.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06551909
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06336291 - A Dose Optimization Study for L19TNF in Combination With Lomustine in Patients With Glioblastoma at Progression or Recurrence (PHASE2, RECRUITING): The trial aims to collect safety, efficacy, exposure, dose- response, pharmacokinetic and pharmacodynamic information of the combination of L19TNF and lomustine at different dose levels in patients with Glioblastoma at progression or recurrence
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06336291
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low
- NCT06297512 - Interventional, Single-arm, Open-label Open-label, Phase II Trial to Evaluate the Role of Anthracycline Infusion After Radio Therapy (RT) in Pediatric and Young Adults With Glioblastoma (pGBM). (PHASE2, RECRUITING): Glioblastoma (GBM) and diffuse intrinsic bridge gliomas (DIPG) only the most aggressive forms of cancer, and their prognosis remains bleak. Currently, the standard of treatment is TMZ concomitant with radiotherapy, and, at the end of combined treatment, as adjuvant therapy. In vitro and in vivo experimental studies have suggested that anthracyclines are effective antineoplastics for the treatment of gliomas. In patients with solid tumors treated with anthracyclines, continuous infusion administration compared with bolus administration has been shown to provide a better safety profile especially with regard to cardiotoxicity. Based on this evidence, this study aims to evaluate the safety and antitumor activity of combined treatment with Dox, WBRT (whole body radiotherapy), and TMZ in pediatric and young adult patients affected by GMB
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06297512
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06136611 - Preoperative Preradiotherapy TTFields (PORTRAIT) (NA, NOT_YET_RECRUITING): PreOperative PreRAdIotherapy Tumour Treating Fields (PORTRAIT) is a Phase I study that will test the safety and feasibility of Optune administered preoperatively and preradiotherapy in patients with a new radiological diagnosis of glioblastoma (GBM). Participants will be required to undergo additional MRI sequencing scans and provide blood, tear fluid and tissue samples over a maximum of 6 months. After the study patients will follow their standard treatment pathway.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06136611
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06102525 - A Phase 1/2a, Open-label, Multicenter, Dose Escalation and Dose Expansion Study Evaluating the Safety, Tolerability, and Efficacy of RZ-001 in Combination With Valganciclovir in Subjects With Glioblastoma (PHASE1, PHASE2, RECRUITING): This is a Phase 1/2a, open-label study to evaluate the safety, tolerability, immunogenicity, and preliminary clinical activity of RZ-001 administered in combination with VGCV in subjects with hTERT-positive GBM.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06102525
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05842746 - Efficacy and Safety of Elemene Plus Stupp Protocol Versus Stupp Protocol Alone for Newly-diagnosed Glioblastoma: A Multi-center Phase II Randomized Controlled Trial (PHASE2, NOT_YET_RECRUITING): The goal of this phase II randomized clinical trial is to compare the safety and efficacy of Elemene plus Stupp Protocol (the new protocol) and Stupp Protocol alone (the standard protocol) in patients with newly-diagnosed glioblastomas (ndGBMs). The main questions to answer are: * Whether the new treatment protocol (Elemene plus Stupp Protocol) is clinically safe for ndGBM patients. * Whether the new treatment protocol (Elemene plus Stupp Protocol) brings better survival benefits for ndGBM patients compared to the standard-of-care Stupp Protocol. Study participants will be enrolled in 5 hospitals in China and randomly assigned to receive either the new protocol or the standard protocol. The overall survival (OS) rate in the 12th month, the progression-free survival (PFS) rate in the 6th month, OS, PFS, and adverse events assessed by the CTCAE (Common Terminology Criteria for Adverse Events) will be evaluated for all patients.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05842746
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05820191 - B-amyloid as a Marker for GBM Bioimaging (PHASE2, NOT_YET_RECRUITING): This project is aimed at improvement of glioblastoma (GBM) diagnostic strategies for discrimination of tumor progression and chemo- and radiotherapeutic treatment-related changes in brain tissue. The study will elucidate the diagnostic value of PET imaging with use of amyloid-β radioisotope tracer Amyvid (Florbetapir F18) for GBM. The results of the study will provide data for development of new approach for GBM diagnostics.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05820191
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05720078 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-3 (UNITED-3): Applying a Two Phase, Personalized Margin, Reduced Clinical Target Volume Approach (NA, RECRUITING): The goal of this study is to test whether an adaptive radiation therapy (RT), two-phase approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive, two-phase RT approach compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05720078
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05653622 - Simultaneous Integrated Boost FDOPA PET Guided in Patients With Partially- or Non-operated Glioblastoma (PHASE2, RECRUITING): Glioblastoma (GBM) is the most common primary brain cancer in adults. Surgery, chemoradiotherapy (temozolomide TMZ) and then adjuvant TMZ is the standard treatment. But, most patients relapse in a median time of 8-9 months; the median overall survival (OS) ranged from 15 to 18 months. Some frail patients received hypofractionated radiation and concomitant and adjuvant TMZ. For some, the radiation dose is not optimal. Moreover, recurrences develop mainly in the initial tumor site. These two reasons justify increasing the dose. To limit the movements of these fragile patients, the method consists of increasing the dose without increasing the number of sessions by using the Simultaneous Integrated Boost (SIB) which increases the dose in targeted volumes while the rest of the volume receives a minimum dose. A phase I trial showed the possibility of increasing the dose in SIB up to 80 Gy in a part of the GBM enhanced on MRI. FDOPA PET detects certain more aggressive tumor areas, areas likely to recur. Integrating them into the SIB seems appropriate. A phase II trial showed the interest of SIB guided by FDOPA PET in terms of progression-free survival but without impact on OS. This study differed from the one the investigators propose, because a dose and conventional fractionation, identical to that of the European Organization for Research and Treatment of Cancer/National Cancer Information Center (NCIC/EORTC) protocol were delivered, the gliomas were unmethylated MGMT, less likely to respond. Studies with SIB and hypofractionation are often retrospective and for others, hypofractionation was debatable and the dose increase was not based on PET capture but on MRI. However, a prospective phase II study, with SIB and hypofractionation, not integrating FDopa PET has demonstrated the relevance of SIB. In this project, the investigators propose to use the integrated boost technique (SIB) guided by PET FDOPA to increase the radiation dose in GBM, in patients either fragile and partially operated, or only biopsied and for whom the prognosis is the most pejorative.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05653622
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery
- NCT05607407 - Targeting Transsulfuration Via Suppression of Thyroid Hormone Signaling in Progressive Glioblastoma: Phase 2 and Pharmacodynamic Trial of Methimazole in Patients With Progressive Glioblastoma (PHASE2, RECRUITING): The purpose of this study is to test the effectiveness, safety, and tolerability of a drug called Methimazole. The investigational drug, Methimazole is not FDA approved for brain tumors, but it is used to treat thyroid illnesses. Different doses of Methimazole will be given to several study participants with glioblastoma. The first several study participants will receive the lowest dose. If the drug does not cause serious side effects, it will be given to other study participants at a higher dose. The doses will continue to increase for every group of study participants until the side effects occur that require the dose to be lowered. The procedures in this study are research blood draws, physical exams, collection of medical history, MRI scans, and study drug administration.
  Quick read: GBM-specific treatment study for GBM or glioma patients; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05607407
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05502991 - Phase 2 Study to Evaluate the Clinical Efficacy and Safety of Sintilimab Plus Low-dose Bevacizumab in Patients With Glioblastoma of Different Relapse Stages (PHASE2, NOT_YET_RECRUITING): This is an ongoing Phase 2, open-label, single-center, non-randomized study of sintilimab (one anti-PD-1 antibody same as nivolumab approved in China) plus bevacizumab administered in a low dosage schedule in adult (≥ 18 years) participants with a clinical relapse or circulating tumor DNA (ctDNA)-level relapse of glioblastoma (GBM). This study has two non-comparative study groups. Both cohorts will receive the same study drug sintilimab 200mg and bevacizumab 3mg/kg every 3 weeks. A stringent two-step non-randomized process will be used to assign participants to one of the study groups. Neither participants nor doctors but the researcher can choose which group participants are in. No one knows if one study group is better or worse than the other. 60 total participants are expected to participate in this study (30 participants in each cohort). Grouping process: After enrollment, under the standard of care, participants will receive regular tumor in situ fluid (fluid within the surgical cavity, TISF) sampling for ctDNA analysis and recceive regular MRI. The researcher will study the TISF ctDNA and imaging dynamics to determine whether the tumor reaches to ctDNA-level (Cohort 1) or clinical relapse (Cohort 2). At the first step, all timely identified as ctDNA-level relapse tumors will be assigned into the Cohort 1 and receive the study drug immediately, those failed to be timely identified will be assigned into the Cohort 2 and receive the study drug after the clinical relapse. At the second step, once either group reaches the target number, the new participants will be all assigned into the other Cohort.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05502991
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05370079 - Control Cohort CTRL COH (NA, RECRUITING): Autoimmune encephalitis (AE) and paraneoplastic neurological syndromes (PNS) are rare disease that could be difficult to diagnose. So it necessary to obtain numerous sample from different disease to develop more specific diagnosis kit It could be possible through the characterisation of new genetic biomarkers.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05370079
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04752280 - Glioblastoma Radiotherapy Using IMRT or Proton Beams (NA, RECRUITING): Radiation therapy is an integral part of the multimodal primary therapy of glioblastomas. As the overall prognosis in this tumor entity remains unfavorable, current research is focused on additional drug therapies, which are often accompanied by increases in toxicity. By using proton beams instead of photon beams, it is possible to protect large parts of the brain which are not affected by the tumor more effectively. An initial retrospective matched-pair analysis showed that this theoretical physical benefit is also clinically associated with a reduction in toxicity during therapy and in the first few months thereafter. The aim of the GRIPS study is to prospectively test this clinical benefit in a randomized, open-label Phase III study. Patients are treated in the study using either modern photon radiation techniques (standard arm) or proton beams (experimental arm). The primary endpoint is the cumulative toxicity CTC grade 2 and higher in the first 4 months. Secondary endpoints include overall survival, progression-free survival, quality of life, and neurocognition.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04752280
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03548571 - Open Label Randomized Phase II/III Trial of Dendritic Cell Immunotherapy Against Cancer Stem Cells in Glioblastoma Patients Receiving Standard Therapy (DEN-STEM) (PHASE2, PHASE3, RECRUITING): Open, randomized study of a trivalent dendritic cell therapy compared to standard therapy in primary treated patients with IDH wild-type, MGMT-promotor methylated glioblastoma. The IMP is dendritic cells transfected with mRNA of survivin, hTERT og autologous tumor stem cells derived from tumorspheres.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03548571
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT02977780 - INdividualized Screening Trial of Innovative Glioblastoma Therapy (INSIGhT) (PHASE2, RECRUITING): This research study is studying several investigational drugs as a possible treatment for Glioblastoma (GBM). The drugs involved in this study are : * Abemaciclib (arm is currently closed to accrual) * Temozolomide (temodar) * Neratinib (arm is currently closed to accrual) * CC115 (arm is currently closed to accrual) * QBS10072S
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02977780
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT06258018 - A Phase I-II Study of Niraparib Plus Temozolomide "One Week on, One Week Off" in Patients With Recurrent Isocitrate Dehydrogenase (IDH) Wild Type Glioblastoma and IDH Mutant Gliomas. (PHASE1, PHASE2, NOT_YET_RECRUITING): The study evaluates safety, tolerability, pharmacokinetics at recommended phase II dose (RP2D) and preliminary antitumor activity of Niraparib + dd-TMZ "one week on, one week off" in patients affected by recurrent GBM IDH wild-type and recurrent IDH mutant (WHO grade 2-4) gliomas. The treatment will be administered until progressive disease, unacceptable toxicity, consent withdrawal, lost to follow-up or death. The entire study is expected to last approximately 40 months.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06258018
  Review priority: 150
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT05226494 - A Phase 1 Trial to Evaluate the Safety and Tolerability of Fb-PMT in Patients With Recurrent Glioblastoma (PHASE1, RECRUITING): Glioblastoma is a highly aggressive and fatal form of primary malignant brain tumor with limited treatment options. fb-PMT affects a large group of cancer cell signaling pathways and thus may be effective in heterogeneous, treatment-resistant tumors such as Glioblastoma. fb-PMT also is actively transported across the blood-brain barrier into the brain. This study is being conducted to determine the dose level for further clinical development of fb-PMT to treat recurrent Glioblastoma.
  Quick read: GBM-related treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05226494
  Review priority: 150
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06001281 - Predictive Value of Soluble CD146 in Patients With Recurrent Glioblastoma Treated by Bevacizumab (NA, RECRUITING): Glioblastoma is the most common malignant primary brain tumor with poor prognosis because of its diffusive and infiltrative nature. The FDA approved the use of the anti-VEGF antibody bevacizumab in recurrent GBM. However, resistance to this anti-angiogenic reagent is frequent and fails to enhance patients' overall survival. The investigators previously identified one novel mechanism responsible for bevacizumab-resistance in CD146-positive glioblastoma (Joshkon et al. Acta Neuropathol Commun, 2022). Now, the investigators objective is to prospectively monitor the soluble CD146 value in plasma from patients treated by bevacizumab for recurrent glioblastoma. The investigators will collect plasma at baseline, before the first bevacizumab administration, before the second administration, at the time of first MRI evaluation and at progression. Plasma CD146 value will be analyzed by ELISA. The investigators expect to confirm the correlation between soluble CD146 value in plasma and patient response to bevacizumab.
  Quick read: GBM-specific treatment study for recurrent GBM; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06001281
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05565118 - Prospective Surgical Study on the Pattern of Electrical Activity in High Grade Glioma (WHO Grade III and IV) as a Predictor of Progression (PHASE1, RECRUITING): The purpose of this study is to test the safety and feasibility of recording brain activity within and around high-grade glioma tumors at the time of surgery. A small biopsy will be taken at the sites of the recordings.
  Quick read: GBM-specific treatment study for recurrent GBM; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05565118
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07416188 - Phase 1/Phase 2 Open Label Trial of a Novel Indenoisoquinolone C-MYC/TOPOISOMERASE 1 Inhibitor (LMP744) in Recurrent Glioblastoma (PHASE1, PHASE2, NOT_YET_RECRUITING): Background: Glioblastoma is a common brain cancer in adults. Treatment includes surgery, radiation, and chemotherapy. But this cancer can return after treatment and is often fatal. Researchers want to know if a study drug (LMP744) can kill glioblastoma tumor cells. Objective: To test LMP744 in people with glioblastoma. Eligibility: People aged 18 years or older with glioblastoma that returned after treatment. Design: Participants will be screened. They will have a surgery to remove a small sample of tumor tissue (biopsy) from the brain. This will be done under protocol 03-N-0164. They will stay in the clinic for 1 night. They will also have imaging scans and tests of their heart function. Participants will have a central line installed: A flexible tube will be inserted into a vein in the chest. It will be attached to a port under the skin. This port will be used to draw blood and give medicines without having to insert new needles into a vein. LMP744 will be given through the central line for 5 days in a row. Participants will remain in the clinic for this time. Participants will then have a second surgery to remove as much of their tumor as possible. They will remain in the clinic until they recover from the surgery. Then they will recover at home after surgery. Participants will return to the clinic to receive the study drug for 5 days in a row through the central line, once a month for up to 12 months. Blood tests, heart function tests, and periodic imaging scans will be repeated during these visits. Participants will continue to have telehealth visits every 3 months after they stop taking the drug.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07416188
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: recurrent_disease
- NCT07263438 - Open-label Phase II Clinical Trial to Test the Efficacy of the Combination of Trimipramine and Atezolizumab With Bevacizumab in Patients With Recurrent Glioblastoma (PHASE2, RECRUITING): This is a multicentric phase II open-label clinical trial aiming to assess the efficacy of the combination of trimipramine and atezolizumab with bevacizumab in patients with recurrent glioblastoma. Eligible patients will be assigned to two cohorts depending on whether there is a medical indication for a neurosurgical resection from first recurrent tumor or not. The aim of the cohort 1 (patients without indication for surgery) is to analyze the clinical efficacy of this triple combination in recurrent glioblastoma. 48 patients will be registered. The aim of cohort 2 (patients with indication for surgery) is to confirm the level of trimipramine that can be achieved in the tumor tissue and cerebrospinal fluid collected during surgery. At least 5 patients will be registered. All patients will receive the combination treatment (trimipramine and atezolizumab associated with bevacizumab) for a maximum period of 2 years from registration. The treatment schedule is slightly different for the 2 cohorts because of the neurosurgical resection foreseen for cohort 2 and the requirement to start bevacizumab only after the surgery. After the end of treatment, all patients will be followed up for safety during 90 days from first treatment administration and then up to 3 years from registration.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07263438
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06552260 - A Surgical Window of Opportunity Clinical Trial of Troriluzole in Recurrent IDH Wild-Type Glioblastoma (EARLY_PHASE1, RECRUITING): This research study is studying troriluzole as a possible treatment for recurrent glioblastoma. The name of the study drug involved in this research study is: -Troriluzole (a tripeptide prodrug of riluzole)
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06552260
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05911230 - Advanced Diffusion MRI to Differentiate Tumor Recurrence From Pseudoprogression in Patients With Glioblastoma and Brain Metastases- AiD GLIO Pilot Trial (NA, RECRUITING): This pilot study investigates whether advanced diffusion-weighted MRI (ADW-MRI) can differentiate between true tumor progression (TP) and a pseudoprogression (PsP) in patients with glioblastoma (GBM) or brain metastases.
  Quick read: GBM-specific treatment study for GBM or glioma patients; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05911230
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05629702 - A Randomised Controlled Phase II Trial of Temozolomide With or Without Cannabinoids in Patients With Recurrent Glioblastoma (PHASE2, RECRUITING): ARISTOCRAT is a phase II, multi-centre, double-blind, placebo-controlled, randomised trial to compare the cannabinoid Nabiximols with placebo in patients with recurrent MGMT methylated glioblastoma (GBM) treated with temozolomide (TMZ).
  Quick read: GBM-related treatment study for first-recurrence GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05629702
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 16 (match), kps_min=80 vs 60 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05432518 - Biomarker and Tumor Cell Culture-Driven Pilot Trial for Treatment of Recurrent Glioblastoma (EARLY_PHASE1, RECRUITING): This will be a single-arm open-label prospective pilot feasibility trial recruiting 10 adult patients with recurrent glioblastoma who are assigned to receive the personalized study treatment based on the genetic profile of their recurrent GBM tumor resected at the time of surgery. It will be aimed to gather preliminary information on the study intervention and the feasibility of conducting a full-scale trial.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05432518
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT03596086 - Phase I-II Study Evaluating HSV-tk + Valacyclovir Gene Therapy Combination With Radiotherapy and Chemotherapy for Recurrent Glioblastoma Multiforme (PHASE1, PHASE2, RECRUITING): Study to assess the safety and efficacy of HSV-tk (gene therapy), valacyclovir, radiotherapy and chemotherapy in recurrent glioblastoma multiforme.
  Quick read: GBM-related treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03596086
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT03423628 - A Phase I, Multicenter Study to Assess the Safety, Tolerability, and Pharmacokinetics of Ascending Doses of AZD1390 in Combination With Radiation Therapy in Patients With Glioblastoma Multiforme and Brain Metastases From Solid Tumors (PHASE1, RECRUITING): This study will test an investigational drug called AZD1390 in combination with radiation therapy for the treatment of brain tumors. This is the first time AZD1390 is being given to patients. This study will test safety, tolerability and PK (how the drug is absorbed, distributed and eliminated) of ascending doses of AZD1390 in combination with distinct regimens of radiation therapy
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03423628
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT01269853 - Phase I/II Trial Of Repeated Super-selective Intraarterial Cerebral Infusion Of Bevacizumab (Avastin) for Treatment of Relapsed/Refractory Glioblastoma Multiforme and Anaplastic Astrocytoma. (PHASE1, PHASE2, RECRUITING): The high-grade malignant brain tumors, glioblastoma multiforme (GBM) and anaplastic astrocytoma (AA), comprise the majority of all primary brain tumors in adults. This group of tumors also exhibits the most aggressive behavior, resulting in median overall survival durations of only 9-12 months for GBM, and 3-4 years for AA. Initial therapy consists of either surgical resection, external beam radiation or both. All patients experience a recurrence after first-line therapy, so improvements in both first-line and salvage therapy are critical to enhancing quality-of-life and prolonging survival. It is unknown if currently used intravenous (IV) therapies even cross the blood brain barrier (BBB). The investigators have shown in a previous phase I trial that a single Super-selective Intraarterial Cerebral Infusion (SIACI) of Bevacizumab (up to 15mg/kg) is safe and effective in the treatment of recurrent GBM. Therefore, this phase I/II clinical research trial is an extension of that trial in that the investigators seek to test the hypothesis that repeated dosing of intraarterial Bevacizumab is safe and effective in the treatment of recurrent malignant glioma. By achieving the aims of this study the investigators will also determine if IV therapy with Bevacizumab should be combined with repeated selected intraarterial Bevacizumab to improve progression free and overall survival. The investigators expect that this project will provide important information regarding the utility of repeated SIACI Bevacizumab therapy for malignant glioma, and may alter the way these drugs are delivered to the patients in the near future.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT01269853
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07179328 - Assessment of Safety and Feasibility of Focused Ultrasound Next Generational Dome Helmet Mediated Blood-Brain Barrier Disruption for the Treatment of High-Grade Glioma in Patients Undergoing Standard Chemotherapy (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and feasibility of focused ultrasound (FUS)-mediated blood-brain barrier (BBB) disruption using the Next Generation Dome Helmet (NGDH) in adults with glioblastoma (GBM) undergoing the maintenance phase of the standard "Stupp protocol". Participants will: * Undergo repeated FUS BBB disruption treatments during the maintenance phase of temozolomide (TMZ) chemotherapy. * Receive intravenous ultrasound contrast (DEFINITY®) prior to each FUS session to facilitate targeted BBB disruption. * Undergo serial MRI scans and clinical assessments to evaluate safety and the extent of BBB opening. * Provide blood samples (and tumor tissue if available) for biomarker analysis related to BBB permeability, tumor presence, and treatment response. * Be followed for progression-free survival (PFS) and overall survival (OS) during routine neuro-oncology visits until end of life.
  Quick read: GBM-related treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07179328
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04523688 - Vaccination With Autologous Dendritic Cells Loaded With Autologous Tumour Homogenate in Glioblastoma: a Phase II Study (PHASE2, RECRUITING): Single arm, monocentric trial to assess the safety and the progression-free survival related to the combined treatment of dendritic cell vaccine loaded with autologous tumor homogenate and temozolomide in patients operated for glioblastoma and then treated with standard radiochemotherapy (according to Stupp regimen).
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04523688
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03861299 - The SAFE-Trial: Safe Surgery for Glioblastoma Multiforme: Awake Craniotomy Versus Surgery Under General Anesthesia. A Multicenter Prospective Randomised Controlled Study (NA, RECRUITING): The trial is designed as a multicenter randomized controlled study. 246 patients with presumed Glioblastoma Multiforme in eloquent areas on diagnostic MRI will be selected by the neurosurgeons according the eligibility criteria (see under). After written informed consent is obtained, the patient will be randomized for an awake craniotomy (AC) (+/-123 patients) or craniotomy under general anesthesia (GA) (+/-123 patients), with 1:1 allocation ratio. Under GA the amount of resection of the tumour has to be performed within safe margins as judged by the surgeon during surgery. The second group will be operated with an awake craniotomy procedure where the resection boundaries for motor or language functions will be identified by direct cortical and subcortical stimulation. After surgery, the diagnosis of GBM will have to be histologically confirmed. If GBM is not histologically confirmed, patients will be considered off-study and withdrawn from the study. These patients will be followed-up according to standard practice. Thereafter, patients will receive the standard treatment with concomitant Temozolomide and radiation therapy and standard follow up. Total duration of the study is 5 years. Patient inclusion is expected to take 4 years. Follow-up is 1 year after surgery. Statistical analysis, cost benefit analysis and article writing will take 3 months.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03861299
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 80 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07422363 - A Phase I Trial of 225Ac-anti-CD33 and PD1-Inhibitor in Recurrent Glioblastoma (PHASE1, NOT_YET_RECRUITING): This phase I trial studies the side effects and best dose of Actimab-A when given together with cemiplimab (REGN2810) in treating patients with glioblastomas that have come back after a period of improvement (recurrent). Actimab-A consists of the monoclonal antibody lintuzumab combined with the radioactive drug actinium Ac 225. Lintuzumab specifically binds to the cell surface antigen CD33 which is found on the glioblastoma cells and delivers the actinium Ac 225. This may allow the glioblastoma to be found and treated by Actimab-A. Immunotherapy with monoclonal antibodies, such as cemiplimab (REGN2810), may help the body's immune system attack the cancer, and may interfere with the ability of tumor cells to grow and spread. Giving Actimab-A with cemiplimab (REGN2810) may be safe, tolerable and/or effective in treating recurrent glioblastoma.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07422363
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT07385846 - Pilot Study for the Use of Navigated Focused Ultrasound and Pembrolizumab in the Treatment of Recurrent WHO Grade 4 IDH-Wildtype Glioblastoma With Mismatch Repair Deficiency: A Phase I Clinical Trial (PHASE1, NOT_YET_RECRUITING): Navigated Focused Ultrasound and Pembrolizumab in the Treatment of Recurrent WHO Grade 4 IDH-Wildtype Glioblastoma with Mismatch Repair Deficiency.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07385846
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07089641 - A Phase Ib Open Label Clinical Trial to Evaluate the Safety and Efficacy of ERAS-801 in Surgically Accessible Recurrent Glioblastoma Patients With EGFR Amplification or Mutation (ERAS801-SARG) (PHASE1, RECRUITING): This phase Ib trial tests the safety and side effects of ERAS-801 in treating patients with isocitrate dehydrogenase (IDH) wildtype, epidermal growth factor receptor (EGFR) amplified or mutated grade IV glioblastoma or astrocytoma that can be removed by surgery (resectable) and that is growing, spreading, or getting worse (progressive) or that has come back after a period of improvement (recurrent). Glioblastoma is the most common brain cancer in adults and survival rates remain poor despite treatment including surgery, radiation and chemotherapy. EGFR is a protein found on the surface of some cells, to which epidermal growth factor binds, causing the cells to divide. It is found at abnormally high levels on the surface of many types of tumor cells, so these cells may divide excessively in the presence of epidermal growth factor. ERAS-801, an EGFR inhibitor that can penetrate the central nervous system, binds to the tumor cells that express EGFR and may help shrink or slow the growth of the tumor cells.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07089641
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06934889 - Phase Ib Trial of ABBV-637 or ABBV-155 in Combination With ERAS-801 for Glioblastoma With Amplification of the Epidermal Growth Factor Receptor (PHASE1, RECRUITING): The researchers are doing this study to find out whether the drugs ABBV-637 and ABBV-155 are safe treatments that cause few or mild side effects when given alone or in combination with ERAS-801 in people with recurrent GBM.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06934889
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06860594 - A Phase I Trial Combining Triapine With Radiation Therapy for Recurrent Glioblastoma or Astrocytoma (PHASE1, RECRUITING): This phase I trial tests the safety, side effects, and best dose of triapine in combination with radiation therapy in treating patients with glioblastoma or astrocytoma that has come back after a period of improvement (recurrent). Triapine may stop the growth of tumor cells by blocking some of the enzymes needed for cell growth. Radiation therapy uses high energy x-rays, particles, or radioactive seeds to kill cancer cells and shrink tumors. Giving triapine in combination with radiation therapy may be safe, tolerable, and/or effective in treating patients with recurrent glioblastoma or astrocytoma.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06860594
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06815029 - A Phase 1 Trial to Evaluate the Safety of IL13Rα2-Targeting Chimeric Antigen Receptor (CAR) T Cells With CRISPR Knockout of TGFβR2 in Patients With Recurrent or Progressive High-Grade Glioma (HGG) (PHASE1, RECRUITING): This phase I trial tests the safety, side effects and best dose of TGFβR2KO/IL13Rα2 chimeric antigen receptor (CAR) T-cells given within the skull (intracranial) in treating patients with glioblastoma or IDH-mutant grade 3 or 4 astrocytoma that has come back after a period of improvement (recurrent) or that is growing, spreading, or getting worse (progressive). CAR T-cell therapy is a type of treatment in which a patient's T cells (a type of immune system cell) are changed in the laboratory so they will attack tumor cells. T cells are taken from a patient's blood. When the cells are taken from the patient's own blood, it is known as autologous. Then the gene for special receptors that bind to a certain proteins on the patient's tumor cells are added to the T cells in the laboratory. The special receptors are called CAR. Large numbers of the CAR T cells are grown in the laboratory and given to the patient by infusion for treatment of certain tumors. Giving TGFβR2KO/IL13Rα2 CAR T cells may be safe, tolerable, and/or effective in treating patients with recurrent or progressive glioblastoma or grade 3 or 4 IDH-mutant astrocytoma.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06815029
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06496971 - A Prospective, Randomized, Standard of Care Controlled, Parallel, Open-Label, Multicenter Pivotal Study to Evaluate the Efficacy and Safety of Avastin® in Combination With NaviFUS System Compared With Avastin® Alone for the Treatment of Recurrent Glioblastoma Multiforme (rGBM) (PHASE3, RECRUITING): This will be a prospective, randomized, standard of care (SoC) controlled, parallel, open-label, multicenter pivotal study to investigate the efficacy and safety of Bevacizumab (BEV) in combination with or without microbubble (MB)-mediated FUS in patients with recurrent GBM. BEV represents the physician's best choice for the standard of care in rGBM after previous treatment with surgery (if appropriate), standard radiotherapy with temozolomide chemotherapy, and with adjuvant temozolomide.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06496971
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs True (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06344130 - A Phase I Hypofractionation Trial of Re-irradiation in Good Prognosis Recurrent Glioblastoma (PHASE1, RECRUITING): Background: Glioblastoma (GBM) is a cancer of the brain. Current survival rates for people with GBM are poor; survival ranges from 5.2 months to 39 months. Most tumors come back within months or years after treatment, and when they do, they are worse: Overall survival drops to less than 10 months. No standard treatment exists for people whose GBM has returned after radiation therapy. Objective: To find a safe schedule for using radiation to treat GBM tumors that returned after initial radiation treatment. Eligibility: People aged 18 years and older with grade 4 GBM that returned after initial radiation treatment. Design: Participants will be screened. They will have a physical exam with blood tests. A sample of tumor tissue may be collected. Participants will undergo re-irradiation planning: They will wear a plastic mask over their head during imaging scans. These scans will pinpoint the exact location of the tumor. This spot will be the target of the radiation treatments. Participants will undergo radiation treatment 4 times per week. Some people will have this treatment for 3 weeks, some for 2 weeks, and some for 1 week. Blood tests and other exams will be repeated at each visit. Participants will complete questionnaires about their physical and mental health. They will answer these questions before starting radiation treatment; once a week during treatment; and at intervals for up to 3 years after treatment ends. Participants will have follow-up visits 1 month after treatment and then every 2 months for 6 months. Follow-up clinic visits will continue up to 3 years. Follow-ups by phone or email will continue an additional 2 years.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06344130
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: prior_radiation, Matched inclusion factor: recurrent_disease
- NCT06329570 - A Prospective, Open-Label, Single-Arm Pilot Study to Evaluate the Safety and Efficacy of Bevacizumab in Combination With NaviFUS System for the Treatment of Recurrent Glioblastoma Multiforme (rGBM) (PHASE1, PHASE2, NOT_YET_RECRUITING): This will be a prospective, open-label, single-arm pilot study to investigate the safety and efficacy of Bevacizumab (BEV) in combination with microbubble (MB)-mediated FUS in patients with recurrent GBM. BEV represents the physician's best choice for the standard of care (SoC) in rGBM after previous treatment with surgery (if appropriate), standard radiotherapy with temozolomide chemotherapy, and with adjuvant temozolomide.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06329570
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs True (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT06058988 - Window of Opportunity Assessment of [Fam-]Trastuzumab DERuxtecan-nxki (T-DXd) Brain Tumor Penetration and Efficacy (WOnDER-BT) (PHASE2, RECRUITING): The purpose of this study is to find out how much tratuzumab deruxtecan (T-DXd) can penetrate the tumor when injected into the body, and whether T-DXd may be an effective treatment for brain cancers that express the HER2 protein.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06058988
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05979064 - Laparoscopically Harvested Omental Tissue Autograft to Bypass the Blood Brain Barrier (BBB) in Human Recurrent Glioblastoma Multiforme (rGBM) (NA, RECRUITING): This single center, single arm, open-label, phase I study will assess the safety of laparoscopically harvested autologous omentum, implanted into the resection cavity of recurrent glioblastoma multiforme (GBM) patients.
  Quick read: GBM-related treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05979064
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05789394 - Phase 1, Dose Escalation, Non-Randomized, Open Label, Clinical Trial Evaluating the Safety and Preliminary Efficacy of Allogenic Adipose-Derived Mesenchymal Stem Cells (AMSCs) for Recurrent Glioblastoma (PHASE1, RECRUITING): This phase I trial tests the safety, side effects, and best dose of allogenic adipose-derived mesenchymal stem cells (AMSCs) in treating patients with glioblastoma or astrocytoma that has come back (recurrent) who are undergoing brain surgery (craniotomy). Glioblastoma is the most common and most aggressive form of primary and malignant tumor of the brain. Currently, the standard of care for this disease includes surgical resection, followed by radiation with chemotherapy and tumor treating fields. Despite this aggressive therapy, the survival after finishing treatment remains low and the disease often reoccurs. Unfortunately, the available therapy options for recurrent glioblastoma are minimal and do not have a great effect on survival. AMSCs are found in body fat and when separated from the fat, are delivered into the surgical cavity at the time of surgery. When in direct contact with tumor cells, AMSCs affect tumor growth, residual tumor cell death, and chemotherapy resistance. The use of AMSCs delivered locally into the surgical cavity of recurrent glioblastoma during a craniotomy could improve the long-term outcomes of these patients by decreasing the progression rate and invasiveness of malignant cells.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05789394
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05698524 - A Phase I Study of Metronomic Temozolomide With Abexinostat (PCI-24781) for Patients With Recurrent High Grade Glioma (PHASE1, RECRUITING): Glioblastoma (GBM), WHO grade IV glioma, represents the majority of adult malignant primary brain tumors, with an incidence of 2-3 per 100,000 person-years. The survival for GBM has increased in the last decade but is still low with a median survival of 15-18 months. Recurrence after initial standard therapy, radiation therapy and chemotherapy with temozolomide, few options are available. Even with further therapy, median progression free survival at 6 months after first relapse (PFS-6) is only 15%. Similarly, anaplastic astrocytoma and anaplastic oligodendroglioma, grade III gliomas, once recurrent after radiation therapy and first-line chemotherapy, have identical therapeutic options and poor outcomes with PFS-6 of 31%. Temozolomide (TMZ) has a favorable side effect profile and is available orally, however, cytotoxicity occurs. Metronomic temozolomide at low doses on a continuous schedule, have demonstrated better survival in studies. This study will determine the recommended dose and the side effects of PCI-24781/Abexinostat with metronomic temozolomide.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05698524
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05465954 - Efficacy and Safety Study of Neoadjuvant Efineptakin Alfa (NT-I7) and Pembrolizumab in Recurrent Glioblastoma (PHASE2, RECRUITING): This phase II trial tests the safety and side effects of efineptakin alfa and pembrolizumab in treating patients with glioblastoma that has come back (recurrent). Efineptakin alfa is an immunotherapy drug that works by helping the immune system fight tumor cells. Immunotherapy with monoclonal antibodies, such as pembrolizumab, may help the body's immune system attack the cancer, and may interfere with the ability of tumor cells to grow and spread. Giving efineptakin alfa and pembrolizumab may kill more tumor cells in patients with recurrent glioblastoma.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05465954
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT05095441 - A Phase 1 Open-Label Study of Genetically Engineered Oncolytic HSV-1 (C5252) Expressing IL-12 and Anti-PD-1 Antibody in Patients With Recurrent or Progressive Glioblastoma (PHASE1, NOT_YET_RECRUITING): This is a Phase 1 open label, first in human study of C5252 monotherapy designed to determine the safety and tolerability of a single intratumoral (IT) injection of C5252 in patients with recurrent or progressive glioblastoma (GBM).
  Quick read: GBM-related treatment study for recurrent GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05095441
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05039281 - Phase I/II Study to Evaluate the Safety and Clinical Efficacy of Atezolizumab (Anti-PD-L1) in Combination With Cabozantinib in Patients With Recurrent Glioblastoma (rGBM) (PHASE1, PHASE2, RECRUITING): This phase I/II trial tests the safety and side effects of atezolizumab in combination with cabozantinib and whether they work to shrink tumors in patients with glioblastoma that has come back (recurrent). Immunotherapy with monoclonal antibodies, such as atezolizumab, may help the body's immune system attack the cancer, and may interfere with the ability of tumor cells to grow and spread. Cabozantinib may stop the growth of tumor cells by blocking some of the enzymes needed for cell growth. Giving atezolizumab and cabozantinib may help control the disease in patients with recurrent glioblastoma.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05039281
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT04991870 - A Phase I Clinical Trial With a Window-of-Opportunity Component of Engineered NK Cells Containing Deleted TGF-ßR2 and NR3C1 in Recurrent Grade 4 Astrocytoma (Glioblastoma) (PHASE1, RECRUITING): This phase I trial is to find out the best dose, possible benefits and/or side effects of engineered natural killer (NK) cells containing deleted TGF-betaR2 and NR3C1 (cord blood \[CB\]-NK-TGF-betaR2-/NR3C1-) in treating patients with glioblastoma that has come back (recurrent). CB-NK-TGF-betaR2-/NR3C1- cells are genetically changed immune cells that may help to control the disease.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04991870
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04541082 - A First-in-human Phase I Single-agent Dose-escalation, Food Effect and Dose Expansion Study of Oral ONC206 in Recurrent and Rare Primary Central Nervous System Neoplasms (PHASE1, RECRUITING): The primary objective of this Phase 1, open-label, dose-escalation, and exploratory study is to evaluate the safety and tolerability profile (establish the maximum-tolerated dose) and evaluate the occurrence of dose-limiting toxicities (DLTs) following single weekly or multiple-day weekly dose regimens of single-agent, oral ONC206 in patients with recurrent, primary central nervous system (CNS) neoplasms.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04541082
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04181684 - Pilot Study of Laser Interstitial Thermal Therapy Followed By Hypofractionated Radiation Therapy for Treatment of Recurrent Gliomas. (NA, RECRUITING): The purpose of this study is to evaluate the treatment regimen of using Laser Interstitial Thermal Therapy (LITT) and Hypo-fractionated Radiation Therapy to treat patients with recurrent gliomas.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04181684
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 22 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT03911388 - Phase 1 Trial of Engineered HSV G207 in Children With Recurrent or Refractory Cerebellar Brain Tumors (PHASE1, RECRUITING): This study is a clinical trial to determine the safety of inoculating G207 (an experimental virus therapy) into a recurrent or refractory cerebellar brain tumor. The safety of combining G207 with a single low dose of radiation, designed to enhance virus replication, tumor cell killing, and an anti-tumor immune response, will also be tested. Funding Source- FDA OOPD
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03911388
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 36 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT02800486 - Phase II Trial of Super Selective Intra-arterial Repeated Infusion of Cetuximab (Erbitux) With Reirradiation for Treatment of Relapsed/Refractory Glioblastoma Multiforme, Anaplastic Astrocytoma, and Anaplastic Oligoastrocytoma (PHASE2, RECRUITING): Primary brain tumors are typically treated by surgery, radiation therapy and chemotherapy, either individually or in combination. Present therapies are inadequate, as evidenced by the low 5-year survival rate for brain cancer patients, with median survival at approximately 12 months. Glioma is the most common form of primary brain cancer, afflicting approximately 7,000 patients in the United States each year. These highly malignant cancers remain a significant unmet clinical need in oncology. GBM often has a high expression of EFGR (Epidermal Growth Factor Receptor), which is associated with poor prognosis. Several methods of inhibiting this receptor have been tested, including monoclonal antibodies, vaccines, and tyrosine kinase inhibitors. The investigators hypothesize that in patients with recurring GBM, intracranial superselective intra-arterial infusion of Cetuximab (CTX), at a dose of 250mg/m2 in conjunction with hypofractionated radiation, will be safe and efficacious and prevent tumor progression in patients with recurrent, residual GBM.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02800486
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07100730 - A Global, Multicenter, Prospective, Controlled, Open-Label Pivotal Study of Iodofalan (131I) Solution for Injection (TLX101-Tx) Plus Lomustine Versus Lomustine Alone in Patients With Radiographically Confirmed Recurrent Glioblastoma at First Recurrence (IPAX BrIGHT [IPAX-3]) (PHASE3, RECRUITING): This global clinical trial which evaluates the efficacy and safety of TLX101-Tx, an investigational radiopharmaceutical therapy, in combination with lomustine versus lomustine alone in adult patients with first recurrence of glioblastoma. TLX101-Tx delivers targeted radiation to glioblastoma cells. The trial is conducted in two parts: Part 1 assesses safety and radiation dosing; Part 2 is a randomized comparison of the combination therapy against standard care.
  Quick read: GBM-related treatment study for first-recurrence GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07100730
  Review priority: 143
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT06975332 - Medical Experiment - Assessment of Efficacy & Safety of Local, Targeted Therapy With Neuropeptide Labelled With Alpha Emitter [225Ac]Ac-DOTA-SP (TAT) as Supplementary Therapy in Glioma (WHO G3-G4) Progression (NA, RECRUITING): Brain tumors account for 1.35% of all cancers and cause 2.2% of cancer-related deaths. Gliomas are the most common type, comprising 40-90% of central nervous system tumors in different age groups. The incidence of malignant gliomas is approximately 0.5-2 per 100,000 people annually. Standard treatments include surgical resection, radiotherapy, and chemotherapy, yet overall survival remains low, typically 1-3 years post-diagnosis. The study highlights the pressing need for novel treatment strategies, particularly given the infiltrative nature of gliomas and the potential for targeted therapies using neuropeptides. The aim of this study is to assess the efficacy and safety of local targeted therapy with \[225Ac\]Ac-DOTA-SP in recurrent glioblastoma. It is an interventional study without a control group, initiated by the researcher. Patients included are aged 18-80 with recurrent WHO G3-G4 glioma post-first-line treatment, not requiring immediate surgery and meeting specific MRI progression criteria. Patients will receive a maximum of six cycles of \[225Ac\]Ac-DOTA-SP, involving pre-treatment assessments, local administration of the agent after ensuring catheter patency, and continuous monitoring. Blood tests and neurological evaluations will be performed regularly. Outcome will be assessed by measuring overall survival (OS) and progression-free survival (PFS). The study anticipates improvements in both OS and PFS when compared to current treatments, contributing to critical insights into targeted alpha therapy's effectiveness in glioblastoma. Treatment with \[225Ac\]Ac-DOTA-SP previously indicated few significant side effects, primarily transient issues like seizures. Patients will be closely monitored throughout the study to identify any adverse effects promptly. The estimated study duration is three years, with biological material collected for histopathological and genetic analysis during surgical reoperation. Data will be anonymized to protect patient confidentiality, stored securely, and made available only for the scope of the study. Led by Prof. Przemysław Kunert, the research team includes multiple co-investigators from neurosurgery and nuclear medicine departments.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06975332
  Review priority: 143
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07459101 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-4 (UNITED-4): Prospective Evaluation of FLAIR-Guided Clinical Target Volume Reduction (NA, RECRUITING): This study builds on the results of prior studies (UNITED and UNITED-3). The goal of UNITED-4 is to test whether an adaptive radiation therapy (RT) therapy approach ('dose painting'), with reduced margins, impacts approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive RT approach with reduced margins compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life * Longitudinal imaging features
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07459101
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07003542 - Targeting Macrophage Migration Inhibitory Factor: A Phase 2 and Pharmacodynamic Study of Sitagliptin in Patients With Progressive Grade 4 Gliomas (PHASE2, RECRUITING): The purpose of this study is to evaluate whether treating glioblastoma patients with sitagliptin can improve immune response against the tumor by targeting specific immune cells called myeloid-derived suppressor cells (MDSCs) that suppress your body's natural immune response against cancer. Sitagliptin is an investigational drug for this condition that works by inhibiting an enzyme called dipeptidyl peptidase 4 (DPP-4), which MDSCs rely on to enter the brain and function. While sitagliptin is FDA-approved for diabetes treatment, its use in glioblastoma is investigational (experimental).
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07003542
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low
- NCT06418113 - Neoadjuvant Radio-chemotherapy Safety Pilot Study in Patients With Glioblastoma (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and efficacy of neoadjuvant radiochemotherapy in the surgical resection of glioblastoma (GBM). The main questions it aims to answer are: * What is the safety profile of neoadjuvant radiochemotherapy in terms of neurological deficit, radionecrosis, edema, headache, wound dehiscence, infection, and cerebrospinal fluid fistula? * What is the efficacy of neoadjuvant radiochemotherapy in terms of progression-free survival, overall survival, cognitive function, and quality of life? Participants will undergo the following tasks and treatments: * Stereotactic biopsy and diagnosis confirmation. * Conformal hypofractionated stereotactic radiotherapy with concurrent temozolomide. * Supramarginal resection guided by 5-ALA under intraoperative neurophysiological monitoring. * Maintenance temozolomide administration for 6 months. Researchers will compare the group receiving neoadjuvant radiochemotherapy to the control group following the standard Stupp protocol to assess safety and efficacy outcomes.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06418113
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06388733 - A Phase 3, Open-label, Randomized 2-arm Study Comparing the Clinical Efficacy and Safety of Niraparib With Temozolomide in Adult Participants With Newly-diagnosed, MGMT Unmethylated Glioblastoma (PHASE3, RECRUITING): The goal of this Phase 3 clinical trial is to compare the efficacy of niraparib versus temozolomide (TMZ) in adult participants with newly-diagnosed, MGMT unmethylated glioblastoma multiforme (GBM). The main question it aims to answer is: Does niraparib improve overall survival (OS) compared to TMZ? Participants will be randomly assigned to one of two treatment arms: niraparib or TMZ. * study drug (Niraparib) or * comparator drug (Temozolomide - which is the standard approved treatment for MGMT unmethylated glioblastoma). The study medication will be taken daily while receiving standard of care radiation therapy (RT) for 6-7 weeks. Participants may continue to take the niraparib or TMZ adjuvantly as long as the cancer does not get worse or completion of 6 cycles of treatment (TMZ). A total of 450 participants will be enrolled in the study. Participants' tasks will include: * Complete study visits as scheduled * Complete a diary to record study medication
  Quick read: GBM-related treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06388733
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low
- NCT06356883 - A Randomized Phase II Study on Intraarterial Carboplatin Combined With Caelyx Compared to Intraarterial Carboplatin Combined With Etoposide Phosphate for Progressing Glioblastoma at First or Second Relapse (PHASE2, RECRUITING): The standard of care for glioblastoma (GBM) treatment involves maximal resection followed by concomitant radiotherapy and temozolomide. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is inevitable. At relapse, there is no consensus regarding the optimal therapeutic strategy. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which impedes drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, can produce responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival (OS) 23 months. How can the OS and PFS be improved? By combining chemotherapeutic agents with different mechanisms of action. Study design: In this phase II trial, treatment will be offered at relapse. Surgery will be performed for cytoreduction if it is warranted, followed with a combination IA carboplatin + IA Cealyx (liposomal doxorubicin) or IA carboplatin + IA etoposide phosphate. Toxicity will be assessed according to the NCIC common toxicity criteria. Treatment will consist in either IA carboplatin (400 mg/m\^2) + IA Cealyx (30 mg/m\^2) or IA carboplatin (400 mg/m\^2) + IA etoposide phosphate (400 mg/m\^2) every 4-6 weeks (1 cycle). Up to twelve cycles will be offered. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. Primary outcome will PFS and tumor response. Secondary outcome will include median OS, toxicity, quality of life (QOL), neurocognition (NC). Putting together these data will allow to correlate clinical and radiological response to QOL and NC.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06356883
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06186401 - Phase 1 Study of Autologous Anti-EGFRvIII synNotch Receptor Induced Anti-EphA2/IL-13R alpha2 CAR (E-SYNC) T Cells in Adult Participants With EGFRvIII+ Glioblastoma (PHASE1, RECRUITING): This phase I trial tests the safety, side effects, and best dose of E-SYNC chimeric antigen receptor (CAR) T cells after lymphodepleting chemotherapy in treating patients with EGFRvIII positive (+) glioblastoma. Chimeric antigen receptor (CAR) T-cell therapy is a type of treatment in which a patient's T cells (a type of immune system cell) are changed in the laboratory so the CAR T cells will attack cancer cells. T cells are taken from a patient's blood. Then the gene for a special receptor that binds to a certain protein on the patient's cancer cells is added to the T cells in the laboratory. The special receptor is called a chimeric antigen receptor. Large numbers of the CAR T cells are grown in the laboratory and given to the patient by infusion for treatment of certain cancers. Lymphodepleting chemotherapy with cyclophosphamide and fludarabine before treatment with CAR T cells may make the CAR T cells more effective.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06186401
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05106296 - Repurposing Ibrutinib for Chemo-Immunotherapy in a Phase 1b Study of Ibrutinib With Indoximod Plus Metronomic Cyclophosphamide and Etoposide for Pediatric Patients With Brain Cancer (PHASE1, RECRUITING): Recent lab-based discoveries suggest that IDO (indoleamine 2,3-dioxygenase) and BTK (Bruton's tyrosine Kinase) form a closely linked metabolic checkpoint in tumor-associated antigen-presenting cells. The central clinical hypothesis for the GCC2020 study is that combining ibrutinib (BTK-inhibitor) with indoximod (IDO-inhibitor) during chemotherapy will synergistically enhance anti-tumor immune responses, leading to improvement in clinical response with manageable overlapping toxicity. The GCC2020 trial is a prospective open-label phase 1 trial to determine the best safe dose of the BTK-inhibitor ibrutinib to use in combination with previously studied chemo-immunotherapy regimens comprised of the investigational IDO-inhibitor indoximod plus oral palliative chemotherapy for participants, age 6 to 25 years, with relapsed or refractory primary brain cancer. Those previously treated with indoximod-based therapy may be eligible, including prior treatment via the phase 2 indoximod study (GCC1949, NCT04049669), the now closed phase 1 study (NLG2105, NCT02502708), or any expanded access (compassionate use) protocols. Ibrutinib will be combined with either indoximod plus oral cyclophosphamide and etoposide (Regimen A) or indoximod plus oral temozolomide (Regimen B). No cross-over between these two regimens will be allowed. Dose-escalation cohorts will determine the best safe dose of ibrutinib for each of these regimens. This will be followed by expansion cohorts, using ibrutinib at the best safe dose for each regimen, to allow assessment of preliminary evidence of efficacy.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05106296
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04678648 - A Phase Ia/Ib, Open Label, Multi-center, Non-randomized Dose Escalation and Dose Expansion Study of RSC-1255 Alone or in Combination With Hydroxychloroquine in Patients With Advanced Solid Tumor Malignancies (PHASE1, RECRUITING): RSC-101 is a Phase 1a/1b clinical trial of RSC-1255 in adult study participants with advanced solid tumor malignancies who are intolerant of existing therapies known to provide clinical benefit, have disease that has progressed after standard therapy, or have previously failed other therapies. The study has two phases. The purpose of Phase 1a (Dose Escalation) is to confirm the appropriate treatment dose and Phase 1b (Dose Expansion) is to characterize the safety and efficacy of RSC-1255.
  Quick read: GBM-related treatment study for GBM or glioma patients; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04678648
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04623931 - Phase II Trial of Treatment Intensification for IDH Wildtype, Non-Histological Glioblastoma, Gliomas (IDH Wildtype Lower Grade Glioma Treatment Intensification) (PHASE2, RECRUITING): This phase II trial studies how well temozolomide and radiation therapy work in treating patients with IDH wildtype historically lower grade gliomas or non-histological molecular glioblastomas. Radiation therapy uses high-energy x-rays to kill tumor cells and shrink tumors. Giving chemotherapy with radiation therapy may kill more tumor cells. Drugs used in chemotherapy, such as temozolomide, work in different ways to stop the growth of tumor cells, either by killing the cells, by stopping them from dividing, or by stopping them from spreading. The goal of this clinical research study is to compare receiving new radiation therapy doses and volumes to the prior standard treatment for patients with historically grade II or grade III IDH wild-type gliomas, which may now be referred to as IDH wildtype molecular glioblastomas at some institutions. Receiving temozolomide in combination with radiation therapy may also help to control the disease.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04623931
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03672721 - A Phase II Study in Relapsing Glioblastoma of Intraarterial Concurrent Chemoradiation Therapy Using IA Carboplatin (PHASE1, PHASE2, RECRUITING): Treatment of glioblastoma involves an optimal surgery, followed by a combination of radiation and temozolomide chemotherapy. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is the norm. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which limits drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, the investigators have observed responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival 23 months. How can this be improved? By coupling radiation with a chemotherapeutic which is also a potent radiosensitizer such as carboplatin. Study design: In this phase I/II trial, patients will be treated at recurrence; a surgery will be performed for cytoreduction and to obtain tumor sample, followed with a combination of re-irradiation and IA carboplatin chemotherapy. A careful escalation scheme from 1.5Gy/fraction up to 3.5Gy/fraction will allow the investigators to determine the optimal re-irradiation dose (10 fractions of radiation over 2 weeks). Toxicity will be assessed according to the NCIC common toxicity criteria. Combined with radiation, patients will receive 2 treatments of IA carboplatin, 400 mg/m2, 4 hours prior to the first and the sixth radiation fraction. IA treatments will then be continued on a monthly basis, up to a total of 12 months, or until progression. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. The investigators will also acquire a sequence that enables the measurement of cerebral blood flow, cerebral blood volume and blood vessel permeability that are all relevant to understand the delivery of therapeutics to the CNS. Primary outcome will be OS and PFS. Secondary outcome will be QOL, neurocognition, and carboplatin delivery. In vitro intracellular carboplatin accumulation: Tumor samples from re-operation will be be analyzed for intracellular Pt concentration by ICP-MS. The amount of Pt bound to DNA will be measured. The level of apoptosis will be determined for each of the sample. Putting together these data will allow to correlate clinical and radiological response to QOL, NC (MOCA), and to delivery surrogates for the IA infusion and intracellular penetration of carboplatin.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03672721
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06623565 - Multimodal Image-guided Resection of IDH Wildtype Glioblastoma and Grade IV IDH-mutant Astrocytoma (NA, RECRUITING): Rationale: Patients with IDH-wildtype glioblastoma or grade IV IDH-mutant astrocytoma have a very poor prognosis despite standard treatment consisting of surgery, radiotherapy, and chemotherapy. Diffuse infiltration of the brain by the tumor is thought to be one of the main causes of this therapy-resistance. In order to improve the surgical treatment, tumor regions with lower infiltration percentages need to be identified and resected during surgery, a so-called supramarginal resection. Currently, pre-operative T1 contrast enhanced weighted (T1c) MRI is used to identify the tumor for resection. We recently found the combination of apparent diffusion coefficient MRI and O-(2-\[ 18F\]fluoroethyl-)-L-tyrosine positron emission tomography (ADC/FET) to be significantly more accurate than T1c MRI alone in the detection of tumor infiltration. This makes ADC/FET a suitable candidate to guide supramarginal resection. Since FET PET is not as accessible and widely available as MRI, identification of an MRI based alternative could result in a more widespread implementation. Amide proton transfer chemical exchange saturation transfer (APT-CEST) MRI is a novel potential alternative for FET PET, since both measures are related to protein content. Objective: In this project we aim to develop a safe and effective technique for ADC/FET guided resection of IDH-wildtype glioblastoma and grade IV IDH-mutant astrocytoma. The safety concerns neurological deficits and time to start of adjuvant therapy, while the effectiveness is aimed at the extent of resection. Our secondary aim is to evaluate the diagnostic accuracy of APT-CEST MRI and to assess whether APT-CEST MRI can serve as an alternative for FET PET for the detection of tumor infiltration. Study design: prospective observational intervention study Study population: 30 patients with clinical and radiological diagnosis of an untreated high grade glioma (suspected for glioblastoma (IDH wildtype) or grade IV astrocytoma (IDH mutant)), who are eligible for a supramarginal surgical resection and adjuvant treatment according two neurosurgeons in consensus and who are in relatively good condition (Karnofsky Performance Score (KPS) ≥70). Intervention (if applicable): supramarginal ADC/FET-guided resection. To make sure that the standard treatment is always guaranteed, T1c MRI abnormalities will be included in the surgical target. Main study parameters/endpoints: the main study endpoint is the optimization of ADC/FET-guided resection. Volumetric and percentual extent of resection, as measured with MRI and PET imaging, combined with surgery-induced morbidity will be used as outcome parameters. The secondary study parameters will be the histopathology-based diagnostic accuracy of APT-CEST MRI in comparison with FET PET, cognitive performance over time and progression free survival. Nature and extent of the burden and risks associated with participation, benefit and group relatedness: participants will undergo pre- and postoperative MRI scanning. This is also part of regular clinical care, except there are additional MRI sequences including APT CEST in the pre-operative and pre-radiotherapy MRI. There are no risks associated with MRI acquisition after MRI safety screening. Participants will furthermore undergo a pre- and postoperative FET PET. The risks associated with PET scanning are limited, and the radiation burden will remain below 10 mSv (ICRP62 category intermediate risk (level IIb)). During surgery, biopsies are performed from areas that will be resected, so these biopsies will not introduce any extra risk. A potential benefit is the possibility of the removal of more tumor tissue. A potential risk is the additional removal of healthy brain tissue with the risk of neurological damage, which is controlled by pre- and intraoperative techniques such as visualization of white matter tracts and mapping (both asleep and awake) of critical functions such as language and control of strength.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06623565
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05990556 - Research on the Safety and Efficacy of Blocking Dural Blood Supply in Glioblastoma Patients (NA, RECRUITING): Glioblastoma is the most common primary malignancy of the central nervous system with a very poor prognosis. Most of the immunotherapies that have made significant breakthroughs in the treatment of other tumors in recent years are unsatisfactory in the application of glioblastoma, which is mainly inseparable from the highly inhibitory immune microenvironment formed by the latter. Therefore, how to change this "immune desert" and better activate immune effector cells to play an anti-tumor effect is currently a hot spot in glioma immune research. In recent years, there has been continuous research support that the myeloid cells of the central nervous system are partly derived from the bone marrow of the skull, and there is a special channel connection between the skull and the dura mater, through which immune cells can be transported. This suggests that some of the tumor-associated macrophages recruited in the glioblastoma microenvironment may be passed through the dura mater. In previous animal experiments, we blocked the main blood supply to the dura mater by ligating the bilateral external carotid arteries of mice, cutting off the potential supply of dura mater to suppressor myeloid cells in the lesion. The results showed that after ligation of bilateral external carotid arteries, the survival period of tumor-forming mice was significantly prolonged and the prognosis was improved. The proportion of myeloid cells in the tumor microenvironment of mice decreased significantly, and the expression of tumor suppressor molecules such as arginase Arg1 decreased, indicating that the improvement of mouse prognosis was closely related to the proportion and phenotypic changes of myeloid cells after dural blood supply blockade. The meningeal lymphatic system of the human central nervous system has been shown to be an important part of the immune system, while the external carotid artery system, the main source of blood supply to the dura, carries abundant immune cells that ooze out to the dura mater through the endothelial window hole of the dural blood vessel, which is an important source of dural immune cells. In the glioblastoma immune microenvironment, the source of immune cells includes dural branches from the external carotid artery system in addition to branches of the internal carotid artery system. Therefore, for patients diagnosed with glioblastoma, this study involves embolization of the dural branch of the external carotid artery system (bilateral middle meningeal artery) to block the dural blood supply before craniotomy. At the same time, microsurgery under multimodal image navigation was used to remove the tumor. It is expected to be effective in reducing the proportion of myeloid suppressor cells in the tumor microenvironment, slowing the growth rate of residual tumor cells, and prolonging the tumor-free progression and survival of patients.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05990556
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03958240 - Deciphering Mechanisms Underlying Cancer Immunogenicity (NA, RECRUITING): This trial is a translational, open-label, multicentric, prospective cohort study of 1100 patients aiming to describe the PD-1 (programmed death) expression in T cells (T lymphocytes) in different solid tumors. The study will be conducted on a population of patients with local and/or metastatic malignant solid tumor and who are followed within a standard of care procedure or clinical trial. Patients with any of the following tumor types may be enrolled in the trial: * Head and neck cancer, * Ovarian cancer, * Cervical cancer, * Pre-invasive CIN III cervical cancer (Cervical Intra-epithelial Neoplasia III cervical cancer), * Other solid tumor types (including glioblastoma, NSCLC (Non-small cell lung cancer), anal cancer) Each tumor type will be considered as an independent cohort. For each included patient, biological specimen (tumor sample, blood samples and ascites samples if applicable) will be collected. Study participation of each patient will be 5 years.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03958240
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06804655 - Pharmacoscopy for Patients With Refractory Primary Brain Tumors (PHASE2, NOT_YET_RECRUITING): Advanced technology of ex vivo drug profiling referred to as pharmacoscopy may allow to identify novel drugs for the treatment of glioblastoma and other refractory brain tumors at an individual patient level. This personalized therapeutic approach was developed and validated in pre-clinical glioma models. With the current research proposal, we seek to establish feasibility for a clinical interventional trial for patients with refractory primary brain tumors that is based on pharmacoscopy-guided selection of treatment. The study is supported by an unrestricted grant from Anti Cancer Fund.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06804655
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06455189 - Magnetic Resonance Fingerprinting Guided Extended Resection in Glioblastomas (PHASE1, NOT_YET_RECRUITING): Magnetic resonance imaging, MRI, is a procedure that uses radio waves, a powerful magnet, and a computer to make a series of detailed pictures of areas inside the body. The goal of this study is to determine if MR fingerprinting, new way of acquiring MRI images, can help identify the extent of tumor spread in the brain, better than routine MRI images.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06455189
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: recurrent_disease
- NCT06129760 - Glioblastoma Remote Monitoring and Care - Research Protocol (NA, RECRUITING): The purpose of this research is to learn more about how what the Apple watch measures, in terms of walking data, heart rate, breathing rate, and sleep habits, relates to how participants feel. During the course of the treatment, the symptoms participants experience change, and whether the Apple watch can detect these changes. Ultimately, this knowledge is being used to design proactive tools and signatures that can predict complications or symptom changes before they happen.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06129760
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05283330 - A Phase 1 Open-Label, First-in-human, Dose Escalation and Expansion Study to Determine the Safety, Tolerability, Dosimetry, Pharmacokinetics, and Preliminary Efficacy of 212Pb-DOTAM-GRPR1 in Adult Participants With Recurrent or Metastatic GRPR-expressing Tumors (PHASE1, RECRUITING): A Phase 1 Open-Label, First-in-human, Dose Escalation and Expansion Study to Determine the Safety, Tolerability, Dosimetry, Pharmacokinetics, and Preliminary Efficacy of 212Pb-DOTAM-GRPR1 in Adult Participants with Recurrent or Metastatic GRPR-expressing Tumors
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05283330
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT03170141 - Immunogene-modified Antigen-specific T (IgT) Cells for the Treatment of Glioblastoma Multiforme (PHASE1, ENROLLING_BY_INVITATION): This study aims to treat patients who have been diagnosed with brain cancer glioblastoma multiforme (GBM) including diffuse intrinsic pontine glioma (DIPG) and diffuse midline glioma (DMG). The treatment combines two different approaches to fight cancer: immune modulators and antigen-specific T cells. Immune checkpoint antibodies have been tested on various tumors with good outcomes. GBM is known to express increased levels of certain antigens that can be targeted by T cells including chimeric antigen receptor-modified T (CAR-T) cells and tumor antigen specific cytotoxic lymphocytes (CTLs). In this study, the gene-modified T cells specific for GBM antigens will be combined with immune modulatory gene-modified dendritic cells (DCs) as individualized treatment regimens to treat patients.
  Quick read: GBM-related treatment study for recurrent GBM; biologic or cellular-therapy; limited-enrollment.
  Source: https://clinicaltrials.gov/study/NCT03170141
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: recurrent_disease
- NCT07493447 - Pilot Study Evaluating Panitumumab-IRDye800 as an Optical Imaging Agent to Detect Intracranial Lesions During Neurosurgical Procedures (EARLY_PHASE1, NOT_YET_RECRUITING): This pilot clinical study evaluates the safety and imaging performance of panitumumab-IRDye800 (pan800), a fluorescent, EGFR-targeted imaging agent - in patients undergoing neurosurgical resection of intracranial lesions.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07493447
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07410494 - A Phase 1/2, Open-Label, Biomarker-Driven Study of Allogeneic Donor-Derived CAR-NK Cells With Antigen Selection by Tissue Biopsy and/or Liquid Biopsy Profiling in Participants With Relapsed/Refractory Advanced Solid Tumors (Single-Target vs Dual-Target Strategy) (PHASE1, PHASE2, RECRUITING): This Phase 1/2 study evaluates the safety, feasibility, and preliminary anti-tumor activity of allogeneic donor-derived CAR-NK cells in participants with advanced solid tumors. The CAR target antigen is selected for each participant after tumor profiling using a tissue biopsy and/or liquid biopsy. Participants will receive either a single-target or dual-target CAR-NK product based on the antigen profile.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07410494
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT06929819 - Research on the Safety and Efficacy of Intraoperative Radiation Therapy in Malignant Cerebral Tumor (NA, NOT_YET_RECRUITING): According to the latest national cancer statistics released by the National Cancer Center in February 2022, intracranial tumors account for about 60%-70% of the more than 3.5 million cancer patients, and the morbidity and mortality remain high. Intracranial malignant tumors have become a problem that needs to be solved urgently because of their early recurrence, rapid progression, and short survival, and intracranial malignant tumors include high-grade gliomas, metastases, lymphomas, etc. Glioblastoma (GB) is the most common primary malignancy in the adult central nervous system, accounting for about 57% of all gliomas and 48% of all primary weighted nervous system malignancies. At present, the standard treatment for glioblastoma is mainly surgical treatment, supplemented by postoperative concurrent chemoradiotherapy and adjuvant chemotherapy, but the prognosis of patients is still poor, with a one-year survival rate of 40.6%, a five-year survival rate of only 5.6%, and an average survival time of 12-15 months. For patients diagnosed with intracranial malignancies (including high-grade glioma, metastases, lymphoma, etc.), multimodal image-guided microsurgery combined with postoperative chemoradiotherapy recommended by the guidelines, and intraoperative radiotherapy with tumor bed radiation therapy to achieve targeted and precise tumor treatment, thereby improving the prognosis of patients (including progression-free survival and median overall survival, etc.)
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06929819
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT06492486 - Glioma Adaptive Radiotherapy With Development of an Artificial Intelligence Workflow (PHASE2, NOT_YET_RECRUITING): Gliomas are common primary brain tumors in adults. Gliomas can be classified into different types based on tumor grade, histopathological features, and molecular characteristics. The common types of diffuse gliomas include glioblastoma, astrocytoma, and oligodendroglioma. The standard treatment for diffuse gliomas includes surgery followed by radiation and chemotherapy. As per standard institutional practice, a uniform dose of radiation is delivered to the disease area and MRI is done before and after the treatment. In this study, MRI and PET scan will be done before starting the treatment and standard dose of radiation will be delivered. The interval imaging will be done twice during the course of treatment with MRI and PET, followed by dose modifications. The CT, MRI, and PET will be combined. Based on PET imaging, specific dose will be altered and delivered to specific areas. Dose modification will be done with the help of artificial intelligence. Participant's assessment will be done at regular intervals. Modifications in radiation plans are done based on the changes in disease seen in scans is likely to improve the accuracy of RT treatments. Dose modifications based on imaging to resistant areas will help achieve better tumor control, reduce treatment-related toxicities, precise delivery of the RT and adjusting doses to the organs at risk (OAR) and changes in disease leading to better treatment compliance. Creating an artificial intelligence framework in radiation oncology promises to improve quality of workflow, treatment planning and RT delivery. The aim of the study is to develop an artificial intelligence workflow for treatment of glioma with adaptive radiotherapy. This study will be conducted in Tata Memorial Centre on a population of 60 patients for a duration of 2 years. The total study duration is 4 years.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06492486
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07384884 - Surgery and Laser Interstitial Thermal Therapy for Bilateral Glioblastomas (NA, NOT_YET_RECRUITING): Butterfly glioblastomas (bGBM), defined as tumours crossing the midline to involve hemispheres bilaterally, have a dismal prognosis with a median survival of 3.3-6 months and only 9% of patients with bGBM survive 2-years. These figures put bGBM in the worst end of the spectrum of GBM prognosis, significantly inferior to the survival figures quoted in the literature with standard of care - 14.6 months - particularly when 5-aminolevulinic acid is used as surgical adjuvant - 17.47 months. Despite the poor outcome of this disease, there is preliminary evidence suggesting that active oncology treatment can impact the survival of patients with this condition.With particular regards to surgical resection versus biopsy, there is a suggestion that resection improves overall survival at 6 months with no clear difference at 12 and 18 months of follow up. Laser-induced thermal therapy (LITT) is a minimally invasive laser ablation technique used in a range of brain tumours, including glioblastomas, with similar overall survival to the ones reported for open surgery in patients with lesions not amenable to open resection. The minimally invasive nature of this technique, significantly reducing the collateral damage to the surrounding brain structures, suggests Its potential in the treatment of this bGBM \[14\] with significant implications as a deficit-sparing technique, particularly if associated with preoperative and intraoperative monitoring and mapping techniques. The SLITT-GBM study will combine unilateral open surgery for maximal tumour resection with contralateral LITT to the smaller component/residual.
  Quick read: GBM-related treatment study for GBM or glioma patients; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07384884
  Review priority: 134
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none

#### Related Papers
- PMID:40578479 - Radiation Therapy for WHO Grade 4 Adult-Type Diffuse Glioma: An ASTRO Clinical Practice Guideline.
  Quick read: Guideline-style reference for GBM-specific, recurrent, focused on radiation, temozolomide, biomarker in Practical radiation oncology (2025).
  Source: https://pubmed.ncbi.nlm.nih.gov/40578479/
- PMID:37059335 - ESTRO-EANO guideline on target delineation and radiotherapy details for glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2023).
  Source: https://pubmed.ncbi.nlm.nih.gov/37059335/
- PMID:35426875 - Congress of Neurological Surgeons Systematic Review and Evidence-Based Guidelines on the Management of Progressive Glioblastoma in Adults: Update of the 2014 Guidelines.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Neurosurgery (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35426875/
- PMID:35246769 - Congress of neurological surgeons systematic review and evidence-based guidelines update on the role of cytoreductive surgery in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35246769/
- PMID:35195819 - Congress of Neurological Surgeons systematic review and evidence-based guidelines update on the role of cytotoxic chemotherapy and other cytotoxic therapies in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35195819/
- PMID:29086250 - SEOM clinical guidelines for diagnosis and treatment of glioblastoma (2017).
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Clinical & translational oncology : official publication of the Federation of Spanish Oncology Societies and of the National Cancer Institute of Mexico (2018).
  Source: https://pubmed.ncbi.nlm.nih.gov/29086250/
- PMID:27907278 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of oncology practice (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27907278/
- PMID:27893327 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of clinical oncology : official journal of the American Society of Clinical Oncology (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27893327/
- PMID:26777122 - ESTRO-ACROP guideline "target delineation of glioblastomas".
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2016).
  Source: https://pubmed.ncbi.nlm.nih.gov/26777122/
- PMID:25079102 - EANO guideline for the diagnosis and treatment of anaplastic gliomas and glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in The Lancet. Oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/25079102/
- PMID:24756348 - The role of cytoreductive surgery in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24756348/
- PMID:24740195 - The role of targeted therapies in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24740195/

#### Related Datasets
- gdc_tcga_gbm - NCI GDC TCGA-GBM
  Quick read: Core GBM tumor-genomics program with somatic variants, copy-number, expression, methylation, and linked clinical metadata; open and controlled-access layers.
  Source: https://gdc.cancer.gov/about-data/publications/gbm_2013
- gdc_tcga_lgg_gbm - NCI GDC TCGA Pan-Glioma Cohorts
  Quick read: Combined glioma genomics across lower-grade glioma and GBM for broader IDH, MGMT, and progression-context comparisons.
  Source: https://portal.gdc.cancer.gov/
- ivy_gap - Ivy Glioblastoma Atlas Project
  Quick read: Region-resolved glioblastoma atlas with anatomic and molecular context across tumor subregions.
  Source: https://glioblastoma.alleninstitute.org/
- cbioportal_gbm - cBioPortal GBM Studies
  Quick read: Searchable GBM and glioma genomics knowledgebase spanning TCGA and many published studies with mutation, CNA, and outcome views.
  Source: https://www.cbioportal.org/
- cptac_gbm - CPTAC Brain / Glioblastoma Proteogenomic Resources
  Quick read: Proteomic and proteogenomic tumor data relevant to GBM biology and pathway activation beyond DNA-only signals.
  Source: https://proteomics.cancer.gov/programs/cptac

#### Missing Evidence

### Recurrent High Steroid Burden
- Case ID: `case_recurrent_high_steroid`
- Patient: `synthetic-003`
- Evidence package: 7 ready / 1 missing
- Standard-care paths to discuss: 2
- Trial candidates for review: 116
- Trials needing more evidence: 1
- Bitmask: `64`

#### Recommended Care Pathways
- Recurrent Disease Salvage Therapy Review: Recurrent GBM prompts review of re-resection, re-irradiation, systemic options, and clinical-trial fit.
  Reasons: Patient state matched: recurrent_disease, Patient state matched: adult_patient
- Molecular Tumor Board Review: Escalate to a molecular review when sequencing data exists and the patient is being screened for advanced options.
  Reasons: Patient state matched: advanced_option_search, Patient state matched: performance_status_good

#### Candidate Trials
- NCT07349693 - A Randomized Trial to Assess the Efficacy and Safety of Cerebraca Wafer Plus Temozolomide Versus Temozolomide Alone in Recurrent Glioblastoma (PHASE2, PHASE3, NOT_YET_RECRUITING): This study is designed as a multi-center, randomized, open-label trial to evaluate the efficacy of Cerebraca Wafer in patients with recurrent glioblastoma. Cerebraca Wafer is intended for use in recurrent glioblastoma as an adjunct to surgery (followed by standard-of-care temozolomide), demonstrating potential to improve outcomes in this serious and life-threatening condition
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07349693
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), recurrence_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07318818 - A Phase I/II Clinical Study to Evaluate the Safety and Efficacy of P134 Cells in the Treatment of Recurrent Glioblastoma (PHASE1, PHASE2, RECRUITING): This is an open-label, single-arm, dose-escalation and expansion Phase 1/2 clinical trial designed to evaluate the safety, tolerability and efficacy of P134 cells in patients with recurrent glioblastoma, to explore the maximum tolerated dose (MTD)and recommended Phase 2 dose (RP2D), and to characterize the cytokinetic profile of CAR-T cells in the cerebrospinal fluid of patients. Eligible participants are adults diagnosed with recurrent or progressive glioblastoma who are confirmed as grade 4 glioblastoma (IDH wild-type) by histopathology or molecular pathology. P134 cells are CD44/CD133 dual-targeting CAR-T cells developed by the research team led by Academician Jiang Tao and Professor Zhang Wei from the Beijing Neurosurgical Institute and the Department of Neurosurgery, Beijing Tiantan Hospital. This study is spearheaded by Professor Zhang Wei of the Department of Neurosurgery, Beijing Tiantan Hospital, Capital Medical University, China, with scientific oversight and guidance provided by Academician Jiang Tao of the Chinese Academy of Engineering.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07318818
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07274787 - An Open Label, Prospective, Pilot Study To Evaluate The Safety And Effectiveness Of The NaviFUS System In Conjunction With A Standard Treatment Regimen Of Bevacizumab (BEV) In Patients With Recurrent Glioblastoma (NA, NOT_YET_RECRUITING): This study will evaluate the safety and early effectiveness of the NaviFUS system with concomitant microbubble administration in conjunction with BEV in recurrent GBM patients.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07274787
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07209241 - Phase Ib, Open-Label Study of CART-EGFR-IL13Rα2 Cells Administered Following Lymphodepleting Chemotherapy or Prior to Surgical Resection in Patients With EGFR-Amplified Recurrent Glioblastoma (PHASE1, RECRUITING): This is an open-label, phase 1b study to evaluate different approaches for CART-EGFR-IL13Ra2 dosing and further characterize the safety, feasibility, preliminary efficacy, and pharmacokinetics of CART-EGFR-IL13Ra2 cells in patients with EGFR-amplified glioblastoma that has recurred following prior radiotherapy.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07209241
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07193628 - An Open-label, First-in-human, Dose-escalation and Dose-expansion, Phase I Study of Fully Human B7H3/IL13Ra2 Bispecific Armored Chimeric Antigen Receptor T-Cell Therapy for Treatment of Recurrent or Refractory Glioblastoma (PHASE1, RECRUITING): This study is an investigator-initiated, open-label Phase I clinical trial designed to evaluate the safety and efficacy of EPC-003 fully human anti-B7H3/IL13Ra2 armored Chimeric Antigen Receptor T-Cell Therapy (CAR-T) cell injection in patients with recurrent or refractory glioblastoma. Approximately 14 patients with relapsed or refractory glioblastoma are planned to be enrolled in this trial. During the screening period (Days -28 to -15), subjects will undergo relevant examinations or observations to confirm the disease status, treatment history, and other related information. Subjects who meet the screening criteria will be enrolled in the clinical trial to receive EPC-003 treatment. Specifically, they will receive intraventricular injection of EPC-003 via Ommaya reservoir on Day 0 (D0), Day 7 (D7), Day 14 (D14), Day 21 (D21), Day 28 (D28), and Day 35 (D35), once a week, totaling 6 administrations. All CAR-T cell infusions will be delivered via intraventricular injection. This trial comprises two phases: the first phase is the dose-escalation phase, and the second phase is the dose-expansion phase.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07193628
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07145112 - A Phase 1 Safety and Feasibility Study of Laser Interstitial Thermal Therapy (LITT) Followed by Lomustine (CCNU) for Recurrent Glioblastoma in Adults (PHASE1, RECRUITING): This is a phase 1 study evaluating the safety and feasibility of laser interstitial thermal therapy (LITT) followed by lomustine (CCNU) for recurrent glioblastoma in adults. The primary aim is to evaluate the safety of the combination of LITT plus lomustine based on the assessment of treatment-related adverse events and the feasibility of completing LITT + lomustine in the proposed timeframe. The secondary aim is to assess overall survival for up to 2 years after the first dose of lomustine.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07145112
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 50 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07145047 - Clinical Study on the Application of Oncolytic Virus in Recurrent Glioblastoma (PHASE1, PHASE2, RECRUITING): This clinical trial aims to evaluate whether an oncolytic viral agent can treat recurrent glioblastoma. It will also assess the safety and tolerability of the oncolytic viral agent. The primary question it seeks to answer is: What medical problems do participants experience when injected with the oncolytic viral agent? Researchers will administer the oncolytic viral agent via intratumoral injection to determine its efficacy in treating recurrent glioblastoma. Participant Procedures: Receive the initial injection, followed by additional injections every 2-4 weeks for a total of 6 injections. Undergo physical examinations and tests every 2 to 4 weeks. Record their symptoms, hematological test results, and imaging findings.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07145047
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07093814 - A Phase I/II Study to Evaluate the Safety, Tolerability, and Preliminary Efficacy of VRT106 for Injection in Patients With Recurrent/Progressive Glioblastoma (PHASE1, PHASE2, RECRUITING): This study is an open-label, single-arm Phase I/II clinical trial with the primary objective of evaluating the safety, tolerability, and efficacy of VRT106 in patients with recurrent/progressive glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07093814
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07076472 - MC240704 Pilot Dose Escalation and Expansion Study of Sonodynamic Therapy With Aminolevulinic Acid Hydrochloride (5-ALA HCl Or SONALA-001) in Combination With Exablate 4000 Type 2.0 MR-Guided Focused Ultrasound (MRgFUS) in Patients With Progressive or Recurrent Glioblastoma Multiforme (RGBM) (EARLY_PHASE1, RECRUITING): This early phase I trial tests the safety, best dose, and effectiveness of SONALA-001 or 5-ALA HCL in combination with magnetic resonance imaging-guided focused ultrasound (MRgFUS), also called sonodynamic therapy, in treating patients with glioblastoma that is growing, spreading, or getting worse (progressive) or that has come back after a period of improvement (recurrent). Sonodynamic therapy is a non-invasive combination therapy that uses low-intensity ultrasound, such as MRgFUS, to activate a drug, such as SONALA-001 or 5-ALA HCL, to kill tumor cells. SONALA-001 or 5-ALA HCL binds to the tumor and may help the sonodynamic therapy target the tumor. MRgFUS is an image-guided, non-invasive technique that uses high energy ultrasound from the Exablate 4000 Type 2.0 device to kill tumors without damaging surrounding healthy tissue. Giving sonodynamic therapy using SONALA-001 or 5-ALA HCL with MRgFUS may be safe, tolerable, and/or effective in treating patients with progressive or recurrent glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07076472
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06910306 - A Study to Assess the Feasibility and Safety of Intratumoral Diffusing Alpha Emitters for the Treatment of Recurrent Glioblastoma (NA, RECRUITING): A unique approach for cancer treatment employing intratumoral diffusing alpha radiation emitter device for the treatment of recurrent Glioblastoma
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06910306
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06894225 - Proof-of-Concept Study of ACT001 in Adult Patients With Recurrent Glioblastoma Harbouring STAT3-High Signature (PHASE2, NOT_YET_RECRUITING): This trial will study the effectiveness of ACT001 in adult patients whose Glioblastoma have recurred with a STAT3-high signature after standard-of-care treatment with at least radiation therapy.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06894225
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06883747 - A Phase 0/1 Study of BMS-986504, a MTA Cooperative PRMT5 Inhibitor in Recurrent Glioblastoma Participants With MTAP Deleted Tumors Scheduled for Resection to Evaluate Central Nervous System (CNS) Penetration With PK-Triggered Expansion Cohort (EARLY_PHASE1, RECRUITING): This is an open-label, multi-center, Phase 0/1 dose-escalation trial designed to enroll up to 9 total recurrent glioblastoma (rGBM) participants with confirmed MTAP loss/deletion in their archival or pretreatment biopsy tissue, who are scheduled for surgical resection. MTAP loss/deletion will be determined by next-generation sequencing (NGS). The trial will include a dose escalation design to evaluate the pharmacokinetics (PK) and safety and tolerability of BMS-986504 (MRTX1719). The trial will be composed of a Phase 0 component and an Expansion Phase 1 component. Participants with tumors demonstrating a positive PK response in the Phase 0 component of the study will be eligible to enroll into the the Phase 1 component that will include 21-day cycles of therapeutic dosing of BMS-986504.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06883747
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06616727 - A Phase I Study to Evaluate the Safety, Tolerability and Pharmacokinetics of SNC109 in Patients With Recurrent Glioblastoma (PHASE1, ENROLLING_BY_INVITATION): A phase I study to evaluate the safety, tolerance and pharmacokinetics of SNC109 in patients with rGBM
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; limited-enrollment.
  Source: https://clinicaltrials.gov/study/NCT06616727
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 50 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06613841 - Pilot Study to Evaluate Multitracer [18F]Fluciclovine and 18F-FDG PET, and Advanced MRI Methods at 7Tesla Metabolic Profiling of Glioblastoma (EARLY_PHASE1, RECRUITING): * To perform metabolic phenotyping of treatment naïve and recurrent GBM by multitracer \[18F\]Fluciclovine and 18F-FDG PET. * To compare uptake measures of 18F-Fluciclovine and 18F-FDG and MRI quantification of glutamate and lactate levels to tumor tissue laboratory assays (RNA seq and proteomics) of glutamine/glutamate, glucose, and lactate metabolism. * To perform metabolic phenotyping of treatment naïve and recurrent GBM by advanced MRI methods at 7 Tesla
  Quick read: GBM-specific treatment study for recurrent GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06613841
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06598787 - A Phase II Clinical Study to Evaluate the Efficacy and Safety of BL-B01D1 for Injection in Patients With Recurrent Glioblastoma (PHASE2, RECRUITING): This is an open-label, multicenter, phase II study to evaluate the safety, efficacy, and pharmacokinetic characteristics of BL-B01D1 for Injection in patients with recurrent glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06598787
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06585527 - A Clinical Study of the Safety and Efficacy of Third-generation Oncolytic TS-2021 in the Treatment of Recurrent Malignant Gliomas (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and efficacy of oncolytic virus TS-2021 in the treatment of recurrent malignant glioma.About 30 eligible participants with recurrent malignant glioma will : * Be intratumoral injected the TS-2021 oncolytic virus to study its safety and efficacy. * Be followed for 1 year after the injection to complete imaging studies, neurological function tests, and report adverse events. Using the data obtained during the follow-up period, researchers will conduct statistical analyses and evaluate the safety and efficacy of oncolytic virus TS-2021.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06585527
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06327451 - Evaluate the Efficacy and Safety of Atorvastatin Combined With Temozolomide in the Treatment of Glioblastoma (PHASE2, RECRUITING): Glioblastoma (GBM) is the primary intracranial malignant tumor with the highest morbidity and mortality, and the 5-year survival rate is less than 10%. The number of primary diagnostic patients and deaths of GBM in China ranks first in the world every year, which seriously threatens people's life and health. At present, the clinical treatment strategy of maximum surgical resection combined with concurrent chemo- and radio-therapy and TTF treatment is still not satisfactory, and the median survival time of GBM patients is only 14.4 months. Statins inhibit cholesterol production with few side effects and are widely used for cholesterol control in patients with hyperlipidemia. In recent years, statins have shown good anti-tumor effect. Our previous study found that statins can block the malignant progression of glioma mediated by EGFR pathway. Therefore, the investigators report a clinical study protocol designed to evaluate the clinical efficacy of a comprehensive treatment strategy of atorvastatin (ATO) combined with temozolomide (TMZ) in primary and recurrent glioblastomas with high EGFR expression. The investigators designed a multicenter, single-arm, double-blind, phase II clinical trial to evaluate the efficacy and safety of oral ATO combined with TMZ in EGFR-high expressing GBM. After informed consent was signed by the patient or authorized family members, the patients were treated with the current STUPP regimen and ATO (20mg, qn) orally. The patients were regularly followed up for 52 weeks after treatment. The primary endpoint was progression-free survival (PFS), which was defined as the time from the start of GBM surgery to tumor progression (recurrence) or death. The secondary end point was the rate of tumor control, which was defined as the proportion of patients with a complete response, a partial response, or a stable disease that had shrunk or remained stable for a given period of time. Safety will be assessed during the study by monitoring of regular MRI scans, laboratory tests (liver function, lipid profile, blood routine), electrocardiography, vital signs (blood pressure, pulse, temperature), and weight. The results of this clinical trial will provide key information on whether the oral combination of atorvastatin and temozolomide prolongs PFS in EGFR-high GBM patients with efficacy and safety.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06327451
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06325683 - Randomized Phase II Trial of Anti-Lag-3 and Anti-PD-1 Blockade vs. SOC in Patients With Recurrent Glioblastoma (PHASE2, RECRUITING): This phase II trial compares the safety, side effects and effectiveness of anti-lag-3 (relatlimab) and anti-PD-1 blockade (nivolumab) to standard of care lomustine for the treatment of patients with glioblastoma that has come back after a period of improvement (recurrent). Relatlimab is a monoclonal antibody that may interfere with the ability of tumor cells to grow and spread. A monoclonal antibody is a type of protein that can bind to certain targets in the body, such as molecules that cause the body to make an immune response (antigens). Immunotherapy with monoclonal antibodies, such as nivolumab, may help the body's immune system attack the tumor, and may interfere with the ability of tumor cells to grow and spread. Lomustine is a chemotherapy drug and in a class of medications called alkylating agents. It damages the cell's deoxyribonucleic acid and may kill tumor cells. Giving relatlimab and nivolumab may be safe, tolerable, and/or effective compared to standard of care lomustine in treating patients with recurrent glioblastoma.
  Quick read: GBM-specific treatment study for first-recurrence GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06325683
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT06271421 - Application of Nanoparticles for Cyclic Hyperthermia In Adjuvant Therapy of gLioblastoma Multiforme (ANCHIALE) (NA, RECRUITING): Glioblastoma multiforme (GBM), the most common and malignant primary brain tumor in adults is classified as a World Health Organisation (WHO) grade 4. Surgical removal of the tumor is the primary method of treatment. Unfortunately, because GBM is a disease of the entire brain, total resection is not possible. Therefore, the use of radiotherapy and/or chemotherapy is considered as Stupp protocol. Patients with recurrent GBM will be included in the ANCHIALE study. The goal of the trial is to evaluate the efficacy and tolerance of using the NanoTherm therapy system in recurrent GBM. The main questions it aims to answer are: 1. how NanoTherm therapy influences overall survival, and progression free survival; 2. what is the tolerance of NanoTherm therapy in terms of side effects (allergies, intracranial bleeding, infections, brain edema, increased intracranial pressure) and quality of life. Participants will undergo: * initial visit, considering the inclusion/exclusion criteria, neurological examination, and surveys regarding daily functioning and quality of life; * standard neurosurgical operation aimed, if possible, complete removal of the recurrent GBM and administration of NanoTherm ASI - a sterile suspension of iron oxide nanoparticles. A catheter will be implanted allowing for measurement of temperature during the first activation in the magnetic field; * between the 6th and 10th day after tumor resection, a standard computerized tomography (CT) scan of the head will be performed for routine postoperative evaluation; * after the first activation (10th day), the catheter will be removed; * subsequently, for 6 times, the patient will be subjected to the variable magnetic field of the NanoActivator® to induce hyperthermia - activations will be conducted on the 10th, 14th, 17th, 21st, 24th, and 28th day; * for up to 2 years post-procedure, a CT scan with an evaluation of treatment efficacy will be performed; * during follow-up visits for up to 2 years after the surgical procedure, a neurological examination, assessment of adverse symptoms, number of hospitalizations, number of medical visits, clinimetric assessment regarding quality of life, neurological deficit and degree of disability will be conducted. Researchers will compare NanoTherm group with patients undergoing Stupp protocol treatment for the abovementioned effects.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06271421
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06220552 - Low-dose Radiotherapy Combined With Sintilimab and Temozolomide in Recurrent Glioblastoma: A Single-arm, Prospective Phase II Clinical Study (PHASE2, RECRUITING): This is an open-label, single-arm, phase II clinical trial to explore the efficacy and safety of low-dose radiotherapy combined with programmed death 1 (PD-1) inhibitor (sintilimab) and temozolomide in recurrent glioblastoma. The eligible patients are scheduled to administered sintilimab 200mg D1 Q3W temozolomide 50mg/m2 QD and radiotherapy 1Gy/1F D1/D2/D8/D15 Q3W for 4-6 cycles, then sintilimab for maintenance. The overall primary study hypothesis is that the combination regimen of low-dose radiotherapy, sintilimab and temozolomide is safe and feasible in the treatment of recurrent glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06220552
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06218524 - Clinical Study for Evaluating the Effectiveness of Haloperidol and Temozolomide Synergism on Adult Recurrence Glioblastoma (PHASE2, NOT_YET_RECRUITING): The study of investigators indicated that TMZ can up-regulate dopamine D2 receptor (DRD2) expression, and mediates Ferroptosis inhibition and chemoresistance of GBM. The clinical data also proved that the DRD2 expression in recurrent GBM is significantly higher than that in primary GBM. Moreover, the DRD2 antagonist haloperidol can attenuate the above function of DRD2, and increase the sensitivity of GBM to the TMZ by inducing fatal autophagy and ferroptosis. In xenograft mice, the combined usage of haloperidol and Temozolomide (TMZ) can significantly inhibit tumor growth and increase overall survival. The investigators' findings have been published in Clinical cancer research. Haloperidol known as a butylbenzene antipsychotic drug, has been widely used in several kinds of mental illnesses, such as depression, schizophrenia, and Bipolar disorder. And the safe dosage of the haloperidol is clear so far. So in this study, the investigators will recruit the patients who suffered from recurrent GBM, and evaluate the effectiveness of single TMZ chemotherapy or combined with haloperidol.
  Quick read: GBM-specific treatment study for recurrent GBM; drug-treatment; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06218524
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06183983 - Hitting the Mark: Introducing State-of-the-art MRI for Precision Radiotherapy of Glioblastoma (NA, RECRUITING): The goal of this prospective cohort study is to assess the potential of advanced MRI for improved radiotherapy target delineation in patients diagnosed with glioblastoma. The main questions it aims to answer are: * How does the coverage of the recurrence volume by a radiotherapy plan based on advanced MRI compare to the coverage by the clinical radiotherapy plan? * How does the distribution of the dose to organs at risk by a radiotherapy plan based on advanced MRI compare to the distribution by the clinical radiotherapy plan? Participants will undergo an extended MRI-protocol prior to radiotherapy. This extended MRI-protocol includes the clinical brain tumor imaging protocol plus additional advanced MRI-sequences. Radiation treatment and patient follow-up will occur according to the clinical standard.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06183983
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06097975 - A Phase I Clinical Trial on Combined (Neo-)Adjuvant Intravenous Plus Intracranial Administration of Ipilimumab and Nivolumab in Recurrent Glioblastoma (PHASE1, RECRUITING): The goal of this phase I interventional study is to determine the safety and feasibility of the proposed investigational (neo-)adjuvant treatment regimen in patients with resectable reccurent glioblastoma. Participants will: * receive neo-adjuvant administration of intravenous immunotherapy * followed by a maximal safe neurosurgical resection * afterwards, immunotherapy will be injected into the brain tissue * followed by insertion of an Ommaya reservoir * postoperatively, administration of immunotherapy will be continued
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06097975
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06039709 - Pilot Study of Sonodynamic Therapy With 5-ALA for the Treatment of Recurrent Glioblastoma Using Neuronavigation-Guided Low-Intensity Focused Ultrasound (PHASE1, RECRUITING): Patients diagnosed with glioblastoma (GBM) are faced with limited treatment options. This pilot study will evaluate the safety and feasibility of combining an investigational drug called 5-ALA with neuronavigation-guided low-intensity focused ultrasound (LIFU) for patients who have recurrent GBM. Focused ultrasound (FUS) can be used to non-invasively destroy tumor tissue while preserving normal tissue. When FUS is combined with 5-ALA, this combinatorial approach is called sonodynamic therapy (SDT), and this investigational therapy is being tested for its ability to cause damage to GBM cells. SDT will take place prior to surgery for recurrent GBM.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06039709
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06011109 - A Pilot Study of APG-157 With Bevacizumab for Patients With Recurrent High-Grade Glioma (PHASE1, PHASE2, RECRUITING): The goal of this interventional study is to evaluate the efficacy of APG-157 in combination with Bevacizumab in subjects with recurrent high-grade glioma. The main questions the study aims to answer are: * Progression-free and overall survival of patients receiving this combination; * Quality of Life (QOL); and * Tumor response on imaging The participants will take APG-157 daily by dissolving two pastilles in their mouth at around breakfast, lunch and dinner time (total of six pastilles per day). The pastilles dissolve in the mouth. The participants will continue to receive Bevacizumab as standard of care.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06011109
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=2 vs 3 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05941234 - Improving Personalised Glioblastoma Care by Stem Cell Analysis, Omics (Including Immunomics) and Artificial Intelligence Approaches (NA, RECRUITING): The study aims at: 1. Perform a multilayer analysis relying on tight integration of in-depth multi-omics approaches with clinical data to discover immune markers, with attention to age and sex differences, predicting prognosis and defining key life/environmental elements, to guide AI-driven personalised treatments and ensure improved care and QoL of glioblastoma patients. 2. To deepen glioblastoma knowledge through the study of glioblastoma stem cell cultures and to assess the sensitivity of glioblastoma stem cell cultures to a number of chemotherapeutics in different experimental conditions. 3. To create a comprehensive, stakeholder-generated guidelines for the ethical use of patient data for artificial intelligence-assisted prediction systems in glioblastoma, including an online, easily accessible patient information brochure to increase patient empowerment in the field.
  Quick read: GBM-specific treatment study for first-recurrence GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05941234
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05871021 - A Phase IIa, Open-label, Multicenter Study of Radiochemotherapy With Isotoxic Dose Escalation and Protective VEGF Inhibition Using Bevacizumab in the Treatment of Patients With First Diagnosis of IDH Wild-type, MGMT Unmethylated Glioblastoma (PHASE2, RECRUITING): Glioblastoma is the most aggressive brain tumor and often recurs locally despite intensive treatment. Standard chemoradiotherapy with 60 Gy may not be sufficient to control the tumor, and dose escalation seems to be warranted, but causes more toxicity. To address this, the multicentric PRIDE trial employs two cycles of bevacizumab to achieve dose escalation isotoxically. The goal is improved survival without significantly increasing side effects. The study uses a simultaneous integrated boost with a total dose of 75 Gy in 2.5 Gy per fraction.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05871021
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05773326 - A Phase 0, Single-center, Open-label, Dose-escalating Trial Using Super-selective Intra-arterial Infusion of a Single Dose of Temsirolimus for the Treatment of Recurrent High-grade Glioma (EARLY_PHASE1, RECRUITING): This is a single-center, open-label, dose-escalating Phase 0 trial that will enroll participants with a confirmed diagnosed recurrent high-grade glioma (grade 3 or 4 per WHO criteria) targeting the mTOR pathway. Eligible participants will be administered a single infusion of temsirolimus through super-selective intra-arterial infusion or intravenous infusion. Participants will receive the study drug administration on the same day as the planned surgical resection of the tumor.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05773326
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05769660 - An Open-label, Phase I Clinical Trial to Assess the Maximum Tolerated Dose (MTD), Safety and Efficacy of BEY1107 in Combination with Temozolomide in Patient with Recurrent or Progressive Glioblastoma Multiforme (GBM) (PHASE1, RECRUITING): This is a Phase 1 study to evaluate the maximum tolerated dose, safety and efficacy of BEY1107 in combination with Temozolomide in Patients with Recurrent or Progressive Glioblastoma Multiforme (GBM)
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05769660
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05653635 - Contribution From PET-DOPA in Glioblastoma Re-irradiation - A Randomized Phase II Study (PHASE2, RECRUITING): ReciDOPA is a phase II, single-stage randomized, multicenter, prospective trial assessing the efficacy of an irradiation protocol based on Intensity-modulated radiation therapy with simultaneous-integrated boost guided by FDOPA-PET in patient with recurrent glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05653635
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05590689 - Phase I/II Dose Escalation Trial of Radiodynamic Therapy (RDT) With 5-Aminolevulinic Acid in Patients With First Recurrence of Glioblastoma (PHASE1, PHASE2, RECRUITING): The investigational drug 5-ALA (known under the trade name Gliolan®) is an approved drug for the surgical removal of malignant glioma (WHO grade III and IV). In this trial, the drug is being tested outside of its actual approval as a radiosensitizer in combination with conventional radiotherapy for first-time recurrence (relapse) of malignant glioma. In this clinical trial, the investigational drug 5-ALA is being used for the first time in a multiple dose escalation regimen in combination with radiotherapy following surgical removal of a recurrent malignant glioma in humans. The investigational drug, 5-ALA, has been used as a single dose to date as a standard of care for visualization of malignant tissue in the surgical removal of gliomas. The planned clinical trial will first and foremost investigate how well repeated administration of the investigational drug 5-ALA is tolerated in combination with radiotherapy. At the same time, the design of the trial serves to optimize this novel therapeutic procedure with regard to the frequency of administration of the investigational drug 5-ALA in combination with radiotherapy for future clinical trials. As a secondary objective, the efficacy of additional 5-ALA administration will also be investigated.
  Quick read: GBM-specific treatment study for first-recurrence GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05590689
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05577091 - Phase 1 Study of Autologous Tris-CAR-T Cell Locoregional Immunotherapy for Recurrent Glioblastoma (PHASE1, RECRUITING): This is a Phase 1 study of recurrent glioblastoma locoregional adoptive therapy with autologous peripheral blood T cells lentivirally transduced to express a dual-target, truncated IL7Ra modified chimeric antigen receptor (CAR), delivered by Ommaya reservoir, a pre-indwelled catheter in the tumor resection cavity or ventricle. Patients with pathological confirmation of glioblastoma and radiological evidence of recurrence are candidates for this clinical trial. If the patient meets all other eligibility criteria, and meets none of the exclusion criteria, will have leukapheresis, and a subsequent Ommaya reservoir implantation. T cells will be isolated from the PBMC sample and then be bioengineered into a 4th generation CAR-T cell, Tris-CAR-T cells. Recipients will be assigned to three courses in the order of enrollment. The first 2 patients will be assigned to the low-dose group. The second 2 patients will be assigned to the high dose group. The first 4 patients will have at least one dose of autologous Tris-CAR-T cells delivery via the Ommaya reservoir, at a maximum of 6 doses. The interval between the first and the second dose is 28 days, and the rest doses will be administered weekly. The last 6 patients will be assigned to the consecutive multidose group, and will receive a weekly dose of autologous Tris-CAR-T cells for a maximum of 8 weeks. All patients will undergo studies including MRI to evaluate the effect of the CAR-T cells, physical examination, and cerebrospinal fluid cytokine assays to evaluate side effects. All patients will undergo a long-term follow-up. The hypothesis is that an adequate amount of Tris-CAR-T cells can be manufactured to complete all the three courses. The other hypothesis is that Tris-CAR-T cells can safely and effectively be administered through the Ommaya reservoir to allow the CAR-T cells to directly interact with the tumor cells for each patient enrolled in the study. The primary aim of the study will be to evaluate the safety of Tris-CAR-T administration. Secondary aims of the study will include evaluating CAR-T cell distribution within cerebrospinal fluid and peripheral blood, tumor progress post-CAR-T cell infusion, and, if tissue samples from multiple time points are available, also evaluate the degree of target expression, biological characteristics of samples at diagnosis versus at recurrence or progression.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05577091
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05557292 - A Phase I/Ib, Open-Label, Dose-Escalation Study of RMC-5552 Monotherapy in Adult Subjects With Recurrent Glioblastoma (PHASE1, RECRUITING): This phase I/Ib trial tests the side effects, best dose, tolerability, and effectiveness of RMC-5552 in treating patients with glioblastoma that has come back (recurrent). RMC-5552 is a type of medicine called an mechanistic target of rapamycin (mTOR) inhibitor. These types of drugs prevent the formation of a specific group of proteins called mTOR. This protein controls cancer cell growth, and the study doctors believe stopping mTOR from forming may help to kill tumor cells.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05557292
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05540275 - Phase 2 Study to Evaluate the Clinical Efficacy and Safety of Tislelizumab Plus Low-dose Bevacizumab in Bevacizumab Refractory Recurrent Glioblastoma With PTEN or TERT Gene Mutations (PHASE2, NOT_YET_RECRUITING): The purpose of this study is to evaluate the clinical efficacy and safety of Tislelizumab (one anti-PD-1 antibody same as nivolumab approved in China) in combination with bevacizumab in patients with recurrent or progressive glioblastoma (GBM) who have progressed on bevacizumab with or without PTEN or TERT gene mutations.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05540275
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05366179 - Phase I Study of Intraventricular Infusion of T Cells Expressing B7-H3 Specific Chimeric Antigen Receptors (CAR) in Subjects With Recurrent or Refractory Glioblastoma (PHASE1, RECRUITING): The purpose of this study is to test the safety of using T lymphocyte chimeric antigen receptor cells against the B7-H3 antigen (CAR.B7-H3T cells) in patients with glioblastoma. CAR.B7-H3T cells treatment has not been tested in humans and is not an approved treatment by the Food and Drug Administration for glioblastoma.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05366179
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05363826 - Phase I Study of the Safety of Intracavitary Photodynamic Therapy (PDT) of the Brain Bordering Resected Recurrent Glioblastoma or Gliosarcoma Using Intravenous Photobac® and a Balloon Light Applicator (PHASE1, RECRUITING): This study is the first step in testing the hypothesis that adding Photobac® Photodynamic Therapy to surgical removal of a glioblastoma or gliosarcoma will be both safe and effective. Photodynamic Therapy (PDT) combines light and a photosensitizer. PDT has been used to treat a variety of cancers with varying degrees of success. For the past thirty years Photolitec has been working to develop a treatment for glioblastoma or gliosarcoma using light and a photosensitizer. Photolitec's scientists were looking for a photosensitizer that: 1. has no significant systemic toxicity apart from some temporary skin photosensitivity, 2. crosses the blood brain barrier, 3. accumulates to a high level in glioblastoma and minimally in the brain, 4. is activated by the wavelength of light that penetrates most deeply into the brain, 5. minimizes any temporary skin photosensitivity. Preliminary testing indicates the Photolitec team has achieved these five goals. Photolitec is now able to offer a clinical trial based on the results of this work.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05363826
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: post_chemoradiation, Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05284643 - Pilot Trial of Spectroscopic MRI-guided, Dose-Escalated Proton Radiation Therapy and Bevacizumab for Recurrent Glioblastoma (NA, RECRUITING): The purpose of this research is to find hidden cancer with an experimental magnetic resonance imaging (MRI) scan called spectroscopic magnetic resonance imaging (sMRI). That spectroscopic MRI scan will be used to increase the area of the brain receiving radiation and then the dose of radiation in attempt to kill more of the cancer. Proton radiotherapy and bevacizumab (Avastin) are used to minimize the possible side effects of this approach.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05284643
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05186064 - Glioblastoma Targeted Treatment Option Maximization by Whole Genome Sequencing (NA, RECRUITING): In Dutch centers performing neurosurgery on and/or treating GBM, all recurrent GBM patients are discussed in local tumor boards and this setup will be used to effectively identify possible GLOW study candidates. 160 patients that will undergo re-resection in the GLOW study will be presented with WGS results leading to added treatment options.
  Quick read: GBM-specific treatment study for first-recurrence GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05186064
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05083754 - A Randomized, Open-label Pilot Trial to Evaluate the Safety and Efficacy of Carmustine Wafer in Combination With Retifanlimab and Standard Radiation With or Without Temozolomide in Newly-Diagnosed Adult Subjects With Glioblastoma (PHASE1, RECRUITING): The purpose of the study is to evaluate the safety and survival of carmustine wafers and radiation and retifanlimab with or without temozolomide (TMZ) in newly-diagnosed adult subjects with glioblastoma multiform after carmustine wafer placement.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05083754
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04863950 - A Phase II, Investigator-Initiated Study of Imipramine Hydrochloride and Lomustine in Recurrent Glioblastoma (PHASE2, RECRUITING): This study is designed as a single center, prospective, open label, single-arm therapeutic trial with both surgical and non-surgical cohorts.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04863950
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04590664 - A Phase 1 / 2 Study of Visudyne (Liposomal Verteporfin) in Persons with Recurrent High Grade EGFR-Mutated Glioblastoma (PHASE1, PHASE2, RECRUITING): This phase I/II trial studies the side effects and best dose of Visudyne (liposomal verteporfin) and to see how well it works in treating patients with high grade EGFR-mutated glioblastoma that has come back (recurrent). Visudyne is FDA approved in combination with light to treat eye diseases. In this study we use Visudyne by itself like chemotherapy to kill tumor cells which may be sensitive to verteporfin.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04590664
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04559230 - A Phase II, Multicenter, Prospective Study of Sacituzumab Govitecan in Recurrent Glioblastoma (PHASE2, RECRUITING): This is an open-label single arm study. All patients will receive the study drug. The aim of the study is to compare overall survival (OS) of patients with recurrent brain tumor, known as Glioblastoma (GBM) having high levels of a protein, Trophoblast cell surface antigen 2 (Trop-2), expression on treatment with Sacituzumab Govitecan (SG) versus lomustine only which has been used in the past.
  Quick read: GBM-specific treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04559230
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04267978 - Open-label Prospective Study of Recombinant Human Endostatin Combined with Cytotoxic Chemotherapy Regimen in the Treatment of Recurrent Gliomas (PHASE2, RECRUITING): Almost all gliomas relapse. After temozolomide rechallenge or combination with irinotecan, the progression-free survival rate at 6 months (PFS-6%) of recurrent glioblastoma was about 21%. After treatment with irinotecan-based chemotherapy regimen, the PFS-6% of recurrent lower-grade gliomas was 40%. The optimal chemotherapeutics of recurrent gliomas has yet to be determined. Anti-angiogenesis is a promising therapeutic strategy. Vascular endothelial growth factor-A (VEGF) is the primary driver of angiogenesis in tumors. Bevacizumab, a humanized monoclonal antibody directed against VEGF, is the prototypical anti-angiogenic drug and received accelerated approval of the United States Food and Drug Administration (FDA) for the treatment of recurrent glioblastoma. Bevacizumab inproved the PFS-6% (36%), but had no effect on the overall survival (OS) (9.2 months). Moreover, the effects of bevacizumab are transient and most patients' tumors progress just after a median time of 3-5 months. Recombinant human endostatin (rh-ES) is an endogenous broad-spectrum angiogenesis inhibitor that has been shown to significantly improve therapeutic efficacy when combining with conventional chemotherapy agents in non-small-cell lung cancer, breast cancer and melanoma. In our previous study, we retrospectively analyzed the effect and toxicity of rh-ES when combined with temozolomide and irinotecan on adult recurrent disseminated glioblastoma. After combined treatment, PFS-6% was 23.3%; the median PFS and OS were 3.2 and 6.9 months, respectively, which were promising compared with that in other studies. Once patients get radiographic remission in a short time (4 months), they may get a long PFS.The combined regimen did not reduce the sensitivity of tumor to bevacizumab. After tumor progression from the combined chemotherapy, bevacizumab usage could help to prolong the survival time (5.1 months versus 2.4 months). Moreover, the toxicities of the combination therapy in this study were manageable. On the basis of prior clinical experience, we carry out this prospective trial to confirm the efficacy and safety of the combination of rh-ES, temozolomide and irinotecan in patients with recurrent gliomas.
  Quick read: GBM-specific treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04267978
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT02394626 - RESURGE - Randomized Controlled Comparative Phase II Trial on Surgery for Glioblastoma Recurrence (PHASE2, RECRUITING): Patients with glioblastoma face a grim prognosis. Despite recent advancement in neurosurgical technology and neuro-oncology glioblastomas almost invariably progress or recur after a median of 4-8 months. The strategy to repeat tumor resection at recurrence in order to minimize tumor load and thus to facilitate subsequent second-line therapy has been shown to be feasible and safe. However, evidence for a survival benefit of surgery for recurrent glioblastoma is scarce and relies entirely on retrospective analyses. While most retrospective analyses report an apparent survival benefit, an EORTC meta-analysis on second-line therapies found no survival difference in patients with or without surgery at recurrence. With regard to the risks and costs inherent to surgery for glioblastoma, a randomized controlled trial is required. The purpose of the study is to compare the effect of craniotomy and tumor resection followed by adjuvant second-line therapy to no surgery followed by second-line therapy on overall survival, neurological status, and quality of life. Analysis of overall survival will be used to improve sample size estimation of a subsequent phase III trial for craniotomy and tumor resection of glioblastoma recurrence in cooperation with the EORTC.
  Quick read: GBM-specific treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02394626
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07492836 - Prospective, Pilot Study to Evaluate Hypofractionated Radiotherapy Associated With Temozolomide in Patients Aged 18 to 70 Years With Glioblastoma (HypoGBM) (NA, NOT_YET_RECRUITING): The goal of this clinical trial is to evaluate the feasibility, safety and effectiveness of radiotherapy with fewer days of treatment and a higher dose of radiation each day in patients under 70 years of age diagnosed with a brain tumor known as glioblastoma.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07492836
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07461948 - Advanced MRI for Visualization and Quantification of the Tumor Immune Microenvironment (TIME) in Glioblastoma (PHASE3, RECRUITING): This phase III trial is evaluating whether a combination of three advanced magnetic resonance imaging (MRI) techniques, including chemical exchange saturation transfer (CEST) MRI, diffusion-relaxation correlation spectrum imaging (DR-CSI), and ferumoxytol-enhanced magnetic resonance imaging (Fe-MRI) are effective as non-invasive methods for assessing the cells and proteins that surround and interact with tumor cells (the tumor immune microenvironment) in patients with glioblastoma. Researchers understand that some types of brain tumors are harder to treat than others, but the reasons for this are not known in many cases. CEST MRI uses differences in the tissue microenvironment, like protein concentration or intracellular pH, to generate contrast differences. DR-CSI detects microstructural changes in tissue associated with immune cells infiltrating the tumor. Fe-MRI uses ferumoxytol as a contrast agent with MRI. Contrast agents are substances that are injected into the body and taken up by certain tissues, making the tissues easier to see in imaging scans. More advanced imaging techniques like CEST, DR-CSI, and Fe-MRI may offer less invasive methods than surgery or biopsy for helping researchers understand the tumor immune microenvironment in patients with glioblastoma, which may help researchers determine why some tumors are more resistant to treatment.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07461948
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07368283 - A Single-arm Phase II Non-inferiority Clinical Study of Limited Target Volume Radiotherapy After Glioblastoma Surgery (NA, NOT_YET_RECRUITING): Research on radiotherapy target volumes for glioblastoma is increasingly focused on exploring more limited yet effective irradiation fields, aiming to achieve local control while minimizing acute and long-term neurotoxicity. Previous retrospective analysis by investigators revealed that local recurrences of glioblastoma are predominantly confined to a narrow margin around the original lesion: 98.3% of recurrences occurred within 0.5 cm of the original T2-FLAIR abnormality, 94.8% within 1 cm of the original T1-enhanced region. These findings have been cited in the ESTRO-EANO treatment guidelines. Building on this evidence, investigators plan to conduct a single-arm, phase II clinical trial to systematically evaluate the efficacy and safety of a 1 cm radiotherapy target volume in post-operative glioblastoma patients.Eligible patients with glioblastoma who have undergone surgical resection will be selected to receive limited-field radiotherapy. The target volume will be defined based on the postoperative MRI enhancing lesion: a 1 cm margin will be added to form the clinical target volume (CTV), followed by a further 0.3 cm margin to create the planning target volume (PTV). A total dose of 60 Gy will be delivered in 30 fractions (2 Gy per fraction, 5 fractions per week). Concurrent and adjuvant chemotherapy will be administered per standard guidelines. The primary efficacy endpoints are the 6-month progression-free survival rate and the incidence of symptomatic radiation-induced brain necrosis of grade 3 or higher. Secondary endpoints include overall survival, patterns of recurrence, neurocognitive function, and quality of life.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07368283
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07144735 - Allogeneic Gamma Delta (γδ) T Cells for the Treatment of Glioblastoma (NA, RECRUITING): This first-in-human clinical study aims to evaluate the safety and feasibility of locally delivered, allogeneic γδ T cells (genetically edited with ARIH1 and BCL11b knockout, designated ABOUT γδT cells) in patients with glioblastoma multiforme (GBM). The engineered effector cells are delivered via localized administration to selectively target and eliminate residual GBM cells. ABOUT: ARIH1 and BCL11b knockOUT γδ T cells.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07144735
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07089758 - A Pilot Feasibility Study for Cerebral Open Flow Microperfusion in Patients Undergoing Planned Neurosurgical Resection of Diseased Parenchyma. (NA, NOT_YET_RECRUITING): The purpose of this study is to evaluate the safety and feasibility of intra-operative microperfusion during a planned neurosurgical resection of diseased brain parenchyma, including either an epileptic focus requiring temporal lobectomy or a glioma. Devices used for microperfusion are Joanneum Research cerebral open flow microperfusion (OFM) catheters, push and pull tubing, and MPP102-II pump.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07089758
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07067905 - Clinical Evaluation of [68Ga]Ga-XT771 PET for Diagnosis in Patients With Glioblastoma and Clear Cell Renal Cell Carcinoma (EARLY_PHASE1, RECRUITING): A prospective, open-label, phase 1 study. This clinical trial aims to evaluate the diagnostic value of 68Ga-XT771, a CAIX/CAXII protein-specific probe, in PET/CT imaging for patients with clear cell renal cell carcinoma and glioblastoma. Safety, tolerability, and biodistribution characteristics of 68Ga-XT771 will also be assessed.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07067905
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06781372 - Development and Characterization of Patient's Derived Organoids as a Platform for the Screening of Novel Therapeutic Treatments for Glioblastoma Multiforme (NA, NOT_YET_RECRUITING): The study will enroll patients suffering from glioblastoma, a malignant brain tumor. Intervention is intended as a laboratory intervention and not as a clinical intervention. In fact, tumor removed from patients' brains will be sent to a dedicated laboratory to obtain an "avatar" of the tumor, named patient-derived organoid (PDO). A number of experimental antitumor approaches will be studied on PDOs. Results of these experiments will be correlated to the prognosis of patients.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06781372
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06764537 - Evaluation of in Vitro Antitumor Activity of GD2 CAR-T Cells Generated From Blood of Glioblastoma Patients (NA, NOT_YET_RECRUITING): Glioblastoma is a brain tumor with a very poor prognosis, affecting around 2,400 new patients every year. Current treatments do not provide good control of the disease. In view of the therapeutic impasse, it is necessary to develop new strategies. CAR-T cells (Chimeric antigen receptor T cells) represent a highly promising therapy for the treatment of incurable cancers, including glioblastoma. This treatment aims to destroy cancer cells by relying on the patient's own immune system. CAR-T cells are generated from the patient's own immune cells, more specifically T lymphocytes, which are genetically modified to express a tumor-specific receptor on their surface. CAR-T cells bind to tumor cells and cause their destruction. However, these cells have shown limited therapeutic power in the treatment of brain tumors. This is mainly due to the microenvironment surrounding the tumor, which is composed of immunosuppressive cells. These cells, and the molecules they secrete, help to reduce the activity of CAR-T cells that would otherwise reach the tumor. Little is currently known about these resistance mechanisms. The aim of this research is therefore to better understand these resistance mechanisms in order to propose a strategy for enhancing the therapeutic action of CAR-T cells in the treatment of glioblastoma. The main objective of this research is to evaluate the impact of the tumor environment on the antitumor efficacy of anti-GD2 CAR-T therapeutic cells in an in vitro glioblastoma model. Both tumor environment cells and CAR-T therapeutic cells will be generated from glioblastoma patient cells. The secondary objectives of this research are to * Evaluate the impact of tumor environment targeting on the in vitro antitumor efficacy of anti-GD2 CAR-T therapeutic cells. * Evaluate the quality/quantity of generated cells (CAR-T cells and tumor environment cells) in relation to glioblastoma patients. * Evaluate the efficiency of the cell isolation technique (CAR-T cells and tumor environment cells)
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06764537
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06749925 - Phase III Randomized, Double-Blind, Placebo-Controlled Clinical Trial Assessing the Efficacy and Safety of Dendritic Cell-Based Immunotherapy for Glioblastoma (PHASE3, NOT_YET_RECRUITING): This Phase III, multicenter, placebo-controlled clinical trial with sequential randomization is designed to evaluate the efficacy and safety of an experimental vaccine composed of hybrid dendritic cells (DCs) for the treatment of glioblastoma. Conducted at the Hospital das Clínicas of the University of São Paulo Medical School (HCFMUSP) and the Institute of Biomedical Sciences of the University of São Paulo (ICB/USP), the study is led by Professor José Alexandre Marzagão Barbuto. A multidisciplinary team of researchers specializing in neurosurgery, pathology, hematology, and other fields will contribute to a comprehensive approach. The trial aims to determine whether the hybrid DC vaccine can increase overall survival in adult patients with glioblastoma who have completed standard treatment, including surgery, chemotherapy, and radiotherapy. Secondary objectives include evaluating progression-free survival, quality of life, immune response, and the safety of the intervention. The study will enroll 186 patients, who will be randomized into three groups: (1) a control group receiving placebo, (2) a group receiving the DC vaccine, and (3) a group receiving the DC vaccine combined with pembrolizumab.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06749925
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06687681 - Efficacy of the Intrathecal Injection of Active Allogeneic Natural Killer Cells in Patients With High-grade Gliomas; A Multi-center Phase II Clinical Trial (PHASE2, RECRUITING): Gliomas are the most common malignant brain tumors, which are often associated with high-grade tumors characterized by an inferior prognosis and low patient survival rates in both children and adults. Surgical removal and tumor resection are the primary treatment approaches for gliomas. In such cases, whole-brain radiation therapy is also employed as a therapeutic option, which itself has significant side effects, and studies have shown limited impact on improving patient survival. Targeted therapy and recently investigated approaches such as targeted therapy have shown some tumor regression, but in most cases, tumor recurrence has been observed after initial regression. Therefore, they have a limited impact on prolonging patient survival. Immunotherapy, particularly immunotherapy with specific immune cells, can effectively identify and eliminate cancer cells and has been utilized as a new approach in the past two decades, especially in cancers where conventional methods have limited success. Among the effective immunotherapy methods, using natural killer cells (NK cells) can be one of the promising approaches. Currently, phase I clinical trials have been conducted by our research group in patients with gliomas.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06687681
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06617208 - Prognostic IntraOperative Biomarkers ideNtification in Tumor rElatEd suRgery (PIONEER Study) (NA, NOT_YET_RECRUITING): INTRODUCTION AND RATIONALE Aggressive brain tumors like glioma have the ability to infiltrate the surrounding healthy brain tissue, disrupting normal neuronal activities and leading to impaired motor and cognitive functions, as well as causing epilepsy. This malignant brain tumor is considered one of the most challenging cancers to treat, with a median survival of 12 to 15 months. Recent findings on direct neuron-tumor interactions indicate that abnormal brain activity in the regions surrounding brain tumors may contribute to develop epilepsy and accelerating tumor growth. Tumors tend to 'fuel' themselves with neurotransmitters released during its 'daily' neuronal firing. Hyperactive neurons in the peritumoral cortex can form excitatory electrochemical synapses with surrounding tumor cells, creating direct communication pathways within the peritumoral microenvironment, which aids in the progression and proliferation of tumor cells via direct and paracrine signalling pathways. However, the specific features of this abnormal brain activity in the peritumoral cortex have not been fully clarified and information on the pathological changes of neuronal activity in glioma patients is largely lacking. To advance more effective treatment strategies, it is crucial to better understand the complex interactions between the tumor and the brain. This is especially important for the group of patients of which many perceive diminished quality of life because of epilepsy, cognitive functioning and language problems after tumor surgery. Furthermore, a thorough understanding is lacking of what tumor resection does to the original hyperactive peritumoral cortex and if resecting this is beneficial for improving postoperative outcome both for epilepsy as well as regarding survival. Therefore, identifying the hyperactive peritumoral cortex and directly addressing its impacts on the brain function and long-term surgical outcome could be a promising novel therapeutic strategy for treating glioma patients. STUDY AIM The measurement focuses on capturing neuronal activity at single-neuron resolution in the peritumoral cortex of glioma patients using cortical depth electrodes. It is well-established that gliomas can remodel the surrounding brain tissue, leading to abnormal neuronal hyperactivity, which contributes to tumor progression and epilepsy. However, the specific neuronal patterns and underlying mechanisms of these changes are not yet fully understood. This study will aim to collect detailed single-neuron recordings in this context, enabling us to map the precise neurophysiological disruptions caused by gliomas. On the long term, this research could lay the groundwork in identifying novel therapeutic approaches by providing critical in-sights into how gliomas alter brain function.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06617208
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06551909 - Radioimmunotherapy in Solid Tumors (Aim 2- Stereotactic Neoadjuvant Radiotherapy for Glioblastoma) (NA, RECRUITING): This is a prospective multicenter study of hypofractionated radiotherapy for the radiation treatment (RT) of solid tumors and in particular for Glioblastoma (in Aim 2). It is based on the results of ongoing studies at our Institute to validate the efficacy of extremely hypofractionated RT in neoadjuvant settings, which observed immunostimulatory effects of RT and the synergy with immune components. The collaboration between San Raffaele Hospital (Milan), the IRCCS Istituto Nazionale dei Tumori Fondazione G. Pascale (Naples) and the San Giuseppe Moscati Hospital of National Relief and High Specialty (Avellino) will ensure that patient recruitment, treatment and monitoring can be translated into facilities of the National Health System using common procedures. The various departments involved will treat patients with the same methods synergistically exploring the immuno/biological factors related to efficacy (and/or toxicity), based on new radioimmunotherapeutic approaches. Clinical and research activity will be developed jointly, drawing on the expertise in radiotherapy, radiomics, oncology, imaging and immunotherapy skills already available.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06551909
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06297512 - Interventional, Single-arm, Open-label Open-label, Phase II Trial to Evaluate the Role of Anthracycline Infusion After Radio Therapy (RT) in Pediatric and Young Adults With Glioblastoma (pGBM). (PHASE2, RECRUITING): Glioblastoma (GBM) and diffuse intrinsic bridge gliomas (DIPG) only the most aggressive forms of cancer, and their prognosis remains bleak. Currently, the standard of treatment is TMZ concomitant with radiotherapy, and, at the end of combined treatment, as adjuvant therapy. In vitro and in vivo experimental studies have suggested that anthracyclines are effective antineoplastics for the treatment of gliomas. In patients with solid tumors treated with anthracyclines, continuous infusion administration compared with bolus administration has been shown to provide a better safety profile especially with regard to cardiotoxicity. Based on this evidence, this study aims to evaluate the safety and antitumor activity of combined treatment with Dox, WBRT (whole body radiotherapy), and TMZ in pediatric and young adult patients affected by GMB
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06297512
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06136611 - Preoperative Preradiotherapy TTFields (PORTRAIT) (NA, NOT_YET_RECRUITING): PreOperative PreRAdIotherapy Tumour Treating Fields (PORTRAIT) is a Phase I study that will test the safety and feasibility of Optune administered preoperatively and preradiotherapy in patients with a new radiological diagnosis of glioblastoma (GBM). Participants will be required to undergo additional MRI sequencing scans and provide blood, tear fluid and tissue samples over a maximum of 6 months. After the study patients will follow their standard treatment pathway.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06136611
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06102525 - A Phase 1/2a, Open-label, Multicenter, Dose Escalation and Dose Expansion Study Evaluating the Safety, Tolerability, and Efficacy of RZ-001 in Combination With Valganciclovir in Subjects With Glioblastoma (PHASE1, PHASE2, RECRUITING): This is a Phase 1/2a, open-label study to evaluate the safety, tolerability, immunogenicity, and preliminary clinical activity of RZ-001 administered in combination with VGCV in subjects with hTERT-positive GBM.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06102525
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05842746 - Efficacy and Safety of Elemene Plus Stupp Protocol Versus Stupp Protocol Alone for Newly-diagnosed Glioblastoma: A Multi-center Phase II Randomized Controlled Trial (PHASE2, NOT_YET_RECRUITING): The goal of this phase II randomized clinical trial is to compare the safety and efficacy of Elemene plus Stupp Protocol (the new protocol) and Stupp Protocol alone (the standard protocol) in patients with newly-diagnosed glioblastomas (ndGBMs). The main questions to answer are: * Whether the new treatment protocol (Elemene plus Stupp Protocol) is clinically safe for ndGBM patients. * Whether the new treatment protocol (Elemene plus Stupp Protocol) brings better survival benefits for ndGBM patients compared to the standard-of-care Stupp Protocol. Study participants will be enrolled in 5 hospitals in China and randomly assigned to receive either the new protocol or the standard protocol. The overall survival (OS) rate in the 12th month, the progression-free survival (PFS) rate in the 6th month, OS, PFS, and adverse events assessed by the CTCAE (Common Terminology Criteria for Adverse Events) will be evaluated for all patients.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05842746
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05820191 - B-amyloid as a Marker for GBM Bioimaging (PHASE2, NOT_YET_RECRUITING): This project is aimed at improvement of glioblastoma (GBM) diagnostic strategies for discrimination of tumor progression and chemo- and radiotherapeutic treatment-related changes in brain tissue. The study will elucidate the diagnostic value of PET imaging with use of amyloid-β radioisotope tracer Amyvid (Florbetapir F18) for GBM. The results of the study will provide data for development of new approach for GBM diagnostics.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05820191
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05720078 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-3 (UNITED-3): Applying a Two Phase, Personalized Margin, Reduced Clinical Target Volume Approach (NA, RECRUITING): The goal of this study is to test whether an adaptive radiation therapy (RT), two-phase approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive, two-phase RT approach compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05720078
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05653622 - Simultaneous Integrated Boost FDOPA PET Guided in Patients With Partially- or Non-operated Glioblastoma (PHASE2, RECRUITING): Glioblastoma (GBM) is the most common primary brain cancer in adults. Surgery, chemoradiotherapy (temozolomide TMZ) and then adjuvant TMZ is the standard treatment. But, most patients relapse in a median time of 8-9 months; the median overall survival (OS) ranged from 15 to 18 months. Some frail patients received hypofractionated radiation and concomitant and adjuvant TMZ. For some, the radiation dose is not optimal. Moreover, recurrences develop mainly in the initial tumor site. These two reasons justify increasing the dose. To limit the movements of these fragile patients, the method consists of increasing the dose without increasing the number of sessions by using the Simultaneous Integrated Boost (SIB) which increases the dose in targeted volumes while the rest of the volume receives a minimum dose. A phase I trial showed the possibility of increasing the dose in SIB up to 80 Gy in a part of the GBM enhanced on MRI. FDOPA PET detects certain more aggressive tumor areas, areas likely to recur. Integrating them into the SIB seems appropriate. A phase II trial showed the interest of SIB guided by FDOPA PET in terms of progression-free survival but without impact on OS. This study differed from the one the investigators propose, because a dose and conventional fractionation, identical to that of the European Organization for Research and Treatment of Cancer/National Cancer Information Center (NCIC/EORTC) protocol were delivered, the gliomas were unmethylated MGMT, less likely to respond. Studies with SIB and hypofractionation are often retrospective and for others, hypofractionation was debatable and the dose increase was not based on PET capture but on MRI. However, a prospective phase II study, with SIB and hypofractionation, not integrating FDopa PET has demonstrated the relevance of SIB. In this project, the investigators propose to use the integrated boost technique (SIB) guided by PET FDOPA to increase the radiation dose in GBM, in patients either fragile and partially operated, or only biopsied and for whom the prognosis is the most pejorative.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05653622
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: post_surgery
- NCT05607407 - Targeting Transsulfuration Via Suppression of Thyroid Hormone Signaling in Progressive Glioblastoma: Phase 2 and Pharmacodynamic Trial of Methimazole in Patients With Progressive Glioblastoma (PHASE2, RECRUITING): The purpose of this study is to test the effectiveness, safety, and tolerability of a drug called Methimazole. The investigational drug, Methimazole is not FDA approved for brain tumors, but it is used to treat thyroid illnesses. Different doses of Methimazole will be given to several study participants with glioblastoma. The first several study participants will receive the lowest dose. If the drug does not cause serious side effects, it will be given to other study participants at a higher dose. The doses will continue to increase for every group of study participants until the side effects occur that require the dose to be lowered. The procedures in this study are research blood draws, physical exams, collection of medical history, MRI scans, and study drug administration.
  Quick read: GBM-specific treatment study for GBM or glioma patients; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05607407
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05502991 - Phase 2 Study to Evaluate the Clinical Efficacy and Safety of Sintilimab Plus Low-dose Bevacizumab in Patients With Glioblastoma of Different Relapse Stages (PHASE2, NOT_YET_RECRUITING): This is an ongoing Phase 2, open-label, single-center, non-randomized study of sintilimab (one anti-PD-1 antibody same as nivolumab approved in China) plus bevacizumab administered in a low dosage schedule in adult (≥ 18 years) participants with a clinical relapse or circulating tumor DNA (ctDNA)-level relapse of glioblastoma (GBM). This study has two non-comparative study groups. Both cohorts will receive the same study drug sintilimab 200mg and bevacizumab 3mg/kg every 3 weeks. A stringent two-step non-randomized process will be used to assign participants to one of the study groups. Neither participants nor doctors but the researcher can choose which group participants are in. No one knows if one study group is better or worse than the other. 60 total participants are expected to participate in this study (30 participants in each cohort). Grouping process: After enrollment, under the standard of care, participants will receive regular tumor in situ fluid (fluid within the surgical cavity, TISF) sampling for ctDNA analysis and recceive regular MRI. The researcher will study the TISF ctDNA and imaging dynamics to determine whether the tumor reaches to ctDNA-level (Cohort 1) or clinical relapse (Cohort 2). At the first step, all timely identified as ctDNA-level relapse tumors will be assigned into the Cohort 1 and receive the study drug immediately, those failed to be timely identified will be assigned into the Cohort 2 and receive the study drug after the clinical relapse. At the second step, once either group reaches the target number, the new participants will be all assigned into the other Cohort.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05502991
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05370079 - Control Cohort CTRL COH (NA, RECRUITING): Autoimmune encephalitis (AE) and paraneoplastic neurological syndromes (PNS) are rare disease that could be difficult to diagnose. So it necessary to obtain numerous sample from different disease to develop more specific diagnosis kit It could be possible through the characterisation of new genetic biomarkers.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05370079
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT04752280 - Glioblastoma Radiotherapy Using IMRT or Proton Beams (NA, RECRUITING): Radiation therapy is an integral part of the multimodal primary therapy of glioblastomas. As the overall prognosis in this tumor entity remains unfavorable, current research is focused on additional drug therapies, which are often accompanied by increases in toxicity. By using proton beams instead of photon beams, it is possible to protect large parts of the brain which are not affected by the tumor more effectively. An initial retrospective matched-pair analysis showed that this theoretical physical benefit is also clinically associated with a reduction in toxicity during therapy and in the first few months thereafter. The aim of the GRIPS study is to prospectively test this clinical benefit in a randomized, open-label Phase III study. Patients are treated in the study using either modern photon radiation techniques (standard arm) or proton beams (experimental arm). The primary endpoint is the cumulative toxicity CTC grade 2 and higher in the first 4 months. Secondary endpoints include overall survival, progression-free survival, quality of life, and neurocognition.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04752280
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT02977780 - INdividualized Screening Trial of Innovative Glioblastoma Therapy (INSIGhT) (PHASE2, RECRUITING): This research study is studying several investigational drugs as a possible treatment for Glioblastoma (GBM). The drugs involved in this study are : * Abemaciclib (arm is currently closed to accrual) * Temozolomide (temodar) * Neratinib (arm is currently closed to accrual) * CC115 (arm is currently closed to accrual) * QBS10072S
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02977780
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05226494 - A Phase 1 Trial to Evaluate the Safety and Tolerability of Fb-PMT in Patients With Recurrent Glioblastoma (PHASE1, RECRUITING): Glioblastoma is a highly aggressive and fatal form of primary malignant brain tumor with limited treatment options. fb-PMT affects a large group of cancer cell signaling pathways and thus may be effective in heterogeneous, treatment-resistant tumors such as Glioblastoma. fb-PMT also is actively transported across the blood-brain barrier into the brain. This study is being conducted to determine the dose level for further clinical development of fb-PMT to treat recurrent Glioblastoma.
  Quick read: GBM-related treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05226494
  Review priority: 150
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: recurrence_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06001281 - Predictive Value of Soluble CD146 in Patients With Recurrent Glioblastoma Treated by Bevacizumab (NA, RECRUITING): Glioblastoma is the most common malignant primary brain tumor with poor prognosis because of its diffusive and infiltrative nature. The FDA approved the use of the anti-VEGF antibody bevacizumab in recurrent GBM. However, resistance to this anti-angiogenic reagent is frequent and fails to enhance patients' overall survival. The investigators previously identified one novel mechanism responsible for bevacizumab-resistance in CD146-positive glioblastoma (Joshkon et al. Acta Neuropathol Commun, 2022). Now, the investigators objective is to prospectively monitor the soluble CD146 value in plasma from patients treated by bevacizumab for recurrent glioblastoma. The investigators will collect plasma at baseline, before the first bevacizumab administration, before the second administration, at the time of first MRI evaluation and at progression. Plasma CD146 value will be analyzed by ELISA. The investigators expect to confirm the correlation between soluble CD146 value in plasma and patient response to bevacizumab.
  Quick read: GBM-specific treatment study for recurrent GBM; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06001281
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05565118 - Prospective Surgical Study on the Pattern of Electrical Activity in High Grade Glioma (WHO Grade III and IV) as a Predictor of Progression (PHASE1, RECRUITING): The purpose of this study is to test the safety and feasibility of recording brain activity within and around high-grade glioma tumors at the time of surgery. A small biopsy will be taken at the sites of the recordings.
  Quick read: GBM-specific treatment study for recurrent GBM; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05565118
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07416188 - Phase 1/Phase 2 Open Label Trial of a Novel Indenoisoquinolone C-MYC/TOPOISOMERASE 1 Inhibitor (LMP744) in Recurrent Glioblastoma (PHASE1, PHASE2, NOT_YET_RECRUITING): Background: Glioblastoma is a common brain cancer in adults. Treatment includes surgery, radiation, and chemotherapy. But this cancer can return after treatment and is often fatal. Researchers want to know if a study drug (LMP744) can kill glioblastoma tumor cells. Objective: To test LMP744 in people with glioblastoma. Eligibility: People aged 18 years or older with glioblastoma that returned after treatment. Design: Participants will be screened. They will have a surgery to remove a small sample of tumor tissue (biopsy) from the brain. This will be done under protocol 03-N-0164. They will stay in the clinic for 1 night. They will also have imaging scans and tests of their heart function. Participants will have a central line installed: A flexible tube will be inserted into a vein in the chest. It will be attached to a port under the skin. This port will be used to draw blood and give medicines without having to insert new needles into a vein. LMP744 will be given through the central line for 5 days in a row. Participants will remain in the clinic for this time. Participants will then have a second surgery to remove as much of their tumor as possible. They will remain in the clinic until they recover from the surgery. Then they will recover at home after surgery. Participants will return to the clinic to receive the study drug for 5 days in a row through the central line, once a month for up to 12 months. Blood tests, heart function tests, and periodic imaging scans will be repeated during these visits. Participants will continue to have telehealth visits every 3 months after they stop taking the drug.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07416188
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: recurrent_disease
- NCT06552260 - A Surgical Window of Opportunity Clinical Trial of Troriluzole in Recurrent IDH Wild-Type Glioblastoma (EARLY_PHASE1, RECRUITING): This research study is studying troriluzole as a possible treatment for recurrent glioblastoma. The name of the study drug involved in this research study is: -Troriluzole (a tripeptide prodrug of riluzole)
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06552260
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05911230 - Advanced Diffusion MRI to Differentiate Tumor Recurrence From Pseudoprogression in Patients With Glioblastoma and Brain Metastases- AiD GLIO Pilot Trial (NA, RECRUITING): This pilot study investigates whether advanced diffusion-weighted MRI (ADW-MRI) can differentiate between true tumor progression (TP) and a pseudoprogression (PsP) in patients with glioblastoma (GBM) or brain metastases.
  Quick read: GBM-specific treatment study for GBM or glioma patients; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05911230
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05629702 - A Randomised Controlled Phase II Trial of Temozolomide With or Without Cannabinoids in Patients With Recurrent Glioblastoma (PHASE2, RECRUITING): ARISTOCRAT is a phase II, multi-centre, double-blind, placebo-controlled, randomised trial to compare the cannabinoid Nabiximols with placebo in patients with recurrent MGMT methylated glioblastoma (GBM) treated with temozolomide (TMZ).
  Quick read: GBM-related treatment study for first-recurrence GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05629702
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 16 (match), kps_min=70 vs 60 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT05432518 - Biomarker and Tumor Cell Culture-Driven Pilot Trial for Treatment of Recurrent Glioblastoma (EARLY_PHASE1, RECRUITING): This will be a single-arm open-label prospective pilot feasibility trial recruiting 10 adult patients with recurrent glioblastoma who are assigned to receive the personalized study treatment based on the genetic profile of their recurrent GBM tumor resected at the time of surgery. It will be aimed to gather preliminary information on the study intervention and the feasibility of conducting a full-scale trial.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05432518
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT03423628 - A Phase I, Multicenter Study to Assess the Safety, Tolerability, and Pharmacokinetics of Ascending Doses of AZD1390 in Combination With Radiation Therapy in Patients With Glioblastoma Multiforme and Brain Metastases From Solid Tumors (PHASE1, RECRUITING): This study will test an investigational drug called AZD1390 in combination with radiation therapy for the treatment of brain tumors. This is the first time AZD1390 is being given to patients. This study will test safety, tolerability and PK (how the drug is absorbed, distributed and eliminated) of ascending doses of AZD1390 in combination with distinct regimens of radiation therapy
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03423628
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT01269853 - Phase I/II Trial Of Repeated Super-selective Intraarterial Cerebral Infusion Of Bevacizumab (Avastin) for Treatment of Relapsed/Refractory Glioblastoma Multiforme and Anaplastic Astrocytoma. (PHASE1, PHASE2, RECRUITING): The high-grade malignant brain tumors, glioblastoma multiforme (GBM) and anaplastic astrocytoma (AA), comprise the majority of all primary brain tumors in adults. This group of tumors also exhibits the most aggressive behavior, resulting in median overall survival durations of only 9-12 months for GBM, and 3-4 years for AA. Initial therapy consists of either surgical resection, external beam radiation or both. All patients experience a recurrence after first-line therapy, so improvements in both first-line and salvage therapy are critical to enhancing quality-of-life and prolonging survival. It is unknown if currently used intravenous (IV) therapies even cross the blood brain barrier (BBB). The investigators have shown in a previous phase I trial that a single Super-selective Intraarterial Cerebral Infusion (SIACI) of Bevacizumab (up to 15mg/kg) is safe and effective in the treatment of recurrent GBM. Therefore, this phase I/II clinical research trial is an extension of that trial in that the investigators seek to test the hypothesis that repeated dosing of intraarterial Bevacizumab is safe and effective in the treatment of recurrent malignant glioma. By achieving the aims of this study the investigators will also determine if IV therapy with Bevacizumab should be combined with repeated selected intraarterial Bevacizumab to improve progression free and overall survival. The investigators expect that this project will provide important information regarding the utility of repeated SIACI Bevacizumab therapy for malignant glioma, and may alter the way these drugs are delivered to the patients in the near future.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT01269853
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07179328 - Assessment of Safety and Feasibility of Focused Ultrasound Next Generational Dome Helmet Mediated Blood-Brain Barrier Disruption for the Treatment of High-Grade Glioma in Patients Undergoing Standard Chemotherapy (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and feasibility of focused ultrasound (FUS)-mediated blood-brain barrier (BBB) disruption using the Next Generation Dome Helmet (NGDH) in adults with glioblastoma (GBM) undergoing the maintenance phase of the standard "Stupp protocol". Participants will: * Undergo repeated FUS BBB disruption treatments during the maintenance phase of temozolomide (TMZ) chemotherapy. * Receive intravenous ultrasound contrast (DEFINITY®) prior to each FUS session to facilitate targeted BBB disruption. * Undergo serial MRI scans and clinical assessments to evaluate safety and the extent of BBB opening. * Provide blood samples (and tumor tissue if available) for biomarker analysis related to BBB permeability, tumor presence, and treatment response. * Be followed for progression-free survival (PFS) and overall survival (OS) during routine neuro-oncology visits until end of life.
  Quick read: GBM-related treatment study for GBM or glioma patients; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07179328
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT04523688 - Vaccination With Autologous Dendritic Cells Loaded With Autologous Tumour Homogenate in Glioblastoma: a Phase II Study (PHASE2, RECRUITING): Single arm, monocentric trial to assess the safety and the progression-free survival related to the combined treatment of dendritic cell vaccine loaded with autologous tumor homogenate and temozolomide in patients operated for glioblastoma and then treated with standard radiochemotherapy (according to Stupp regimen).
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04523688
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07385846 - Pilot Study for the Use of Navigated Focused Ultrasound and Pembrolizumab in the Treatment of Recurrent WHO Grade 4 IDH-Wildtype Glioblastoma With Mismatch Repair Deficiency: A Phase I Clinical Trial (PHASE1, NOT_YET_RECRUITING): Navigated Focused Ultrasound and Pembrolizumab in the Treatment of Recurrent WHO Grade 4 IDH-Wildtype Glioblastoma with Mismatch Repair Deficiency.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07385846
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07089641 - A Phase Ib Open Label Clinical Trial to Evaluate the Safety and Efficacy of ERAS-801 in Surgically Accessible Recurrent Glioblastoma Patients With EGFR Amplification or Mutation (ERAS801-SARG) (PHASE1, RECRUITING): This phase Ib trial tests the safety and side effects of ERAS-801 in treating patients with isocitrate dehydrogenase (IDH) wildtype, epidermal growth factor receptor (EGFR) amplified or mutated grade IV glioblastoma or astrocytoma that can be removed by surgery (resectable) and that is growing, spreading, or getting worse (progressive) or that has come back after a period of improvement (recurrent). Glioblastoma is the most common brain cancer in adults and survival rates remain poor despite treatment including surgery, radiation and chemotherapy. EGFR is a protein found on the surface of some cells, to which epidermal growth factor binds, causing the cells to divide. It is found at abnormally high levels on the surface of many types of tumor cells, so these cells may divide excessively in the presence of epidermal growth factor. ERAS-801, an EGFR inhibitor that can penetrate the central nervous system, binds to the tumor cells that express EGFR and may help shrink or slow the growth of the tumor cells.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07089641
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06934889 - Phase Ib Trial of ABBV-637 or ABBV-155 in Combination With ERAS-801 for Glioblastoma With Amplification of the Epidermal Growth Factor Receptor (PHASE1, RECRUITING): The researchers are doing this study to find out whether the drugs ABBV-637 and ABBV-155 are safe treatments that cause few or mild side effects when given alone or in combination with ERAS-801 in people with recurrent GBM.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06934889
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06860594 - A Phase I Trial Combining Triapine With Radiation Therapy for Recurrent Glioblastoma or Astrocytoma (PHASE1, RECRUITING): This phase I trial tests the safety, side effects, and best dose of triapine in combination with radiation therapy in treating patients with glioblastoma or astrocytoma that has come back after a period of improvement (recurrent). Triapine may stop the growth of tumor cells by blocking some of the enzymes needed for cell growth. Radiation therapy uses high energy x-rays, particles, or radioactive seeds to kill cancer cells and shrink tumors. Giving triapine in combination with radiation therapy may be safe, tolerable, and/or effective in treating patients with recurrent glioblastoma or astrocytoma.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06860594
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT06815029 - A Phase 1 Trial to Evaluate the Safety of IL13Rα2-Targeting Chimeric Antigen Receptor (CAR) T Cells With CRISPR Knockout of TGFβR2 in Patients With Recurrent or Progressive High-Grade Glioma (HGG) (PHASE1, RECRUITING): This phase I trial tests the safety, side effects and best dose of TGFβR2KO/IL13Rα2 chimeric antigen receptor (CAR) T-cells given within the skull (intracranial) in treating patients with glioblastoma or IDH-mutant grade 3 or 4 astrocytoma that has come back after a period of improvement (recurrent) or that is growing, spreading, or getting worse (progressive). CAR T-cell therapy is a type of treatment in which a patient's T cells (a type of immune system cell) are changed in the laboratory so they will attack tumor cells. T cells are taken from a patient's blood. When the cells are taken from the patient's own blood, it is known as autologous. Then the gene for special receptors that bind to a certain proteins on the patient's tumor cells are added to the T cells in the laboratory. The special receptors are called CAR. Large numbers of the CAR T cells are grown in the laboratory and given to the patient by infusion for treatment of certain tumors. Giving TGFβR2KO/IL13Rα2 CAR T cells may be safe, tolerable, and/or effective in treating patients with recurrent or progressive glioblastoma or grade 3 or 4 IDH-mutant astrocytoma.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06815029
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06344130 - A Phase I Hypofractionation Trial of Re-irradiation in Good Prognosis Recurrent Glioblastoma (PHASE1, RECRUITING): Background: Glioblastoma (GBM) is a cancer of the brain. Current survival rates for people with GBM are poor; survival ranges from 5.2 months to 39 months. Most tumors come back within months or years after treatment, and when they do, they are worse: Overall survival drops to less than 10 months. No standard treatment exists for people whose GBM has returned after radiation therapy. Objective: To find a safe schedule for using radiation to treat GBM tumors that returned after initial radiation treatment. Eligibility: People aged 18 years and older with grade 4 GBM that returned after initial radiation treatment. Design: Participants will be screened. They will have a physical exam with blood tests. A sample of tumor tissue may be collected. Participants will undergo re-irradiation planning: They will wear a plastic mask over their head during imaging scans. These scans will pinpoint the exact location of the tumor. This spot will be the target of the radiation treatments. Participants will undergo radiation treatment 4 times per week. Some people will have this treatment for 3 weeks, some for 2 weeks, and some for 1 week. Blood tests and other exams will be repeated at each visit. Participants will complete questionnaires about their physical and mental health. They will answer these questions before starting radiation treatment; once a week during treatment; and at intervals for up to 3 years after treatment ends. Participants will have follow-up visits 1 month after treatment and then every 2 months for 6 months. Follow-up clinic visits will continue up to 3 years. Follow-ups by phone or email will continue an additional 2 years.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06344130
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: prior_radiation, Matched inclusion factor: recurrent_disease
- NCT06058988 - Window of Opportunity Assessment of [Fam-]Trastuzumab DERuxtecan-nxki (T-DXd) Brain Tumor Penetration and Efficacy (WOnDER-BT) (PHASE2, RECRUITING): The purpose of this study is to find out how much tratuzumab deruxtecan (T-DXd) can penetrate the tumor when injected into the body, and whether T-DXd may be an effective treatment for brain cancers that express the HER2 protein.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06058988
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05979064 - Laparoscopically Harvested Omental Tissue Autograft to Bypass the Blood Brain Barrier (BBB) in Human Recurrent Glioblastoma Multiforme (rGBM) (NA, RECRUITING): This single center, single arm, open-label, phase I study will assess the safety of laparoscopically harvested autologous omentum, implanted into the resection cavity of recurrent glioblastoma multiforme (GBM) patients.
  Quick read: GBM-related treatment study for recurrent GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05979064
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05789394 - Phase 1, Dose Escalation, Non-Randomized, Open Label, Clinical Trial Evaluating the Safety and Preliminary Efficacy of Allogenic Adipose-Derived Mesenchymal Stem Cells (AMSCs) for Recurrent Glioblastoma (PHASE1, RECRUITING): This phase I trial tests the safety, side effects, and best dose of allogenic adipose-derived mesenchymal stem cells (AMSCs) in treating patients with glioblastoma or astrocytoma that has come back (recurrent) who are undergoing brain surgery (craniotomy). Glioblastoma is the most common and most aggressive form of primary and malignant tumor of the brain. Currently, the standard of care for this disease includes surgical resection, followed by radiation with chemotherapy and tumor treating fields. Despite this aggressive therapy, the survival after finishing treatment remains low and the disease often reoccurs. Unfortunately, the available therapy options for recurrent glioblastoma are minimal and do not have a great effect on survival. AMSCs are found in body fat and when separated from the fat, are delivered into the surgical cavity at the time of surgery. When in direct contact with tumor cells, AMSCs affect tumor growth, residual tumor cell death, and chemotherapy resistance. The use of AMSCs delivered locally into the surgical cavity of recurrent glioblastoma during a craniotomy could improve the long-term outcomes of these patients by decreasing the progression rate and invasiveness of malignant cells.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05789394
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05698524 - A Phase I Study of Metronomic Temozolomide With Abexinostat (PCI-24781) for Patients With Recurrent High Grade Glioma (PHASE1, RECRUITING): Glioblastoma (GBM), WHO grade IV glioma, represents the majority of adult malignant primary brain tumors, with an incidence of 2-3 per 100,000 person-years. The survival for GBM has increased in the last decade but is still low with a median survival of 15-18 months. Recurrence after initial standard therapy, radiation therapy and chemotherapy with temozolomide, few options are available. Even with further therapy, median progression free survival at 6 months after first relapse (PFS-6) is only 15%. Similarly, anaplastic astrocytoma and anaplastic oligodendroglioma, grade III gliomas, once recurrent after radiation therapy and first-line chemotherapy, have identical therapeutic options and poor outcomes with PFS-6 of 31%. Temozolomide (TMZ) has a favorable side effect profile and is available orally, however, cytotoxicity occurs. Metronomic temozolomide at low doses on a continuous schedule, have demonstrated better survival in studies. This study will determine the recommended dose and the side effects of PCI-24781/Abexinostat with metronomic temozolomide.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05698524
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT05095441 - A Phase 1 Open-Label Study of Genetically Engineered Oncolytic HSV-1 (C5252) Expressing IL-12 and Anti-PD-1 Antibody in Patients With Recurrent or Progressive Glioblastoma (PHASE1, NOT_YET_RECRUITING): This is a Phase 1 open label, first in human study of C5252 monotherapy designed to determine the safety and tolerability of a single intratumoral (IT) injection of C5252 in patients with recurrent or progressive glioblastoma (GBM).
  Quick read: GBM-related treatment study for recurrent GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05095441
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT04991870 - A Phase I Clinical Trial With a Window-of-Opportunity Component of Engineered NK Cells Containing Deleted TGF-ßR2 and NR3C1 in Recurrent Grade 4 Astrocytoma (Glioblastoma) (PHASE1, RECRUITING): This phase I trial is to find out the best dose, possible benefits and/or side effects of engineered natural killer (NK) cells containing deleted TGF-betaR2 and NR3C1 (cord blood \[CB\]-NK-TGF-betaR2-/NR3C1-) in treating patients with glioblastoma that has come back (recurrent). CB-NK-TGF-betaR2-/NR3C1- cells are genetically changed immune cells that may help to control the disease.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04991870
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04541082 - A First-in-human Phase I Single-agent Dose-escalation, Food Effect and Dose Expansion Study of Oral ONC206 in Recurrent and Rare Primary Central Nervous System Neoplasms (PHASE1, RECRUITING): The primary objective of this Phase 1, open-label, dose-escalation, and exploratory study is to evaluate the safety and tolerability profile (establish the maximum-tolerated dose) and evaluate the occurrence of dose-limiting toxicities (DLTs) following single weekly or multiple-day weekly dose regimens of single-agent, oral ONC206 in patients with recurrent, primary central nervous system (CNS) neoplasms.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04541082
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT04181684 - Pilot Study of Laser Interstitial Thermal Therapy Followed By Hypofractionated Radiation Therapy for Treatment of Recurrent Gliomas. (NA, RECRUITING): The purpose of this study is to evaluate the treatment regimen of using Laser Interstitial Thermal Therapy (LITT) and Hypo-fractionated Radiation Therapy to treat patients with recurrent gliomas.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04181684
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 22 (match), kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT02800486 - Phase II Trial of Super Selective Intra-arterial Repeated Infusion of Cetuximab (Erbitux) With Reirradiation for Treatment of Relapsed/Refractory Glioblastoma Multiforme, Anaplastic Astrocytoma, and Anaplastic Oligoastrocytoma (PHASE2, RECRUITING): Primary brain tumors are typically treated by surgery, radiation therapy and chemotherapy, either individually or in combination. Present therapies are inadequate, as evidenced by the low 5-year survival rate for brain cancer patients, with median survival at approximately 12 months. Glioma is the most common form of primary brain cancer, afflicting approximately 7,000 patients in the United States each year. These highly malignant cancers remain a significant unmet clinical need in oncology. GBM often has a high expression of EFGR (Epidermal Growth Factor Receptor), which is associated with poor prognosis. Several methods of inhibiting this receptor have been tested, including monoclonal antibodies, vaccines, and tyrosine kinase inhibitors. The investigators hypothesize that in patients with recurring GBM, intracranial superselective intra-arterial infusion of Cetuximab (CTX), at a dose of 250mg/m2 in conjunction with hypofractionated radiation, will be safe and efficacious and prevent tumor progression in patients with recurrent, residual GBM.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02800486
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT07100730 - A Global, Multicenter, Prospective, Controlled, Open-Label Pivotal Study of Iodofalan (131I) Solution for Injection (TLX101-Tx) Plus Lomustine Versus Lomustine Alone in Patients With Radiographically Confirmed Recurrent Glioblastoma at First Recurrence (IPAX BrIGHT [IPAX-3]) (PHASE3, RECRUITING): This global clinical trial which evaluates the efficacy and safety of TLX101-Tx, an investigational radiopharmaceutical therapy, in combination with lomustine versus lomustine alone in adult patients with first recurrence of glioblastoma. TLX101-Tx delivers targeted radiation to glioblastoma cells. The trial is conducted in two parts: Part 1 assesses safety and radiation dosing; Part 2 is a randomized comparison of the combination therapy against standard care.
  Quick read: GBM-related treatment study for first-recurrence GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07100730
  Review priority: 143
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), recurrence_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease, Matched inclusion factor: first_recurrence
- NCT06975332 - Medical Experiment - Assessment of Efficacy & Safety of Local, Targeted Therapy With Neuropeptide Labelled With Alpha Emitter [225Ac]Ac-DOTA-SP (TAT) as Supplementary Therapy in Glioma (WHO G3-G4) Progression (NA, RECRUITING): Brain tumors account for 1.35% of all cancers and cause 2.2% of cancer-related deaths. Gliomas are the most common type, comprising 40-90% of central nervous system tumors in different age groups. The incidence of malignant gliomas is approximately 0.5-2 per 100,000 people annually. Standard treatments include surgical resection, radiotherapy, and chemotherapy, yet overall survival remains low, typically 1-3 years post-diagnosis. The study highlights the pressing need for novel treatment strategies, particularly given the infiltrative nature of gliomas and the potential for targeted therapies using neuropeptides. The aim of this study is to assess the efficacy and safety of local targeted therapy with \[225Ac\]Ac-DOTA-SP in recurrent glioblastoma. It is an interventional study without a control group, initiated by the researcher. Patients included are aged 18-80 with recurrent WHO G3-G4 glioma post-first-line treatment, not requiring immediate surgery and meeting specific MRI progression criteria. Patients will receive a maximum of six cycles of \[225Ac\]Ac-DOTA-SP, involving pre-treatment assessments, local administration of the agent after ensuring catheter patency, and continuous monitoring. Blood tests and neurological evaluations will be performed regularly. Outcome will be assessed by measuring overall survival (OS) and progression-free survival (PFS). The study anticipates improvements in both OS and PFS when compared to current treatments, contributing to critical insights into targeted alpha therapy's effectiveness in glioblastoma. Treatment with \[225Ac\]Ac-DOTA-SP previously indicated few significant side effects, primarily transient issues like seizures. Patients will be closely monitored throughout the study to identify any adverse effects promptly. The estimated study duration is three years, with biological material collected for histopathological and genetic analysis during surgical reoperation. Data will be anonymized to protect patient confidentiality, stored securely, and made available only for the scope of the study. Led by Prof. Przemysław Kunert, the research team includes multiple co-investigators from neurosurgery and nuclear medicine departments.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06975332
  Review priority: 143
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07459101 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-4 (UNITED-4): Prospective Evaluation of FLAIR-Guided Clinical Target Volume Reduction (NA, RECRUITING): This study builds on the results of prior studies (UNITED and UNITED-3). The goal of UNITED-4 is to test whether an adaptive radiation therapy (RT) therapy approach ('dose painting'), with reduced margins, impacts approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive RT approach with reduced margins compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life * Longitudinal imaging features
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07459101
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06418113 - Neoadjuvant Radio-chemotherapy Safety Pilot Study in Patients With Glioblastoma (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and efficacy of neoadjuvant radiochemotherapy in the surgical resection of glioblastoma (GBM). The main questions it aims to answer are: * What is the safety profile of neoadjuvant radiochemotherapy in terms of neurological deficit, radionecrosis, edema, headache, wound dehiscence, infection, and cerebrospinal fluid fistula? * What is the efficacy of neoadjuvant radiochemotherapy in terms of progression-free survival, overall survival, cognitive function, and quality of life? Participants will undergo the following tasks and treatments: * Stereotactic biopsy and diagnosis confirmation. * Conformal hypofractionated stereotactic radiotherapy with concurrent temozolomide. * Supramarginal resection guided by 5-ALA under intraoperative neurophysiological monitoring. * Maintenance temozolomide administration for 6 months. Researchers will compare the group receiving neoadjuvant radiochemotherapy to the control group following the standard Stupp protocol to assess safety and efficacy outcomes.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06418113
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06356883 - A Randomized Phase II Study on Intraarterial Carboplatin Combined With Caelyx Compared to Intraarterial Carboplatin Combined With Etoposide Phosphate for Progressing Glioblastoma at First or Second Relapse (PHASE2, RECRUITING): The standard of care for glioblastoma (GBM) treatment involves maximal resection followed by concomitant radiotherapy and temozolomide. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is inevitable. At relapse, there is no consensus regarding the optimal therapeutic strategy. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which impedes drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, can produce responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival (OS) 23 months. How can the OS and PFS be improved? By combining chemotherapeutic agents with different mechanisms of action. Study design: In this phase II trial, treatment will be offered at relapse. Surgery will be performed for cytoreduction if it is warranted, followed with a combination IA carboplatin + IA Cealyx (liposomal doxorubicin) or IA carboplatin + IA etoposide phosphate. Toxicity will be assessed according to the NCIC common toxicity criteria. Treatment will consist in either IA carboplatin (400 mg/m\^2) + IA Cealyx (30 mg/m\^2) or IA carboplatin (400 mg/m\^2) + IA etoposide phosphate (400 mg/m\^2) every 4-6 weeks (1 cycle). Up to twelve cycles will be offered. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. Primary outcome will PFS and tumor response. Secondary outcome will include median OS, toxicity, quality of life (QOL), neurocognition (NC). Putting together these data will allow to correlate clinical and radiological response to QOL and NC.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06356883
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06186401 - Phase 1 Study of Autologous Anti-EGFRvIII synNotch Receptor Induced Anti-EphA2/IL-13R alpha2 CAR (E-SYNC) T Cells in Adult Participants With EGFRvIII+ Glioblastoma (PHASE1, RECRUITING): This phase I trial tests the safety, side effects, and best dose of E-SYNC chimeric antigen receptor (CAR) T cells after lymphodepleting chemotherapy in treating patients with EGFRvIII positive (+) glioblastoma. Chimeric antigen receptor (CAR) T-cell therapy is a type of treatment in which a patient's T cells (a type of immune system cell) are changed in the laboratory so the CAR T cells will attack cancer cells. T cells are taken from a patient's blood. Then the gene for a special receptor that binds to a certain protein on the patient's cancer cells is added to the T cells in the laboratory. The special receptor is called a chimeric antigen receptor. Large numbers of the CAR T cells are grown in the laboratory and given to the patient by infusion for treatment of certain cancers. Lymphodepleting chemotherapy with cyclophosphamide and fludarabine before treatment with CAR T cells may make the CAR T cells more effective.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06186401
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05106296 - Repurposing Ibrutinib for Chemo-Immunotherapy in a Phase 1b Study of Ibrutinib With Indoximod Plus Metronomic Cyclophosphamide and Etoposide for Pediatric Patients With Brain Cancer (PHASE1, RECRUITING): Recent lab-based discoveries suggest that IDO (indoleamine 2,3-dioxygenase) and BTK (Bruton's tyrosine Kinase) form a closely linked metabolic checkpoint in tumor-associated antigen-presenting cells. The central clinical hypothesis for the GCC2020 study is that combining ibrutinib (BTK-inhibitor) with indoximod (IDO-inhibitor) during chemotherapy will synergistically enhance anti-tumor immune responses, leading to improvement in clinical response with manageable overlapping toxicity. The GCC2020 trial is a prospective open-label phase 1 trial to determine the best safe dose of the BTK-inhibitor ibrutinib to use in combination with previously studied chemo-immunotherapy regimens comprised of the investigational IDO-inhibitor indoximod plus oral palliative chemotherapy for participants, age 6 to 25 years, with relapsed or refractory primary brain cancer. Those previously treated with indoximod-based therapy may be eligible, including prior treatment via the phase 2 indoximod study (GCC1949, NCT04049669), the now closed phase 1 study (NLG2105, NCT02502708), or any expanded access (compassionate use) protocols. Ibrutinib will be combined with either indoximod plus oral cyclophosphamide and etoposide (Regimen A) or indoximod plus oral temozolomide (Regimen B). No cross-over between these two regimens will be allowed. Dose-escalation cohorts will determine the best safe dose of ibrutinib for each of these regimens. This will be followed by expansion cohorts, using ibrutinib at the best safe dose for each regimen, to allow assessment of preliminary evidence of efficacy.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05106296
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT04678648 - A Phase Ia/Ib, Open Label, Multi-center, Non-randomized Dose Escalation and Dose Expansion Study of RSC-1255 Alone or in Combination With Hydroxychloroquine in Patients With Advanced Solid Tumor Malignancies (PHASE1, RECRUITING): RSC-101 is a Phase 1a/1b clinical trial of RSC-1255 in adult study participants with advanced solid tumor malignancies who are intolerant of existing therapies known to provide clinical benefit, have disease that has progressed after standard therapy, or have previously failed other therapies. The study has two phases. The purpose of Phase 1a (Dose Escalation) is to confirm the appropriate treatment dose and Phase 1b (Dose Expansion) is to characterize the safety and efficacy of RSC-1255.
  Quick read: GBM-related treatment study for GBM or glioma patients; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04678648
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT04623931 - Phase II Trial of Treatment Intensification for IDH Wildtype, Non-Histological Glioblastoma, Gliomas (IDH Wildtype Lower Grade Glioma Treatment Intensification) (PHASE2, RECRUITING): This phase II trial studies how well temozolomide and radiation therapy work in treating patients with IDH wildtype historically lower grade gliomas or non-histological molecular glioblastomas. Radiation therapy uses high-energy x-rays to kill tumor cells and shrink tumors. Giving chemotherapy with radiation therapy may kill more tumor cells. Drugs used in chemotherapy, such as temozolomide, work in different ways to stop the growth of tumor cells, either by killing the cells, by stopping them from dividing, or by stopping them from spreading. The goal of this clinical research study is to compare receiving new radiation therapy doses and volumes to the prior standard treatment for patients with historically grade II or grade III IDH wild-type gliomas, which may now be referred to as IDH wildtype molecular glioblastomas at some institutions. Receiving temozolomide in combination with radiation therapy may also help to control the disease.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04623931
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT03672721 - A Phase II Study in Relapsing Glioblastoma of Intraarterial Concurrent Chemoradiation Therapy Using IA Carboplatin (PHASE1, PHASE2, RECRUITING): Treatment of glioblastoma involves an optimal surgery, followed by a combination of radiation and temozolomide chemotherapy. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is the norm. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which limits drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, the investigators have observed responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival 23 months. How can this be improved? By coupling radiation with a chemotherapeutic which is also a potent radiosensitizer such as carboplatin. Study design: In this phase I/II trial, patients will be treated at recurrence; a surgery will be performed for cytoreduction and to obtain tumor sample, followed with a combination of re-irradiation and IA carboplatin chemotherapy. A careful escalation scheme from 1.5Gy/fraction up to 3.5Gy/fraction will allow the investigators to determine the optimal re-irradiation dose (10 fractions of radiation over 2 weeks). Toxicity will be assessed according to the NCIC common toxicity criteria. Combined with radiation, patients will receive 2 treatments of IA carboplatin, 400 mg/m2, 4 hours prior to the first and the sixth radiation fraction. IA treatments will then be continued on a monthly basis, up to a total of 12 months, or until progression. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. The investigators will also acquire a sequence that enables the measurement of cerebral blood flow, cerebral blood volume and blood vessel permeability that are all relevant to understand the delivery of therapeutics to the CNS. Primary outcome will be OS and PFS. Secondary outcome will be QOL, neurocognition, and carboplatin delivery. In vitro intracellular carboplatin accumulation: Tumor samples from re-operation will be be analyzed for intracellular Pt concentration by ICP-MS. The amount of Pt bound to DNA will be measured. The level of apoptosis will be determined for each of the sample. Putting together these data will allow to correlate clinical and radiological response to QOL, NC (MOCA), and to delivery surrogates for the IA infusion and intracellular penetration of carboplatin.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03672721
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06623565 - Multimodal Image-guided Resection of IDH Wildtype Glioblastoma and Grade IV IDH-mutant Astrocytoma (NA, RECRUITING): Rationale: Patients with IDH-wildtype glioblastoma or grade IV IDH-mutant astrocytoma have a very poor prognosis despite standard treatment consisting of surgery, radiotherapy, and chemotherapy. Diffuse infiltration of the brain by the tumor is thought to be one of the main causes of this therapy-resistance. In order to improve the surgical treatment, tumor regions with lower infiltration percentages need to be identified and resected during surgery, a so-called supramarginal resection. Currently, pre-operative T1 contrast enhanced weighted (T1c) MRI is used to identify the tumor for resection. We recently found the combination of apparent diffusion coefficient MRI and O-(2-\[ 18F\]fluoroethyl-)-L-tyrosine positron emission tomography (ADC/FET) to be significantly more accurate than T1c MRI alone in the detection of tumor infiltration. This makes ADC/FET a suitable candidate to guide supramarginal resection. Since FET PET is not as accessible and widely available as MRI, identification of an MRI based alternative could result in a more widespread implementation. Amide proton transfer chemical exchange saturation transfer (APT-CEST) MRI is a novel potential alternative for FET PET, since both measures are related to protein content. Objective: In this project we aim to develop a safe and effective technique for ADC/FET guided resection of IDH-wildtype glioblastoma and grade IV IDH-mutant astrocytoma. The safety concerns neurological deficits and time to start of adjuvant therapy, while the effectiveness is aimed at the extent of resection. Our secondary aim is to evaluate the diagnostic accuracy of APT-CEST MRI and to assess whether APT-CEST MRI can serve as an alternative for FET PET for the detection of tumor infiltration. Study design: prospective observational intervention study Study population: 30 patients with clinical and radiological diagnosis of an untreated high grade glioma (suspected for glioblastoma (IDH wildtype) or grade IV astrocytoma (IDH mutant)), who are eligible for a supramarginal surgical resection and adjuvant treatment according two neurosurgeons in consensus and who are in relatively good condition (Karnofsky Performance Score (KPS) ≥70). Intervention (if applicable): supramarginal ADC/FET-guided resection. To make sure that the standard treatment is always guaranteed, T1c MRI abnormalities will be included in the surgical target. Main study parameters/endpoints: the main study endpoint is the optimization of ADC/FET-guided resection. Volumetric and percentual extent of resection, as measured with MRI and PET imaging, combined with surgery-induced morbidity will be used as outcome parameters. The secondary study parameters will be the histopathology-based diagnostic accuracy of APT-CEST MRI in comparison with FET PET, cognitive performance over time and progression free survival. Nature and extent of the burden and risks associated with participation, benefit and group relatedness: participants will undergo pre- and postoperative MRI scanning. This is also part of regular clinical care, except there are additional MRI sequences including APT CEST in the pre-operative and pre-radiotherapy MRI. There are no risks associated with MRI acquisition after MRI safety screening. Participants will furthermore undergo a pre- and postoperative FET PET. The risks associated with PET scanning are limited, and the radiation burden will remain below 10 mSv (ICRP62 category intermediate risk (level IIb)). During surgery, biopsies are performed from areas that will be resected, so these biopsies will not introduce any extra risk. A potential benefit is the possibility of the removal of more tumor tissue. A potential risk is the additional removal of healthy brain tissue with the risk of neurological damage, which is controlled by pre- and intraoperative techniques such as visualization of white matter tracts and mapping (both asleep and awake) of critical functions such as language and control of strength.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06623565
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05990556 - Research on the Safety and Efficacy of Blocking Dural Blood Supply in Glioblastoma Patients (NA, RECRUITING): Glioblastoma is the most common primary malignancy of the central nervous system with a very poor prognosis. Most of the immunotherapies that have made significant breakthroughs in the treatment of other tumors in recent years are unsatisfactory in the application of glioblastoma, which is mainly inseparable from the highly inhibitory immune microenvironment formed by the latter. Therefore, how to change this "immune desert" and better activate immune effector cells to play an anti-tumor effect is currently a hot spot in glioma immune research. In recent years, there has been continuous research support that the myeloid cells of the central nervous system are partly derived from the bone marrow of the skull, and there is a special channel connection between the skull and the dura mater, through which immune cells can be transported. This suggests that some of the tumor-associated macrophages recruited in the glioblastoma microenvironment may be passed through the dura mater. In previous animal experiments, we blocked the main blood supply to the dura mater by ligating the bilateral external carotid arteries of mice, cutting off the potential supply of dura mater to suppressor myeloid cells in the lesion. The results showed that after ligation of bilateral external carotid arteries, the survival period of tumor-forming mice was significantly prolonged and the prognosis was improved. The proportion of myeloid cells in the tumor microenvironment of mice decreased significantly, and the expression of tumor suppressor molecules such as arginase Arg1 decreased, indicating that the improvement of mouse prognosis was closely related to the proportion and phenotypic changes of myeloid cells after dural blood supply blockade. The meningeal lymphatic system of the human central nervous system has been shown to be an important part of the immune system, while the external carotid artery system, the main source of blood supply to the dura, carries abundant immune cells that ooze out to the dura mater through the endothelial window hole of the dural blood vessel, which is an important source of dural immune cells. In the glioblastoma immune microenvironment, the source of immune cells includes dural branches from the external carotid artery system in addition to branches of the internal carotid artery system. Therefore, for patients diagnosed with glioblastoma, this study involves embolization of the dural branch of the external carotid artery system (bilateral middle meningeal artery) to block the dural blood supply before craniotomy. At the same time, microsurgery under multimodal image navigation was used to remove the tumor. It is expected to be effective in reducing the proportion of myeloid suppressor cells in the tumor microenvironment, slowing the growth rate of residual tumor cells, and prolonging the tumor-free progression and survival of patients.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05990556
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT03958240 - Deciphering Mechanisms Underlying Cancer Immunogenicity (NA, RECRUITING): This trial is a translational, open-label, multicentric, prospective cohort study of 1100 patients aiming to describe the PD-1 (programmed death) expression in T cells (T lymphocytes) in different solid tumors. The study will be conducted on a population of patients with local and/or metastatic malignant solid tumor and who are followed within a standard of care procedure or clinical trial. Patients with any of the following tumor types may be enrolled in the trial: * Head and neck cancer, * Ovarian cancer, * Cervical cancer, * Pre-invasive CIN III cervical cancer (Cervical Intra-epithelial Neoplasia III cervical cancer), * Other solid tumor types (including glioblastoma, NSCLC (Non-small cell lung cancer), anal cancer) Each tumor type will be considered as an independent cohort. For each included patient, biological specimen (tumor sample, blood samples and ascites samples if applicable) will be collected. Study participation of each patient will be 5 years.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03958240
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06804655 - Pharmacoscopy for Patients With Refractory Primary Brain Tumors (PHASE2, NOT_YET_RECRUITING): Advanced technology of ex vivo drug profiling referred to as pharmacoscopy may allow to identify novel drugs for the treatment of glioblastoma and other refractory brain tumors at an individual patient level. This personalized therapeutic approach was developed and validated in pre-clinical glioma models. With the current research proposal, we seek to establish feasibility for a clinical interventional trial for patients with refractory primary brain tumors that is based on pharmacoscopy-guided selection of treatment. The study is supported by an unrestricted grant from Anti Cancer Fund.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06804655
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT06455189 - Magnetic Resonance Fingerprinting Guided Extended Resection in Glioblastomas (PHASE1, NOT_YET_RECRUITING): Magnetic resonance imaging, MRI, is a procedure that uses radio waves, a powerful magnet, and a computer to make a series of detailed pictures of areas inside the body. The goal of this study is to determine if MR fingerprinting, new way of acquiring MRI images, can help identify the extent of tumor spread in the brain, better than routine MRI images.
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06455189
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: recurrent_disease
- NCT06129760 - Glioblastoma Remote Monitoring and Care - Research Protocol (NA, RECRUITING): The purpose of this research is to learn more about how what the Apple watch measures, in terms of walking data, heart rate, breathing rate, and sleep habits, relates to how participants feel. During the course of the treatment, the symptoms participants experience change, and whether the Apple watch can detect these changes. Ultimately, this knowledge is being used to design proactive tools and signatures that can predict complications or symptom changes before they happen.
  Quick read: GBM-related treatment study for recurrent GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06129760
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 70 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: recurrent_disease
- NCT05283330 - A Phase 1 Open-Label, First-in-human, Dose Escalation and Expansion Study to Determine the Safety, Tolerability, Dosimetry, Pharmacokinetics, and Preliminary Efficacy of 212Pb-DOTAM-GRPR1 in Adult Participants With Recurrent or Metastatic GRPR-expressing Tumors (PHASE1, RECRUITING): A Phase 1 Open-Label, First-in-human, Dose Escalation and Expansion Study to Determine the Safety, Tolerability, Dosimetry, Pharmacokinetics, and Preliminary Efficacy of 212Pb-DOTAM-GRPR1 in Adult Participants with Recurrent or Metastatic GRPR-expressing Tumors
  Quick read: GBM-related treatment study for recurrent GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05283330
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: recurrent_disease
- NCT07493447 - Pilot Study Evaluating Panitumumab-IRDye800 as an Optical Imaging Agent to Detect Intracranial Lesions During Neurosurgical Procedures (EARLY_PHASE1, NOT_YET_RECRUITING): This pilot clinical study evaluates the safety and imaging performance of panitumumab-IRDye800 (pan800), a fluorescent, EGFR-targeted imaging agent - in patients undergoing neurosurgical resection of intracranial lesions.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07493447
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=58 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06929819 - Research on the Safety and Efficacy of Intraoperative Radiation Therapy in Malignant Cerebral Tumor (NA, NOT_YET_RECRUITING): According to the latest national cancer statistics released by the National Cancer Center in February 2022, intracranial tumors account for about 60%-70% of the more than 3.5 million cancer patients, and the morbidity and mortality remain high. Intracranial malignant tumors have become a problem that needs to be solved urgently because of their early recurrence, rapid progression, and short survival, and intracranial malignant tumors include high-grade gliomas, metastases, lymphomas, etc. Glioblastoma (GB) is the most common primary malignancy in the adult central nervous system, accounting for about 57% of all gliomas and 48% of all primary weighted nervous system malignancies. At present, the standard treatment for glioblastoma is mainly surgical treatment, supplemented by postoperative concurrent chemoradiotherapy and adjuvant chemotherapy, but the prognosis of patients is still poor, with a one-year survival rate of 40.6%, a five-year survival rate of only 5.6%, and an average survival time of 12-15 months. For patients diagnosed with intracranial malignancies (including high-grade glioma, metastases, lymphoma, etc.), multimodal image-guided microsurgery combined with postoperative chemoradiotherapy recommended by the guidelines, and intraoperative radiotherapy with tumor bed radiation therapy to achieve targeted and precise tumor treatment, thereby improving the prognosis of patients (including progression-free survival and median overall survival, etc.)
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06929819
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good
- NCT06492486 - Glioma Adaptive Radiotherapy With Development of an Artificial Intelligence Workflow (PHASE2, NOT_YET_RECRUITING): Gliomas are common primary brain tumors in adults. Gliomas can be classified into different types based on tumor grade, histopathological features, and molecular characteristics. The common types of diffuse gliomas include glioblastoma, astrocytoma, and oligodendroglioma. The standard treatment for diffuse gliomas includes surgery followed by radiation and chemotherapy. As per standard institutional practice, a uniform dose of radiation is delivered to the disease area and MRI is done before and after the treatment. In this study, MRI and PET scan will be done before starting the treatment and standard dose of radiation will be delivered. The interval imaging will be done twice during the course of treatment with MRI and PET, followed by dose modifications. The CT, MRI, and PET will be combined. Based on PET imaging, specific dose will be altered and delivered to specific areas. Dose modification will be done with the help of artificial intelligence. Participant's assessment will be done at regular intervals. Modifications in radiation plans are done based on the changes in disease seen in scans is likely to improve the accuracy of RT treatments. Dose modifications based on imaging to resistant areas will help achieve better tumor control, reduce treatment-related toxicities, precise delivery of the RT and adjusting doses to the organs at risk (OAR) and changes in disease leading to better treatment compliance. Creating an artificial intelligence framework in radiation oncology promises to improve quality of workflow, treatment planning and RT delivery. The aim of the study is to develop an artificial intelligence workflow for treatment of glioma with adaptive radiotherapy. This study will be conducted in Tata Memorial Centre on a population of 60 patients for a duration of 2 years. The total study duration is 4 years.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06492486
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=70 vs 60 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07384884 - Surgery and Laser Interstitial Thermal Therapy for Bilateral Glioblastomas (NA, NOT_YET_RECRUITING): Butterfly glioblastomas (bGBM), defined as tumours crossing the midline to involve hemispheres bilaterally, have a dismal prognosis with a median survival of 3.3-6 months and only 9% of patients with bGBM survive 2-years. These figures put bGBM in the worst end of the spectrum of GBM prognosis, significantly inferior to the survival figures quoted in the literature with standard of care - 14.6 months - particularly when 5-aminolevulinic acid is used as surgical adjuvant - 17.47 months. Despite the poor outcome of this disease, there is preliminary evidence suggesting that active oncology treatment can impact the survival of patients with this condition.With particular regards to surgical resection versus biopsy, there is a suggestion that resection improves overall survival at 6 months with no clear difference at 12 and 18 months of follow up. Laser-induced thermal therapy (LITT) is a minimally invasive laser ablation technique used in a range of brain tumours, including glioblastomas, with similar overall survival to the ones reported for open surgery in patients with lesions not amenable to open resection. The minimally invasive nature of this technique, significantly reducing the collateral damage to the surrounding brain structures, suggests Its potential in the treatment of this bGBM \[14\] with significant implications as a deficit-sparing technique, particularly if associated with preoperative and intraoperative monitoring and mapping techniques. The SLITT-GBM study will combine unilateral open surgery for maximal tumour resection with contralateral LITT to the smaller component/residual.
  Quick read: GBM-related treatment study for GBM or glioma patients; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07384884
  Review priority: 134
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none

#### Related Papers
- PMID:40578479 - Radiation Therapy for WHO Grade 4 Adult-Type Diffuse Glioma: An ASTRO Clinical Practice Guideline.
  Quick read: Guideline-style reference for GBM-specific, recurrent, focused on radiation, temozolomide, biomarker in Practical radiation oncology (2025).
  Source: https://pubmed.ncbi.nlm.nih.gov/40578479/
- PMID:37059335 - ESTRO-EANO guideline on target delineation and radiotherapy details for glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2023).
  Source: https://pubmed.ncbi.nlm.nih.gov/37059335/
- PMID:35426875 - Congress of Neurological Surgeons Systematic Review and Evidence-Based Guidelines on the Management of Progressive Glioblastoma in Adults: Update of the 2014 Guidelines.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Neurosurgery (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35426875/
- PMID:35246769 - Congress of neurological surgeons systematic review and evidence-based guidelines update on the role of cytoreductive surgery in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35246769/
- PMID:35195819 - Congress of Neurological Surgeons systematic review and evidence-based guidelines update on the role of cytotoxic chemotherapy and other cytotoxic therapies in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35195819/
- PMID:29086250 - SEOM clinical guidelines for diagnosis and treatment of glioblastoma (2017).
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Clinical & translational oncology : official publication of the Federation of Spanish Oncology Societies and of the National Cancer Institute of Mexico (2018).
  Source: https://pubmed.ncbi.nlm.nih.gov/29086250/
- PMID:27907278 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of oncology practice (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27907278/
- PMID:27893327 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of clinical oncology : official journal of the American Society of Clinical Oncology (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27893327/
- PMID:26777122 - ESTRO-ACROP guideline "target delineation of glioblastomas".
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2016).
  Source: https://pubmed.ncbi.nlm.nih.gov/26777122/
- PMID:25079102 - EANO guideline for the diagnosis and treatment of anaplastic gliomas and glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in The Lancet. Oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/25079102/
- PMID:24756348 - The role of cytoreductive surgery in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24756348/
- PMID:24740195 - The role of targeted therapies in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24740195/

#### Related Datasets
- gdc_tcga_gbm - NCI GDC TCGA-GBM
  Quick read: Core GBM tumor-genomics program with somatic variants, copy-number, expression, methylation, and linked clinical metadata; open and controlled-access layers.
  Source: https://gdc.cancer.gov/about-data/publications/gbm_2013
- gdc_tcga_lgg_gbm - NCI GDC TCGA Pan-Glioma Cohorts
  Quick read: Combined glioma genomics across lower-grade glioma and GBM for broader IDH, MGMT, and progression-context comparisons.
  Source: https://portal.gdc.cancer.gov/
- ivy_gap - Ivy Glioblastoma Atlas Project
  Quick read: Region-resolved glioblastoma atlas with anatomic and molecular context across tumor subregions.
  Source: https://glioblastoma.alleninstitute.org/
- cbioportal_gbm - cBioPortal GBM Studies
  Quick read: Searchable GBM and glioma genomics knowledgebase spanning TCGA and many published studies with mutation, CNA, and outcome views.
  Source: https://www.cbioportal.org/
- cptac_gbm - CPTAC Brain / Glioblastoma Proteogenomic Resources
  Quick read: Proteomic and proteogenomic tumor data relevant to GBM biology and pathway activation beyond DNA-only signals.
  Source: https://proteomics.cancer.gov/programs/cptac

#### Missing Evidence
- HLA typing available: HLA typing lab result.
  Missing artifact types: hla_typing_result

### Minimal Workup
- Case ID: `case_minimal_workup`
- Patient: `synthetic-004`
- Evidence package: 2 ready / 6 missing
- Standard-care paths to discuss: 0
- Trial candidates for review: 36
- Trials needing more evidence: 64
- Bitmask: `231`

#### Recommended Care Pathways

#### Candidate Trials
- NCT07284069 - Phase 0/1 Randomized Clinical Trial of SENIcapoc and PERAmpanel Mono- and Combination Therapy of Newly Diagnosed Glioblastoma (EARLY_PHASE1, RECRUITING): Glioblastoma is the most common and aggressive form of brain cancer in adults. Despite surgery, radiotherapy, and chemotherapy, most patients only live about one year after diagnosis. There is an urgent need for new and better treatments. Recent research has shown that glioblastoma cancer cells communicate with surrounding brain cells through electrical signals that help the tumor grow and resist treatment. Two existing drugs, perampanel (used for epilepsy) and senicapoc (previously tested for blood disorders), may block these harmful signals. Laboratory studies suggest that combining these two drugs could slow tumor growth and make cancer cells more sensitive to standard therapy. The SENIPERA trial will test whether perampanel and senicapoc, alone and in combination, are safe and well tolerated when added to standard treatment for newly diagnosed glioblastoma. The study will also measure how well these drugs reach the brain and tumor, and how they affect tumor biology. The study has two parts: Part A: Tests different doses of senicapoc alone to find the maximum tolerable dose. Part B: Randomly assigns patients to receive either perampanel alone or perampanel together with senicapoc. Participants will all receive standard therapy, including surgery, radiochemotherapy, and adjuvant chemotherapy. During surgery, small samples of tumor and fluid will be collected safely to study how the drugs act in the body and how tumor cells respond. Participants will be closely monitored for side effects and followed with regular clinical visits and MRI scans. The trial will take place at Aarhus University Hospital, Denmark, from February 2026 to November 2028 and will enroll 27-36 adult patients. The study aims to identify safe and biologically active treatment combinations that could be tested in larger trials to improve future glioblastoma care.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07284069
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07195591 - Randomized Study of Resection and GammaTile® Followed by Concurrent External Beam Radiation Therapy (EBRT) and Temozolomide (TMZ) and Adjuvant TMZ Versus Standard of Care in Newly Diagnosed Glioblastoma (GBM) (PHASE3, RECRUITING): This is a Phase 3 prospective, randomized, superiority, open-label, multi-site study. The overview of this study is as follows: * A Screening/Baseline Period of 21 days. During this time, patients will be randomized into a 1:2 allocation of Arm A:Arm B. * A Perioperative/Operative Phase where patients will undergo tumor resection (Arm A) or tumor resection plus GammaTile implantation (Arm B). * An EBRT Prior to Start Period. This occurs within 10 business days prior to EBRT and Concurrent TMZ Phase. * An EBRT and Concurrent TMZ Phase, which will begin 30 ±10 days post-surgery. EBRT (30 fractions) and TMZ will be administered up to 5 days a week for 6 weeks in Arm A, and EBRT (20 fractions) and TMZ will be administered for up to 5 days a week for 4 weeks in Arm B. TMZ will be administered at a dose of 75 mg/m2/day orally for each Arm. * An Adjuvant TMZ Phase, which begins 28 ±7 days following the EBRT and Concurrent TMZ Phase, and is comprised of six 28-day cycles. TMZ (150-200 mg/m2/day orally) will be administered for the first 5 days of each 28-day cycle for each Arm. Tumor treating fields are allowed but are not mandated during this phase. Up to 6 additional cycles (for a total of 12) can be completed at the discretion of the Investigator. * An Early Discontinuation/Follow-Up Phase will occur 28 ±7 days after completion of Cycle 6 of the Adjuvant TMZ Phase, regardless of the total number of cycles completed or any delays in cycle start. If fewer than six cycles are completed, the first follow-up assessment will occur 28 ±7 days after the last administered dose of adjuvant TMZ. If patient has a qualifying event requiring entrance to Early Discontinuation Phase, the first follow-up assessment will occur as soon as feasible, but within 28 days. For any unscheduled visits, data collected should be documented in the case report form (CRF) and must include, but are not limited to, safety evaluations, survival status, and disease status.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07195591
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=67 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07193654 - Stupp Regimen Combined With Intrathecal Injection of Thiotepa for the Treatment of Glioblastoma With Ventricular Invasion or Meningeal Metastasis：a Prospective, Single-Arm, Exploratory Study (PHASE2, RECRUITING): The goal of this clinical trial is to learn if a combined treatment approach can treat glioblastoma (GBM) with ventricular invasion or meningeal metastasis in adults. The main questions it aims to answer are: Does the combined treatment of radical radiotherapy, the Stupp regimen (oral temozolomide), and intrathecal injection of thiotepa improve progression-free survival compared to standard treatment alone? Does the combined treatment improve overall survival compared to standard treatment alone? Participants will: * Undergo maximal surgical resection of the tumor； * Receive radical radiotherapy； * Take oral temozolomide according to the Stupp regimen； * Receive intrathecal injections of thiotepa。
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07193654
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07143812 - Clinical Research of Suicide Gene Expressing Allogenic Bone Marrow Derived Mesenchymal Stem Cells(MSC11FCD) in Patients With Newly Diagnosed Glioblastoma (PHASE1, RECRUITING): This is a phase I clinical trial evaluating the safety, tolerability, and maximum tolerated dose of MSC11FCD, an investigational allogeneic bone marrow-derived mesenchymal stem cell therapy expressing a suicide gene, in patients with newly diagnosed glioblastoma. The investigational product is administered intratumorally following surgical resection. This study aims to explore whether MSC11FCD can provide a targeted, localized treatment option during the postsurgical period, potentially addressing residual tumor cells and reducing early recurrence.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07143812
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07130149 - Clinical Investigation of Sonodynamic Therapy in Conjunction With Chemoradiotherapy for Glioblastoma Management (PHASE2, ENROLLING_BY_INVITATION): This Phase II trial tests if sonodynamic therapy (SDT)-a non-invasive treatment using ultrasound to activate a cancer-killing drug-improves outcomes for newly diagnosed glioblastoma patients. Who? 230 adults (\<75 years) with confirmed glioblastoma, adequate organ function, no major health issues. Groups: Test Group: SDT + standard therapy (radiation, chemo, bevacizumab). Control Group: Standard therapy alone. Procedure: SDT uses the drug Hiporfin® followed by focused ultrasound sessions. Patients avoid sunlight for 1 month. Study Duration: Treatment: \~6-8 weeks. Follow-up: 24 months (monthly MRIs). Key Goal: Compare progression-free survival (time until tumor worsens) between groups. Secondary goals: overall survival, safety.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; limited-enrollment.
  Source: https://clinicaltrials.gov/study/NCT07130149
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07047066 - A Phase II Clinical Study to Evaluate the Efficacy and Safety of Flazoparib Combined With Temozolomide After the Completion of Standard Concurrent Chemoradiotherapy (CCRT) in Newly Diagnosed Glioblastoma (PHASE2, NOT_YET_RECRUITING): A Phase II clinical study is planned to evaluate the efficacy and safety of fluzoparib combined with temozolomide in newly diagnosed glioblastoma patients after completing standard concurrent chemoradiotherapy (CCRT), explore the effectiveness and safety of this regimen, and find a better treatment option for glioblastoma patients
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07047066
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=67 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06936046 - Enhanced Adjuvant Therapy for Newly Diagnosed Glioblastoma With Partial Surgical Resection or Short-term Progression: a Bayesian Adaptive Randomized Phase II Study (PHASE2, RECRUITING): This study is a prospective Bayesian adaptive randomized phase II clinical trial of enhanced adjuvant therapy for newly diagnosed glioblastoma with partial surgical resection or short-term progression. The Stupp regimen is the standard treatment regimen (control group), while the experimental group receives enhanced treatment by combining different drugs or increasing the radiation dose based on the Stupp standard treatment regimen. Participants will undergo screening and evaluation according to the inclusion and exclusion criteria of the protocol, within 28 days prior to randomization. Patients who agree to participate in this study will sign an informed consent form (ICF) prior to the screening process. After completing all screening activities, those who meet the criteria can start receiving study treatment. Based on sample size estimation, a total of 210 patients are planned to be enrolled. Among the first 28 patients, an average of 7 patients will be allocated to each group for initial randomization to ensure the balance of each group in the early stages of the trial. Starting from the 29th patient, the 12-month PFS rate will be re estimated for every 15 patients enrolled, and the subsequent randomization probability will be calculated based on the observed data. On the first day of self adjuvant therapy, the PD-1/VEGF bispecific group received intravenous administration of PD-1/VEGF bispecific antibody 20mg/kg treatment, with 21 days per cycle, is expected to be administered for a total of 8 cycles. The PD-1/CTLA-4 dual antibody group received intravenous infusion of 6mg/kg PD-1/CTLA-4 dual antibody once on the first day of self adjuvant therapy, with 14 days per cycle. It is expected to be administered for a total of 12 cycles. The dose adjusted Stupp regimen group (mStupp) administered PGTV locally to residual or short-term recurrent lesions after surgery 66Gy/30Gy high-dose irradiation, PTV1 60Gy/30F in high-risk areas around the tumor bed, and 54Gy/30F radiotherapy in low-risk areas. Each group will have weekly blood routine, liver and kidney function, myocardial enzyme spectrum, thyroid function, electrocardiogram, and head MR every 4 weeks to evaluate the efficacy and toxic side effects. Follow up observation will be conducted. The study will start on January 1, 2025 and end on December 31, 2027, to explore the efficacy of enhanced adjuvant therapy for newly diagnosed glioblastoma with partial surgical resection or short-term progression.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06936046
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06477939 - Phase III Randomized Study of Adding or Not Liposomal Transcrocetin (L-TC) With Concomitant HypoFractionated Radiation ThErapy and TEmozolomide in Newly Diagnosed GLioblastoma (GBM) Patients to Evaluate Efficacy and Safety (PHASE3, NOT_YET_RECRUITING): This is phase III randomized, multicenter study adding or not intra-venous Liposomal Trasncrocetin (L-TC) to hypofractionated radiotherapy and concomitant Temozolomide followed by adjuvant Temozolomide in patients with histologically confirmed diagnosis of glioblastoma (GBM).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06477939
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05768087 - Escalated Dose Proton Therapy Within the Multimodality Treatment of Glioblastoma Patients - A Phase 1 Proton Dose Finding Trial - (NA, RECRUITING): The goal of this phase 1 dose finding study is to to assess the clinical tolerability and safety of escalated dose proton therapy in glioblastoma patients treated with multimodality treatment, according to treatment volume. The main questions it aims to answer are: * what is the maximum tolerated proton dose in glioblastoma patients? * is the maximum tolerated proton dose in glioblastoma patients dependent on treatment volume? * what is the recommended phase 2 proton dose in glioblastoma patients? Patients will be asked to undergo radiotherapy to step-wise escalated doses using proton therapy as part of their multimodality treatment. Patients will be monitored closely for treatment effects.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05768087
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=67 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05736406 - An Interventional, Multicenter, and International Phase 1/2, Light-dose-escalation Study to Investigate the Safety and Feasibility of Intraoperative Photodynamic Therapy (PDT) With Pentalafen® Drug and Heliance® Solution Device in Male and Female Patients 18 to 75 Years of Age With Grade IV Glioblastoma. (PHASE1, PHASE2, RECRUITING): The primary objective of this clinical trial is to determine the safety and tolerability of two doses of light in intraoperative PDT added to standard of care; temozolomide-based chemotherapy in male and female patients aged 18 to 75 with newly diagnosed glioblastoma. This treatment will be carried out in addition to the maximal surgical resection. Data collected during this trial will be used to design the upcoming pivotal study . The study will utilize an independent Data and Safety Monitoring Board (iDSMB) that will review safety data to allow dose escalation.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05736406
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05380349 - A Phase 1 Study of Combination Drug Therapy Based on Personalized Cancer Stem Cell (CSC) High-Throughput Drug Screening (HTS) With Standard of Care for Newly Diagnosed Glioblastoma (EARLY_PHASE1, RECRUITING): Proposed treatment of subjects with newly diagnosed glioblastoma with novel personalized drug regimens identified to be effective in vitro using cancer stem cells derived from their individual tumors, alongside standard of care radiation and TMZ.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05380349
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT02613988 - Early Response Assessment Using on 3T Advanced MR Imaging as Predictor of Long-term Treatment Response in Newly Diagnosed Glioblastomas (NA, RECRUITING): This clinical trial studies advanced MR imaging techniques in measuring early response of standard treatment may become predictors of long-term treatment response in patients with newly diagnosed glioblastomas.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02613988
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07492836 - Prospective, Pilot Study to Evaluate Hypofractionated Radiotherapy Associated With Temozolomide in Patients Aged 18 to 70 Years With Glioblastoma (HypoGBM) (NA, NOT_YET_RECRUITING): The goal of this clinical trial is to evaluate the feasibility, safety and effectiveness of radiotherapy with fewer days of treatment and a higher dose of radiation each day in patients under 70 years of age diagnosed with a brain tumor known as glioblastoma.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07492836
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07368283 - A Single-arm Phase II Non-inferiority Clinical Study of Limited Target Volume Radiotherapy After Glioblastoma Surgery (NA, NOT_YET_RECRUITING): Research on radiotherapy target volumes for glioblastoma is increasingly focused on exploring more limited yet effective irradiation fields, aiming to achieve local control while minimizing acute and long-term neurotoxicity. Previous retrospective analysis by investigators revealed that local recurrences of glioblastoma are predominantly confined to a narrow margin around the original lesion: 98.3% of recurrences occurred within 0.5 cm of the original T2-FLAIR abnormality, 94.8% within 1 cm of the original T1-enhanced region. These findings have been cited in the ESTRO-EANO treatment guidelines. Building on this evidence, investigators plan to conduct a single-arm, phase II clinical trial to systematically evaluate the efficacy and safety of a 1 cm radiotherapy target volume in post-operative glioblastoma patients.Eligible patients with glioblastoma who have undergone surgical resection will be selected to receive limited-field radiotherapy. The target volume will be defined based on the postoperative MRI enhancing lesion: a 1 cm margin will be added to form the clinical target volume (CTV), followed by a further 0.3 cm margin to create the planning target volume (PTV). A total dose of 60 Gy will be delivered in 30 fractions (2 Gy per fraction, 5 fractions per week). Concurrent and adjuvant chemotherapy will be administered per standard guidelines. The primary efficacy endpoints are the 6-month progression-free survival rate and the incidence of symptomatic radiation-induced brain necrosis of grade 3 or higher. Secondary endpoints include overall survival, patterns of recurrence, neurocognitive function, and quality of life.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07368283
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07089758 - A Pilot Feasibility Study for Cerebral Open Flow Microperfusion in Patients Undergoing Planned Neurosurgical Resection of Diseased Parenchyma. (NA, NOT_YET_RECRUITING): The purpose of this study is to evaluate the safety and feasibility of intra-operative microperfusion during a planned neurosurgical resection of diseased brain parenchyma, including either an epileptic focus requiring temporal lobectomy or a glioma. Devices used for microperfusion are Joanneum Research cerebral open flow microperfusion (OFM) catheters, push and pull tubing, and MPP102-II pump.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07089758
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07067905 - Clinical Evaluation of [68Ga]Ga-XT771 PET for Diagnosis in Patients With Glioblastoma and Clear Cell Renal Cell Carcinoma (EARLY_PHASE1, RECRUITING): A prospective, open-label, phase 1 study. This clinical trial aims to evaluate the diagnostic value of 68Ga-XT771, a CAIX/CAXII protein-specific probe, in PET/CT imaging for patients with clear cell renal cell carcinoma and glioblastoma. Safety, tolerability, and biodistribution characteristics of 68Ga-XT771 will also be assessed.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07067905
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06687681 - Efficacy of the Intrathecal Injection of Active Allogeneic Natural Killer Cells in Patients With High-grade Gliomas; A Multi-center Phase II Clinical Trial (PHASE2, RECRUITING): Gliomas are the most common malignant brain tumors, which are often associated with high-grade tumors characterized by an inferior prognosis and low patient survival rates in both children and adults. Surgical removal and tumor resection are the primary treatment approaches for gliomas. In such cases, whole-brain radiation therapy is also employed as a therapeutic option, which itself has significant side effects, and studies have shown limited impact on improving patient survival. Targeted therapy and recently investigated approaches such as targeted therapy have shown some tumor regression, but in most cases, tumor recurrence has been observed after initial regression. Therefore, they have a limited impact on prolonging patient survival. Immunotherapy, particularly immunotherapy with specific immune cells, can effectively identify and eliminate cancer cells and has been utilized as a new approach in the past two decades, especially in cancers where conventional methods have limited success. Among the effective immunotherapy methods, using natural killer cells (NK cells) can be one of the promising approaches. Currently, phase I clinical trials have been conducted by our research group in patients with gliomas.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06687681
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06551909 - Radioimmunotherapy in Solid Tumors (Aim 2- Stereotactic Neoadjuvant Radiotherapy for Glioblastoma) (NA, RECRUITING): This is a prospective multicenter study of hypofractionated radiotherapy for the radiation treatment (RT) of solid tumors and in particular for Glioblastoma (in Aim 2). It is based on the results of ongoing studies at our Institute to validate the efficacy of extremely hypofractionated RT in neoadjuvant settings, which observed immunostimulatory effects of RT and the synergy with immune components. The collaboration between San Raffaele Hospital (Milan), the IRCCS Istituto Nazionale dei Tumori Fondazione G. Pascale (Naples) and the San Giuseppe Moscati Hospital of National Relief and High Specialty (Avellino) will ensure that patient recruitment, treatment and monitoring can be translated into facilities of the National Health System using common procedures. The various departments involved will treat patients with the same methods synergistically exploring the immuno/biological factors related to efficacy (and/or toxicity), based on new radioimmunotherapeutic approaches. Clinical and research activity will be developed jointly, drawing on the expertise in radiotherapy, radiomics, oncology, imaging and immunotherapy skills already available.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06551909
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05720078 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-3 (UNITED-3): Applying a Two Phase, Personalized Margin, Reduced Clinical Target Volume Approach (NA, RECRUITING): The goal of this study is to test whether an adaptive radiation therapy (RT), two-phase approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive, two-phase RT approach compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05720078
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05565521 - UNITy-BasED MR-Linac Adaptive Simultaneous Integrated Hypofractionated Boost Trial for High Grade Glioma in the Elderly (PHASE2, RECRUITING): The usual standard of care for patients over 65 diagnosed with glioblastoma ("GBM") or Grade 4 astrocytoma, IDH-mutant is a 3-week course of radiotherapy, with concurrent and adjuvant temozolomide (TMZ). This radiation dose and length of treatment are less than what would be given for younger patients, primarily due to unclear survival benefits from randomized trials. However, survival remains dismal, and may be partially due to the reduced radiation dose. Recent studies investigating this have found that increased radiation dose (to the equivalent of what is normally given over 6 weeks in younger patients) over 3 weeks is well-tolerated and has improved survival rates. Additionally, with the advent of novel technology such as the MR-Linac, adaptive radiotherapy with this regimen using reduced radiation margins is possible. Use of the MR-Linac allows for daily MRI scans to be done prior to treatment, so plans can be adapted to tumour dynamics and anatomical deformations. In this trial, we will examine the outcomes of increased radiation dose, combined with reduced-margin adaptive radiotherapy in this patient population.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05565521
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=67 vs 65 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT04752280 - Glioblastoma Radiotherapy Using IMRT or Proton Beams (NA, RECRUITING): Radiation therapy is an integral part of the multimodal primary therapy of glioblastomas. As the overall prognosis in this tumor entity remains unfavorable, current research is focused on additional drug therapies, which are often accompanied by increases in toxicity. By using proton beams instead of photon beams, it is possible to protect large parts of the brain which are not affected by the tumor more effectively. An initial retrospective matched-pair analysis showed that this theoretical physical benefit is also clinically associated with a reduction in toxicity during therapy and in the first few months thereafter. The aim of the GRIPS study is to prospectively test this clinical benefit in a randomized, open-label Phase III study. Patients are treated in the study using either modern photon radiation techniques (standard arm) or proton beams (experimental arm). The primary endpoint is the cumulative toxicity CTC grade 2 and higher in the first 4 months. Secondary endpoints include overall survival, progression-free survival, quality of life, and neurocognition.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04752280
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=67 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05669820 - Antisecretory Factor During Concomitant and Adjuvant Therapy of Primary Glioblastoma, a Randomised, Prospective and Double Blinded Study (PHASE2, PHASE3, RECRUITING): This is a randomised, double blinded and multiple center , Phase 2 study in patients with newly diagnosed glioblastoma. Participants will receive an egg powder enriched for antisecretory factor (AF), Salovum, or a placebo egg powder daily from 2 days before concomitant radio-chemo therapy or chemotherapy until 14 days after finalisation plus during adjuvant chemotherapy.The primary aims of are overall survival at 6 and 12 months after diagnosis
  Quick read: GBM-specific treatment study for newly diagnosed GBM; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05669820
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05911230 - Advanced Diffusion MRI to Differentiate Tumor Recurrence From Pseudoprogression in Patients With Glioblastoma and Brain Metastases- AiD GLIO Pilot Trial (NA, RECRUITING): This pilot study investigates whether advanced diffusion-weighted MRI (ADW-MRI) can differentiate between true tumor progression (TP) and a pseudoprogression (PsP) in patients with glioblastoma (GBM) or brain metastases.
  Quick read: GBM-specific treatment study for GBM or glioma patients; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05911230
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT04188535 - RELAY: Repeated Magnetic Resonance Imaging Examinations to Analyze and Assess Your Cancer: A Prospective Study on the Use of Serial Magnetic Resonance Imaging in the Assessment of Changes During Treatment With Radiation Therapy (NA, RECRUITING): This is a phase 1 study to determine the feasibility and utility of using serial magnetic resonance imaging (MRI) to assess treatment response during and after radiation therapy (standard of care cancer treatment) for participants with advanced esophageal cancer, glioblastoma, prostate cancer, vulvar cancer or pediatric glioma. The research study procedures include three MRI scans (one before, one during, and one after standard of care cancer radiation therapy) for participants with advanced esophageal cancer, glioblastoma, prostate cancer, vulvar cancer or pediatric glioma. The research study procedures include: * Screening for eligibility * Three MRI scans
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04188535
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT04523688 - Vaccination With Autologous Dendritic Cells Loaded With Autologous Tumour Homogenate in Glioblastoma: a Phase II Study (PHASE2, RECRUITING): Single arm, monocentric trial to assess the safety and the progression-free survival related to the combined treatment of dendritic cell vaccine loaded with autologous tumor homogenate and temozolomide in patients operated for glioblastoma and then treated with standard radiochemotherapy (according to Stupp regimen).
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04523688
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07439172 - A Multi-Centered Evaluation of Pre-Radiation Chemotherapy for Newly Diagnosed High-Grade Glioma (HGG): An Approach to Drug Screening That Requires Confirmation (PHASE2, NOT_YET_RECRUITING): Better treatments are needed for high-grade gliomas (HGG), and new ways of treating this disease should be tested. The investigators want to see if giving medicine before radiation works well. After radiation, MRI scans can be harder to understand because radiation changes how the brain looks on the scan. If new medicines are given before radiation, the scans are easier to read. First, the investigators need to find out if giving chemotherapy early works using a drug we already know can treat gliomas. The investigators will start with temozolomide, which is the only chemotherapy approved by the FDA for HGG. If this approach is successful, the investigators can then test new drugs using this screening method.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07439172
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06017063 - Coaching for Coping in Glioblastoma Patients and Caregivers and Its Association With Compliance to TTFields (NA, NOT_YET_RECRUITING): The aim is to improve patients' compliance to TTFields therapy by a psychological video intervention in a multi-center, randomized controlled trial.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06017063
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07211841 - Correlative Analysis Between Magnetic Resonance Spectroscopy (MRS) and Essential Clinicobiological Data in Glioblatoma Multiforme (GBM) (NA, NOT_YET_RECRUITING): Glioblastoma multiforme (GBM) is the most common primary brain tumor, and it is well-known to be associated with a poor prognosis. MRI is the key medical technique for the diagnosis and the follow-up of GBM. By allowing for MRS studies, MRI permits a non-invasive characterization of the TME of GBM, including their metabolic characterization. The investigators propose to address the link between the MRS profile of GBM and basic clinical and biological parameters, with the aim of : i) identifying correlations between these parameters, ii) attempting to integrate clinical, biological and spectroscopic profiles of GBM. The investigators plan to recruit 30 newly diagnosed GBM patients for which surgery / radiochemotherapy will be proposed in the Medical oncology unit of Amiens University Hospital. Following inclusion of patients with probable GBM, MRS study will be performed during the first (pre-therapeutic) MRI examination. Basic clinical and biological parameters of the blood (CRP, complete blood count, fibrinogen, lactate and choline) will be assessed. A metabolomic study will also be performed on the plasma of GBM patients before any therapeutics. A second biological, post-therapeutic assesment (one month after surgery/radiochemotherapy) will allow the same analyses (basic biological parameters + plasma metabolomics), in order to examine the stability of the blood parameters.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07211841
  Review priority: 143
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07459101 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-4 (UNITED-4): Prospective Evaluation of FLAIR-Guided Clinical Target Volume Reduction (NA, RECRUITING): This study builds on the results of prior studies (UNITED and UNITED-3). The goal of UNITED-4 is to test whether an adaptive radiation therapy (RT) therapy approach ('dose painting'), with reduced margins, impacts approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive RT approach with reduced margins compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life * Longitudinal imaging features
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07459101
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06418113 - Neoadjuvant Radio-chemotherapy Safety Pilot Study in Patients With Glioblastoma (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and efficacy of neoadjuvant radiochemotherapy in the surgical resection of glioblastoma (GBM). The main questions it aims to answer are: * What is the safety profile of neoadjuvant radiochemotherapy in terms of neurological deficit, radionecrosis, edema, headache, wound dehiscence, infection, and cerebrospinal fluid fistula? * What is the efficacy of neoadjuvant radiochemotherapy in terms of progression-free survival, overall survival, cognitive function, and quality of life? Participants will undergo the following tasks and treatments: * Stereotactic biopsy and diagnosis confirmation. * Conformal hypofractionated stereotactic radiotherapy with concurrent temozolomide. * Supramarginal resection guided by 5-ALA under intraoperative neurophysiological monitoring. * Maintenance temozolomide administration for 6 months. Researchers will compare the group receiving neoadjuvant radiochemotherapy to the control group following the standard Stupp protocol to assess safety and efficacy outcomes.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06418113
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT06356883 - A Randomized Phase II Study on Intraarterial Carboplatin Combined With Caelyx Compared to Intraarterial Carboplatin Combined With Etoposide Phosphate for Progressing Glioblastoma at First or Second Relapse (PHASE2, RECRUITING): The standard of care for glioblastoma (GBM) treatment involves maximal resection followed by concomitant radiotherapy and temozolomide. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is inevitable. At relapse, there is no consensus regarding the optimal therapeutic strategy. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which impedes drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, can produce responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival (OS) 23 months. How can the OS and PFS be improved? By combining chemotherapeutic agents with different mechanisms of action. Study design: In this phase II trial, treatment will be offered at relapse. Surgery will be performed for cytoreduction if it is warranted, followed with a combination IA carboplatin + IA Cealyx (liposomal doxorubicin) or IA carboplatin + IA etoposide phosphate. Toxicity will be assessed according to the NCIC common toxicity criteria. Treatment will consist in either IA carboplatin (400 mg/m\^2) + IA Cealyx (30 mg/m\^2) or IA carboplatin (400 mg/m\^2) + IA etoposide phosphate (400 mg/m\^2) every 4-6 weeks (1 cycle). Up to twelve cycles will be offered. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. Primary outcome will PFS and tumor response. Secondary outcome will include median OS, toxicity, quality of life (QOL), neurocognition (NC). Putting together these data will allow to correlate clinical and radiological response to QOL and NC.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06356883
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT03672721 - A Phase II Study in Relapsing Glioblastoma of Intraarterial Concurrent Chemoradiation Therapy Using IA Carboplatin (PHASE1, PHASE2, RECRUITING): Treatment of glioblastoma involves an optimal surgery, followed by a combination of radiation and temozolomide chemotherapy. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is the norm. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which limits drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, the investigators have observed responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival 23 months. How can this be improved? By coupling radiation with a chemotherapeutic which is also a potent radiosensitizer such as carboplatin. Study design: In this phase I/II trial, patients will be treated at recurrence; a surgery will be performed for cytoreduction and to obtain tumor sample, followed with a combination of re-irradiation and IA carboplatin chemotherapy. A careful escalation scheme from 1.5Gy/fraction up to 3.5Gy/fraction will allow the investigators to determine the optimal re-irradiation dose (10 fractions of radiation over 2 weeks). Toxicity will be assessed according to the NCIC common toxicity criteria. Combined with radiation, patients will receive 2 treatments of IA carboplatin, 400 mg/m2, 4 hours prior to the first and the sixth radiation fraction. IA treatments will then be continued on a monthly basis, up to a total of 12 months, or until progression. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. The investigators will also acquire a sequence that enables the measurement of cerebral blood flow, cerebral blood volume and blood vessel permeability that are all relevant to understand the delivery of therapeutics to the CNS. Primary outcome will be OS and PFS. Secondary outcome will be QOL, neurocognition, and carboplatin delivery. In vitro intracellular carboplatin accumulation: Tumor samples from re-operation will be be analyzed for intracellular Pt concentration by ICP-MS. The amount of Pt bound to DNA will be measured. The level of apoptosis will be determined for each of the sample. Putting together these data will allow to correlate clinical and radiological response to QOL, NC (MOCA), and to delivery surrogates for the IA infusion and intracellular penetration of carboplatin.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03672721
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT05990556 - Research on the Safety and Efficacy of Blocking Dural Blood Supply in Glioblastoma Patients (NA, RECRUITING): Glioblastoma is the most common primary malignancy of the central nervous system with a very poor prognosis. Most of the immunotherapies that have made significant breakthroughs in the treatment of other tumors in recent years are unsatisfactory in the application of glioblastoma, which is mainly inseparable from the highly inhibitory immune microenvironment formed by the latter. Therefore, how to change this "immune desert" and better activate immune effector cells to play an anti-tumor effect is currently a hot spot in glioma immune research. In recent years, there has been continuous research support that the myeloid cells of the central nervous system are partly derived from the bone marrow of the skull, and there is a special channel connection between the skull and the dura mater, through which immune cells can be transported. This suggests that some of the tumor-associated macrophages recruited in the glioblastoma microenvironment may be passed through the dura mater. In previous animal experiments, we blocked the main blood supply to the dura mater by ligating the bilateral external carotid arteries of mice, cutting off the potential supply of dura mater to suppressor myeloid cells in the lesion. The results showed that after ligation of bilateral external carotid arteries, the survival period of tumor-forming mice was significantly prolonged and the prognosis was improved. The proportion of myeloid cells in the tumor microenvironment of mice decreased significantly, and the expression of tumor suppressor molecules such as arginase Arg1 decreased, indicating that the improvement of mouse prognosis was closely related to the proportion and phenotypic changes of myeloid cells after dural blood supply blockade. The meningeal lymphatic system of the human central nervous system has been shown to be an important part of the immune system, while the external carotid artery system, the main source of blood supply to the dura, carries abundant immune cells that ooze out to the dura mater through the endothelial window hole of the dural blood vessel, which is an important source of dural immune cells. In the glioblastoma immune microenvironment, the source of immune cells includes dural branches from the external carotid artery system in addition to branches of the internal carotid artery system. Therefore, for patients diagnosed with glioblastoma, this study involves embolization of the dural branch of the external carotid artery system (bilateral middle meningeal artery) to block the dural blood supply before craniotomy. At the same time, microsurgery under multimodal image navigation was used to remove the tumor. It is expected to be effective in reducing the proportion of myeloid suppressor cells in the tumor microenvironment, slowing the growth rate of residual tumor cells, and prolonging the tumor-free progression and survival of patients.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05990556
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT03958240 - Deciphering Mechanisms Underlying Cancer Immunogenicity (NA, RECRUITING): This trial is a translational, open-label, multicentric, prospective cohort study of 1100 patients aiming to describe the PD-1 (programmed death) expression in T cells (T lymphocytes) in different solid tumors. The study will be conducted on a population of patients with local and/or metastatic malignant solid tumor and who are followed within a standard of care procedure or clinical trial. Patients with any of the following tumor types may be enrolled in the trial: * Head and neck cancer, * Ovarian cancer, * Cervical cancer, * Pre-invasive CIN III cervical cancer (Cervical Intra-epithelial Neoplasia III cervical cancer), * Other solid tumor types (including glioblastoma, NSCLC (Non-small cell lung cancer), anal cancer) Each tumor type will be considered as an independent cohort. For each included patient, biological specimen (tumor sample, blood samples and ascites samples if applicable) will be collected. Study participation of each patient will be 5 years.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03958240
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=67 vs 18 (match), ecog_max=2 vs 2 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07493447 - Pilot Study Evaluating Panitumumab-IRDye800 as an Optical Imaging Agent to Detect Intracranial Lesions During Neurosurgical Procedures (EARLY_PHASE1, NOT_YET_RECRUITING): This pilot clinical study evaluates the safety and imaging performance of panitumumab-IRDye800 (pan800), a fluorescent, EGFR-targeted imaging agent - in patients undergoing neurosurgical resection of intracranial lesions.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07493447
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=67 vs 18 (match), requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none
- NCT07384884 - Surgery and Laser Interstitial Thermal Therapy for Bilateral Glioblastomas (NA, NOT_YET_RECRUITING): Butterfly glioblastomas (bGBM), defined as tumours crossing the midline to involve hemispheres bilaterally, have a dismal prognosis with a median survival of 3.3-6 months and only 9% of patients with bGBM survive 2-years. These figures put bGBM in the worst end of the spectrum of GBM prognosis, significantly inferior to the survival figures quoted in the literature with standard of care - 14.6 months - particularly when 5-aminolevulinic acid is used as surgical adjuvant - 17.47 months. Despite the poor outcome of this disease, there is preliminary evidence suggesting that active oncology treatment can impact the survival of patients with this condition.With particular regards to surgical resection versus biopsy, there is a suggestion that resection improves overall survival at 6 months with no clear difference at 12 and 18 months of follow up. Laser-induced thermal therapy (LITT) is a minimally invasive laser ablation technique used in a range of brain tumours, including glioblastomas, with similar overall survival to the ones reported for open surgery in patients with lesions not amenable to open resection. The minimally invasive nature of this technique, significantly reducing the collateral damage to the surrounding brain structures, suggests Its potential in the treatment of this bGBM \[14\] with significant implications as a deficit-sparing technique, particularly if associated with preoperative and intraoperative monitoring and mapping techniques. The SLITT-GBM study will combine unilateral open surgery for maximal tumour resection with contralateral LITT to the smaller component/residual.
  Quick read: GBM-related treatment study for GBM or glioma patients; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07384884
  Review priority: 134
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=False vs False (mismatch)
  Reasons: none

#### Related Papers
- PMID:34898238 - Therapy for Diffuse Astrocytic and Oligodendroglial Tumors in Adults: ASCO-SNO Guideline.
  Quick read: Guideline-style reference for GBM-specific, newly_diagnosed, focused on radiation, temozolomide in Journal of clinical oncology : official journal of the American Society of Clinical Oncology (2022). Linked to NCT06504381.
  Source: https://pubmed.ncbi.nlm.nih.gov/34898238/
- PMID:37059335 - ESTRO-EANO guideline on target delineation and radiotherapy details for glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2023).
  Source: https://pubmed.ncbi.nlm.nih.gov/37059335/
- PMID:35426875 - Congress of Neurological Surgeons Systematic Review and Evidence-Based Guidelines on the Management of Progressive Glioblastoma in Adults: Update of the 2014 Guidelines.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Neurosurgery (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35426875/
- PMID:35246769 - Congress of neurological surgeons systematic review and evidence-based guidelines update on the role of cytoreductive surgery in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35246769/
- PMID:35195819 - Congress of Neurological Surgeons systematic review and evidence-based guidelines update on the role of cytotoxic chemotherapy and other cytotoxic therapies in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35195819/
- PMID:29086250 - SEOM clinical guidelines for diagnosis and treatment of glioblastoma (2017).
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Clinical & translational oncology : official publication of the Federation of Spanish Oncology Societies and of the National Cancer Institute of Mexico (2018).
  Source: https://pubmed.ncbi.nlm.nih.gov/29086250/
- PMID:27907278 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of oncology practice (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27907278/
- PMID:27893327 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of clinical oncology : official journal of the American Society of Clinical Oncology (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27893327/
- PMID:26777122 - ESTRO-ACROP guideline "target delineation of glioblastomas".
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2016).
  Source: https://pubmed.ncbi.nlm.nih.gov/26777122/
- PMID:25079102 - EANO guideline for the diagnosis and treatment of anaplastic gliomas and glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in The Lancet. Oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/25079102/
- PMID:24756348 - The role of cytoreductive surgery in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24756348/
- PMID:24740195 - The role of targeted therapies in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24740195/

#### Related Datasets
- gdc_tcga_gbm - NCI GDC TCGA-GBM
  Quick read: Core GBM tumor-genomics program with somatic variants, copy-number, expression, methylation, and linked clinical metadata; open and controlled-access layers.
  Source: https://gdc.cancer.gov/about-data/publications/gbm_2013
- gdc_tcga_lgg_gbm - NCI GDC TCGA Pan-Glioma Cohorts
  Quick read: Combined glioma genomics across lower-grade glioma and GBM for broader IDH, MGMT, and progression-context comparisons.
  Source: https://portal.gdc.cancer.gov/
- ivy_gap - Ivy Glioblastoma Atlas Project
  Quick read: Region-resolved glioblastoma atlas with anatomic and molecular context across tumor subregions.
  Source: https://glioblastoma.alleninstitute.org/
- cbioportal_gbm - cBioPortal GBM Studies
  Quick read: Searchable GBM and glioma genomics knowledgebase spanning TCGA and many published studies with mutation, CNA, and outcome views.
  Source: https://www.cbioportal.org/
- cptac_gbm - CPTAC Brain / Glioblastoma Proteogenomic Resources
  Quick read: Proteomic and proteogenomic tumor data relevant to GBM biology and pathway activation beyond DNA-only signals.
  Source: https://proteomics.cancer.gov/programs/cptac

#### Missing Evidence
- Tumor sequencing report available: A structured NGS report or equivalent molecular panel.
  Missing artifact types: ngs_report
- MGMT status documented: Pathology or molecular result with MGMT status.
  Missing artifact types: pathology_report, mgmt_result
- IDH status documented: Pathology or molecular result with explicit IDH status.
  Missing artifact types: pathology_report, ngs_report
- Current steroid burden documented: Medication list or clinic note describing current steroid use.
  Missing artifact types: clinic_note, medication_list
- HLA typing available: HLA typing lab result.
  Missing artifact types: hla_typing_result
- Usable tissue status documented: Tissue handling note, pathology note, or operative note describing tissue availability.
  Missing artifact types: tissue_handling_note, operative_note, pathology_report

### Newly Diagnosed Adult
- Case ID: `case_postop_radiation_in_progress`
- Patient: `synthetic-005`
- Evidence package: 6 ready / 2 missing
- Standard-care paths to discuss: 2
- Trial candidates for review: 100
- Trials needing more evidence: 55
- Bitmask: `65`

#### Recommended Care Pathways
- Postoperative Radiation Plus Temozolomide: Standard newly diagnosed postoperative pathway after surgery in a fit adult with GBM.
  Reasons: Patient state matched: newly_diagnosed, Patient state matched: post_surgery, Patient state matched: adult_patient, Patient state matched: performance_status_good
- Tumor Treating Fields: Device-based therapy to discuss alongside standard treatment in appropriate newly diagnosed GBM settings.
  Reasons: Patient state matched: newly_diagnosed, Patient state matched: adult_patient, Patient state matched: performance_status_good

#### Candidate Trials
- NCT07488754 - Medical Experiment - Assessment of Efficacy & Safety of Local, Targeted Therapy With Neuropeptide Labelled With Alpha Emitter [225Ac]Ac-DOTA-SP (TAT) as Supplementary Therapy Following Standard Treatment Of Glioma (WHO G3-G4) (NA, RECRUITING): Brain tumors account for 1.35% of all cancers and cause 2.2% of cancer-related deaths. Gliomas are the most common type, comprising 40-90% of central nervous system tumors in different age groups. The incidence of malignant gliomas is approximately 0.5-2 per 100,000 people annually. Standard treatments include surgical resection, radiotherapy, and chemotherapy, yet overall survival remains low, typically 1-3 years post-diagnosis. The study highlights the pressing need for novel treatment strategies, particularly given the infiltrative nature of gliomas and the potential for targeted therapies using neuropeptides.The aim of this study is to assess the efficacy and safety of local targeted therapy with \[225Ac\]Ac-DOTA-SP in newly diagnosed glioblastoma following standard treatment.It is an interventional study without a control group, initiated by the researcher. Patients included are aged 18-80 with WHO G3-G4 glioma post-first-line treatment, not requiring immediate surgery and meeting specific MRI criteria.Patients will receive a maximum of six cycles of \[225Ac\]Ac-DOTA-SP, involving pre-treatment assessments, local administration of the agent after ensuring catheter patency, and continuous monitoring. Blood tests and neurological evaluations will be performed regularly.Outcome will be assessed by measuring overall survival (OS) and progression-free survival (PFS). The study anticipates improvements in both OS and PFS when compared to current treatments, contributing to critical insights into targeted alpha therapy's effectiveness in glioblastoma.Treatment with \[225Ac\]Ac-DOTA-SP previously indicated few significant side effects, primarily transient issues like seizures. Patients will be closely monitored throughout the study to identify any adverse effects promptly.The estimated study duration is three years, with biological material collected for histopathological and genetic analysis during surgical reoperation.Data will be anonymized to protect patient confidentiality, stored securely, and made available only for the scope of the study.Led by Prof. Przemysław Kunert, the research team includes multiple co-investigators from neurosurgery and nuclear medicine departments.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07488754
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07485049 - A Phase 0/2 Study of BGB-58067, an MTA Cooperative PRMT5 Inhibitor, in Newly Diagnosed Glioblastoma Patients With Methylthioadenosine Phosphorylase (MTAP) Deleted Tumors Scheduled for Resection to Evaluate Central Nervous System (CNS) Penetration With Pharmacodynamic (PD)-Triggered Expansion Cohorts (EARLY_PHASE1, NOT_YET_RECRUITING): This is an open-label, multi-center, Phase 0/2 trial designed to enroll up to 78 total participants with suspected newly diagnosed glioblastoma (nGBM) who are scheduled for surgical resection to accrue at least 14 participants in Arm A and 10 participants in Arm B. The trial will evaluate the pharmacokinetics (PK), pharmacodynamics (PD), and safety of BGB-58067. The study is composed of a Phase 0 and expansion Phase 2 component. The Phase 0 primary endpoint will be suppression of symmetric dimethylarginine (SDMA) in tumor tissue measured by immunohistochemistry (IHC). The Phase 2 primary endpoint will be 12-month overall survival rate (OS12). The Phase 0 secondary endpoint will be to characterize the PK of BGB-58067 in tumor tissue, plasma, and cerebrospinal fluid (CSF). The Phase 2 secondary endpoints will include assessing the safety profile of BGB-58067 and evaluating clinical efficacy of BGB 58067 using overall survival (OS) and the 6-month progression-free survival rate (PFS6) estimated by Kaplan-Meier (K-M) methods.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07485049
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07455045 - An Open-Label, Multicenter, Phase I Study of FZ-AD005 Antibody-Drug Conjugate in Patients With Recurrent/Refractory High-Grade Glioma (HGG) (PHASE1, NOT_YET_RECRUITING): An Open Label, Phase I Study to Evaluate the Safety, Tolerability, Pharmacokinetics, and Preliminary Antitumor Activity of FZ-AD005 in Patients with HGG, especially in DMG and other Recurrent HGG.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07455045
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07452458 - A Randomized Phase III Study Comparing Temporally-Modulated Pulsed Radiation Therapy (TMPRT) Versus Standard Radiation Therapy With Temozolomide for Adults With Newly Diagnosed MGMT-Unmethylated Glioblastoma (PHASE3, NOT_YET_RECRUITING): This phase III trial compares temporally-modulated pulsed radiation therapy versus standard radiation therapy in treating patients with newly diagnosed, IDH wildtype, MGMT-unmethylated glioblastoma. After completion of surgery, the standard of care for glioblastoma is radiation therapy. Radiation therapy uses high energy x-rays, particles, or radioactive seeds to kill cancer cells and shrink tumors. For older and frail patients, standard treatment also includes the chemotherapy drug temozolomide. Temozolomide is in a class of medications called alkylating agents. It works by damaging the cell's DNA and may kill tumor cells and slow down or stop tumor growth. Approximately 70% of glioblastoma patients have MGMT-unmethylated status. MGMT unmethylated tumors are less likely to respond to temozolomide chemotherapy, so there is more reliance on radiation therapy to kill the tumor cells. Recent clinical trials studying new therapies for MGMT-unmethylated glioblastoma have failed to improve outcomes over temozolomide. These recent studies also indicate that 80% of patients experience a decline in memory and thinking function after treatment. TMPRT differs from standard radiation therapy by delivering the same amount of radiation dose in 10-13 "pulses" with 3-minute breaks between pulses. TMPRT with temozolomide may work better than standard radiation therapy with temozolomide in increasing survival, as well as improving memory and thinking function in patients with newly diagnosed, IDH wildtype, MGMT-unmethylated glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07452458
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07387666 - A Prospective, Open-label Phase 0 Single-center Study to Assess the Effect of Acetadote on Metabolism in Newly Diagnosed Glioblastoma (EARLY_PHASE1, NOT_YET_RECRUITING): This goal of this clinical trial is to evaluate how Acetadote affects metabolism in patients with glioblastoma. Drugs like Acetadote, which affect the level of damage in a cell (oxidative stress), may impact brain tumor metabolism and slow the growth of brain tumors. The investigators are evaluating how Acetadote affects glioblastoma metabolism by using MRI-based methods and by determining the changes in metabolism in brain tumor tissue resected from patients with a new diagnosis of glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07387666
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07356973 - Open-label Phase 2 Safety and Efficacy Trial of Irinotecan-ChemoSeed Administered Directly Into the Resection Margin in Patients With Surgically Resectable Glioblastoma (PHASE2, NOT_YET_RECRUITING): Part 1 (dose escalation, safety, and preliminary efficacy) Part 1 is a non-randomised, single-arm design in 12 participants with recurrent GBM suitable for maximal safe surgical resection. Part 1 will evaluate safety, determine the MTD of irinotecan-ChemoSeed and the RP2D (corresponding to coverage of as much of the resection cavity as possible, up to the MTD) and evaluate efficacy. All Part 1 participants will be administered irinotecan- ChemoSeed concurrent to Standard of Care (SoC) treatment. Part 1 dose- escalation will start at 72 mg of IRN Part 2, in 135 participants with newly diagnosed GBM suitable for maximal safe surgical resection, will assess the efficacy of irinotecan-ChemoSeed. The actual number of irinotecan-ChemoSeeds administered into the resected tumour margin of the tumour cavity after surgical resection will be at the discretion of the neurosurgical consultant up to the MTD, to cover as much of the resection cavity as possible. Participants will be randomised in a 2:1 ratio: * Arm 1: Irinotecan-ChemoSeed +SoC: Irinotecan-Chemoseeds administered into the resection margin following maximal safe surgical resection, with fractionated RT, concomitant and maintenance TMZ (based on Stupp protocol) starting 4 to 6 weeks after surgery per institution standard practice. * Arm 2: SoC treatment only: maximal safe surgical resection with fractionated RT, concomitant and maintenance TMZ (based on Stupp protocol) starting 4 to 6 weeks after surgery per institution standard practice.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07356973
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07347210 - Evaluation of UCPVax Vaccine +/- Pembrolizumab Combined With Standard Treatment as Adjuvant Therapy in Patients With Unmethylated MGMT Glioblastoma: a Randomized Phase II Trial (PHASE2, NOT_YET_RECRUITING): Glioblastomas (GBM) are the most frequent brain tumors and one of the most lethal adult cancers despite maximal multimodal therapy. Despite maximal safe resection followed by radiotherapy and temozolomide (TMZ) ± tumor-treating fields, median overall survival for newly diagnosed GBM remains around 18 months and long-term survival is rare, and recurrence is nearly universal. So, the development of new therapeutic strategies is a critical unmet need in GBM. Despite the limited success of anti-PD(L)-1 therapy, immunotherapy remains a promising option in GBM. Current challenge supports to develop combinatorial therapy approaches considering the particular immune tumor microenvironment in GBM. Anticancer vaccines have shown promising signs of efficacy in GBM but critical factors challenge their efficacy. CD4 T help is of major interest for cancer vaccine effectiveness and for immune checkpoint inhibitors success. We previously designed UCPVax a CD4 T helper-targeted cancer vaccine derived from telomerase (TERT), a very attractive GBM-associated antigen (Adotévi O, J Clin Oncol 2023 ; Laheurte C, Cell Report Med 2025). The induction of robust tumor reactive CD4 T cell response with UCPVax together with TMZ-mediated immune effects will promote recruitment of effectors immune cells into tumor bed creating a more suitable microenvironment for anti-PD-1 action. This is a proof-of-concept phase II trial to evaluate the efficacy of maintenance therapy evaluating UCPVax +/- pembrolizumab combined to standard treatment in newly diagnosed unmethylated MGMT glioblastoma. A translational research network will be implemented to better understand the therapeutic efficacy of this combination.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07347210
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07343986 - Phase I Clinical Trial of Anti-CD3 × Anti-EGFR Bispecific-armed T Cells (EGFR BATs) and Low-Intensity Focused Ultrasound (LIFU) Blood-brain Barrier Opening in Patients With MGMT Unmethylated Glioblastoma (GBM) (PHASE1, RECRUITING): This is a phase 1 study for patients with newly diagnosed MGMT unmethylated IDH wild-type glioblastoma utilizing autologous activated T-cells armed with bispecific antibody (EGFR-BATs) that recognize the tumor. The investigators hypothesized that the combination of infusions of EGFR BATs and low-intensity focused ultrasound would induce blood-brain barrier opening and increase the permeability of the adoptive immunotherapy. The investigators will radiolabel the EGFR BATs with 89Zr-oxine for subsequent PET imaging to determine the trafficking and uptake of this approach. There is a concern that several infusions of EGFR BATs before BBB opening could change the immune tumor microenvironment that would not allow a permissive BBB after LIFU. Therefore, Arm A will have two LIFU with BBB opening after the 4th and the 8th infusion, and Arm B will have three LIFU with BBB opening after the 1st, 4th, and 8th infusions. This study will determine the safety and feasibility of the combination of low-intensity focused ultrasound (LIFU) with microbubbles BBB opening and EGFR BATs and the access of the adoptive cell immunotherapy to the tumor microenvironment to inform future studies.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07343986
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07284069 - Phase 0/1 Randomized Clinical Trial of SENIcapoc and PERAmpanel Mono- and Combination Therapy of Newly Diagnosed Glioblastoma (EARLY_PHASE1, RECRUITING): Glioblastoma is the most common and aggressive form of brain cancer in adults. Despite surgery, radiotherapy, and chemotherapy, most patients only live about one year after diagnosis. There is an urgent need for new and better treatments. Recent research has shown that glioblastoma cancer cells communicate with surrounding brain cells through electrical signals that help the tumor grow and resist treatment. Two existing drugs, perampanel (used for epilepsy) and senicapoc (previously tested for blood disorders), may block these harmful signals. Laboratory studies suggest that combining these two drugs could slow tumor growth and make cancer cells more sensitive to standard therapy. The SENIPERA trial will test whether perampanel and senicapoc, alone and in combination, are safe and well tolerated when added to standard treatment for newly diagnosed glioblastoma. The study will also measure how well these drugs reach the brain and tumor, and how they affect tumor biology. The study has two parts: Part A: Tests different doses of senicapoc alone to find the maximum tolerable dose. Part B: Randomly assigns patients to receive either perampanel alone or perampanel together with senicapoc. Participants will all receive standard therapy, including surgery, radiochemotherapy, and adjuvant chemotherapy. During surgery, small samples of tumor and fluid will be collected safely to study how the drugs act in the body and how tumor cells respond. Participants will be closely monitored for side effects and followed with regular clinical visits and MRI scans. The trial will take place at Aarhus University Hospital, Denmark, from February 2026 to November 2028 and will enroll 27-36 adult patients. The study aims to identify safe and biologically active treatment combinations that could be tested in larger trials to improve future glioblastoma care.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07284069
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07195591 - Randomized Study of Resection and GammaTile® Followed by Concurrent External Beam Radiation Therapy (EBRT) and Temozolomide (TMZ) and Adjuvant TMZ Versus Standard of Care in Newly Diagnosed Glioblastoma (GBM) (PHASE3, RECRUITING): This is a Phase 3 prospective, randomized, superiority, open-label, multi-site study. The overview of this study is as follows: * A Screening/Baseline Period of 21 days. During this time, patients will be randomized into a 1:2 allocation of Arm A:Arm B. * A Perioperative/Operative Phase where patients will undergo tumor resection (Arm A) or tumor resection plus GammaTile implantation (Arm B). * An EBRT Prior to Start Period. This occurs within 10 business days prior to EBRT and Concurrent TMZ Phase. * An EBRT and Concurrent TMZ Phase, which will begin 30 ±10 days post-surgery. EBRT (30 fractions) and TMZ will be administered up to 5 days a week for 6 weeks in Arm A, and EBRT (20 fractions) and TMZ will be administered for up to 5 days a week for 4 weeks in Arm B. TMZ will be administered at a dose of 75 mg/m2/day orally for each Arm. * An Adjuvant TMZ Phase, which begins 28 ±7 days following the EBRT and Concurrent TMZ Phase, and is comprised of six 28-day cycles. TMZ (150-200 mg/m2/day orally) will be administered for the first 5 days of each 28-day cycle for each Arm. Tumor treating fields are allowed but are not mandated during this phase. Up to 6 additional cycles (for a total of 12) can be completed at the discretion of the Investigator. * An Early Discontinuation/Follow-Up Phase will occur 28 ±7 days after completion of Cycle 6 of the Adjuvant TMZ Phase, regardless of the total number of cycles completed or any delays in cycle start. If fewer than six cycles are completed, the first follow-up assessment will occur 28 ±7 days after the last administered dose of adjuvant TMZ. If patient has a qualifying event requiring entrance to Early Discontinuation Phase, the first follow-up assessment will occur as soon as feasible, but within 28 days. For any unscheduled visits, data collected should be documented in the case report form (CRF) and must include, but are not limited to, safety evaluations, survival status, and disease status.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07195591
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07193654 - Stupp Regimen Combined With Intrathecal Injection of Thiotepa for the Treatment of Glioblastoma With Ventricular Invasion or Meningeal Metastasis：a Prospective, Single-Arm, Exploratory Study (PHASE2, RECRUITING): The goal of this clinical trial is to learn if a combined treatment approach can treat glioblastoma (GBM) with ventricular invasion or meningeal metastasis in adults. The main questions it aims to answer are: Does the combined treatment of radical radiotherapy, the Stupp regimen (oral temozolomide), and intrathecal injection of thiotepa improve progression-free survival compared to standard treatment alone? Does the combined treatment improve overall survival compared to standard treatment alone? Participants will: * Undergo maximal surgical resection of the tumor； * Receive radical radiotherapy； * Take oral temozolomide according to the Stupp regimen； * Receive intrathecal injections of thiotepa。
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07193654
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07143812 - Clinical Research of Suicide Gene Expressing Allogenic Bone Marrow Derived Mesenchymal Stem Cells(MSC11FCD) in Patients With Newly Diagnosed Glioblastoma (PHASE1, RECRUITING): This is a phase I clinical trial evaluating the safety, tolerability, and maximum tolerated dose of MSC11FCD, an investigational allogeneic bone marrow-derived mesenchymal stem cell therapy expressing a suicide gene, in patients with newly diagnosed glioblastoma. The investigational product is administered intratumorally following surgical resection. This study aims to explore whether MSC11FCD can provide a targeted, localized treatment option during the postsurgical period, potentially addressing residual tumor cells and reducing early recurrence.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07143812
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07138001 - A Randomized, Controlled, Open-label, Multicenter Phase 2 Clinical Trial to Evaluate the Efficacy and Safety of KH617 in Combination With Temozolomide Versus Investigator's Choice Treatment or KH617 Monotherapy for Recurrent Glioblastoma (PHASE2, NOT_YET_RECRUITING): To evaluate the efficacy and safety of KH617 for injection in combination with temozolomide versus investigator's choice therapy or KH617 monotherapy for recurrent glioblastoma
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07138001
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07130149 - Clinical Investigation of Sonodynamic Therapy in Conjunction With Chemoradiotherapy for Glioblastoma Management (PHASE2, ENROLLING_BY_INVITATION): This Phase II trial tests if sonodynamic therapy (SDT)-a non-invasive treatment using ultrasound to activate a cancer-killing drug-improves outcomes for newly diagnosed glioblastoma patients. Who? 230 adults (\<75 years) with confirmed glioblastoma, adequate organ function, no major health issues. Groups: Test Group: SDT + standard therapy (radiation, chemo, bevacizumab). Control Group: Standard therapy alone. Procedure: SDT uses the drug Hiporfin® followed by focused ultrasound sessions. Patients avoid sunlight for 1 month. Study Duration: Treatment: \~6-8 weeks. Follow-up: 24 months (monthly MRIs). Key Goal: Compare progression-free survival (time until tumor worsens) between groups. Secondary goals: overall survival, safety.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; limited-enrollment.
  Source: https://clinicaltrials.gov/study/NCT07130149
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07091864 - Phase II Randomized Trial Of Glucose Monitoring In Glioblastoma (NA, RECRUITING): This clinical trial studies whether continuous glucose monitoring (CGM) can be used to help patients with glioblastoma manage their blood sugar (glucose) levels and improve survival. Glioblastoma is the most common malignant primary brain tumor in adults, with an average survival time of approximately 15-18 months despite therapy. Studies have shown that having a higher-than-normal amount of glucose in the blood (hyperglycemia) during radiation therapy is associated with poorer survival outcomes in glioblastoma patients. Hyperglycemia in glioblastoma patients is often driven by steroids that are commonly used during treatment. CGM uses a device that places a sensor under the skin that monitors glucose levels at regular intervals, providing real-time, or near real-time, glucose information. This can help to identify when a patient has changes in their glucose levels so they may receive necessary interventions or medications sooner. CGM may be an effective way for glioblastoma patients to manage their glucose levels, which may improve survival.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07091864
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07047066 - A Phase II Clinical Study to Evaluate the Efficacy and Safety of Flazoparib Combined With Temozolomide After the Completion of Standard Concurrent Chemoradiotherapy (CCRT) in Newly Diagnosed Glioblastoma (PHASE2, NOT_YET_RECRUITING): A Phase II clinical study is planned to evaluate the efficacy and safety of fluzoparib combined with temozolomide in newly diagnosed glioblastoma patients after completing standard concurrent chemoradiotherapy (CCRT), explore the effectiveness and safety of this regimen, and find a better treatment option for glioblastoma patients
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07047066
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06936046 - Enhanced Adjuvant Therapy for Newly Diagnosed Glioblastoma With Partial Surgical Resection or Short-term Progression: a Bayesian Adaptive Randomized Phase II Study (PHASE2, RECRUITING): This study is a prospective Bayesian adaptive randomized phase II clinical trial of enhanced adjuvant therapy for newly diagnosed glioblastoma with partial surgical resection or short-term progression. The Stupp regimen is the standard treatment regimen (control group), while the experimental group receives enhanced treatment by combining different drugs or increasing the radiation dose based on the Stupp standard treatment regimen. Participants will undergo screening and evaluation according to the inclusion and exclusion criteria of the protocol, within 28 days prior to randomization. Patients who agree to participate in this study will sign an informed consent form (ICF) prior to the screening process. After completing all screening activities, those who meet the criteria can start receiving study treatment. Based on sample size estimation, a total of 210 patients are planned to be enrolled. Among the first 28 patients, an average of 7 patients will be allocated to each group for initial randomization to ensure the balance of each group in the early stages of the trial. Starting from the 29th patient, the 12-month PFS rate will be re estimated for every 15 patients enrolled, and the subsequent randomization probability will be calculated based on the observed data. On the first day of self adjuvant therapy, the PD-1/VEGF bispecific group received intravenous administration of PD-1/VEGF bispecific antibody 20mg/kg treatment, with 21 days per cycle, is expected to be administered for a total of 8 cycles. The PD-1/CTLA-4 dual antibody group received intravenous infusion of 6mg/kg PD-1/CTLA-4 dual antibody once on the first day of self adjuvant therapy, with 14 days per cycle. It is expected to be administered for a total of 12 cycles. The dose adjusted Stupp regimen group (mStupp) administered PGTV locally to residual or short-term recurrent lesions after surgery 66Gy/30Gy high-dose irradiation, PTV1 60Gy/30F in high-risk areas around the tumor bed, and 54Gy/30F radiotherapy in low-risk areas. Each group will have weekly blood routine, liver and kidney function, myocardial enzyme spectrum, thyroid function, electrocardiogram, and head MR every 4 weeks to evaluate the efficacy and toxic side effects. Follow up observation will be conducted. The study will start on January 1, 2025 and end on December 31, 2027, to explore the efficacy of enhanced adjuvant therapy for newly diagnosed glioblastoma with partial surgical resection or short-term progression.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06936046
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06780592 - The Efficacy of Vebreltinib Combined With Temozolomide for Glioblastoma (GBM) After Surgery: a Study Protocol for a Prospective, Open-label ,Multi-center, Randomized, Controlled Trial in China (PHASE2, NOT_YET_RECRUITING): The purpose of this study is to explore the effects of Vebreltinib in primary glioblastoma patients receiving a combination therapy of chemotherapy (temozolomidel) and MET-TKI.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06780592
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06595186 - A Multicenter, Single Arm, Open-label, Dose-escalation Phase 2 Study of JK-1201I Combined with Adjuvant Temozolomide in Patients with Newly Diagnosed Glioblastoma Multiforme (GBM) After Surgery and Concomitant Radio-chemotherapy (PHASE2, RECRUITING): This study was designed to evaluate the safety, tolerability, efficacy and pharmacokinetics of JK-1201I combined with adjuvant temozolomide in patients with newly diagnosed glioblastoma multiforme after surgery and concomitant radio-chemotherapy.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06595186
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: newly_diagnosed
- NCT06533163 - Low-Intensity Oscillatory Magnetic Therapy in Patients With Newly Diagnosed Glioblastoma Multiforme (GBM) - An Exposure-time Escalation Pilot Trial (NA, RECRUITING): The clinical investigation is a non-randomized, multicenter, open-label, prospective, exposure-time escalation clinical investigation. The clinical investigation is designed to assess the clinical safety and performance of the Oncomagnetic Device.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06533163
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06524063 - Phase I Clinical Study of Targeted Survivin DC Cell Injection for the Treatment of Newly Diagnosed Primary Glioblastoma Multiforme (GBM) (PHASE1, NOT_YET_RECRUITING): Primary Objective: To evaluate the safety and tolerability of targeted Survivin DC cell injection for postoperative treatment of newly diagnosed primary glioblastoma multiforme. Secondary Objectives: Utilize progression-free survival (PFS) and overall survival (OS) to preliminarily assess the effectiveness of targeted Survivin DC cell injection for postoperative treatment of newly diagnosed primary glioblastoma multiforme in China. Evaluate the immunological effects of targeted Survivin DC cell injection. Explore the impact of targeted Survivin DC cell injection on human DC cell activity and in vivo processes. Patients will undergo a combined treatment of radiotherapy and temozolomide (TMZ) for a duration of 6 weeks, with concurrent chemotherapy. After completing this phase, there will be a 4-week interval (28 days) before entering multiple cycles of adjuvant TMZ chemotherapy. Each cycle will last 28 days, involving daily oral administration of temozolomide at a dose of 150-200mg/m2 for 5 consecutive days, followed by a 23-day drug-free period. This entire cycle will be repeated every 28 days. Nine days after completing the standard 6-week concurrent chemoradiotherapy, targeted Survivin DC cell injections will be administered. The injections will be given on days 0, 14, and 28. The administration will involve both intradermal (ID) and intravenous (IV) routes. Four hours before the administration, the injection sites will be pre-treated with lidocaine cream. The injection procedures will be conducted sequentially, starting with ID injection. After completing the ID injection, a 30-minute observation will be conducted. If no adverse reactions are observed, IV infusion will be initiated. Both IV infusion and ID injection will be performed on the same side. Intradermal Injection: Draw 1ml of cell suspension with a 1ml syringe, and the remaining cell product will be stored at 2-8℃. Administer the drug immediately after preparation. Intravenous Infusion: Before administration, infuse 20ml of normal saline through IV.Extract 25ml of normal saline, dilute the remaining cell product (5ml), and administer it through IV infusion. Control the room temperature during infusion and complete it within 30 minutes. After administration, inject 50ml of normal saline into the cell bag to ensure all cell products are returned to the patient's body.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06524063
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06512311 - Personalized Targeted Glioblastoma Therapies by ex Vivo Drug Screening: Advanced Brain Tumor TheRApy Clinical Trial (ATTRACT) (NA, RECRUITING): Patient derived cell line (PDC) -based drug screening will be applied to formulate a personalized treatment approach.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06512311
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06477939 - Phase III Randomized Study of Adding or Not Liposomal Transcrocetin (L-TC) With Concomitant HypoFractionated Radiation ThErapy and TEmozolomide in Newly Diagnosed GLioblastoma (GBM) Patients to Evaluate Efficacy and Safety (PHASE3, NOT_YET_RECRUITING): This is phase III randomized, multicenter study adding or not intra-venous Liposomal Trasncrocetin (L-TC) to hypofractionated radiotherapy and concomitant Temozolomide followed by adjuvant Temozolomide in patients with histologically confirmed diagnosis of glioblastoma (GBM).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06477939
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06419946 - Phase III Trial of Temozolomide/Lomustine (TMZ/LOM) Combination Therapy vs. Standard TMZ Therapy for Newly Diagnosed MGMT Promoter Methylated Glioblastoma (IDHwt) Patients +/- Tumor Treating Fields (Optune) (PHASE3, NOT_YET_RECRUITING): Background: Glioblastoma (GBM) is notoriously difficult to treat, with current therapies often extending life by only a few months. The standard treatment involves surgery followed by radiation and chemotherapy with Temozolomide (TMZ). The efficacy of TMZ, however, is significantly enhanced when the tumor's o6-methylguanine-DNA-methyltransferase (MGMT) gene is methylated. Recent studies, such as the NOA-09 trial, have suggested that adding Lomustine (LOM) to TMZ could improve outcomes for patients with this specific tumor profile. Hypothesis: The investigators hypothesize that the addition of LOM to the TMZ regimen will lead to significantly improved survival rates among patients with newly diagnosed glioblastoma who have a methylated MGMT promoter compared to those receiving only TMZ. Treatment Plans: The study will randomly assign participants to two groups: * Control Group: Standard treatment with TMZ during and after radiation therapy. * Experimental Group: TMZ combined with LOM, starting on the first day of radiation therapy. Outcome Measures: The primary outcome measure will be survival. Other outcomes will include progression-free survival (time from randomization until tumor progression or death), safety profiles (adverse effects of the treatments), and quality of life measures as well as neurocognitive outcomes.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06419946
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06176066 - PH Weighted Chemical Exchange Saturation Transfer Based Surgical Resections of Glioblastoma (PHASE1, RECRUITING): Current standard of care therapy and all FDA approved adjuvant therapy for glioblastoma continue to provide less than 12 months of progression free survival (PFS) and less than 24 months of overall survival (OS). There is an extreme need for any novel therapy against glioblastoma that increases progression free survival and overall survival in patients diagnosed with this invasive form of cancer. A significant reason for such a poor prognosis is the infiltrative nature of this tumor in non-enhancing regions (NE) beyond the central contrast-enhancing (CE) portion of tumor, which is difficult to visualize and treat with surgical, medical, or radiotherapeutic means. Since tumor cells exhibit abnormal metabolic behavior leading to extracellular acidification, we theorize a newly developed pH-sensitive MRI technique called amine chemical exchange saturation transfer echoplanar imaging (CEST-EPI) may identify infiltrating NE tumor beyond what is clear on standard MRI with gadolinium contrast. This phase I safety study will use use intraoperative CEST-EPI guided resections in glioblastoma at increasing distances from areas of CE tumor to test whether this technique is safe and can remove additional areas of infiltrative NE tumor. The primary objective of this study is to assess the safety of pH-sensitive amine CEST-EPI guided resections for glioblastoma.The secondary objectives of this study include: 1. A preliminary efficacy analysis of CEST-EPI guided resections in extending progression free and overall survival. 2. To confirm that resected tissue obtained from pH-sensitive amine CEST-EPI guided resections contain infiltrating NE tumor. The primary endpoint for this study will be safety of resecting "CEST positive", acidic regions within T2 hyperintense regions of glioblastoma thought to contain active NE tumor at increasing distances from contrast enhancing tumor with development of a recommended maximal tolerated resection. 1. At the maximal tolerated resection, a preliminary efficacy study with endpoints of progression free survival (as defined by RANO Resect 2.0) 1 and overall survival. 2. Quantitation of infilitrating tumor burden on CEST-EPI resected tissue using immunohistochemical staining. 12 patients up to 24 patients based on resection limiting toxicities with potential expansion of up to 16 patients at the maximum tolerated resection. Inclusion Criteria: 1. Must be able to provide written informed consent 2. Male or female \> 18 years of age 3. Karnofsky Performance Scale (KPS) \> 70 (indicating good performance status). 4. Individuals with suspected, newly diagnosed or recurrent IDH wild type WHO IV glioblastoma (intraxial, expansile contrast-enhancing mass without evidence of metastatic disease. This will be reviewed by UCLA neuroradiology to only include patients with high likelihood of GBM) Exclusion Criteria: 1. Pediatric patients 2. Diagnostic uncertainty (reviewed by UCLA neuroradiology history extracranial malignancy or autoimmune disease) 3. Medical conditions that make patients a poor candidate for anesthesia and/or surgery (decision for surgery will follow standard pre-operative clearance guidelines and will not differ for this specific study from standard of care treatment plan) 4. Involvement of eloquent areas (as defined by MRI signal clearly involving areas that would lead to a qualifying neurologic deficit as defined in surgical limiting toxicity - this will specifically include: 1) primary motor cortex, 2) primary sensory cortex, 3) sensorimotor fibers as defined on pre-operative diffusion tensor imaging, 4) primary language areas (Broca, Wernicke), 5) arcuate fasiculus as defined on pre-operative diffusion tensor imaging Pre-operative: Standard of care pre-operative MRI including perfusion and pH-weighted amine CEST-EPI (which will add up to 15 minutes of scan time) for a single pre-operative exam prior to surgery. Surgery: 1 day (subjects to be admitted to the hospital) Follow-up: inpatient stay (1-3 days), 2 week clinical assessment (outpatient post-op clinic visit). MRI and clinical assessment at 4 weeks (end of resection limited toxicity window). Following this, there will be standard of care follow up with MRI and clinical assessment starting at 8 weeks +/- 4 weeks (per RANO 2.0). 1 Total study duration for recruitment, enrollment, and study completion of all subjects is up to 2 years. Single-arm, surgical resection escalation safety trial with a preliminary efficacy study at the maximal tolerated resection This safety evaluation will mimic a phase 1 dose escalation safety study using a rule based approach on based on a i3+3 design.2 Using standard of care resection of contrast enhancement as the baseline, we will begin with 3 subjects with maximal resection + "CEST positive" areas 0.7 cm from the contrast enhancing boundary within areas of T2 hyperintensity. If there is not \> 1 pre-determined resection limiting toxicity (RLT, defined below) in this cohort, the r
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06176066
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06140875 - Amplitude Modulated Radiofrequency Electromagnetic Field Treatment Combined With Radiochemotherapy and Maintenance Chemotherapy in Patients With Glioblastoma (Brain-RF) (NA, RECRUITING): Combined chemoradiation and radiofrequency electromagnetic field treatment for patients with glioblastoma
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06140875
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: newly_diagnosed
- NCT06132438 - Immunotherapy Targeting of Cytomegalovirus Antigens in Glioblastoma (INTERROGATE-GBM) (PHASE1, NOT_YET_RECRUITING): In Australia, glioblastoma (GBM) has a higher annual fatality rate than a variety of other cancers, such as melanoma, bladder, and kidney tumors. While the 5-year survival rate for other cancers, such as breast and prostate cancer, has increased, there have been no notable advancements in GBM during the past ten years, and the incidence and mortality patterns have barely changed between 1982 and 2011. In particular, GBM poses a challenging therapeutic dilemma for patients and physicians due to its aggressive biology and resistance to available treatments. Recent studies showed that cytomegalovirus (CMV) is expressed in GBM tumors, making it a good target for immunotherapy trials. This phase I trial aims to determine the safety and tolerability of the PEP-CMV vaccine in patients with newly diagnosed MGMT-unmethylated GBM in combination with one cycle of adjuvant temozolomide.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06132438
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05904119 - Lomustine With and Without Reirradiation for First Progression of Glioblastoma: a Randomized Phase III Study (PHASE3, RECRUITING): Despite comprehensive multimodal treatment of newly diagnosed glioblastoma, almost all patients suffer from tumour relapse. Currently, no standard of care exists to treat these tumour relapses. Treatment options include repeated surgery (if feasible), systemic therapy (bevacizumab, lomustine, temozolomide re-challenge), reirradiation and best supportive care. Currently, the superiority of combined chemoradiation versus chemotherapy alone remains unproven. Given that lomustine is the standard chemotherapeutic agent for the treatment of recurrent glioblastoma in Europe and the unclear efficacy of reirradiation, we want to explore whether combining lomustine and reirradiation may be a better treatment than lomustine alone. The results of the prospective randomized trial proposed here should demonstrate a significant improvement in overall survival when lomustine is combined with reirradiation in patients with recurrent glioblastoma compared to lomustine alone without adversely affecting quality of survival. The trial will be stopped based on overall survival in a preplanned futility and efficacy interim analysis.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05904119
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05768919 - Phase I/II Study of the Tolerability, Safety, and Efficacy of Liposomal Curcumin in Combination With Radiation and Temozolomide in Patients With Newly Diagnosed High-Grade Gliomas (PHASE1, PHASE2, RECRUITING): The objective of this study is to assess the tolerability, safety, and efficacy of Liposomal Curcumin (LC) in combination with radiotherapy (RT) and Temozolomide (TMZ) in patients with newly diagnosed High-Grade Gliomas (HGG).
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05768919
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05768087 - Escalated Dose Proton Therapy Within the Multimodality Treatment of Glioblastoma Patients - A Phase 1 Proton Dose Finding Trial - (NA, RECRUITING): The goal of this phase 1 dose finding study is to to assess the clinical tolerability and safety of escalated dose proton therapy in glioblastoma patients treated with multimodality treatment, according to treatment volume. The main questions it aims to answer are: * what is the maximum tolerated proton dose in glioblastoma patients? * is the maximum tolerated proton dose in glioblastoma patients dependent on treatment volume? * what is the recommended phase 2 proton dose in glioblastoma patients? Patients will be asked to undergo radiotherapy to step-wise escalated doses using proton therapy as part of their multimodality treatment. Patients will be monitored closely for treatment effects.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05768087
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05736406 - An Interventional, Multicenter, and International Phase 1/2, Light-dose-escalation Study to Investigate the Safety and Feasibility of Intraoperative Photodynamic Therapy (PDT) With Pentalafen® Drug and Heliance® Solution Device in Male and Female Patients 18 to 75 Years of Age With Grade IV Glioblastoma. (PHASE1, PHASE2, RECRUITING): The primary objective of this clinical trial is to determine the safety and tolerability of two doses of light in intraoperative PDT added to standard of care; temozolomide-based chemotherapy in male and female patients aged 18 to 75 with newly diagnosed glioblastoma. This treatment will be carried out in addition to the maximal surgical resection. Data collected during this trial will be used to design the upcoming pivotal study . The study will utilize an independent Data and Safety Monitoring Board (iDSMB) that will review safety data to allow dose escalation.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05736406
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05708352 - A Randomized Controlled Phase 2 Study of the Ketogenic Diet Versus Standard Dietary Guidance for Patients With Newly Diagnosed Glioblastoma in Combination With Standard-of-care Treatment (PHASE2, RECRUITING): This is a Phase 2, randomized two-armed, multi-site study of 170 patients with newly diagnosed glioblastoma multiforme. Patients will be randomized 1:1 to receive Keto Diet, or Standard Anti-Cancer Diet. All patients will receive standard of care treatment for their glioblastoma. The Keto Diet intervention will be for an 18-week period and conducted by trained research dietitians. Daily ketone and glucose levels will be recorded to monitor Keto Diet adherence. This two-armed randomized multi-site study aims to provide evidence to support the hypothesis that a Keto Diet vs. Standard Anti-Cancer Diet improves overall survival in newly diagnosed glioblastoma multiforme patients who receive standard of care treatment.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05708352
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05664464 - A Phase Ib/II Randomized, Open Label Drug Repurposing Trial of Glutamate Signaling Inhibitors in Combination With Chemoradiotherapy in Patients With Newly Diagnosed Glioblastoma (PHASE1, PHASE2, RECRUITING): The goal of this 1:1 randomized, multi-center, open-label phase Ib/II clinical trial is to explore the efficacy of the add-on of the anti-glutamatergic drugs gabapentin, sulfasalazine and memantine to standard chemoradiotherapy with temozolomide compared to chemoradiotherapy alone in patients with newly diagnosed glioblastoma.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05664464
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05380349 - A Phase 1 Study of Combination Drug Therapy Based on Personalized Cancer Stem Cell (CSC) High-Throughput Drug Screening (HTS) With Standard of Care for Newly Diagnosed Glioblastoma (EARLY_PHASE1, RECRUITING): Proposed treatment of subjects with newly diagnosed glioblastoma with novel personalized drug regimens identified to be effective in vitro using cancer stem cells derived from their individual tumors, alongside standard of care radiation and TMZ.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05380349
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05235737 - A Single Center, Open-Label, Randomized Study to Evaluate the Safety and Efficacy of Neoadjuvant and Adjuvant Pembrolizumab on Top of Standard Chemo-Radiotherapy (Stupp Protocol) in Treatment of Patients With Newly Diagnosed Glioblastoma Multiforme (GBM). (PHASE4, RECRUITING): To evaluate the short-term and longer-term safety, tolerability, and effectiveness of neoadjuvant and adjuvant Pembrolizumab on top of standard therapy (Stupp protocol) in patients with Glioblastoma Multiforme (GBM). Randomized comparison of safety, tolerability, and clinical efficacy of (1) neoadjuvant and adjuvant Pembrolizumab (on top of Stupp protocol, n=12 patients), (2) neoadjuvant Pembrolizumab (on top of Stupp protocol, n=12 patients), and (3) standard of care (Stupp protocol only, n=12 patients). Immuno-PET examination will be performed before and after surgery in all patients.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05235737
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 8 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT04443010 - A Study to Evaluate the Safety and Efficacy of the Tumor-targeting Human Antibody-cytokine Fusion Protein L19TNF Plus Standard Temozolomide Chemoradiotherapy in Patients With Newly Diagnosed Glioblastoma (PHASE1, PHASE2, RECRUITING): The purpose of this study is to explore the safety profile and establish a recommended dose (RD) for phase II of the antibody-cytokine fusion protein L19TNF plus standard TMZ chemoradiotherapy in patients with newly diagnosed glioblastoma. The study will be conducted in three consecutive parts: a dose finding part to determine the RD of L19TNF in combination with chemoradiotherapy, followed by a signal seeking part that investigates first signs of activity and then an activity evaluation part that studies the efficacy of L19TNF in combination with chemoradiotherapy against chemoradiotherapy alone.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04443010
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT04373785 - A Multi-Center Pilot/Phase I and Phase II Clinical Trial of NG101m Adjuvant Therapy in Newly Diagnosed Glioblastoma Patients (PHASE1, PHASE2, NOT_YET_RECRUITING): The purpose of this clinical trial is to evaluate the addition of NG101m adjuvant therapy to standard of care treatment of glioblastoma multiforme. All subjects will receive NG101m capsules along with the standard treatment of temozolomide and radiation.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT04373785
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT04115761 - A Phase II, Randomized, Open-Label, Parallel-Group Study to Evaluate the Efficacy and Safety of Autologous Dendritic Cell Vaccination (ADCV01) As an Add-On Treatment for Primary Glioblastoma Multiforme (GBM) Patients (PHASE2, RECRUITING): This study is designed with open-label and randomized parallel group to evaluate the efficacy and safety of autologous dendritic cell vaccination (ADCV01) as an add-on treatment for primary glioblastoma multiforme
  Quick read: GBM-specific treatment study for newly diagnosed GBM; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04115761
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT02704858 - An Open-Label, Phase 1/2A Dose Escalation Study of Safety and Efficacy of NEO100 in Recurrent or Progressive Grade III or Grade IV Gliomas With IDH1 Mutation (PHASE1, PHASE2, RECRUITING): This multi-site, Phase 1/2a clinical trial is an open-label study to identify the safety, pharmacokinetics, and efficacy of a repeated dose regimen of NEO100 (perillyl alcohol) for the treatment of patients with radiographically-confirmed progression of Grade IV glioma or recurrent primary or secondary Grade IV glioma. The study will have two phases, Phase 1 and Phase 2a. Phase 1 is a standard cohort dose escalation 3+3 design used to determine the maximum tolerated dose for Phase 2a. There will be up to 24 patients enrolled in Phase 1. There will be 25 patients enrolled in Phase 2a. For both phases of the study, NEO100 will be self-administered four times daily for a 28-day treatment cycles until disease progression, death or patient withdraw from study for any reason, whichever occurs first. Version 10 of the protocol changed the inclusion criteria for Phase 2a to limit inclusion to those patients with progressive or recurrent primary or secondary Grade IV gliomas expressing IDH1 mutations. Prior to the protocol amendment, 4 patients were enrolled who were IDH1 wild-type. Therefore, an additional 28 patients will be recruited for a total of 32 patients enrolled into Phase 2a of this study to have 35 evaluable cases. Version 12 of the protocol expanded the inclusion criteria for Phase 2a to include those patients with progressive or recurrent Grade III Astrocytoma expressing IDH1 mutations. Review of the literature specific to these patients found the same expected time to progression and death. As a result, the number of patients to enroll remains 32 to have 35 evaluable cases.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02704858
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT02613988 - Early Response Assessment Using on 3T Advanced MR Imaging as Predictor of Long-term Treatment Response in Newly Diagnosed Glioblastomas (NA, RECRUITING): This clinical trial studies advanced MR imaging techniques in measuring early response of standard treatment may become predictors of long-term treatment response in patients with newly diagnosed glioblastomas.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02613988
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT01777919 - A PHASE II CLINICAL TRIAL FOR THE EVALUATION OF THE EFFICACY OF DISULFIRAM/COPPER COMBINATION AS AN ADJUVANT AND CONCURRENT CHEMOTHERAPY IN THE TREATMENT OF NEWLY DIAGNOSED GLIOBLASTOMA MULTIFORM (PHASE2, NOT_YET_RECRUITING): Glioblastoma multiform (GBM) is the most common malignant primary brain tumor in adults. Despite maximal treatment tumor relapse occurs regularly accompanied by unfavourable prognosis. Among other reasons, it is believed that this could be in part due to the existence of the so-called tumor stem cells (TSCs), a cellular subfraction within GBM which escape therapy by being highly resistant to irradiation and chemotherapy and thus constituting the source of tumor recurrence. GBM, like many other cancers, show a sub-population of aldehyde dehydrogenase (ALDH) overexpressing TSCs. More specifically, ALDH1A1, a cytoplasmatic isoform of ALDH, proved to be a novel stem cell marker in human GBM. In addition, ALDH1A1 has been shown to be a mediator for resistance of GBM to temozolomide (TMZ) and a reliable predictor of clinical outcome; prognosis of patients with a high level of ALDH1A1 expression was poor compared with that of patients with low levels. Consequently, ALDH1A1 may serve as a potential target to improve treatment of human GBM through inhibition of the enzyme. Disulfiram (DSF) has been used for more than sixty years in the treatment of chronic alcoholism because of the unpleasant symptoms it provokes after ethanol intake. The underlying mechanism is believed to be the accumulation of acetaldehyde in the blood, due to inhibition of the liver ALDHs. Actually, DSF is a strong inhibitor of ALDH1A1 and relatively non-toxic at therapeutic (for chronic alcoholism) doses that can penetrate the blood-brain barrier. In addition, DSF has been shown to be cytotoxic on GBM stem-like cells, inhibiting the growth of TMZ resistant GBM cells and blocking self-renewal by \~100% , while it has been identified as an inhibitor of human GBM stem cells in high-throughput chemical screens. Interestingly, a number of these actions were copper-dependent. In the current Phase II clinical trial, DSF/copper combination will be tested as an adjunctive and concurrent chemotherapy in the treatment of newly diagnosed GBM. According to our hypothesis, initiation of DSF chemotherapy after the resection of the tumor and before the introduction of the standard radio-chemotherapy will inhibit ALDH1A1 of GBM TSCs making them more susceptible to radio-chemotherapy and possibly reducing the recurrence rate of GBM. On the other hand, the addition of copper will probably enhance the cytotoxic effects of DSF possibly through augmentation of its pro-apoptotic and proteasomal inhibitory actions.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT01777919
  Review priority: 153
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery, Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07492836 - Prospective, Pilot Study to Evaluate Hypofractionated Radiotherapy Associated With Temozolomide in Patients Aged 18 to 70 Years With Glioblastoma (HypoGBM) (NA, NOT_YET_RECRUITING): The goal of this clinical trial is to evaluate the feasibility, safety and effectiveness of radiotherapy with fewer days of treatment and a higher dose of radiation each day in patients under 70 years of age diagnosed with a brain tumor known as glioblastoma.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07492836
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07461948 - Advanced MRI for Visualization and Quantification of the Tumor Immune Microenvironment (TIME) in Glioblastoma (PHASE3, RECRUITING): This phase III trial is evaluating whether a combination of three advanced magnetic resonance imaging (MRI) techniques, including chemical exchange saturation transfer (CEST) MRI, diffusion-relaxation correlation spectrum imaging (DR-CSI), and ferumoxytol-enhanced magnetic resonance imaging (Fe-MRI) are effective as non-invasive methods for assessing the cells and proteins that surround and interact with tumor cells (the tumor immune microenvironment) in patients with glioblastoma. Researchers understand that some types of brain tumors are harder to treat than others, but the reasons for this are not known in many cases. CEST MRI uses differences in the tissue microenvironment, like protein concentration or intracellular pH, to generate contrast differences. DR-CSI detects microstructural changes in tissue associated with immune cells infiltrating the tumor. Fe-MRI uses ferumoxytol as a contrast agent with MRI. Contrast agents are substances that are injected into the body and taken up by certain tissues, making the tissues easier to see in imaging scans. More advanced imaging techniques like CEST, DR-CSI, and Fe-MRI may offer less invasive methods than surgery or biopsy for helping researchers understand the tumor immune microenvironment in patients with glioblastoma, which may help researchers determine why some tumors are more resistant to treatment.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07461948
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07368283 - A Single-arm Phase II Non-inferiority Clinical Study of Limited Target Volume Radiotherapy After Glioblastoma Surgery (NA, NOT_YET_RECRUITING): Research on radiotherapy target volumes for glioblastoma is increasingly focused on exploring more limited yet effective irradiation fields, aiming to achieve local control while minimizing acute and long-term neurotoxicity. Previous retrospective analysis by investigators revealed that local recurrences of glioblastoma are predominantly confined to a narrow margin around the original lesion: 98.3% of recurrences occurred within 0.5 cm of the original T2-FLAIR abnormality, 94.8% within 1 cm of the original T1-enhanced region. These findings have been cited in the ESTRO-EANO treatment guidelines. Building on this evidence, investigators plan to conduct a single-arm, phase II clinical trial to systematically evaluate the efficacy and safety of a 1 cm radiotherapy target volume in post-operative glioblastoma patients.Eligible patients with glioblastoma who have undergone surgical resection will be selected to receive limited-field radiotherapy. The target volume will be defined based on the postoperative MRI enhancing lesion: a 1 cm margin will be added to form the clinical target volume (CTV), followed by a further 0.3 cm margin to create the planning target volume (PTV). A total dose of 60 Gy will be delivered in 30 fractions (2 Gy per fraction, 5 fractions per week). Concurrent and adjuvant chemotherapy will be administered per standard guidelines. The primary efficacy endpoints are the 6-month progression-free survival rate and the incidence of symptomatic radiation-induced brain necrosis of grade 3 or higher. Secondary endpoints include overall survival, patterns of recurrence, neurocognitive function, and quality of life.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07368283
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07144735 - Allogeneic Gamma Delta (γδ) T Cells for the Treatment of Glioblastoma (NA, RECRUITING): This first-in-human clinical study aims to evaluate the safety and feasibility of locally delivered, allogeneic γδ T cells (genetically edited with ARIH1 and BCL11b knockout, designated ABOUT γδT cells) in patients with glioblastoma multiforme (GBM). The engineered effector cells are delivered via localized administration to selectively target and eliminate residual GBM cells. ABOUT: ARIH1 and BCL11b knockOUT γδ T cells.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07144735
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07089758 - A Pilot Feasibility Study for Cerebral Open Flow Microperfusion in Patients Undergoing Planned Neurosurgical Resection of Diseased Parenchyma. (NA, NOT_YET_RECRUITING): The purpose of this study is to evaluate the safety and feasibility of intra-operative microperfusion during a planned neurosurgical resection of diseased brain parenchyma, including either an epileptic focus requiring temporal lobectomy or a glioma. Devices used for microperfusion are Joanneum Research cerebral open flow microperfusion (OFM) catheters, push and pull tubing, and MPP102-II pump.
  Quick read: GBM-specific treatment study for GBM or glioma patients; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07089758
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT07067905 - Clinical Evaluation of [68Ga]Ga-XT771 PET for Diagnosis in Patients With Glioblastoma and Clear Cell Renal Cell Carcinoma (EARLY_PHASE1, RECRUITING): A prospective, open-label, phase 1 study. This clinical trial aims to evaluate the diagnostic value of 68Ga-XT771, a CAIX/CAXII protein-specific probe, in PET/CT imaging for patients with clear cell renal cell carcinoma and glioblastoma. Safety, tolerability, and biodistribution characteristics of 68Ga-XT771 will also be assessed.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07067905
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06781372 - Development and Characterization of Patient's Derived Organoids as a Platform for the Screening of Novel Therapeutic Treatments for Glioblastoma Multiforme (NA, NOT_YET_RECRUITING): The study will enroll patients suffering from glioblastoma, a malignant brain tumor. Intervention is intended as a laboratory intervention and not as a clinical intervention. In fact, tumor removed from patients' brains will be sent to a dedicated laboratory to obtain an "avatar" of the tumor, named patient-derived organoid (PDO). A number of experimental antitumor approaches will be studied on PDOs. Results of these experiments will be correlated to the prognosis of patients.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06781372
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06764537 - Evaluation of in Vitro Antitumor Activity of GD2 CAR-T Cells Generated From Blood of Glioblastoma Patients (NA, NOT_YET_RECRUITING): Glioblastoma is a brain tumor with a very poor prognosis, affecting around 2,400 new patients every year. Current treatments do not provide good control of the disease. In view of the therapeutic impasse, it is necessary to develop new strategies. CAR-T cells (Chimeric antigen receptor T cells) represent a highly promising therapy for the treatment of incurable cancers, including glioblastoma. This treatment aims to destroy cancer cells by relying on the patient's own immune system. CAR-T cells are generated from the patient's own immune cells, more specifically T lymphocytes, which are genetically modified to express a tumor-specific receptor on their surface. CAR-T cells bind to tumor cells and cause their destruction. However, these cells have shown limited therapeutic power in the treatment of brain tumors. This is mainly due to the microenvironment surrounding the tumor, which is composed of immunosuppressive cells. These cells, and the molecules they secrete, help to reduce the activity of CAR-T cells that would otherwise reach the tumor. Little is currently known about these resistance mechanisms. The aim of this research is therefore to better understand these resistance mechanisms in order to propose a strategy for enhancing the therapeutic action of CAR-T cells in the treatment of glioblastoma. The main objective of this research is to evaluate the impact of the tumor environment on the antitumor efficacy of anti-GD2 CAR-T therapeutic cells in an in vitro glioblastoma model. Both tumor environment cells and CAR-T therapeutic cells will be generated from glioblastoma patient cells. The secondary objectives of this research are to * Evaluate the impact of tumor environment targeting on the in vitro antitumor efficacy of anti-GD2 CAR-T therapeutic cells. * Evaluate the quality/quantity of generated cells (CAR-T cells and tumor environment cells) in relation to glioblastoma patients. * Evaluate the efficiency of the cell isolation technique (CAR-T cells and tumor environment cells)
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06764537
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06749925 - Phase III Randomized, Double-Blind, Placebo-Controlled Clinical Trial Assessing the Efficacy and Safety of Dendritic Cell-Based Immunotherapy for Glioblastoma (PHASE3, NOT_YET_RECRUITING): This Phase III, multicenter, placebo-controlled clinical trial with sequential randomization is designed to evaluate the efficacy and safety of an experimental vaccine composed of hybrid dendritic cells (DCs) for the treatment of glioblastoma. Conducted at the Hospital das Clínicas of the University of São Paulo Medical School (HCFMUSP) and the Institute of Biomedical Sciences of the University of São Paulo (ICB/USP), the study is led by Professor José Alexandre Marzagão Barbuto. A multidisciplinary team of researchers specializing in neurosurgery, pathology, hematology, and other fields will contribute to a comprehensive approach. The trial aims to determine whether the hybrid DC vaccine can increase overall survival in adult patients with glioblastoma who have completed standard treatment, including surgery, chemotherapy, and radiotherapy. Secondary objectives include evaluating progression-free survival, quality of life, immune response, and the safety of the intervention. The study will enroll 186 patients, who will be randomized into three groups: (1) a control group receiving placebo, (2) a group receiving the DC vaccine, and (3) a group receiving the DC vaccine combined with pembrolizumab.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06749925
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06687681 - Efficacy of the Intrathecal Injection of Active Allogeneic Natural Killer Cells in Patients With High-grade Gliomas; A Multi-center Phase II Clinical Trial (PHASE2, RECRUITING): Gliomas are the most common malignant brain tumors, which are often associated with high-grade tumors characterized by an inferior prognosis and low patient survival rates in both children and adults. Surgical removal and tumor resection are the primary treatment approaches for gliomas. In such cases, whole-brain radiation therapy is also employed as a therapeutic option, which itself has significant side effects, and studies have shown limited impact on improving patient survival. Targeted therapy and recently investigated approaches such as targeted therapy have shown some tumor regression, but in most cases, tumor recurrence has been observed after initial regression. Therefore, they have a limited impact on prolonging patient survival. Immunotherapy, particularly immunotherapy with specific immune cells, can effectively identify and eliminate cancer cells and has been utilized as a new approach in the past two decades, especially in cancers where conventional methods have limited success. Among the effective immunotherapy methods, using natural killer cells (NK cells) can be one of the promising approaches. Currently, phase I clinical trials have been conducted by our research group in patients with gliomas.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06687681
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06551909 - Radioimmunotherapy in Solid Tumors (Aim 2- Stereotactic Neoadjuvant Radiotherapy for Glioblastoma) (NA, RECRUITING): This is a prospective multicenter study of hypofractionated radiotherapy for the radiation treatment (RT) of solid tumors and in particular for Glioblastoma (in Aim 2). It is based on the results of ongoing studies at our Institute to validate the efficacy of extremely hypofractionated RT in neoadjuvant settings, which observed immunostimulatory effects of RT and the synergy with immune components. The collaboration between San Raffaele Hospital (Milan), the IRCCS Istituto Nazionale dei Tumori Fondazione G. Pascale (Naples) and the San Giuseppe Moscati Hospital of National Relief and High Specialty (Avellino) will ensure that patient recruitment, treatment and monitoring can be translated into facilities of the National Health System using common procedures. The various departments involved will treat patients with the same methods synergistically exploring the immuno/biological factors related to efficacy (and/or toxicity), based on new radioimmunotherapeutic approaches. Clinical and research activity will be developed jointly, drawing on the expertise in radiotherapy, radiomics, oncology, imaging and immunotherapy skills already available.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06551909
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06336291 - A Dose Optimization Study for L19TNF in Combination With Lomustine in Patients With Glioblastoma at Progression or Recurrence (PHASE2, RECRUITING): The trial aims to collect safety, efficacy, exposure, dose- response, pharmacokinetic and pharmacodynamic information of the combination of L19TNF and lomustine at different dose levels in patients with Glioblastoma at progression or recurrence
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06336291
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low
- NCT06102525 - A Phase 1/2a, Open-label, Multicenter, Dose Escalation and Dose Expansion Study Evaluating the Safety, Tolerability, and Efficacy of RZ-001 in Combination With Valganciclovir in Subjects With Glioblastoma (PHASE1, PHASE2, RECRUITING): This is a Phase 1/2a, open-label study to evaluate the safety, tolerability, immunogenicity, and preliminary clinical activity of RZ-001 administered in combination with VGCV in subjects with hTERT-positive GBM.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06102525
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05842746 - Efficacy and Safety of Elemene Plus Stupp Protocol Versus Stupp Protocol Alone for Newly-diagnosed Glioblastoma: A Multi-center Phase II Randomized Controlled Trial (PHASE2, NOT_YET_RECRUITING): The goal of this phase II randomized clinical trial is to compare the safety and efficacy of Elemene plus Stupp Protocol (the new protocol) and Stupp Protocol alone (the standard protocol) in patients with newly-diagnosed glioblastomas (ndGBMs). The main questions to answer are: * Whether the new treatment protocol (Elemene plus Stupp Protocol) is clinically safe for ndGBM patients. * Whether the new treatment protocol (Elemene plus Stupp Protocol) brings better survival benefits for ndGBM patients compared to the standard-of-care Stupp Protocol. Study participants will be enrolled in 5 hospitals in China and randomly assigned to receive either the new protocol or the standard protocol. The overall survival (OS) rate in the 12th month, the progression-free survival (PFS) rate in the 6th month, OS, PFS, and adverse events assessed by the CTCAE (Common Terminology Criteria for Adverse Events) will be evaluated for all patients.
  Quick read: GBM-specific treatment study for GBM or glioma patients; biologic or cellular-therapy; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05842746
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05820191 - B-amyloid as a Marker for GBM Bioimaging (PHASE2, NOT_YET_RECRUITING): This project is aimed at improvement of glioblastoma (GBM) diagnostic strategies for discrimination of tumor progression and chemo- and radiotherapeutic treatment-related changes in brain tissue. The study will elucidate the diagnostic value of PET imaging with use of amyloid-β radioisotope tracer Amyvid (Florbetapir F18) for GBM. The results of the study will provide data for development of new approach for GBM diagnostics.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05820191
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05720078 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-3 (UNITED-3): Applying a Two Phase, Personalized Margin, Reduced Clinical Target Volume Approach (NA, RECRUITING): The goal of this study is to test whether an adaptive radiation therapy (RT), two-phase approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive, two-phase RT approach compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05720078
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05653622 - Simultaneous Integrated Boost FDOPA PET Guided in Patients With Partially- or Non-operated Glioblastoma (PHASE2, RECRUITING): Glioblastoma (GBM) is the most common primary brain cancer in adults. Surgery, chemoradiotherapy (temozolomide TMZ) and then adjuvant TMZ is the standard treatment. But, most patients relapse in a median time of 8-9 months; the median overall survival (OS) ranged from 15 to 18 months. Some frail patients received hypofractionated radiation and concomitant and adjuvant TMZ. For some, the radiation dose is not optimal. Moreover, recurrences develop mainly in the initial tumor site. These two reasons justify increasing the dose. To limit the movements of these fragile patients, the method consists of increasing the dose without increasing the number of sessions by using the Simultaneous Integrated Boost (SIB) which increases the dose in targeted volumes while the rest of the volume receives a minimum dose. A phase I trial showed the possibility of increasing the dose in SIB up to 80 Gy in a part of the GBM enhanced on MRI. FDOPA PET detects certain more aggressive tumor areas, areas likely to recur. Integrating them into the SIB seems appropriate. A phase II trial showed the interest of SIB guided by FDOPA PET in terms of progression-free survival but without impact on OS. This study differed from the one the investigators propose, because a dose and conventional fractionation, identical to that of the European Organization for Research and Treatment of Cancer/National Cancer Information Center (NCIC/EORTC) protocol were delivered, the gliomas were unmethylated MGMT, less likely to respond. Studies with SIB and hypofractionation are often retrospective and for others, hypofractionation was debatable and the dose increase was not based on PET capture but on MRI. However, a prospective phase II study, with SIB and hypofractionation, not integrating FDopa PET has demonstrated the relevance of SIB. In this project, the investigators propose to use the integrated boost technique (SIB) guided by PET FDOPA to increase the radiation dose in GBM, in patients either fragile and partially operated, or only biopsied and for whom the prognosis is the most pejorative.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05653622
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: post_surgery
- NCT05502991 - Phase 2 Study to Evaluate the Clinical Efficacy and Safety of Sintilimab Plus Low-dose Bevacizumab in Patients With Glioblastoma of Different Relapse Stages (PHASE2, NOT_YET_RECRUITING): This is an ongoing Phase 2, open-label, single-center, non-randomized study of sintilimab (one anti-PD-1 antibody same as nivolumab approved in China) plus bevacizumab administered in a low dosage schedule in adult (≥ 18 years) participants with a clinical relapse or circulating tumor DNA (ctDNA)-level relapse of glioblastoma (GBM). This study has two non-comparative study groups. Both cohorts will receive the same study drug sintilimab 200mg and bevacizumab 3mg/kg every 3 weeks. A stringent two-step non-randomized process will be used to assign participants to one of the study groups. Neither participants nor doctors but the researcher can choose which group participants are in. No one knows if one study group is better or worse than the other. 60 total participants are expected to participate in this study (30 participants in each cohort). Grouping process: After enrollment, under the standard of care, participants will receive regular tumor in situ fluid (fluid within the surgical cavity, TISF) sampling for ctDNA analysis and recceive regular MRI. The researcher will study the TISF ctDNA and imaging dynamics to determine whether the tumor reaches to ctDNA-level (Cohort 1) or clinical relapse (Cohort 2). At the first step, all timely identified as ctDNA-level relapse tumors will be assigned into the Cohort 1 and receive the study drug immediately, those failed to be timely identified will be assigned into the Cohort 2 and receive the study drug after the clinical relapse. At the second step, once either group reaches the target number, the new participants will be all assigned into the other Cohort.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT05502991
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT04752280 - Glioblastoma Radiotherapy Using IMRT or Proton Beams (NA, RECRUITING): Radiation therapy is an integral part of the multimodal primary therapy of glioblastomas. As the overall prognosis in this tumor entity remains unfavorable, current research is focused on additional drug therapies, which are often accompanied by increases in toxicity. By using proton beams instead of photon beams, it is possible to protect large parts of the brain which are not affected by the tumor more effectively. An initial retrospective matched-pair analysis showed that this theoretical physical benefit is also clinically associated with a reduction in toxicity during therapy and in the first few months thereafter. The aim of the GRIPS study is to prospectively test this clinical benefit in a randomized, open-label Phase III study. Patients are treated in the study using either modern photon radiation techniques (standard arm) or proton beams (experimental arm). The primary endpoint is the cumulative toxicity CTC grade 2 and higher in the first 4 months. Secondary endpoints include overall survival, progression-free survival, quality of life, and neurocognition.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04752280
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03548571 - Open Label Randomized Phase II/III Trial of Dendritic Cell Immunotherapy Against Cancer Stem Cells in Glioblastoma Patients Receiving Standard Therapy (DEN-STEM) (PHASE2, PHASE3, RECRUITING): Open, randomized study of a trivalent dendritic cell therapy compared to standard therapy in primary treated patients with IDH wild-type, MGMT-promotor methylated glioblastoma. The IMP is dendritic cells transfected with mRNA of survivin, hTERT og autologous tumor stem cells derived from tumorspheres.
  Quick read: GBM-specific treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03548571
  Review priority: 151
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07472387 - Impact of Androgen Signaling on the Composition of the Immune Microenvironment in Glioblastomas (NA, NOT_YET_RECRUITING): Glioblastoma (GBM) is the most common and most aggressive primary brain cancer in adults. GBM is more common in men than in women, with a male-to-female ratio of 1.6. Furthermore, being male is associated with a poorer prognosis. These data suggest that sex and/or sexual hormones and more specifically androgens may play a role in the initiation, the growth, and the resistance to treatments of GBM.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07472387
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07218367 - Targeting Infiltrating Glioblastoma Via pH Sensitive Visualization of Tumor and pH Modulation Through Bicarbonate Transporter SLC4A4 (PHASE1, NOT_YET_RECRUITING): Glioblastoma is an infiltrating tumor that is difficult to visualize in surgery and on standard images. A special pH (acid-base) related magnetic resonance imaging (MRI) has been developed to better see infiltrating tumor. In this safety study, the investigators will carry out increased levels of pH based resections of infiltrating tumor to assess the tolerability in VA populations.
  Quick read: GBM-specific treatment study for newly diagnosed GBM; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07218367
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05669820 - Antisecretory Factor During Concomitant and Adjuvant Therapy of Primary Glioblastoma, a Randomised, Prospective and Double Blinded Study (PHASE2, PHASE3, RECRUITING): This is a randomised, double blinded and multiple center , Phase 2 study in patients with newly diagnosed glioblastoma. Participants will receive an egg powder enriched for antisecretory factor (AF), Salovum, or a placebo egg powder daily from 2 days before concomitant radio-chemo therapy or chemotherapy until 14 days after finalisation plus during adjuvant chemotherapy.The primary aims of are overall survival at 6 and 12 months after diagnosis
  Quick read: GBM-specific treatment study for newly diagnosed GBM; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05669820
  Review priority: 149
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07326566 - A Phase 2 Randomized, Multicenter Study to Evaluate the Efficacy and Safety of Silevertinib, an Oral EGFR Inhibitor, in Combination With Temozolomide in Patients With Newly Diagnosed Glioblastoma With Unmethylated MGMT Promoter and EGFRvIII (PHASE2, RECRUITING): The purpose of this study is to see if combining silevertinib with temozolomide after surgery and radiotherapy helps treat newly diagnosed glioblastoma (GBM) better than using temozolomide alone in the maintenance setting. Specifically, this study is being done to find answers to the following questions: * How much of the study drugs (silevertinib combined with temozolomide) should be given to participants with GBM? * What are the side effects participants have when taking the study drug (silevertinib combined with temozolomide)? * Can the study drug (silevertinib combined with temozolomide) help participants with GBM live longer without disease progression compared to treatment with temozolomide alone?
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07326566
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07134842 - Window Studies in Glioblastoma: A Phase I Trial Investigating Neoadjuvant Ipilimumab in Newly Diagnosed Glioblastoma (PHASE1, RECRUITING): WinGlio is a phase I study investigating neoadjuvant (before surgery) ipilimumab ( a type of immunotherapy drug) in patients with newly diagnosed glioblastoma (a form of brain cancer). Participants will receive up to 2 cycles of ipilimumab prior to the standard of care treatments for this patient group which can include debulking surgery and chemoradiation. The aim of giving the ipilimumab to the participants is to see if it is safe to treat patients with this condition with ipilimumab and also to see if the drug helps to reduce or control the patient's disease.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07134842
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT06047379 - An Open-label Phase 1/2 Dose Finding, Safety and Efficacy Study of Oral NEO212 in Patients With Astrocytoma IDH-mutant, Glioblastoma IDH-wildtype or Uncontrolled Brain Metastasis in Patients With Select Solid Tumors. (PHASE1, PHASE2, RECRUITING): This multi-site, Phase 1/2 clinical trial is an open-label study to identify the safety, pharmacokinetics, and efficacy of a repeated dose regimen of NEO212 alone for the treatment of patients with radiographically-confirmed progression of Astrocytoma IDH- mutant, Glioblastoma IDH-wildtype, and the safety, pharmacokinetics and efficacy of a repeated dose regimen of NEO212 when given with select SOC for the treatment of solid tumor patients with radiographically confirmed uncontrolled metastases to the brain. The study will have three phases, Phase 1, Phase 2a and Phase 2b.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06047379
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05911230 - Advanced Diffusion MRI to Differentiate Tumor Recurrence From Pseudoprogression in Patients With Glioblastoma and Brain Metastases- AiD GLIO Pilot Trial (NA, RECRUITING): This pilot study investigates whether advanced diffusion-weighted MRI (ADW-MRI) can differentiate between true tumor progression (TP) and a pseudoprogression (PsP) in patients with glioblastoma (GBM) or brain metastases.
  Quick read: GBM-specific treatment study for GBM or glioma patients; treatment-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05911230
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT05765812 - A Phase 1/2 Open-label Study of Debio 0123 in Combination With Temozolomide in Adult Participants With Recurrent or Progressive Glioblastoma and of Debio 0123 in Combination With Temozolomide and Radiotherapy in Adult Participants With Newly Diagnosed Glioblastoma (PHASE1, PHASE2, RECRUITING): The primary purpose of the Phase 1 (Dose Escalation) of this study is to identify the dose-limiting toxicities (DLTs) of Debio 0123 combined with temozolomide (TMZ) (Arm A) and with TMZ and radiotherapy (RT) (Arms B and C) and to characterize the safety and tolerability of these combinations in adult participants with glioblastoma (GBM). Arm B which was previously added to the protocol, has been permanently halted per the safety monitoring committees' decision on the safety findings of this arm. The primary purpose of Phase 1 (Dose expansion) of the study is to assess the doses studied under Phase 1 (Dose Escalation) Arm A and identify the recommended dose (RD) for further development. The Phase 2 will start once the RD Phase 1 has been defined. The primary objective of Phase 2 is to assess the efficacy of Debio 0123 at the RD for further development in combination with TMZ, compared to the standard of care (SOC) in adult participants with GBM.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05765812
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 60 (match), recurrence_max=0 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT05450744 - A Phase 1 Safety and Dose Finding Study of 131I -TLX101 Plus Standard of Care in Patients With Newly Diagnosed Glioblastoma (PHASE1, RECRUITING): This is an open label, single arm, parallel-group, multicentre, and dose finding study to evaluate the safety of ascending radioactive dose levels of 131I-TLX101 administered intravenously in combination with best standard of care in newly diagnosed GBM patients.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05450744
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT04188535 - RELAY: Repeated Magnetic Resonance Imaging Examinations to Analyze and Assess Your Cancer: A Prospective Study on the Use of Serial Magnetic Resonance Imaging in the Assessment of Changes During Treatment With Radiation Therapy (NA, RECRUITING): This is a phase 1 study to determine the feasibility and utility of using serial magnetic resonance imaging (MRI) to assess treatment response during and after radiation therapy (standard of care cancer treatment) for participants with advanced esophageal cancer, glioblastoma, prostate cancer, vulvar cancer or pediatric glioma. The research study procedures include three MRI scans (one before, one during, and one after standard of care cancer radiation therapy) for participants with advanced esophageal cancer, glioblastoma, prostate cancer, vulvar cancer or pediatric glioma. The research study procedures include: * Screening for eligibility * Three MRI scans
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04188535
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT03603405 - Phase I-II Study Evaluating HSV-tK + VALACYCLOVIR GENE THERAPY Combination With Radiotherapy and Chemotherapy for Newly Diagnosed Anaplastic Astrocytoma and Glioblastoma Multiforme. (PHASE1, PHASE2, RECRUITING): Study to assess the safety and efficacy of HSV-tk (gene therapy), valacyclovir, radiotherapy and chemotherapy in newly diagnosed glioblastoma multiforme (GBM) or anaplastic astrocytoma (AA).
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03603405
  Review priority: 147
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT04523688 - Vaccination With Autologous Dendritic Cells Loaded With Autologous Tumour Homogenate in Glioblastoma: a Phase II Study (PHASE2, RECRUITING): Single arm, monocentric trial to assess the safety and the progression-free survival related to the combined treatment of dendritic cell vaccine loaded with autologous tumor homogenate and temozolomide in patients operated for glioblastoma and then treated with standard radiochemotherapy (according to Stupp regimen).
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04523688
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03861299 - The SAFE-Trial: Safe Surgery for Glioblastoma Multiforme: Awake Craniotomy Versus Surgery Under General Anesthesia. A Multicenter Prospective Randomised Controlled Study (NA, RECRUITING): The trial is designed as a multicenter randomized controlled study. 246 patients with presumed Glioblastoma Multiforme in eloquent areas on diagnostic MRI will be selected by the neurosurgeons according the eligibility criteria (see under). After written informed consent is obtained, the patient will be randomized for an awake craniotomy (AC) (+/-123 patients) or craniotomy under general anesthesia (GA) (+/-123 patients), with 1:1 allocation ratio. Under GA the amount of resection of the tumour has to be performed within safe margins as judged by the surgeon during surgery. The second group will be operated with an awake craniotomy procedure where the resection boundaries for motor or language functions will be identified by direct cortical and subcortical stimulation. After surgery, the diagnosis of GBM will have to be histologically confirmed. If GBM is not histologically confirmed, patients will be considered off-study and withdrawn from the study. These patients will be followed-up according to standard practice. Thereafter, patients will receive the standard treatment with concomitant Temozolomide and radiation therapy and standard follow up. Total duration of the study is 5 years. Patient inclusion is expected to take 4 years. Follow-up is 1 year after surgery. Statistical analysis, cost benefit analysis and article writing will take 3 months.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03861299
  Review priority: 145
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 80 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07439172 - A Multi-Centered Evaluation of Pre-Radiation Chemotherapy for Newly Diagnosed High-Grade Glioma (HGG): An Approach to Drug Screening That Requires Confirmation (PHASE2, NOT_YET_RECRUITING): Better treatments are needed for high-grade gliomas (HGG), and new ways of treating this disease should be tested. The investigators want to see if giving medicine before radiation works well. After radiation, MRI scans can be harder to understand because radiation changes how the brain looks on the scan. If new medicines are given before radiation, the scans are easier to read. First, the investigators need to find out if giving chemotherapy early works using a drug we already know can treat gliomas. The investigators will start with temozolomide, which is the only chemotherapy approved by the FDA for HGG. If this approach is successful, the investigators can then test new drugs using this screening method.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07439172
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT06991101 - Randomized Phase 2 Trial of Ruxolitinib in Combination With Radiation and Temozolomide Compared to Radiation and Temozolomide for Newly Diagnosed Glioblastoma. (PHASE2, RECRUITING): The purpose of this research is to test the safety and effectiveness of the investigational drug ruxolitinib when it is combined with standard of care treatment (radiation therapy and temozolomide) for the treatment of newly diagnosed glioblastoma. Half the people in the study will be assigned to take the study drug ruxolitinib in addition to the standard of care temozolomide and radiation therapy and the other half will be assigned to the standard of care temozolomide and radiation therapy only. This assignment will be randomized in a 1-to-1 ratio, like the flip of a coin.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06991101
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT06017063 - Coaching for Coping in Glioblastoma Patients and Caregivers and Its Association With Compliance to TTFields (NA, NOT_YET_RECRUITING): The aim is to improve patients' compliance to TTFields therapy by a psychological video intervention in a multi-center, randomized controlled trial.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06017063
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05929495 - Phase 2, Open-label, Single-arm Study on the Use of Metformin as Adjunctive Therapy in High-grade Glioma (PHASE2, RECRUITING): About 75% of CNS malignant tumors are classified as gliomas and the IDH-wildtype glioblastoma (GBM) represents the most aggressive form among CNS malignancies. This is a nationwide single-center phase II drug clinical trial with an approximate duration of 32 months. The clinical trial will be single-arm to evaluate the biological activity and effects of metformin in combination with TMZ in patients with GBM.
  Quick read: GBM-related treatment study for newly diagnosed GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05929495
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05909618 - An Open Label Phase 2 Study of Intravenously Administered Crizanlizumab Alone or in Combination With Nivolumab for Glioblastoma and Melanoma With Brain Metastases (PHASE2, RECRUITING): A single-center, open-label, non-randomized phase I/II study to evaluate the efficacy, safety and tolerance of crizanlizumab monotherapy and in combination with nivolumab in patients with advanced glioblastoma (GB) who exhausted standard of care (SOC) therapy, patients with metastatic brain melanoma (MBM) and patients with newly diagnosed unmethylated GB. Subjects will be screened for up to 28 days prior to treatment initiation. Eligible subjects will be allocated to one of 3 cohorts: Cohort 1: Patients with metastatic melanoma with primarily diagnosed or newly progressing brain metastases who failed immunotherapy. Cohort 2: Patients with recurrent or progressing GB following primary radiation therapy and temozolomide. Patients may have failed up to 2 prior systemic treatment lines (including temozolomide as adjuvant therapy) and are candidates for further treatment. Cohort 3: Patients with newly diagnosed GB who were evaluated for methylguanine-DNA methyltransferase(MGMT) methylation status and have un-methylated MGMT promotor-therefore, they are not candidates for maintenance temozolomide therapy.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05909618
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), ecog_max=1 vs 1 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05879367 - An Open-label, Phase 1b Study to Evaluate the Safety and Tolerability of Eflornithine Plus Temozolomide in Patients With Newly Diagnosed Glioblastoma or Astrocytoma (PHASE1, RECRUITING): The purpose of this study is to establish the recommended phase 2 dose of eflornithine in combination with temozolomide in patients whose glioblastoma or astrocytoma is newly diagnosed, and to evaluate safety and tolerability of this combination at that dose.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05879367
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05864534 - A Phase 2a Trial of Immune Modulation in Combination With Ultrasound-mediated Blood Brain Barrier Opening in Patients With Newly Diagnosed Glioblastoma (PHASE2, RECRUITING): Brain tumor treatment is hampered by the blood-brain barrier (BBB). This barrier prevents drugs carried in the bloodstream from getting into the brain. If the BBB can be opened, making it temporarily more permeable, drugs may able to better reach the brain tumor. In this trial we will implant a novel device with 9 ultrasound emitters, allowing temporary and reversible opening of the BBB to maximize brain penetration of drugs that modulate the immune system. The device will be implanted after radiation is completed. Immune modulating drugs will be given every 3 weeks in conjunction with activation of the device to open the BBB. The objectives of this trial are to establish whether it is safe and feasible to administer immune modulating drugs in this manner, and identify whether the treatment is effective in treating glioblastoma.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05864534
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05271240 - A Phase III Randomized Trial of Repeated Superselective Intraarterial Cerebral Infusion (SIACI) of Bevacizumab (Avastin) With Temozolomide and Radiation Compared to Temozolomide and Radiation Alone in Newly Diagnosed Glioblastoma (GBM) (PHASE3, RECRUITING): Primary brain cancer kills up to 10,000 Americans a year. These brain tumors are typically treated by surgery, radiation therapy and chemotherapy, either individually or in combination. Present therapies are inadequate, as evidenced by the low 5-year survival rate for brain cancer patients, with median survival at approximately 12 months. Glioma is the most common form of primary brain cancer, afflicting approximately 7,000 patients in the United States each year. These highly malignant cancers remain a significant unmet clinical need in oncology. The investigators have completed a Phase I clinical trial that has shown that Superselective Intraarterial Cerebral Infusion (SIACI) of Bevacizumab (BV) is safe up to a dose of 15mg/kg in patients with recurrent malignant glioma. Additionally, the investigators have shown in a recently completed Phase I/II clinical trial, that SIACI BV improves the median progression free survival (PFS) from 4-6 months to 11.5 months and overall survival (OS) from 12-15 months to 23 months in patients with newly diagnosed GBM. Therefore, this two-arm, randomized trial (2:1) is a follow up study to these trials and will ask simple questions: Will this repeated SIACI treatment regimen increase progression free survival (PFS-primary endpoint) and overall survival (OS-secondary endpoint) when compared with standard of care in patients with newly diagnosed GBM? Exploratory endpoints will include adverse events and safety analysis as well as quality of life (QOL) assessments. The investigators expect that this project will provide important information regarding the utility of repeated SIACI BV therapy for newly diagnosed GBM and may alter the way these drugs are delivered to our patients in the near future.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05271240
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT05084430 - A Phase I/II Study of Pembrolizumab and M032 (NSC 733972), a Genetically Engineered HSV-1 Expressing IL-12, in Patients With Recurrent/Progressive and Newly Diagnosed Glioblastoma Multiforme, Grade 3 or Grade 4 Astrocytoma, or Gliosarcoma (PHASE1, PHASE2, RECRUITING): This Phase I (Cohort I and Cohort II) and Phase II trial is designed to confirm the safety and tolerability of Pembrolizumab when given in conjunction with M032, an Oncolytic Herpes Simplex Virus (oHSV) that expresses IL-12 and perform the Phase II portion using a Recommended Phase 2 Dose (RP2D) of M032 (provided by the Phase I) when given in conjunction with Pembrolizumab for recurrent malignant glioma (glioblastoma multiforme, anaplastic astrocytoma, or glio-sarcoma).
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05084430
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT03213002 - Phase I/II Study of Oral Capecitabine and Temozolomide (CAPTEM) for Newly Diagnosed Glioblastoma (GBM) (PHASE1, PHASE2, RECRUITING): The purpose of this study is to evaluate the safety and efficacy of administering the medication capecitabine along with temozolomide when you start your monthly regimen of oral temozolomide for the treatment of your newly diagnosed glioblastoma multiforme (GBM). Capecitabine is an oral chemotherapy that is given to patients with other types of cancer. The study will evaluate whether the dosage of 1500 mg/m2 of capecitabine is tolerable after radiation, when taken along with temozolomide. It will also try to determine if the medication capecitabine helps patients respond to treatment for a longer period of time compared to just temozolomide alone, which is the standard of care.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03213002
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT02861898 - Phase I/II Trial of Super-selective Intra-arterial Repeated Infusion of Cetuximab for the Treatment of Newly Diagnosed Glioblastoma (PHASE1, PHASE2, RECRUITING): Primary brain cancer kills up to 10,000 Americans a year. These brain tumors are typically treated by surgery, radiation therapy and chemotherapy, either individually or in combination. Present therapies are inadequate, as evidenced by the low 5-year survival rate for brain cancer patients, with median survival at approximately 12 months. Glioma is the most common form of primary brain cancer, afflicting approximately 7,000 patients in the United States each year. These highly malignant cancers remain a significant unmet clinical need in oncology. GBM often has a high expression EFGR (Epidermal Growth Factor Receptor) which is blocked by Cetuximab (CTX). The investigators have recently completed a separate Phase I clinical trial using superselective intra-arterial cerebral infusion (SIACI) of CTX after blood brain barrier disruption (BBBD) for recurrent GBM (Chakraborty et al, in revision, Journal of Neurooncology). The investigators found that intra-arterial infusion of CTX is well tolerated with few adverse effects. The investigators hypothesize that in patients with newly diagnosed GBM, repeated SIACI of this drug after BBBD will be safe and efficacious for our patients when combined with standard chemoradiation (STUPP protocol). This trial will be a non-randomized open label Phase I/II clinical trial. In addition to standard chemotherapy and radiation therapy (STUPP protocol) the patient will be given CTX intra-arterially after BBBD for a total of three doses at approximately post surgery days 30, 120 and 210.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT02861898
  Review priority: 144
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT07211841 - Correlative Analysis Between Magnetic Resonance Spectroscopy (MRS) and Essential Clinicobiological Data in Glioblatoma Multiforme (GBM) (NA, NOT_YET_RECRUITING): Glioblastoma multiforme (GBM) is the most common primary brain tumor, and it is well-known to be associated with a poor prognosis. MRI is the key medical technique for the diagnosis and the follow-up of GBM. By allowing for MRS studies, MRI permits a non-invasive characterization of the TME of GBM, including their metabolic characterization. The investigators propose to address the link between the MRS profile of GBM and basic clinical and biological parameters, with the aim of : i) identifying correlations between these parameters, ii) attempting to integrate clinical, biological and spectroscopic profiles of GBM. The investigators plan to recruit 30 newly diagnosed GBM patients for which surgery / radiochemotherapy will be proposed in the Medical oncology unit of Amiens University Hospital. Following inclusion of patients with probable GBM, MRS study will be performed during the first (pre-therapeutic) MRI examination. Basic clinical and biological parameters of the blood (CRP, complete blood count, fibrinogen, lactate and choline) will be assessed. A metabolomic study will also be performed on the plasma of GBM patients before any therapeutics. A second biological, post-therapeutic assesment (one month after surgery/radiochemotherapy) will allow the same analyses (basic biological parameters + plasma metabolomics), in order to examine the stability of the blood parameters.
  Quick read: GBM-related treatment study for newly diagnosed GBM; device / TTFields-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07211841
  Review priority: 143
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT07459101 - UNIty-Based MR-Linac Guided Adaptive RadioThErapy for High GraDe Glioma-4 (UNITED-4): Prospective Evaluation of FLAIR-Guided Clinical Target Volume Reduction (NA, RECRUITING): This study builds on the results of prior studies (UNITED and UNITED-3). The goal of UNITED-4 is to test whether an adaptive radiation therapy (RT) therapy approach ('dose painting'), with reduced margins, impacts approach in participants with glioblastoma impacts local control compared to standard non-adaptive RT approach. The main questions of the study are to see how this adaptive RT approach with reduced margins compares to standard RT in terms of: * Local control * Overall and progression-free survival * Patterns of failure * Toxicity, Neurological Function, and Quality of Life * Longitudinal imaging features
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT07459101
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06418113 - Neoadjuvant Radio-chemotherapy Safety Pilot Study in Patients With Glioblastoma (PHASE1, RECRUITING): The goal of this clinical trial is to evaluate the safety and efficacy of neoadjuvant radiochemotherapy in the surgical resection of glioblastoma (GBM). The main questions it aims to answer are: * What is the safety profile of neoadjuvant radiochemotherapy in terms of neurological deficit, radionecrosis, edema, headache, wound dehiscence, infection, and cerebrospinal fluid fistula? * What is the efficacy of neoadjuvant radiochemotherapy in terms of progression-free survival, overall survival, cognitive function, and quality of life? Participants will undergo the following tasks and treatments: * Stereotactic biopsy and diagnosis confirmation. * Conformal hypofractionated stereotactic radiotherapy with concurrent temozolomide. * Supramarginal resection guided by 5-ALA under intraoperative neurophysiological monitoring. * Maintenance temozolomide administration for 6 months. Researchers will compare the group receiving neoadjuvant radiochemotherapy to the control group following the standard Stupp protocol to assess safety and efficacy outcomes.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06418113
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06356883 - A Randomized Phase II Study on Intraarterial Carboplatin Combined With Caelyx Compared to Intraarterial Carboplatin Combined With Etoposide Phosphate for Progressing Glioblastoma at First or Second Relapse (PHASE2, RECRUITING): The standard of care for glioblastoma (GBM) treatment involves maximal resection followed by concomitant radiotherapy and temozolomide. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is inevitable. At relapse, there is no consensus regarding the optimal therapeutic strategy. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which impedes drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, can produce responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival (OS) 23 months. How can the OS and PFS be improved? By combining chemotherapeutic agents with different mechanisms of action. Study design: In this phase II trial, treatment will be offered at relapse. Surgery will be performed for cytoreduction if it is warranted, followed with a combination IA carboplatin + IA Cealyx (liposomal doxorubicin) or IA carboplatin + IA etoposide phosphate. Toxicity will be assessed according to the NCIC common toxicity criteria. Treatment will consist in either IA carboplatin (400 mg/m\^2) + IA Cealyx (30 mg/m\^2) or IA carboplatin (400 mg/m\^2) + IA etoposide phosphate (400 mg/m\^2) every 4-6 weeks (1 cycle). Up to twelve cycles will be offered. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. Primary outcome will PFS and tumor response. Secondary outcome will include median OS, toxicity, quality of life (QOL), neurocognition (NC). Putting together these data will allow to correlate clinical and radiological response to QOL and NC.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06356883
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT04678648 - A Phase Ia/Ib, Open Label, Multi-center, Non-randomized Dose Escalation and Dose Expansion Study of RSC-1255 Alone or in Combination With Hydroxychloroquine in Patients With Advanced Solid Tumor Malignancies (PHASE1, RECRUITING): RSC-101 is a Phase 1a/1b clinical trial of RSC-1255 in adult study participants with advanced solid tumor malignancies who are intolerant of existing therapies known to provide clinical benefit, have disease that has progressed after standard therapy, or have previously failed other therapies. The study has two phases. The purpose of Phase 1a (Dose Escalation) is to confirm the appropriate treatment dose and Phase 1b (Dose Expansion) is to characterize the safety and efficacy of RSC-1255.
  Quick read: GBM-related treatment study for GBM or glioma patients; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04678648
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03672721 - A Phase II Study in Relapsing Glioblastoma of Intraarterial Concurrent Chemoradiation Therapy Using IA Carboplatin (PHASE1, PHASE2, RECRUITING): Treatment of glioblastoma involves an optimal surgery, followed by a combination of radiation and temozolomide chemotherapy. Progression-free survival (PFS) with this treatment is only 6.9 months and relapse is the norm. The rationale behind the fact that limited chemotherapy agents are available in the treatment of malignant gliomas is related to the blood-brain barrier (BBB), which limits drug entry to the brain. Intraarterial (IA) chemotherapy allows to circumvent this. Using IA delivery of carboplatin, the investigators have observed responses in 70% of patients for a median PFS of 5 months. Median survival from study entry was 11 months, whereas the overall survival 23 months. How can this be improved? By coupling radiation with a chemotherapeutic which is also a potent radiosensitizer such as carboplatin. Study design: In this phase I/II trial, patients will be treated at recurrence; a surgery will be performed for cytoreduction and to obtain tumor sample, followed with a combination of re-irradiation and IA carboplatin chemotherapy. A careful escalation scheme from 1.5Gy/fraction up to 3.5Gy/fraction will allow the investigators to determine the optimal re-irradiation dose (10 fractions of radiation over 2 weeks). Toxicity will be assessed according to the NCIC common toxicity criteria. Combined with radiation, patients will receive 2 treatments of IA carboplatin, 400 mg/m2, 4 hours prior to the first and the sixth radiation fraction. IA treatments will then be continued on a monthly basis, up to a total of 12 months, or until progression. Outcome measurements: Tumor response will be evaluated using the RANO criteria by magnetic resonance imaging monthly. The investigators will also acquire a sequence that enables the measurement of cerebral blood flow, cerebral blood volume and blood vessel permeability that are all relevant to understand the delivery of therapeutics to the CNS. Primary outcome will be OS and PFS. Secondary outcome will be QOL, neurocognition, and carboplatin delivery. In vitro intracellular carboplatin accumulation: Tumor samples from re-operation will be be analyzed for intracellular Pt concentration by ICP-MS. The amount of Pt bound to DNA will be measured. The level of apoptosis will be determined for each of the sample. Putting together these data will allow to correlate clinical and radiological response to QOL, NC (MOCA), and to delivery surrogates for the IA infusion and intracellular penetration of carboplatin.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03672721
  Review priority: 142
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06623565 - Multimodal Image-guided Resection of IDH Wildtype Glioblastoma and Grade IV IDH-mutant Astrocytoma (NA, RECRUITING): Rationale: Patients with IDH-wildtype glioblastoma or grade IV IDH-mutant astrocytoma have a very poor prognosis despite standard treatment consisting of surgery, radiotherapy, and chemotherapy. Diffuse infiltration of the brain by the tumor is thought to be one of the main causes of this therapy-resistance. In order to improve the surgical treatment, tumor regions with lower infiltration percentages need to be identified and resected during surgery, a so-called supramarginal resection. Currently, pre-operative T1 contrast enhanced weighted (T1c) MRI is used to identify the tumor for resection. We recently found the combination of apparent diffusion coefficient MRI and O-(2-\[ 18F\]fluoroethyl-)-L-tyrosine positron emission tomography (ADC/FET) to be significantly more accurate than T1c MRI alone in the detection of tumor infiltration. This makes ADC/FET a suitable candidate to guide supramarginal resection. Since FET PET is not as accessible and widely available as MRI, identification of an MRI based alternative could result in a more widespread implementation. Amide proton transfer chemical exchange saturation transfer (APT-CEST) MRI is a novel potential alternative for FET PET, since both measures are related to protein content. Objective: In this project we aim to develop a safe and effective technique for ADC/FET guided resection of IDH-wildtype glioblastoma and grade IV IDH-mutant astrocytoma. The safety concerns neurological deficits and time to start of adjuvant therapy, while the effectiveness is aimed at the extent of resection. Our secondary aim is to evaluate the diagnostic accuracy of APT-CEST MRI and to assess whether APT-CEST MRI can serve as an alternative for FET PET for the detection of tumor infiltration. Study design: prospective observational intervention study Study population: 30 patients with clinical and radiological diagnosis of an untreated high grade glioma (suspected for glioblastoma (IDH wildtype) or grade IV astrocytoma (IDH mutant)), who are eligible for a supramarginal surgical resection and adjuvant treatment according two neurosurgeons in consensus and who are in relatively good condition (Karnofsky Performance Score (KPS) ≥70). Intervention (if applicable): supramarginal ADC/FET-guided resection. To make sure that the standard treatment is always guaranteed, T1c MRI abnormalities will be included in the surgical target. Main study parameters/endpoints: the main study endpoint is the optimization of ADC/FET-guided resection. Volumetric and percentual extent of resection, as measured with MRI and PET imaging, combined with surgery-induced morbidity will be used as outcome parameters. The secondary study parameters will be the histopathology-based diagnostic accuracy of APT-CEST MRI in comparison with FET PET, cognitive performance over time and progression free survival. Nature and extent of the burden and risks associated with participation, benefit and group relatedness: participants will undergo pre- and postoperative MRI scanning. This is also part of regular clinical care, except there are additional MRI sequences including APT CEST in the pre-operative and pre-radiotherapy MRI. There are no risks associated with MRI acquisition after MRI safety screening. Participants will furthermore undergo a pre- and postoperative FET PET. The risks associated with PET scanning are limited, and the radiation burden will remain below 10 mSv (ICRP62 category intermediate risk (level IIb)). During surgery, biopsies are performed from areas that will be resected, so these biopsies will not introduce any extra risk. A potential benefit is the possibility of the removal of more tumor tissue. A potential risk is the additional removal of healthy brain tissue with the risk of neurological damage, which is controlled by pre- and intraoperative techniques such as visualization of white matter tracts and mapping (both asleep and awake) of critical functions such as language and control of strength.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06623565
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT05990556 - Research on the Safety and Efficacy of Blocking Dural Blood Supply in Glioblastoma Patients (NA, RECRUITING): Glioblastoma is the most common primary malignancy of the central nervous system with a very poor prognosis. Most of the immunotherapies that have made significant breakthroughs in the treatment of other tumors in recent years are unsatisfactory in the application of glioblastoma, which is mainly inseparable from the highly inhibitory immune microenvironment formed by the latter. Therefore, how to change this "immune desert" and better activate immune effector cells to play an anti-tumor effect is currently a hot spot in glioma immune research. In recent years, there has been continuous research support that the myeloid cells of the central nervous system are partly derived from the bone marrow of the skull, and there is a special channel connection between the skull and the dura mater, through which immune cells can be transported. This suggests that some of the tumor-associated macrophages recruited in the glioblastoma microenvironment may be passed through the dura mater. In previous animal experiments, we blocked the main blood supply to the dura mater by ligating the bilateral external carotid arteries of mice, cutting off the potential supply of dura mater to suppressor myeloid cells in the lesion. The results showed that after ligation of bilateral external carotid arteries, the survival period of tumor-forming mice was significantly prolonged and the prognosis was improved. The proportion of myeloid cells in the tumor microenvironment of mice decreased significantly, and the expression of tumor suppressor molecules such as arginase Arg1 decreased, indicating that the improvement of mouse prognosis was closely related to the proportion and phenotypic changes of myeloid cells after dural blood supply blockade. The meningeal lymphatic system of the human central nervous system has been shown to be an important part of the immune system, while the external carotid artery system, the main source of blood supply to the dura, carries abundant immune cells that ooze out to the dura mater through the endothelial window hole of the dural blood vessel, which is an important source of dural immune cells. In the glioblastoma immune microenvironment, the source of immune cells includes dural branches from the external carotid artery system in addition to branches of the internal carotid artery system. Therefore, for patients diagnosed with glioblastoma, this study involves embolization of the dural branch of the external carotid artery system (bilateral middle meningeal artery) to block the dural blood supply before craniotomy. At the same time, microsurgery under multimodal image navigation was used to remove the tumor. It is expected to be effective in reducing the proportion of myeloid suppressor cells in the tumor microenvironment, slowing the growth rate of residual tumor cells, and prolonging the tumor-free progression and survival of patients.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05990556
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT03958240 - Deciphering Mechanisms Underlying Cancer Immunogenicity (NA, RECRUITING): This trial is a translational, open-label, multicentric, prospective cohort study of 1100 patients aiming to describe the PD-1 (programmed death) expression in T cells (T lymphocytes) in different solid tumors. The study will be conducted on a population of patients with local and/or metastatic malignant solid tumor and who are followed within a standard of care procedure or clinical trial. Patients with any of the following tumor types may be enrolled in the trial: * Head and neck cancer, * Ovarian cancer, * Cervical cancer, * Pre-invasive CIN III cervical cancer (Cervical Intra-epithelial Neoplasia III cervical cancer), * Other solid tumor types (including glioblastoma, NSCLC (Non-small cell lung cancer), anal cancer) Each tumor type will be considered as an independent cohort. For each included patient, biological specimen (tumor sample, blood samples and ascites samples if applicable) will be collected. Study participation of each patient will be 5 years.
  Quick read: GBM-related treatment study for GBM or glioma patients; biologic or cellular-therapy; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT03958240
  Review priority: 141
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), ecog_max=1 vs 2 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06719440 - Impact of Reducing the Irradiation Volume on Survival, Toxicity, and Quality of Life in Patients With Glioblastoma Treated With Radiochemotherapy: a Prospective Multicenter Randomised Study (NA, RECRUITING): The objective of the BELGICA trial is to evaluate if radiotherapy could be given in a more focused manner in patients with glioblastoma in order to reduce side effects and improve quality of life. The glioblastoma (GBM) is the most common and aggressive tumour originating from the brain, affecting approximately 600 patients per year in Belgium. The treatment consists in surgical resection of the tumour (when feasible), followed by a combination of radiotherapy and chemotherapy. Despite multimodal treatment (surgery, radiotherapy, and chemotherapy), the life expectancy of patients with GBM remains limited, with an average survival of 12-18 months and only 5% of patients surviving more than 5 years. In addition to limited survival, most patients with GBM experience impaired quality of life, both because of the disease and treatments. Radiotherapy is a treatment where radiation is used to kill cancer cells. In GBM, radiotherapy is targeted at the tumour (or tumour bed if the tumour was resected) with a safety margin around it (the "Clinical Target Volume" or CTV) to account for potential microscopic spread of the tumour. The downside of this safety margin is that a substantial amount of brain tissue is irradiated, which can lead to treatment toxicity. Reducing the CTV margin would enable to decrease the volume of brain being irradiated and could thereby allow to reduce the side effects of brain irradiation. The BELGICA trial (Achieving a BEtter outcome through Limiting the GlIoblastoma Clinical tArget volume) is a national multicentre trial which will evaluate if reducing the irradiation volume in glioblastoma is safe and allows for lowering side effects and improving quality of life.
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT06719440
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: newly_diagnosed
- NCT05954858 - Tissue Autograft to Bypass the Blood Brain Barrier (BBB) in Human Glioblastoma Multiforme (GBM) (NA, RECRUITING): This single center, single arm, open-label, phase 2 study will assess the safety and efficacy of a pedicled temporoparietal fascial (TPF) or pericranial flap into the resection cavity of newly diagnosed glioblastoma multifome (GBM) patients. The objective of the Phase 2 study is to demonstrate that this surgical technique is safe and effective in a human cohort of patients with resected newly diagnosed AA or GBM and may improve progression-free survival (PFS) and overall survival (OS).
  Quick read: GBM-related treatment study for newly diagnosed GBM; radiotherapy-focused; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT05954858
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 70 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good, Matched inclusion factor: newly_diagnosed
- NCT04266977 - Restrictive Use of Dexamethasone in Glioblastoma (NA, RECRUITING): The administration of steroids, most commonly dexamethasone (DEX), has established as standard of care during treatment of glioblastoma (GBM) and is widely used during the entire course of the disease including pre- and postoperative management, chemo- and radiotherapy. The primary purpose is to reduce tumor-associated vasogenic edema and to prevent or treat increased intracranial pressure. However, steroids are also linked to a multitude of adverse side effects that may affect survival of GBM patients such as major immunosuppression. The use of steroids during radiotherapy is associated with reduced overall- and progression-free survival and has been identified as an independent poor prognostic factor. Despite these findings, the suspicion of GBM often triggers the administration of DEX in routine clinical practice, regardless of neurological symptoms, tumor size, or extension of cerebral edema. The purpose of this study is to assess whether selected GBM patients can be treated safely with a restrictive DEX regimen from referral to the neurosurgical center until discharge. The primary objective is to determine the failure rate of a restrictive DEX regimen defined as edema or mass effect leading to any of the following: GCS deterioration ≥ 2 points, NIHSS increase ≥ 3 points, increase of midline Shift ≥ 2mm, or any surgical rescue procedure for increasing mass effect.
  Quick read: GBM-related treatment study for newly diagnosed GBM; drug-treatment; currently recruiting.
  Source: https://clinicaltrials.gov/study/NCT04266977
  Review priority: 140
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: steroid_stable_low, Matched inclusion factor: newly_diagnosed
- NCT07493447 - Pilot Study Evaluating Panitumumab-IRDye800 as an Optical Imaging Agent to Detect Intracranial Lesions During Neurosurgical Procedures (EARLY_PHASE1, NOT_YET_RECRUITING): This pilot clinical study evaluates the safety and imaging performance of panitumumab-IRDye800 (pan800), a fluorescent, EGFR-targeted imaging agent - in patients undergoing neurosurgical resection of intracranial lesions.
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07493447
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: min_age_years=52 vs 18 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none
- NCT06929819 - Research on the Safety and Efficacy of Intraoperative Radiation Therapy in Malignant Cerebral Tumor (NA, NOT_YET_RECRUITING): According to the latest national cancer statistics released by the National Cancer Center in February 2022, intracranial tumors account for about 60%-70% of the more than 3.5 million cancer patients, and the morbidity and mortality remain high. Intracranial malignant tumors have become a problem that needs to be solved urgently because of their early recurrence, rapid progression, and short survival, and intracranial malignant tumors include high-grade gliomas, metastases, lymphomas, etc. Glioblastoma (GB) is the most common primary malignancy in the adult central nervous system, accounting for about 57% of all gliomas and 48% of all primary weighted nervous system malignancies. At present, the standard treatment for glioblastoma is mainly surgical treatment, supplemented by postoperative concurrent chemoradiotherapy and adjuvant chemotherapy, but the prognosis of patients is still poor, with a one-year survival rate of 40.6%, a five-year survival rate of only 5.6%, and an average survival time of 12-15 months. For patients diagnosed with intracranial malignancies (including high-grade glioma, metastases, lymphoma, etc.), multimodal image-guided microsurgery combined with postoperative chemoradiotherapy recommended by the guidelines, and intraoperative radiotherapy with tumor bed radiation therapy to achieve targeted and precise tumor treatment, thereby improving the prognosis of patients (including progression-free survival and median overall survival, etc.)
  Quick read: GBM-related treatment study for GBM or glioma patients; radiotherapy-focused; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT06929819
  Review priority: 138
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: kps_min=80 vs 60 (match), requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: Matched inclusion factor: performance_status_good
- NCT07384884 - Surgery and Laser Interstitial Thermal Therapy for Bilateral Glioblastomas (NA, NOT_YET_RECRUITING): Butterfly glioblastomas (bGBM), defined as tumours crossing the midline to involve hemispheres bilaterally, have a dismal prognosis with a median survival of 3.3-6 months and only 9% of patients with bGBM survive 2-years. These figures put bGBM in the worst end of the spectrum of GBM prognosis, significantly inferior to the survival figures quoted in the literature with standard of care - 14.6 months - particularly when 5-aminolevulinic acid is used as surgical adjuvant - 17.47 months. Despite the poor outcome of this disease, there is preliminary evidence suggesting that active oncology treatment can impact the survival of patients with this condition.With particular regards to surgical resection versus biopsy, there is a suggestion that resection improves overall survival at 6 months with no clear difference at 12 and 18 months of follow up. Laser-induced thermal therapy (LITT) is a minimally invasive laser ablation technique used in a range of brain tumours, including glioblastomas, with similar overall survival to the ones reported for open surgery in patients with lesions not amenable to open resection. The minimally invasive nature of this technique, significantly reducing the collateral damage to the surrounding brain structures, suggests Its potential in the treatment of this bGBM \[14\] with significant implications as a deficit-sparing technique, particularly if associated with preoperative and intraoperative monitoring and mapping techniques. The SLITT-GBM study will combine unilateral open surgery for maximal tumour resection with contralateral LITT to the smaller component/residual.
  Quick read: GBM-related treatment study for GBM or glioma patients; treatment-related; not yet recruiting.
  Source: https://clinicaltrials.gov/study/NCT07384884
  Review priority: 134
  Ranking: rank=n/a, gbm_specificity=n/a, treatment_relevance=n/a, focus=n/a, purpose=n/a
  Parsed constraints: age>=n/a, KPS>=n/a, ECOG<=n/a, recurrence_max=n/a, HLA=n/a
  Parsed provenance count: 0
  Patient/trial comparisons: requires_stable_or_decreasing_steroids=True vs False (match)
  Reasons: none

#### Related Papers
- PMID:34898238 - Therapy for Diffuse Astrocytic and Oligodendroglial Tumors in Adults: ASCO-SNO Guideline.
  Quick read: Guideline-style reference for GBM-specific, newly_diagnosed, focused on radiation, temozolomide in Journal of clinical oncology : official journal of the American Society of Clinical Oncology (2022). Linked to NCT06504381.
  Source: https://pubmed.ncbi.nlm.nih.gov/34898238/
- PMID:37059335 - ESTRO-EANO guideline on target delineation and radiotherapy details for glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2023).
  Source: https://pubmed.ncbi.nlm.nih.gov/37059335/
- PMID:35426875 - Congress of Neurological Surgeons Systematic Review and Evidence-Based Guidelines on the Management of Progressive Glioblastoma in Adults: Update of the 2014 Guidelines.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Neurosurgery (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35426875/
- PMID:35246769 - Congress of neurological surgeons systematic review and evidence-based guidelines update on the role of cytoreductive surgery in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35246769/
- PMID:35195819 - Congress of Neurological Surgeons systematic review and evidence-based guidelines update on the role of cytotoxic chemotherapy and other cytotoxic therapies in the management of progressive glioblastoma in adults.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2022).
  Source: https://pubmed.ncbi.nlm.nih.gov/35195819/
- PMID:29086250 - SEOM clinical guidelines for diagnosis and treatment of glioblastoma (2017).
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Clinical & translational oncology : official publication of the Federation of Spanish Oncology Societies and of the National Cancer Institute of Mexico (2018).
  Source: https://pubmed.ncbi.nlm.nih.gov/29086250/
- PMID:27907278 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of oncology practice (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27907278/
- PMID:27893327 - Radiation Therapy for Glioblastoma: American Society of Clinical Oncology Clinical Practice Guideline Endorsement of the American Society for Radiation Oncology Guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on radiation in Journal of clinical oncology : official journal of the American Society of Clinical Oncology (2017).
  Source: https://pubmed.ncbi.nlm.nih.gov/27893327/
- PMID:26777122 - ESTRO-ACROP guideline "target delineation of glioblastomas".
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Radiotherapy and oncology : journal of the European Society for Therapeutic Radiology and Oncology (2016).
  Source: https://pubmed.ncbi.nlm.nih.gov/26777122/
- PMID:25079102 - EANO guideline for the diagnosis and treatment of anaplastic gliomas and glioblastoma.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in The Lancet. Oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/25079102/
- PMID:24756348 - The role of cytoreductive surgery in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24756348/
- PMID:24740195 - The role of targeted therapies in the management of progressive glioblastoma : a systematic review and evidence-based clinical practice guideline.
  Quick read: Guideline-style reference for GBM-specific, mixed-stage, focused on general treatment context in Journal of neuro-oncology (2014).
  Source: https://pubmed.ncbi.nlm.nih.gov/24740195/

#### Related Datasets
- gdc_tcga_gbm - NCI GDC TCGA-GBM
  Quick read: Core GBM tumor-genomics program with somatic variants, copy-number, expression, methylation, and linked clinical metadata; open and controlled-access layers.
  Source: https://gdc.cancer.gov/about-data/publications/gbm_2013
- gdc_tcga_lgg_gbm - NCI GDC TCGA Pan-Glioma Cohorts
  Quick read: Combined glioma genomics across lower-grade glioma and GBM for broader IDH, MGMT, and progression-context comparisons.
  Source: https://portal.gdc.cancer.gov/
- ivy_gap - Ivy Glioblastoma Atlas Project
  Quick read: Region-resolved glioblastoma atlas with anatomic and molecular context across tumor subregions.
  Source: https://glioblastoma.alleninstitute.org/
- cbioportal_gbm - cBioPortal GBM Studies
  Quick read: Searchable GBM and glioma genomics knowledgebase spanning TCGA and many published studies with mutation, CNA, and outcome views.
  Source: https://www.cbioportal.org/
- cptac_gbm - CPTAC Brain / Glioblastoma Proteogenomic Resources
  Quick read: Proteomic and proteogenomic tumor data relevant to GBM biology and pathway activation beyond DNA-only signals.
  Source: https://proteomics.cancer.gov/programs/cptac

#### Missing Evidence
- Tumor sequencing report available: A structured NGS report or equivalent molecular panel.
  Missing artifact types: ngs_report
- HLA typing available: HLA typing lab result.
  Missing artifact types: hla_typing_result
