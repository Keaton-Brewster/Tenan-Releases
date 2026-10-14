# Tenan — Releases

This repository hosts compiled releases of **Tenan**, a local desktop app for managing multiple Microsoft 365 client tenants from a single interface — built for Power Platform consultants.

> Source code is maintained in a private repository. This repo distributes signed installers, and is where you report bugs.

---

## Download

Go to the [**Releases**](https://github.com/Keaton-Brewster/Tenan-Releases/releases) tab and download the latest `Tenan_x.x.x_x64-setup.exe`.

## Auto-updates

Installed copies of Tenan check for new releases automatically. When an update is available, a toast notification appears in the app — click **Install & Restart** to apply it.

---

## About Tenan

- Manage multiple Microsoft 365 / Power Platform tenants from one place
- Environment health, Dataverse data browsing, security analysis, Power Automate inspection and ALM comparison across environments
- **Reeve**, an AI assistant that works in your tenants with your own Azure OpenAI deployment
- Credentials and tokens stay local — stored in Windows Credential Manager, never in the cloud. Your clients' tenant data never passes through our servers.
- Built with [Tauri](https://tauri.app) (Rust + React)

---

## Free and Firm

**Free** — for individual consultants, and teams of up to 3 people. Everyone who signs in from the same Microsoft Entra tenant counts as one team; personal Microsoft accounts are always individuals. Includes:
- unlimited client profiles and tenants
- environment health, Data, Security and Processes
- ALM solution comparison
- Reeve, with your own Azure OpenAI deployment
- the editor, terminal and source control

**Firm** — for consultancies, priced per active person, with unlimited client tenants. Everything in Free, plus:
- organization-wide Reeve settings: a shared Azure OpenAI deployment, a chat-history policy, and who can use Reeve
- client access controls
- Remote Reeve, from your phone
- white-glove support

More Firm features are coming: a portfolio view across every client, scheduled health checks and alerts, client health reports, Reeve audit export, and a shared team library.

Interested in Firm? Email [keaton@millwright.solutions](mailto:keaton@millwright.solutions?subject=Tenan%20Firm%20plan).

---

## Support

See [SUPPORT.md](SUPPORT.md). In short: on Free, [open a bug report](https://github.com/Keaton-Brewster/Tenan-Releases/issues/new?template=bug_report.yml) (or use **Settings → Plan & Support → Report a bug** in the app), handled on a best-effort basis. This repository is public, so **never include client data in an issue.**

---

## Security

All releases are signed with a Tauri keypair. The installer signature is verified automatically by the built-in updater before any update is applied.

Windows SmartScreen may show an "unrecognized app" warning on first install — this is expected for apps without an Authenticode certificate. Click **More info → Run anyway** to proceed.

---

## Terms, privacy and licensing

- [Terms of Use](TERMS.md)
- [Privacy Policy](PRIVACY.md)
- [License Agreement](LICENSE) — Tenan is proprietary software, licensed by Millwright.

Licensing questions: [keaton@millwright.solutions](mailto:keaton@millwright.solutions).
