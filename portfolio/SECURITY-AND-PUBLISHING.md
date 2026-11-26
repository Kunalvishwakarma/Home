# Public Portfolio Security and Publishing Checklist

Use this checklist before publishing any file, diagram, screenshot, script or project narrative.

## Confidentiality

- [ ] No customer, employer or partner confidential information.
- [ ] No internal project names, organization charts, contact lists or non-public business information.
- [ ] No proprietary architecture diagrams, operational procedures, statements of work or internal documents.
- [ ] Project stories are generalized and do not imply employer endorsement.

## Secrets and identity

- [ ] No passwords, API keys, access tokens, private keys, certificates or connection strings.
- [ ] No personal data, email addresses or phone numbers belonging to other people.
- [ ] No production usernames, tenant IDs, subscription IDs or account identifiers.
- [ ] Example configuration uses placeholders and synthetic identities.

## Network and infrastructure

- [ ] Replace real IP addresses with documentation ranges such as 192.0.2.0/24, 198.51.100.0/24 and 203.0.113.0/24.
- [ ] Replace real domains, hostnames, site names and device identifiers with examples.
- [ ] Remove public IPs, VPN endpoints, firewall rules, routing tables and topology details that could expose a real environment.
- [ ] Check screenshots for browser tabs, notifications, metadata and background information.

## Code and data

- [ ] Use synthetic test data.
- [ ] Review scripts for hard-coded secrets, paths, usernames and environment details.
- [ ] Include safe usage instructions and a warning before destructive operations.
- [ ] Add dependency/version notes and basic tests where practical.

## Accuracy and professional presentation

- [ ] Clearly distinguish personal labs from work experience.
- [ ] Do not publish unverified metrics or claim sole ownership of team outcomes.
- [ ] Keep dates, titles and certifications consistent with the current CV.
- [ ] Explain limitations and assumptions.
- [ ] Include a README with purpose, setup, usage, validation and licensing.

## Publication rule

If uncertain whether an artefact is safe to publish, do not publish it. Recreate the concept from scratch using synthetic information or obtain written authorization from the information owner.
