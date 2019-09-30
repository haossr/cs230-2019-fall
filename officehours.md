---
layout: default
keywords:
comments: false

title: Office Hours
description: Times and locations may occasionally change each week; please check this page often.
buttons: [project_appt_calendly, queuestatus]
micro_nav: false
---

## Project Office Hours
You will need to make a 15-minute appointment with project TAs — click <https://calendly.com/cs230-2019-fall> to start.

## Other Office Hours
You will need to create an account on QueueStatus. When you wish to join the queue, click on the "Sign Up" button in the CS230 - Spring 2019 Queue page. Be sure to properly enter all information needed in the menu when you sign up. This will enable the TAs to properly contact you. Also check "Announcements" and "chat" boxes reguarly for messages from TAs.

## Zoom URLs for SCPD Office Hours
<table>
    <thead>
        <tr>
            <th>TA</th>
            <th>Zoom URL</th>
        </tr>
    </thead>
{% for ta in site.course.ta %}
    {% unless ta.zoom_id == null %}
    <tr><td>{{ ta.name }}</td><td><a href="https://stanford.zoom.us/j/{{ ta.zoom_id }}">{{ ta.zoom_id }}</a></td></tr>
    {% endunless %}
{% endfor %}
</table>

## Google Calendar
<div>
<iframe src="https://calendar.google.com/calendar/embed?height=600&amp;wkst=1&amp;bgcolor=%23ffffff&amp;ctz=America%2FLos_Angeles&amp;src=aHNoZW5nLm9yZ19wZHRwZm1hM3NuazRsZzFmZ3ZqajExaGY0NEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&amp;color=%23D50000&amp;title=CS230%202019%20Fall&amp;showCalendars=1&amp;mode=WEEK" width="100%" height="800" frameborder="0" scrolling="no"></iframe>
</div>
