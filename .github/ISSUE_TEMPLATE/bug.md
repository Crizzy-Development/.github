---
name: Bug
about: It behaves wrongly. Someone could hit it.
title: ''
---

<!--
  Set the issue type to Bug, and leave KI-Number blank — it is assigned by
  `gh_issues.py backfill` on the next sync. Never type one yourself.

  Cite other work as [ADR 0045] or [KI-029], with or without the hyphen.
  Never write a relative path: the mirror computes it.

  These comments do not render. Delete them or leave them.
-->

**Intended.** What the code or the design says should happen, and where that is written down.

**Actual.** What happens instead — precisely enough that a reader can see the defect without
reproducing it. Name the file and the symbol.

**Why deferred.** Why this is not being fixed today. "Not blocked, just not worth the turn" is a
real answer; so is "blocked on [KI-029]". Say which, because the two age differently.

**Done looks like.** What would have to be true for this to close. Specific enough that whoever
picks it up is not redesigning it from scratch.

<!--
  When this is resolved, add a NOTE saying what closed it — do not edit the text above.
  The body is the record of what was believed when it was raised.

    python docs/tools/gh_issues.py note KI-NNN --body "Resolved by ..."
-->
