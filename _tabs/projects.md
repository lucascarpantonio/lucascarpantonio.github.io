---
title: Projects
icon: fas fa-folder-open
order: 2
layout: page
---

Benvenuto nella sezione **Projects** 👋  
Qui raccolgo i miei progetti sviluppati in **Python** e **Data Science**, frutto di curiosità, studio e sperimentazione.  
Ogni progetto è pensato per esplorare nuovi strumenti, migliorare le competenze analitiche e condividere soluzioni pratiche a problemi reali.

---

## 🚀 Progetti principali

{% assign sorted_projects = site.projects | sort: "title" %}
{% for project in sorted_projects %}
  <div class="project-entry" style="margin-bottom: 1.5rem;">
    <h3>
      <a href="{{ project.url }}" target="_blank">
        {{ project.title }}
      </a>
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
    <a href="{{ project.url }}" class="btn btn-outline-primary" target="_blank">🔗 View on GitHub</a>
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
