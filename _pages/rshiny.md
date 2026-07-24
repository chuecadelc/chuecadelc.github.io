---
title: "RShiny Applications"
permalink: /rshiny/
layout: single
---

I build interactive RShiny applications to make complex datasets and research findings accessible to technical and non-technical audiences. Below are some of my published apps.

## SIMD Explorer

An interactive tool for exploring and comparing the Scottish Index of Multiple Deprivation (SIMD) 2016 and 2020 datasets through dynamic visualisations, statistical analysis and interactive mapping.

The latest release introduces a redesigned and modernised interface built with bslib, expanded visualisation and statistical testing capabilities, downloadable datasets and figures, interactive tooltips that tell you about the data zone and council area as you hover over it and Scotland-wide map using Local Authority boundaries. 

The project also incorporates a CI/CD workflow using GitHub Actions, including automated syntax checks, linting and a custom validation R script ensure consistency between the application's UI and server components,.

[Launch App →](https://cchuecadelcerro.shinyapps.io/SIMD-Shiny-App/){: .btn .btn--primary}

[View Code on GitHub →](https://github.com/chuecadelc/ShinySIMD)

---

## DEMED Democracy Explorer

Interactive exploration of V-Dem democracy indicators, developed for the DEMED research project at the University of Glasgow.

[Launch App →](https://shiny.cent.gla.ac.uk/){: .btn .btn--primary}

[View Code on GitHub →](https://github.com/chuecadelc/DEMED-Shiny-App)

{% include base_path %}

{% for post in site.rshiny reversed %}
  {% include archive-single.html %}
{% endfor %}

