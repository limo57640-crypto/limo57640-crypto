# Ping7 Defensive CVE Tools

Ping7 publishes small defensive checkers for site owners, hosting teams, and agencies that need a first pass before a repair job.

Live site: https://ping7.cc

## GitHub Tool Pages

| Tool | CVE | Browse page | Repository | Ping7 guide |
| --- | --- | --- | --- | --- |
| NGINX Rift Detector | CVE-2026-42945 | https://limo57640-crypto.github.io/nginx-rift-detector/ | https://github.com/limo57640-crypto/nginx-rift-detector | https://ping7.cc/guides/nginx-rift-cve-2026-42945-self-check/ |
| WordPress User Registration Checker | CVE-2026-1492 | https://limo57640-crypto.github.io/wp-user-registration-vuln-checker/ | https://github.com/limo57640-crypto/wp-user-registration-vuln-checker | https://ping7.cc/cve/wordpress-1492/ |
| cPanel CVE-2026-41940 IOC Detector | CVE-2026-41940 | https://limo57640-crypto.github.io/cpanel-cve-41940-detector/ | https://github.com/limo57640-crypto/cpanel-cve-41940-detector | https://ping7.cc/guides/cpanel-cve-2026-41940-self-check/ |

## Ping7 Entry Points

- CVE dashboard: https://ping7.cc/cve/
- CVE lookup: https://ping7.cc/cve/lookup/
- GitHub tools index: https://ping7.cc/github-tools/
- CVE repair: https://ping7.cc/cve-repair/
- Sample repair report: https://ping7.cc/cve-repair/sample-report/
- Live alerts: https://t.me/ping7cve

## Defensive Boundary

These projects are for owned systems and client-approved environments. They focus on version checks, configuration review, log review, compromise indicators, and repair handoff.

They do not include exploit code, credential theft, unauthorized scanning steps, or attack-chain walkthroughs.

## When To Ask For Repair Help

Use Ping7 repair when a checker returns `SUSPICIOUS`, `VULNERABLE`, or `COMPROMISED`, or when logs are missing and the system stores customer, payment, membership, or hosting data.

Send the CVE ID, product version, tool output, first suspicious timestamp, and sanitized logs or screenshots. Do not send passwords in the first message.
