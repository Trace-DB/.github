# Contributing

Thanks for contributing to TraceDB.

## Routing

- Core database changes: `tracedb`
- HTTP API, OpenAPI, protocol, and conformance changes: `tracedb-protocol`
- SDK changes: the matching SDK repo
- Example changes: `tracedb-examples`
- Design proposals: `tracedb-rfcs`
- Questions and community updates: `tracedb` Discussions

## Validation

This organization uses remote CI for builds, linting, tests, and package checks.
Local validation should stay lightweight unless a repo says otherwise:

- `git status`
- `git diff`
- syntax checks for changed JSON/YAML/Markdown where useful
- focused greps for public/private boundary mistakes

Do not add hosted-service implementation details, private endpoints, operator
runbooks, deployment architecture, credentials, or secrets to public repos.

