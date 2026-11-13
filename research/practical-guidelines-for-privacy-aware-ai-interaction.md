# Practical Guidelines for Privacy-Aware AI Interaction

## Purpose

Privacy-aware AI use requires more than knowing that a system may process user-provided information. Users also need practical skills for deciding what to disclose, how much context a task requires, and how to keep an interaction focused on their actual goal.

These guidelines are educational recommendations. They are not a substitute for a service's privacy policy, institutional rules, or professional advice.

## 1. Recognize information that deserves extra protection

Users should avoid sharing sensitive information unless it is genuinely necessary, the use is appropriate, and they understand the relevant service's data practices. Examples include:

- **Credentials and financial identifiers:** passwords, authentication codes, recovery keys, full payment-card details, and banking credentials.
- **Government and identity documents:** national identification numbers, passport details, scans of identity documents, and other identifiers that could enable impersonation.
- **Precise location and routine information:** home addresses, real-time location, access codes, travel plans, and predictable periods when a home or workplace is unoccupied.
- **Sensitive health and psychological information:** identifiable medical records, detailed therapy notes, diagnoses linked to a named person, and other highly personal health information.
- **Other people's private information:** private messages, photographs, contact details, family circumstances, or confidential information shared without appropriate permission.
- **Confidential organizational information:** internal documents, customer records, unpublished research, proprietary data, and information protected by workplace or institutional obligations.

The sensitivity of information depends on context. A detail that appears harmless in isolation may become identifying when combined with other details.

## 2. Apply data minimization before submitting a prompt

Before sharing information, users can ask:

1. Does the system need this detail to complete the task?
2. Can I remove names, exact locations, account numbers, or other identifying details?
3. Could a generalized description or fictional example achieve the same result?
4. Am I authorized to share this information, especially if it concerns another person or an organization?

For example, a study-planning request usually does not require a student's full name, university, home address, or exact daily movements. A generalized statement such as “I am a student who is usually available in the afternoons” may be sufficient.

Data minimization does not mean withholding all context. It means providing the least sensitive information that is adequate for the task.

## 3. Write focused prompts with clear boundaries

A well-structured prompt can reduce unnecessary disclosure and keep the interaction aligned with the user's goal. Users can specify:

- **Goal:** what they want to accomplish.
- **Relevant context:** only the details needed for that task.
- **Constraints:** time, format, level, or other practical limits.
- **Scope:** what the system should and should not address.
- **Clarification:** whether the system should ask focused questions when essential information is missing.
- **Critical feedback:** whether the system should identify assumptions, weaknesses, and alternative approaches.

### Example prompt

> **Goal:** Help me prepare a realistic study plan for a psychology exam.  
> **Relevant context:** I can study for about two hours per day and prefer short study blocks.  
> **Constraints:** Keep the plan manageable and suitable for a beginner.  
> **Scope:** Focus only on the study plan; do not introduce unrelated topics.  
> **Clarification:** If essential information is missing, ask up to three specific questions before making the plan.  
> **Critical feedback:** Point out unrealistic assumptions and suggest a more practical alternative.  
> **Privacy boundary:** Do not request identifying or sensitive personal information unless it is genuinely necessary.

This structure is a practical aid, not a guarantee that a system will follow every instruction or protect submitted data.

## 4. Ask AI to challenge assumptions, not merely agree

Users can encourage more reflective and less confirmatory interactions by asking questions such as:

- Which assumption in my reasoning may be incorrect?
- What relevant factor might I have overlooked?
- What evidence could challenge this conclusion?
- Is there a simpler or lower-risk alternative?
- Which parts of your answer are uncertain, and why?

Such prompts can support critical thinking. However, users should independently verify important claims and should not treat an AI response as authoritative merely because it sounds confident.

## 5. Maintain appropriate boundaries and verify service practices

A warm, fluent, or personalized conversational style should not be treated as evidence that an AI system is a human confidant or that information is confidential. Before sharing sensitive material, users should consider the service's privacy settings, data retention and deletion practices, access controls, and applicable organizational or legal requirements.

Users should also remember that:
- AI-generated information can be inaccurate, incomplete, or misleading.
- Important medical, psychological, legal, financial, and safety-related decisions require appropriate independent review or qualified professional support.
- Information about other people should be handled with respect for their privacy and applicable consent requirements.
- A prompt asking the system not to retain or use information does not, by itself, establish how the service actually processes that information.

## 6. Design implication: make safer choices easier

Privacy-aware interaction should not depend entirely on users remembering every precaution. Designers can support safer decisions through:

- **Contextual, proportionate reminders:** brief notices at moments when a user is about to share potentially sensitive information, without overwhelming routine tasks.
- **Data-minimizing defaults:** avoid requesting personal details that are not needed for the requested function.
- **Clear explanations:** communicate what information is needed, why it is needed, and relevant limits on confidentiality and data handling.
- **User control:** make it easy to skip questions, use fictional or generalized details, review submitted information, and access available privacy controls.
- **Professional conversational boundaries:** use supportive language without implying human intimacy, guaranteed confidentiality, or unrestricted trust.

These design recommendations complement technical safeguards such as encryption, access control, and secure data handling. They do not replace them.

## Conclusion

Responsible AI interaction is a shared design and user-literacy challenge. Systems should minimize unnecessary data collection and make privacy choices understandable; users should provide only the context needed, define the scope of their requests, and critically evaluate AI-generated responses.

The practical principle is simple: **share the minimum necessary information, ask for the help you actually need, and retain your own judgment.**

## Scope note

This section presents practical recommendations and design implications. It does not report empirical findings, and it does not establish that any particular conversational tone causes increased disclosure. The proposed experimental protocol in this repository would need to be conducted, reviewed under applicable ethics requirements, and analyzed before causal or behavioral conclusions could be drawn.
