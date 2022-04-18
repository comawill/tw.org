---
title: "Taskwarrior - FAQ"
---

Q: How to annotate to a project?
Can I add an annotation to an entire project instead of its tasks individually?

A: You can add the same annotation to each task in a project like this:

$ task project:WORK annotate ...
But you cannot directly annotate the project, because it does not exist - it's just an attribute of tasks.
The project is itself not an entity.

