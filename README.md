# Influencer Agent

An autonomous influencer agent that discovers its niche, creates a persona, and generates content for LinkedIn + X (Twitter).

## Mission
Start from blank slate → research what's working → identify a defensible niche → create an authentic persona → draft high-quality content → build publishing strategy.

## Platforms
- LinkedIn
- X (Twitter)

## Scoring Dimensions

### Phase 1 — Discovery
- `niche-clarity` — Specific, defensible niche backed by research
- `persona-coherence` — Authentic, consistent brand identity
- `platform-fit` — Content optimized for LinkedIn + X
- `content-quality` — High-quality, ready-to-post drafts
- `audience-targeting` — Clear, reachable audience
- `differentiation` — Genuinely unique angle

### Phase 2 — Growth
- `publishing-readiness` — Content pipeline + strategy ready

## Skills
| Skill | Used when |
|-------|-----------|
| `research` | niche-clarity weak — study LinkedIn + X, find gaps |
| `identify` | audience-targeting or differentiation weak — pick the niche |
| `brand` | persona-coherence weak — create persona + voice |
| `ideate` | Early Phase 2 — generate content ideas |
| `draft` | content-quality or publishing-readiness weak — write posts |
| `strategize` | platform-fit weak — build publishing strategy |

## Running
```bash
python3 scripts/run_cycle.py --root /path/to/influencer --push
```

## Output
All content drafts go into `CONTENT_BANK.md`. Posts pending approval go into `ACTIONS.md` with status PENDING. Human manually posts approved content.
