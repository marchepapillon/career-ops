# Pipeline Context Storage

This directory holds the persistent state and cache of the JobTeaser pipeline:
- Scraped job offers and history (`offers.json`)
- Triage scores, rankings, queue/stack, and choices (`state.json`)
- Pipeline settings (`settings.json`)
- Routine canvas configuration (`routine.json`)
- Cached offer page details (`jobteaser_cache.jsonl`)

The state is synchronized with this repository rather than stored in ephemeral Docker instances.
