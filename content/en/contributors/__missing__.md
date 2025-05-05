---
title:  Missing
shortTitle:  __MISSING__
aliases:
  - "Not Committed Yet"
---

This means the documentation software could not infer the contributor from the header and source files. This is mostly fine for external libraries but your code shouldn't be missing authors...

Currently, the only mode of inferring authors is through Git author lookups of specific ranges of lines. If you are documenting a project that is not managed by Git, you can either:
- Initialize Git, then commit everything if you are the sole developer of your project.
- Or, Open a documentation issue, mentioning your specific use case.

{{% pageinfo %}}
If you build the documentation locally, you may get missing authors for lines that are not committed yet!
{{% /pageinfo %}}
