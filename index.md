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
| **TA**         | [Jiesen Zhang](mailto:jiz147@ucsd.edu), OH: during discussion sections|
| **PLAs**       | [Parinita Saha](mailto:psaha@ucsd.edu) & [Johny Nguyen](mailto:jon009@ucsd.edu)|
| **Reader**     | [Zhicheng Wang](mailto:zhw049@ucsd.edu)  |
| **Lectures**   | MWF, 9-9:50am @ CENTR 113 |
| **Discussion**   |• W, 2-2:50pm @ WLH 2113 <br> • F, 4-4:50pm @ WLH 2207 <br> • F, 5-5:50pm @ WLH 2207 |
| **Prof. Lai's Office Hours** | W, 3-4:30pm ([book](https://calendar.app.google/1nebbtvdYdn6WFpw5)/walk-in) or Th, 4:30-5:30pm ([book](https://calendar.app.google/1nebbtvdYdn6WFpw5) only) @ CSB 244/Zoom) |

## Course Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
