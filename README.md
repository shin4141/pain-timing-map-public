# Pain Timing Map

Pain Timing Map is a manual framework for recording pain signals, rechecking them over time, and deciding whether a signal is still worth action, delay, or rejection. It treats weak signals as decision material: useful only when paired with evidence, timing, fit, risk, and clear boundaries.

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

## Included Files

- `docs/mvp_scope.md`: manual MVP scope and non-goals.
- `docs/manual_usage_flow.md`: step-by-step manual usage flow.
- `docs/visual_overview.md`: simple diagrams for signal flow.
- `inputs/signal_recheck_card_template.md`: blank card for manual review.
- `inputs/user_profile.md`: optional profile template for fit and constraints.
- `inputs/evidence_sources.md`: evidence source notes.
- `examples/`: sample signal recheck cards.
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

## Current Status

This folder is a public shelf candidate, not a release. It is prepared for review as a clean documentation surface and should not be treated as publication, launch, or implementation approval.

Public posting, release/tag work, pricing work, build decisions, API work, scraping, and automation remain out of scope unless separately approved.

## License And Contributions

No license file is included in this shelf yet. Before reuse or publication, add an explicit license or keep usage limited to review.

For contribution boundaries, see `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, and `SUPPORT.md`.

This is not a recommendation to build.
This is an evidence-backed pain signal map.
The build decision remains with the user.
