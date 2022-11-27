---
title: "First Taste of Generics in Go"
layout: post
date: 2020-07-19 12:15
tag: [go, programming]
category: blog
author: cedrickchee
externalLink: false
---

This [friendly, down-to-earth tutorial](https://bitfieldconsulting.com/golang/generics) explains what generic functions and types are, why we need them, how they work in Go, and where we can use them.

## Generic functions in Go

```go
func PrintAnything(type T)(thing T) {
}

func main() {
    PrintAnything(int)(99)
}
```
