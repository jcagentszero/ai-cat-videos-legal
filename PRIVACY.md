# Privacy Policy

**Last updated:** February 25, 2026

## 1. Overview

AI Cat Videos ("the Service") is an automated video generation and publishing tool. This policy describes how the Service handles data.

## 2. Data We Collect

The Service collects and stores the following data locally:

- **TikTok OAuth tokens** — Used to authenticate with the TikTok API. Stored locally in `credentials/tiktok_tokens.json` and never shared with third parties.
- **Run history logs** — Records of generated videos, prompts used, and publish status. Stored locally for operational purposes.
- **Generated video files** — Temporarily stored on the local filesystem before publishing. Older files are automatically cleaned up.

## 3. Data We Do Not Collect

- No personal data from end users or viewers is collected
- No analytics or tracking cookies are used
- No data is sold or shared with third parties

## 4. Third-Party Services

The Service sends data to the following third-party services as part of normal operation:

- **Google Cloud (Vertex AI / Veo 3)** — Text prompts are sent to generate videos. Subject to [Google Cloud's Privacy Policy](https://cloud.google.com/terms/cloud-privacy-notice).
- **TikTok Content Posting API** — Generated videos and captions are uploaded for publishing. Subject to [TikTok's Privacy Policy](https://www.tiktok.com/legal/privacy-policy).
- **Anthropic Claude API** — Prompts may be sent to generate video captions. Subject to [Anthropic's Privacy Policy](https://www.anthropic.com/privacy).

## 5. Data Storage and Security

All data is stored locally on the machine running the Service. OAuth credentials are stored in files excluded from version control via `.gitignore`. No data is stored in external databases or cloud storage beyond what the third-party APIs retain per their own policies.

## 6. Data Retention

- OAuth tokens are retained until revoked or expired
- Run history logs are retained indefinitely for operational reference
- Generated videos are automatically deleted after a configurable retention period

## 7. Changes to This Policy

This policy may be updated at any time. Changes will be reflected in the "Last updated" date above.

## 8. Contact

For questions about this privacy policy, open an issue on the project's GitHub repository.
