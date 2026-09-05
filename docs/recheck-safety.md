# Independent review of AI intake, priority and access

Review date: 5 September 2026. Scope: the questions, case study, answers and supporting research for challenges 2, 3 and 5. The findings describe the version examined before this review's corrections. This review checks the proposals against their own requirements and examines failure cases; it does not certify a deployed system.

All three corrections below have been applied. The revised answers and research notes received a follow-up check, with no material regression found.

## Findings requiring attention

### Challenge 2: a remaining assumption in the research notes

The short answer correctly limits the AI to information disclosed during intake. However, step 5 of the research workflow lists "a child in the household" as a reason for transfer without qualification. Ripon's quoted opening does not disclose a child. The broader case study cannot silently become information available to the AI.

Replace that wording with "any child risk disclosed". The reported violence and deprivation already warrant prompt human review. Preserve the source of each claim, and distinguish Ripon's report from Moyuri's own instructions.

### Challenge 3: make the proposed bands reproducible

The answer uses exactly three substantive factors and separates urgency from evidence confidence. Its comparison mechanism would be stronger if the research supplied an actual decision table, rather than only naming possible bands.

A defensible proposed table is:

| Condition, assessed using the three factors | Suggested handling |
| --- | --- |
| Serious reported danger from delay | Immediate human review before ordinary intake finishes. |
| A legal deadline or need for prompt relief, or a concrete access barrier that makes ordinary delay more harmful | Prompt review, with the reason and time consequence shown. |
| No urgent condition identified after an adequate human assessment | Routine review, retaining first-contact order among comparable files. |
| Important facts remain unknown | Assisted review to resolve the uncertainty; missing information cannot itself justify a lower band. |

The last row is a review safeguard, not a fourth merit factor. These are proposed rules for local approval, not statutory time limits. The DLAO must be able to change the suggested band with reasons. A reported immediate threat must not be cancelled by weak documentary evidence or uncertain prospects of litigation.

### Challenge 5: pause an unsafe channel before approving a replacement

The answer properly withholds approval of a new contact arrangement until it can be verified. A separate failure case needs explicit treatment: Ripon might report that a previously safe contact window has become unsafe. If that report stays "pending" while the old contact plan remains active, staff could expose Moyuri's attempt to seek help.

Suggested addition: "Pause a channel reported unsafe pending review; an unverified update cannot authorise new contact."

This preserves the distinction between stopping a potentially dangerous communication and granting a proxy authority to arrange a new one. The telephone read-back should also occur only when Ripon can speak safely, because the timing note itself is protected information. Neither caller ID nor a familiar voice is adequate proof of identity or permission.

## Checks that passed

- Challenge 2 provides an AI disclosure, an offer of a person, attributed third-party information, urgent triggers, an accepted human handover and a failed-transfer route. It does not authorise AI decisions about credibility, consent, eligibility or mediation suitability.
- The research explicitly says urgent safeguarding must not wait for a direct survivor call or completed identity verification. That does not give the AI authority to notify police, the husband or the household automatically.
- Challenge 3 contains three factors. First-contact order, waiting-file review and reconsideration are procedural safeguards rather than hidden assessments of legal merit. Disability and incomplete documents are not credibility penalties.
- Challenge 5 selects one information item and explains who needs it. An assigned lawyer's access remains conditional on a need to contact Moyuri; assignment alone does not grant access to every private communication. A mediator receives arranged appointments without the underlying timing note.
- Access checks apply on the server and extend to exports and search results. Encryption, logging without duplicating the sensitive note, and revocation supplement those checks. The research addresses administrators and exceptional access rather than assuming that a hidden field is protected.
- Ripon's proposed telephone step requires no sighted companion, separate recording app or visual OTP. Staff assistance does not contradict the question's requirement that he complete his part without a sighted person beside him.

## Fresh primary-source check

The [ICT Division publication page](https://ictd.gov.bd/pages/laws/ব্যক্তিগত-উপাত্ত-সুরক্ষা-আইন-২০২৬-70is1t-69df5ba2210b1799cc640412) was reopened and its official download was retrieved. The Bengali [Personal Data Protection Act, 2026 gazette](https://objectstorage.ap-dcc-gazipur-1.oraclecloud15.com/n/axvjbnqprylg/b/V2Ministry/o/office-ictd/2026/3/1c355c6a-cc9c-42a0-b07f-e0876b89dc9d.pdf), PDF pages 15-16, was rendered and visually reread.

Section 16 limits disclosure for purposes other than those for which the information was collected without the person's consent, subject to the Act's other provisions. Section 17 addresses technical and organisational protection against unauthorised access or disclosure and expressly includes encryption. The short answer's reference to purpose and security principles is supported. The statute does not prescribe the proposed DLAS role matrix or make encryption sufficient on its own.

## Verification limits

The web PDF viewer failed, but a direct download of the same official link succeeded. This review did not inspect DBLA's internal permissions, place a helpline call, test a blind user's device or verify a working proxy-authentication procedure. Those remain deployment checks. The fresh legal check covered the cited sections 16-17; it was not a search for every later rule, exemption or instrument affecting the Act.
