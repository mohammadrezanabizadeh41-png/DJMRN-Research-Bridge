# DJMRN Research Bridge

**Purpose:** This private GitHub repository is only a mailbox for exchanging *long research prompts and full reports* between the ChatGPT coordinator and ChatGPT Work. It is **not** a code project, automation service, or a second research library.

**Canonical authority:** DJMRN's existing Applied AI Discovery and Capability Index in Notion. The coordinator reviews Work reports and records verified findings there. Work does not edit Notion. General Discovery remains independent.

## Exchange protocol

1. Coordinator creates a numbered file at `requests/Q0001.md` (then Q0002, Q0003, ...). A user's short message to Work, such as **"Read Q0001"**, means: open this repository, read this README and the **actual** file `requests/Q0001.md`. Never guess a request from its code.
2. Work performs the full requested research and writes the **complete** report to the corresponding `responses/A0001.md` (same number). Include research sources, findings, uncertainties, failed searches, and relevant limitations. Work then opens the written response to confirm its contents exist.
3. Work replies in the chat only with the response code, write-confirmation status, and a short summary. The user passes **"A0001 is ready"** to the coordinator.
4. Coordinator reads the actual response from GitHub, independently reviews it, updates the **existing Notion Applied library** as appropriate, verifies Notion persistence, and writes the next request here.
5. Every new request and response is a **new file**. Never overwrite an existing exchange file or use a different number after an uncertain result without checking GitHub first.

## Rules

- Only the coordinator writes **requests/**; only Work writes matching **responses/**. Neither party alters the other's historical messages.
- Keep the entire substantive task/report in GitHub, **not** in the chat; send only short identifiers and status to the user.
- Use Markdown UTF-8. Clearly reference the corresponding request ID in each response.
- No secrets, credentials, private customer data, unnecessary code, repositories, extra services, paid services, account actions, or unrelated GitHub/Notion changes.
- A report is research evidence for review, not an authorization to execute an action or change architecture.
- If GitHub access, read, or write fails: say **BLOCKED**; do not invent successful access or a commit. A temporary Markdown report may be passed manually.
- A one-time **T0001** synthetic test precedes the first real **Q0001** research request.

## Files

- `README.md`: these brief permanent instructions
- `requests/Q####.md`: coordinator-to-Work full research tasks
- `responses/A####.md`: Work-to-coordinator full research reports
- `requests/T0001.md` and `responses/T0001.md`: only the initial connection test

**Repository:** https://github.com/mohammadrezanabizadeh41-png/DJMRN-Research-Bridge
