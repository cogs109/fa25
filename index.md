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

{% assign instructors = site.staffers | where: 'role', 'Instructor' %} {% for staffer in instructors %} {{ staffer nobio='true'}} {% endfor %}

## Course Information

| **Instructor** | [Lucy Lai, Ph.D.](https://www.lucylai.com) ([lai@ucsd.edu](mailto:lai@ucsd.edu)) |
| **TA**         | [Jiesen Zhang](https://diling69.github.io/) ([jiz147@ucsd.edu](jiz147@ucsd.edu))   |
| **Lectures**   | MWF, 9-9:50am @ Center Hall 113|
| **Discussion**   | W, 2:00-2:50pm @ Warren Lecture Hall 2113 <br> F, 4:00-4:50pm @ Warren Lecture Hall 2207 <br> F, 5:00-5:50pm @ Warren Lecture Hall 2207
| **Office Hours** | TBD |

## Course Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
