# Tenan — Terms of Use

**Effective date:** _[set on publication]_
**Provided by:** Millwright, Jackson County, Missouri, United States ("Millwright", "we", "us")
**Applies to:** the Tenan desktop application ("Tenan", "the application", "the software"), the Tenan account service it signs in to, and anyone who installs or uses them ("you").

These terms sit alongside the **Tenan Proprietary Software License Agreement** (the `LICENSE` file distributed with Tenan). The License Agreement covers what you may do with the software itself; these terms cover the plans, your account, the AI features and support. If the two conflict, the License Agreement governs. How we handle personal information is described in the **Tenan Privacy Policy**.

**Meaning of "data":** in these terms, **"data" is defined broadly**. It means any data, content and records **and** all **configuration**, including environment, tenant, security and application configuration such as security roles, permissions, cloud flows, connections, solutions, customizations, settings and metadata, that is accessed, created, modified or deleted through Tenan. Every reference to "data" below carries this meaning, so any disclaimer of liability for "loss of data" applies equally to loss, corruption or unwanted change of configuration.

> These terms are written in plain language and are intended to be legally operative. They are **not a substitute for legal advice**, and should be reviewed by counsel before they are relied on.

---

## 1. Acceptance

By installing, signing in to or using Tenan, you agree to these terms. If you use Tenan on behalf of an organization, you accept them on that organization's behalf and confirm you have authority to do so. **If you do not agree, do not install or use Tenan.**

---

## 2. What Tenan is

Tenan is a **local desktop application** for managing Microsoft 365 and Power Platform environments. It runs on your machine, keeps the tenant data it caches in an encrypted local database, stores credentials only in your operating system's keychain, and talks directly to Microsoft's APIs and, if you enable it, to the AI service you configure (see Section 6).

To use Tenan you sign in with a Microsoft account. That sign-in goes to the **Tenan account service**, which we run. It confirms your access, determines your plan, stores your organization's Tenan settings, and relays Remote Reeve connections if you turn that on. Your clients' tenant data does not pass through it. The Privacy Policy lists exactly what it stores.

---

## 3. Plans

### Free

Tenan is free for:
- **individuals**, and
- **organizations of up to 3 active people.**

An **organization** is everyone who signs in to Tenan with an account from the same **Microsoft Entra tenant**. Personal Microsoft accounts are individuals and never form an organization. A person is **active** if they have used Tenan in the last 30 days.

Free includes Tenan's core features. It does not include the Firm features listed below, and support is limited to bug reports (Section 8).

### Firm

**Firm** is a paid subscription for organizations, priced per managed client tenant. It includes everything in Free, plus:
- organization-wide Reeve settings
- client access controls
- Remote Reeve
- further Firm features as we release them
- white-glove support

Prices, billing and any commitments are set out in your order or subscription terms. We may also grant Firm without charge, for example to design partners. A grant lasts for the period we tell you, or until we end it with notice.

### When an organization outgrows Free

If an organization on Free has more than 3 active people, Tenan will tell its owners and administrators. After a grace period, people beyond the first 3 (by the date they joined) may be unable to sign in until the organization moves to Firm or drops back to 3 active people. Nobody loses their local data because of this.

### Changes to plans

We may change what each plan includes, or the Free limits, from time to time. We'll give reasonable notice of changes that reduce what your plan includes, and changes to a paid subscription follow its terms.

---

## 4. Using Tenan for client work

You may use Tenan to deliver consulting, implementation, support or managed services to **your own clients**, against tenants and environments you are authorized to access. You may not offer Tenan itself to anyone else as a hosted or shared service, or let your clients operate your copy of it. Section 2 of the License Agreement sets out the full restrictions.

---

## 5. Your account

- You are responsible for the Microsoft accounts you use with Tenan and for keeping the devices Tenan runs on secure.
- If you are an owner or administrator of a Tenan organization, you control its Tenan settings, and you can see who its members are and when they last used Tenan.
- We may suspend or block an account or organization that breaches these terms or the License Agreement, or whose use puts others or the service at risk.

---

## 6. AI features, and your responsibility to supervise them

Tenan includes **optional, AI-assisted features**, including the Reeve assistant (the "AI assistant"). You should understand and accept the following before using them:

