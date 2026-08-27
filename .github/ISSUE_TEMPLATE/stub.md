---
name: Stub
about: It behaves as built, and what is built is deliberately less than intended.
title: ''
type: Stub
---

<!--
  A stub is not a bug. Nothing is broken; something is absent, on purpose.
  If a reader of the code would think "this looks wrong", this is the entry
  that tells them it was a decision.

  Set the issue type to Stub. Leave KI-Number blank — `gh_issues.py backfill`
  assigns it. Cite as [ADR 0045] or [KI-029]; never write a path.
-->

**Intended.** What the design says should exist, and where it says so. A stub is measured against
a design, so name it.

**Actual.** What is built instead, and what is simply absent. Name the file and the symbol, so
someone reading that code finds this entry rather than assuming a mistake.

**Why deferred.** What made this the right amount to build for now — sequencing, a missing
prerequisite, a decision not yet taken. If it is blocked, name what on.

**Done looks like.** The rest of the design, stated concretely enough to build.

<!--
  Resolution goes in a note, not in the text above:
    python docs/tools/gh_issues.py note KI-NNN --body "Resolved by ..."
-->
