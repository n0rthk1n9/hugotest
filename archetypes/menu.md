---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: false
summary: "Brief description for menu listings."
params:
  price: "$0"
  tags: []
---

Full description of the pizza. List key ingredients and any dietary notes (e.g., *Vegetarian*, *Spicy*).
