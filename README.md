# NICVTC CRM

## A simple admissions workspace for vocational training institutes

NICVTC CRM is a self-hosted institute management application designed for
small vocational training centres that still manage admissions with paper
forms, notebooks, and spreadsheets.

It gives staff one clear workspace to:

- Register and search students
- Store paper admission-form details
- Manage courses, durations, and fee structures
- Upload scanned admission forms or photos
- Review OCR/AI-extracted information before saving
- Keep a lightweight daily admissions ledger

The interface is intentionally simple and practical: large fields, clear
actions, minimal steps, and no unnecessary attendance or academic modules.

## How it works

1. Staff open the admissions workspace.
2. They enter a student manually or upload a scanned admission form.
3. OCR and optional AI extraction suggest the form fields.
4. Staff review and correct the suggested values.
5. The approved information becomes a searchable student record.
6. Courses and fee details remain available alongside the student records.

Nothing extracted from a document is saved as a student automatically. A staff
member always reviews the information first.

## Designed for self-hosting

The application is intended to run on a private home server, office server,
or homelab. It can be deployed with Docker and PostgreSQL, then accessed by
staff through a browser on the local network or through a protected reverse
proxy.

This approach keeps institute data under the owner’s control and avoids
depending on a hosted SaaS platform.

## Privacy and safety

- No institute data is included in this public repository.
- No passwords, API keys, database files, or uploaded documents are included.
- OCR/AI providers are optional and configurable.
- Manual entry remains available when OCR or AI is unavailable.
- The production deployment should be restricted to a trusted network or VPN.

## Project status

NICVTC CRM is being developed as a practical MVP for real-world institute
admission workflows. The private implementation repository contains the
application and deployment configuration. This public repository is the
project overview and public-facing documentation.

## Live demo

The live self-hosted deployment link will be added here after deployment.

> The demo may require authentication and may only be available to authorised
> users. Please do not submit real personal information to a public demo.

## Planned improvements

- User login and role-based access
- Student profile editing and printable admission summaries
- Safer backup and restore tools
- More OCR provider integrations
- Audit history for important changes
- Better reporting for admissions and fee collections

## Repository note

This public repository intentionally contains documentation only. The complete
private application source is maintained separately for deployment and
continued development.
