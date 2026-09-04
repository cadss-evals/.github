# Security and responsible disclosure

## Reporting

- **Vulnerabilities in this code** (the runner, scorer, or tooling): email **john@aichildsafety.org** with subject "SECURITY:". We acknowledge within 72 hours. Please do not open public issues for exploitable problems.
- **Findings about deployed AI products** surfaced by running these instruments: these are handled as responsible disclosure, not as public issues. Email us first; we coordinate disclosure with the affected provider before anything publishes.
- **Instrument-gaming discoveries** (ways a model could be tuned to pass the public arcs without the underlying behavior): tell us privately. Contamination and gaming resistance are core to the design; your finding shapes the private corpus rotation.

## Standing commitments

- No secrets, keys, or credentials are ever committed to these repositories; CI uses organization-level secrets with least-privilege scopes.
- No real children's data exists anywhere in this organization — all personas and transcripts are synthetic. Anything that appears to violate this is a critical bug: report it immediately.
- The benchmark canary GUID in the scenario pack must remain in all forks; stripping it defeats contamination detection for everyone.

## Supported versions

Design-stage prototypes carry no support guarantees; the pilot release will define a supported-version policy.
