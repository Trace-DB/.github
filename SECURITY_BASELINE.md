# Trace-DB Security Baseline

Trace-DB repositories use GitHub-native controls first:

- private vulnerability reporting and the organization security policy
- Dependabot alerts and dependency graph
- secret scanning and push protection
- CodeQL for JavaScript, TypeScript, Python, and Go repositories where code is
  present
- protected default branches or rulesets before production deploys or package
  releases
- protected environments for production deploy and package-release jobs

Do not commit secrets, private endpoints, operator logs, production tokens, or
hosted-service incident material. Report security issues privately through
GitHub private vulnerability reporting or the contact listed on the TraceDB
website.

Release tokens should be avoided where trusted publishing is available. Where a
long-lived registry token is still required, store it only as a GitHub
Environment secret and rotate it after any suspected exposure, maintainer
offboarding, or deployment incident.
