---
title: str capitalize
version: 0.64.0
usage: |
  Capitalize first letter of text
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> str capitalize ...rest```

## Parameters

 -  `...rest`: optionally capitalize text by column paths

## Examples

Capitalize contents
```shell
> 'good day' | str capitalize
```

Capitalize contents
```shell
> 'anton' | str capitalize
```

Capitalize a column in a table
```shell
> [[lang, gems]; [nu_test, 100]] | str capitalize lang
```
