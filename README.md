# ALOE

<p align="center">
  <img src="assets/aloe_app_icon.png" alt="ALOE icon" width="160">
</p>

<p align="center">
  <strong>Automated Lead Outreach Engine</strong>
</p>

ALOE is a private, human-guided workspace for discovering promising businesses,
organizing contact intelligence, prioritizing opportunities, and preparing
personalized outreach across multiple channels.

> **Status:** Actively under development. The application source code and lead
> data remain private; this repository is a public product overview.

## What ALOE is designed to do

- Discover leads from permission-compatible public APIs, feeds, directories,
  and approved local imports.
- Normalize and deduplicate companies gathered from different sources.
- Incrementally enrich missing business and contact information without
  repeating completed work.
- Rank opportunities using growth signals, recency, reachability, audience
  size, and evidence quality.
- Verify that named contacts and personal profile links actually correspond to
  the right organization.
- Build reviewable outreach batches for email, LinkedIn, X, and Telegram.
- Personalize drafts using project evidence while keeping a human in control of
  external communication.
- Track outreach status, channel, replies, delivery outcomes, and experiment
  performance.
- Compare message variants and use measured results to improve future outreach.
- Schedule bounded lead-discovery and outreach-preparation workflows with an
  audit trail.

## Product principles

### Evidence before automation

Lead ranking and personalization should be explainable from saved source
evidence. Missing or uncertain information is labeled rather than invented.

### Incremental by default

ALOE preserves useful information, skips contacted or sufficiently complete
records, and focuses each run on genuinely unfinished work.

### Human approval for external actions

The system can prepare, organize, and track outreach. Sending messages or
performing social actions remains an explicit human decision.

### Permission-aware data collection

Source adapters respect access boundaries. Permission-gated or paid sources are
kept separate from sources that can be accessed through documented public
interfaces.

### Privacy-conscious development

Application code, credentials, private datasets, outreach records, and contact
details are intentionally excluded from this public repository.

## Current product areas

| Area | Purpose |
|---|---|
| Dashboard | Explore, filter, rank, and track leads across sources |
| Contact verification | Review named contacts, roles, and profile associations |
| Outreach workspace | Select batches, review personalized drafts, and record outcomes |
| LinkedIn workflow | Prepare verified, user-specific connection-review queues |
| Source configuration | Monitor source health, yield, readiness, and recommended actions |
| Automation | Schedule bounded discovery and outreach-preparation workflows |
| Experimentation | Organize message variants and compare outreach performance |

## Development roadmap

- Improve source coverage and source-health diagnostics.
- Expand contact verification and confidence scoring.
- Strengthen cross-source company identity resolution.
- Add safer, clearer multi-channel outreach workflows.
- Improve batch analytics, reply classification, and experimentation feedback.
- Create privacy-preserving operational dashboards and exports.

## Availability

ALOE is currently a private project and is not distributed from this
repository. Public documentation and product updates will be added here as the
project develops.

