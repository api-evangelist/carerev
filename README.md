# CareRev

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

CareRev is a healthcare workforce management and on-demand labor marketplace that connects hospitals and health systems directly with local, credentialed clinical professionals — RNs, LPN/LVNs, CNAs, surgical and ER techs, medical assistants, respiratory therapists, phlebotomists and mental health techs — without a traditional staffing agency in the middle. Facilities post open shifts from their existing scheduling and HR systems and vetted clinicians browse, claim and self-schedule them in the CareRev app. Products span the CareRev Marketplace, IRP+ (internal resource pool) and Smart Rates. CareRev is certified by The Joint Commission under its Health Care Staffing Services program and serves 650+ US facilities.

## API status

CareRev publishes **no public API program** — no developer portal, no API reference, and no machine-readable contract of any kind (no OpenAPI/Swagger, GraphQL, AsyncAPI, MCP server or A2A agent card). `api.carerev.com` is a real, live, TLS-enforced API gateway serving the CareRev applications and CareRev's partner integrations (VMS, scheduling and HR systems, including UKG Dimensions via the UKG Connect Technology Partner Program), but it is auth-gated and undocumented. Access is arranged through a CareRev partnership or customer implementation.

Contract discovery was run against every CareRev host; results are recorded in `well-known/carerev-well-known.yml`.

## Links

- Website: https://www.carerev.com/
- Partners / integrations: https://www.carerev.com/partners
- Status: https://status.carerev.com
- GitHub: https://github.com/CareRevolutions
- Forge (secondary market): https://forgeglobal.com/carerev_stock/
