> **A free bonus online-only guide for *ChatGPT Visual Bible*, not included in the print edition**

![Profession-Specific Prompts](Bonus-Chapter-Profession-Specific-Prompts-hero.png)

- [Introduction](#introduction)
- [Legal](#legal)
- [Healthcare](#healthcare)
- [Marketing](#marketing)
- [Sales](#sales)
- [Education](#education)
- [Finance and accounting](#finance-and-accounting)
- [HR and recruiting](#hr-and-recruiting)
- [Journalism and media](#journalism-and-media)
- [Real estate](#real-estate)
- [Government and public sector](#government-and-public-sector)

# Introduction

In *ChatGPT Visual Bible*, *Book 1* to *Book 4* taught you how to write a good prompt for almost any task. This guide adds a layer that general prompting skill does not cover: the specific duties, risks, and rules that come with your profession.

A lawyer, a nurse, a teacher, and a real estate agent can all ask ChatGPT to draft a letter. Only one of them needs to worry about attorney-client privilege before doing it. This guide walks through ten professions where using AI carries a duty or risk beyond the general advice throughout *ChatGPT Visual Bible*, along with adaptable prompts for each.

Treat every prompt here as a starting point, not a finished product. Nothing in this guide replaces the judgment of your compliance team, your legal counsel, or your professional licensing body. Rules change by state, country, and employer, so confirm current requirements before you rely on any of them.

> **Special considerations for regulated and client-facing professions**: Some professions carry a duty that changes how you should use an AI assistant: a duty of confidentiality, a duty to avoid discrimination, a duty to disclose, or a duty to verify before anything reaches a client or the public. This chapter covers ten such professions. Each section names the specific risk, gives one habit that reduces it, one mistake to avoid, and several prompts you can adapt to your own work.

# Legal

Attorneys hold a duty of confidentiality that covers almost everything a client tells them, and a duty of competence that now extends to understanding the tools they use. The American Bar Association's Formal Opinion 512, issued in July 2024, states that lawyers using generative AI must understand its capabilities and limitations under Model Rule 1.1 and must protect client information under Model Rule 1.6, regardless of which AI tool touches that information. More than a dozen state bars have since issued their own opinions on the same questions.

In the United Kingdom, the Solicitors Regulation Authority (SRA) has not written AI-specific rules, because it considers the existing SRA Standards and Regulations sufficient: the duty of confidentiality and the duty of competence already cover how a solicitor uses any tool, including AI. Sending client information to a general AI tool without checking its terms can itself breach confidentiality, and using an open, public AI tool for legal research can waive legal professional privilege. In June 2025, the Divisional Court warned that AI tools are not reliable for legal research on their own and that a solicitor who files unverified, AI-generated case citations risks contempt of court.

If you are outside the US and UK, ask:
```
What confidentiality and legal professional privilege rules apply to a lawyer using AI tools in [your country]?
```

> **Watch out:** Never paste client names, case facts, or privileged communications into a consumer AI account unless your firm has confirmed that the account meets its confidentiality and data-retention requirements. A general-purpose free account is rarely the right place for this.

> **Good practice:** Use AI to draft, summarize, and organize using anonymized or hypothetical facts, then add real client details yourself once the draft is ready for your own systems.

**Prompts to adapt:**
- `Summarize the key deadlines and obligations in [this contract, with names and figures replaced by placeholders], and flag anything unusual for a [type of agreement].`
- `Draft an outline for a client letter explaining [a legal concept] in plain language, without referencing any specific case facts.`
- `List the standard elements of a [type of motion or filing] in [jurisdiction], so I can confirm my draft includes everything required.`
- `Rewrite this paragraph from a contract to use clearer, plainer language, without changing its legal meaning.`

# Healthcare

Healthcare professionals work under the Health Insurance Portability and Accountability Act (HIPAA), which protects patient health information from being shared with anyone or anything that has not agreed to protect it the same way. The US Department of Health and Human Services' Office for Civil Rights has made clear that HIPAA's technical safeguards apply to any AI system that touches protected health information, and that a vendor's own security claims do not remove your organization's responsibility to verify them.

In the United Kingdom, NHS England's own guidance tells staff not to enter personal, confidential, or business-sensitive data into public generative AI tools such as ChatGPT, under the UK General Data Protection Regulation (UK GDPR) and the wider duty of patient confidentiality. Reusing patient data for training or research purposes generally requires either removing identifying details or, where that is not possible, a formal application to the Health Research Authority's Confidentiality Advisory Group.

If you are outside the US and UK, ask:
```
What patient data protection and confidentiality rules apply to healthcare staff using AI tools in [your country]?
```

> **Watch out:** A consumer AI account is not a HIPAA-covered tool unless your organization has a signed business associate agreement with the provider. Typing a real patient's name, diagnosis, or chart notes into a general AI chat is a data breach, not a shortcut.

> **Good practice:** Draft with placeholders (a fictional patient, a general condition, a rounded age) and only add real identifying details afterward, inside your organization's approved systems.

**Prompts to adapt:**
- `Draft a plain-language explanation of [a diagnosis or condition] that a patient with no medical background could understand.`
- `Write a template for a discharge instruction sheet for [a condition or procedure], with placeholders for medication names and follow-up dates.`
- `Summarize the general symptoms and standard treatment options for [a condition], citing that this is general information and not a diagnosis.`
- `Suggest three ways to phrase a difficult conversation about [a general topic, such as a treatment delay], without referencing a specific patient.`

# Marketing

Marketers who use AI to help write or generate content face a two-part disclosure rule. As of 2026, the Federal Trade Commission generally expects separate disclosures for sponsorship and for AI involvement. A label that says a post is sponsored does not also cover AI involvement, and a label that says content is AI-generated does not also cover a paid relationship. Both statements must appear when both apply.

In the United Kingdom, there is no blanket legal requirement to label an ad as AI-generated. Instead, the Advertising Standards Authority and its Committee of Advertising Practice apply the existing CAP Code: the question is whether an audience would be misled by not knowing AI was involved, not whether AI was used at all. From June 2026, CAP guidance specifically addresses AI-generated deepfakes, synthetic endorsements, and misleading product depictions as breaches of existing rules, whether or not an advertiser separately discloses AI use.

If you are outside the US and UK, ask:
```
What advertising and AI-disclosure rules apply to marketers using AI-generated content in [your country]?
```

> **Watch out:** Do not treat a single disclosure, such as "#ad," as covering AI involvement too. If a post is both sponsored and AI-assisted, disclose both facts as separate, visible statements.

> **Good practice:** Keep a short internal note on which parts of a campaign used AI assistance (a draft, an image, a voiceover) so your disclosure is accurate rather than guessed at after the fact.

**Prompts to adapt:**

- `Draft three subject-line options for an email campaign about [product or offer], each under 50 characters.`
- `Compare the tone and structure of these two ad drafts for [audience], and suggest which fits a [formal/casual] brand voice better.`
- `Suggest five angles for a social post about [topic], written for an audience that already knows the product.`
- `Rewrite this product description to lead with the customer benefit rather than the feature list: [paste description].`

# Sales

Sales professionals face a narrower but still real risk: overstating what a product or service can do. Claims made in a sales conversation, proposal, or follow-up email can create a binding representation, and general consumer-protection law treats a false or misleading claim about a product the same whether a human or an AI assistant wrote the words.

In the United Kingdom, the Consumer Protection from Unfair Trading Regulations 2008, carried forward under the Digital Markets, Competition and Consumers Act 2024, ban misleading actions and misleading omissions in any commercial practice, regardless of whether AI helped write the pitch. A buyer misled into a purchase can generally unwind the contract and claim a full refund within 90 days, so an AI-invented feature or guarantee is not a drafting slip your organization can shrug off.

If you are outside the US and UK, ask:
```
What consumer protection or misleading-advertising rules apply to sales claims made with AI help in [your country]?
```

> **Watch out:** Do not let AI invent a feature, guarantee, or delivery date your product does not actually have. Review every generated claim against your product's real specifications before it reaches a prospect.

> **Good practice:** Give the AI your actual product facts and pricing as part of the prompt, so it works from what is true rather than filling gaps with a plausible-sounding guess.

**Prompts to adapt:**
- `Using these facts about [the product: list specifications, pricing, and limits], draft a follow-up email after a sales call with [prospect's role or industry].`
- `Compare our offer against a competitor's based on these facts only: [list facts], and highlight where we are genuinely stronger.`
- `Draft three responses to the objection "[a common objection]," based only on our actual pricing and features.`
- `Summarize this call transcript into next steps and open questions: [paste transcript].`

# Education

Teachers carry a duty to protect student privacy under the Family Educational Rights and Privacy Act (FERPA), and a separate duty to model honest, disclosed use of AI for the students they teach. Both duties apply whether the AI use is for lesson planning or for grading student work.

In the United Kingdom, the Department for Education expects schools to complete a Data Protection Impact Assessment under the UK GDPR before adopting any AI tool, and its guidance is explicit that student data should never go into an open, public AI platform. Schools are expected to adopt a written AI use policy and to be transparent with parents and students about how and where AI is used with their data.

If you are outside the US and UK, ask:
```
What student data protection rules apply to teachers using AI tools with school data in [your country]?
```

> **Watch out:** Free consumer AI accounts are generally not appropriate for uploading identifiable student work, grades, or behavior notes. Check whether your school or district has an approved, FERPA-compliant AI tool before using student data with any assistant.

> **Good practice:** Use AI freely for your own planning work (lesson ideas, rubrics, practice questions) where no student data is involved, and be explicit with students about when and how you used AI in materials you give them.

**Prompts to adapt:**
- `Plan a 45-minute lesson on [topic] for [grade level], including one hands-on activity and two check-for-understanding questions.`
- `Write five practice questions on [topic] at three difficulty levels, with an answer key.`
- `Draft a rubric for a [type of assignment] that scores [specific skills], with three performance levels for each.`
- `Suggest three ways to explain [a difficult concept] to students who struggled with the first explanation.`

# Finance and accounting

Financial professionals often hold a fiduciary duty, a legal obligation to act in a client's best interest rather than their own. The Securities and Exchange Commission and FINRA have both made clear that using AI to draft communications or analysis does not reduce a firm's existing supervisory, recordkeeping, and fair-dealing obligations. Client financial data also carries its own confidentiality expectations, separate from the advice itself.

In the United Kingdom, the Financial Conduct Authority (FCA) regulates AI use through its existing, technology-neutral rules rather than AI-specific ones, chiefly the Consumer Duty and the Senior Managers and Certification Regime. A firm must be able to show that any AI-assisted customer interaction, from a chatbot answering a pension question to an AI-drafted suitability letter, still delivers the good outcomes Consumer Duty requires, and a named senior manager remains accountable for harm the AI causes.

If you are outside the US and UK, ask:
```
What financial regulator rules apply to using AI in client-facing financial advice in [your country]?
```

> **Watch out:** Do not paste a real client's account numbers, balances, or portfolio details into a consumer AI account. Firms remain responsible for supervising and retaining anything AI helps produce, so check your firm's policy before using AI for client-facing work.

> **Good practice:** Use rounded, hypothetical figures when drafting explanations or templates, and only substitute real client numbers inside your firm's approved, supervised systems.

**Prompts to adapt:**
- `Explain [a financial concept, such as a Roth conversion] in plain language for a client with no finance background.`
- `Draft a template email summarizing quarterly performance for a hypothetical portfolio with a [percentage] return, with placeholders for real figures.`
- `List the standard disclosures typically required when discussing [a type of financial product], so I can confirm my draft is complete.`
- `Summarize this general market trend in two paragraphs suitable for a client newsletter: [paste public article or data].`

# HR and recruiting

Recruiters and HR professionals sit close to employment discrimination law, including Title VII, the Americans with Disabilities Act, and the Age Discrimination in Employment Act. The Equal Employment Opportunity Commission has made clear that using an AI tool in hiring does not shift responsibility for a discriminatory outcome away from the employer, even when a vendor built the tool. Some states and cities, including New York City's Local Law 144, add their own audit and disclosure requirements for automated hiring tools.

In the United Kingdom, the Equality Act 2010 prohibits both direct and indirect discrimination in recruitment across nine protected characteristics, and it applies to a decision made or supported by AI just as it applies to a human interviewer. In March 2026, the Information Commissioner's Office (ICO) published a report and draft guidance on automated decision-making in recruitment, finding that many employers who believed their AI tool was only supporting a human decision were, in practice, letting it make the decision outright.

If you are outside the US and UK, ask:
```
What employment discrimination rules apply to using AI in hiring decisions in [your country]?
```

> **Watch out:** Do not use AI to screen, score, or rank real candidates without confirming your organization has tested the process for adverse impact across protected groups. "The AI did it" is not a defense.

> **Good practice:** Use AI to draft job postings, interview questions, and structured feedback templates, which keep a human making every decision about an individual candidate.

**Prompts to adapt:**
- `Write a job posting for [role] that focuses on required skills and avoids language that could discourage any protected group from applying.`
- `Draft five structured interview questions for [role] that ask every candidate the same thing.`
- `Create a feedback template for interviewers to fill in after speaking with a candidate for [role], focused on job-related criteria.`
- `Summarize this policy document into a plain-language FAQ for new employees: [paste policy].`

# Journalism and media

Journalists carry a duty to verify facts and disclose their methods, both of which are directly challenged by generative AI. A fabricated quote, an invented statistic, or an unverified claim from an AI assistant becomes a much bigger problem once it appears under a byline. Newsrooms are still building formal AI policies industry-wide, but the underlying duties of sourcing, accuracy, and disclosure have not changed.

In the United Kingdom, the Independent Press Standards Organisation (IPSO) holds publishers to the Editors' Code of Practice regardless of how a story was produced. Clause 1 of the Code requires care not to publish inaccurate, misleading, or distorted material, and responsibility for anything an AI tool gets wrong still rests with the publisher, not the tool. Ofcom has separately been examining AI content labeling for broadcast material, though the UK does not yet impose a statutory AI-labeling requirement.

If you are outside the US and UK, ask:
```
What accuracy and disclosure standards apply to journalists using AI tools in [your country]?
```

> **Watch out:** Never publish a quote, statistic, or citation produced by AI without verifying it against a real, checkable source. AI assistants can produce confident, detailed, and entirely invented details.

> **Good practice:** Use AI for structure, summarization, and first-draft organization, and disclose to your editor and, where your outlet requires it, to readers, which parts of a piece involved AI assistance.

**Prompts to adapt:**
- `Summarize this transcript into a list of the five most newsworthy quotes, with timestamps: [paste transcript].`
- `Suggest three possible headlines for this draft that accurately reflect its content, without exaggerating the claim: [paste draft].`
- `Draft an outline for a story on [topic], listing the sources I still need to verify each claim.`
- `Rewrite this paragraph for a general audience, keeping every fact and figure exactly as stated: [paste paragraph].`

# Real estate

Real estate professionals work under the Fair Housing Act, which bans discrimination based on race, color, religion, sex, national origin, familial status, or disability in housing sales, rentals, and advertising. The US Department of Housing and Urban Development has issued guidance warning that AI-generated advertising and algorithmic tenant screening can violate the Fair Housing Act even without any intent to discriminate, through how an ad is worded or targeted alone.

In the United Kingdom, there is no direct equivalent to the Fair Housing Act, but the Equality Act 2010 covers housing and property services under the same nine protected characteristics that apply to employment: age, disability, gender reassignment, marriage and civil partnership, pregnancy and maternity, race, religion or belief, sex, and sexual orientation. An AI-generated listing or ad that indirectly targets or excludes people with one of these characteristics can breach the Act even without any intention to discriminate.

If you are outside the US and UK, ask:
```
What housing or property discrimination rules apply to AI-generated advertising in [your country]?
```

> **Watch out:** Review every AI-generated property description or ad for language that could describe or target a type of buyer or tenant rather than the property itself, such as references to a neighborhood's demographics or a preferred type of family.

> **Good practice:** Ask AI to describe the property, not the ideal buyer, and review the output against your board's fair housing guidelines before publishing.

**Prompts to adapt:**
- `Write a property listing description for [property details: beds, baths, square footage, features] that focuses only on the property itself.`
- `Suggest three subject lines for a listing email about [property], based only on its features and price.`
- `Draft a neutral, factual response to a buyer's question about [a neighborhood amenity, such as schools or transit], without commenting on who lives there.`
- `Summarize these inspection notes into a plain-language list for a buyer: [paste notes].`

# Government and public sector

Public-sector employees produce records that are often subject to public disclosure laws, such as the Freedom of Information Act at the federal level or an equivalent state open-records law. Any AI-assisted draft, note, or analysis created as part of official business can become a public record, and government agencies are increasingly expected to keep AI use explainable and auditable rather than hidden inside an unreviewed tool.

In the United Kingdom, the Cabinet Office's Central Digital and Data Office publishes a Generative AI Framework setting out principles for safe use of AI across government and the wider public sector. Records of that AI use are not automatically private: a Freedom of Information Act 2000 request in 2025 successfully obtained records of a government minister's interactions with ChatGPT, establishing that AI prompts and outputs created in the course of official business can be disclosable public records, just as an email or a paper memo would be.

If you are outside the US and UK, ask:
```
What public records or freedom of information rules apply to government staff using AI tools in [your country]?
```

> **Watch out:** Do not use a consumer AI account for drafting anything that states or implies official agency policy, legal position, or a decision about a specific person's benefits or case, without review and approval through your normal process.

> **Good practice:** Keep a record of when and how you used AI to help draft public-facing material, the same way you would document any other drafting tool, in case the record is requested later.

**Prompts to adapt:**
- `Draft a plain-language summary of [a public policy or program] for a general audience, based only on this official source text: [paste text].`
- `Suggest a structure for a public meeting agenda covering these topics: [list topics].`
- `Rewrite this internal memo into a public-facing FAQ, keeping every fact unchanged: [paste memo].`
- `List the standard sections typically included in a [type of public report], so I can check my draft is complete.`

---

> **Try it now:** Pick the profession above closest to your own work, or the one you interact with most. Adapt one prompt to a real, non-confidential task you have this week, using placeholders for any real names or figures. Review the result the way you would review a colleague's first draft, not a finished document.

> **Check the result**
> - [ ] Did you replace every placeholder with real information only after reviewing the draft?
> - [ ] Did you avoid entering any confidential, client, patient, student, or personal data into a general AI account?
> - [ ] Would this draft still need a compliance, legal, or editorial review before it reaches a client, patient, student, or the public?
