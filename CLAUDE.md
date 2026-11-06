# find-the-space — rules for Claude

Football tactics game for kids, served by GitHub Pages from main. **Public repo:** everything committed is public, and every push to main republishes the site. Workspace project: personal.

- **Where it runs:** Cloud is fine for code. Check in a browser locally before pushing.
- **Handovers:** `handovers/<task>.md`.

## Working rules (cloud and Mac)
- **Resuming?** Read the handover for the task first and start from its "Next step".
- **Cloud or Mac?** Say which in one line before real work. Cloud if repo files + remote connectors are enough; Mac if it needs local files, Mac apps or sign-ins. Wrong kind of session → say so.
- **One task, one handover**, updated as work happens (state, decisions, dead ends, Next step). Re-read before overwriting.
- **Every stop ends with a resume prompt.** When work stops unfinished: update the handover (Status, Next step, its Resume prompt section), commit and push it, then give Reuven the resume prompt in a code block (handover path, repo, Cloud/Mac, folder to start in).
- **New unrelated task → offer a new session.** Long session → update the handover, then suggest /compact or a fresh session.
- On the Mac this repo sits in `~/Projects/repos/`; the workspace rules and the cross-project task list are in `~/Projects/CLAUDE.md` and `~/Projects/ACTIVE.md` (repo Reuven93/claude-workspace).
