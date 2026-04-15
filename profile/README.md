<div align="center">

<p align="center">
  <img src="../assets/logo.svg" alt="ConsentOS" width="260">
</p>

<br />
<br />

[![Licence: ELv2](https://img.shields.io/badge/Licence-ELv2-1B3C7C?style=flat-square)](https://github.com/consentos/consentos/blob/main/LICENSE)
[![IAB TCF v2.2](https://img.shields.io/badge/IAB%20TCF-v2.2-2C6AE4?style=flat-square)](https://github.com/consentos/consentos)
[![Google Consent Mode](https://img.shields.io/badge/Google%20Consent%20Mode-v2-2C6AE4?style=flat-square)](https://github.com/consentos/consentos)
[![Self-hostable](https://img.shields.io/badge/Self--hostable-Docker%20%2F%20Kubernetes-0DAA72?style=flat-square)](https://github.com/consentos/consentos)

<br />

**Self-hosted, multi-tenant cookie consent management.**

ConsentOS is a source-available alternative to OneTrust, Cookiebot, and CookieYes -- built for teams who want full control over their consent stack without per-domain SaaS fees. One script tag on your site. Everything else runs on your own infrastructure.

[Website](https://www.consentos.dev) &nbsp;·&nbsp; [Documentation](https://www.consentos.dev/docs) &nbsp;·&nbsp; [Main Repository](https://github.com/consentos/consentos) &nbsp;·&nbsp; [Report an Issue](https://github.com/consentos/consentos/issues)

</div>

---

### What it does

| | |
|---|---|
| **Consent banner** | 2KB loader, full bundle in Shadow DOM -- style-isolated from your site |
| **Auto-blocking** | Intercepts scripts, cookies, and storage writes until consent is granted per category |
| **IAB TCF v2.2** | Full TC string encoding and CMP API -- works with major ad networks and DSPs |
| **Google Consent Mode v2** | Automatic `gtag('consent', ...)` signalling for GA4 and Google Ads |
| **Cookie scanner** | Playwright crawler with 2,200+ auto-categorisation patterns |
| **Compliance engine** | Rule-based checks for GDPR, CNIL, CCPA/CPRA, ePrivacy, and LGPD |
| **Multi-tenant admin** | Organisations, sites, RBAC, and regional config overrides |

---

### Get started

```bash
git clone https://github.com/consentos/consentos.git
cd consentos && cp .env.example .env
make up && make seed
```

Admin UI at `localhost:5173`. Full setup guide at [consentos.dev/docs](https://www.consentos.dev/docs).

---

### Licence

Licensed under the [Elastic Licence 2.0](https://github.com/consentos/consentos/blob/main/LICENSE). Free to self-host and modify. The [Open Cookie Database](https://github.com/jkwakman/Open-Cookie-Database) bundled with this project is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

<div align="center">

Built by [Slate Data](https://www.slatedata.co.uk)

</div>
