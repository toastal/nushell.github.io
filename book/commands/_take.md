---
title: take
version: 0.64.0
usage: |
  Creates new dataframe using the given indices
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> take (indices)```

## Parameters

 -  `indices`: list of indices used to take data

## Examples

Takes selected rows from dataframe
```shell
> let df = ([[a b]; [4 1] [5 2] [4 3]] | to-df);
    let indices = ([0 2] | to-df);
    $df | take $indices
```

Takes selected rows from series
```shell
> let series = ([4 1 5 2 4 3] | to-df);
    let indices = ([0 2] | to-df);
    $series | take $indices
```
