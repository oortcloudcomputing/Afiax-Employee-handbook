# Welcome Pack

If it's your first day today — we're really glad you're here. Welcome to Afiax.

This guide covers what to expect in your first days and weeks, and gives you a checklist to make sure you're set up and ready to contribute.

## What we'll cover together

Over your first few days and weeks we will introduce:

1. **Mission, [values](about.md#our-values), and platform** — We will walk you through why Afiax exists, what we are building, and how your role connects to improving healthcare across Africa.
2. **Your buddy** — You will be introduced to a colleague who will be your go-to for any questions during your first weeks — from simple things to bigger concerns. The rest of the team is always available too.
3. **[Role expectations](../roles/README.md)** — We will work through what is expected in your specific role over your first month so there are no surprises.
4. **Monthly 1-2-1s** — You will have a monthly career development 1-2-1 with your Line Manager. These sessions are for your progress, your concerns, and identifying where Afiax can support your growth.
5. **Weekly showcases** — Every Friday we run product and engineering showcases. Start by attending; contribute when you are ready; facilitate when you feel confident.
6. **Salary, pension & expenses** — The People team will walk you through how pay, contributions, and expenses work at Afiax.

## Getting Started Checklist

### Everyone

* [ ] Meet your buddy
* [ ] Attend your first career development 1-2-1 to review role expectations
* [ ] Read the [Acceptable Use Policy](../guides/security/acceptable_use_policy.md) and [Bring Your Own Device Policy](../guides/security/bring_your_own_device.md)
* [ ] Ensure any personal devices used for work are secured as per our [BYOD policy](../guides/security/bring_your_own_device.md)
* [ ] Set up your Slack profile — photo, full name, name pronunciation, and pronouns

### Non-Engineers

* [ ] Complete the [GitHub Hello World tutorial](https://docs.github.com/en/get-started/start-your-journey/hello-world) to get comfortable with pull requests and the handbook contribution process

---

## Accounts and Tools

All accounts below will be provisioned for you before your first day. Google Workspace (Docs, Sheets, Drive) is our default for internal documents.

### Everyone

* [ ] **Google Workspace** (Gmail, Drive, Meet) — enable 2FA
* [ ] **GitHub** — enable 2FA; you will be added to the `oortcloudcomputing` org
* [ ] **Slack** — enable 2FA; join your team channels and `#general`, `#announcements`
* [ ] **1Password** — enable 2FA; this is where all shared credentials live
* [ ] **Google Calendar** — accept recurring team meetings and onboarding sessions

### Engineers

* [ ] **Oortcloud** — request sandbox access in `#cop-cloud` on Slack
* [ ] **GitHub — Afiax repos** — confirm you have access to the platform monorepo
* [ ] **Medplum local environment** — follow the [dev setup guide](https://github.com/oortcloudcomputing) (linked from `#engineering`)

### Health Informatics & Clinical Partnerships

* [ ] **AfyaLink sandbox credentials** — request from the Engineering team
* [ ] **SHA developer portal access** — request from your Line Manager

### Sales, Partnerships & Marketing

* [ ] **HubSpot** — for CRM and pipeline management
* [ ] **LinkedIn Sales Navigator** — for partnership outreach

### Finance & Operations

* [ ] **Xero** — for expense submission and financial reporting

---

## Setting Up Your Machine

### Engineers

Clone the platform repo and follow the README to get your local environment running. The stack is **TypeScript / Node.js / React** on a Medplum FHIR server. You will need:

- Node.js (use `nvm` — version pinned in `.nvmrc`)
- Docker (for running the local FHIR server and dependencies)
- `git` and a configured GitHub SSH key

Ask in `#engineering` on Slack if you hit any setup issues — we keep the dev setup documented and up to date.
