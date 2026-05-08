# Black Forest Labs (black-forest-labs)

Black Forest Labs is the company behind the Flux family of image generation models. The Flux API exposes asynchronous image generation endpoints via global and regional base URLs with model-named paths (e.g. `/v1/flux-2-pro`). Models include FLUX.2 (flex/pro/max/klein), FLUX.1 Kontext, FLUX1.1 [pro] Ultra, FLUX1.1 [pro], FLUX.1 Fill, and FLUX Schnell.

**APIs.json:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/black-forest-labs/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- AI, Image Generation, Flux, Open Weights, BFL

## APIs
1. **Flux Image Generation API** — async REST API at `https://api.bfl.ai` (regional: `api.eu.bfl.ai`, `api.us.bfl.ai`); submit + poll pattern.

## Common Properties
- [Website](https://blackforestlabs.ai/)
- [Documentation](https://docs.bfl.ai/)
- [Plans](plans/black-forest-labs-plans-pricing.yml) — partial (FLUX.2 specific prices via calculator)
- [RateLimits](rate-limits/black-forest-labs-rate-limits.yml) — partial
- [FinOps](finops/black-forest-labs-finops.yml) — reconciled

## Pricing Snapshot
- Flux Schnell: free direct from BFL
- Flux Pro / Flux 1.1 Pro: ~$0.04/image
- FLUX.2 family: priced via calculator (varies by model + dimensions)
- Aggregator pricing on Replicate/fal.ai differs (typically slightly higher)
- Enterprise: custom

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
