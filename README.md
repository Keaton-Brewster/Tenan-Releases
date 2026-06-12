# Tenan — Releases

This repository hosts compiled releases of **Tenan**, a local desktop app for managing multiple Microsoft 365 client tenants from a single interface — built for Power Platform consultants.

> Source code is maintained in a private repository. This repo exists solely to distribute signed installers.

---

## Download

Go to the [**Releases**](https://github.com/Keaton-Brewster/Tenan-Releases/releases) tab and download the latest `Tenan_x.x.x_x64-setup.exe`.

## Auto-updates

Installed copies of Tenan check for new releases automatically. When an update is available, a toast notification appears in the app — click **Install & Restart** to apply it.

---

## About Tenan

- Manage multiple Microsoft 365 / Power Platform tenants from one place
- Credentials and tokens stay local — stored in Windows Credential Manager, never in the cloud
- Built with [Tauri](https://tauri.app) (Rust + React)

---

## Security

All releases are signed with a Tauri keypair. The installer signature is verified automatically by the built-in updater before any update is applied.

Windows SmartScreen may show an "unrecognized app" warning on first install — this is expected for apps without an Authenticode certificate. Click **More info → Run anyway** to proceed.

---

## Licensing

Tenan is proprietary software. To inquire about licensing, please email [keaton.brewster@gmail.com](mailto:keaton.brewster@gmail.com).
