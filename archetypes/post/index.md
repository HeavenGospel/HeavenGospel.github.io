---
title: "{{ replace .File.ContentBaseName "-" " " | humanize | title }}"
description: balabala
slug: "{{ .Name }}"
date: {{ .Date | time.Format "2006-01-02"}}
categories:
    - Category
tags:
    - Tag1
    - Tag2
    - Tag3
math: true
# weight: 1
# image: 1.jpg
---
