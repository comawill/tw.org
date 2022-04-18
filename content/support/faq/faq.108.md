---
title: "Taskwarrior - FAQ"
---

Q: How can I assign a task to a project while creating the task?
For instance I recently did :

```
$ task project:todaysproject add pick up laundry
```

however when I list all tasks it shows that the task is not assigned to a project.

A: The "project:todaysproject", when it appears before the "add" command is ignored.
Try putting the command first:

```
$ task add project:todaysproject pick up laundry
```
