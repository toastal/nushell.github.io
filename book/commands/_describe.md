---
title: describe
version: 0.64.0
usage: |
  Describes dataframes numeric columns
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> describe --quantiles```

## Parameters

 -  `--quantiles {table}`: optional quantiles for describe

## Examples

dataframe description
```shell
> [[a b]; [1 1] [1 1]] | to-df | describe
```
