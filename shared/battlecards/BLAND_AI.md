# Bland AI

## 1. System Architecture
- Channels: Voice (Outbound calling)
- Orchestrator: AI calling workflow engine
- LLM: OpenAI (GPT-4 class)
- Memory: Conversation-level context
- Tools: Scripted actions + APIs
- Human handoff: Limited (primarily automated)

## 2. Latency & Streaming
- Realtime / Turn-based: Near-realtime
- Interrupts / Barge-in: LIMITED support

## 3. Telephony & Voice Stack
- Telephony: Twilio
- ASR: Deepgram
- TTS: ElevenLabs

## 4. Safety & Compliance
- PII handling: Claimed secure handling (DETAILS UNKNOWN)
- Guardrails: Script + prompt constraints
- Consent / recording: Dependent on telephony provider

## 5. Observability
- Logs / Traces: Call logs available
- Analytics: Call outcome metrics
- Debugging visibility: LOW (UNKNOWN deep visibility)

## 6. Deployment Model
- SaaS / VPC / On-prem: SaaS
- Tenant isolation: Logical isolation

## 7. Integration Surface
- CRM: Webhook-based
- Webhooks / APIs: Limited APIs
- Tools: Custom scripts

## 8. Reliability Patterns
- Retries: UNKNOWN
- Fallbacks: Script fallback
- Queues / rate limits: UNKNOWN

## Credibility Signals
- Public demos on website
- Clear positioning for sales automation
- Usage-based pricing cues

## Sources
- https://www.bland.ai
- https://docs.bland.ai

