What VAPI Does : 
VAPI is a developer-focused platform for building AI voice agents.
It supports both phone-based calls and web voice experiences using SDKs.

Architecture Summary : 
VAPI runs on an event-driven agent runtime.
It uses OpenAI models (GPT-4 / GPT-4o) for responses.
Conversation state is maintained during each session.
Agents can trigger custom functions and webhooks.
Calls can be transferred to a human agent when needed.
The platform is designed for flexibility and fast development.

Latency and Call Experience : 
Conversations run in real-time streaming mode.
Users can interrupt the agent naturally.
This makes interactions feel responsive.

Telephony and Voice Stack : 
Telephony support includes Twilio and SIP.
Speech-to-text is handled by Deepgram or Whisper.
Text-to-speech uses ElevenLabs or PlayHT.
The voice stack is modular and configurable.

Safety and Compliance : 
VAPI supports configurable redaction of sensitive data.
Guardrails are applied through prompts and tool rules.
Call recording and consent depend on the telephony setup.
Public compliance details are limited.

Observability and Monitoring : 
Basic logs are available through the dashboard.
Call transcripts and call history can be reviewed.
Deep trace-level debugging is partially available.
This is useful for development and basic monitoring.

Deployment Model : 
VAPI is offered as a SaaS platform.
Tenant isolation is handled logically.

Integrations : 
Integrations are handled mainly through webhooks and APIs.
Custom functions allow agents to interact with external systems.
CRM connections can be built using webhooks.

Reliability : 
Basic model fallback is supported.
Other reliability mechanisms are not clearly documented.

Overall Impression : 
Strong developer tooling and SDKs.
Easy to experiment and iterate.
Good support for web and phone agents.
Limited transparency into deeper infrastructure details.

Sources
- https://docs.vapi.ai
- https://vapi.ai

