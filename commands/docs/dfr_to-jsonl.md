---
title: dfr to-jsonl
categories: |
  dataframe
version: 0.83.0
dataframe: |
  Saves dataframe to a JSON lines file.
usage: |
  Saves dataframe to a JSON lines file.
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> dfr to-jsonl (file)```

## Parameters

 -  `file`: file path to save dataframe

## Examples

Saves dataframe to JSON lines file
```shell
> [[a b]; [1 2] [3 4]] | dfr into-df | dfr to-jsonl test.jsonl

```