---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

For a complete and up-to-date list of publications, please see my [Google Scholar profile](https://scholar.google.com/citations?user=SyxOVcQAAAAJ&hl=en).

## Selected publications

<div class="publications">

{% bibliography --query @*[site_visible=true]* %}

</div>

<style>
  .publications h2.bibliography {
    color: var(--global-text-color) !important;
    font-size: 1.4rem;
    font-weight: 600;
    text-align: left !important;
    opacity: 1;
    margin: 2.5rem 0 1rem;
  }

  .publications ol.bibliography li {
    margin-bottom: 2rem;
  }
</style>
