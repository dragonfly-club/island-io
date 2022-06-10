---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
subtitle: "Hello World"
slug: "hello-world"
author: holger
resources:
- name: hero
  src: hero.jpg
categories:
- Blog
tags:
- mastodon
- update
---

{{< mastodon "https://mastodon.social/@natecull/100109432395996840" >}}

