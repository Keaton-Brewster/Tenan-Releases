# Tenan — Privacy Policy

**Effective date:** _[set on publication]_
**Provided by:** Millwright, Jackson County, Missouri, United States ("Millwright", "we", "us")

This policy explains what information Tenan collects, why, and who can see it. It covers the Tenan desktop application and the **Tenan account service** it signs in to. Tenan is built to keep your clients' data on your own machine, so most of what Tenan handles never reaches us at all.

> This policy is written in plain language. It is **not a substitute for legal advice**, and should be reviewed by counsel before it is relied on.

---

## 1. What stays on your machine

These never reach us. They leave your computer only to go to Microsoft, or to the AI service configured for you when you use the Reeve assistant (Section 3):

- **Your clients' tenant data.** Environments, records, flows, security configuration and everything else Tenan reads from or writes to Microsoft 365, Power Platform and Dataverse. Tenan talks to Microsoft's APIs directly from your machine. Data Tenan caches is kept in an encrypted local database.
- **Credentials and tokens** for your client tenants and AI services. They're stored only in your operating system's keychain.
- **Your conversations with the Reeve assistant, and its memory notes.** These are stored locally.

Tenan has no analytics or tracking.

---

## 2. What the Tenan account service stores

When you sign in, Tenan contacts the account service we run to confirm your access and plan. It stores:

**About you**
- your email address and display name, as provided by your Microsoft sign-in
- your Microsoft account's object ID and Entra tenant ID
- whether your access is allowed or blocked
- when your account was created and when you last used Tenan

**About your organization** (everyone signing in from the same Entra tenant)
- the tenant ID, a name for the organization, and its plan
- each member's role (owner, administrator or member) and when they joined
- the organization's Tenan settings, if its owners or administrators set any: whether Reeve and Remote Reeve are on, a chat-history policy, and an Azure OpenAI endpoint and key. The key is encrypted at rest.

**On the Firm plan only**
- the domain and display name of each client profile your members create, so administrators can manage client access
- optional per-client Azure OpenAI endpoints and keys (encrypted at rest), and which members are allowed each client

**If you turn on Remote Reeve**
- your computer's name, and a public encryption key for it
- for each phone you pair, its name and public key, and pairing and revocation records (pairing codes are stored only as hashes)

Messages between your phone and your desktop pass through our relay, but they are **end-to-end encrypted**: the relay can't read them, and it doesn't store them.

The account service never receives your client tenants' data, your client-tenant tokens, your AI conversations, or Reeve's memory.

---

## 3. Other services Tenan uses

Some features involve third parties directly. Their own privacy policies apply.

- **Microsoft:** for signing in to Tenan, and for everything Tenan does in your tenants.
- **The AI service configured for you** (for example, Azure OpenAI): receives what you give the Reeve assistant and the data it reads to answer you. It's your service, or your organization's, under its own terms.
- **GitHub:** Tenan checks GitHub for updates, which shares your IP address with GitHub. Bug reports you file go to a **public** repository there, so never include client data in them.
- **Hosting:** the account service runs on Microsoft Azure, and its database is hosted by Neon on Amazon Web Services. Both are in the eastern United States (Azure East US 2; AWS US East 1, N. Virginia).

When paid billing launches, payments will be handled by a payment processor, and we'll update this policy before then.

---

## 4. Why we use this information

- to sign you in, confirm your access, and apply your plan, including counting active members toward the Free limit
- to provide your organization's settings to its members, and administration to its owners and administrators
- to run Remote Reeve, if you turn it on
- to contact you about your account, your plan or important changes
- to keep the service secure, and investigate problems

We don't sell your information, use it for advertising, or share it with anyone except as described in this policy or where the law requires it.

---

## 5. Who can see it

- **Millwright**, which operates the service.
- **Your organization's owners and administrators.** They can see members' email addresses, names, roles and when each member last used Tenan, plus the organization's settings. On Firm, they can also see the client profiles members have registered.
- **The providers in Section 3**, as needed to run the service.

---

## 6. Logs and security

The account service keeps operational logs, which can include internal account and organization identifiers, request details such as IP addresses, and error information. We use them to keep the service running and secure, and keep them only as long as that requires. Stored AI keys are encrypted, and access to the service's systems is restricted.

---

## 7. How long we keep it, and your choices

- We keep your account information while your account exists.
- You can ask us for a copy of your information, to correct it, or to delete your account, by emailing the address below. Deleting your account removes your information from the account service. Your organization's settings remain for its other members.
- Data on your own machine is yours to manage. Signing out removes your Tenan sign-in; uninstalling Tenan and removing its data folder and keychain entries removes everything else.

---

## 8. Children

Tenan is a professional tool and isn't intended for anyone under 18.

---

## 9. Changes and contact

We may update this policy. We'll give reasonable notice of material changes, for example in the app or on the Tenan-Releases repository.

Questions or requests: **keaton.brewster@millwright.solutions**
