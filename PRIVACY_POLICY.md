# Manilla Network — Privacy Policy

**Version:** 1.0
**Effective Date:** 2026-06-01
**Controller:** LILCKY STUDIO LIMITED trading as Manilla Network

---

## 1. WHO WE ARE

Manilla Network ("Manilla", "we", "our") is a music distribution and artist services platform operated by LILCKY STUDIO LIMITED. We are reachable at privacy@rald.cloud.

---

## 2. DATA WE COLLECT

| Category | Data | Purpose |
|----------|------|---------|
| Identity | Name, stage name, email, country | Account creation, communications |
| Application | Application ID, IP hash (SHA-256), signature timestamp | Contract audit trail |
| Music Content | Audio files, artwork, metadata (ISRC, UPC, credits) | Distribution |
| Financial | Payment reference numbers, transaction amounts | Royalty processing |
| Usage | Login timestamps, upload activity, fanlink clicks | Platform analytics |
| Technical | Browser type, operating system, Cloudflare region | Security, fraud prevention |

**We do NOT store:** Raw IP addresses (we store only SHA-256 hashes), full payment card numbers, or government ID numbers.

---

## 3. HOW WE USE YOUR DATA

- **Provide Services:** Distribute your music, process royalties, generate fanlinks
- **Communications:** Send release updates, payment notifications, admin alerts
- **Security:** Detect fraud, enforce rate limits, verify webhook signatures
- **Legal Compliance:** Maintain audit logs as required by Nigerian law
- **Analytics:** Understand platform usage to improve the service

---

## 4. DATA SHARING

We share data only with:
- **Once.app:** Distribution metadata (DDEX ERN 4.3 format) — no personal data beyond artist credits
- **SquadCo:** Payment reference and email for transaction processing
- **Supabase:** Encrypted database storage (data does not leave your region)
- **Resend:** Email address for transactional emails
- **Cloudflare:** Technical hosting and DDoS protection

We do **not** sell your data to third parties.

---

## 5. DATA RETENTION

| Data Type | Retention |
|-----------|-----------|
| Account data | Duration of account + 7 years (legal requirement) |
| Audit logs | 7 years (immutable) |
| Payment records | 7 years (Nigerian FIRS requirement) |
| Application records | Indefinite (contract compliance) |
| Session tokens | 7 days (auto-expire) |
| Magic link tokens | 15 minutes (auto-expire) |

---

## 6. YOUR RIGHTS

Under applicable Nigerian data protection law (NDPA 2023), you have the right to:
- **Access** your personal data
- **Correct** inaccurate data
- **Delete** your account and associated data (subject to legal retention obligations)
- **Export** your data in machine-readable format
- **Object** to processing for marketing purposes

To exercise these rights, email: privacy@rald.cloud

---

## 7. SECURITY

- All data transmitted over HTTPS (TLS 1.3)
- Database encrypted at rest (Supabase AES-256)
- Passwords not stored (WorkOS SSO or magic link only)
- Admin actions require multi-factor authentication
- All admin access logged to immutable audit trail
- Webhook signatures verified with HMAC-SHA256/SHA512

---

## 8. COOKIES

We use session cookies only. No third-party tracking cookies. Cookie properties: HttpOnly, Secure, SameSite=None, Domain=.manilla.rald.cloud.

---

## 9. CHANGES

We will notify artists of material changes via email at least 14 days before they take effect.

---

## 10. CONTACT

**Data Protection Officer:** privacy@rald.cloud
**General:** support@rald.cloud
**Address:** LILCKY STUDIO LIMITED, Nigeria

---

*Last updated: 2026-06-01*
