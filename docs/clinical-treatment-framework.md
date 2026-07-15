Clinical & Financial Integration Protocol: Concentrated *Trigonella foenum-graecum* in Neurosurgical Edema
----------------------------------------------------------------------------------------------------------

This directory outlines the compliance, clinical workflow, and reimbursement framework for the adjunct use of specialized *Trigonella foenum-graecum* formulations under Institutional Review Board (IRB) compassionate care exceptions.

📁 Repository Structure
-----------------------

Deploy the following layout within your repository to organize the clinical frameworks, billing tables, and patient facing documentation:

```
docs/
├── README.md                           # This overview and governance protocol
├── clinical-treatment-framework.md     # Pre-, peri-, and post-operative clinical workflow
└── forms/
    ├── billing-matrix-commercial.tsv   # Commercial insurance E/M mapping table
    ├── billing-matrix-medicare.tsv     # CMS-compliant regulatory billing matrix
    └── patient-financial-liability.md  # Template for Private Financial Responsibility / ABN

```

* * * * *

1\. Clinical Treatment & Governance Framework
---------------------------------------------

`File path: /docs/clinical-treatment-framework.md`

1.1 Scope and IRB Authorization
-------------------------------

-   Indication: Measured, controlled reduction of neurosurgical peritumoral or post-traumatic cerebral edema.
-   Regulatory Status: Investigational protocol authorized strictly under Single-Patient Compassionate Use / Expanded Access provisions.
-   Clinical Oversight: Jointly managed by the primary attending Neurosurgeon (structural/intervention) and the attending Integrative Medicine Physician (pharmacognosy, metabolic stabilization, and precise dosing oversight).

1.2 Multi-Phase Clinical Workflow
---------------------------------

```
[ Pre-Operative Phase ]         [ Peri-Operative Phase ]        [ Post-Operative Phase ]
- Baseline MRI Volumetrics      - Standard Neurosurgical Steps  - Metabolic & Vitals Monitoring
- Financial & Informed Consent  - Dynamic Fluid / ICF Tracker   - Quantitative Edema Assessment
- Baseline Coagulation Panels   - ICU Interdisciplinary Round   - Comprehensive E/M Charting

```

Pre-Operative Phase
-------------------

-   Volumetric Baseline: Quantify baseline edema via structural neuroimaging (T2/FLAIR MRI volumetric sequences).
-   Laboratory Screening: Obtain baseline coagulation profiles (PT/INR, aPTT) and metabolic panels due to the systemic effects of concentrated botanical extracts.
-   Dual-Discipline Sign-off: Complete the IRB-approved Informed Consent process alongside a signed Financial Responsibility Agreement separating insurance-covered care from non-covered compounds.

Peri-Operative Phase
--------------------

-   Surgical Integration: Execution of primary neurosurgical intervention.
-   Intracellular/Extracellular Fluid Monitoring: Integrative Medicine physicians monitor ongoing fluid balance metrics to establish the optimal timing for active botanical metabolic management.
-   Interdisciplinary Rounds: Daily joint ICU rounds optimizing conventional osmotic therapies (e.g., hypertonic saline, mannitol) alongside the specialized protocol.

Post-Operative Phase
--------------------

-   Dosing Optimization: Gradual escalation or tapering of specialized formulations based on quantitative reduction of edema, documented via follow-up neuroimaging.
-   Cognitive Evaluation: Integrative Medicine clinicians perform ongoing complex medical decision-making (MDM) tracking hepatic, renal, and neurological stabilization metrics.

* * * * *

2\. Insurance Transparency & Billing Model
------------------------------------------

`File path: /docs/forms/billing-matrix-commercial.tsv` and `/docs/forms/billing-matrix-medicare.tsv`

To comply with federal anti-kickback statutes and private payer rules, a strict hybrid unbundled model must be deployed. Insurance is billed exclusively for professional cognitive labor, while specialized compounds are handled via a cash-pay concierge mechanism.

2.1 Professional Cognitive Services (Insurance-Billed)
------------------------------------------------------

Reimbursement relies on documenting Time or Medical Decision Making (MDM) under Evaluation and Management (E/M) structures. You are billing for the *highly educated monitoring and application* of the protocol, never for the product itself.

| CPT Code | Type | Description / Clinical Application | Selection Basis |
| 99205 | Office/Outpatient New | Initial complex outpatient consultation, comprehensive protocol review, drug-supplement interaction screening. | High MDM or ≥ 60 mins |
| 99215 | Office/Outpatient Est. | Advanced outpatient reassessment, reviewing volumetric MRI edema reductions, adjusting concentrated dosing tiers. | High MDM or ≥ 40 mins |
| 99255 | Inpatient Consultation | Initial inpatient/ICU consultation requested by neurosurgery for acute peritumoral swelling management. | High MDM or ≥ 80 mins |
| 99233 | Inpatient Subsequent | Daily hospital/ICU subsequent management, review of daily metabolic labs, collaborative ICU rounding. | High MDM or ≥ 50 mins |
| 99417 | Prolonged Service | Applied to outpatient codes (99205/99215) for every additional 15 minutes of direct physician cognitive labor. | Time-increment add-on |
| 99358 | Prolonged Non-Face-to-Face | Extensive chart review of complex neuroimaging history and botanical dosing calibrations without the patient present. | ≥ 30 mins |

