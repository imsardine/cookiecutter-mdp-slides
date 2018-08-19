%title: {{cookiecutter.topic}}
%author: {{cookiecutter.author_name}} ({{cookiecutter.author_email}})

# Agenda

 * Introduction
 * ...
 * Q&A

{% set number_of_slides = cookiecutter.number_of_slides | int -%}
{% for page in range(1, number_of_slides + 1) -%}
---

# Page {{page}}

{% endfor -%}

---

# Q&A

-> Thank you for listening

-> Happy Learning!
