---
title: "{{ replace .Name "-" " " | title }}"
date: {{ dateFormat "2006-01-02" .Date }}
year: "{{ dateFormat "2006" .Date }}"
draft: true
---
