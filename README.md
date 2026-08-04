# ManyPets

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

ManyPets (formerly Bought By Many, part of ManyGroup) is a London-headquartered,
digital-first pet insurance provider founded in 2012. It sells lifetime dog, cat and
multi-pet insurance direct to consumers in the UK, alongside a preventative
flea/tick/worm plan, online claims and 24/7 video vet consultations. Sister ManyGroup
brands include ExoticDirect and VetBox. The US book is transitioning to Odie.

- Website: https://manypets.com/uk/
- Group: https://many-group.com/
- Partner programme (the only published API route): https://many-group.com/partners/
- GitHub: https://github.com/boughtbymany
- Trust centre: https://trust.manypets.com/

## API surface

**No public machine-readable API contract.** As of 2026-08-01, probes across
`manypets.com`, `www.manypets.com`, `many-group.com`, `trust.manypets.com` and
`exoticdirect.co.uk` found no OpenAPI/Swagger, no GraphQL endpoint, no AsyncAPI, no
MCP server, no A2A agent card and no `/.well-known/` discovery document — every path
returned 404. No `api.`/`developer.`/`docs.`/`status.` subdomain resolves.

ManyPets does operate an API: `many-group.com/partners/` lists **API Partner** as one
of five partnership types ("Integrate with our API to create a seamless journey for
customers to access our insurance"), alongside Affiliate, Widget Partner, Perk and
Custom Solutions. Onboarding is a contact form — no spec, endpoint, sandbox, auth
model or rate limit is published, so nothing can be captured without a partner
agreement.

## Artifacts

| Path | Type | Method |
|---|---|---|
| `conformance/manypets-conformance.yml` | Conformance | searched |
| `security/manypets-trust-center.yml` | TrustCenter | searched |
| `security/manypets-vulnerability-disclosure.yml` | VulnerabilityDisclosure | searched |
| `security/manypets-domain-security.yml` | DomainSecurity | probed |
| `packages/manypets-packages.yml` | Packages | searched |
| `lifecycle/manypets-lifecycle.yml` | Lifecycle | searched |
| `well-known/manypets-well-known.yml` | — (negative probe record) | probed |
| `llms/manypets-llms.txt` | LLMsTxt | generated |
