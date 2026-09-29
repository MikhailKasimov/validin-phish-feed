# validin-phish-feed
Feed of phish-domains found using the Validin Threat Intelligince Platform

Web-site: https://validin.com

Platform: https://app.validin.com/portal

Social: https://twitter.com/ValidinLLC

# Contributing

Open a pull request. An indicator needs:

1. **A verifiable source** under a `# Reference:` header — a report, a sandbox run, a VirusTotal
   link. "I saw it" is not a source.
2. **Specificity.** A shared platform's apex (`azurewebsites.net`), a public suffix, or a CDN edge
   address flags every tenant on it.

# False positives and false negatives in databases

Please open an ordinary [issue](https://github.com/MikhailKasimov/validin-phish-feed/issues)
or [pull request](https://github.com/MikhailKasimov/validin-phish-feed/pulls).

# Third-party usage/integrations
* Hagezi DNS-blocklists: https://github.com/hagezi/dns-blocklists
* IPFire DBL (Phishing category): https://dbl.ipfire.org/
