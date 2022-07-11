---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
url: /{{ .Name }}/
image: /images/{{ .Name }}/
draft: false
categories:
  - default
tags:
  - default
---
<!--more-->

<!--
```bash
echo "Hello World"
```
-->
