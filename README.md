# Leona

Leona is a healthcare communication company building an AI co-pilot for doctors and medical teams who run their practices over WhatsApp. Patients keep messaging WhatsApp as they always have, while the clinician side moves into Leona, where work conversations are separated from personal ones, categorized and prioritized, summarized for context, and voice notes are transcribed. Teams delegate chats by role, keep internal notes on a patient that the patient never sees, and reuse templates for repeated answers.

Founded by Caroline Merin (CEO, formerly COO at Rappi), Tom Chokel (CTO, formerly CTO at Modern Fertility) and Arela Solis (Head of Operations), Leona launched publicly in December 2025 and serves physicians across Latin America.

Backed by: Accel, Andreessen Horowitz, General Catalyst, Homebrew — https://www.leona.health/en

## API surface

Leona publishes **no public developer API**. It ships end-user clients (iOS, Android, and a web app at https://web.leona.health/#/start). `api.leona.health` is the product's own backend; it serves no OpenAPI, no reference documentation, and no developer portal. There are no first-party SDKs or CLIs in any public package registry, and no `/.well-known/` discovery documents on any host.

## Artifacts

| Artifact | File |
|---|---|
| llms.txt | `llms/leona-llms.txt` |
| Well-known probe (all 404 — recorded negative) | `well-known/leona-well-known.yml` |
| Domain security probe | `security/leona-domain-security.yml` |

## Links

- Website — https://www.leona.health/en
- Web app — https://web.leona.health/#/start
- App download — https://onelink.to/kvadu2
- FAQs — https://www.leona.health/en/faqs
- Blog — https://www.leona.health/en/blog
- Careers — https://www.leona.health/en/careers
- GitHub — https://github.com/Leona-Health
- Terms — https://www.leona.health/en/tyc
- Privacy — https://www.leona.health/en/privacidad
