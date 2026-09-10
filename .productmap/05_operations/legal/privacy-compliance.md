# Privacy & Compliance

> Phase 5 — Operations

The minimum privacy, security, and risk hygiene a pre-seed startup needs: know what personal data you hold, publish honest policies, lock the doors, and keep a short register of the risks that could actually kill you.

> This file organises your own information. It is not legal advice — confirm specifics with a qualified lawyer in your jurisdiction.

## Privacy & ToS Status

| Item | Status | Location / Notes |
|------|--------|------------------|
| Privacy policy published | [Done / To do] | [URL] |
| Terms of service published | [Done / To do] | [URL] |
| Cookie consent (if using tracking cookies in EU/UK) | [Done / To do / N/A] | [Tool] |
| Data deletion process (user can request deletion) | [Done / To do] | [How it works] |

## Data Inventory

| Personal Data | Where Stored | Processor / Vendor | Why Collected |
|---------------|--------------|--------------------|----------------|
| [e.g., email, name] | [e.g., Postgres on AWS eu-west-1] | [e.g., AWS] | [Account creation] |
| [e.g., usage events] | [e.g., analytics tool] | [Vendor] | [Product analytics] |
| [e.g., payment details] | [e.g., not stored — tokenised] | [e.g., Stripe] | [Billing] |

## GDPR / CCPA Quick Check

- **Users in the EU/UK?** [Yes / No] — if yes, GDPR applies regardless of where the company is based.
- **California users at scale?** [Yes / No] — CCPA thresholds mostly bite later, but check if selling data.
- **Lawful basis for processing:** [Fill in: e.g., contract for account data, consent for marketing]
- **DPAs signed with processors handling personal data:** [Yes / No / list]

## Security Basics Checklist

| Item | Status |
|------|--------|
| 2FA enforced on email, cloud, code hosting, and banking | [Done / To do] |
| Password manager used by all team members | [Done / To do] |
| Access control: least privilege, offboarding checklist exists | [Done / To do] |
| Production data backups tested | [Done / To do] |
| Secrets not in code (env vars / secret manager) | [Done / To do] |

## Operational Risk Register

The handful of risks that could stop the company from shipping safely or operating legally. Review monthly; keep it under ten rows.

| Risk | Probability | Impact | Owner | Mitigation | Status |
|------|------------|--------|-------|------------|--------|
| [e.g., single point of failure: only one founder can deploy] | [H/M/L] | [H/M/L] | [Name] | [Fill in] | [Open / Mitigated] |
| [e.g., key vendor/API dependency changes terms] | | | | | |
| [e.g., data breach of user emails] | | | | | |

## Related

- [ip-and-contracts.md](./ip-and-contracts.md)
- [04_delivery/development/development.md](../../04_delivery/development/development.md)
