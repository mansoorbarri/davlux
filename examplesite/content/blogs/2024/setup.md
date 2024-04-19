---
title: "Setup"
date: 2024-03-19
description: "Initial setup for Davlux." 
type: posts
url: "/setup"
---

![](https://raw.githubusercontent.com/mansoorbarri/davlux/main/images/screenshot.png)

A Hugo theme inspired by [Nexxel.dev](https://nexxel.dev)

***Note: all variables in { } should be personalised***

## Prereq 
You should have the following packages install on your system: 
- Git
- Hugo extended
- nodejs *(optional)*

## Setup 
make a new site 
```bash 
hugo new site {sitename}
```

clone the theme 
```bash
git clone https://github.com/mansoorbarri/davlux.git themes/davlux
```

copy `config.toml`
```bash 
cp themes/davlux/examplesite/config.toml . 
```
