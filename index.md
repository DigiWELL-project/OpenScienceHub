---
layout: splash
title: "DigiWELL Open Science Hub"
permalink: /
intro:
  - excerpt: "A internal portal for DigiWELL researchers: publication workflow, data management, data sharing, commitments, and guidance for internal and external data access."
feature_row:
  - icon: "fa-solid fa-book"
    title: "Publication Workflow"
    url: "{{ '/publication-workflow/' | relative_url }}"
    excerpt: "Required steps before submission and after acceptance."

  - icon: "fa-solid fa-database"
    title: "Data Management & Sharing"
    url: "{{ '/data-management/' | relative_url }}"
    excerpt: "Internal storage, documentation, anonymisation, and Zenodo sharing."

  - icon: "fa-solid fa-share-nodes"
    title: "External Data Requests"
    url: "{{ '/external-data-requests/' | relative_url }}"
    excerpt: "Official process for handling external requests for DigiWELL datasets."

  - icon: "fa-solid fa-scale-balanced"
    title: "Open Science Commitments"
    url: "{{ '/commitments/' | relative_url }}"
    excerpt: "Open Science principles implemented across DigiWELL work packages."

  - icon: "fa-solid fa-circle-question"
    title: "FAQ"
    url: "{{ '/faq/' | relative_url }}"
    excerpt: "Most common questions and answers regarding DigiWELL Open Science."

---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
