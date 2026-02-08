---
name: Pages created
about: Monthly creation is done
title: "It's done at: {{ date | date('MMMM Do') }} X"
labels:
  - "Creation 💬"
---
# Header, {{ date | date('MMM Do') }}

body1
body2

title: "It's done at: {{ date | date('MMMM Do') }} X {{ date | date('%FT%T%:z') }}"
