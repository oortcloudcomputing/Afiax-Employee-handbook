# Oortcloud Computing Cloud Sandbox

## Overview

Afiax runs its infrastructure on **Oortcloud Computing**, our parent company's cloud platform. The Oortcloud Sandbox environment is available to all engineers for personal development, testing, and learning purposes.

Resources in the sandbox are automatically cleaned up every Friday evening to keep costs down.

## Access

1. Request access by messaging the `#cop-cloud` Slack channel with your name and team.
2. The DevOps team will provision your sandbox account and email your credentials.
3. Follow the setup instructions in the email and enable MFA before first login.
4. Log in via the Oortcloud internal portal — details provided with your credentials.

## Usage Policy

- Sandbox environments are for **non-production** use only — testing, learning, and short-lived experiments.
- Do not store real patient data or any production secrets in the sandbox.
- All resources are destroyed every Friday at 18:00 EAT — do not rely on sandbox for persistent storage.
- Tag your resources with your name and project so the team can identify them.

## CLI Access

The DevOps team maintains CLI tooling and configuration guides in the [Oortcloud DevOps repo](https://github.com/oortcloudcomputing). Request access via `#cop-cloud` if you don't already have it.

## Security

- The sandbox is isolated from all production systems by network policy.
- IAM user creation is disabled in the sandbox; all access is via SSO using your Afiax email.
- Any security concerns should be raised immediately in `#security` or by emailing [security@afiax.africa](mailto:security@afiax.africa).

## Admin

Sandbox administration is handled by the `@sandbox-admins` group. Contact them in `#cop-cloud` for:
- Adding or removing users
- Adjusting resource quotas
- Investigating cleanup issues
