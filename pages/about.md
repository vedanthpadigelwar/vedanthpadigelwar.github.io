---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

<!-- Hi I am **{{ site.author.name }}** :wave:,<br> -->

- As an international student at Aalto University in Finland, I understood the benefits and challenges of working within a culturally diverse project group.
-  Received Amrita Nidhi scholarship of 25% for bachelor’s.
- Eager to support in a development-friendly environment  and grow along with the organization through value-added contribution by building impeccable and customer valued products.
- Adaptable and transformational leader with an ability to demonstrate exceptional organisational skills and making critical decisions during challenging

{% include elements/button.html link="/documents/FormalResume/main.pdf" text="Download my Resume" style="outline-dark" size="lg" %}
<!-- {% include elements/button.html link="/documents/resume.pdf" text="Download my Fun Resume" style="primary" size="lg" %} -->

<div class="row">
{% include about/skills.html title="Skills" source=site.data.programming-skills %}
{% include about/skills.html title="hidden" source=site.data.other-skills %}
</div>

## Work Experience

<div class="row">
{% include about/workExperience.html %}
</div>

## Education

<div class="row">
{% include about/education.html %}
</div>
