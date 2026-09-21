# CADSS trademark and results policy

Version 0.2 (draft, 21 September 2026; 0.1 superseded: item 4.6 reworded). Owner: AIChildSafety.org.

## 1. What this policy covers

The names **CADSS**, **Childhood AI Developmental Safety Suite**, **EMST**, **Emotional Manipulation Stress Test**, **ASHA**, **CORB**, **EIA**, **IWA** and **CPQ**, and any logos we publish for them (the "Marks"), identify evaluation instruments developed by the Childhood and AI Lab at AIChildSafety.org. This policy says how the Marks may be used. It does not change the licences on the code or the content.

## 2. What the licences give you, and what they do not

- The code is licensed under Apache-2.0. The content packs and grading materials are licensed under CC BY 4.0.
- Those licences let you use, study, modify and redistribute the code and content for any purpose, including commercial use, subject only to their attribution and notice terms.
- Neither licence grants rights in the Marks (Apache-2.0 §6; CC BY 4.0 §2(b)(2)). Use of the Marks is governed by this policy alone.

## 3. Uses that need no permission

- Referring to the instruments by name to say what they are, to cite them, to compare with them, or to say that your work uses, extends or is derived from them ("built on EMST", "derived from the CADSS harness", "EMST-compatible pack").
- Redistributing unmodified releases with the Marks and notices intact.
- Running a released instrument as released and reporting the output as an **EMST result** (or ASHA result, etc.) when the conditions in section 4 are met.
- Academic, journalistic and educational use.

## 4. Conditions for reporting results under a Mark

A result may be described as an EMST result, an EMST profile, or a result of any CADSS instrument only if all of the following hold. The purpose is that a number carrying the name was produced the way the instrument specifies, so that readers can compare it with other numbers carrying the same name.

1. **Released content, unmodified.** The pack is a released version and its content hash matches the release. Draft lines, added lines and edited lines disqualify the run; a private held-back set supplied by the Lab for contamination control counts as released.
2. **Released protocol.** The run followed the released protocol for that instrument: the specified conditions (for EMST, bare and child-safety system-prompt), continuity modes, number of repeats, and delivery settings, and the run manifest and comparability class are published with the result.
3. **Conforming harness.** The run used a released harness version, or another harness that passes the instrument's published conformance test suite.
4. **Grading as specified.** Grades were produced by graders certified under the instrument's certification procedure (human, or an AI grader certified under section 5.5 of the EMST design), with the double-grading share the instrument requires, and the full reliability panel (base rate per level, percent agreement, Krippendorff's α with its interval, Gwet's AC1, disagreement counts) is published for every cell.
5. **Reliability gate applied.** Cells that do not pass the instrument's reliability gate are withheld and the reliability finding is published in their place. Publishing a withheld cell with a caveat is not permitted under the Mark.
6. **Statement of what the instrument does not measure, and profile.** Every table carries the instrument's construct scope statement: it measures system conduct, at the level of mechanisms and harms, and no outcome in any person. No composite score, ranking or grade is derived from the profile and presented under the Mark.
7. **Contamination signals reported.** Canary status, public-versus-private comparison and the evaluation-awareness rate are reported where the protocol calls for them.
8. **Grader provenance.** Each published figure states whether it was produced by human or AI graders.

If any condition is not met, you may still publish your work and say that it was produced with, derived from or inspired by the instrument, but you may not call the numbers an EMST result or use a Mark as the name of your result, your method or your product.

## 5. Modified versions and derived instruments

- A modified pack, a modified rubric, a modified harness that fails the conformance suite, or an instrument built from these materials must be given its own name. It may say that it is derived from or based on the relevant CADSS instrument.
- Names must not be confusingly similar to the Marks ("EMST-Lite", "EMST 2", "OpenEMST", "CADSS-X" are not permitted).
- Nothing may state or imply that AIChildSafety.org or the Childhood and AI Lab endorses, certifies or is affiliated with a modified version or its results.

## 6. Locale packs

A pack for another language or region that is authored under the instrument's parallel-authorship and crosswalk protocol with the Lab, and whose functional-equivalence check has been published, may be released as an authorized locale pack and designated with the Mark and a locale tag (for example, EMST es-CL). Any other translation or adaptation is a derived pack under section 5.

## 7. Uses that are not permitted

- Using a Mark as the name, or part of the name, of your product, service, company, dataset, benchmark or domain name.
- Using a Mark on results that do not meet section 4, or on results obtained with modified content.
- Using a Mark or logo in a way that implies endorsement, certification, partnership or affiliation that does not exist.
- Altering the logos.

## 8. Registration status and enforcement

The Marks are claimed as trademarks and service marks of AIChildSafety.org. Registration is [pending / not yet filed]. Until registration, the Marks carry the ™ symbol. AIChildSafety.org may ask you to correct a use that does not follow this policy; we will do so first by writing to you.

## 9. Questions and changes

Questions about this policy, requests for permission for a use not covered here, and requests to be listed as an authorized locale pack: [contact address]. This policy may change; the version in the repository's main branch is current, and earlier versions remain available in its history. Changes do not affect results that were properly reported under the version in force when they were published.

*This policy is modelled on the trademark policies of the Mozilla Foundation, the Python Software Foundation and the Rust Foundation, and on the results-reporting rules of MLCommons (MLPerf).*
