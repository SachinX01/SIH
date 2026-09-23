# Praman Setu Research and Hyperlink Library

> Research source library for the SIH26231 presentation. Each entry includes a PPT keyword, a clickable source link, what it supports, and the claim boundary. These sources inform the design; they do not by themselves certify the prototype as legally admissible, operationally approved, or laboratory-accredited.

## How to Use This File in the PPT

- Link a short keyword or phrase rather than displaying a long URL on every slide.
- Use government and statutory sources for the legal-context slide.
- Use forensic and laboratory sources for quality, validation, presumptive testing, and confirmation boundaries.
- Use digital-evidence and cryptography sources for hash, signature, integrity, and export architecture.
- Use technical documentation for the implementation stack.
- Keep the claim boundary next to legal or standards references: “reference guidance, not a claim of compliance.”

## 1. Indian Government and Problem Context

### SIH26231 Problem Statement

- PPT keyword: `SIH26231 Problem Statement`
- Link: [Smart India Hackathon 2026 problem statements](https://sih.gov.in/sih2026PS)
- Authority: Smart India Hackathon / Government innovation program.
- Supports: The official problem context, organization, category, theme, deadline, and requirement to build a mobile application alongside existing colorimetric field-test kits.
- Use in PPT: Title slide, problem slide, or final references slide.
- Claim boundary: This is the competition requirement, not a scientific or legal approval of the proposed solution.

### Ministry of Home Affairs

- PPT keyword: `Ministry of Home Affairs`
- Link: [Ministry of Home Affairs, Government of India](https://www.mha.gov.in/)
- Authority: Government of India, Ministry of Home Affairs.
- Supports: Institutional context for the problem owner and law-enforcement domain.
- Use in PPT: Problem-owner, stakeholder, or solution-context slide.
- Claim boundary: The ministry website establishes institutional context; it does not endorse Praman Setu.

### Narcotics Control Bureau

- PPT keyword: `NCB drug-law enforcement context`
- Link: [Narcotics Control Bureau, Government of India](https://ncb.gov.in/)
- Authority: Government of India, Ministry of Home Affairs.
- Supports: National drug-law-enforcement context and the operational environment in which seized-substance workflows may occur.
- Use in PPT: “Stakeholders and operational context” or references slide.
- Claim boundary: NCB information must not be presented as an NCB endorsement or as a product-specific operating procedure.

### India Code

- PPT keyword: `India Code official legislation`
- Link: [India Code official legislation portal](https://www.indiacode.gov.in/)
- Authority: Government of India legislation portal.
- Supports: Official access point for checking current Acts and statutory wording, including the NDPS Act, BNSS, and BSA.
- Use in PPT: Legal framework slide and statutory-source footnotes.
- Claim boundary: Always verify the current Act, section, commencement, amendments, and applicable rules before production use.

## 2. Legal and Procedural Alignment

### BNSS Section 105 - Audio-Video Recording of Search and Seizure

- PPT keyword: `BNSS Section 105`
- Link: [Bharatiya Nagarik Suraksha Sanhita, 2023 - official MHA PDF](https://www.mha.gov.in/sites/default/files/2024-02/BNSS_2023_English.pdf)
- Additional source: [MHA - Three New Criminal Laws](https://www.mha.gov.in/en/commoncontent/three-new-criminal-laws)
- Supports: Legal-context discussion of audio-video recording for search and seizure processes and the need for procedural documentation.
- Praman Setu mapping: Store capture timestamps, event sequence, operator identity, device metadata, image hash, and references to any separate statutory recording.
- Use in PPT: `Legal framework -> Audio-video recording and traceability`.
- Claim boundary: Praman Setu does not replace the authorized officer’s statutory recording, forwarding, custody, or procedural duties. Confirm the current official text and legal interpretation with competent authority.

### NDPS Act Section 52A - Inventory, Photographs, Samples, and Magistrate Process

- PPT keyword: `NDPS Section 52A`
- Link: [NDPS Act, 1985 - Department of Revenue PDF](https://dor.gov.in/sites/default/files/NDPSAct1985.pdf)
- Additional source: [India Code legislation portal](https://www.indiacode.gov.in/)
- Authority: Statutory framework for narcotics and psychotropic-substance matters in India.
- Supports: Legal context for inventory, photographs, representative samples, and the Magistrate-related certification process for seized material.
- Praman Setu mapping: Provide checklist fields for inventory reference, photograph reference, sample reference, responsible officer, certificate reference, and review status; preserve the original image and metadata.
- Use in PPT: `Legal framework -> NDPS Section 52A workflow checkpoint`.
- Claim boundary: The app cannot perform Magistrate certification, decide compliance, replace a seizure memo, or replace laboratory analysis.

### Bharatiya Sakshya Adhiniyam Section 63(4) - Electronic Records

- PPT keyword: `BSA Section 63(4)`
- Link: [Bharatiya Sakshya Adhiniyam, 2023 - India Code PDF](https://www.indiacode.nic.in/bitstream/123456789/20098/1/a2023-47.pdf)
- Additional source: [India Code official legislation portal](https://www.indiacode.gov.in/)
- Supports: Legal context for electronic-record production, certificate requirements, and source/device particulars.
- Praman Setu mapping: Export a certificate-ready evidence bundle containing canonical JSON, original image, hash, signature, public key, device details, software/reference versions, and record identifiers.
- Use in PPT: `Digital evidence -> Certificate-ready export`.
- Claim boundary: A hash or digital signature alone is not automatic compliance with Section 63(4); the competent authority must determine the required certificate and evidentiary use.

### Bharatiya Sakshya Adhiniyam and Digital Evidence

- PPT keyword: `Electronic record integrity`
- Link: [India Code official legislation portal](https://www.indiacode.gov.in/)
- Supports: Current official location for checking the BSA and related statutory text.
- Praman Setu mapping: Separate technical integrity checks from legal certification and courtroom admissibility.
- Use in PPT: Add as a linked keyword on the verification or legal-boundary slide.
- Claim boundary: Do not say “legally admissible” merely because the record is hashed or signed.

### Yusuf @ Asif v. State - Section 52A Case-Law Checkpoint

- PPT keyword: `Section 52A case-law checkpoint`
- Link: [Supreme Court of India](https://www.sci.gov.in/)
- Reference: Yusuf @ Asif v. State, cited in the supplied reference video in the context of Section 52A compliance.
- Supports: The importance of treating statutory seizure, sampling, and certification safeguards as substantive procedural requirements.
- Praman Setu mapping: Add a compliance checklist and review trail rather than allowing the app to imply that a field color result is final evidence.
- Use in PPT: `Legal framework -> Case-law lesson`.
- Claim boundary: Verify and cite the official judgment PDF and exact citation before making a detailed legal argument in a final submission.

## 3. Forensic Science and Drug-Analysis Guidance

### NIST Forensic Science

- PPT keyword: `NIST forensic quality and validation`
- Link: [NIST Forensic Science](https://www.nist.gov/forensic-science)
- Authority: U.S. National Institute of Standards and Technology.
- Supports: Scientific methods, validation, quality assurance, evidence handling, human factors, and reliable communication of forensic results.
- Praman Setu mapping: Version the Reference DB and classifier, record quality signals, preserve the original image, and expose uncertainty.
- Use in PPT: `Research basis -> Validation and reproducibility`.
- Claim boundary: NIST guidance is not Indian law and does not certify Praman Setu.

### NIST OSAC Forensic Science Standards

- PPT keyword: `OSAC forensic standards`
- Link: [Organization of Scientific Area Committees for Forensic Science](https://www.nist.gov/adlp/spo/organization-scientific-area-committees-forensic-science)
- Supports: Technically sound forensic standards, minimum requirements, best practices, protocols, and guidance for reliable and reproducible forensic analysis.
- Praman Setu mapping: Keep capture, analysis, review, and export steps explicit and auditable.
- Use in PPT: `Forensic standards and quality`.
- Claim boundary: OSAC is a standards and guidance reference; it is not a Government of India operating approval.

### OSAC Seized Drugs Process Map

- PPT keyword: `Seized-drugs process map`
- Link: [OSAC Seized Drugs Subcommittee process map](https://www.nist.gov/news-events/news/2022/11/osacs-seized-drugs-subcommittee-develops-process-map)
- Supports: Process-oriented thinking for seized-drug examination decisions and documentation.
- Praman Setu mapping: Make kit validation, capture quality, classification, Inconclusive handling, review, and laboratory escalation visible as separate states.
- Use in PPT: `Workflow -> Decision points and escalation`.
- Claim boundary: This is a reference process map, not a substitute for Indian agency SOPs or kit protocols.

### SWGDRUG Recommendations

- PPT keyword: `SWGDRUG recommendations`
- Link: [SWGDRUG approved recommendations](https://www.swgdrug.org/approved.htm)
- Supports: International forensic drug-analysis recommendations, terminology, analytical approach, and confirmation limitations.
- Praman Setu mapping: Keep the field result presumptive and route uncertain or out-of-range results to repeat testing or laboratory confirmation.
- Use in PPT: `Presumptive field test -> laboratory confirmation boundary`.
- Claim boundary: SWGDRUG is not an Indian statutory authority and does not validate the prototype’s thresholds.

### ISO/IEC 17025:2017

- PPT keyword: `ISO 17025 laboratory competence`
- Link: [ISO/IEC 17025:2017](https://www.iso.org/standard/66912.html)
- Supports: Competence, impartiality, consistent operation, and quality management of testing and calibration laboratories.
- Praman Setu mapping: Treat the app output as a field-support record and preserve a path to competent laboratory confirmation.
- Use in PPT: `Quality assurance -> Laboratory confirmation`.
- Claim boundary: The prototype is not an ISO/IEC 17025-accredited laboratory and does not claim certification.

## 4. Digital Evidence, Security, and Integrity

### NIST FIPS 180-4 - Secure Hash Standard

- PPT keyword: `SHA-256 image integrity`
- Link: [NIST FIPS 180-4 Secure Hash Standard](https://csrc.nist.gov/pubs/fips/180-4/upd1/final)
- Supports: Cryptographic hash functions and change detection through message digests.
- Praman Setu mapping: Hash the original uncorrected image bytes and store the image hash in the canonical record.
- Use in PPT: `Evidence record -> SHA-256 fingerprint`.
- Claim boundary: A hash detects changes; it does not prove who captured the image, when it was captured, or that the underlying test was scientifically valid.

### NIST FIPS 186-5 - Digital Signature Standard

- PPT keyword: `Digital signature`
- Link: [NIST FIPS 186-5 Digital Signature Standard](https://csrc.nist.gov/pubs/fips/186-5/final)
- Supports: Digital-signature algorithms used to detect unauthorized modification and authenticate the signatory.
- Praman Setu mapping: Sign canonical record bytes or the documented record hash, export the public key, and verify the signature in `verify.html`.
- Use in PPT: `Evidence record -> Signature verification`.
- Claim boundary: Prototype signing is not agency PKI, HSM protection, trusted timestamping, or legal certification.

### ISO/IEC 27001:2022

- PPT keyword: `Information security controls`
- Link: [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)
- Supports: Information-security risk management, confidentiality, integrity, availability, and organizational controls.
- Praman Setu mapping: Use for future production security planning, key management, access control, retention, incident response, and auditability.
- Use in PPT: `Security roadmap`.
- Claim boundary: The prototype is not ISO/IEC 27001 certified.

### ISO/IEC 27037 - Digital Evidence Handling

- PPT keyword: `Digital evidence preservation`
- Link: [ISO/IEC 27037 overview](https://www.iso.org/standard/44381.html)
- Supports: Identification, collection, acquisition, and preservation principles for digital evidence.
- Praman Setu mapping: Preserve original image bytes, record acquisition metadata, keep append-only evidence references, and prevent silent mutation.
- Use in PPT: `Evidence lifecycle -> Preservation`.
- Claim boundary: The standard is a reference for evidence handling; legal acceptance depends on the applicable jurisdiction and authority.

### NIST Digital Evidence

- PPT keyword: `Digital evidence lifecycle`
- Link: [NIST Digital Evidence](https://www.nist.gov/digital-evidence)
- Supports: Digital-forensics and digital-evidence research context.
- Praman Setu mapping: Separate acquisition, preservation, verification, review, and export from the color-classification result.
- Use in PPT: `Evidence lifecycle`.
- Claim boundary: A mobile evidence workflow still requires agency SOPs, validation, access control, and legal review.

## 5. Privacy, Data Protection, and Operations

### Digital Personal Data Protection Act

- PPT keyword: `Privacy and personal data`
- Link: [MeitY Digital Personal Data Protection framework](https://www.meity.gov.in/data-protection-framework)
- Authority: Ministry of Electronics and Information Technology, Government of India.
- Supports: Privacy and personal-data governance context for operator IDs, GPS, case identifiers, witness IDs, and captured images.
- Praman Setu mapping: Minimize collected data, define purpose and retention, secure local storage, control exports, and document deletion/archival behavior.
- Use in PPT: `Privacy by design`.
- Claim boundary: Confirm the current Act, rules, exemptions, and agency policy before production deployment.

### CERT-In Directions

- PPT keyword: `Cyber incident and logging readiness`
- Link: [CERT-In Directions and advisories](https://www.cert-in.org.in/)
- Authority: Indian Computer Emergency Response Team.
- Supports: Security-operations and incident-reporting context for a future connected deployment.
- Praman Setu mapping: Define audit logs, failed-sync diagnostics, key-compromise response, and incident escalation before adding a backend.
- Use in PPT: `Future production security`.
- Claim boundary: Do not imply that a local offline prototype is compliant with every CERT-In requirement; assess the final deployment architecture.

## 6. Additional Relevant Government Posts and Research

### BPR&D SOP for Crime Scene Audio-Video Recording

- PPT keyword: `BPR&D audio-video recording SOP`
- Link: [SOP for Crime Scene Audio-Video Recording - BPR&D](https://bprd.nic.in/uploads/pdf/1723616060_2a3a0a30527ffcffc634.pdf)
- Authority: Bureau of Police Research and Development, Ministry of Home Affairs, Government of India.
- Supports: Operational guidance for recording crime-scene processes and connecting the legal requirement to a practical police workflow.
- Praman Setu mapping: Add a recording-availability field, event timestamp sequence, responsible officer, media reference, hash, and review checklist.
- Use in PPT: `Legal framework -> From statutory requirement to operational SOP`.
- Claim boundary: The app can support documentation; it does not replace the SOP or certify that an officer followed it.

### BPR&D Criminal-Law Resource Page

- PPT keyword: `BPR&D new criminal laws resources`
- Link: [BPR&D official website](https://bprd.nic.in/)
- Direct resources visible on the official page:
	- [BNSS 2023 PDF](https://bprd.nic.in/uploads/pdf/1706692115_3dc6c3da9f188c3dd856.pdf)
	- [BSA 2023 PDF](https://bprd.nic.in/uploads/pdf/1706692128_8f492ecc039016415853.pdf)
	- [SOP for FIR and e-FIR](https://bprd.nic.in/uploads/pdf/1720265696_7d2a5fcaa27d7d6f5245.pdf)
	- [NCRB Sankalan of New Criminal Laws](https://ncrb.gov.in/uploads/SankalanPortal/Index.html)
- Authority: Bureau of Police Research and Development / NCRB, Government of India.
- Supports: Official training and implementation context for the new criminal laws and police documentation workflows.
- Praman Setu mapping: Use as a source for implementation checklists and training-oriented legal context, not as a replacement for agency legal review.
- Use in PPT: `Government implementation resources`.
- Claim boundary: Link the exact section and version used; do not cite the resource page as a product endorsement.

### NIST Safe, Efficient, Reliable: New Science in the Fight Against Killer Drugs

- PPT keyword: `Safe field handling and laboratory confirmation`
- Link: [NIST - Safe, Efficient, Reliable: New Science in the Fight Against Killer Drugs](https://www.nist.gov/feature-stories/safe-efficient-reliable-new-science-fight-against-killer-drugs)
- Publisher: National Institute of Standards and Technology.
- Supports: The danger of unknown/high-potency substances, the need to minimize exposure, collaboration with forensic laboratories, method validation, and the limits of rapid identification.
- Praman Setu mapping: Add a safety disclaimer, do not require opening or handling substances for the demo, keep field results presumptive, and route uncertain results to laboratory confirmation.
- Use in PPT: `Safety and laboratory boundary`.
- Claim boundary: This article discusses NIST research and U.S. operational context; it is not an Indian field-testing SOP.

### NIST A Safer Way for Police to Test Drug Evidence

- PPT keyword: `Minimize exposure during testing`
- Link: [NIST - A Safer Way for Police to Test Drug Evidence](https://www.nist.gov/news-events/news/2019/09/safer-way-police-test-drug-evidence)
- Publisher: National Institute of Standards and Technology.
- Supports: The principle of reducing direct handling and exposure while obtaining an initial indication before laboratory work.
- Praman Setu mapping: The app documents the visual field-kit workflow without asking the team to handle real substances in the demonstration.
- Use in PPT: `Safety-by-design`.
- Claim boundary: This research does not validate Praman Setu’s color thresholds or replace safe-handling SOPs.

### NIST Validation in Forensic Science - NISTIR 8589

- PPT keyword: `Forensic method validation`
- Link: [NISTIR 8589 - Validation in Forensic Science](https://www.nist.gov/publications/validation-forensic-science-guiding-principles-collection-and-use-validation-data)
- DOI: [10.6028/NIST.IR.8589](https://doi.org/10.6028/NIST.IR.8589)
- Supports: Validation planning, performance characterization, validation data, reproducibility, and sharing of validation evidence.
- Praman Setu mapping: Validate kit-specific Reference DB values, thresholds, lighting conditions, camera variability, false-positive/false-negative behavior, and Inconclusive rules before operational deployment.
- Use in PPT: `Validation plan -> Calibration and classification evidence`.
- Claim boundary: A prototype demonstration is not method validation.

### NIST Forensic Process Mapping

- PPT keyword: `Decision-point workflow`
- Link: [NIST Forensic Science Process Mapping](https://www.nist.gov/forensic-science/process-mapping)
- Supports: Process maps that make decision points visible, reveal improvement opportunities, support training, and help compare protocols.
- Praman Setu mapping: Model the test as explicit states: kit validation, timer, capture, card validation, sample measurement, result, export, verification, and escalation.
- Use in PPT: `Workflow and decision gates`.
- Claim boundary: A process map helps organize a workflow; it does not establish legal authority or scientific validity by itself.

### NIST Forensic Quality Assurance

- PPT keyword: `Forensic quality assurance`
- Link: [NIST Forensic Quality Assurance](https://www.nist.gov/forensic-quality-assurance)
- Supports: Policies and practices used by forensic laboratories to ensure analytical results are accurate and reliable, including interlaboratory studies and reference materials.
- Praman Setu mapping: Preserve quality scores, calibration residuals, algorithm/reference versions, and test datasets for future validation.
- Use in PPT: `Quality assurance and reproducibility`.
- Claim boundary: Praman Setu is not a forensic laboratory quality system.

### NIST Digital Evidence Research

- PPT keyword: `Preserve without alteration`
- Link: [NIST Digital Evidence](https://www.nist.gov/digital-evidence)
- Supports: Retrieving, storing, and analyzing electronic data while ensuring methods capture data reliably without altering it.
- Praman Setu mapping: Keep original image bytes immutable, separate evidence from the analysis copy, record acquisition metadata, and verify the exported bundle.
- Use in PPT: `Digital evidence lifecycle`.
- Claim boundary: Hashing supports integrity checking but does not independently establish authenticity, lawful acquisition, or admissibility.

### NIST OSAC Standard for Sampling Seized Drugs

- PPT keyword: `Sampling requires validated procedure`
- Link: [OSAC Standard for Sampling Seized Drugs](https://www.nist.gov/news-events/news/2017/04/standard-sampling-seized-drugs-approved-osac-registry)
- Supports: The importance of a technically sound, documented sampling procedure for seized-drug analysis.
- Praman Setu mapping: Keep the app’s field color result separate from sample selection, representative sampling, and laboratory confirmation.
- Use in PPT: `Field indication versus laboratory sampling`.
- Claim boundary: This is a forensic standard reference, not a license to define sampling rules in the app.

### National Forensic Sciences University

- PPT keyword: `Forensic science ecosystem`
- Link: [National Forensic Sciences University](https://nfsu.ac.in/)
- Authority: Institution of National Importance in the forensic-science domain.
- Supports: Indian forensic-science education, research, training, and professional ecosystem context.
- Praman Setu mapping: Identifies the type of expert, laboratory, and training ecosystem needed for future validation and adoption.
- Use in PPT: `Future validation and stakeholder ecosystem`.
- Claim boundary: NFSU is a contextual research/training source, not an endorsement of the prototype.

### Research Sources Not Used as Direct Claims

- UNODC scientific and forensic resources are relevant to drug-analysis methods, but the specific pages were not reliably retrievable during this session; do not quote an exact UNODC guideline until the official document and version are verified.
- General news, blogs, and third-party legal explainers may help discover topics, but the PPT should link the official statute, official SOP, judgment, or primary research source instead.

## 7. Implementation Documentation

### React Native

- PPT keyword: `React Native mobile application`
- Link: [React Native documentation](https://reactnative.dev/)
- Supports: Cross-platform mobile implementation context.
- Use in PPT: Technical approach slide.

### VisionCamera

- PPT keyword: `Camera capture`
- Link: [VisionCamera documentation](https://visioncamera.margelo.com/)
- Supports: Mobile camera preview, capture, and camera capability integration.
- Use in PPT: Technical approach and guided-capture slide.

### OpenCV

- PPT keyword: `OpenCV image quality`
- Link: [OpenCV documentation](https://docs.opencv.org/)
- Supports: Image-processing concepts for blur, glare, clipping, ROI, and color operations.
- Use in PPT: Technical approach slide.

### SQLite

- PPT keyword: `Offline-first SQLite`
- Link: [SQLite documentation](https://www.sqlite.org/docs.html)
- Supports: Local transactional storage and offline queue design.
- Use in PPT: Offline-first architecture slide.

## 8. Reference Video

- PPT keyword: `Reference video - legal framework`
- Link: [Pramaan - Digital Companion for Field Drug Testing, Team Trojans](https://youtu.be/wOZUXeezgX0)
- Observed topics from the supplied screenshots: legal framework for digital evidence, BNSS Section 105, NDPS Section 52A, BSA Section 63(4), hashes, certificates, audio-video recording, and proper documentation of search/seizure steps.
- Use in PPT: Research inspiration only; cite the official legal sources above for the actual claims.
- Note: The video page did not provide a machine-readable transcript in the research session, so exact spoken wording should be checked manually before quoting it.