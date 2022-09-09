---
title: "Taskwarrior - FAQ"
---

Q: Filter only pending tasks

I thought about using a virtual tag, but there is nothing like `+PENDING`.

I have lots of recurring tasks that I want to delete in batch, but `task &lt;taskname&gt;` returns the completed ones, too and I don’t want to delete these.

A: A `+PENDING` virtual tag is a good idea. It would make a nice feature request.

A: Please try

```
task status:pending all
```

A: It is worth noting that most reports already have a filter that already includes `status:pending`, but the `all` report used here as an example has no filter, which makes it useful as an example like this.
