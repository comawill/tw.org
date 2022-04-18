---
title: "Taskwarrior - FAQ"
---

Q: Report sorting on the fly

Is it possible to change the sorting of a report on the fly on the commandline?

A: Yes.
Here is an example for the next report:

$ task rc.report.next.sort=due-,urgency- next

