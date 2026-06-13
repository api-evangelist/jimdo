# Jimdo

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
