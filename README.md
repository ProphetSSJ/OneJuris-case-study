# Trademark docket system: OneJuris PC

Software contract by Ayush Arbind Bhardwaj for a California trademark law firm. July 2026 - present.

I gathered 19 requirements, scoped the application, directed development with substantial AI coding assistance, reviewed and tested outputs, handled security remediation, wrote documentation, and managed delivery. The system has been live in production since the firm-wide cutover on 7 October 2026, on an Ubuntu server behind Nginx over HTTPS. I run its staged releases, nightly USPTO refreshes, backups and security patching.

Python/FastAPI, SQLite WAL, and vanilla JavaScript consolidate spreadsheet records into a searchable docket. Features include USPTO TSDR integration, deadline tracking, access roles, preview-before-commit imports, billing workflows, reminders, and backups.

## Highlights

- A multi-thousand-matter docket with calculated statutory deadlines.
- Production cutover from 26 firm spreadsheets using three-way reconciliation, so late sheet edits were never silently overwritten.
- 700+ automated checks, including end-to-end tests of the real frontend against the real API.
- Nine findings remediated during a security review.
- Migration discrepancies and potentially lapsed deadlines flagged for attorney review.

Client source ownership was transferred to OneJuris. This case study contains no application source, database, credentials, client records, or internal screenshots. It is not legal guidance.
