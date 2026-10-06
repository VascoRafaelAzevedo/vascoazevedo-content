---
title: Markdown cookbook
date: 2026-10-04
minutes: 4
pinned: false
desc: Everything this site renders — links, images, tables and code.
---

This post exercises **everything** the site understands. Bold, *italic* and `inline code` work anywhere, including list items and tables.

Internal links work Obsidian-style: see [[small-projects]] or [[small-projects|the small projects post]]. External links are normal: [@vazevedo5](https://x.com/vazevedo5).

![[cover.svg]]

| Feature | Syntax | Notes |
|:--------|:------:|------:|
| Bold | `**x**` | left |
| Links | `[[x]]` | center |
| Code | `` `x` `` | right |

```python
def greet(name):
    # comment here
    return f"hi {name}!"  # strings stay strings
```

```go
package main

import "fmt"

func main() {
    for i := 0; i < 3; i++ {
        fmt.Println(i) // numbers stay numbers
    }
}
```

```brainfuck
+++[>++++<-] totally unknown languages still render fine
```
