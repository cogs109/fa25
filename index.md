---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: Modeling and Data Analysis
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %} {% for staffer in instructors %} {{ staffer}} {% endfor %}

## Important Course Info

|--|-----|
| **TA**         | [Jiesen Zhang](https://diling69.github.io/) ([jiz147@ucsd.edu](jiz147@ucsd.edu))   |
| **Reader**     | TBD  |
| **Lectures**   | MWF, 9-9:50am @ CENTR 113 |
| **Discussion**   |• W, 2-2:50pm @ WLH 2113 <br> • F, 4-4:50pm @ WLH 2207 <br> • F, 5-5:50pm @ WLH 2207 |
| **Prof. Lai's Office Hours** | W, 3-4:30pm ([book](https://calendar.app.google/1nebbtvdYdn6WFpw5)/walk-in) or Th, 4:30-5:30pm ([book](https://calendar.app.google/1nebbtvdYdn6WFpw5) only) @ CSB 244/Zoom) |
| **Jiesen's Office Hours** | During discussion section |

## Course Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
