---
title: get-minute
version: 0.64.0
usage: |
  Gets minute from date
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> get-minute ```

## Examples

Returns minute from a date
```shell
> let dt = ('2020-08-04T16:39:18+00:00' | into datetime -z 'UTC');
    let df = ([$dt $dt] | to-df);
    $df | get-minute
```
