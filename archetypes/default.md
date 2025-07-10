---
title: {{ replace .Name "-" " " | title }}
date: {{ .Date }}
draft: true
tags: []
params:
    description: ""
    disableAutoSummary: false
    noindex: false
    image: ""
    hide: []
build:
    list: always
    publishResources: true
    render: always
---

<!--more-->
