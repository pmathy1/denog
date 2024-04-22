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

# Network as Code Primer

<!-- Do not add page number on this slide -->
<!--
_paginate: false
-->

```text
How to build out / test / deploy network configuration through a CI Pipeline / Test123

Patrick Mathy
                                      Apr 2024
```

<style scoped>footer {font-size: 25px; color: blue; opacity: 0.6; text-shadow: 2px 2px rgba(0,0,0,.4);}</style>
<!-- Add footer starting from this slide -->
<!--
footer: 'DENOG Meetup 2024-04, Darmstadt'
-->

---

# $ whoami

<style scoped>section {font-size: 18px;}</style>

- Patrick Mathy
  
  - Arista Systems Engineering at Arista Networks
  - Networking around since 2016
  - ACE: L5, CCIE 57751
  - Having fun with network and automation in campus, DC and everywhere else
  - Some Python, Ansible, Terraform, NetDevOps, etc

![bg right w:200](img/bmage.jpg)

---

# Agenda

<style scoped>section {font-size: 22px;}</style>

![bg right ](img/pexels-suzy-hazelwood-1226398.jpg)

- Ansible AVD collection overview
- Common challenges when building Ansible environment
- Why devcontainers?
- Pre-building a devcontainer with [arista.avd](https://avd.arista.com/), docker-in-docker and Containerlab using Github [devcontainers/ci@v0.3](https://github.com/devcontainers/ci) action.
- How to run the container on any machine (with docker run or as devcontainer) or Github Codespaces

---

# Q&A

- [forum.ansible.com](https://forum.ansible.com/)
- [in/patrick-mathy](https://www.linkedin.com/in/patrick-mathy/)