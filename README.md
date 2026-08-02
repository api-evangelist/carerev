# CareRev

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
