---
title: n-unique
version: 0.64.0
usage: |
  Counts unique values
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> n-unique ```

## Examples

Counts unique values
```shell
> [1 1 2 2 3 3 4] | to-df | n-unique
```
