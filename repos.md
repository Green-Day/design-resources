---
layout: page
title: репозитории
permalink: /repos/

---
<div class="container">
  <div class='row'>
    {% assign sort_order = 'pushed_at' %}
    {% assign filtered_repos = site.github.public_repositories | where:'fork', false | sort: sort_order | reverse %}
    {% for repository in filtered_repos %}
      {% unless site.projects.exclude.projects contains repository.name %}
        <div class="col-sm-4 col-md-12 col-lg-6 col-xl-3 mb-3">
          {% include repo-card.html %}
        </div>
      {% endunless %}
    {% endfor %}
  </div>
</div>
