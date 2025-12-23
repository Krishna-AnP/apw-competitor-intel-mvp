# APW Voice Agent – Reference Architecture

## Overview
This document defines the minimum reference architecture for building a production-grade AI voice agent at APW.

## Channels
- Inbound phone calls
- Outbound calling
- Web-based voice widget

## Telephony Layer
- Twilio / SIP
- Call routing and recording

## Speech Layer
- ASR: Deepgram / Whisper
- TTS: ElevenLabs / PlayHT

## LLM Layer
- Models: GPT-4 / GPT-4o / Claude
- Prompt templates with role separation
- Tool calling and function execution
- Safety guardrails

## Orchestration
- Agent router
- State and session management
- Tool invocation engine
- Human handoff triggers

## Memory
- Short-term: In-call context
- Long-term: Conversation summaries

## Integrations
- CRM (HubSpot, Salesforce)
- Ticketing systems
- Calendars
- Custom APIs via webhooks

## Observability
- Call transcripts
- Latency and error metrics
- Conversation replay
- Prompt and model version tracking

## Reliability
- Retries and fallbacks
- Rate limiting
- Queue-based async tasks

## Security & Compliance
- PII redaction
- Secure secret management
- Consent handling
- Audit logs

## Deployment Model
- SaaS-first
- Optional VPC deployments
- Logical tenant isolation

