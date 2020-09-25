---
layout: essay
type: essay
title: Blemish Proportions
# All dates must be YYYY-MM-DD format!
date: 2020-09-24
labels:
  - Software Engineering
  - Coding Standards
---

<img src="../images/flowchart.jpg">

### Nice Windows

A perhaps underacknowledged benefit of well-structured, highly readable codebases is that contributors encountering a clean codebase will know that any sloppiness on their part will stick out.  That is, “making a mess where there wasn’t one” tends to be harder to justify than “leaving just a little bit more mess; nobody will notice.”  This idea mirrors the “broken window” theory that New York City politicians and law enforcement utilized in the 1980s to decrease crime the area.  They contended that a potential criminal who sees a broken window will take it as a sign that their misdeeds would go unnoticed.  Thus, city officials poured resources into, among other things, removing graffiti, particularly in the subways; subsequently, crime fell dramatically.  Although some dismiss the program’s true causal influence in this trend, many believe it to be the primary catalyst of a more peaceful era.  I personally find this notion to endorse a norm of respectably clean codebases; the “windows” don’t have to be spotless, but being free of cracks or unsightly amounts of dirt will go a long way in deterring mischief (in a software-writing context, laziness and sloppiness).  As the justifiability of a blemish depends on its proportion added to the existing mess, cleanliness deters micro-messes.

### On the Ground

To follow this analogy, ESLint guides us to keep our “windows” not necessarily spotless, but damage-free and transparent.  Sometimes, letting temporary variable declaration use let rather than const will be inconsequential; however, in other circumstances, it contribute to nebulous bugs causing serious delays.  Granted, in real life, extra time for "cleanliness" in the face of deadlines shouldn't take precendence over performance, but the long-term attitude of keeping a "clean city" will save much grief in the long run.
