---
layout: home
title: 🧑🏻‍🏫 Home
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
| **TA**         | [Lucy Lai, Ph.D.] [jiz147@ucsd.edu](jiz147@ucsd.edu)   |
| **Dates**      | Fall 2025 |
| **Lectures**   | MWF, 9-9:50am PT @ Center Hall 113|
| **Discussion**   | * W 2:00p-2:50p @ Warren Lecture Hall 2113 <br> * F 4:00p-4:50p @ Warren Lecture Hall 2207 <br> * F 5:00p-5:50p @ Warren Lecture Hall 2207
| **Office Hours** | Dr. Lai: Monday 10-11am & Wednesday 3-4pm |
| **Prerequisites**  | Statistics: [COGS 14B] and Linear algebra: [MATH 18 or 31AH] and Programming: [COGS18 or CSE 7 or CSE 8A or CSE 11]
| **Canvas**  | [canvas.ucsd.edu/courses/68350](https://canvas.ucsd.edu/courses/68350) |
| **Piazza**  | |
| **Discord**  | |

{: .important } Test

## Quick links 
* [Course Syllabus](https://docs.google.com/document/d/1SdpRRqtwHRpUCxthoSMRfS8kZEPTlqgsQaZ8pjTMwKE/edit?usp=sharing) 

## Course Schedule
{% for module in site.modules %}
{{ module }}
{% endfor %}
