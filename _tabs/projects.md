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

### 🏙 Venice Airbnb Analysis
**Analisi dei prezzi e dei fattori che influenzano gli affitti brevi a Venezia.**  
Un progetto di *data exploration* e *feature analysis* che utilizza `pandas`, `numpy`, `matplotlib` e `seaborn` per indagare pattern di prezzo, stagionalità e recensioni.

- 📂 [Repository su GitHub](https://github.com/scarpl/venice-airbnb)
- 📖 [Approfondimento nel blog](../posts/2025-10-18-welcome) _(se vuoi aggiungere un articolo correlato)_

---

### 🌱 Altri esperimenti
In questa sezione aggiungo periodicamente mini-progetti o notebook dedicati a:
- Analisi esplorative di dataset pubblici (Kaggle, Open Data)
- Script di automazione QA e monitoraggio
- Piccoli studi di *Machine Learning* e *Data Visualization*

---
layout: page
title: Projects
icon: fas fa-lightbulb
order: 3
---

<h2>Projects 🚀</h2>

{% for project in site.projects %}
  <div class="project-entry">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.description }}</p>
    <hr>
  </div>
{% endfor %}

📬 **Suggerimento:** se vuoi restare aggiornato sui prossimi progetti, seguimi su  
[GitHub](https://github.com/lucascarpantonio) 💻 o [LinkedIn](https://www.linkedin.com/in/lucascarpantonio/) 🌐


