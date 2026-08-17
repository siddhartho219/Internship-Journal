# Workflow

1. Brain dump (raw, unfiltered) into Claude Project chat.
2. Claude produces: (A) journal entry, (B) agent instruction block.
3. Paste instruction block to Freebuff/Cursor agent.
4. Agent edits the markdown file only — no git actions.
5. Review the diff yourself before accepting.
6. Commit via GitHub Desktop using conventional commit messages:
   - feat: add journal entry 2026-08-17
   - docs: add August 2026 monthly summary
   - fix: correct date heading in 2026-08.md
7. Push to the public repo.

Monthly (last day of month or first workday of next):
1. Open journal/YYYY-MM.md, copy full contents.
2. Paste into Claude Project, ask for the monthly summary.
3. Claude generates summary + resume bullets → save to summaries/monthly/.
4. Same review → commit → push flow as above.