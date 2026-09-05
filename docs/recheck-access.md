# Access and prompt-coverage recheck

Reviewed on 5 September 2026. This independent pass compared all six answers and the mediation diagram with the supplied case and question requirements. It also retrieved the live application and current service documents again. The legal analysis received separate review; this pass focused on service evidence, accessibility and practical fit.

The Friday-staffing clarification has been applied to challenges 4 and 6, and challenge 4 now explicitly requires safe support for physical execution. A follow-up check found no material regression. The findings below describe why those changes were needed.

## Finding that warrants a short-answer change

Moyuri has only one known private speaking window: roughly twenty minutes on Friday. The detailed research correctly identifies the staffing gap, but the six short answers leave it behind general phrases such as "safely agreed times." Add an explicit requirement to arrange a staffed Friday appointment or another safely verified route in the mediation and telephone proposals. State that existing Friday coverage is unverified. Otherwise a reader could assume that the proposed safe verification is available during ordinary service hours.

This is a design dependency, not evidence that Friday helpline service is unavailable. The district charter states Sunday to Thursday, 9 a.m. to 5 p.m.; the helpline poster states 9 a.m. to 5 p.m. without specifying days. An appointment must still be safe on that particular day. The reported Friday interval is not permanent permission to call the household.

## Fresh source checks

| Source and method | What the check establishes | What it does not establish |
| --- | --- | --- |
| [Live online application](https://db.nlaso.gov.bd/Pages/OnlineApplications.aspx), web retrieval and fresh unauthenticated HTML GET | General Description is a textarea. Its adjacent label has no `for` attribute and the textarea has no explicit ARIA label in the retrieved markup. Applicant contact number is starred; applicant NID is unstarred, with no HTML `required` attribute on that input. Separate representative details exist. | Successful screen-reader operation, dynamic validation, server acceptance without NID, signature requirements or notification behaviour. |
| [District charter](https://objectstorage.ap-dcc-gazipur-1.oraclecloud15.com/n/axvjbnqprylg/b/V2Ministry/o/office-nlaso/2026/6/a84db22f-9b31-4abd-a32d-c01e51460d62.pdf), fresh download and visual inspection of page 11 | Office hours are Sunday to Thursday, 9 a.m. to 5 p.m. Applicant instruction 4 provides office-assistant help with form completion for people who cannot read. | An existing telephone filing service, permission for any entrepreneur to access a case, or Friday helpline coverage. |
| [Central charter](https://objectstorage.ap-dcc-gazipur-1.oraclecloud15.com/n/axvjbnqprylg/b/V2Ministry/o/office-nlaso/2026/6/bcfb1eb6-07c3-4a05-a4fe-63f2353914aa.pdf), fresh download and visual inspection of page 2 | 16699 accepts toll-free incoming calls for legal advice/information; the published service standard is immediate. Online advice appears separately. | A measured waiting-time guarantee, a common cross-channel draft or complete telephone application filing. |
| [Helpline page](https://dbla.gov.bd/pages/static-pages/69ca4e8234fc363bf320ca55) and its [original poster](https://objectstorage.ap-dcc-gazipur-1.oraclecloud15.com/n/axvjbnqprylg/b/V2Ministry/o/office-nlaso/2026/2/745cdf34-0ba8-4c9d-a0a0-0adb04f6e5db.jpeg), fresh retrieval and visual inspection | Current advertised number is 16699; the poster states 9 a.m. to 5 p.m. | Working days or around-the-clock coverage. |

The web tool could not open the two charter PDFs directly. The files were retrieved from the cited official URLs with an ordinary read-only download and rendered for visual inspection. No form was filled, no application was submitted, no call was made and no local office was visited.

## Coverage of the six prompts

| Answer | Required content checked | Result |
| --- | --- | --- |
| [1: citizen access](../questions/01-citizen-access/answer.md) | One amendment, section reference, legal change, operational effect and technology support | All present. The answer does not claim the amendment created the existing website or that a relative can consent for Moyuri. |
| [2: AI intake](../questions/02-ai-for-legal-aid/answer.md) | AI capabilities and prohibitions, workflow, urgent escalation, human ownership, third-party provenance and handover contents | All present. Risk and missing information remain distinct. Child danger is framed as reported or disclosed, rather than information the AI somehow already knows. |
| [3: priority](../questions/03-justice-operations/answer.md) | Exactly three factors, digital representation, comparison, human judgment and protection against unfair deprioritisation | All present. Access barriers can raise priority. First-contact ordering and ageing review are queue safeguards, not additional merit factors. |
| [4: mediation](../questions/04-odr-and-accountability/answer.md) | Entry, intake, mediation, lawful outcome, record and follow-up, stop condition and alternative, diagram explanation | All present. Short audio sessions and connection pauses address the case. Add explicit Friday staffing. A physical execution step must remain safely arranged; it cannot silently require Moyuri to travel alone to Joypurhat. |
| [5: restricted information](../questions/05-community-innovation/answer.md) | One data item, authorised roles, reasons, technical enforcement and an independent step for Ripon | All present. Telephone assistance removes the need for a sighted companion while retaining staff verification. Permission to request an update is distinct from approval or authority to view the note. |
| [6: omnichannel support](../questions/06-call-centre-and-omnichannel/answer.md) | One observed barrier, its effect, one improvement, preserved requirements, no citizen internet, no readable screen and no unsafe handset pushes | All present. The shared voice-to-form draft remains one improvement. Its current-service basis and proposed extension are distinguished. Add the Friday staffing dependency. |

## Consistency and practical limits

The answers consistently distinguish Moyuri, Ripon as reporter, and a legally authorised representative. They retain unknown facts and restrict notification channels. Neither caller ID, a spoken reference nor voice recognition is treated as proof of identity or permission. The telephone proposal relies on ordinary voice coverage and service staff, which is compatible with the condition that the citizen has no internet.

The [diagram](../questions/04-odr-and-accountability/process-diagram.md) matches the written mediation sequence. Its stop branch reaches a protected record and human follow-up; the explanation correctly says that stopping online participation does not itself waive a mandatory procedure or produce a valid failure report. A dropped connection is a pause, as specified in the answer, rather than immediate agreement or failure.

Before implementation, the proposed spoken verification process needs a concrete approved method, a safe fallback if it is forgotten or compromised, and testing with blind Bangla-speaking users. Union Digital Centre access also requires authorisation and privacy controls. These are identified implementation questions rather than claims that the current service already provides those functions. The submission does not need an invented identity shortcut to answer its design questions.

The current answers meet the required structure. The Friday staffing clarification is the substantive improvement identified by this pass; no other mandatory prompt component was found missing.
