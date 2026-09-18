# ALOE

<p align="center">
  <img src="assets/aloe_app_icon.png" alt="ALOE icon" width="160">
</p>

<p align="center">
  <strong>Automated Lead Outreach Engine</strong>
</p>

ALOE is a private, human-guided workspace for discovering promising businesses, organizing contact intelligence, prioritizing opportunities, and preparing personalized outreach across multiple channels.

> **Status:** Actively under development. Application source code, credentials, lead data, and outreach records remain private; this repository is a public product showcase and development log.

## Why ALOE exists

Lead research is fragmented across directories, websites, feeds, public APIs, and internal records. ALOE brings that evidence into one reviewable workflow so a person can decide whom to contact, why an opportunity matters, and what to say.

## What ALOE is designed to do

- Discover leads from permission-compatible public APIs, feeds, directories, and approved local imports.
- Normalize and deduplicate companies gathered from different sources.
- Incrementally enrich missing business and contact information without repeating completed work.
- Rank opportunities using growth signals, recency, reachability, audience size, and evidence quality.
- Verify that named contacts and personal profiles correspond to the right organization.
- Build reviewable outreach batches for email, LinkedIn, X, and Telegram.
- Prepare personalized drafts while keeping a human in control of external communication.
- Track outreach status, channels, replies, delivery outcomes, and experiments.
- Schedule bounded discovery and outreach-preparation workflows with an audit trail.

## How AI is used

AI assists with work that benefits from synthesis and judgment while preserving human control.

| AI-assisted capability | Contribution | Human control |
|---|---|---|
| Evidence synthesis | Summarizes relevant signals from collected evidence | Users can inspect the supporting evidence |
| Lead prioritization | Assesses relevance, timing, reachability, and confidence | Users choose which leads enter a working queue |
| Contact verification | Helps distinguish similarly named people and organizations | Uncertain associations are flagged for review |
| Draft preparation | Produces context-aware drafts grounded in available evidence | Nothing is sent without an explicit human decision |
| Reply classification | Organizes responses and possible follow-up states | Users determine the actual next action |
| Experiment analysis | Compares message variants and outcome patterns | Users decide what changes to adopt |

AI output is treated as a recommendation, not a fact. Missing information is identified rather than invented, and important decisions retain an evidence trail. Read more in [AI, Privacy, and Human Oversight](docs/AI_AND_PRIVACY.md).

## Product principles

- **Evidence before automation:** Ranking and personalization should be explainable from saved source evidence.
- **Incremental by default:** ALOE preserves useful information and focuses each run on unfinished work.
- **Human approval:** Sending messages or performing social actions remains an explicit human decision.
- **Permission-aware collection:** Source adapters respect access boundaries and documented interfaces.
- **Privacy-conscious development:** Private code, credentials, datasets, outreach records, and contact details are excluded from this repository.

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

## Product gallery

Real application screenshots will be published after review for contact information, private lead data, credentials, and other sensitive content. Fabricated mockups will not be presented as product screenshots.

## Development

See the public [roadmap](ROADMAP.md) and [development log](CHANGELOG.md).

## Availability

ALOE is currently a private project and is not distributed from this repository. Public documentation and privacy-reviewed product updates will be added as development continues.
