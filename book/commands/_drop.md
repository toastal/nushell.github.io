---
title: drop
version: 0.64.0
usage: |
  Creates a new dataframe by dropping the selected columns
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> drop ...rest```

## Parameters

 -  `...rest`: column names to be dropped

## Examples

drop column a
```shell
> [[a b]; [1 2] [3 4]] | to-df | drop a
```
