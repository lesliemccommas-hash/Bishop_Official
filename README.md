# Privacy Policy — Bishop AI Assistant

Last Updated: February 28, 2026

---

## 1. Overview

This Privacy Policy describes how Bishop, a privately operated AI assistant service, collects, uses, retains, and protects information when you interact with it via SMS, voice calls, or WhatsApp.

By sending a message to or calling the Bishop Twilio number, you agree to the practices described in this policy.

---

## 2. Who We Are

Bishop is a privately operated AI assistant service.

**Privacy contact:**
Email: [leslie.mccommas@grid-synergy.net](mailto:leslie.mccommas@grid-synergy.net)
GitHub: [github.com/lesliemccommas-hash/Bishop_Official](https://github.com/lesliemccommas-hash/Bishop_Official)

---

## 3. What This Service Does

Bishop is an AI assistant that responds to text messages, WhatsApp messages, and voice calls. Interactions may include:

- Answering general questions and providing advice
- Generating documents or written content
- Assisting with personal, household, and business tasks
- Conducting outbound communications on behalf of authorized users

Bishop uses large language models (LLMs) hosted on private infrastructure and may route requests through third-party AI model providers. Conversation context is retained in a vector database to enable continuity across sessions.

---

## 4. Information We Collect

When you interact with this service, we may collect:

**a) Message Content**
The text of messages you send, including any information, questions, or requests you include.

**b) Voice Data**
Audio from voice calls. Audio is transcribed to text for processing and is not permanently stored in raw form beyond the duration required for transcription.

**c) Phone Number and Metadata**
Your phone number (as provided by Twilio), timestamps, message direction (inbound/outbound), and carrier metadata.

**d) Conversation History and Extracted Facts**
Summaries and factual extracts from conversations are stored in a private vector database (Qdrant) running on local infrastructure. This enables Bishop to recall context from prior interactions. Verbatim conversation transcripts are not stored indefinitely; fact extraction and summarization are used to reduce raw data volume.

---

## 5. How We Use Your Information

Information collected is used to:

- Generate relevant, context-aware responses to your messages and calls
- Maintain conversational continuity across sessions
- Conduct outbound communications you explicitly authorize on your behalf
- Improve the accuracy and quality of the service
- Troubleshoot technical issues

Your information is not used for advertising, sale to third parties, or any purpose unrelated to providing and improving this service.

---

## 6. Outbound Communications on Behalf of Users

Authorized users may direct Bishop to communicate with third parties on their behalf via SMS or voice. When conducting such outbound communications:

- The recipient will be notified at the start of the interaction that the communication is AI-assisted and that the conversation may be logged for accuracy purposes.
- Outbound messages will accurately represent the user's intent without misrepresentation of identity or affiliation.
- Authorized users are responsible for ensuring their outbound use complies with applicable laws, including the TCPA and CAN-SPAM Act.

---

## 7. Disclosure to Third Parties

Your personal information is not sold, rented, or traded. Data may be shared with:

**Service Providers**
Twilio, Inc. — SMS/voice infrastructure. Subject to [Twilio's Privacy Policy](https://www.twilio.com/legal/privacy). Twilio receives your phone number and message metadata as part of message delivery.

**AI Model Providers**
Responses may be generated using models operated by Anthropic, Google, or other providers via a private routing layer. Personally identifiable information in prompts is minimized where possible.

**Legal Requirements**
Information may be disclosed if required by law, court order, or government authority, or to protect the rights, property, or safety of this service or others.

Conversation content is not otherwise disclosed to third parties without your explicit consent.

---

## 8. Data Retention

- Conversation facts and summaries stored in the vector database are retained to support long-term continuity of the service.
- You may request deletion of your stored data at any time by contacting [leslie.mccommas@grid-synergy.net](mailto:leslie.mccommas@grid-synergy.net). Records associated with your phone number will be purged within 30 days of a verified request.
- Raw message logs on private infrastructure are retained for up to 90 days for troubleshooting, then deleted.
- Twilio retains message logs per their own retention policy.

---

## 9. SMS Messaging — Specific Disclosures

This service uses SMS messaging via Twilio. The following applies to all SMS interactions:

- Message frequency varies based on your interactions.
- Standard message and data rates from your carrier may apply.
- To opt out, reply **STOP** at any time. You will receive one confirmation message and no further messages will be sent.
- To resume after opting out, reply **START**.
- For help, reply **HELP** or contact [leslie.mccommas@grid-synergy.net](mailto:leslie.mccommas@grid-synergy.net).
- Opting out of SMS does not delete your stored conversation data — submit a separate deletion request if desired.

---

## 10. Children's Privacy

This service is not directed to children under 13. Personal information from children under 13 is not knowingly collected. Use by minors between 13 and 17 requires parental or guardian consent.

---

## 11. Data Security

All communication between service components occurs over WireGuard-encrypted tunnels (Tailscale). Data stored in the vector database resides on private, locally operated infrastructure not exposed to the public internet. All internal service endpoints require bearer token authentication.

No security measure is 100% guaranteed. Affected users will be notified promptly in the event of a breach involving personal information.

---

## 12. Your Rights

Depending on your jurisdiction, you may have the right to:

- Access the personal data held about you
- Request correction of inaccurate data
- Request deletion of your data
- Withdraw consent for processing

To exercise any of these rights, contact [leslie.mccommas@grid-synergy.net](mailto:leslie.mccommas@grid-synergy.net). Requests will receive a response within 30 days.

---

## 13. Changes to This Policy

This Privacy Policy may be updated from time to time. The "Last Updated" date at the top reflects the most recent revision. Continued use of the service after changes constitutes acceptance of the updated policy. Material changes will be communicated via SMS to active users where feasible.

---

## 14. Contact

[leslie.mccommas@grid-synergy.net](mailto:leslie.mccommas@grid-synergy.net)
[github.com/lesliemccommas-hash/Bishop_Official](https://github.com/lesliemccommas-hash/Bishop_Official)
