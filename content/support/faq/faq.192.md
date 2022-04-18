---
title: "Taskwarrior - FAQ"
---

Q: How do I contribute to documentation?

I would like to contribute a small change to the documentation. Specifically, the change I want to suggest is that the API v1 documentation is still written as if API v2 does not exist yet, so it should be updated to link to the API v2 so that people like me, who come to the page from a Google search, don't get confused by out-of-date information.

In general, how should I go about submitting patches to the documentation? I cannot find a git repository containing the documentation.

A: All our public repositories are listed here: https://github.com/GothenburgBitFactory

Simply clone, modify and send a patch to support@taskwarrior.org.

In this specific example, it the v1 and v2 API should not be distinct, and the documentation on these pages:

    https://taskwarrior.org/docs/hooks.html

    https://taskwarrior.org/docs/hooks2.html

should be merged into one document (hooks.html), and the second URL replaced by a redirect.

