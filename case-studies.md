# n8n Workflow Review

This review is based on read-only inspection. Nothing was changed in n8n.

## Featured

### Toda WhatsApp Commerce Assistant

Problem: customers need fast product discovery, price answers, website links, and order collection over WhatsApp.

Why it qualifies: the workflow normalizes WhatsApp messages, uses an AI sales assistant with catalog context, formats safe customer replies, sends WhatsApp responses, and appends ready orders to Google Sheets.

Portfolio positioning: ecommerce WhatsApp assistant for catalog support and order capture.

Status: demo-ready case study. Production activation and credential checks should be handled separately.

### Ibda3 Customer Support Assistant

Problem: a publisher needs Arabic customer support for books, publishing inquiries, website links, contact info, and recommendations.

Why it qualifies: the workflow has intent detection, dedicated reply paths, AI recommendation branches, memory, and WhatsApp response formatting. A related website chat version is also available.

Portfolio positioning: Arabic customer support assistant for publishing and ecommerce.

Status: demo-ready case study.

### Clinic Telegram Booking Assistant

Problem: clinics lose leads when booking requests and specialty questions come through chat without structured follow-up.

Why it qualifies: the workflow handles Telegram messages, detects booking intent locally to reduce token usage, uses AI only for fallback messages, captures phone/customer data, saves qualified leads to Google Sheets, and sends replies.

Portfolio positioning: healthcare lead capture and appointment routing assistant.

Status: demo-ready case study.

### Vapi Sales Call Automation Suite

Problem: sales teams need automated outbound/inbound call handling, memory, lead status updates, and fallback SMS after missed calls.

Why it qualifies: the suite includes inbound call trigger, call status handling, and call turn response workflows. It integrates webhook routing, Airtable lead/memory storage, Vapi calls, OpenAI response generation, and Twilio fallback SMS.

Portfolio positioning: voice AI sales automation pipeline.

Status: architecture-ready case study. Needs live credential and webhook validation before public production claims.

### Dahab BMW Reception Demo

Problem: an automotive service center needs a Telegram receptionist that collects car model, year, service type, slot, name, and phone.

Why it qualifies: the workflow has a Telegram trigger, AI receptionist, structured parser, routing, customer replies, and booking confirmation logic.

Portfolio positioning: automotive service booking assistant.

Status: demo-ready, with persistence/admin notifications currently disabled and best described as a reception demo.

## Not Featured As Production-Ready

### Content Facebook

Reason: good idea and schedule flow, but the inspected version has incomplete publishing flow and a disabled English post node. It should be repaired before being shown as a complete automated publishing system.

### Generic WhatsApp Clinic Bot

Reason: strong concept with voice transcription and booking tools, but it still contains placeholders for production IDs and sheets. It is better treated as a prototype until setup is completed.

### Older Clinic / Test Workflows

Reason: several older variants contain placeholder expressions, experimental routing, or overlapping approaches. They should not be presented as final client work.

