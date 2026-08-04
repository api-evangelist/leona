# Leona

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
