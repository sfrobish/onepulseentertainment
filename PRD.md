# Product Requirements Document
## Entertainment Business Management Platform

**Version:** 1.0  
**Status:** Draft  
**Last Updated:** June 2026

---

## Overview

A unified software platform to manage the full lifecycle of an entertainment business — from lead acquisition through post-event follow-up. The system will automate and streamline business development, deal-closing, performer/production logistics, and promotion, replacing a fragmented manual workflow with an integrated, AI-assisted toolset.

---

## Module 1: Client Acquisition & Business Development

**Goal:** Increase the volume and quality of inbound leads by systematizing outreach, referrals, and follow-up that currently happen inconsistently or not at all.

### Requirements

**REQ-1.1 – CRM & Venue Database**  
The system shall maintain a searchable database of prospective venues and booking contacts, with fields for venue type, capacity, contact info, last outreach date, and status. Users shall be able to log, update, and filter records.

**REQ-1.2 – Automated Follow-Up with Past Clients**  
The system shall track all past clients and trigger follow-up reminders or automated outreach sequences (e.g., anniversary of event, seasonal check-ins) to re-engage lapsed relationships.

**REQ-1.3 – Third-Party Booking Platform Integration**  
The system shall provide tools or reminders to keep third-party platform profiles (e.g., Gig Salad) current, including media uploads, availability, and service descriptions. Stretch goal: direct API sync where available.

**REQ-1.4 – Social Media Automation**  
The system shall support scheduling and publishing content across major social platforms (Facebook, Instagram, TikTok, etc.) with an AI-assisted content generation feature to reduce manual effort.

**REQ-1.5 – Lead Source Tracking**  
All inbound leads shall be tagged by source (word of mouth, Gig Salad, social, cold outreach, etc.) so the user can evaluate which channels produce the best-converting business.

### Success Metrics

| Metric | Description |
|---|---|
| **Lead Volume** | Total number of new inbound inquiries per month; baseline established at launch and tracked for upward trend. |
| **Lead Source Diversity** | Percentage of leads from non-word-of-mouth sources; goal is to grow this from near 0% to a meaningful share over 6–12 months. |
| **Follow-Up Rate** | Percentage of past clients who receive a follow-up touchpoint within 12 months of their event; target 100%. |
| **Re-Engagement Conversion** | Number of past clients who book again after a system-triggered follow-up sequence. |

---

## Module 2: Deal Closing & Event Pre-Planning

**Goal:** Streamline the decision-making process for evaluating new opportunities and automate the logistical groundwork before a deal is finalized.

### Requirements

**REQ-2.1 – Opportunity Fit Assessment**  
The system shall present a structured intake form or checklist for each new inquiry capturing event date, type, location, budget, and key logistics. An AI-assisted scoring or summary view shall help the user quickly assess fit.

**REQ-2.2 – Speculative Event Pre-Planning**  
Upon receiving a qualified lead, the system shall allow the user to begin planning in "speculative mode," including:
- Tentative personnel assignments
- Equipment needs assessment
- Travel logistics outline
- A working calendar with provisional to-do items

**REQ-2.3 – Deal Activation (Speculative → Inked)**  
When a deal is confirmed, all speculative tasks and calendar items shall automatically convert to active, assigned work items with deadlines calculated backward from the event date.

**REQ-2.4 – Contract Generation**  
The system shall maintain a modular contract template library with:
- A set of standard, reusable clauses used across all contracts
- Event-specific variable fields (client name, date, venue, scope, compensation) auto-populated from the inquiry record
- Multiple contract tiers (e.g., short-form 2-page and long-form 10-page) selectable based on event type and client context
- AI-assisted review to flag missing or unusual terms

### Success Metrics

| Metric | Description |
|---|---|
| **Time-to-Decision** | Average time from inquiry received to go/no-go decision; target reduction vs. current baseline. |
| **Pre-Planning Completion Rate** | Percentage of inked deals where personnel, equipment, and logistics were already started in speculative mode before signing. |
| **Contract Turnaround Time** | Average time from deal agreement to signed contract delivered; target under 24 hours. |
| **Task Activation Rate** | Percentage of speculative task lists that successfully auto-convert to active timelines upon deal confirmation (measures system reliability). |

---

## Module 3: Performers & Production

**Goal:** Ensure the right performers and production elements are identified, confirmed, and fully prepared by event day — starting as early as the lead stage.

### Requirements

**REQ-3.1 – Performer Roster & Availability**  
The system shall maintain a database of performers with contact info, instrument/role, availability calendar, and preferred/confirmed status. Performers shall be pencilable at the lead stage and formally confirmed at deal signing.

