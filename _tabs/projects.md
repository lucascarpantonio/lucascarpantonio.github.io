---
title: Projects
icon: fas fa-folder-open
order: 2
layout: page
---

# Projects Portfolio

Welcome to my **Projects** space — a collection of Python and Data Science work that blends curiosity, learning, and real-world problem solving.

Each project represents a step forward in exploring new technologies, refining analytical thinking, and transforming data into actionable insights.  
From exploratory analyses to automation tools, these works showcase how data can tell stories, uncover patterns, and drive better decisions.

💡 Whether it’s visualizing urban trends, analyzing market behaviors, or building small-scale digital tools — every project is a reflection of experimentation and growth.


---

## Progetti principali

{% assign sorted_projects = site.projects | sort: "title" %}
{% for project in sorted_projects %}
  <div class="project-entry" style="margin-bottom: 2.5rem;">
    <h3>
      <a href="{{ project.url }}" target="_blank">{{ project.title }}</a>
    </h3>

    {% if project.description %}
      <p>{{ project.description }}</p>
    {% endif %}

    {% if project.tags %}
      <p>
        {% for tag in project.tags %}
          <img src="https://img.shields.io/badge/{{ tag | replace: ' ', '%20' }}-{{ '555555' }}?style=flat-square&labelColor={{ '0d1117' }}&color={{ '2ea043' }}" 
               alt="{{ tag }}" 
               style="margin-right: 5px; border-radius: 4px;">
        {% endfor %}
      </p>
    {% endif %}

    <a href="{{ project.url }}" class="btn btn-outline-primary" target="_blank">
      🔗 View on GitHub
    </a>
    <hr>
  </div>
{% endfor %}

---

### 🌱 Altri esperimenti
In questa sezione aggiungo periodicamente mini-progetti o notebook dedicati a:
- Analisi esplorative di dataset pubblici (Kaggle, Open Data)
- Script di automazione QA e monitoraggio
- Piccoli studi di *Machine Learning* e *Data Visualization*

---

📬 **Suggerimento:** se vuoi restare aggiornato sui prossimi progetti, seguimi su  
[GitHub](https://github.com/lucascarpantonio) 💻 o [LinkedIn](https://www.linkedin.com/in/lucascarpantonio/) 🌐
