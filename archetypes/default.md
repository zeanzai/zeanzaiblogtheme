---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
description: "Example article description"
thumbnail: "img/placeholder.jpg"
disable_comments: true # Optional, disable Disqus comments if true
authorbox: true # Optional, enable authorbox for specific post
toc: true # Optional, enable Table of Contents for specific post
mathjax: true # Optional, enable MathJax for specific post
categories:
  - "Category 1"
  - "Category 2"
tags:
  - "Test"
  - "Another test"
---