- **AI can be wrong.** AI-generated output, including answers, summaries, queries, code and proposed actions, may be **inaccurate, incomplete, outdated or fabricated**. This is an inherent characteristic of AI systems, not a defect in Tenan.
- **You must verify everything.** You are responsible for **independently reviewing and verifying any AI output before relying on it or acting on it.** Do not treat AI suggestions as authoritative.
- **You choose how much the AI may do without asking.** In its default mode, Tenan asks for your confirmation before the AI assistant writes, modifies or deletes anything, or runs a command. Other modes let some or all of those actions run without asking. **Confirming an action, and choosing a mode that doesn't ask, are your decisions and your responsibility.** Confirmation is a safeguard, not a guarantee that an action is correct or safe.
- **Don't run the AI unsupervised on data you can't afford to lose.** Using the AI assistant on production data, security configuration or other material systems without human supervision and verification is done **entirely at your own risk.**
- **Content goes to the AI service you configure.** When you use the AI assistant, what you give it, and data it reads to answer you, is sent to the AI service configured for you (your own, or your organization's). That service's terms apply. **Do not use the AI assistant with data you are not permitted to send to that service.**
- **AI features are optional.** They are off until you enable them, and can be disabled.

---

## 7. Data, credentials and security

- Tenan works with the **privileges of the account you sign in with**. Use appropriately scoped (least-privilege) accounts.
- You are responsible for revoking Tenan's access, and offboarding accounts, when an engagement ends or access is no longer appropriate.
- You are responsible for maintaining **independent backups** of any data you act on through Tenan.

---

## 8. Support

- **Free:** you can report bugs on the public Tenan-Releases GitHub repository. Reports are handled on a best-effort basis, with no response time and no guarantee of a fix. That repository is public, so **never include client data in a report.**
- **Firm:** support as described in your subscription, including onboarding and priority handling.

---

## 9. No warranty

Tenan is provided **"AS IS" and "AS AVAILABLE", without warranty of any kind**, whether express, implied or statutory. To the maximum extent permitted by law, all warranties, including merchantability, fitness for a particular purpose, accuracy, reliability, non-infringement and uninterrupted or error-free operation, are disclaimed. No advice or information obtained from Tenan or its AI features creates any warranty. The Tenan account service may be unavailable at times, and Tenan may then be unable to sign in.

---

## 10. Limitation of liability

**To the maximum extent permitted by applicable law:**

- Millwright, and anyone providing Tenan on its behalf, **shall not be liable for any loss of data (as broadly defined above, including configuration), data or configuration corruption, business interruption, or any indirect, incidental, special, consequential or punitive damages** arising out of or related to your use of (or inability to use) Tenan.
- This expressly includes, **without limitation, any loss, corruption or damage to data resulting from AI-generated output, or from unsupervised, unverified or unconfirmed use of the AI features**, including in modes that run actions without asking. You assume full responsibility for supervising the AI assistant and for verifying its output and actions.
- Liability for loss of data that adequate backups would have prevented is excluded.
- Our total liability is limited as set out in Section 7 of the License Agreement.

Some jurisdictions do not allow certain limitations; where that applies, the above limitations apply to the fullest extent permitted.

---

## 11. Acceptable use

You agree to use Tenan only against tenants and environments **you are authorized to access**, in compliance with all applicable agreements, policies and laws. You will not use Tenan to attempt to exceed your authorized privileges, circumvent security controls, or access data you are not entitled to. You will not attempt to get around plan limits, for example by creating accounts to avoid the Free limit for your organization.

---

## 12. Ending your use

You can stop using Tenan at any time, and ask us to delete your Tenan account (see the Privacy Policy). We may end or suspend your access as described in Section 5 and in the License Agreement. Sections 6, 9, 10 and 13 continue to apply after your use ends.

---

## 13. Changes, governing law and contact

- **Changes.** We may update these terms. We'll give reasonable notice of material changes, for example in the app or on the Tenan-Releases repository. Continued use after a change takes effect means you accept the updated terms.
- **Severability.** If any provision is held unenforceable, the rest stay in effect.
- **Governing law.** These terms are governed by the laws of the State of Missouri, United States, without regard to its conflict-of-laws rules. The exclusive venue for any dispute is the state and federal courts located in Jackson County, Missouri.
- **Contact:** keaton.brewster@millwright.solutions
