# Cortico (cortico)

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
