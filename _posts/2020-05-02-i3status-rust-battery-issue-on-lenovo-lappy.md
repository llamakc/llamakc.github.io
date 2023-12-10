---
id: 223
title: 'i3status-rust battery issue on Lenovo lappy'
date: '2020-05-02T12:24:45+00:00'
author: Ken
layout: post
guid: 'https://lifebydictionary.com/?p=223'
categories:
    - Other
---

This works for i3status-rust on my Lenovo Yoga:

 \[\[block\]\] block = “battery”

device = “BAT1”

interval = 60

format = “{percentage}% {time}”

(saved for later when I forget this again)