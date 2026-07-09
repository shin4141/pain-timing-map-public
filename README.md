# Pain Timing Map

![Manual MVP](https://img.shields.io/badge/Manual%20MVP-PASS-brightgreen)
![Status](https://img.shields.io/badge/Status-PUBLIC%20SHELF%20%2F%20Public%20intake%20BLOCK%20%2F%20Chart%20renderer%20HOLD-yellow)
![Implementation](https://img.shields.io/badge/Implementation-HOLD-yellow)
![API / Scraping / Automation](https://img.shields.io/badge/API%20%2F%20Scraping%20%2F%20Automation-BLOCK-red)
![Public Posting](https://img.shields.io/badge/Public%20Posting-HOLD-yellow)
![Prediction Guarantee](https://img.shields.io/badge/Prediction%20Guarantee-NO-lightgrey)

Pain Timing Map is a manual framework for recording pain signals, rechecking them over time, and deciding whether a signal is still worth action, delay, or rejection. It treats weak signals as decision material: useful only when paired with evidence, timing, fit, risk, and clear boundaries.

## Current Status

Manual MVP: PASS  
Public Repo: PUBLIC  
Public Surface: PUBLIC SHELF
Public Intake: BLOCK
Chart Renderer: HOLD
Implementation: HOLD  
API / Scraping / Automation: BLOCK  
Public Posting: HOLD  
Release / Tag: HOLD  
Pricing / Sell-test: HOLD  
Prediction Guarantee: NO  
Medical Advice: NO  
Build Recommendation: NO

This repository is a manual, evidence-backed pain signal map. It does not guarantee prediction, diagnosis, automation, or build decisions.

## What This Is

- A manual evidence-structuring workflow.
- A way to record weak signals, small pains, feature announcements, repo trends, and operational frictions.
- A recheck format for asking whether a signal is noise, evidence, or something to watch.
- A timing map for placing signals into WATCH, HOLD, CAP, PREPARE, or BUILD CANDIDATE gates.
- An evidence-backed pain signal map.

## What This Is Not

- This is not medical advice.
- This is not a recommendation engine.
- This is not an automation, scraping, API, or chart-rendering system.
- This is not a build/sell instruction.
- This is not investment advice, prediction, or market validation.
- BUILD CANDIDATE does not authorize implementation.

The build decision remains with the user or operator.

## Manual Usage Flow

1. Capture a light signal.
2. Recheck the signal against source type, surface claim, hidden pain hypothesis, affected user group, timing, pre-signals, and risk.
3. Create an output card with the signal, hidden pain, timing, pre-signals, and gate.
4. Compare repeated signals over time.
5. Decide whether the signal should remain WATCH, HOLD, CAP, PREPARE, BUILD CANDIDATE, or be rejected.

## Example Output

After several signals are captured, Pain Timing Map can place them across a Timing Line, Deadline Line, and Trigger Line.

```text
Now ----- 1M ----- 3M ----- 6M ----- 12M ----- Evergreen
          |        |                                  |
          |        |- AI Paper Delta Score            |- Fable Audit
          |        |- Small Everyday Memory           |- Small Curiosity Signal
          |
          |- EV-Based Fix Filter
```

See `examples/public_timing_batch_example.md`.

## Color Tags

Color tags are optional review-state markers for timing and evidence. They are not medical labels, recommendations, or action instructions.

See `docs/color_tags.md` for the public color tag guide.

## Downstream Entry Use

Pain Timing Map can produce a Pain Signal Package / Entry Intake Pack. This package does not decide what to build. It prepares evidence-backed material that can later be evaluated by an Entry Window / Entry Decision process.

The package sits between Pain Timing Map and downstream Entry evaluation:

```text
Pain Timing Map
-> Pain Signal Package / Entry Intake Pack
-> Entry Window Radar
-> Entry Decision
```

Pain is allowed to package evidence-backed material. Pain is not allowed to issue a Build Command.

## Included Files

- `docs/mvp_scope.md`: manual MVP scope and non-goals.
- `docs/manual_usage_flow.md`: step-by-step manual usage flow.
- `docs/visual_overview.md`: simple diagrams for signal flow.
- `docs/color_tags.md`: public guide for color tag meanings.
- `docs/entry_intake_pack.md`: Pain-side transfer format for downstream Entry evaluation.
- `inputs/signal_recheck_card_template.md`: blank card for manual review.
- `inputs/entry_intake_pack_template.md`: blank Pain Signal Package / Entry Intake Pack template.
- `inputs/user_profile.md`: optional profile template for fit and constraints.
- `inputs/evidence_sources.md`: evidence source notes.
- `examples/`: sample signal recheck cards.
- `examples/public_entry_intake_pack_example.md`: fictional public-safe Entry Intake Pack example.
- `schema/pain_record.schema.json`: optional structured record schema.
- `prompts/evaluate_pain_signal_prompt.md`: manual prompt for reviewing a pain record.
- `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, `SUPPORT.md`: project boundary and support documents.

## Example Workflow

```text
Light signal
-> Signal Recheck
-> Pain hypothesis
-> Timing hypothesis
-> Pre-signals
-> Gate
-> Recheck later
```

Example question set:

- What was noticed?
- Where did the signal come from?
- What hidden pain might it point to?
- Who would feel that pain first?
- What evidence would confirm or weaken it?
- Is the right gate WATCH, HOLD, CAP, PREPARE, BUILD CANDIDATE, or reject?

## Safety And Privacy Note

Do not paste personal data, sensitive scraped data, medical records, confidential business material, credentials, or exploit details into records or examples. Keep evidence specific enough to review, but avoid including information that should not be shared.

This framework can help organize decision material. It does not provide medical, legal, financial, security, business, or product guarantees.

## Publication Boundary

This folder is a public shelf candidate, not a release. It is prepared for review as a clean documentation surface and should not be treated as publication, launch, or implementation approval.

Public posting, release/tag work, pricing work, build decisions, API work, scraping, and automation remain out of scope unless separately approved.

## License And Contributions

No license file is included in this shelf yet. Before reuse or publication, add an explicit license or keep usage limited to review.

See `LICENSE_DECISION_REQUIRED.md` for the current license hold.

For contribution boundaries, see `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, and `SUPPORT.md`.

This is not a recommendation to build.
This is an evidence-backed pain signal map.
The build decision remains with the user.
