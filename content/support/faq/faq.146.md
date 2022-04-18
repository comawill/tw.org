---
title: "Taskwarrior - FAQ"
---

Q: Modifying End Dates
Some days I forget to log the "extra" tasks that I picked up and completed throughout the day.
The next morning, I  wish to log these tasks as completed on the previous day.
I can'tfigure out the syntax for these.
I have tried 

log "task desc." done.yesterday

complete.yesterday

mod complete.yesterday

 

How do I make this happen?

A: Try this:

$ task log "task desc." end:yesterday
Taskwarrior will warn you, but that is just a warning.

