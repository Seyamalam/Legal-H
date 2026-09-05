# Research notes: AI voice intake

Research checked on 5 September 2026. The workflow below is a design proposal for the future system in the question. It is not a claim that the national helpline already uses AI.

## What the evidence establishes

The Legal Aid Services Act, 2000, in the official consolidated copy dated 4 May 2026, includes legal information and advice for any applicant in section 2(b)(আ). Section 7(1)(গ) provides for emergency legal support where applicable; section 7(1)(ঝ) addresses referrals, including shelter and mental health support; section 7(1)(ণ) addresses digital access and database protection. These provisions support a human legal aid service with referral capacity. They do not establish an AI's authority to determine legal rights, consent, eligibility or urgency. [S1](sources.md#s1-current-legal-aid-act)

UNDP's April 2026 announcement identifies the Directorate of Bangladesh Legal Aid, ADLASB and the national legal aid helpline 16699. It does not verify automated intake, round-the-clock staffing, emergency dispatch, or voice-based authentication. [S2](sources.md#s2-current-service-context)

WHO recommends private consultation, confidentiality with its limits explained, supportive listening and respect for the woman's decisions. This is health-sector guidance, applied here by analogy to safe intake rather than presented as Bangladesh law. [S3](sources.md#s3-who-first-line-support)

The UN essential-services guidance covers legal aid within justice services. It supports accessible initial contact, accurate records, survivor safety and informed consent for disclosure where possible. Its risk-assessment guidance considers repeated or escalating violence, harm, threats and weapons, and seeks the survivor's own perspective. [S4](sources.md#s4-un-essential-services-package)

NIST identifies confidently false outputs, privacy risks, unequal performance across languages, and excessive reliance on AI. It recommends checking generated citations and recording human overrides. Its voluntary US framework is useful design guidance, not a Bangladesh legal requirement. [S5](sources.md#s5-nist-generative-ai-profile)

## The decisive distinction: report, permission and representation

Ripon can report a concern. His relationship to Moyuri does not itself establish that she authorized a legal application, litigation, disclosure to others, mediation, or future communication. Record each permission separately. His consent to record his own call cannot establish Moyuri's consent to processing or sharing her information. The service needs an approved legal basis and staff protocol for necessary third-party safeguarding records.

Label the intake as "Ripon's account; Moyuri not yet consulted". Preserve which details he witnessed, which he heard from her, and which he cannot explain. A transcript checked by Ripon confirms what he said; it does not verify that events occurred or that Moyuri agrees with his interpretation. The system must never convert "my sister said" into a statement supposedly made directly by Moyuri.

Blindness does not imply that Ripon lacks decision-making capacity. Inability to read an OTP or form is an access requirement. Nor does Moyuri's isolation establish that she cannot make her own choices. A trained officer must safely establish her wishes and assess any lawful proxy authority required for the particular next step.

## Proposed workflow

1. Identify the service as an AI assistant in spoken Bangla. Offer a person immediately, without requiring a menu, captcha, NID or OTP. Ask whether Ripon can speak safely and whether anyone is in immediate danger. Keep the first questions short.
2. If danger is reported, interrupt routine intake and connect a trained human. Otherwise, explain the limited purpose of intake and ask only for information needed to route help. Do not collect a complete family history before offering assistance.
3. Capture the account in Bangla. Ask one question at a time, accept approximate dates, and allow "unknown". Read back important details for correction. If speech recognition repeatedly fails, hand over to a person rather than treating silence or a low-confidence transcript as a negative answer.
4. Record the safe-contact restrictions separately from the allegations. Treat Friday's twenty-minute window as information supplied in the case, not permanent permission for a callback. The human must confirm the number, time, recipient and acceptable content before initiating contact. Until then, suppress outgoing SMS, notifications, voice messages and household callbacks. A supposedly neutral message can still reveal contact with a legal service.
5. Transfer this case to a legal aid officer during the interaction if one is available. Reported violence and deprivation justify prompt human review even without proof of an emergency. Add any child risk disclosed; Moyuri's instructions remain unverified. The AI can arrange a safe follow-up only under an approved protocol; it cannot promise a response time unsupported by staffing.
6. The human reviews risk, consent and representation; seeks a private conversation with Moyuri when safe; identifies legal options; and coordinates any necessary referral. Legal filing, contact with the alleged abuser and mediation require that human assessment. Intake should not trigger an automated notice to Sohel.

## Urgent-review triggers

Proposed triggers include an assault in progress, serious injury, threats to kill, strangulation, weapons, rapidly worsening violence, immediate danger to the child, urgent food or shelter needs, or a credible risk that the call itself will be discovered. WHO's handbook includes several serious-violence indicators, but its clinical job aid is not a validated Bangla proxy-call scoring instrument. Do not copy a numerical cutoff or wait for a minimum number of indicators before escalation. [S6](sources.md#s6-who-immediate-risk-guidance)

An unknown answer is not reassurance. If Ripon cannot establish whether Moyuri is currently safe, show "current safety unknown" to the human alongside the reported abuse. Routine intake must not postpone a necessary safety response until Moyuri's identity or permission can be obtained. Equally, a family member's allegation must not cause automatic police reporting, public disclosure or confrontation. Staff must assess necessity, safety, applicable duties and the minimum information needed under the approved emergency protocol.

## Minimum handover record

| Field | Record for this case |
| --- | --- |
| People and provenance | Ripon, relationship claimed, access needs; Moyuri, Sohel and child only as needed; source of each allegation |
| Allegations and time | Reported assaults, five months without financial support, dowry-related motorcycle demand if disclosed; approximate dates and what remains unknown |
| Immediate concern | Last known incident, injuries or threats if known, child risk, present location only where needed for a safe response |
| Contact restrictions | Shared and monitored phones, forbidden outgoing channels, provisional Friday window, safe recipient and channel still to be confirmed |
| Consent and authority | Ripon's permissions, whether he says Moyuri requested help, Moyuri's consent unverified, authority for later steps unresolved |
| Identity gaps | NID unavailable, not "invalid applicant"; identifying details already supplied and safe verification still needed |
| System and ownership | Intake time, spoken corrections, uncertain transcription, trigger reason, assigned human, acceptance of handover, next safe action |

## Boundaries and practical checks

The AI may explain the service, ask approved questions, transcribe, read back, translate cautiously, summarize and flag reasons for review. It must not decide credibility, infer guilt, predict success, give tailored legal strategy, certify consent, impersonate a lawyer or promise protection. Do not use tone, accent, fluency or emotion to score truthfulness.

Restrict access to case details by staff role; log access and disclosures; set retention rules; and keep records out of public repositories and model-training datasets. Audio is particularly identifying. Store it only when necessary under an approved lawful process, with a clear explanation; a corrected text record may be sufficient for intake. These are proposed operational controls requiring local approval.

Before deployment, test misheard negation, Bangla regional speech, interruptions, repeated questions, disconnected calls and failed transfers with local users, including blind callers. A human handover counts as complete when a named staff member accepts it. A dashboard flag without an owner is not an intervention.

Open questions include staffing and response times, current NID and proxy procedures, recording and retention rules, emergency disclosure duties, and the effect of current mediation rules and commencement notifications on the particular claim. The AI should route these questions to a lawyer, not invent an exemption or promise that refusal of mediation has no legal consequences.

The [protection-law status review](../../docs/domestic-violence-law-status.md) identifies broad standing to apply on another person's behalf under section 11 of the verified 2010 text. The AI should not say that every urgent protective step must wait for a direct survivor call. A human assesses that route, current law and emergency disclosure duties. Standing to apply remains distinct from authority to settle or consent to mediation.
