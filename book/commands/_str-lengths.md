---
title: str-lengths
version: 0.64.0
usage: |
  Get lengths of all strings
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> str-lengths ```

## Examples

Returns string lengths
```shell
> [a ab abc] | to-df | str-lengths
```
