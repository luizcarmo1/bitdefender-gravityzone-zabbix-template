# Security Policy

## Supported Versions

The following versions of this project are currently supported for security-related updates.

| Version | Supported |
|---|---|
| Zabbix 7.0 LTS template | Yes |
| Other versions | Not officially supported |

Security fixes and updates are provided on a best-effort basis.

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it responsibly.

**Do not disclose security vulnerabilities in public GitHub issues, discussions, pull requests, or other public channels.**

Preferred reporting method:

1. Open the repository's **Security** tab.
2. Look for **Report a vulnerability** or **Report a vulnerability privately**.
3. Submit a private vulnerability report with the details needed to investigate the issue.

If private vulnerability reporting is unavailable, contact the repository maintainer through their [GitHub profile](https://github.com/luizcarmo1) to arrange a private disclosure.

Please include, when possible:

- A description of the vulnerability and its potential impact.
- The affected template version and Zabbix version.
- Steps to reproduce the issue.
- Relevant logs or sanitized examples.
- Any suggested mitigation or fix.

**Do not include API keys, credentials, access tokens, personal data, or sensitive production information in your report.**

## Response and Disclosure

Reports will be reviewed on a best-effort basis. This is a community project maintained independently, and no guaranteed response or resolution time is provided.

Please allow the maintainer a reasonable opportunity to investigate and address a confirmed vulnerability before publicly disclosing it.

## Scope

Security reports relevant to this project include, but are not limited to:

- Exposure or mishandling of GravityZone API credentials.
- Unsafe handling of API responses or untrusted data.
- Vulnerabilities in template scripts or preprocessing logic.
- Security issues caused by the template's configuration or documented usage.

Issues originating solely in Zabbix, Bitdefender GravityZone, or other third-party products should be reported to their respective vendors. However, issues involving how this template interacts with those products are in scope.

## Security Best Practices

When using this template:

- Store API keys in Zabbix **Secret text** macros.
- Grant the GravityZone API key only the permissions required for monitoring.
- Use HTTPS for API communication.
- Never commit credentials or sensitive environment data to the repository.
- Review configuration changes before deploying them to production.

## Disclaimer

This project is a community-maintained template and is not an official Bitdefender or Zabbix product.