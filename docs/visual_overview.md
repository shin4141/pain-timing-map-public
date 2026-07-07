# Visual Overview

## Manual Signal Recheck Flow

```mermaid
flowchart LR
  A[Light Signal / Noise] --> B[Signal Recheck]
  B --> C[Hidden Pain Hypothesis]
  C --> D[User Species]
  D --> E[Timing Hypothesis]
  E --> F[Pre-Signals]
  F --> G[Gate]
```

## Accumulation Flow

```mermaid
flowchart LR
  A[Light Signal] --> B[Signal Recheck Log]
  B --> C[Pain Cluster]
  C --> D[Evidence Candidate]
  D --> E[Decision Material Record]
```

## Signal Source Flow

```mermaid
flowchart LR
  A[Official Signal] --> D[Signal Recheck]
  B[User Pain Signal] --> D
  C[Internal Validation Signal] --> D
  E[Market Signal] --> D
  F[Trending Repo Signal] --> D
  D --> G[WATCH / HOLD / CAP / PREPARE]
```

## Boundary

These diagrams are documentation only. They do not authorize chart renderer, dashboard, automation, scraping, API, or implementation.
