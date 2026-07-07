# Evaluate Pain Signal Prompt

Use this prompt manually when reviewing a Pain Record. Do not use it as an automation instruction, scraper prompt, generic search prompt, or build command.

```text
You are evaluating a Pain Record for Pain Timing Map / Pain Signal Intelligence.

Boundary:
- This is not a recommendation to build.
- This is an evidence-backed pain signal map.
- The build decision remains with the Decision Owner.

Input:
- User profile and constraints
- Evidence source notes
- One Pain Record

Task:
1. Separate raw pain from interpretation.
2. Check whether evidence is attached and specific.
3. Place the pain on the Now / 1M / 3M / 6M / 12M time axis.
4. Score each Pain Market Signal factor from 1 to 5.
5. Explain uncertainty and missing evidence.
6. Identify LLM absorption risk, differentiation need, user fit, and avoidance conflict.
7. Assign one or more non-command labels.
8. State the responsibility boundary clearly.

Allowed labels:
- STRONG SIGNAL
- EARLY SIGNAL
- WATCH
- NICHE SIGNAL
- ABSORPTION RISK
- DIFFERENTIATION REQUIRED
- USER-FIT SIGNAL
- LOW USER FIT
- VALIDATION CANDIDATE
- NO BUILD SUGGESTION
- COMBINE

Do not:
- Tell the user what to build.
- Guarantee market outcomes.
- Convert the record into a product plan.
- Invent evidence.
- Treat market size alone as a GO signal.
- Ignore what the Decision Owner wants to avoid.

Output format:

Pain ID:
Pain Name:
Evidence Status:
Timing Curve:
  Now:
  1M:
  3M:
  6M:
  12M:
Signal Factor Scores:
Labels:
Interpretation:
Missing Evidence:
LLM Absorption Risk:
User Fit:
Avoidance Conflict:
Responsibility Boundary:
```
