# Getting started with Tenan

This takes about ten minutes.

## 1. Install

1. Download the latest `Tenan_x.x.x_x64-setup.exe` from [Releases](https://github.com/Keaton-Brewster/Tenan-Releases/releases).
2. Run it. Windows may say **"Windows protected your PC"**, because the installer isn't signed with a Windows code-signing certificate yet. Click **More info**, then **Run anyway**.

Tenan updates itself after that. When a new version is out, a notice appears in the app; click **Install & Restart**.

## 2. Sign in

Sign in with your **work** Microsoft account. Everyone who signs in from the same Microsoft tenant joins the same organization automatically, with the same plan. Nothing else is needed.

## 3. Add your first client

1. Click **Add your first client** (later, **New Profile** in the profile switcher) and sign in to the client's tenant with the account you use there.
2. **"Admin consent required"** means the client's tenant only lets users sign in to apps an administrator has approved. Click **Copy admin consent link** and send it to their IT admin. Once they approve it, add the client again.

Each client gets its own tab and its own sign-in, so you can have several open at once.

## 4. Grant Power Automate access (once per client)

Tenan needs a separate permission for flows. Without it, the Flows tab, flow run history and the Portfolio's flow numbers stay empty for that client.

Open the client's **Profile** tab, find **Power Automate (Flow) access**, and click **Grant access**.

## 5. Set up Reeve

Reeve is the AI assistant. It needs an Azure OpenAI or Azure AI Foundry model, set in **File → Settings → Reeve**:

- **Your organization is on Firm:** an organization admin sets the model once, on that same page, and everyone gets it. Members don't need their own key. If Reeve says no model is set, ask your admin.
- **You're on Free, or on your own:** add your own endpoint and key there.

Then open a client and start a Reeve chat. The first time, Reeve asks you to enable it for that client: it sends your questions and the tenant data it reads to your model's endpoint (never to Tenan's servers), so make sure that endpoint is allowed to handle the client's data.

- **Ask** (the default) asks before every change.
- **Auto** asks only before Reeve sends a change to a live tenant.

Every change Reeve makes or tries to make is listed in **Settings → Reeve → Audit Log**.

## 6. Things to try

- **The walkthrough:** it starts after your first client. Replay it any time from **Help → Replay Walkthrough**.
- **Portfolio** (Ctrl+Alt+P, Firm): every client and environment on one screen, worst first. **Refresh all** fetches fresh numbers; click a cell to jump to that client's health tab.
- **Environment health:** connections, flows, capacity and solutions for an environment.
- **ALM:** lines up a solution across Dev, Test and Prod and shows what's missing or behind.
- **Data:** browse any Dataverse table, read-only, and export it to Excel.
- **Security** and **Processes:** role and privilege matrices, and flows drawn as diagrams.

## Known rough edges

- **The Microsoft sign-in window sometimes ignores typing** on a second sign-in in the same session. Click inside the window and it works.
- **"—" in the Portfolio** means Tenan couldn't get that number for that environment, usually because Power Automate access isn't granted yet. It doesn't mean zero.

## Reporting a problem

Use **Settings → About → Report a bug**. It opens a GitHub issue with your Tenan version already filled in. If you can, attach the log file:

```
%LOCALAPPDATA%\net.brewster.tenan\logs\tenan.log
```

This repository is public, so **never put client data in an issue**, including screenshots that show client records.
