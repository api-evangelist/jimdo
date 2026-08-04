# Jimdo

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

Jimdo is a website builder platform that provides REST APIs for managing website content, blog posts, online store products, and customer data for small business websites. The platform offers AI-powered website creation tools, ecommerce capabilities, and developer integrations enabling businesses to build and manage their online presence programmatically.

- **Website:** https://www.jimdo.com/
- **Developer Blog:** https://dev.jimdoweb.com/
- **GitHub:** https://github.com/Jimdo
- **LinkedIn:** https://www.linkedin.com/company/jimdo/
- **X:** https://x.com/jimdo
- **Pricing:** https://www.jimdo.com/pricing/
- **Status:** https://status.jimdo.com/

## APIs

Jimdo provides REST API access for managing website and ecommerce data programmatically, including content management, blog posts, online store products, orders, and customer records.

## Plans

Jimdo offers two main product tracks:

- **Jimdo Dolphin (AI Builder):** Website plans (Play $0, Start $11, Grow $17, Unlimited $28/mo) and Ecommerce plans (Basic $15, Business $19, VIP $39/mo)
- **Jimdo Creator (Template Editor):** Free, Pro $9, Business $15, SEO Plus $20, Platinum $30/mo

Annual billing provides 10-13% savings over monthly rates.

## Rate Limits

Jimdo does not publicly publish specific rate limit thresholds. Developers should implement exponential backoff on HTTP 429 responses and monitor standard rate limit headers.

## FinOps

- No transaction fees on paid ecommerce plans (third-party processors charge ~2.9% + $0.30/transaction)
- Annual billing cycles offer cost savings
- Free tiers available for development and evaluation

---

**APIs.json Profile:** [apis.yml](apis.yml)
