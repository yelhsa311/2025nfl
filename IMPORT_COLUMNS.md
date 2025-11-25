# Import CSV columns

Use these columns when uploading weekly games via the Admin Importer (Games Only):

- **day** – Day label for display (e.g., `Thursday`, `Sunday`, `Monday`).
- **kickoff_date** – Local calendar date for kickoff in `MM/DD/YYYY` (or ISO `YYYY-MM-DD`) format.
- **kickoff_time** – Local kickoff time in `HH:MM` 24-hour or `h:mm AM/PM` format; combined with `kickoff_date`.
- **kickoff_local** (optional) – Single-field alternative to date/time; accepts ISO-like strings (`2025-09-07T13:00`) or `M/D/YY HH:MM am/pm` fallback. Ignored when both date and time are provided.
- **home** – Home team name.
- **away** – Away team name.
- **winner** – Winner slug (`home`, `away`, or `pending`) used to mark game results.

Only the columns above are needed—matchup and pick-related columns were removed from the importer flow.
