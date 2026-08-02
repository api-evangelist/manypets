# ManyPets

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
