# PHI Safety Checklist

Use this before sharing any healthcare AI demo, notebook, screenshot, prompt, or repository publicly.

## Data

- Confirm all examples are synthetic or fully de-identified.
- Remove names, exact contact details, account IDs, addresses, and direct identifiers.
- Avoid rare combinations that could re-identify someone.
- Replace real dates with relative timing or synthetic dates.

## Systems

- Do not include credentials, tokens, production URLs, hidden endpoints, or vendor exports.
- Do not publish screenshots from live clinical systems.
- Do not publish internal operating procedures that expose private workflows.

## Review

- Run keyword scans for identifiers and secrets.
- Review examples manually as if an outsider were trying to identify the source.
- Add a clear synthetic-data disclaimer.
- Keep a private source of truth separate from public demos.
