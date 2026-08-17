# Powder

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

Powder was a Paris-based gaming company (founded 2018, $14M Series A led by Serena) that built
AI-powered clipping software for gamers and content creators — a low-resource Windows screen
recorder plus on-device machine learning that turned gameplay recordings and long Twitch, YouTube
and Kick streams into short vertical clips, AutoEdits and automontages, with per-title models for
40-plus games.

**No public API surface.** Powder was distributed only as an end-user Windows desktop application
(Steam, Microsoft Store, Razer Cortex). It published no public API, developer portal, SDK, webhook
catalogue or machine-readable contract that this profile could find.

**Discontinued.** The apex host `powder.gg` now 301-redirects every path — including
`/openapi.json` and every `/.well-known/` path — to a first-party notice from the Powder team
stating that "the Powder app will no longer be updated or maintained" and that all subscriptions
have been cancelled. The notice is saved verbatim at
[`lifecycle/powder-end-of-life-notice.txt`](lifecycle/powder-end-of-life-notice.txt) and the
lifecycle record, with the probe evidence, is at
[`lifecycle/powder-lifecycle.yml`](lifecycle/powder-lifecycle.yml). The `www.powder.gg` marketing
site is still live but stale — it continues to advertise a subscription the notice says was
cancelled.

Source: portfolio company of [serena](https://github.com/api-evangelist/serena) — https://www.powder.gg/
