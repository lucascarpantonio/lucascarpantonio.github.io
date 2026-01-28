---
title: Projects
icon: fas fa-folder-open
order: 2
layout: page
---

# Portfolio

Welcome to my **Projects** space — a collection of Python and Data Science work that blends curiosity, learning, and real-world problem solving.

Each project represents a step forward in exploring new technologies, refining analytical thinking, and transforming data into actionable insights.  
From exploratory analyses to automation tools, these works showcase how data can tell stories, uncover patterns, and drive better decisions.

💡 Whether it’s visualizing urban trends, analyzing market behaviors, or building small-scale digital tools — every project is a reflection of experimentation and growth.


---

## Main Projects

{% assign sorted_projects = site.projects | sort: "title" %}
{% for project in sorted_projects %}
  {% assign href = project.external_url | default: project.url %}

  <div class="project-entry" style="margin-bottom: 1.5rem;">
    <h3>
      <a href="{{ href }}" target="_blank">{{ project.title }}</a>
    </h3>

    {% if project.description %}
      <p>{{ project.description }}</p>
    {% endif %}

    {% if project.tags %}
      <p>
        {% for tag in project.tags %}
          <span class="tag">{{ tag }}</span>
        {% endfor %}
      </p>
    {% endif %}

    {% if project.repo %}
      <a href="{{ project.repo }}" class="btn btn-outline-primary" target="_blank">🔗 View on GitHub</a>
    {% endif %}
    <hr>
  </div>
{% endfor %}

---

## Other Experiments

This section includes smaller side projects and notebooks focused on:

- Exploratory data analysis of public datasets (Kaggle, Open Data)
- Automation and QA monitoring scripts
- Small-scale *Machine Learning* and *Data Visualization* studies

**Tip:** Stay updated on new projects by following me on  
[GitHub](https://github.com/lucascarpantonio) or [LinkedIn](https://www.linkedin.com/in/lucascarpantonio/)
