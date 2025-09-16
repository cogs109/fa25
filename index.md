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

## Course Information

|-------------|--------|
| **Instructor** | [Lucy Lai, Ph.D.](https://www.lucylai.com) ([lai@ucsd.edu](mailto:lai@ucsd.edu)) |
| **TA**         | [Jiesen Zhang](https://diling69.github.io/) [jiz147@ucsd.edu](jiz147@ucsd.edu)   |
| **Lectures**   | MWF, 9-9:50am PT @ Center Hall 113|
| **Discussion**   | W 2:00p-2:50p @ Warren Lecture Hall 2113 <br> F 4:00p-4:50p @ Warren Lecture Hall 2207 <br> F 5:00p-5:50p @ Warren Lecture Hall 2207
| **Office Hours** | TBD |
| **Canvas**  | [canvas.ucsd.edu/courses/68350](https://canvas.ucsd.edu/courses/68350) |
| **Piazza**  | |
| **Discord**  | |

## Course Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
