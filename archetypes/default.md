---
title: {{ replace .Name "-" " " | title }}
date: {{ .Date }}
description: ""
draft: true
tags: []
params:
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
