# VAPI

## 1. System Architecture
- Channels: Voice (phone), Web SDK
- Orchestrator: Event-driven agent runtime
- LLM: OpenAI (GPT-4 / GPT-4o)
- Memory: Session-based conversation state
- Tools: Function calling, webhooks
- Human handoff: Supported via call transfer

## 2. Latency & Streaming
- Realtime / Turn-based: Realtime streaming
- Interrupts / Barge-in: Supported

## 3. Telephony & Voice Stack
- Telephony: Twilio, SIP
- ASR: Deepgram, Whisper
- TTS: ElevenLabs, PlayHT

## 4. Safety & Compliance
- PII handling: Configurable redaction (LIMITED PUBLIC INFO)
- Guardrails: Prompt + tool constraints
- Consent / recording: Telephony-provider dependent

## 5. Observability
- Logs / Traces: Basic logs via dashboard
- Analytics: Call logs, transcripts
- Debugging visibility: Partial (UNKNOWN deeper tracing)

## 6. Deployment Model
- SaaS / VPC / On-prem: SaaS
- Tenant isolation: Logical isolation

## 7. Integration Surface
- CRM: Via webhooks
- Webhooks / APIs: Yes
- Tools: Custom functions

## 8. Reliability Patterns
- Retries: UNKNOWN (how to verify: infra docs)
- Fallbacks: Basic model fallback
- Queues / rate limits: UNKNOWN

## Credibility Signals
- Public docs available
- Live demos and SDKs
- Usage-based pricing

## Sources
- https://docs.vapi.ai
- https://vapi.ai

