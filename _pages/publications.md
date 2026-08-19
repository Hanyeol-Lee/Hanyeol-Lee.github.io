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

  .publications img.preview[src*="T-ase.png"] {
    display: block !important;
    width: 90% !important;
    margin-right: auto !important;
    margin-left: auto !important;
  }

  @media (min-width: 576px) {
    .publications ol.bibliography li .row > .abbr:has(.preview) {
      flex: 0 0 25%;
      max-width: 25%;
    }

    .publications ol.bibliography li .row > .abbr:has(.preview) + [id] {
      flex: 0 0 58.333333%;
      max-width: 58.333333%;
    }
  }
</style>
