---
marp: true
theme: default
# class: invert
author: Patrick Mathy
# size 16:9 1280px 720px
size: 16:9
paginate: true
math: mathjax
# backgroundImage: "linear-gradient(to bottom, #abbaab, #ffffff)"
# #ece9e6, #ffffff
# #8e9eab, #eef2f3
# #e6dada, #274046
# #abbaab, #ffffff
style: |
    :root {
      background: linear-gradient(to left, #abbaab, #ffffff);
    }
    img[alt~="custom"] {
      float: right;
    }
    .columns {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 1rem;
    }
    footer {
      font-size: 14px;
    }
    section::after {
      font-size: 14px;
    }
    img {
      background-color: transparent;
    }
    pre {
        background: linear-gradient(to top, #abbaab, #ffffff);
        background-color: transparent;
    }
---

# Network As Code Primer

<!-- Do not add page number on this slide -->
<!--
_paginate: false
-->

```text
Network As Code: eine kurze Einführung

Patrick Mathy
                                      Apr 2024
```

<style scoped>footer {font-size: 25px; color: darkblue; opacity: 0.6; text-shadow: 2px 2px rgba(0,0,0,.4);}</style>
<!-- Add footer starting from this slide -->
<!--
footer: 'DENOG Meetup 2024-04, Darmstadt'
-->

---

# $ whoami

<style scoped>section {font-size: 18px;}</style>

- Patrick Mathy
  
  - Systems Engineer bei Arista Networks
  - Herumnetzwerken seit 2016
  - ACE:L3; ACE:L5
  - Spaß mit Netzwerk und Automatisierung in Campus, DC und überall sonst
  - Ein bisschen Python, Ansible, Terraform, NetDevOps, etc.

![bg right w:200](img/bmage.jpg)

---

# Agenda

<style scoped>section {font-size: 22px;}</style>

![bg right ](img/agenda.jpg)

- Was ist Network as Code?
- Warum NaC?
- Automatisierung und Pipelines und Git, oh weh!
- Eine kleine Toolsammlung

---

# Q&A

- [in/patrick-mathy](https://www.linkedin.com/in/patrick-mathy/)