# Black Forest Labs (black-forest-labs)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Black Forest Labs is the company behind the Flux family of image generation models. The Flux API exposes asynchronous image generation endpoints via global and regional base URLs with model-named paths (e.g. /v1/flux-2-pro). Models include FLUX.2 (flex/pro/max/klein), FLUX.1 Kontext, FLUX1.1 [pro] Ultra, FLUX1.1 [pro], FLUX.1 Fill, and FLUX Schnell. Auth via BFL_API_KEY bearer token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/black-forest-labs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/black-forest-labs/refs/heads/main/apis.yml)

## Tags

- AI
- Image Generation
- Flux
- Open Weights
- BFL

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Flux Image Generation API

REST API for asynchronous image generation across the Flux model family. Submit a generation request, then poll the returned polling_url for the result. Global endpoint at https://api.bfl.ai with regional alternatives at https://api.eu.bfl.ai (GDPR) and https://api.us.bfl.ai. Model-name path pattern /v1/{model}.

- **Human URL:** [https://docs.bfl.ai/](https://docs.bfl.ai/)
- **Base URL:** `https://api.bfl.ai`

#### Tags

- Image Generation
- Flux
- Async
- Polling
- Text-to-Image
- Image Editing

#### Properties

- [Documentation](https://docs.bfl.ai/)
- [Sign Up](https://dashboard.bfl.ai/)
- [Pricing](https://bfl.ai/pricing)
- [L L Ms Txt](https://docs.bfl.ml/llms.txt)
- [Git Hub](https://github.com/black-forest-labs/flux)
- [Postman Collection](collections/black-forest-labs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/black-forest-labs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/bflai)
- [Website](https://blackforestlabs.ai/)
- [Documentation](https://docs.bfl.ai/)
- [Git Hub](https://github.com/black-forest-labs)
- [Plans](plans/black-forest-labs-plans-pricing.yml)
- [Rate Limits](rate-limits/black-forest-labs-rate-limits.yml)
- [Fin Ops](finops/black-forest-labs-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
