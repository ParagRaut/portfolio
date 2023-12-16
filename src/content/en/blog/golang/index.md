---
title: "Hello World with Golang"
date: 2020-11-01T15:38:46+01:00
tags: ["code", "golang"]
series: ["learning"]
draft: false
---

Hello world is first stepping stone while learning any new computer language.
Writing hello world in go was very exciting for me as I tried my hand for the first time in systems programming language

![GopherInWonderland](go-gopher.jpg)

Code block:

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```
&nbsp;
##### So here is the summary, in Golang you always need to know few things:
  1. First line of program is always package declaration
  2. Import go modules/packages to do basic readily available things like printing and scanning, make http requests
  3. func main() every program's entry point 

  As easy as it looks to me Golang felt like the best gateway to systems programming