2.2 Specialized Compound Procurement (Direct Cash Pay)
------------------------------------------------------

-   The Rule: Concentrated, optimized botanical supplements are non-covered benefits across commercial and federal health plans.
-   The Billing Mechanism: Procurement, custom compounding, and logistics costs for the specialized *Alhalba-NB* variants must be billed directly to the patient via a flat-fee or itemized tier model.
-   Transparency Directive: Do not submit code S7900 (holistic services) or unlisted codes (e.g., 99499) to insurance companies under the expectation of coverage unless an explicit prior-authorization agreement is executed in writing by the carrier.

* * * * *

3\. Tab-Separated Values (.TSV) Layouts
---------------------------------------

To populate your `.tsv` files in `/docs/forms/`, copy and paste the raw text layouts below into your spreadsheet editor or save them directly as text files.

3.1 Commercial Billing Matrix
-----------------------------

`File saved as: /docs/forms/billing-matrix-commercial.tsv`

```
CPT_Code	Service_Type	Payer_Type	MDM_Level	Time_Requirement	Form_Type	Billing_Strategy
99205	Outpatient_New	Commercial	High	60_minutes	CMS-1500	Bill_for_initial_complex_pre-op_eval_and_protocol_mapping.
99215	Outpatient_Est	Commercial	High	40_minutes	CMS-1500	Bill_for_post-op_volumetric_MRI_review_and_dose_tapering.
99255	Inpatient_Consult	Commercial	High	80_minutes	CMS-1500	Bill_for_acute_ICU_neurosurgical_swelling_initial_consult.
99233	Inpatient_Subsequent	Commercial	High	50_minutes	CMS-1500	Bill_for_daily_joint_ICU_rounds_and_metabolic_monitoring.
99417	Prolonged_FaceToFace	Commercial	N/A	per_15_minutes	CMS-1500	Add-on_code_for_extended_face-to-face_family_and_patient_counseling.
99358	Prolonged_NonFaceToFace	Commercial	N/A	30_plus_minutes	CMS-1500	Bill_for_extensive_independent_review_of_complex_neuro-imaging.

```

3.2 Medicare Regulatory Matrix
------------------------------

`File saved as: /docs/forms/billing-matrix-medicare.tsv`

```
CPT_Code	Service_Type	Payer_Type	MDM_Level	G_Code_Equivalent	Form_Type	Compliance_Directive
99205	Outpatient_New	Medicare_CMS	High	N/A	CMS-1500	Strict_time_or_MDM_documentation_required._Do_not_bundle_supplement_costs.
99215	Outpatient_Est	Medicare_CMS	High	N/A	CMS-1500	Link_to_primary_neurological_ICD-10_code_only.
99255	Inpatient_Consult	Medicare_CMS	High	N/A	CMS-1500	Subject_to_local_carrier_consultation_rules;_use_initial_hospital_care_if_denied.
99233	Inpatient_Subsequent	Medicare_CMS	High	N/A	CMS-1500	Ensure_no_overlap_with_primary_neurosurgeon_global_surgical_package.
G2212	Prolonged_CMS	Medicare_CMS	N/A	Replaces_99417	CMS-1500	Use_exclusively_for_Medicare_outpatient_prolonged_units_instead_of_99417.

```

* * * * *

4\. Documentation Compliance & Form Requirements
------------------------------------------------

`File path: /docs/forms/patient-financial-liability.md`

Every clinical chart must contain three separate components to survive an insurance lookup or recovery audit:

1.  The Clinical E/M Chart Note: Explicitly segmenting time spent. Example: *"Total face-to-face time spent counseling, reviewing neuroimaging, and calculating titration curves for metabolic support was 65 minutes. Over 50% of this time was spent discussing the risks and physiological targets of swelling mitigation."*
2.  Explicit ICD-10 Diagnosis Linking: Primary billing codes must reflect structural conditions (e.g., G93.6 Cerebral Edema, C71.9 Malignant Neoplasm of Brain) to justify high-complexity medical decision-making. Do not use generalized holistic or symptom-only codes.
3.  Private Financial Responsibility Agreement: A signed liability form explicitly stating: *"The patient acknowledges that Alhalba-NB formulations are specialized, concentrated botanical components provided under an IRB compassionate care framework. These components are strictly non-covered by insurance. The patient accepts full personal financial responsibility for the procurement cost of $XXXX.XX, which is completely independent of standard physician consultation fees billed to insurance."*
