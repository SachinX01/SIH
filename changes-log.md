# Praman Setu Change Log

> Running record of actions, decisions, corrections, and generated deliverables. Add a new entry whenever project work changes a file or establishes a decision.

## 2026-09-22

### Project context created

- Read `Praman_Setu_SIH26231_Final_Clean.docx` and extracted its solution details.
- Created the initial living project context with the SIH problem statement, proposed stack, prototype scope, screens, evidence model, demo constraints, future scope, corrections log, and decision log.

### Proposal audit

- Audited the proposal for internal contradictions before implementation.
- Logged C-001 through C-008 covering backend/sync scope, cryptography, roles, deletion and hash-chain behavior, Reference DB definition, device integrity, and verification contracts.

### Source-document issue audit

- Logged C-009 through C-015 covering duplicate numbering, missing numbered scope items, lost bullet formatting, incorrect PDF dependency, misplaced sync/review sections, stale future-scope entries, and missing supervisor status in History.

### Library and implementation audit

- Verified the role of `react-native-pdf` as a PDF viewer and identified `react-native-html-to-pdf` as the PDF-generation direction.
- Audited OpenCV, QR scanning, cryptography, PIN authentication, SQLite, camera controls, GPS, device time, React Native project mode, and permissions.
- Logged C-016 through C-025 for the resulting integration and architecture risks.

### Corrected proposal generated

- Created `Praman_Setu_SIH26231_Corrected.docx` as a separate file.
- Preserved `Praman_Setu_SIH26231_Final_Clean.docx` unchanged.
- Repaired scope numbering and native bullet lists.
- Moved Offline Sync and Supervisor Review before the judge-demo section.
- Replaced the PDF viewer dependency with the PDF-generation dependency.
- Removed stale future-scope mock entries.
- Added supervisor review status to History.
- Added prototype architecture boundaries, evidence contracts, GPS metadata rules, permission behavior, Reference DB requirements, and demo-safety constraints.
- Validated the corrected DOCX archive and XML structure.

### Complete project information

- Expanded the project context into a complete requirements reference covering the problem statement, implementation checklist, detailed screens, canonical data model, state machines, classification contract, demo runbook, delivery checklist, and remaining architecture decisions.
- Renamed `context.md` to `project-info.md`.
- Renamed the document title to Project Information and linked the requirements file to this running action log.
- Created `SIH26231.md` as the dedicated project-information source and reduced `project-info.md` to a workspace file index.
- Removed the chronological Change Log from `SIH26231.md`; chronological actions remain only in `changes-log.md`.
- Cleaned `SIH26231.md` into a final project specification by removing correction history, decision history, and open planning notes while preserving the complete solution details.
- Created `Praman_Setu_SIH26231_Presentation.pptx` with 11 editable slides covering the problem, solution, workflow, classification, evidence integrity, operations, architecture, demo safety, and impact; validated its slide count and core text markers.
- Presentation decision: the generated deck is a reference draft only; the user will create the final PPT, with assistance on content, structure, visuals, speaker notes, fact-checking, and rehearsal.
- Created `Praman_Setu_SIH26231_Reference_Style.pptx` as a separate six-slide deck matching the reference SIH structure: title, proposed solution, technical approach, feasibility and viability, impact and benefits, and research/references.
- Added eight embedded hyperlinks to official government, problem-statement, standards, and technical documentation sources; validated the deck successfully.
- Researched and added a categorized Research and Standards Alignment section to `SIH26231.md`, distinguishing Indian government context, forensic/drug-analysis guidance, digital-evidence references, and non-legal technical standards.
- Updated the reference deck links to current NCB and India Code destinations and added NIST forensic, OSAC seized-drugs, SWGDRUG, ISO/IEC 17025, and NIST signature references.
- The original reference-style PPTX was locked, so the research-updated deck was generated separately as `Praman_Setu_SIH26231_Reference_Style_Research.pptx` without overwriting the earlier deck.
- Validated the research-updated deck: 6 slides, 10 embedded hyperlinks, current NCB and India Code URLs, and NIST OSAC reference markers present.
- Reviewed the supplied reference-video screenshots and added legal-alignment checkpoints for BNSS Section 105, NDPS Act Section 52A, Bharatiya Sakshya Adhiniyam Section 63(4), and Yusuf @ Asif v. State, with explicit non-admissibility and non-certification boundaries.
- Created `Praman_Setu_SIH26231_Reference_Style_Legal.pptx` with the legal-alignment references and validated 6 slides plus 14 embedded legal/technical hyperlinks.
- Created `link.md` as the reusable project research library, covering Indian government and statutory sources, BNSS/NDPS/BSA checkpoints, forensic guidance, digital evidence, cryptography, privacy, security operations, implementation documentation, and the supplied reference video.
- Expanded `link.md` with additional relevant posts and research: BPR&D crime-scene audio-video SOP, BPR&D/NCRB criminal-law resources, NIST drug-safety research, NISTIR 8589 validation guidance, NIST process mapping, forensic quality assurance, NIST digital evidence, OSAC sampling guidance, and NFSU context.

## Running Log Format

Future entries should include:

- Date and time when useful.
- Current goal.
- Files or tools changed.
- Key result.
- Decisions or unresolved questions.
- Next step.