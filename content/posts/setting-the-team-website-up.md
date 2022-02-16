---
title: "Setting the Team Website Up"
date: 2022-02-16T22:06:12+03:00
author: "Bayram Kazık"
draft: true
---

The Rapture ROV team website is built using [Hugo](https://gohugo.io) static site generator with [Hyde theme](https://github.com/spf13/hyde). In this blog I will be explaining the why's and how's of this decision.


## Why Hugo?

Hugo is a static site generator written in [Go programming language](https://go.dev) which is well known for its speed and efficiency. Hugo is mostly used for serving content that doesn't get updated often and is especially well suited for blogs. With the wide variety of community themes, Hugo can be used to build and configure a website blazing fast.


## How?
In order to use Hugo, it first needs to be installed for the current platform. The instructions can be found [here](https://gohugo.io/getting-started/installing).

After installing Hugo, a new site can be created with the command;

```sh
hugo new site quickstart
```

Configuration instructions for the website can be found [here](https://gohugo.io/getting-started/configuration).

The Hugo server can be started with the command;

```sh
hugo server -D
```

---

*Author: Bayram Kazık*
