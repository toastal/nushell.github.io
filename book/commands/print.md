---
title: print
version: 0.64.0
usage: |
  Prints the values given
---

# <code>{{ $frontmatter.title }}</code>

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> print ...rest --no-newline```

## Parameters

 -  `...rest`: the values to print
 -  `--no-newline`: print without inserting a newline for the line ending

## Examples

Print 'hello world'
```shell
> print "hello world"
```

Print the sum of 2 and 3
```shell
> print (2 + 3)
```
