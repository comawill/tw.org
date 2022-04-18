---
title: "Taskwarrior - FAQ"
---

Q: Why are virtual tags better than direct attribute comparisons?

(Great question copied from support email)

For example, why should I do this:

$ task +WEEK list
Instead of:

$ task due.after:sow and due.before:eow list
It's shorter, but is it better?

A: It's better because it is fewer character to type, and therefore less prone to error.
But it is identical.
