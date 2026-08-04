# Cortico (cortico)

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

Cortico (Cortico Health Technologies) is a Vancouver, British Columbia based healthcare connection platform, founded in 2019, that links patients, medical clinics, and health records across Canada and the United States. Its patient-engagement suite layers online booking, automated appointment reminders, secure two-way patient messaging, digital intake forms, telemedicine, specialist e-referrals, payments, and AI-driven administrative automation on top of the electronic medical records (EMRs) clinics already run — most notably a supported two-way integration with OSCAR EMR through that system's REST/SOAP web services, plus SMART on FHIR contextual launch and robotic process automation (RPA). Cortico is SOC 2 Type II and ISO 27001 certified and compliant with HIPAA, PIPEDA, and PHIPA.

Cortico **consumes** EMR and FHIR interfaces rather than publishing its own public developer API. As of this review there is no public developer portal, API reference, downloadable OpenAPI/Swagger, or FHIR CapabilityStatement. Integration with OSCAR EMR and other systems is delivered through a partnership and onboarding model, where the clinic's EMR service provider issues API credentials and enables the relevant endpoints. This profile is therefore an identity stub — honest about a real healthcare company with a real integration story but no self-serve public API surface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cortico/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cortico/refs/heads/main/apis.yml)

**Home market:** Canada (headquartered in Vancouver, BC; also serves the United States)

## Tags

- Healthcare
- Canada
- Patient Engagement
- EMR
- OSCAR EMR
- SMART on FHIR
- Telemedicine
- Clinical Workflow Automation
- Interoperability

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

No public, self-serve developer API is documented by Cortico. The company integrates into third-party EMRs (for example OSCAR EMR's `/ws/services/` REST and SOAP web services) and uses SMART on FHIR contextual launch and RPA to embed its patient-engagement tools. These are consumption patterns against other systems' APIs, not a Cortico-published API, so no `apis[]` entries are asserted.

## Common Properties

- [Website](https://cortico.health/)
- [About](https://cortico.health/about/)
- [Pricing](https://cortico.health/pricing/)
- [Blog](https://cortico.health/resources/)
- [GitHub Organization](https://github.com/cortico-health)
- [Privacy Policy](https://cortico.health/privacy-policy/)
- [Terms of Service](https://cortico.health/legal/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
