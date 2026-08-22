---
name: Feature
about: It behaves as intended, and we have since thought of better.
title: ''
---

<!--
  A feature is not a stub. Nothing is missing against the design — the design
  itself is what would change. Usually raised by playing the thing.

  Recording one here does NOT schedule it. It records that the idea was had and
  knowingly not taken up, so it does not have to be had again.

  Set the issue type to Feature. Leave KI-Number blank — `gh_issues.py backfill`
  assigns it. Cite as [ADR 0045] or [KI-029]; never write a path.
-->

**Wanted.** What would be better, and what prompted it — playing it, a beta round, a support
question. "Wanted" rather than "Intended" on purpose: there is no design this falls short of.

**Actual.** What happens today. Often this reads as perfectly reasonable, which is the point —
say why it is nonetheless worse than it could be.

**Why deferred.** Why this is not being built. Scope, sequencing, or simply that it is an idea
rather than a commitment.

**Done looks like.** What would change, and what would have to be decided first. If this needs a
decision before it needs code, say so — that is an ADR, not a commit.

<!--
  Resolution goes in a note, not in the text above:
    python docs/tools/gh_issues.py note KI-NNN --body "Resolved by ..."
-->
