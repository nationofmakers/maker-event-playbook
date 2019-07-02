---
title: Welcome to the Maker Event Playbook
keywords: homepage
tags: [getting_started]
sidebar: home_sidebar
permalink: index.html
summary: This guide will help you plan a maker event and to learn from the experience of other maker event producers.
---

## Maker Event Guides
Maker events come in all shapes & sizes - so we've separated this playbook into three guides by event size to help you learn from other events that are similar in scope and size to your planned event.

### Large Maker Events
The [large event guide](event_type_large.html) is for events with hundreds of makers / maker exhibits and thousands of attendees. Most commonly this is a multi-day Maker Faire or Maker Festival type of event.

###  Medium Maker Events
The [medium event guide](event_type_medium.html) is for events with dozens of makers / maker exhibits and hundreds of attendees
Most commonly this is a single-day Maker Faire or Maker Festival type of event.

### Small Maker Events
The [small event guide](event_type_small.html) is for events with a few makers and dozens of attendees. Most commonly this is a makerspace event. 




## Learn More & Get Involved
This playbook is a project created and maintained by the maker event producers that are part of the (Nation of Makers)[http://www.nationofmakers.us] community. We need your contributions to extend it to be a world-class resource for maker event producers!

### Contribute to the Maker Event Playbook
Want to contribute to the overall playbook? - [learn how to contribute](contributing.html)

### Create a Playbook for your Maker Event
You can easily create a playbook for your event - [learn how to create your own playbook](document_your_event.html)

### Why GitHub?
Wondering why this isn't a Wiki or a Google Doc? Someone should create a page to explain this!


## Maker Events

<div class="maker-events">
    <ul class="listing">
        {% assign events = site.events | sort: 'name' %}
        {% for event in events %}
        <li>
            <h2><a href="{{ event.url | prepend: site.baseurl }}">{{ event.name }}</a></h2>
            {{ event.content }}
        </li>
        {% endfor %}
    </ul>
</div>

Last change: {{ site.time }}


