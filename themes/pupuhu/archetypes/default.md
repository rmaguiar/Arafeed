---
draft: true
date: {{ .Date }}
title: "{{ replace .TranslationBaseName "-" " " | title }}"
slug: {{ .BaseFileName }}

tags:
    - Python

categories:
    - Pemrograman

image:
    alt: "{{ replace .TranslationBaseName "-" " " | title }}"
    src: https://lorempixel.com/720/380
    thumblink: https://lorempixel.com/320/160
---
