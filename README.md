# Claude and Codex skills

A collection of AI agent skills and scheduled automations for Claude Code and Codex. Each repo below is one skill.

Common thread: every skill states its guardrails up front. Facts are sourced and dated, outputs are checked by code or by a second agent, and nothing is sent, submitted or bought without the user's approval.

## General skills

General-purpose skills for research, review, handoffs, applications and setup.

| Skill | What it does | Type |
|---|---|---|
| [interview-call-prep](https://github.com/adiyt4soni/interview-call-prep) | Builds a prep pack and a one-page cue card for a recruiter screen, hiring-manager call, founder call, assessment or in-person round. | Claude Code skill |
| [cross-model-handoff](https://github.com/adiyt4soni/cross-model-handoff) | Writes a self-contained handoff packet so Codex, ChatGPT, Gemini or a fresh Claude session can take over a task with none of this conversation's context. | Claude Code skill |
| [verified-research-run](https://github.com/adiyt4soni/verified-research-run) | Runs research and comparisons where every fact is sourced, dated and confidence-tagged, and nothing counts until a separate skeptical pass has checked it against the live primary page. | Claude Code skill |
| [independent-review-audit](https://github.com/adiyt4soni/independent-review-audit) | Audits a prompt, plan, automation or deliverable with a reviewer that didn't produce it and works out the right answer before reading anyone's claim of success. | Claude Code skill |
| [jd-tailored-cv-and-letter](https://github.com/adiyt4soni/jd-tailored-cv-and-letter) | Builds one CV and one cover letter for one job description, then tests them hard before anything is sent. | Claude Code skill |
| [uk-area-safety-screen](https://github.com/adiyt4soni/uk-area-safety-screen) | Compares London areas to live in using public data only: police crime near each station, the Census 25-34 share, and TfL commute times, with built-in positive controls. | Claude Code skill |
| [room-listing-triage](https://github.com/adiyt4soni/room-listing-triage) | Finds, verifies, ranks and shortlists rooms or flats to rent, with scam rules and photo review, and drafts messages that are only sent with approval. | Claude Code skill |
| [project-scaffold](https://github.com/adiyt4soni/project-scaffold) | Sets up a new project folder so every future Claude or Codex session starts with the goal, the rules and the current state. | Claude Code skill |

## Job search and networking

Who to contact and what to say, in the user's own voice, measured against their reply rates.

| Skill | What it does | Type |
|---|---|---|
| [linkedin-target-finder](https://github.com/adiyt4soni/linkedin-target-finder) | Decides who to contact at a target company in a job search, and the warmest route in, before any message is written. | Claude Code skill |
| [linkedin-networking-writer](https://github.com/adiyt4soni/linkedin-networking-writer) | Drafts LinkedIn connection notes, replies, follow-ups and referral asks in the user's own voice, checked against their rules and their measured reply rates. | Claude Code skill |

## Job search automation

Scheduled agents that run a UK job search every day: find roles, tier them against a written rulebook, build tested applications, and check that work actually gets sent. None of them ever submits or sends on its own.

| Skill | What it does | Type |
|---|---|---|
| [uk-application-staging](https://github.com/adiyt4soni/uk-application-staging) | Codex version of the application sprint: discover, verify, rank and stage UK job applications without ever submitting one. | Codex skill |
| [uk-job-search-evening-close](https://github.com/adiyt4soni/uk-job-search-evening-close) | Codex version of the nightly check that today's committed actions actually went out: sent mail, real draft list, unanswered inbound. | Codex skill |
| [uk-daily-brief](https://github.com/adiyt4soni/uk-daily-brief) | A daily job-search command centre: reads email and calendar, syncs every application's status, finds and tiers new roles, prepares applications, and gives exactly three actions for the day. | Claude scheduled task |
| [uk-application-sprint](https://github.com/adiyt4soni/uk-application-sprint) | Runs every two hours: finds new UK roles worth applying to, builds a tailored, tested CV and cover letter for each, and stages them as a numbered batch for the user to approve. | Claude scheduled task |
| [uk-evening-close](https://github.com/adiyt4soni/uk-evening-close) | A short nightly check that catches the most expensive failure in a job search: work that gets done and then never actually gets sent. | Claude scheduled task |
| [uk-weekly-board](https://github.com/adiyt4soni/uk-weekly-board) | A weekly strategy review of a job search by a ten-seat advisory panel that reasons independently, names the real bottleneck, and fires its own dated triggers. | Claude scheduled task |
| [uk-weekly-scorecard](https://github.com/adiyt4soni/uk-weekly-scorecard) | A Sunday read-only audit of the job-search automation itself: regression tests, tracker integrity, run-log gaps, drift, submissions and overrides. | Claude scheduled task |

## Sales research

For SDR work: a sourced account brief and a call-to-CRM handover, each with a code checker.

| Skill | What it does | Type |
|---|---|---|
| [account-brief](https://github.com/adiyt4soni/account-brief) | Builds a one-page, fully sourced account brief on a UK multi-site employer that an SDR can trust before reaching out. | Claude Code skill |
| [call-handover](https://github.com/adiyt4soni/call-handover) | Turns a discovery-call transcript into CRM fields, a qualification check and an AE handover note, where every field quotes the exact words it came from. | Claude Code skill |

## Health dashboard

Routines for Tau, a local dashboard for WHOOP data.

| Skill | What it does | Type |
|---|---|---|
| [tau-whoop-refresh](https://github.com/adiyt4soni/tau-whoop-refresh) | Codex version of the Tau refresh: pull WHOOP data, build and validate the dashboard, and save a dated report without hiding failures. | Codex skill |
| [tau-routine](https://github.com/adiyt4soni/tau-routine) | One scheduled routine that runs a personal WHOOP health dashboard: morning data pull, validation, a written analysis and text, an evening reminder, and a night check-in. | Claude scheduled task |

## Investing research (paper money)

Routines for Argus 2.0, a paper-trading research engine with pre-registered rules. Paper money only; no orders, ever.

| Skill | What it does | Type |
|---|---|---|
| [argus-paper-fleet](https://github.com/adiyt4soni/argus-paper-fleet) | Codex version of the Argus paper-trading run: refresh price data, verify the hash chains, or list the queued paper orders, without ever trading. | Codex skill |
| [argus-paper-fleet-daily](https://github.com/adiyt4soni/argus-paper-fleet-daily) | After each US market close, runs a paper-trading research fleet end to end: read-only price fetch, daily and intraday accounts, hash-chain checks, number-checked company write-ups and a plain-English report. | Claude scheduled task |
| [argus-paper-fleet-open](https://github.com/adiyt4soni/argus-paper-fleet-open) | Every weekday around the US open, reports which paper buys and sells are going in for each fleet account. Read-only. | Claude scheduled task |

## From other authors (credited)

Unmodified copies of MIT-licensed skills that this collection builds on, each with its original licence and a link to the source.

| Skill | Author | What it does |
|---|---|---|
| [cold-email](https://github.com/adiyt4soni/cold-email) | Corey Haines | Writing and running B2B cold outbound: emails, follow-ups, sending setup, LinkedIn, multichannel cadences and reply handling. |
| [humanizer](https://github.com/adiyt4soni/humanizer) | Siqi Chen | Rewriting AI-sounding text so it reads like the writer, based on Wikipedia's "Signs of AI writing". |
| [stop-slop](https://github.com/adiyt4soni/stop-slop) | Hardik Pandya | Removing predictable AI writing patterns from prose (filler phrases, staged structures, tidy closers). |
| [prospecting](https://github.com/adiyt4soni/prospecting) | Corey Haines | Finding, qualifying and building prospect lists: signals, freshness windows and account research. |
| [networking-outreach](https://github.com/adiyt4soni/networking-outreach) | mbajaj (manojbajaj95) | Relationship-first networking: choosing who to connect with and drafting value-add outreach. |
| [social-graph-ranker](https://github.com/adiyt4soni/social-graph-ranker) | Affaan Mustafa | Weighted social-graph ranking for warm-intro discovery and bridge scoring. |

---

Each README says what is not included.
