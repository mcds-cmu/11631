---
layout: f23
title: Contact Us
nav_order: 10
---

# Contact Us

<!-- If you are an incoming student or a student interested in taking the course, please email us at [Who We Are]({{ site.baseurl }}{{ page.subpath }}{% link f23/home/index.md %}#who-we-are) -->

If you are an incoming student or a student interested in taking the course, please email us at

{% assign instructors = site.staffers | where: 'role', 'Instructor' | where: 'staff_for', 'f23' | sort:"list_order" %}
<div class="staffer-container">
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

If you are currently enrolled in the course, please contact us via Piazza with your questions, concerns or feedback.