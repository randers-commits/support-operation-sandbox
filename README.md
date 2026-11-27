# The record

This repository is your support operation, written down. It belongs to
your organisation: Haven proposes changes to it and never writes to main;
the people named in CODEOWNERS approve every change, as themselves, and
merging is what makes a change real.

What lives here:

- `standard/` — your principles, one file each, with the named ways of
  failing them. The standard's version is the count of merged changes to
  this directory; the commit is the real identity.
- `decisions/` — what was chosen, what was rejected, and what would
  change the decision. One file each.
- `readings/` — the maturity reading, kept current by Haven on its own
  branch and frozen per version.
- `haven.yaml` — the operation's configuration. No secrets, ever.
- `CODEOWNERS` — who approves what. GitHub enforces it on every proposal.

Nothing arrives here that a named person did not merge. The first
proposal you see will be the standard itself, drafted from your own
conversations: correcting it and merging it is what makes it v1.

If you ever stop using Haven, this repository keeps working: it is plain
Markdown on your git host, with its full history, approvals, and
readings. Run git clone; that is the exit interview.
