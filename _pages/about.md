---
layout: about
title: About
permalink: /
subtitle: >-
  Robotics researcher | Ph.D. Candidate
  <span class="about-links">
    <a href="/assets/pdf/hanyeol_lee_cv.pdf" target="_blank" rel="noopener noreferrer">CV</a>
    <span aria-hidden="true">·</span>
    <a href="https://scholar.google.com/citations?user=SyxOVcQAAAAJ&amp;hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a>
    <span aria-hidden="true">·</span>
    <a href="https://github.com/Hanyeol-Lee" target="_blank" rel="noopener noreferrer">GitHub</a>
  </span>

profile:
  align: left
  image: profile_crop_v3.jpg
  image_circular: false # crops the image to make it circular

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="about-intro" markdown="1">

I am a Ph.D. candidate in the Department of Aerospace Engineering at Seoul National University (SNU).

My research vision is to enable robotic systems to perceive and understand the world at a semantic level by leveraging diverse sensing modalities, including LiDAR, monocular and stereo vision, event cameras, radar, and IMUs. Toward this goal, I integrate object-level perception with reliable state estimation to develop smarter perception systems for intelligent robots, autonomous vehicles, and aerial platforms.

</div>

<style>
  .post-header .desc {
    font-size: 1.25rem;
    line-height: 1.5;
  }

  .post-header .about-links {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    margin-left: 0.75rem;
    font-size: 0.82em;
    white-space: nowrap;
  }

  .post-header .about-links a {
    font-weight: 500;
  }

  @media (max-width: 576px) {
    .post-header .about-links {
      display: flex;
      margin-top: 0.25rem;
      margin-left: 0;
    }
  }

  .about-intro {
    font-size: 1.05rem;
    line-height: 1.65;
  }

  article > .clearfix + h2 {
    margin-top: 3rem;
  }

  article > .clearfix + h2 a {
    text-transform: capitalize;
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