**REQ-3.2 – Song & Repertoire Database**  
The system shall maintain a master database of all songs, each tagged with:
- Show type compatibility (tribute show: Buffett, Springsteen, etc.; general; festival; bar gig; corporate)
- Chart availability status
- Key, tempo, and any performance notes

**REQ-3.3 – Set List Generator**  
The system shall generate suggested set lists based on:
- Event type and style
- Show timing and duration
- Confirmed personnel (i.e., what each performer can cover)

Users shall be able to accept, modify, or regenerate suggestions.

**REQ-3.4 – Chart Management**  
The system shall track which charts exist for each song. It shall flag gaps where charts are missing. AI-assisted chart creation or import from standard notation tools shall be explored as a stretch goal.

**REQ-3.5 – Equipment & Production Checklist**  
For each event, the system shall generate a production checklist covering:
- User's personal gear list
- Audio tech assignment and contact
- Stage plot and input list (auto-generated template per personnel configuration)
- Lighting requirements

### Success Metrics

| Metric | Description |
|---|---|
| **Performer Confirmation Lead Time** | Average number of days before an event that all performers are formally confirmed; target 30+ days. |
| **Set List Readiness at Signing** | Percentage of events where a complete set list is generated at or before deal signing; target grows toward 100% as song database matures. |
| **Chart Coverage** | Percentage of active repertoire songs that have a complete, verified chart on file; target 90%+. |
| **Production Checklist Completion** | Percentage of events where the full production checklist (gear, audio tech, stage plot) is completed more than 7 days out. |

---

## Module 4: Promotion

**Goal:** Build a consistent promotional presence that currently does not exist — both for general brand awareness and for individual event marketing.

### Requirements

**REQ-4.1 – Front-End Brand Promotion (General)**  
The system shall support the creation and distribution of promotional content showcasing the user's productions, including:
- AI-generated social posts, bios, and pitch copy
- Media asset management (photos, videos, audio clips)
- A simple profile or press kit view suitable for sharing with prospective clients

**REQ-4.2 – Event-Specific Promotion**  
For confirmed events, the system shall generate event promotion assets including:
- Social media posts (pre-event countdown, day-of, post-event recap)
- Suggested hashtags and tagging for venues/partners
- A simple scheduling calendar for promotional posts keyed to the event date

**REQ-4.3 – Promotion Calendar & Automation**  
All promotional content shall be schedulable in advance. The system shall send reminders or auto-publish on schedule with minimal user intervention to account for the user's preference to minimize time spent on marketing tasks.

**REQ-4.4 – Performance Analytics**  
The system shall provide basic reporting on promotional activity — post reach, engagement, and lead attribution — so the user can see ROI on any marketing effort over time.

### Success Metrics

| Metric | Description |
|---|---|
| **Posting Consistency** | Number of promotional posts published per month across all platforms; starting from near zero, any positive trend is meaningful early on. |
| **Event Promotion Coverage** | Percentage of confirmed events that receive at least one pre-event and one post-event social post. |
| **Audience Growth Rate** | Month-over-month follower/reach growth across social platforms. |
| **Promotion-Attributed Leads** | Number of inbound inquiries that cite or can be traced to a social/promotional touchpoint (tracked via REQ-1.5 lead source tagging). |

---

## Cross-Cutting Requirements

**REQ-X.1 – AI Assistance Throughout**  
AI assistance shall be available across all modules to draft content, surface suggestions, fill in variables, and reduce manual data entry. The user should be able to initiate most workflows with minimal input and review/approve AI-generated output.

**REQ-X.2 – Unified Calendar & Task View**  
A master calendar shall aggregate all event dates, pre-event to-dos, promotional schedules, and follow-up tasks across all modules in a single view.

**REQ-X.3 – Mobile Accessibility**  
Core features (lead capture, task review, set list viewing, contract status) shall be accessible on mobile.

**REQ-X.4 – Data Portability**  
Users shall be able to export key data (client list, song database, contracts, past events) in standard formats (CSV, PDF).

---

## Out of Scope (v1.0)

- Payment processing or invoicing
- Ticketing or public-facing event pages
- Audio/video streaming or recording tools
- Multi-user / team collaboration (single-user initially)

---

## Open Questions

1. Which third-party booking platforms should be prioritized for integration in v1?
2. What contract template(s) should seed the library at launch?
3. Is chart creation (REQ-3.4) a must-have for v1 or a later milestone?
4. Should social publishing be native or routed through an existing tool (e.g., Buffer, Later)?
