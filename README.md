<img src="banner.png" alt="Healthcare software that never lies about its own state" width="100%">

Software engineer in Vienna with an M.Sc. in Medical Engineering and eHealth (FH Technikum Wien) and a TÜV AUSTRIA certificate as Quality & Regulatory Affairs Manager-Junior for medical devices (ISO/IEC 17024). Founding Engineer at FSHNiSTA. Case files for each project at [henrycarto.com](https://henrycarto.com).

One rule runs through all of it: a system should never lie about its own state. A missing value comes back absent, never as zero.

| Project | What it does | Stack |
|---|---|---|
| [Passayge](https://github.com/Henrycarto/passayge) | ELGA-style health data exchange sandbox on IHE FHIR profiles: e-card access windows, every access audited. 116 tests. Live at [passayge.vercel.app](https://passayge.vercel.app). | React, TypeScript, Node, HAPI FHIR |
| [wardkit](https://github.com/Henrycarto/wardkit) | Five FHIR R4 clinical UI components that refuse to show a missing value as zero. 148 tests. Live at [wardkit.vercel.app](https://wardkit.vercel.app). | React, TypeScript |
| [Chemsisy](https://github.com/Henrycarto/chemsisy) | Open-source molecule explorer for pharmacy and medical students: each functional group highlighted with a sourced note. 227 tests. Live at [chemsisy.vercel.app](https://chemsisy.vercel.app). | React, TypeScript, 3Dmol.js, RDKit |
| [hl7-fhir-gateway](https://github.com/Henrycarto/hl7-fhir-gateway) | HL7 v2 ADT and ORU over MLLP to FHIR R4 bundles. Idempotent on resends, ordered outbox with backoff and a dead-letter queue. 35 tests. | Java 21, Spring Boot 3, HAPI |
| [second-read](https://github.com/Henrycarto/second-read) | Medical image annotation with four-eyes review, a hash-chained audit trail and DICOM de-identification. 54 tests. | Django, DRF, pydicom |
| [pulse-fhir-gateway](https://github.com/Henrycarto/pulse-fhir-gateway) | A 200 Hz pulse stream to FHIR R4 Observations that reports gaps instead of inventing values. Passes the HL7 validator. | Python |
| [medtrace](https://github.com/Henrycarto/medtrace) | IEC 62304 traceability check that fails the build when a requirement has no code or no passing test. | Python |
| [medrag-eval](https://github.com/Henrycarto/medrag-eval) | Retrieval on PubMedQA measured with bootstrap confidence intervals. | Python |

Clinical UI suite, live: [ward-monitor.vercel.app](https://ward-monitor.vercel.app)

[henrycarto.com](https://henrycarto.com) · [LinkedIn](https://www.linkedin.com/in/henrymba) · henrymailing@yahoo.com
